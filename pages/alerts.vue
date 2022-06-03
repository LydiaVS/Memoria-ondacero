<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Alerts</h1>
        <p>Una alerta muestra un mensaje breve e importante de una manera que atrae la atención del usuario sin interrumpir la tarea del usuario.
           <br> Este mensaje aparecerá en diferentes ocasiones:<br> 
           - Cuando registres un nuevo correo, con el cual deberías confirmar usuario <br> 
           - Cuando sigas a una cuenta <br> 
           - Cuando des like/fav a un podcast <br> 
           - Cuando descargues un programa
        
        </p>
        <img  class="fondo" src="../assets/img/alerts.jpg" alt="">
        <h2> Base alert</h2>
        <p>La base del alert se basa en la misma de la barra de reporducción y se ajusta de la misma manera en la barra inferior. Este serái una forma sólida y por ello no se le añadiría sombra al elemento.</p>
        <img class="espacio" src="../assets/img/base-alert.jpg" alt="">
        <h2>Texto + icon </h2>
        <p>Este estaría basado en una serie de textos que describan brevemente la acción que has realizado para que salga ese mensaje. Junto a este un icon que represente esa acción y sea más intuitiva y rápido a la hora de leer. Mucho de ellos tendran otro botón que cierre el mensaje o te lleve a l página modificada por la acción realizada. Esto por ejemplo en la confirmación del email no a aparecería.</p>
        <img class="espacio" src="../assets/img/alerts-text.jpg" alt="">
        <p>Aquí los textos montados con su fondo</p>
        <img class="espacio" src="../assets/img/alerts-phone.jpg" alt="">



     </div>

  </div>

</template>
<style lang="sass">
    .espacio
        @apply mb-10 mt-10
    .fondo
        @apply max-w-lg mb-10 mt-10
        

    

</style>