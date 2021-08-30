<template>
  <div class="navigation">
    <Logo/>
    <NavLinks/>
  </div>
</template>

<script>
import Logo from "./Logo.vue";
import NavLinks from "./NavLinks.vue";
export default {
  name: 'Navigation',
  components: {
    Logo,
    NavLinks,
  },
  props: {
    msg: String
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
