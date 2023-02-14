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
            <p>Blog</p>
            <h2><strong>Latest </strong>Posts</h2>
            <p>When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                upper surface .
            </p>
            <div class="row">
                <div class="col-6">
                    <div class=" my-card d-flex justify-content-between align-items-end">
                        <div>
                            <p>
                                April 21,2019 by Paul
                            </p>
                            <h4>
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
                    <div class=" my-card d-flex justify-content-between align-items-end">
                        <div>
                            <p>
                                April 21,2019 by Paul
                            </p>
                            <h4>
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
                    <div class=" my-card d-flex justify-content-between align-items-end">
                        <div>
                            <p>
                                April 21,2019 by Paul
                            </p>
                            <h4>
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
    height: 600px;
    background-color: red;
    border: 1px solid black;
    text-align: left;
    color: white;
    padding: 0px;

}

.my-card {
    height: 100%;
    padding: 10px;
    background-image: url(../assets/images/headway-537308-unsplash-1380x703.jpg);

}

.my-btn-primary {
    background-color: white;
    color: black;
}

p {
    margin-bottom: 0;
}
</style>