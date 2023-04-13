<template>
    <div class="black white-text center-align" id="nav-title-back"><h2 id="nav-title">{{ title }}</h2></div>
</template>

<script>
export default {
    name: "NavContent",
    props: ["title"]
}
</script>

<style scoped>
#nav-title-back {
    background-color: #000000;
}

#nav-title {
    margin: 0;
}
</style>