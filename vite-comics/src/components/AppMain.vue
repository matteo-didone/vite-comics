<template>
    <main>
        <h1> --> Content goes here &lt-- </h1>
    </main>
</template>

<script>
    export default {
        name: 'AppMain',
        data() {
            return {

            }
        },
    }
</script>

<script setup>

</script>

<style lang="scss">
    main {
        background-color: #1c1c1c;
        height: 150px;

        display: flex;
        align-items: center;
    }

    main h1 {
        color: #fff;
        font-size: 3rem;
        padding-left: 320px;
    }
</style>