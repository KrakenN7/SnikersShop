<script setup>
import Header from './components/Header.vue'
import CardList from './components/CardList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-10">
    <!-- <Drawer /> -->
    <Header />

    <div class="p-10">
      <div class="flex justify-between items-center">
        <h2 class="text-3xl font-bold mb-8">Все кросовки</h2>

        <div class="flex gap-4">
          <select class="py-2 px-3 border rounded-md outline-none">
            <option>По названию</option>
            <option>По цене(дешевые)</option>
            <option>По цене(дорогие)</option>
          </select>

          <div class="relative">
            <img class="absolute left-4 top-2.5" src="/search.svg" />
            <input
              class="border rounded-md py-1.5 pl-11 pr-4 outline-none focus: border-gray-400"
              placeholder="Поиск..."
            />
          </div>
        </div>
      </div>

      <CardList />
    </div>
  </div>
</template>
