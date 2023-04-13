<template>
    <div>
        <NavContent title="EARPHONES"></NavContent>
        <ProductLink
                name="XY1 EARPHONES"
                description="Tailor your listening experience with bespoke dynamic drivers from the new YX1 Wireless Earphones. Enjoy incredible high-fidelity sound even in noisy environments with its active noise cancellation feature."
                src="YX1-earphones.jpg"
                alt="YX1 earphones">
        </ProductLink>
        <CategoryCards></CategoryCards>
        <BestGearBanner></BestGearBanner>
    </div>
</template>

<script>
import NavContent from "@/components/navbar/NavContent.vue";
import ProductLink from "@/components/card/ProductLinkLeft.vue";
import BestGearBanner from "@/components/banner/BestGearBanner.vue";
import CategoryCards from "@/components/CategoryCards.vue";
import ProductLinkRight from "@/components/card/ProductLinkRight.vue";

export default {
    name: "EarphonesView",
    components: {ProductLinkRight, CategoryCards, BestGearBanner, ProductLink, NavContent}
}
</script>

<style scoped>

</style>