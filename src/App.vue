<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <nav class="bg-black text-white flex items-center justify-between px-5 py-2 text-2xl">
      <div class="flex gap-4">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/shoppingcart">ShoppingCart</RouterLink>
        <RouterLink to="/shoppingcheck">ShoppingCheck</RouterLink>
        <RouterLink to="/buysuccess">BuySuccess</RouterLink>
      </div>
      <i class="fa-solid fa-cart-shopping relative">
        <span
          class="absolute flex bg-red-500 w-[20px] h-[20px] text-base rounded-full -top-2 -left-2 justify-center items-center">1</span>
      </i>
    </nav>
  </header>

  <RouterView />
</template>

<style scoped></style>
