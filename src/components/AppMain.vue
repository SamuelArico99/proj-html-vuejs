<script>
import WhatWeDo from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import Carousel from './Carousel.vue';
import OurPricing from './OurPricing.vue';
import LatestPosts from './LatestPosts.vue';
export default {
    name: ' AppMain',
    components: {
        WhatWeDo,
        GrowBusiness,
        Carousel,
        OurPricing,
        LatestPosts
    }
}
</script>

<template>
    <main>
        <WhatWeDo />
        <GrowBusiness />
        <Carousel />
        <OurPricing />
        <LatestPosts />
    </main>
</template>

<style lang="scss" scoped>

</style>