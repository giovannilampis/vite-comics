<script></script>

<template>

    <section>

        <div class="top-footer-container">

            <div class="d-flex flex-column">

                <ul>
                    <li class="text-white text-uppercase"><h5>DC COMICS</h5></li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>

                </ul>

                <ul>
                    <li class="text-white text-uppercase mt-4"><h5>shop</h5></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>

                </ul>

                </div>

                <ul>
                <li><h5 class="text-white text-uppercase">dc</h5></li>
                <li>Terms Of Use</li>
                <li>Privacy policy (New)</li>
                <li>Ad Choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent Workshoos</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop Help</li>
                <li>Contact Us</li>

                </ul>

                <ul>
                <li><h5 class="text-white text-uppercase">SITES</h5></li>
                <li>DC</li>
                <li>MAD Magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>

                </ul>


        </div>

      
    </section>

    <div class="bottom-footer">

        <div class="bottom-footer-container d-flex justify-content-between align-items-center text-uppercase">

            <a href="#" class="sign-up">sign-up now!</a>

            <ul class="d-flex">

                <li class="d-flex align-items-center"><a href="#">follow us</a></li>
                <li><a href="#"><img src="/public/img/footer-facebook.png" alt="facebook logo link"></a></li>
                <li><a href="#"><img src="/public/img/footer-twitter.png" alt="twitter logo link"></a></li>
                <li><a href=""><img src="/public/img/footer-youtube.png" alt="youtube logo link"></a></li>
                <li><a href="#"><img src="/public/img/footer-pinterest.png" alt="pinterest logo link"></a></li>
                <li><a href="#"><img src="/public/img/footer-periscope.png" alt="periscope logo link"></a></li>

            </ul>

        </div>

    </div>

</template>

<style scoped lang="scss">

    .top-footer-container {
        width: 85%;
        margin: 0 auto;
        min-height: 25rem;
        display: flex;
        justify-content: left;
        align-items: flex-start;
        padding: 2rem 0;
    }

    section {
        background-color: rgba(48, 48, 48, 1);
        background-image: url(/public/img/footer-bg.jpg);
        background-size: cover;
    }

    ul {
        list-style-type: none;
        margin: 0;
        color: gray;
    }

    ul li {
        margin-right: 2rem;
    }

    ul li:first-child a {
        color: rgba(2, 130, 249, 1);
    }

    a {
        text-decoration: none;
    }

    .bottom-footer {
        background-color: rgba(48, 48, 48, 1);
    }

    .bottom-footer-container {
        width: 85%;
        height: 6rem;
        color: rgba(255, 255, 255, 1);
        margin: 0 auto;
    }

    .bottom-footer-container a {
        color: rgba(255, 255, 255, 1);
        text-decoration: none;
    }

    .bottom-footer-container > a {
        border: 2px solid rgba(2, 130, 249, 1);
        padding: 0.7rem 0.9rem;
    }

    .icon-bg {
        color: rgba(121, 121, 121, 1);
    }

</style>