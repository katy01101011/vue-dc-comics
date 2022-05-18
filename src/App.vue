<template>
  <div id="app" class="app">
    <!-- Header -->
    <AppHeader />
    <!-- Main -->
    <div style="background-color: black; color: white">
      <div class="container">
        <div class="app__content">Content</div>
      </div>
    </div>

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
import AppNav from "../src/components/AppNav.vue";
import AppPrefooter from "../src/components/AppPrefooter.vue";
import AppFooter from "../src/components/AppFooter.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppNav,
    AppPrefooter,
    AppFooter,
  },
};
</script>

<style lang="scss">
@import "./style/common.scss";
</style>
