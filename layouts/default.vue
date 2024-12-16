<script setup lang="ts">
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";
</script>

<template>
<div class="wrapper">
  <Header />
  <main>
    <slot /> <!-- Сюда будет вставляться содержимое страницы -->
  </main>
  <Footer />
</div>
</template>


<style scoped>
/* Устанавливаем минимальную высоту для всего layout */
html, body {
  margin: 0;
  padding: 0;
  height: 100%;
}

.wrapper {
  display: grid;
  grid-template-rows: auto 1fr auto; /* Три строки: Header, Main (растягивается), Footer */
  min-height: 100vh;
}
</style>
