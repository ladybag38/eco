<script setup lang="ts">


import {useQuasar} from "quasar";
import {ref} from "vue";

const $q = useQuasar()
const slide = ref()
const steps = ref()
const autoplay = ref()
</script>

<template>

  <div style="">
    <div class="q-gutter-lg ">
      <div class="eco-container-new bg-grey-3 text-white shadow-1 rounded-borders">
        <div class="column no-wrap flex-center">
          <span class="text-h1 for_text_black  " style="font-weight: bold">ECOVERSE</span> <br>
          <span class="text-h3 for_text_black column  flex-center">сортируй просто</span>
          <q-btn class="q-mt-lg for_text_black text-h6" color="light-green-10" no-caps label="Подробнее"/>
        </div>
        <div></div>
        <div class="q-ml-lg">
          <img src="/images/least.png" style="width: 800px; height:  350px"/>
        </div>
      </div>

    </div>
  </div>
  <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h6 for_text_green ">Мы хотим рассказать о себе</span> <br>
  </div>
  <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h4 for_text_black" style="font-weight: bold">Наша задача состоит в следующем</span>
  </div>
  <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h6 for_text_black">Вместе мы можем сделать мир чище и прекраснее: сортируй мусор, чтобы сохранить природу для будущих поколений!</span>
  </div>

  <!--  карусель-->
  <div class="q-gutter-lg ">
    <q-carousel
      v-model="steps"
      transition-prev="stepone"
      transition-next="stepone"
      swipeable
      animated
      control-color="light-green-10"
      navigation
      thumbnails
      autoplay
      padding
      arrows
      height="350px"
      class="bg-grey-3 text-white shadow-1 rounded-borders"
    >

      <q-carousel-slide name="stepone">
        <div class="eco_card">
          <div class="flex justify-center items-center">
            <q-btn
              style="width: 100px; height:  100px;"
              color="light-green-10"
              round
              outline
              size="30px"
              icon="mdi-numeric-1"
            />
          </div>
          <span class="text-h6 for_text flex justify-center items-center" style="width: 350px; padding: 50px"> Cортируй отходы, помечая мусорные пакеты QR-наклейкой, теперь это твой пакет!</span>
          <img src="/images/qr.png" style="width: 250px; height:  250px;"/>
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="steptwo">
        <div class="eco_card">
          <div class="flex justify-center items-center">
            <q-btn
              style="width: 100px; height:  100px;"
              color="light-green-10"
              round
              outline
              size="30px"
              icon="mdi-numeric-2"
            />
          </div>
          <span class="text-h6 for_text flex justify-center items-center" style="width: 350px; padding: 50px">Относи мусор в пункт приёма, где его с радостью примут наши волонтёры </span>
          <img src="/images/garbage.png" style="width: 250px; height:  250px"/>
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="stepthree">
        <div class="eco_card">
          <div class="flex justify-center items-center">
            <q-btn
              style="width: 100px; height:  100px;"
              color="light-green-10"
              round
              outline
              size="30px"
              icon="mdi-numeric-3"
            />
          </div>
          <span class="text-h6 for_text justify-center items-center" style="width: 350px; padding: 50px">Получай бонусы в приложении и обменивай их на реальные призы</span>
          <img src="/images/sale.png" style="width: 250px; height:  250px ; "/><br>
        </div>
      </q-carousel-slide>
    </q-carousel>
  </div>
  <div class="eco-container">
  </div>
  <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h3 for_text_green "> Как с нами связаться? </span>
  </div>
  <div class="eco-container">
    <div>
      <img src="/images/leader.png" style="width: 300px; height:  300px"/>
    </div>
    <div class="for_card_text">
      <span class="text-h4 for_text">Главный хомяк</span><br>
      <span class="text-h5 for_text">Строков Вячеслав</span><br>
      <span class="text-h5 for_text">8 800 555 35 35</span>
    </div>
  </div>
</template>

<style scoped lang="scss">

.eco-container {
  display: grid;
  grid-template-columns:   repeat(2, 500px);
  // background: linear-gradient(90deg, $green-6, $green-7, $green-8, $green-9);
  margin-top: 10px;
  justify-content: center;
  padding: 50px;

}

.eco_card {
  display: grid;
  grid-template-columns:  repeat(3, auto);
  // background: linear-gradient(90deg, $green-6, $green-7, $green-8, $green-9);
  justify-content: center;
  padding: 20px;
  margin-left: 50px;
}

.eco-container-new {
  display: grid;
  grid-template-columns:  auto 60px auto;
  background: $grey-3;
  padding-top: 30px;
  justify-content: center;
  padding-left: 50px;
  height: 450px;
}

ul {
  list-style-type: "\2705";
}

.for_text {
  color: black;
}

.for_text_green {
  color: $light-green-10;
}

.for_text_black {
  color: $grey-10;
}

.for_text2 {
}

.for_card_text {
  padding-top: 100px
}
</style>
