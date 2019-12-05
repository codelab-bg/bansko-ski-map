<template>
  <div class="relative">
    <div class="p-4 lg:py-8">
      <h1 class="text-center leading-tight md:leading-normal text-3xl">Открий проблемните ски писти в Банско</h1>
      <p class="text-center text-xl mt-4">Кликни върху съоръженията и научи повече</p>
    </div>
    <div id="app" class="relative font-serif lg:max-w-4xl mx-auto">
      <div class="absolute inset-0">
        <img class="w-full h-auto" src="./assets/bg_bansko-ski-map.jpg" alt="map of Bansko">
      </div>
      <div class="absolute inset-0">
        <InteractiveMap/>
      </div>
    </div>
    <div class="absolute right-0 top-0 w-6 h-auto mt-40 mr-12 hidden lg:block">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 72.09 164.08"><path d="M32.27.24c15.33-1.86 31 7.49 36.9 21.73a38.12 38.12 0 012.89 16.08c-.1 12 .12 24.06-.11 36.09-.66 15.93-13.27 30.29-28.92 33.18-14.94 3.24-31.25-4.48-38.47-17.89a37.92 37.92 0 01-4.5-20.38c.1-11.7-.11-23.39.1-35.08C.8 16.88 15.28 1.79 32.29.27m-2.72 8.59C17.66 11.53 8.34 22.75 8.12 34.99s0 24.74 0 37.12a28.004 28.004 0 1056-1c-.11-12.58.22-25.16-.17-37.73-1.16-16.33-18.57-28.87-34.4-24.55z"/><path d="M34.44 22.37A4 4 0 0140 25.95a122.73 122.73 0 01-.11 13c-.53 3.63-6.13 4.17-7.46.78-.79-3.5-.22-7.14-.4-10.7.03-2.35-.28-5.6 2.41-6.66zM16.81 124.22c-2.82-3.23 2.3-8.27 5.48-5.38 4.79 4.31 9.12 9.13 13.78 13.59 3.89-3.9 7.8-7.78 11.65-11.72 1.41-1.3 3-3.18 5.13-2.6 2.94.51 4.37 4.64 2 6.66-4.52 4.82-9.39 9.32-14 14.1-1.24 1.12-2.35 2.55-4 3.09-2.44.64-4.1-1.65-5.68-3.07-4.65-4.99-9.79-9.57-14.36-14.67z"/><path d="M16.06 144.05c-.17-3 3.86-5.34 6.21-3.24 4.82 4.31 9.15 9.13 13.81 13.61 4.66-4.48 9-9.31 13.81-13.62 3.2-2.84 8.26 2.28 5.38 5.46-4.21 4.74-9 9-13.35 13.57-1.56 1.47-2.94 3.31-5 4.13-2.19.59-3.79-1.29-5.21-2.61-4.45-4.55-9-9-13.48-13.5-.95-1.09-2.28-2.19-2.17-3.8z"/></svg>
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
