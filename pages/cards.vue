<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Cards</h1>
        <p>Las cards contienen elementos de los podcast, todo ellos tendrán como mínimo el nombre del programa y el de su presentador. Todo comparten el mismo estilo, color,...Pero de manera opcional y dependiendo de su función se suele incluir un botón de segui, favorito o eliminar en el caso de que estemos hablando de las cards guardadas en diferentes carpetas.</p>
        <h2>Componente base</h2>
        <p> Como he mecionado las cards comparten los mismos estilos base, es por ello que para seguir una coherencia visual, todos ellos estarán en un componente sólido con fondo blanco, esquinas redondeadas y una ligera sombra de fondo para que no sea totalmente blanca la página.</p>
        <img src="../assets/img/card-base.jpg" alt="">
        <p>Y con la estructura tenemos algo parecido, nos podemos encontrar dos tipos los de botón y los sin botón: </p>
        <img class="fondo" src="../assets/img/card-fondo.jpg" alt="">
        <img class="fondo" src="../assets/img/card-fondo2.jpg" alt="">
        <h2>Componente con botón</h2>
        <h3>Carrousel</h3>
        <p>Este componente es de los más llamativos del sistema, ya que es el que más ocupa en nuestras pantallas, este caso este componente tiene un botón en su interior para seguir al podcast.
          <br> En la imagen podemos encontrar tanto la version pc como la versión responsive del móvil.En las del móvil hemos intenato mantener una relacion de 4px y basado en sus múltiplos.
        </p>
        <img src="../assets/img/card-carrousel.jpg" alt="">
        <h3>Card + icon</h3>
        <p>En este caso solo lo mantedríamos en la versión móvil ya que al tener todo tamaños más reducidos este tipo de cars estarían acompañados de un botón de seguir con la verisón icon. O de borrar dependiendo de su función.</p>
        <img class="fondo" src="../assets/img/card-podcast.jpg" alt="">
        <h3>Card perfil</h3>
        <p>Para el perfil de los podcast hemos seguido la misma línea estética pero adaptando la forma a las imágenes de los programas para variar y que no se convierta en un sistema muy repetitivo. 
         </p>
         <h3>Versión pc</h3>
         <img src="../assets/img/card-perfil-pc.jpg" alt="">
         <h3>Versión móvil</h3>
         <img class="fondo" src="../assets/img/card-perfil-phone.jpg" alt="">

     </div>

  </div>

</template>
<style lang="sass">
  .fondo
    @apply max-w-lg mb-10 mt-10
    

</style>