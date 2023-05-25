<script setup>
import cabecalho from "./components/cabecalho.vue";
import corpo from "./components/corpo.vue";
</script>

<template>
  <NavBar></NavBar>
  <header>
    <cabecalho />
    <corpo />
  </header>

  <main></main>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}
header {
  line-height: 1.5;
}
</style>
