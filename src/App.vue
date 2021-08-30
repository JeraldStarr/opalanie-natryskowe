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
  body {
    background-image: url("../src/assets/background.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>
