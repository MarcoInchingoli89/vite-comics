<script>
export default {
    name: 'SiteFooter'
}

</script>

<template>
    <footer id="site_footer">
        <div class="container_fluid">
            <div class="footer_head">
                <ul>
                    <li>

                        <a class="footer_icon" href="#"><img width="40"
                                src="../assets/img/buy-comics-digital-comics.png" alt=""></a>
                        <a class="text" href="#">Digital Comics</a>

                    </li>

                    <li>

                        <a class="footer_icon" href="#"><img width="40" src="../assets/img/buy-comics-merchandise.png"
                                alt=""></a>
                        <a class="text" href="#">DC Merchandise</a>

                    </li>

                    <li>

                        <a class="footer_icon" href="#"><img width="40" src="../assets/img/buy-comics-subscriptions.png"
                                alt=""></a>
                        <a class="text" href="#">Subscription</a>

                    </li>

                    <li>

                        <a class="footer_icon" href="#"><img width="40" src="../assets/img/buy-comics-shop-locator.png"
                                alt=""></a>
                        <a class="text" href="#">Comic Shop Locator</a>

                    </li>

                    <li>

                        <a class="footer_icon" href="#"><img width="40" src="../assets/img/buy-dc-power-visa.svg"
                                alt=""></a>
                        <a class="text" href="#">DC Power Visa</a>

                    </li>
                </ul>
            </div>
        </div>
        <div class="footer_main">
            <div class="container_row d-flex justify-content-center">
                <div class="row d-flex justify-content-center">
                    <div class="col d-flex">
                        <div class="col">
                            <h3>DC Comics</h3>
                            <ul>
                                <li><a href="#">Characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul>
                            <h3>Shop</h3>
                            <ul>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">Shop DC Collectibles</a></li>
                            </ul>
                        </div>
                        <div class="col">
                            <h3>DC</h3>
                            <ul>
                                <li><a href="#">Terms of Use</a></li>
                                <li><a href="#">Privacy Policy (New)</a></li>
                                <li><a href="#">Add Choice</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>
                                <li><a href="#">Subscriptions</a></li>
                                <li><a href="#">Talent Workshops</a></li>
                                <li><a href="#">CPSC Certificated</a></li>
                                <li><a href="#">Ratings</a></li>
                                <li><a href="#">Shop Help</a></li>
                                <li><a href="#">Contact Us</a></li>
                            </ul>
                        </div>
                        <div class="col">
                            <h3>Sites</h3>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">DC Kids</a></li>
                                <li><a href="#">DC Universe</a></li>
                                <li><a href="#">DC Power Visa</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col d-flex justify-content-center logo_bg">
                        <!-- <img width="300" src="../assets/img/dc-logo-bg.png" alt=""> -->
                    </div>
                </div>
            </div>
        </div>
        <div class="footer_bottom d_flex">
            <button class="btn">Sign-Up Now!</button>
            <div class="social_contacts">
                <div class="follow">Follow Us</div>
                <div class="social_icons">
                    <ul>
                        <li>

                            <a class="footer_icon" href="#"><img width="30" src="../assets/img/footer-facebook.png"
                                    alt=""></a>

                        </li>

                        <li>

                            <a class="footer_icon" href="#"><img width="30" src="../assets/img/footer-twitter.png"
                                    alt=""></a>

                        </li>

                        <li>

                            <a class="footer_icon" href="#"><img width="30" src="../assets/img/footer-youtube.png"
                                    alt=""></a>

                        </li>

                        <li>

                            <a class="footer_icon" href="#"><img width="30" src="../assets/img/footer-pinterest.png"
                                    alt=""></a>

                        </li>

                        <li>

                            <a class="footer_icon" href="#"><img width="30" src="../assets/img/footer-periscope.png"
                                    alt=""></a>

                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.container_fluid {
    background-color: $dc-primary;
    display: flex;
    justify-content: center;
}

.footer_head {
    max-width: 80%;

    .footer_icon img {
        padding: 1rem 1rem;
    }

    .text {
        color: white;
        text-decoration: none;
        text-transform: uppercase;
        font-size: 0.7rem;
    }

    ul {
        padding: 0;
        display: flex;
        justify-content: space-around;
        gap: 3rem;
    }

    li {
        display: flex;
        align-items: center;
    }
}

.footer_main {
    background-image: url('../assets/img/footer-bg.jpg');
}

.footer_main .row {
    width: 100%;
}

.footer_main .logo_bg {
    background-image: url('../assets/img/dc-logo-bg.png');
    background-position: right center;
    background-repeat: no-repeat;
}

.space_between {
    justify-content: space-between;
}

.footer_main h3 {
    color: white;
    text-transform: uppercase;
    text-align: left;
    font-weight: bold;
    font-size: 1rem;
}

.footer_main li {
    list-style: none;
}

.footer_main a {
    text-decoration: none;
    color: grey;
    font-size: 0.8rem;
}

.footer_bottom {
    display: flex;
    justify-content: space-around;
    background-color: $dc-dark;
}

.footer_bottom .btn {
    border: 2px solid $dc-primary;
    background-color: $dc-dark;
    color: white;
    text-transform: uppercase;
    font-weight: bold;
    height: 50px;
    margin: 1rem;
}

.footer_bottom .follow {
    font-size: 1.2rem;
    color: blue;
    text-transform: uppercase;
    font-weight: bolder;
}

.social_contacts {
    display: flex;
    align-items: center;
}

.social_icons ul {
    display: flex;
    gap: 1rem;
}

.social_icons li {
    list-style: none;
}
</style>