<template>
    <div class="container row" id="zx9-banner">
        <div class="col l6" id="zx9-left">
            <img src="../../../public/img/image-speaker-zx9.png" alt="zx9" id="zx9-image">
        </div>
        <div class="col l6 white-text">
            <h1>ZX9 SPEAKERS</h1>
            <h6>Upgrade to premium speakers that are phenomenally built to deliver truly remarkable sound.</h6>
            <a class="waves-effect waves-light btn black">See product</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "VX9Banner"
}
</script>

<style scoped>

#zx9-banner {
    background-color: #D87D4A;
    height: 300px;
}

#zx9-left {
    background-image: url("../../../public/img/pattern-circles.svg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

#zx9-image {
    height: 250px;
}

</style>