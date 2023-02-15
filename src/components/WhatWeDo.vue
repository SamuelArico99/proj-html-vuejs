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
                        <div class="my position-relative">
                            <img class="position-absolute top-0 start-50 translate-middle"
                                src="../assets/images/Group-247.png" alt="">
                            <div class="text position-absolute top-50 start-50 translate-middle">
                                <h4>Data Analysis</h4>
                                <p class="my-margin">
                                    When, while the lovely valley teems with vapour around meand the meridian sun
                                    strikes
                                    the
                                    upper
                                </p>
                            </div>
                            <button class="position-absolute top-100 start-50 translate-middle my-btn-secondary">
                                <font-awesome-icon icon="fa-solid fa-arrow-right" />
                            </button>
                        </div>
                    </div>
                    <div class="col pe-5">
                        <div class="my position-relative">
                            <img class="position-absolute top-0 start-50 translate-middle"
                                src="../assets/images/Group-247.png" alt="">
                            <div class="text position-absolute top-50 start-50 translate-middle">
                                <h4>Data Analysis</h4>
                                <p class="my-margin">
                                    When, while the lovely valley teems with vapour around meand the meridian sun
                                    strikes
                                    the
                                    upper
                                </p>
                            </div>
                            <button class="position-absolute top-100 start-50 translate-middle my-btn-secondary">
                                <font-awesome-icon icon="fa-solid fa-arrow-right" />
                            </button>
                        </div>
                    </div>
                    <div class="col ps-5">
                        <div class="my position-relative">
                            <img class="position-absolute top-0 start-50 translate-middle"
                                src="../assets/images/Group-247.png" alt="">
                            <div class="text position-absolute top-50 start-50 translate-middle">
                                <h4>Data Analysis</h4>
                                <p class="my-margin">
                                    When, while the lovely valley teems with vapour around meand the meridian sun
                                    strikes
                                    the
                                    upper
                                </p>
                            </div>
                            <button class="position-absolute top-100 start-50 translate-middle my-btn-secondary">
                                <font-awesome-icon icon="fa-solid fa-arrow-right" />
                            </button>
                        </div>
                    </div>
                    <div class="col">
                        <div class="my position-relative">
                            <img class="position-absolute top-0 start-50 translate-middle"
                                src="../assets/images/Group-247.png" alt="">
                            <div class="text position-absolute top-50 start-50 translate-middle">
                                <h4>Data Analysis</h4>
                                <p class="my-margin">
                                    When, while the lovely valley teems with vapour around meand the meridian sun
                                    strikes
                                    the
                                    upper
                                </p>
                            </div>
                            <button class="position-absolute top-100 start-50 translate-middle my-btn-secondary">
                                <font-awesome-icon icon="fa-solid fa-arrow-right" />
                            </button>
                        </div>
                    </div>
                </div>

                <button class=" my-btn-secondary">
                    View All
                    Services
                </button>

            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    padding: 100px;
}

.col {
    height: 300px;
}

.my {
    height: 100%;
    border-radius: 30px;

    &:hover {
        background-color: $primary-color;
        color: white;

        .my-btn-secondary {
            display: block;
        }
    }

    .my-btn-secondary {
        border-radius: 50%;
        padding: 10px 15px;
        margin: 0;
        display: none;
    }

    .text {
        margin-top: 50px;
        width: 100%;
    }
}

.my-color {
    color: $third-color;
}

img {
    height: 150px;
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