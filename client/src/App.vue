<template>
  <q-layout view="hhh lpR fFf">
    <q-header elevated class="bg-white text-black">
      <q-toolbar class="q-pa-none-lg">
        <q-toolbar-title v-if="!$q.screen.xs">
          <q-btn round color="white" flat to="/">
            <q-avatar size="lg">
              <img src="/images/eco.png"/>
            </q-avatar>
          </q-btn>
          <q-chip class="bg-white" size="lg">

            <div class="text-h5">Ecoverse</div>
            <q-tooltip anchor="center right" self="center left" :offset="[10, 10]" transition-show="jump-left"
                       transition-hide="jump-right" class="text-body2">
              Проект переработки второсырья
            </q-tooltip>
          </q-chip>
        </q-toolbar-title>

        <q-tabs inline-label dense shrink stretch>
          <q-route-tab label="Контакты"/>

        </q-tabs>
      </q-toolbar>
    </q-header>
    <q-page-container class="container">
      <q-page>
        <router-view/>

      </q-page>
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
//
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap');

* {
  font-family: "Montserrat", sans-serif;
}


</style>
