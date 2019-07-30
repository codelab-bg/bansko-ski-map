<template>
  <div id="app" class="relative">
    <div class="absolute inset-0">
      <img class="w-full h-auto" src="./assets/bansko-ski-map.jpg" alt="map of Bansko">
    </div>
    <div class="absolute inset-0">
      <InteractiveMap/>
    </div>
  </div>
</template>

<script>
import InteractiveMap from './components/InteractiveMap.vue'

export default {
  name: 'app',
  components: {
    InteractiveMap
  }
}
</script>

<style src="./assets/tailwind.css"></style>
