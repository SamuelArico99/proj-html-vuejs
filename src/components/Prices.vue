

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
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z" />
            </svg>
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
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z" />
            </svg>
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
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-arrow-right"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M1 8a.5.5 0 0 1 .5-.5h11.793l-3.147-3.146a.5.5 0 0 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L13.293 8.5H1.5A.5.5 0 0 1 1 8z" />
            </svg>
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
        background-color: $third-color;
        color: white;
        border: none;

        .my-btn-secondary {
            background-color: white;
            color: $third-color;
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