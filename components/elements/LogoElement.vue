<template>
    <nuxt-link to="/about">
        <img src="@/static/icons/logo-green-black.svg" alt="logo" class="logo">
    </nuxt-link>
</template>
<script>
    export default {
        name: "LogoElement"
    }
</script>
<style scoped lang="scss">
    .logo {
        height: 80px; 
    }
</style>