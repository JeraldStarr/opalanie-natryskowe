<template>
  <div>
    <Navigation />
    <Article />
    <PriceList />
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue';
import Article from './components/Article.vue';
import PriceList from './components/PriceList.vue';

export default {
  name: 'App',
  components: {
    Navigation,
    Article,
    PriceList,
  }
}
</script>

<style lang="scss">
@font-face {
  font-family: "Oswald";
  src: url("./assets/fonts/Oswald/Oswald-VariableFont_wght.ttf");
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
  body {
    background-image: url("../src/assets/background.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    font-family: "Oswald";

  }
</style>
