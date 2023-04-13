<template>
    <nav class="nav-backgroud">
        <div class="nav-wrapper container">
            <div class="row">
                <div class="col l3">
                    <a class="brand-logo">
                        <BrandLogo></BrandLogo>
                    </a>
                </div>
                <div class="col l8">
                    <NavLinks class="left hide-on-med-and-down "></NavLinks>
                </div>
                <div class="col l1">
                    <IconMenu></IconMenu>
                </div>
            </div>
        </div>
    </nav>
</template>

<script>

import BrandLogo from "@/components/navbar/BrandLogo.vue";
import NavLinks from "@/components/navbar/NavLinks.vue";
import IconMenu from "@/components/navbar/IconMenu.vue";

export default {
    name: "NavBar",
    components: {IconMenu, NavLinks, BrandLogo}
}

</script>

<style scoped>
.nav-backgroud{
    background-color: #000000;
}

.nav-backgroud :hover{
    background-color: transparent;
}
</style>