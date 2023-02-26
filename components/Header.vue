<script lang="ts" setup>
import { Icon } from "@iconify/vue";
</script>
<template>
  <div class="py-4 bg-gradient-to-tr from-purple-300 to-pink-200">
    <div class="flex justify-between max-w-7xl m-auto">
      <div class="font-moon ml-4 font-bold text-zinc-800 text-5xl">
        Algodão Doce
      </div>
      <div
        class="flex text-zinc-800 font-bold font-moon items-center gap-6 text-2xl"
      >
        <RouterLink to="/" class="hover:scale-125 hover:transition-transform"
          >Home</RouterLink
        >
        <RouterLink
          to="/build"
          class="hover:scale-125 hover:transition-transform"
          >Sobre mim</RouterLink
        >
        <RouterLink
          to="/resenha"
          class="hover:scale-125 hover:transition-transform"
          >Reseha</RouterLink
        >
        <div class="flex ml-20 gap-2">
          <Icon icon="ion:logo-instagram"></Icon>
          <Icon icon="tabler:brand-twitter"> </Icon>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped></style>
