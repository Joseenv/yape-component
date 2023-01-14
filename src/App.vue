<script setup>
</script>

<template>
  <main>
    <img src="@/assets/banner-yapero-1.png" alt="Yape cover">
    <img src="./assets/qr.png" alt="QR">
    <div class="wrapper">
      <p>Para continuar, no olvides enviar tu comprobante de pago.</p>
      <a href="https://api.whatsapp.com/send?phone=+51932844629&text=Hola,%20he%20pagado%20mi%20producto.%20Quiero%20continuar%20con%20la%20compra.">
        Enviar comprobante
      </a>
    </div>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}
main {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100vh;
  gap: 64px;
  margin: 0 auto;
}
img {
  height: 320px;
  object-fit: cover;
}
.wrapper {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 20px;
}
p {
  font-size: 20px;
  font-weight: 500;
  color: #fff;
}
a{
  background-color: #fff;
  color: #6B4092;
  text-decoration: none;
  padding: 16px 32px;
  font-weight: 500;
  border-radius: 8px;  
}
</style>
