<template>
  <div>
      <MainMenu/>
      <div class="caja">
       <h1>Inputs</h1>
       <p>Los campos de texto y los formularios son muy importates para la experiencia del usuario. Onda Cero da la posibilidad de registrarse y esto da una serie de beneficios como usuario. 
           Cuando inicias sesón o te registras nos podemos encontrar con una línea de texto que al clickar este sube y te permite rellenar el campo. Estos están disponibles en verde para contrastar con el blanco del fondo. 
    
       </p>
       <h2>Campo de texto</h2>
       <p>Este consta de un texto y una línea. Estso siempre aparecerán uno encima del otro y el único cambio que encontraremos en él es al activarlo, la etiqueta se mueve hacia arribar, se reduce la opacidad y deja espacio para que el usuario escriba.
       Los campos de texto que requieren ciertos formatos de datos, como números, direcciones de correo electrónico o contraseñas, se declaran en consecuencia </p>
       <img class="fondo" src="../assets/img/linea-input.jpg" alt="">
        <h2>Campo de texto de búsqueda</h2>
        <p> En un campo de búsqueda, combina un botón con un icono en su interior y un campo de texto estándar,donde se filtran los elementos por nombre. El botón si le haces click sin ingresar texto sirve paara que te lleve a una página de navegación donde se dividen los podcast por estilo. </p>
        <img src="../assets/img/INPUT-BTN2.jpg" alt="">
        <h3>Versión móvil</h3>
        <p>Para la versión móvil mantendríamos solo el botón con la misma función y al clickar se desplegaría el espacio de texto en la página de navegación.</p>
        <img class="fondo" src="../assets/img/INPUT-BTN.jpg" alt="">

     </div>

  </div>

</template>
<style lang="sass">
    .fondo
        @apply mt-10 mb-10 max-w-lg
    .espacios
        @apply mt-10 mb-10

    

</style>