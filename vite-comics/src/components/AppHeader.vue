<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="dc-comics-logo">
        </div>

        <nav class="navbar">
            <ul>

                <li>
                    <a href="#">Characters</a>
                </li>

                <li>
                    <a href="#" class="dc-blue">Comics</a>
                </li>

                <li>
                    <a href="#">Movies</a>
                </li>

                <li>
                    <a href="#">TV</a>
                </li>

                <li>
                    <a href="#">Games</a>
                </li>

                <li>
                    <a href="#">Collectibles</a>
                </li>

                <li>
                    <a href="#">Videos</a>
                </li>

                <li>
                    <a href="#">Fans</a>
                </li>

                <li>
                    <a href="#">News</a>
                </li>

                <li>
                    <a href="#">Shop</a>
                </li>

            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: 'AppHeader',
    data() {
        return {

        }
    },
}
</script>

<script setup>

</script>

<style lang="scss" scoped>
// Scoped styles
@use '/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/styles/partials/_mixins.scss' as *;
@use '/Users/matteodidone/VS Code Projects/vite-comics/vite-comics/src/styles/partials/_variables.scss' as *;

header {

    height: 150px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    div.logo {
        padding-left: 320px;
        ;
    }

    div.logo img {
        width: 100px;
        height: 100px;
    }

    nav.navbar ul {
        @include flex();
        font-size: x-large;
        padding-right: 200px;
        font-weight: 550;
    }

    nav.navbar ul li {
        list-style: none;
        margin: 0 20px;
        text-transform: uppercase;
    }

    nav.navbar ul li .dc-blue {
        padding-bottom: 50px;
        border-bottom: 5px solid $dc-blue;
    }
}
</style>