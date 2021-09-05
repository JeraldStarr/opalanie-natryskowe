<template>
<article class="article">
  <h1 class="article__header">OPALANIE NATRYSKOWE</h1>
  <p class="article__paragraph">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Quod quibusdam veritatis quae nisi, 
      libero architecto eveniet. Eligendi odio vero quos incidunt, nobis ab expedita tempore eius 
      esse labore beatae nulla.
      </p>
  <p class="article__paragraph">Nulla malesuada ante sit amet est finibus maximus. Integer sem neque, 
      luctus at ligula quis, aliquam scelerisque dolor. Donec molestie, nisl sed blandit fermentum, 
      arcu tortor venenatis enim, sed egestas dui justo vitae augue. Fusce at mi vel neque rutrum 
      sagittis. Nunc tristique sed lacus finibus feugiat. Suspendisse id turpis pellentesque est 
      scelerisque scelerisque et at erat. Praesent rhoncus, magna vel vulputate semper, libero 
      diam malesuada neque, vel vulputate purus nulla non ex. Cras vulputate commodo justo vitae 
      vestibulum.
      </p>
  <p class="article__paragraph">
      In hac habitasse platea dictumst. In gravida nisl non venenatis tristique. Nam consectetur 
      ullamcorper urna, nec porttitor turpis accumsan sit amet. Donec a metus libero. Vestibulum 
      auctor leo eget feugiat tristique. Nunc volutpat aliquam magna, in venenatis orci ullamcorper 
      eu. Morbi lectus augue, ultricies ac convallis at, rhoncus hendrerit justo. Phasellus pretium 
      lacinia eros, et consectetur felis consectetur vel. Vivamus eleifend enim consequat, tempor 
      nisi ac, hendrerit erat. Aenean dignissim eu quam a eleifend. Lorem ipsum dolor sit amet, 
      consectetur adipiscing elit. Integer posuere ligula ipsum, id tincidunt diam efficitur ac. 
      In et tortor vel ipsum consequat vestibulum.
  </p>
  <section class="article__images">
      <figure class="article__imageContainer">
          <img src="../assets/photos/room.jpg" alt="room" class="article__image">
      </figure>
      <figure class="article__imageContainer">
          <img src="../assets/photos/room_and_flowers.jpg" alt="room and flowers" class="article__image">
      </figure>
  </section>
  <h2 class="article__minorHeader">DLA KOGO?</h2>
    <p class="article__paragraph">In ut egestas nulla. Cras fringilla risus leo, id venenatis magna 
      condimentum commodo. Etiam et lorem eu orci posuere auctor sed eget nunc. Vestibulum 
      vestibulum, leo nec pulvinar hendrerit, lacus ligula tempor justo, a auctor urna enim sit 
      amet dui. Donec ac aliquam velit, nec ultricies risus. Vestibulum ante ipsum primis 
      in faucibus orci luctus et ultrices posuere cubilia curae; Aenean scelerisque est a 
      feugiat posuere. Morbi vel quam rhoncus, iaculis sapien id, tincidunt lacus. Pellentesque 
      sed massa et metus hendrerit aliquet sodales ac ligula. Maecenas ultrices tempor laoreet.
    </p>
    <p class="article__paragraph">
        t cursus enim eu dolor maximus mollis. Aenean ut elit ac metus vulputate accumsan id ut 
        lectus. Fusce mattis dictum purus, in accumsan dolor lacinia nec. Aliquam laoreet non 
        turpis sit amet tincidunt. Suspendisse ac congue est. Vivamus sollicitudin, ex sed luctus 
        congue, nunc tellus fringilla nunc, congue gravida elit purus ut tortor. Duis suscipit dolor 
        neque, et dictum turpis tristique sed. Sed pellentesque libero sit amet turpis ullamcorper, 
        at imperdiet nulla varius. Proin eleifend massa quis sodales mollis.
    </p>
  <section class="article__images">
      <figure class="article__imageContainer">
              <img src="../assets/photos/woman_back.jpg" alt="woman's back" class="article__image">
      </figure>
      <figure class="article__imageContainer">
              <img src="../assets/photos/woman_side.jpg" alt="woman's side" class="article__image">
      </figure>
  </section>
  <h2 class="article__minorHeader">MOŻESZ ZDECYDOWAĆ SIĘ NA JEDNĄ Z DOSTĘPNYCH OPCJI ZABIEGU OPALANIA NATRYSKOWEGO</h2>
  <p class="article__paragraph">
      Praesent ac enim sit amet orci interdum auctor venenatis eget felis. Donec pulvinar sodales 
      libero egestas dictum. Vivamus accumsan, nisl et varius tempor, elit ex faucibus nibh, vel 
      cursus diam dui eget ligula. Ut consequat feugiat lectus, ac molestie turpis cursus vitae. 
      Sed massa orci, imperdiet in dolor ultrices, accumsan sodales magna. Nunc porttitor mollis 
      sem ac faucibus. Ut cursus enim eu dolor maximus mollis. 
  </p>
</article>
</template>

<script>
export default {
    name: 'Article',
}
</script>

<style lang="scss" scoped>
    .article {
        display: flex;
        flex-direction: column;
        align-items: center;
        &__header {
            font-size: 40px;
            padding: 10px 0 40px;
        }
        &__paragraph {
            font-size: 18px;
            padding: 10px 20%;
            text-align: justify;
        }
        &__images {
            display: flex;
            justify-content: center;
        }
        &__image {
            width: 100%;
        }
        &__imageContainer {
            width: 30vw;
        }
        &__minorHeader {
            color: #e7a5aa;
            font-size: 25px;
            padding: 15px 0;
            max-width: 500px;
            text-align: center;
        }
    }
</style>     