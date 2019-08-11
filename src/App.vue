<template>
  <div id="app" class="relative font-serif lg:max-w-4xl mx-auto">
    <div class="absolute inset-0">
      <img class="w-full h-auto" src="./assets/bg_bansko-ski-map.jpg" alt="map of Bansko">
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
