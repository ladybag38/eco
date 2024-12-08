<script setup lang="ts">


</script>

<template>
<div class="eco-container">
      <div  >
          <img  src="/images/main.png"  style="width: 350px; height:  350px"/>
      </div>
  <div>
    <span class="text-h3 " >Ecoverse - сортируй просто!</span>
    <br>
     <br>
    <span class="text-h5">
      Инновационная цифровая экосистема, решает проблемы: </span><br>

    <ul class="text-h6">
  <li>низкой степени переработки бытовых отходов</li>
  <li>неразвитость культуры раздельного сбора и сортировки мусора</li>
  <li>привлечение и удержания клиентов в малом и среднем бизнесе</li>
</ul>

  </div>
  <div>
    <q-card class="my-card">
      <q-card-section>
        <div class="text-h6">справка</div>
        <div class="text-subtitle2">


        </div>
      </q-card-section>

      <q-separator />

      <q-card-actions vertical>
        <q-btn flat>Action 1</q-btn>
        <q-btn flat>Action 2</q-btn>
      </q-card-actions>
    </q-card>
    <q-card class="q-mr-lg">
<span class="text-body1">Продукт проекта представляет собой комплексный IT продукт, направленный на улучшение экологии, повышение качества жизни граждан благодаря системе мотивации. Пользователи Ecoverse будут получать цифровые бонусы за раздельный сбор мусора и выполнение определенных задач в приложении, обмениваемые на продукты компаний-партнеров: скидки, бонусы, образовательные программы и товарные наборы. Также планируется использование блокчейна и работа с криптовалютами. Участниками-партнерами экосистемы станут малый и средний бизнес, пользователи приложения, а также компании, занимающиеся переработкой мусорных отходов.</span>
</q-card>
  </div>

</div>

</template>

<style scoped lang="scss">

.eco-container {
  display: grid;
  grid-template-columns: 400px repeat(1, auto) 500px;
  background: white;
  margin-top: 150px;
  margin-left: 50px;
}

ul {
    list-style-type: "\2705";
}
</style>
