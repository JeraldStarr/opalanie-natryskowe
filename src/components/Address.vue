<template>
  <div class="address">
      <div class="address__elementsGroup">
          Zapraszamy na profesjonalny zabieg opalania natryskowego FAKE BAKE<br/>
            w samym centrum Warszawy.
      </div>
      <div class="address__elementsGroup">
          Tel. <span class="address__highlighted">22-416-22-08</span>
      </div>
      <div class="address__elementsGroup">
          <div>Poniedziałek - Środa</div>
          <div>9:00 - 17:00</div>
      </div>
      <div class="address__elementsGroup">
        <div>Czwartek - Piatek</div>
          <div>10:00 - 19:00</div>
      </div>
      <div class="address__elementsGroup">
          <div class="address__highlighted">FAKE BAKE POLSKA</div>
           <div>ul. Pańska 98 lok.204</div>
            <div>00-837 Warszawa</div>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Address',
}
</script>

<style lang="scss" scoped>
    .address {
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: #fff;
        padding: 60px 0;
        font-size: 20px;
        &__elementsGroup {
            text-align: center;
            margin: 10px 0;
            @media (max-width: 500px) {
                padding: 0 15%;
            }
        }
        &__highlighted {
            color: #e7a5aa;
        }
    }
</style>