<template>
    <div class="container row" id="zx7-banner">
        <div class="col l6 black-text" id="zx7-left">
            <h4>ZX7 SPEAKERS</h4>
                <a class="waves-effect waves-light btn transparent black-text">See product</a>
        </div>
        <div class="col l6">
        </div>
    </div>
</template>

<script>
export default {
    name: "ZX7Banner"
}
</script>

<style scoped>

#zx7-banner {
    background-image: url("../../../public/img/image-speaker-zx7.jpg");
    background-size: contain;
    background-repeat: no-repeat;
    height: 276px;
    display: flex;
}

#zx7-left {
    display: flex;
    flex-direction: column;
    align-content: center;
    align-items: center;
    margin: auto;
}
</style>