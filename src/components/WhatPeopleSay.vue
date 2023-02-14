<script>
import People from './People.vue';
export default {
    name: ' WhatPeopleSay',
    components: {
        People
    }
}
</script>

<template>
    <section>
        <div class="my-container">
            <span class="color">Testimonial</span>
            <h2><strong>What</strong> People Say</h2>
            <p>
                When, while the lovely valley teems with vapour around meand the meridian sun strikes <br> the
                upper surface .
            </p>
            <div class="row">
                <People />
            </div>
            <div class="row">
                <div class="col">
                    <img src="../assets/images/client-1-1.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/images/clienty-2.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/images/clienty-3.png" alt="">
                </div>

                <div class="col">
                    <img src="../assets/images/clienty-4.png" alt="">
                </div>
                <div class="col">
                    <img src="../assets/images/client-5.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    padding: 200px;
}

.my-container {
    text-align: center;

}

.row {
    margin-top: 200px;
}

.color {
    color: $third-color;
}
</style>