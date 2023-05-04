<script>

    import ComicBook from ./components/ComicBook.vue';

    export default{
        name: "AppMain",
        data() {
            return {
                products: [
                    {
                        "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                        "price": "$19.99",
                        "series": "Action Comics",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                        "price": "$3.99",
                        "series": "American Vampire 1976",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
                        "price": "$16.99",
                        "series": "Aquaman",
                        "type": "graphic novel"
                    },
                    {
                        "thumb": "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
                        "price": "$2.99",
                        "series": "Batgirl",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
                        "price": "$3.99",
                        "series": "Batman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
                        "price": "$2.99",
                        "series": "Batman Beyond",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
                        "price": "$3.99",
                        "series": "Batman/Superman",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
                        "price": "$4.99",
                        "series": "Batman/Superman Annual",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
                        "price": "$5.99",
                        "series": "Batman: The Joker War Zone",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
                        "price": "$6.99",
                        "series": "Batman: Three Jokers",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
                        "price": "$4.99",
                        "series": "Batman: White Knight Presents: Harley Quinn",
                        "type": "comic book"
                    },
                    {
                        "thumb": "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
                        "price": "$16.99",
                        "series": "Catwoman",
                        "type": "graphic novel"
                    }
                    ]
            }
        },
    }

</script>

<template>

    <main>

        <div class="comics">
            <div class="comics-container">
                
                <div class="card" v-for="(element, index) in products" 
                    :key="index">

                    <img :src="element.thumb" :alt="element.series">

                    <div class="comics-specs">

                        <h6 class="text-uppercase">{{ element.series }}</h6>

                        <span>{{ element.type }} - {{ element.price }}</span>

                    </div>

                </div>

            </div>
        </div>

        <div class="blue-menu">

            <div class="container-blue">

                <ul class="d-flex text-uppercase">

                    <li class="d-flex justify-content-between align-items-center">
                        <div>
                            <img src="/public/img/buy-comics-digital-comics.png" alt="digital-comics-buy">
                        </div>
                        <a href="#">digital comics</a>
                    </li>

                    <li class="d-flex justify-content-between align-items-center">
                        <div>
                            <img src="/public/img/buy-comics-merchandise.png" alt="comics-merchandise">
                        </div>
                        <a href="#">dc merchandise</a>
                    </li>

                    <li class="d-flex justify-content-between align-items-center">
                        <div>
                            <img src="/public/img/buy-comics-subscriptions.png" alt="comics-subscriptions">
                        </div>
                        <a href="#">subscription</a>
                    </li>

                    <li class="d-flex justify-content-between align-items-center">
                        <div>
                            <img src="/public/img/buy-comics-shop-locator.png" alt="shop-locator">
                        </div>  
                        <a href="#">comic shop locator</a>
                    </li>

                    <li class="d-flex justify-content-between align-items-center">
                        <div>
                            <img src="/public/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                        </div>
                        <a href="">dc power visa</a>
                    </li>

                </ul>

            </div>

        </div>

    </main>

</template>

<style scoped lang="scss">

    main {
        color: rgba(255, 255, 255, 1);
        margin: 0 auto;
        padding: 2rem 0;
    }
    .blue-menu img {
        height: 2.5rem;
        width: 80%;
    }

    .blue-menu {
        height: 8rem;
        background-color: rgba(2, 130, 249, 1);
    }
    .container-blue {
        width: 85%;
        margin: 0 auto;
    }

    .blue-menu ul li div {
        height: 2.5rem;
        aspect-ratio: 1 / 1;
    }

    li {
        list-style-type: none;
        margin-right: 3rem;
    }

    a {
        text-decoration: none;
        color: rgba(255, 255, 255, 1);
    }
    .comics {
        min-height: 10rem;
        background-color: rgba(28, 28, 28, 1);
    }

    .comics-container {
        width: 85%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
    }

    .card {
        width: calc(100% / 6 - 0.5rem);
        background-color: rgba(28, 28, 28, 1);
        padding: 1rem;
    }

    .comics-container img {
        width: 100%;
    }

</style>