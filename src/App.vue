<script>
//Importo il components AppTitle e AppBanner
import AppTitle from "./components/AppTitle.vue";
import AppBanner from "./components/AppBanner.vue";

export default {
  //Components
  components: {
    AppTitle,
    AppBanner,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <!-- Titolo -->
  <AppTitle />

  <!-- Immagine -->
  <AppBanner />

</template>

<style></style>