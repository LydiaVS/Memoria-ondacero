<template>
  <div class="side-bar">
    <div class="logo"><Logo/></div>
    <div class="said-main">
      <ul class="main">
        <li  class="visible" id="cero">
           <NuxtLink to="/apariencia">Apariencia de Marca </NuxtLink>
        </li>
        <li @click="panelIsOpen = !panelIsOpen" class="visible" id="open" >
          Marca
          <ul class="panel" v-show="panelIsOpen">
            <li class="invisibl" > <NuxtLink to="/elementos">Elementos Básicos </NuxtLink></li>
            <li class="invisibl" ><NuxtLink to="/colores2">Colores </NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/tipo">Tipografía </NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/animacion">Animación</NuxtLink></li>
          </ul>
        </li>
        <li @click="panelIs2Open = !panelIs2Open" class="visible" >Estilos identidad visual
          <ul class="panel" v-show="panelIs2Open">
            <li class="invisibl" > <NuxtLink to="/tipo2">Tipografía</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/colores2">Paleta Colores</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/estilo">Estilo gráfico</NuxtLink></li>
            <li class="invisibl"><NuxtLink to="/grid">Grid</NuxtLink></li>

          </ul>
        </li>
        <li @click="panelIs3Open = !panelIs3Open" class="visible">Componentes
          <ul class="panel" v-show="panelIs3Open">
            <li class="invisibl" > <NuxtLink to="/botones">Botones</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/mosca">Navegación</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/cabecera">Cards</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/rotulos">Reproductor</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/cortinillas">Alerts</NuxtLink></li>
            <li class="invisibl" > <NuxtLink to="/cortinillas">Inputs</NuxtLink></li>
          </ul>
        </li>
      </ul>
    </div>


  </div>
</template>
<script>
    export default {
        data(){
            return{
                panelIsOpen: false,
                panelIs2Open: false,
                panelIs3Open: false
            }
        }
    
    }
</script>

<style lang="sass">

  @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;600;700;800;900&display=swap')
  .side-bar
    background-color: $blanco
    width: 40vh
    height: 100vh
    position: fixed
    box-shadow: $sombra1
    ul 
      font-family: 'Nunito', sans-serif
      font-size: 12pt
      font-style: 400
      color: $azul
      li
        font-family: 'Nunito', sans-serif
        font-size: 12pt
        font-style: 400
        color: $azul
        @apply ml-11 mt-8
        &:hover
          color: $verde
          cursor: pointer
          
  #cero
    margin-top: 0
</style>
