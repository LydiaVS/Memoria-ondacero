<template>
<div>
    <MainMenu/>
    <div class="caja">
    <h1>Paleta de colores primaria</h1>
        <p>La paleta de color primaria  está compuesta de los mismos colores que coponen la marca con el objetivo de dar continuidad y unificación.
        El color principal es el blanco, que es acentuado por un nuevo verde definido, más brillante y claro que el original, haciendolo un verde rejuvenecido.
        La sensación que se quiere dar con la combinación de ambos colores es de negativo-positivo, enlazando el logotipo original de OndaCero
        </p>
        <img src="../assets/img/coloresp2.jpg" alt="">
        <img src="../assets/img/tintas1.jpg" alt=""></img>
    <h2>Recomendaciones de uso</h2>
    <p>En cuánto al verde:  no debe usarse en pesos bajos o en  texto corrido bajo ningún concepto puesto que su accesibilidad es baja tanto sobre fondos oscuros como claros.
    Para un uso adecuado de este color en texto se debe aplicar en cuerpos grandes y pesos superiores al regular ( H1, H2, H3).
    Puede usarse como relleno de superficies amplias pero conservando la proporción de colores indicada.
    <br>En cuánto al blanco:  debe usarse como color de relleno para cards. Si se usa en texto, debe ser siempre sobre verde con un peso superior al regular para incrementar la legibilidad.</p>
    <h1>Paleta de colores secundaria</h1>
    <p>La paleta de color secundaria está compuesta por un verde comformado por una proporción de blanco mucho mayor que el verde principal y por un azul muy oscuro que no llega a ser negro. Ambos colores han sido escogidos con el objetivo de rejuvenecer y aportar vitalidad a la marca.</p>
    <img src="../assets/img/colores2s.jpg" alt="">
    <img src="../assets/img/tintas2.jpg" alt="">
    <h2>Recomendaciones de uso</h2>
    <p>En cuánto al verde claro:  debe usarse únicamente en el relleno de botones, nunca en texto. <br>
En cuánto al azul oscuro: Puede usarse en todos los textos pero siempre sobre fondos blancos para conseguir una buena accesibilidad.</p>
    <h2>Paleta de color funcional</h2>
    <p>El color funcional representa un mensaje claro, así como el estado de algunos componentes y alerts.
Representan fallo, error, éxito, link... La selección del color funcional debe cumplir con la comprensión básica del color por parte del usuario.  Para ello nos hemos basado en la plaeta de color funcional de Ant Design</p>
    <div class="funcional">
        <img src="../assets/img/funcional.jpg" alt="">
        <img src="../assets/img/funcional2.jpg" alt="">
    </div>

</div>

</div>

</template>
<style lang="sass">
    .funcional
        @apply mb-12 ml-20
    .caja
        img
            @apply max-w-lg
</style>