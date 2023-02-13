<script>
import Jumbotrone from './Jumbotrone.vue'
export default {
    name: ' AppHeader',
    components: {
        Jumbotrone

    }
}
</script>

<template>
    <header>
        <nav class="my-container d-flex justify-content-between">
            <div>
                <img src="../assets/images/white-logo-2.png" alt="">
            </div>
            <div class="d-flex align-items-center">
                <ul class="d-flex">
                    <li>
                        <a href="">
                            Home
                        </a>
                    </li>
                    <li>
                        <a href="">
                            About
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Services
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Blog
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Contact
                        </a>
                    </li>
                    <li>
                        <a href="">
                            Portfolio
                        </a>
                    </li>

                </ul>
                <button class="my-btn-primary">
                    Sign in
                </button>

            </div>
        </nav>
    </header>
    <Jumbotrone />
</template>

<style lang="scss" scoped>
header {
    background-color: $primary-color;
    padding: 20px;
    border: none;
}

li {
    margin: 0 10px;
    list-style: none;

    a {
        text-decoration: none;
        color: white;

        &:hover {
            color: $third-color;
        }
    }


}

ul {
    margin: 0;
}

button {
    margin-left: 20px;
}
</style>