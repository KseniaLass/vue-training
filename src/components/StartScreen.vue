<template>
    <div class="alert alert-secondary">
        <h3>Are you ready?</h3>
        <button class="btn btn-success" @click="$emit('onStart')">Yes!</button>
    </div>
</template>

<script>
    export default {
        methods: {
        	some() {
        		alert(1)
            }
        }
    }
</script>

<style scoped>
    .alert {
        text-align: center;
    }
    h3, .btn {
        margin: 20px 0;
    }
</style>