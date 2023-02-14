<script>
import WhatWeDo from './WhatWeDo.vue';
import GrowBusiness from './GrowBusiness.vue';
import Carousel from './Carousel.vue';
export default {
    name: ' AppMain',
    components: {
        WhatWeDo,
        GrowBusiness,
        Carousel,
    }
}
</script>

<template>
    <main>
        <WhatWeDo />
        <GrowBusiness />
        <Carousel />
    </main>
</template>

<style lang="scss" scoped>

</style>