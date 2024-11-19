<template>
<header>
  <nav>
    <a class = "link-main" href="/">Главная</a> | <a class = "link-about" href="/about">О проекте</a>
  </nav>
</header>
</template>

<script setup>
</script>

<style scoped>
header {
  background-color: #ffcc00;
padding: 10px;
text-align: center;
}
nav a {
margin: 0 10px;
text-decoration: none;
color: #333;
}
nav a:hover {
text-decoration: underline;
}
.link-main {
  color: red;
}
.link-about {
  color: green;
}
</style>
