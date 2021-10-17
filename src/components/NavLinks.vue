<template>
  <div class="navigation__links">
    <a class="navigation__link">Sklep</a>
    <a class="navigation__link">Szkolenia</a>
    <a class="navigation__link">Opalanie Natryskowe</a>
    <a class="navigation__link">Salony partnerskie</a>
    <a class="navigation__link">O nas</a>
    <a class="navigation__link">Kontakt</a>
  </div>
</template>

<script>
export default {
    name: "NavLinks",
    setup() {
      
    },
}
</script>

<style lang="scss" scoped>
  .navigation {
    &__links {
      @media(max-width: 719px) {
          position: fixed;
          top: 0;
          width: 100vw;
          transform: translateY(-300px);
          transition: .4s;
        .menuSheet & {
          z-index: 2;
          transform: translateY(30px);
        }
      } 
    }
    &__link {
      padding: 10px;
      transition: .3s;
      &:hover {
        color: #e7a5aa;
        cursor: pointer;
        @media(max-width: 719px) {
          color: #fff;
        }
      }
      @media(max-width: 719px) {
        display: block;
        text-align: center;
      }
    }
  }

</style>