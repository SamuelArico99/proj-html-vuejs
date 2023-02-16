<script>
export default {
    name: ' Email',
    components: {

    }
}
</script>

<template>
    <section>
        <div class="my-container d-flex justify-content-between align-items-center">
            <div class="text">
                <h2>
                    We Offer Awesome Services
                </h2>
                <p>
                    When, while the lovely valley teems with vapour around meand the meridian sun strikes the
                    upper surface.
                </p>

            </div>
            <div class="search-container">
                <form action="">
                    <input type="text" placeholder="Enter Your Email Address">
                    <button class="my-btn-primary position-absolute top-50 translate-middle-y">Send</button>
                </form>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    width: 100%;
}

.my-container {
    background: rgb(242, 92, 108);
    background: linear-gradient(266deg, rgba(242, 92, 108, 1) 21%, rgba(185, 39, 110, 1) 50%);
    padding: 120px 60px;
    border-radius: 20px;

    .text {
        color: white;
    }
}

.search-container {
    width: 600px;
    height: 50px;
    border-radius: 30px;
    position: relative;

    input {
        width: 100%;
        height: 50px;
        border-radius: 30px;
        padding: 10px;
        border: none;
        outline: none;
    }

    .my-btn-primary {
        border-radius: 30px;
        width: 100px;
        height: 80%;
        right: 10px;
        padding: 5px;
    }
}
</style>