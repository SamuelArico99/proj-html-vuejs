<script>
export default {
    name: ' GrowBusiness',
    components: {

    }
}
</script>

<template>
    <section>
        <div class="my-container">
            <div class="container">
                <div class="row gx-5">
                    <div class="col pe-5">
                        <img src="../assets/images/men-data.png" alt="">
                    </div>
                    <div class="col pt-5 px-5">
                        <span>Set Your Project</span>
                        <h1 class="mb-5"><strong>Grow Your Business</strong> <br> With Our Strategy</h1>
                        <p class="mb-5">
                            When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                            upper surface of the important follage of my tries, and but a few stray gleams steal into
                            the inner sanctuary
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
                </div>
            </div>

        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    background-color: $primary-color;
    padding: 170px 0;
}

span,
h1 {
    color: white;
}

p {
    color: $p-color;
}

.my-btn-secondary {
    margin: 0;
}

.my-btn-primary:hover {
    background: rgb(242, 92, 108);
    background: linear-gradient(266deg, rgba(242, 92, 108, 1) 21%, rgba(185, 39, 110, 1) 50%);
}

.my-btn-secondary:hover {
    background: rgb(28, 72, 138);
    background: linear-gradient(297deg, rgba(28, 72, 138, 1) 34%, rgba(9, 143, 192, 1) 100%);
}
</style>