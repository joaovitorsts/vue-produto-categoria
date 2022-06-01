<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <RouterLink to="/">Home |</RouterLink>
    <RouterLink to="/products">Produtos |</RouterLink>
    <RouterLink to="/categories">Categorias |</RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
</template>

<style>
@import '@/assets/base.css';

#app {
  height: 100vh;
}

header {
  height: 10%;
  background-color: rgb(54, 54, 109);
  color: whitesmoke;
  font-size: 1.5em;
  display: flex;
}

main{
  padding: 10px;
}
</style>
