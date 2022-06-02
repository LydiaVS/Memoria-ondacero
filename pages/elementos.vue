<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Elementos Básicos</h1>
        <p>A continuación se muestran las variaciones del logotipo, tanto cromáticamente como de tamaño.</p>
        <img class="max" src="../assets/img/Logo.png" alt="">
        <h2>Variaciones cromáticas</h2>
        <img class="max" src="../assets/img/logov2.jpg" alt="">
        <img class="max" src="../assets/img/logov3.jpg" alt="">
        <h2>Versión en negativo</h2>
        <img class="max" src="../assets/img/logonegro.jpg" alt="">
        <h2>Tamaños</h2>
        <img class="max" src="../assets/img/alturas.jpg" alt="">

      </div>

  </div>

</template>
<style lang="sass">
  .caja
    .max
      @apply max-w-sm mb-10 mt-10
</style>