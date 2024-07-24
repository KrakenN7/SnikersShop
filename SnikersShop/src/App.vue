<script setup>
import MyHello from './components/MyHello.vue'
</script>

<template>
  <MyHello title="Кросовки Puma" :price="9500" />
  <MyHello />
  <MyHello />
  <MyHello />
</template>
