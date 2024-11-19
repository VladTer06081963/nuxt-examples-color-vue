<script setup >
  const about = "About";
  const project = "О проекте ";
</script>

<template>
  <div class="wrapper">
    <main>
      <h1><span class = "project">{{project}}</span> <span class = "about">{{about}}</span></h1>
      <p>Это пример страницы с контентом.</p>
    </main>
  </div>
</template>

<style scoped>
/* Только для about.vue */
html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
}
.about {
  color: red;
}
.project {
  color: blue;
}
p {
  color: purple
}

</style>

<!-- <script setup>
</script>

<template>
<div>
  <h1>О проекте</h1>
  <p>Это пример проекта с использованием Nuxt-3</p>
</div>
</template> -->
