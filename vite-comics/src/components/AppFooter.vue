<template>
    <footer>

        <div class="footer-left">
            <button class="footer-button">SIGN-UP NOW!</button>
        </div>

        <div class="footer-right">

            <h3> FOLLOW US </h3>

            <ul>
                <li>
                    <div class="social-link">
                        <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-facebook.png" alt="Facebook Logo">
                    </div>
                </li>

                <li>
                    <div class="social-link">
                        <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-twitter.png" alt="Twitter Logo">
                    </div>
                </li>

                <li>
                    <div class="social-link">
                        <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-youtube.png" alt="YouTube Logo">
                    </div>
                </li>

                <li>
                    <div class="social-link">
                        <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-pinterest.png" alt="Pinterest Logo">
                    </div>
                </li>

                <li>
                    <div class="social-link">
                        <img src="/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/assets/img/footer-periscope.png" alt="Periscope Logo">
                    </div>
                </li>

            </ul>
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

    footer{
        height: 50px;
        background-color: #303030;
    }

</style>