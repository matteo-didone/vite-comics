<template>

    <div class="blue-line">
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital-Comics">
                <span>DIGITAL COMICS</span>
            </li>

            <li>
                <img src="../assets/img/buy-comics-merchandise.png"  alt="DC-Merchandise">
                <span>DC MERCHANDISE</span>
            </li>

            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
                <span>SUBSCRIPTIONS</span>
            </li>

            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="Comic Shop Locator">
                <span>COMIC SHOP LOCATOR</span>
            </li>

            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="DC Power Visa">
                <span>DC POWER VISA</span>
            </li>

        </ul>
    </div>

</template>

<script>
    export default {
        name: 'AppBlueLine',
        data() {
            return {

            }
        },
    }
</script>

<script setup>

</script>


<style lang="scss">
    .blue-line {
        background-color: #0282f9;
        height: 150px;

        display: flex;
        justify-content: center;
        align-items: center;        
    }

    .blue-line ul {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .blue-line ul li {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding: 0 20px;
    }

    .blue-line ul li img {
        width: 40%;
        height: 40%;
    }

</style>