<script>
import WhatWeDo from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import Carousel from './Carousel.vue';
import OurPricing from './OurPricing.vue';
import LatestPosts from './LatestPosts.vue';
import WhatPeopleSay from './WhatPeopleSay.vue'

export default {
    name: ' AppMain',
    components: {
        WhatWeDo,
        GrowBusiness,
        Carousel,
        OurPricing,
        LatestPosts,
        WhatPeopleSay,

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
        <WhatPeopleSay />

    </main>
</template>

<style lang="scss" scoped>

</style>