<template>
  <div class="sheet"></div>
</template>

<script>
export default {
    name: 'Sheet',

}
</script>

<style scoped lang="scss">
    .sheet {
        visibility: hidden;
        position: fixed;
        top: 0;
        width: 100vw;
        height: 1px;
        background-color: #e7a5aa;
        transition-duration: .4s;
    }
    .menuSheet .sheet {
        visibility: visible;
        transform: scaleY(2000);
    }
</style>