<template>
  <div id="app">
    <div class="bg-wrapper">
      <img src="./assets/bansko-ski-map.jpg" alt="map of Bansko">
    </div>
    <div class="map-wrapper">
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

<style lang="scss">
  @mixin absolute-pinned {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
  }
  body {
    margin: 0;
    #app {
      position: relative;
      .bg-wrapper {
        @include absolute-pinned;
        img {
          width: 100%;
          height: auto;
        }
      }
      .map-wrapper {
        @include absolute-pinned;
      }
    }
  }
</style>
