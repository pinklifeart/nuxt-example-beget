<script setup lang="ts">
const version = 2 + 1
</script>

<template>

  <div class="h-screen place-content-center flex bg-zinc-300 font-sans">
    <div class="p-6 max-w-xl mx-auto bg-white rounded-xl shadow-lg flex items-center space-x-6 m-auto">
    <div class="shrink-0">
      <img class="h-12 w-24" src="/img/logo.png" alt="Beget Logo">
    </div>
    <div>
      <h1 class="font-medium text-black text-xl">Привет, это Nuxt {{ version }}!</h1>
      <p class="text-slate-500">У тебя получилось, молодец :)</p>
      <p class="text-slate-500">Рекомендую ознакомиться с <a class="text-red-300 hover:text-red-500" target="_blank" href="https://nuxt.com/docs/getting-started/introduction">документацией Nuxt</a>, если это твой первый проект на данном фреймворке.</p>
    </div>
  </div>


      
  </div>
</template>


