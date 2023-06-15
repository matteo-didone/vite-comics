<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBlueLine from './components/AppBlueLine.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {

  },
}
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppBlueLine />
  <AppFooter />
</template>

<style lang="scss">
@import '/styles/general.scss';
</style>