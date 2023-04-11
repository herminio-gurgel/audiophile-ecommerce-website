<template>
    <ul id="nav-links">
        <li>
            <router-link to="/">HOME</router-link>
        </li>
        <li>
            <router-link to="/headphones">HEADPHONES</router-link>
        </li>
        <li>
            <router-link to="/speakers">SPEAKERS</router-link>
        </li>
        <li>
            <router-link to="/earphones">EARPHONES</router-link>
        </li>
    </ul>
</template>

<script>
export default {
    name: "NavLinks"
}
</script>

<style scoped>
#nav-links :hover {
    color: #D87D4A;
    transition: .5s;
}
</style>