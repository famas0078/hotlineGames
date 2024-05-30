
<template>
  <div class="wrapper-yandex-map ms-3">
    <div id="map">
        <iframe 
        src="https://yandex.ru/map-widget/v1/?um=constructor%3A07c9bfb252a94bd4ff548cc0c3d844a78572f4b4a75e5f6d2465c4b6cc5f3860&amp;source=constructor" 
        height="400" 
        class="map"
        frameborder="0">
        </iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Map',
  mounted() {
    this.myMap = new ymaps.Map('map', {
      center: [55.75, 37.57],
      zoom: 10
    });
  }
};
</script>

<style scoped>
#map {
  width: 100%;
  height: 400px;
}
</style>
