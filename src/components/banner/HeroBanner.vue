<template>
    <div class="background">
        <div class="container row" id="hero-banner">
            <div class="col l6 white-text center-align" id="hero-banner-link">
                <h5>New Product</h5>
                <h1>XX99 Mark II Headphones</h1>
                <h6>Experience natural, lifelike audio and exceptional build quality made for the passionate music
                    enthusiast.</h6>
                <a class="waves-effect waves-light btn orange darken-4">See product</a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "HeroBanner"
}
</script>

<style scoped>
.background {
    background-color: #191919;
}

#hero-banner {
    background-image: url("../../../public/img/image-hero.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 550px;
}

#hero-banner-link {
    margin-top: 120px;
}
</style>