<template>
  <div class="footer">
      <div class="footer__text">
          ©Copyright 2020 Fake Bake Polska
      </div>
      <div class="footer__socialMedia">
          <img src="./../assets/facebook.png" alt="facebook icon" class="footer__icon">
          <img src="./../assets/instagram.png" alt="istagram icon" class="footer__icon">
      </div>
  </div>
</template>

<script>
export default {
    name: "Footer",
}
</script>

<style lang="scss" scoped>
    .footer {
        display: flex;
        align-items: center;
        justify-content: space-between;
        background-color: #e7a5aa;
        height: 60px;
        color: #fff;
        padding-left: 5%;
        &__socialMedia {
            display: flex;
            padding-right: 3%;
        }
        &__icon {
            display: block;
            width: auto;
            height: auto;
            max-width: 50px;
            max-height: 50px;
            padding-left: 10%;
            padding-right: 10%;
            cursor: pointer;
        }
    }
</style>