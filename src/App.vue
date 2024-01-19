<template>
  <NavBar/>
  <GalleryPhotos/>
  <StartQuote/>
</template>

<script>
import NavBar from './components/NavBar.vue'
import StartQuote from './components/home/StartQuote.vue'
import GalleryPhotos from './components/home/GalleryPhotos.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    StartQuote,
    GalleryPhotos
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
