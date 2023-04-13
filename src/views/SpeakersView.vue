<template>
    <div>
        <NavContent title="SPEAKERS"></NavContent>
        <ProductLink
                name="ZX9 SPEAKER"
                description="Upgrade your sound system with the all new ZX9 active speaker. It’s a bookshelf speaker system that offers truly wireless connectivity -- creating new possibilities for more pleasing and practical audio setups."
                src="ZX9-speaker.jpg"
                alt="ZX9 Speaker">
        </ProductLink>

        <ProductLinkRight
                name="ZX7 SPEAKER"
                description="Stream high quality sound wirelessly with minimal loss. The ZX7 bookshelf speaker uses high-end audiophile components that represents the top of the line powered speakers for home or studio use."
                src="ZX7-speaker.jpg"
                alt="ZX7 Speaker">
        </ProductLinkRight>
        <CategoryCards></CategoryCards>
        <BestGearBanner></BestGearBanner>
    </div>
</template>

<script>
import NavContent from "@/components/navbar/NavContent.vue";
import ProductLinkRight from "@/components/card/ProductLinkRight.vue";
import ProductLink from "@/components/card/ProductLinkLeft.vue";
import BestGearBanner from "@/components/banner/BestGearBanner.vue";
import CategoryCards from "@/components/CategoryCards.vue";

export default {
    name: "SpeakersView",
    components: {CategoryCards, BestGearBanner, ProductLink, ProductLinkRight, NavContent}
}
</script>

<style scoped>

</style>