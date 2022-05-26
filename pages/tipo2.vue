<template>
<div>
    <MainMenu/>
    <div class="caja">
    <h1>Tipografía</h1>
        <p>La tipografía escogida para el sistema de diseño es Nunito, una sans serif con bordes redondeados que la hacen amigable y cercana.
        </p>
        <img class="tipos" src="../assets/img/tipo.jpg" alt="">
    <h1>Escala tipográfica</h1>
    <h2>Los tamaños</h2>
    <p>   
        La constante en la escala tipográfica es de un incremento de 1,250 (Major Third).
        El tamaño más pequeño permitido es 15 puntos en PC y X en móvil.
        El límite de tamaño superior es 72 pt en Pc y X en móvil.
        Estas escalas tipográficas de ejemplo utilizan la fuente Nunito para todos los titulares, cuerpo y subtítulos en dispositivos móviles y Pc.
        La jerarquía se comunica 
        a través de diferencias en el peso de la fuente (Black, bold, Regular) y tamaño.</p>
    <img class="tipo" src="../assets/img/escala pc.jpg" alt="">
</div>
</div>

</template>
<style lang="sass">
    .tipos
        @apply w-60
    .tipo
        @apply max-w-5xl pb-12

</style>