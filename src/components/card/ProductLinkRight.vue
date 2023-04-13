<template>
    <div class="section container row">
        <div class="l col l6">
            <h2>{{ name }}</h2>
            <h6>{{ description }}</h6>
            <a class="waves-effect waves-light btn orange darken-4">See product</a>
        </div>
        <div class="r col l6">

            <img :src="require(`../../assets/${src}`)" :alt="alt" class="responsive-img">
        </div>
    </div>
</template>

<script>
export default {
    name: "ProductLinkRight",
    props: ["name", "description", "src", "alt"]
}
</script>

<style scoped>

.r {
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    height: 560px;
}

.l {
    height: 560px;
    padding-top: 65px;
    padding-left: 75px;
}

</style>