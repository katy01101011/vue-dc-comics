<template>
  <div id="app" class="app">
    <!-- Header -->
    <AppHeader />
    <!-- Jumbotron -->
    <AppJumbotron />
    <!-- Main -->
    <AppMain />
    <!-- Nav -->
    <AppNav />
    <!-- Prefooter -->
    <AppPrefooter />
    <!-- Footer -->
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "../src/components/AppHeader.vue";
import AppJumbotron from "../src/components/AppJumbotron.vue";
import AppMain from "../src/components/AppMain.vue";
import AppNav from "../src/components/AppNav.vue";
import AppPrefooter from "../src/components/AppPrefooter.vue";
import AppFooter from "../src/components/AppFooter.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppJumbotron,
    AppMain,
    AppNav,
    AppPrefooter,
    AppFooter,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
