<script></script>

<template>

    <section class="container-main">

        <main>

            <div class="provisional-content">
            Content goes here
            </div>

            <div class="sub-menu">

                <ul class="text-uppercase d-flex">

                    <li class="d-flex">
                        <div>
                            <img src="/public/img/buy-comics-digital-comics.png" alt="digital-comics-buy">
                        </div>
                        <a href="#">digital comics</a>
                    </li>

                    <li class="d-flex">
                        <div>
                            <img src="/public/img/buy-comics-merchandise.png" alt="comics-merchandise">
                        </div>
                        <a href="#">dc merchandise</a>
                    </li>

                    <li class="d-flex">
                        <div>
                            <img src="/public/img/buy-comics-subscriptions.png" alt="comics-subscriptions">
                        </div>
                        <a href="#">subscription</a>
                    </li>

                    <li class="d-flex">
                        <div>
                            <img src="/public/img/buy-comics-shop-locator.png" alt="shop-locator">
                        </div>
                        <a href="#">comic shop locator</a>
                    </li>

                    <li class="d-flex">
                        <div>
                            <img src="/public/img/buy-dc-power-visa.svg" alt="dc-power-visa">
                        </div>
                        <a href="">dc power visa</a>
                    </li>
                
                </ul>

            </div>

        </main>

    </section>

    

</template>

<style scoped lang="scss">

    .container-main {
        background-color: rgba(28, 28, 28, 1);
    }

    img {
        width: 100%;
    }

    main {
        color: rgba(255, 255, 255, 1);
    }
    .provisional-content {
        height: 6rem;
    }

    .sub-menu {
        height: 8rem;
        background-color: rgba(2, 130, 249, 1);
    }

    .sub-menu ul li div {
        height: 3rem;
    }

    li {
        list-style-type: none;
        margin-right: 3rem;
    }

    a {
        text-decoration: none;
        color: rgba(255, 255, 255, 1);
    }

</style>