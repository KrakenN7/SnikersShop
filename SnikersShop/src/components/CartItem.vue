<script setup></script>

<template>
  <div class="flex item-center border border-slate-200 p-4 rounded-xl gap-4">
    <img class="w-16 h-16" :src="imageUrl" alt="Sneaker" />

    <div class="flex flex-col">
      <p>кросовки</p>
      <div class="flex justify-between mt-2">
        <b>12500 руб.</b>
        <img class="opacity-40 hover:opacity-100 cursor-pointer transition" src="/close.svg" />
      </div>
    </div>
  </div>
</template>
