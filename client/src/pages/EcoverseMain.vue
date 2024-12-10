<script setup lang="ts">


</script>

<template>
  <div style="margin-top: 100px; justify-content: center; display: flex">
    <span class="text-h3 for_text_green " style="font-style: italic; " >Ecoverse</span>
    <span class="text-h3 for_text_green " > - сортируй просто!</span>
  </div>
<div class="eco-container">
      <div>
          <img  src="/images/main.png"  style="width: 300px; height:  300px"/>
      </div>
  <div>
    <br>
    <br>
    <span class="text-h5 for_text " >Наша система решит проблемы: </span><br>
    <ul class="text-h5  for_text">
        <li>низкой степени переработки бытовых отходов</li> <br>
        <li>неразвитость культуры раздельного сбора и сортировки мусора</li> <br>
        <li>привлечение и удержания клиентов в малом и среднем бизнесе</li> <br>
    </ul>
  </div>
  <div>
          <img  src="/images/love.png"  style="width: 300px; height:  300px"/>
      </div>
</div>
   <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h3 for_text_green " > Что нужно делать? </span>
  </div>
  <div class="eco-container">
    <div>
      <img  src="/images/qr.png"  style="width: 300px; height:  300px"/>
    </div>
    <div class="for_card_text" >
      <span class="text-h4 for_text">1</span>
      <span class="text-h5 for_text" > Сортируй мусор, помечая пакеты QR-наклейкой, теперь это твой пакет!</span>
    </div>
     <div>
      <img  src="/images/garbage.png"  style="width: 300px; height:  300px"/>
    </div>
    <div class="for_card_text">
      <span class="text-h4 for_text">2</span>
      <span class="text-h5 for_text"> Относи мусор в пункт приёма</span>
    </div>
     <div>
      <img  src="/images/money.png"  style="width: 300px; height:  300px"/>
    </div>
    <div class="for_card_text">
      <span class="text-h4 for_text">3</span>
      <span class="text-h5 for_text"> Получай бонусы и обменивай их на реальные призы</span>
    </div>
  </div>
   <div style="margin-top: 10px; justify-content: center; display: flex">
   <span class="text-h3 for_text_green " > Как с нами связаться? </span>
   </div>
  <div class="eco-container">
    <div>
      <img  src="/images/leader.png"  style="width: 300px; height:  300px"/>
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
  grid-template-columns:  repeat(2, auto) 500px;
  background: $green-5;
  margin-top: 10px;
  justify-content: center;
  display: flex;
 padding: 50px;

}

ul {
    list-style-type: "\2705";
}
.for_text{
  font-family: "Comic Sans MS";
  color: white;
}
.for_text_green{
  font-family: "Comic Sans MS";
  color: $green-8;
}
.for_text2{
  font-family: "Sans Serif Collection";
}
.for_card_text{
  padding-top: 100px
}
</style>
