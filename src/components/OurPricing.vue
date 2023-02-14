<script>
import Prices from './Prices.vue';
export default {
    name: 'OurPricing ',
    components: {
        Prices
    }
}
</script>

<template>
    <section>
        <div class="my-container text-center">
            <p class="color mb-3">
                Price List
            </p>
            <h2>
                Our Pricing
            </h2>
            <p class="mb-5">
                When, while the lovely valley teems with vapour around meand the meridian sun strikes <br> the
                upper surface.
            </p>
            <div class="row ">
                <Prices />
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    background-color: $primary-color;
    height: 500px;
    margin-bottom: 600px;
    padding-top: 50px;

    .my-container {
        color: white;


    }
}

.color {
    color: $third-color;
}
</style>