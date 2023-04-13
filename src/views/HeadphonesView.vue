<template>
    <NavContent title="HEADPHONES"></NavContent>
    <ProductLink
            name="XX99 Mark II Headphones"
            description="The new XX99 Mark II headphones is the pinnacle of pristine audio. It redefines your premium headphone experience by reproducing the balanced depth and precision of studio-quality sound."
            src="XX99-Mark-II-Headphones.jpg"
            alt="XX99 Mark II Headphones">
    </ProductLink>

    <ProductLinkRight
            name="XX99 Mark I Headphones"
            description="As the gold standard for headphones, the classic XX99 Mark I offers detailed and accurate audio reproduction for audiophiles, mixing engineers, and music aficionados alike in studios and on the go."
            src="XX99-Mark-I-Headphones.jpg"
            alt="XX99 Mark I Headphones">
    </ProductLinkRight>

    <ProductLink
            name="XX59 Headphones"
            description="Enjoy your audio almost anywhere and customize it to your specific tastes with the XX59 headphones. The stylish yet durable versatile wireless headset is a brilliant companion at home or on the move."
            src="XX59-headphones.jpg"
            alt="XX59 Headphones">
    </ProductLink>
    <CategoryCards></CategoryCards>
    <BestGearBanner></BestGearBanner>
</template>

<script>
import NavContent from "@/components/navbar/NavContent.vue";
import ProductLink from "@/components/card/ProductLinkLeft.vue";
import ProductLinkRight from "@/components/card/ProductLinkRight.vue";
import CategoryCards from "@/components/CategoryCards.vue";
import BestGearBanner from "@/components/banner/BestGearBanner.vue";

export default {
    name: "HeadphonesView",
    components: {BestGearBanner, CategoryCards, ProductLinkRight, ProductLink, NavContent}
}
</script>

<style scoped>

</style>