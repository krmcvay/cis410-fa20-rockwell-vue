<template>
    <div>
        <h1>Login</h1>
        <div v-if="this.$route.query.loginsuccess" class="alert alert-success">
            Thanks for signing up. Please log in now. 
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>