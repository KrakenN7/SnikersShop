<script setup>
import Header from './components/Header.vue'
import CardList from './components/CardList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-10">
    <Drawer />
    <Header />

    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все кросовки</h2>

      <CardList />
    </div>
  </div>
</template>
