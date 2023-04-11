<template>
    <div class="card grey lighten-3">
        <div class="card-image">
            <img :src="src" :alt="alt">
        </div>
        <div class="card-content">
            <span class="card-title black-text center">{{ title }}</span>
            <div class="action">
                <a class="grey-text" href="#">Shop</a>
                <a href=""><i class="material-icons orange-text">chevron_right</i></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "Category",
    props: ["src", "alt", "title"]
}
</script>

<style scoped>

.card {
    margin-top: 150px;
}

.action {
    display: flex;
    justify-content: center;
}

.card-image {
    height: 150px;
    display: flex;
    align-items: flex-end;
}
</style>