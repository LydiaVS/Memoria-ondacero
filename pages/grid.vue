<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Elementos Básicos</h1>
        <p>El sistema de rejillas de la nueva identidad de OndaCero está compuesto de la superposición de una grid de  4 px y una serie de columnas y filas que varían según el dispositivo con la intención de hacer el sistema responsive.</p>
        <h2>Recomendaciones de uso</h2>
        <h3>En el caso del móvil</h3>
        <p>las columnas son 4 y las filas 8, ambas casos con un medianil de 20 px, un ancho de 65px (columnas) y alto de 65px (filas).
        La grid de móvil debe aplicarse para dispositivos con un ancho máximo de 480px.</p>
        <img src="../assets/img/grid-mov.jpg" alt="">
        
        <h3>En el caso del Pc: </h3>
        <p>tanto las columnas como las filas son 10, ambos casos con un medianil de 30px, los anchos y altos son automáticos.
        La grid de Pc debe aplicarse para dispositivos con un ancho máximo de 992 px</p>
        <img class="pc" src="../assets/img/grid-pc.jpg" alt="">
        <h3>Breakpoints de ejemplo para media queries:</h3>
        <p>
         móvil <br>
        @media only screen and (min-width : 480px){}  <br>

         PC  <br>
        @media only screen and (min-width : 992px){}</p></div>


  </div>

</template>
<style lang="sass">
    .pc
        @apply max-w-2xl
</style>