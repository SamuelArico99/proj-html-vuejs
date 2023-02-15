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
            <div class="input-type">
                <input type="text" placeholder="Enter Your Email Address">
                <div class="part-input">
                    <button type="button" id="button-addon2">Subscribe</button>
                </div>


            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section {
    width: 80%;
}

.my-container {
    background-color: $third-color;
    padding: 80px;
    border-radius: 20px;

    .text {
        color: white;
    }
}

.input-type {
    width: 50%;
    display: flex;
    justify-content: end;

    input {
        width: 50%;
        height: 50px;
        padding: 20px;
        border: transparent;
        border-top-left-radius: 30px;
        border-bottom-left-radius: 30px;
    }

    .part-input {
        background-color: white;
        display: flex;
        align-items: center;
        width: 150px;
        padding: 5px;
        border-top-right-radius: 30px;
        border-bottom-right-radius: 30px;
        border-left: transparent;

        button {
            width: 100%;
            height: 100%;
            border-radius: 30px;
            border: none;
            background-color: $btn-blue-color;
            color: white;
        }
    }
}
</style>