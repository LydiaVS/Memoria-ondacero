<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Elementos Básicos</h1>
        <p>A continuación se muestran las variaciones del logotipo, tanto cromáticamente como de tamaño.</p>
        <img class="max" src="../assets/img/Logo.png" alt="">
        <h2>Variaciones cromáticas</h2>
        <p>Diferentes versiones del logo, según el fondo del color, estos colores son los mismos empleados duarante todo el sistema de diseño, así no habría ninguno equivocación sobre que color alegir según el fondo.</p>
        <img class="max" src="../assets/img/logov2.jpg" alt="">
        <img class="max" src="../assets/img/logov3.jpg" alt="">
        <h2>Versión en negativo</h2>
        <p>Estas versiones en positivo y negativo se usarán en elementos impresos en blanco y negro, por ejemplo facturas, cartas …</p>
        <img class="max" src="../assets/img/logonegro.jpg" alt="">
        <h2>Tamaños</h2>
        <p>Estos son los tamaños mínimos tanto para pantallas como para impresión, si se llegrá a reducir mucho más el tamaño, este sería totalmente ilegible e identificable.</p>
        <img class="max" src="../assets/img/alturas.jpg" alt="">

      </div>

  </div>

</template>
<style lang="sass">
  .caja
    .max
      @apply max-w-sm mb-10 mt-10
</style>