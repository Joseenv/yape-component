<script setup>
</script>

<template>
  <main>
    <img src="./assets/yape-cover.png" alt="Yape cover">
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  main {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
  }
  img {
    height: 720px;
    object-fit: cover;
  }
}
</style>
