<template>
  <a class="navigation__logo" href="/">
    <img src="../assets/logo.png" alt="fake bake logo" class="navigation__img">
  </a>
</template>

<script>
export default {
    name: "Logo",
}
</script>

<style lang="scss" scoped>
  .navigation {
    &__logo {
      width: 77px;
      height: 70px;
    }
    &__img {
      width: 100%;
    }
  }
</style>