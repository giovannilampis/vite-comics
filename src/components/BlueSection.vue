<script>

    export default {
        name: 'BlueSection'
    }

</script>

<template>
    
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

</template>

<style lang="scss" scoped>

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

</style>
