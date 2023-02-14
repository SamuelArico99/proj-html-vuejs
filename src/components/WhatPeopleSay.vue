<script>
export default {
    name: ' WhatPeopleSay',
    components: {

    }
}
</script>

<template>
    <section>
        <div class="my-container">
            <span class="color">Testimonial</span>
            <h2><strong>What</strong> People Say</h2>
            <p>
                When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                upper surface .
            </p>
            <div class="row">
                <div class="col">
                    <img src="../assets/images/szabo-viktor-1266895-unsplash-1024x1024.png" alt=""> <br>
                    <span>
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-solid fa-star" />
                        <font-awesome-icon icon="fa-regular fa-star" />
                        <font-awesome-icon icon="fa-regular fa-star" />
                    </span>
                </div>
                <div class="col">col</div>
                <div class="col">col</div>
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

    p {
        margin-bottom: 100px;
    }
}

.col {
    img {
        width: 50px;
    }
}

.color {
    color: $third-color;
}
</style>