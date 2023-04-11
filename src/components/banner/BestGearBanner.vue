<template>
    <div class="container row" id="banner">
        <div class="col l6 l">
            <h3>BRINGING YOU THE <span id="best">BEST</span> AUDIO GEAR</h3>
            <p>Located at the heart of New York City, Audiophile is the premier store for high end headphones,
                earphones, speakers, and audio accessories. We have a large showroom and luxury demonstration rooms
                available for you to browse and experience a wide range of our products. Stop by our store to meet some
                of the fantastic people who make Audiophile the best place to buy your portable audio equipment.</p>
        </div>
        <div class="col l6 r">
        </div>
    </div>
</template>

<script>
export default {
    name: "BestGearBanner"
}
</script>

<style scoped>

#best {
    color: #D87D4A;
}

#banner{
    display: flex;
}

.l{
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.r {
    background-image: url("../../../public/img/image-best-gear.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    height: 588px;
}
</style>