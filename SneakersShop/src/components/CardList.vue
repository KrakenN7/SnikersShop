<script setup>
import Card from './Card.vue'

difineProps({
  items: Array
})
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      v-for="item in items"
      :key="item.id"
      :title="item.title"
      :imageUrl="item.imageUrl"
      :price="item.price"
      :isA-dded="false"
      :onClickAdd="onClickAdd"
    />
    <!-- <Card />
    <Card />
    <Card />
    <Card />
    <Card /> -->
  </div>
</template>
