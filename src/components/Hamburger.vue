<template>
  <button class="hamburger" @click="toggleBodyClass"></button>
</template>

<script>
export default {
    name: 'Hamburger',
    setup() {
        function toggleBodyClass() {
            document.body.classList.toggle("menuSheet");
        }
        return {toggleBodyClass}
    }
}

</script>

<style scoped lang="scss">
    .hamburger {
        display: none;
        z-index: 3;
        @media (max-width: 719px) {   
            display: block; 
            height: 17px;
            width: 20px;
            border: 0;
            border-top: 3px solid #AD6364;
            background-color: transparent;
            transition: .3s transform linear;
            position: fixed;
            right: 29px;
            top: 20px;
            outline: none;
            &::after,
            &::before {
                content: '';
                position: absolute;
                top: 0;
                left: 0;
                width: 100%;
                border-top: 3px solid #AD6364;
                transform: translateY(5px);
            }
            &::after {
                transform: translateY(13px);
                transition: .3s transform linear;
            }
            .menuSheet & {
                transform: rotate(45deg) translateY(5px);
                border: none;
            }
            .menuSheet &::after {
                transform: rotate(-90deg) translateX(-5px);
            }
        }
        
    }
</style>