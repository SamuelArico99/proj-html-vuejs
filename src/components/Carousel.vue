<script>




export default {
    data() {
        return {
            cards: [
                {
                    img: '/DRY-1-790x576.jpg',
                    title: 'Purinky Products',
                    description: 'Digital Experience'
                },
                {
                    img: '/8wa60okr-1-790x576.jpg',
                    title: 'Basket of Flower on Table',
                    description: 'Branding Strategy'
                },
                {
                    img: '/84316050-0af0-49db-a53a-241d47ddad0e-2-790x576.jpg',
                    title: 'Mock-up',
                    description: 'Digital Experience'

                },
                {
                    img: '/a247b00b-3621-470f-b4b8-b3ac46f25907-1-790x576.jpg',
                    title: 'Satisfy Poster',
                    description: 'Branding Strategy'
                },
                {
                    img: '/studio-republic-644339-unsplash-1380x703.jpg',
                    title: 'Basket of Flower on Table',
                    description: 'Branding Strategy'
                },
                {
                    img: '/timon-studler-63413-unsplash-1380x703.jpg',
                    title: 'Basket of Flower on Table',
                    description: 'Branding Strategy'
                }
            ],
            innerStyles: {},
            step: '',
            transitioning: false
        }
    },
    mounted() {
        this.setStep()
        this.resetTranslate()
    },
    methods: {
        setStep() {
            const innerWidth = this.$refs.inner.scrollWidth
            const totalCards = this.cards.length
            this.step = `${innerWidth / totalCards}px`
        },
        next() {
            if (this.transitioning) return
            this.transitioning = true
            this.moveLeft()
            this.afterTransition(() => {
                const card = this.cards.shift()
                this.cards.push(card)
                this.resetTranslate()
                this.transitioning = false
            })
        },
        prev() {
            if (this.transitioning) return
            this.transitioning = true
            this.moveRight()
            this.afterTransition(() => {
                const card = this.cards.pop()
                this.cards.unshift(card)
                this.resetTranslate()
                this.transitioning = false
            })
        },
        moveLeft() {
            this.innerStyles = {
                transform: `translateX(-${this.step})
                    translateX(-${this.step})`
            }
        },
        moveRight() {
            this.innerStyles = {
                transform: `translateX(${this.step})
                    translateX(-${this.step})`
            }
        },
        afterTransition(callback) {
            const listener = () => {
                callback()
                this.$refs.inner.removeEventListener('transitionend', listener)
            }
            this.$refs.inner.addEventListener('transitionend', listener)
        },
        resetTranslate() {
            this.innerStyles = {
                transition: 'none',
                transform: `translateX(-${this.step})`
            }
        }
    },
    name: 'Carousel',
    components: {

    }
}
</script>
<template>
    <section>
        <div class="my-container d-flex justify-content-between">
            <div>
                <span class="color">Portfolio</span> <br>
                <span class="fs-2"><strong>latest</strong> work</span>
            </div>
            <div class="d-flex align-items-center">
                <button class="circle color me-3" @click="prev">
                    <font-awesome-icon icon="fa-solid fa-arrow-left" />
                </button>
                <button class="circle color" @click="next">
                    <font-awesome-icon icon="fa-solid fa-arrow-right" />
                </button>
            </div>
        </div>
        <div class="carousel">
            <div class="inner" ref="inner" :style="innerStyles">
                <div class="card" v-for="card in cards" :key="card">
                    <img :src="`src/assets/images${card.img} `" class="card-img-top" alt="...">
                    <div class="card-body d-flex justify-content-between align-items-center">
                        <strong class="fs-5">{{ card.title }}</strong>
                        <p class="fs-5">{{ card.description }}</p>
                    </div>
                </div>
            </div>
        </div>
</section>
</template>

<style lang="scss" scoped>
section {
    padding: 150px 60px;
}

.carousel {
    margin-top: 150px;
    width: 100%;
    overflow: hidden;
}

.inner {
    transition: transform 1s;
    white-space: nowrap;
}

.card {
    width: 600px;
    height: 500px;
    border-radius: 30px;
    margin-right: 10px;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    color: black;

    &:hover {
        background: rgb(242, 92, 108);
        background: linear-gradient(266deg, rgba(242, 92, 108, 1) 21%, rgba(185, 39, 110, 1) 50%);
        cursor: pointer;

        strong {
            color: white;
        }
    }

    .card-body {
        width: 100%;

        p {
            margin: 0;
            color: lightgray;
        }
    }


    img {
        width: 100%;
        height: 80%;
        object-fit: cover;
        border-radius: 30px;
    }
}

.color {
    color: $third-color;
}

button {
    background-color: white;

    &:hover {
        font-size: 20px;
    }
}

.circle {
    padding: 10px 15px;
    border: 1px solid $third-color;
    border-radius: 50%;
}
</style>