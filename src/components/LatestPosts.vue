<script>
export default {
    name: ' LatestPosts',
    components: {

    }
}
</script>

<template>
    <section>
        <div class="my-container">
            <p class="color">Blog</p>
            <h2><strong>Latest </strong>Posts</h2>
            <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes <br> the
                upper surface .
            </p>
            <div class="row">
                <div class="col-6">
                    <div class=" my-card background-img px-5 py-5 d-flex justify-content-between align-items-end">
                        <div>
                            <p class="mb-3">
                                April 21,2019 by Paul
                            </p>
                            <h4 class="mb-3">
                                Amazon gets CCI nod to acquire 49% stake in
                            </h4>
                            <p>
                                When, while the lovely valley teems with vapour around meand the meridian sun s...
                            </p>
                        </div>
                        <button class="my-btn-primary">
                            Read More
                        </button>
                    </div>
                </div>
                <div class="col-3 ps-3">
                    <div class=" my-card px-5 py-5 background-color d-flex flex-column justify-content-between  ">
                        <div>
                            <p class="mb-3">
                                April 21,2019 by Paul
                            </p>
                            <h4 class="mb-3">
                                Clearing Corporation get SEBI nod to invest in overnight funds
                            </h4>
                            <p>
                                When, while the lovely valley teems with vapour around meand the meridian sun s...
                            </p>
                        </div>
                        <button class="my-btn-primary">
                            Read More
                        </button>
                    </div>
                </div>
                <div class="col-3 ps-3">
                    <div class=" my-card px-5 py-5 background-color d-flex flex-column justify-content-between">
                        <div>
                            <p class="mb-3">
                                April 21,2019 by Paul
                            </p>
                            <h4 class="mb-3">
                                Shabnam Dhillion, wife of RSSB chief Gurinder Dhillon, passes away in London
                            </h4>
                            <p>
                                When, while the lovely valley teems with vapour around meand the meridian sun s...
                            </p>
                        </div>
                        <button class="my-btn-primary">
                            Read More
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.my-container {
    text-align: center;
}

.col-6,
.col-3 {
    height: 500px;
    text-align: left;
    color: white;
    padding: 0px;

}

.background-img {
    background-image: url(../assets/images/headway-537308-unsplash-1380x703.jpg);
}

.background-color {
    background-color: $primary-color;
}

.my-card {
    height: 100%;
    border-radius: 20px;

}

.my-btn-primary {
    background-color: white;
    color: black;
    margin: 0;
    width: 150px;
}

p {
    margin-bottom: 0;
}

.row {
    margin-top: 100px;
}

.color {
    color: $third-color;
}
</style>