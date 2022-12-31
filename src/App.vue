<script setup>
</script>

<template>
  <main>
    <img src="@/assets/banner-yapero-1.png" alt="Yape cover">
    <img src="./assets/qr.png" alt="QR">
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
    gap: 64px;
  }
  img {
    height: 320px;
    object-fit: cover;
  }
}
</style>
