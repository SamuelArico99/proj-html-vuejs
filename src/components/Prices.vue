

<script>

export default {
    name: ' AppFooter',
    components: {

    }
}
</script>

<template>
    <div class="col d-flex flex-column align-items-center justify-content-evenly">
        <h2>Designing</h2>
        <span>PROCESS</span>
        <h1>
            $
            <strong>40</strong>
        </h1>
        <p>Per Month</p>
        <ul>
            <li class="my-3">
                <strong>Creative</strong> Design Enabled
            </li>
            <li class="my-3">
                <strong>Vibrant</strong> Color Usage
            </li>
            <li class="my-3">
                <strong>Eye</strong> Catching Design
            </li>
            <li class="my-3">
                <strong>Extreme</strong> Typography
            </li>
            <li class="my-3">
                <strong>Exceptional</strong> Design
            </li>
        </ul>
        <button class="my-btn-secondary d-flex align-items-center justify-content-between">
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
        </button>
    </div>
    <div class="col mx-5 d-flex flex-column align-items-center justify-content-evenly">
        <h2>Developing</h2>
        <span>PRODUCT</span>
        <h1>
            $
            <strong>60</strong>
        </h1>
        <p>Per Month</p>
        <ul>
            <li class="my-3">
                <strong>Creative</strong> Design Enabled
            </li>
            <li class="my-3">
                <strong>Vibrant</strong> Color Usage
            </li>
            <li class="my-3">
                <strong>Eye</strong> Catching Design
            </li>
            <li class="my-3">
                <strong>Extreme</strong> Typography
            </li>
            <li class="my-3">
                <strong>Exceptional</strong> Design
            </li>
        </ul>
        <button class="my-btn-secondary d-flex align-items-center justify-content-between">
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
        </button>
    </div>
    <div class="col d-flex flex-column align-items-center justify-content-evenly">
        <h2>Supporting</h2>
        <span>CLIENTS</span>
        <h1>
            $
            <strong>80</strong>
        </h1>
        <p>Per Month</p>
        <ul>
            <li class="my-3">
                <strong>Creative</strong> Design Enabled
            </li>
            <li class="my-3">
                <strong>Vibrant</strong> Color Usage
            </li>
            <li class="my-3">
                <strong>Eye</strong> Catching Design
            </li>
            <li class="my-3">
                <strong>Extreme</strong> Typography
            </li>
            <li class="my-3">
                <strong>Exceptional</strong> Design
            </li>
        </ul>
        <button class="my-btn-secondary d-flex align-items-center justify-content-between">
            Order Now
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
        </button>
</div>
</template>

<style lang="scss" scoped>
.col {
    height: 700px;
    background-color: white;
    color: black;
    border: 0.5px solid lightgrey;
    border-radius: 20px;
    padding: 40px;

    &:hover {
        background: rgb(242, 92, 108);
        background: linear-gradient(266deg, rgba(242, 92, 108, 1) 21%, rgba(185, 39, 110, 1) 50%);
        color: white;
        border: none;
        cursor: pointer;

        .my-btn-secondary {
            color: $third-color;
            background: rgb(255, 255, 255);
        }
    }

}

li {
    list-style: none;
}

.my-btn-secondary {
    width: 170px;
    font-weight: bold;
}

h1 {
    strong {
        font-size: 100px;
    }
}
</style>