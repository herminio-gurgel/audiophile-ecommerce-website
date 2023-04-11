<template>
    <div class="container">
        <div class="row">

            <router-link to="/headphones">
                <div class="col l4">
                    <Category src="/img/image-category-thumbnail-headphones.png" alt="HeadphonesALT"
                              title="Headphones">
                    </Category>
                </div>
            </router-link>

            <router-link to="/speakers">
                <div class="col l4">
                    <Category src="/img/image-category-thumbnail-speakers.png" alt="SpeakersALT"
                              title="Speakers">
                    </Category>
                </div>
            </router-link>

            <router-link to="/earphones">
                <div class="col l4">
                    <Category src="/img/image-category-thumbnail-earphones.png" alt="EarphonesALT"
                              title="Earphones">
                    </Category>
                </div>
            </router-link>
        </div>
    </div>
</template>

<script>
import Category from "@/components/card/Category.vue";

export default {
    name: "CategoryCards",
    components: {Category}
}
</script>

<style scoped>

</style>