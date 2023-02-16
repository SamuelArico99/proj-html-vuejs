<script>
export default {
    name: ' Jumbotrone',
    components: {

    }
}
</script>

<template>
    <div class="jumbotrone">
        <div class="my-container">
            <div class="row">
                <div class="col d-flex flex-column justify-content-center">
                    <h1>
                        Business Planning
                    </h1>
                    <span class="fs-1 text">Digital Technology</span>
                    <h1 class="mb-5">
                        Modern Solution
                    </h1>
                    <p class="mb-5">
                        When, while the lovely valley teems with vapour around <br> meand the meridian sun strikes the
                        upper
                        surface
                    </p>

                    <div class="d-flex">
                        <button class="my-btn-secondary">
                            Try it Now
                        </button>
                        <button class="my-btn-primary">
                            Explore More
                        </button>
                    </div>
                </div>
                <div class="col">
                    <img src="../assets/images/header.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.jumbotrone {
    background: rgb(2, 2, 49);
    background: linear-gradient(0deg, rgba(2, 2, 49, 1) 13%, rgba(10, 23, 79, 1) 50%);

    .col {
        color: white;

        .my-btn-primary:hover {
            background: rgb(242, 92, 108);
            background: linear-gradient(266deg, rgba(242, 92, 108, 1) 21%, rgba(185, 39, 110, 1) 50%);
        }

        .my-btn-secondary:hover {
            background: rgb(28, 72, 138);
            background: linear-gradient(297deg, rgba(28, 72, 138, 1) 34%, rgba(9, 143, 192, 1) 100%);
        }
    }
}

p {
    color: $p-color;
}

.row {
    padding-bottom: 200px;
}
</style>