<script>
export default {
    name: 'Social',
    components: {

    }
}
</script>

<template>
    <div class="my">
        <div class="my-container d-flex justify-content-between">
            <div class="d-flex align-items-center">
                <p>
                    &#169; 2020 Phlox. All Rights Reserved.
                </p>
            </div>
            <div class="d-flex align-items-center">
                <font-awesome-icon class="color fs-5" icon="fa-brands fa-instagram" />
                <font-awesome-icon class="color mx-3 fs-5" icon="fa-brands fa-linkedin-in" />
                <font-awesome-icon class="color me-3 fs-5" icon="fa-brands fa-facebook-f" />
                <font-awesome-icon class="color fs-5" icon="fa-brands fa-twitter" />
                <div class="circle-container mx-2">
                    <div class="circle">
                        <font-awesome-icon icon="fa-solid fa-arrow-up" />
                    </div>
                </div>
                <font-awesome-icon class="comment color fs-4 p-3" icon="fa-regular fa-comment" />
            </div>
        </div>

    </div>
</template>

<style lang="scss" scoped>
.my {
    border-top: 1px solid rgba(119, 127, 152, 255);
    height: 100px;
    display: flex;
    align-items: center;
}

.circle-container {
    height: 99px;

    .circle {
        padding: 5px 10px;
        background-color: white;
        border-radius: 50%;
    }
}

.color {
    color: white;
}

p {
    margin: 0;
    color: rgba(119, 127, 152, 255);
}

.comment {
    background-color: #527ceb;
    border-radius: 50%;
}
</style>