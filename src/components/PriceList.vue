<template>
    <div class="priceList">
      <div class="priceList__itemContainer">
      <span class="priceList__item">
        <strong class="priceList__text">
          STANDARD
        </strong>
        <strong class="priceList__text">
          120 zł
        </strong>

      </span>
        <span class="priceList__itemDescription">
          całe ciało
        </span>
      </div>
    <div class="priceList__itemContainer">
      <span class="priceList__item">
        <strong class="priceList__text">
          STANDARD
        </strong>
        <strong class="priceList__text">
          80 zł
        </strong>
      </span>
        <span class="priceList__itemDescription">
          połowa ciała
        </span>
    </div>
    <div class="priceList__itemContainer">
      <span class="priceList__item">
        <strong class="priceList__text">
          PREMIUM
        </strong>
        <strong class="priceList__text">
          160 zł
        </strong>
      </span>
        <span class="priceList__itemDescription">
          całe ciało + peeling*
        </span>
    </div>
    <div class="priceList__itemContainer">
      <span class="priceList__item">
        <strong class="priceList__text">
          FIT
        </strong>
        <strong class="priceList__text">
          200 zł
        </strong>
      </span>
        <span class="priceList__itemDescription">
          opalanie natryskowe + konturowanie**
        </span>
    </div>
      <div class="priceList__footnotes">
        <span class="priceList__footnote">
          <strong>*Peeling Fake Bake</strong> – dzięki beztłuszczowej formule zapewni odpowiednie 
          przygotowanie skóry przed zabiegiem,
            pozostawi ją odpowiednio nawilżoną i gładką oraz przedłuży efekt opalenizny.
          </span>
          <span class="priceList__footnote">
            <strong>
              **Usługa skierowana do branży kulturystycznej.
            </strong>
          </span>
      </div>
  </div>
</template>

<script>
export default {
  name: "PriceList",

}
</script>

<style lang="scss" scoped>
.priceList {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  padding: 40px 22%;
  &__itemContainer {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 170px;
    height: 280px;
  }
  &__item {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #e7a5aa;
    font-weight: bold;
    width: 160px;
    height: 160px;
    border-radius: 50%;
  }
  &__text {
    color: #fff;
    font-size: 30px;
    line-height: 1.2;
  }
  &__footnotes {
    width: 100vw;
  }
  &__itemDescription {
    text-align: center;
    font-size: 17px;
    padding-top: 20px;
  }
  &__footnote {
    display: block;
    font-size: 13px;
  }
}

</style>