<template>
    <nav>
        <div class="nav-wrapper">
            <router-link to="/"><a class="brand-logo"><img :src="logo" :alt="alt"></a></router-link>
            <ul class="right">
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
                <li>
                    <router-link to="/about"><i class="material-icons">shopping_cart</i></router-link>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>

export default {
    name: "NavBar",
    props: ["logo", "alt"]
}

</script>

<style scoped>

</style>