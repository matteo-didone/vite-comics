<template>
    <footer>

        <div class="footer-top">

            <div class="footer-top-left">

                <div class="first-column">

                    <div class="dc-comics">

                    </div>

                    <div class="shop">

                    </div>

                </div>

                <div class="second-column">

                </div>

                <div class="third-column">

                </div>

            </div>

            <div class="footer-top-right">
                
            </div>

        </div>

        <div class="footer-bottom">
            <div class="footer-bottom-left">
                <button class="footer-button">SIGN-UP NOW!</button>
            </div>

            <div class="footer-bottom-right">

                <h3> FOLLOW US </h3>

                <ul>
                    <li>
                        <div class="social-link">
                            <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-facebook.png"
                                alt="Facebook Logo">
                        </div>
                    </li>

                    <li>
                        <div class="social-link">
                            <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-twitter.png"
                                alt="Twitter Logo">
                        </div>
                    </li>

                    <li>
                        <div class="social-link">
                            <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-youtube.png"
                                alt="YouTube Logo">
                        </div>
                    </li>

                    <li>
                        <div class="social-link">
                            <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-pinterest.png"
                                alt="Pinterest Logo">
                        </div>
                    </li>

                    <li>
                        <div class="social-link">
                            <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-periscope.png"
                                alt="Periscope Logo">
                        </div>
                    </li>

                </ul>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'AppFooter',
    data() {
        return {

        }
    },
}
</script>

<script setup>

</script>

<style lang="scss">
footer {
    height: 470px;

    display: flex;
    flex-direction: column;

    .footer-top {
        background-color: #212121;
        height: 370px;
        background-image: url("/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }

    .footer-bottom {
        background-color: #303030;
        height: 100px;
    }

}</style>