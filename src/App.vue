<template>
  <div>
    <Navigation />
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Navigation,
  }
}
</script>

<style lang="scss">
@font-face {
  font-family: "Oswald";
  src: url("./assets/fonts/Oswald/Oswald-VariableFont_wght.ttf");
}
  body {
    background-image: url("../src/assets/background.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    font-family: "Oswald";

  }
</style>
