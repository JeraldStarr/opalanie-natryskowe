<template>
  <div class="hints">
      <h2 class="hints__header">
          WSKAZÓWKI PRZED ZABIEGIEM
      </h2>
      <section class="hints__textContainer">
          <div class="hints__item hints__item--noListed">Pamiętaj o odpowiednim przygotowaniu 
              skóry, co sprawi, że Twoja opalenizna będzie perfekcyjna a Ty będziesz się nią mogła 
              cieszyć maksymalnie długo.</div>
          <div class="hints__item">Nie używaj innych produktów opalających na tydzień przed zabiegiem.</div>
          <div class="hints__item">Wykonaj beztłuszczowy peeling całego ciała 24h przed zabiegiem. 
              Specjalnie dedykowany jest do tego nasz kokosowy peeling Fake Bake.</div>
          <div class="hints__item">Depilację wykonaj na 1 – 2 dni przed zaplanowaną wizytą, dzięki 
              czemu unikniesz ciemniejszych „kropeczek”.</div>
          <div class="hints__item">
              Jeżeli masz tendencję do rozszerzonych porów – weź prysznic na 4-6 h godzin przed 
              zabiegiem i zakończ go zimną wodą.
          </div>
          <div class="hints__item">
              Skóra powinna być oczyszczona z makijażu, dezodorantu, perfum, balsamu i innych 
              kosmetyków, które mogą powodować barierę i nieprawidłowe wchłanianie produktu.
          </div>
          <div class="hints__item">W dniu zabiegu zalecamy założyć ciemne, luźne rzeczy.</div>
          <div class="hints__item">Umów się 2 – 3 dni przed planowanym wydarzeniem, aby mieć 
              pewność, że opalenizna pięknie się rozwinie.</div>
          <div class="hints__item">Jeśli planujesz inne zabiegi kosmetyczne – umów się na nie przed 
              opalaniem natryskowym.
          </div>
      </section>

      <h2 class="hints__header">
          WSKAZÓWKI PO ZABIEGU
      </h2>
      <section class="hints__textContainer">
          <div class="hints__item">Nie zakładaj obcisłych rzeczy tuż po zabiegu. Pilnuj również aby 
              skóra nie ocierała się o skórę w miejscach styku..</div>
          <div class="hints__item">Unikaj kontaktu z wodą do pierwszego prysznica.</div>
          <div class="hints__item">Po określonym czasie zmyj dokładnie kolor wstępny przy użyciu 
              letniej wody, możesz użyć płynu do higieny intymnej. Nie używaj tłustych żeli pod 
              prysznic. Opalenizna rozwija się do 24h od pierwszego prysznica.
          </div>
          <div class="hints__item">
              Pamiętaj o delikatnym osuszaniu skóry po każdym prysznicu, a nie mocnym wycieraniu 
              się ręcznikiem.
          </div>
          <div class="hints__item">
              Nawilżaj skórę produktami lekkiej konsystencji, które nie posiadają w swoim składzie 
              tłustych składników. Polecamy naszą mgiełkę Mistifier, która przedłuży efekt.
          </div>
          <div class="hints__item">Unikaj aktywności fizycznej w dniu zabiegu oraz 24h po 
              pierwszym prysznicu.</div>
          <div class="hints__item">Jeśli chcesz cieszyć się opalenizną maksymalnie długo, 
              odpuść sobie kąpiele w wannie, saunę, basen czy masaż. Wszystkie te czynności 
              przyspieszą schodzenie opalenizny.</div>
          <div class="hints__item">Wykonaj peeling, kiedy będziesz chciała całkowicie pożegnać 
              się z opalenizną.
          </div>
      </section>
  </div>
</template>

<script>
export default {
    name: "Hints",
}
</script>

<style lang="scss" scoped>

.hints {
    $hints: &;
    background-color: #e7a5aa;
    color: #fff;
    padding-bottom: 80px;
    &__header {
        text-align: center;
        padding: 50px 0;
        font-size: 32px;
    }
    &__textContainer {
        padding: 0 27%;
    }
    &__item {
        font-size: 16px;
        position: relative;
        padding: 5px;
        margin-top: 5px;
        &.#{hints}__item--noListed {
            position: relative;
            left: -45px;
            &::before {
                content: none;
            }
        }
        &::before {
            content: "+";
            color: #e7a5aa;
            font-size: 30px;
            text-align: center;
            line-height: 1;
            position: absolute;
            left: -40px;
            top: 50%;
            transform: translateY(-50%);
            display: block;
            background-color: #fff;
            height: 30px;
            width: 30px;
            border-radius: 50%;
        }
    }
}

</style>