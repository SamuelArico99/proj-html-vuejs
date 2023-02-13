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
                    <h1>
                        Modern Solution
                    </h1>
                    <p>
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
    background-color: $primary-color;

    .col {
        color: white;

        .my-btn-primary:hover {
            background-color: $third-color;
        }

        .my-btn-secondary:hover {
            background-color: $btn-blue-color;
        }
    }
}

.row {
    padding-bottom: 200px;
}
</style>