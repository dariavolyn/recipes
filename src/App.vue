<template>
  <HeaderComponent />
  <WelcomePage />
</template>

<script>
import WelcomePage from "./components/Main.vue";
import HeaderComponent from "./components/Header.vue";

export default {
  name: "App",
  components: {
    WelcomePage,
    HeaderComponent,
  },
};
</script>

<style lang="sass">
@import './styles/main.sass'
</style>
