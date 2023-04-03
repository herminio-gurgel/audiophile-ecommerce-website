<template>
    <NavBar :logo="logo_src" :alt="app_name"></NavBar>
    <router-view/>
</template>

<script>
import NavBar from "@/components/NavBar.vue";

export default {
    components: {
        NavBar
    },
    data() {
        return {
            logo_src: '/img/logo.svg',
            app_name: 'audiophile'
        }
    }
}
</script>

<style>
</style>