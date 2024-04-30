<script>
export default {
  data() {
    return {
      image : "picsum.jpg",
      altText : "Dev" 
    }
  },
  methods : {
    getImagePath(image){
        return new URL(`../assets/${image}`, import.meta.url).href;
    }
  }
}
</script>

<template>
    <!-- Immagine con path dinamico e testo alternativo dinamico -->
    <img :src="getImagePath(image)" :alt="altText">

</template>

<style>
img {
    width: 300px;
    height: 200px;
    aspect-ratio: 1;
}
</style>