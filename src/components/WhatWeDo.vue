<script>
export default {
    name: ' WhatWeDo',
    components: {

    }
}
</script>

<template>
    <section>
        <div class="my-container">
            <div class="title">
                <span class="my-color">Our Services</span><br>
                <span class="fs-1"><strong>What</strong> We Do</span>
                <p>When, while the lovely valley teems with vapour around meand the</p>
            </div>
            <div class="container">
                <div class="row gx-5">
                    <div class="col">
                        <img class="mb-5" src="../assets/images/Group-247.png" alt="">
                        <h4>Data Analysis</h4>
                        <p class="my-margin">
                            When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                            upper
                        </p>
                    </div>
                    <div class="col">
                        <img class="mb-5" src="../assets/images/Group-567.png" alt="">
                        <h4>SEO Optimization</h4>
                        <p>
                            When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                            upper
                        </p>
                    </div>
                    <div class="col">
                        <img class="mb-5" src="../assets/images/Group-538.png" alt="">
                        <h4>Security Data</h4>
                        <p>
                            When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                            upper
                        </p>
                    </div>
                    <div class="col">
                        <img class="mb-5" src="../assets/images/Group-566.png" alt="">
                        <h4>Branding Strategy</h4>
                        <p>
                            When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                            upper
                        </p>
                    </div>
                </div>

                <button class="my-btn-secondary">View All Services</button>

            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    padding: 100px;
}

.my-color {
    color: $third-color;
}

.my-container {
    text-align: center;
}

.title {
    margin-bottom: 150px;
}

.row {
    margin-bottom: 200px;
}
</style>