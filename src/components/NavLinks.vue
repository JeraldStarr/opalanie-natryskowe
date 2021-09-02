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
      display: flex;
    }
    &__link {
      padding: 10px;
      transition: .3s;
      &:hover {
        color: #e7a5aa;
        cursor: pointer;
      }
    }
  }

</style>