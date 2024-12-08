<script setup lang="ts">


</script>

<template>
  <div style="margin-top: 100px; justify-content: center; display: flex">
    <span class="text-h3 for_text " style="font-style: italic; " >Ecoverse</span>
    <span class="text-h3 for_text " > - сортируй просто!</span>
  </div>
<div class="eco-container">
      <div  >
          <img  src="/images/main.png"  style="width: 300px; height:  300px"/>
      </div>
  <div>

    <br>
     <br>
    <span class="text-h5 for_text">
      Инновационная цифровая экосистема, решает проблемы: </span><br>

    <ul class="text-h5  for_text">
  <li>низкой степени переработки бытовых отходов</li>
  <li>неразвитость культуры раздельного сбора и сортировки мусора</li>
  <li>привлечение и удержания клиентов в малом и среднем бизнесе</li>
</ul>

  </div>
  <div>


  </div>

</div>

   <div style="margin-top: 10px; justify-content: center; display: flex">
    <span class="text-h3 for_text " > Что нужно делать? </span>
  </div>

</template>

<style scoped lang="scss">

.eco-container {
  display: grid;
  grid-template-columns:  repeat(2, auto) 500px;
  background: $green-3;
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
}
.for_text2{
  font-family: "Sans Serif Collection";
}
</style>
