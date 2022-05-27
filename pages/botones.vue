<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Botones</h1>
        <p>Hemos agregado nuevos componentes para garantizar una nueva apariencia a la web y que sea más intuitivo para los usuarios. <br>
        Los botones se utilizan para generar diferentes acciones como: navegación, añadir usuarios, favoritos,...</p>
        <p>Los botones utilizan la misma gama cromática empleada durante todo el sistema, verde o blanco.</p>
        <p>El tamaño de los botones dependerá del dispositivo en el que se esté viendo, en caso del móvil el tamaño más pequeño que nos encontramos es de 40px y siempre manteniendo el múltiplo de 4.</p>
        <h2>Botones con texto</h2>
        <h3>Botón primario</h3>
        <p>El botón principal se usa para la acción más importante de una página</p>
        <img class="btn-ic" src="../assets/img/btnprimario.jpg" alt="">
        <h3>Botón secundario</h3>
        <p>El botón secundario cambia ligeramnete el tamaño para mantener una jerarquía en la web. Acciones subordinadas</p>
        <img class="btn-ic" src="../assets/img/btnsecundario .jpg" alt="">
        <h3>Botón de texto</h3>
        <p>Se aplica de manera sutil para llevar a diferentes páginas cuando se realiza una acción, por ejemplo, cuando salta un alert y quieres ir a la página donde se ha descargado el programa</p>
        <img class="btn-ic" src="../assets/img/btntxt.jpg" alt="">
        <h2>Botones con iconos</h2>
        <p>Los botones con iconos del sistema se utilizan para activar acciones clásicas del sistema(guardar, descargar, compartir...)Siempre irán acompñados de un borde redondeado.</p>
        <img class="btn-ic" src="../assets/img/btnicon.jpg" alt="">
        <h2>Botones de navegación: iconos flotantes y texto</h2>
        <p>Este en concreto son botones que solo podemos encontrar en la barra de naegación de los menus de móviles. Estos para una mejor comprensión se incluye el icono y un texto para resaltar a lo que se quiere referir. <br>
        Tiene dos versiones, esto se utliza para que el usuario no se pierda y sea consciente de la página en la que se encuentra.
        </p>
        <img class="btn-ic" src="../assets/img/btnnav.jpg" alt="">
        
      </div>

  </div>

</template>
<style lang="sass">
    .btn-ic
        @apply max-w-xs pb-8 pt-4

</style>