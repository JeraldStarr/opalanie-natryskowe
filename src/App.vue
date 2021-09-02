<template>
  <div>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&display=swap" rel="stylesheet">
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
    font-family: 'Oswald', sans-serif;
  }
</style>
