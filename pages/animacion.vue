<template>
  <div>
      <MainMenu/>
      <div class="caja">
        <h1>Animación</h1>
        <p>Para crear una pequeña animación del logo decidimos usar las similitudes que tiene con las tarjetas o cartas. Realizamos un pequeño story de las posibles variaciones de aniamción que puede tener:</p>
        <img src="../assets/img/story.jpg" alt="">
        <h2>Animación final</h2>
        <p>Este tipo de animación se usará para crear dinamismo en los diferentes video promocionales y para la recargas de pantallas en la versión web de cualquier dispositivo.</p>
        <video-player class="cabecera" src="video/onda cero logo.mp4"/>
        
      </div>

  </div>

</template>
<script>
import VideoPlayer from 'nuxt-video-player'

//require('nuxt-video-player/src/assets/css/main.css')

export default{
components: {
    VideoPlayer
}

}
</script>
<style lang="sass">
    .cabecera
        @apply mb-20 mt-10
        

</style>