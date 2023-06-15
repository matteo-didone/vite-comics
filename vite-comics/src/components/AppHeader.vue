<template>
    <header>
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="dc-comics-logo">
        </div>

        <nav class="navbar">
            <ul>
                <li>

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

    header{
        display: flex;

        div.logo img{
            width: 100%;
        }

        nav.navbar ul{
            @include flex();
        }
    }

</style>