<script >
import Home from "./pages/Home.vue";
import AppHeader from "./cmps/AppHeader.vue";
import AppFooter from "./cmps/AppFooter.vue";

export default {
  components: {
    Home,
    AppHeader,
    AppFooter
  }
}

</script>

<template>
  <div  class="app-container main-layout">
    <AppHeader />
    <main class="main-content main-layout full">
      <Home />
    </main>
    <AppFooter />
  </div>
</template>

<style lang="scss">

</style>
