<template>
    <div class="container row" id="xy1">
        <div class="col l6" id="xy1-banner">
        </div>
        <div class="col l6 black-text" id="xy1-left">
            <h4>XY1 EARPHONES</h4>
            <a class="waves-effect waves-light btn transparent black-text">See product</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "YX1Banner"
}
</script>

<style scoped>

#xy1{
    display: flex;
    align-items: stretch;
}

#xy1-left{
    background-color: #F1F1F1;
    flex-direction: column;
    display: flex;
    align-items: center;
    justify-content: center;
}

#xy1-banner {
    background-image: url("../../../public/img/image-earphones-yx1.jpg");
    background-repeat: no-repeat;
    background-size: contain;
    height: 276px;
}
</style>