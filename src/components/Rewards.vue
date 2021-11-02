<template>
  <div class="rewards">
      <div class="rewards__imgContainer" v-for="i in 12" v-bind:key="i">
            <img class="rewards__img" v-bind:src="require('../assets/photos/rewards/reward' + i + '.jpg')" alt="reward image">
      </div>
  </div>
</template>


<script>
export default {
    name: 'Rewards',
}
</script>

<style lang="scss" scoped>
.rewards {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 5vw;
        @media (max-width: 719px) {
            flex-wrap: wrap;
        }
    &__imgContainer {
        width: 5%;
        @media (max-width: 719px) {
            flex-basis: 50px;
            margin: 15px;
        }
    }
    &__img {
        width: 100%;
    }
}

</style>