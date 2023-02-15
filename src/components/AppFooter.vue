<script>
import Email from './Email.vue';
import Social from './Social.vue';
export default {
    name: ' AppFooter',
    components: {
        Email,
        Social
    }
}
</script>

<template>
    <footer class="position-relative">
        <Email class="position-absolute top-0 start-50 translate-middle" />
        <div class="my-container">
            <div class="row">
                <div class="col">
                    <img class="mb-5" src="../assets/images/white-logo-2.png" alt="">
                    <p>
                        When, while the lovely valley teems with vapour around meand the meridian sun strikes the <br>
                        upper impenetrable
                    </p>
                </div>
                <div class="col">
                    <h3 class="mb-3">
                        Quick Links
                    </h3>
                    <ul>
                        <li class="mb-2">
                            <a href="">Services</a>
                        </li>
                        <li class="mb-2">
                            <a href="">Contact</a>
                        </li>
                        <li class="mb-2">
                            <a href="">Blog</a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <h3 class="mb-4">
                        Resources
                    </h3>
                    <ul>
                        <li class="mb-2 text-center">
                            <a href="">Art Design</a>
                        </li>
                        <li class="mb-2 text-center">
                            <a href="">Computer</a>
                        </li>
                        <li class="mb-2 text-center">
                            <a href="">IT News</a>
                        </li>
                        <li class="mb-2 text-center">
                            <a href="">Networking</a>
                        </li>
                        <li class="mb-2 text-center">
                            <a href="">Web Security</a>
                        </li>
                    </ul>
                </div>
                <div class="col">
                    <h3 class="mb-4">
                        Contact Us
                    </h3>
                    <ul>
                        <li class="mb-2">
                            <a href=""><strong>Address: </strong>Patricia C.Amedee 4401 Waldeck <br> Street Grapevine,
                                Tx 76051</a>
                        </li>
                        <li class="mb-2">
                            <a href=""><strong>Phone: </strong>+99 (0) 101 0000 888</a>
                        </li>
                        <li class="mb-2">
                            <a href=""><strong>Email: </strong> info@yourdomain.com</a>
                        </li>
                    </ul>
                </div>
            </div>

        </div>
        <Social />

    </footer>
</template>

<style lang="scss" scoped>
footer {
    background-color: $primary-color;
    margin-top: 200px;
    padding-top: 300px;
}

.col {
    padding: 50px;

    ul {
        padding: 0;
    }

    li {
        list-style: none;
        text-align: start;
    }

    h3 {
        color: white;
    }

    p,
    a {
        color: rgba(119, 127, 152, 255);
        text-decoration: none;
    }
}

strong {
    color: white;
}
</style>