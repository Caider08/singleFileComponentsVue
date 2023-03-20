<template>
    <p class="username">{{username}}</p>
</template>

<script>
export default {
    props: {
        username: {
            type: String,
            required: true
        }
    }
}
</script>

<style lang="css" scoped>
    .username {
        color: #DCAE1D;

    }
</style>

