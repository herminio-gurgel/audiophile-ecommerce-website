<template>
    <HeroBanner></HeroBanner>
    <div class="section">
        <CategoryCards></CategoryCards>
    </div>
    <div class="section">
        <VX9Banner></VX9Banner>
        <ZX7Banner></ZX7Banner>
        <YX1Banner></YX1Banner>
    </div>
    <div class="section">
        <BestGearBanner></BestGearBanner>
    </div>
</template>

<script>
import {defineComponent} from "vue";
import CategoryCards from "@/components/CategoryCards.vue";
import HeroBanner from "@/components/banner/HeroBanner.vue";
import VX9Banner from "@/components/banner/VX9Banner.vue";
import ZX7Banner from "@/components/banner/ZX7Banner.vue";
import YX1Banner from "@/components/banner/YX1Banner.vue";
import BestGearBanner from "@/components/banner/BestGearBanner.vue";

export default defineComponent({
    components: {BestGearBanner, YX1Banner, ZX7Banner, VX9Banner, HeroBanner, CategoryCards}
})
</script>

<style scoped>

</style>