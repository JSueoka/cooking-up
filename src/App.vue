<script lang="ts">
import Banner from "./components/Banner.vue";
import ConteudoPrincipal from "./components/ConteudoPrincipal.vue";
import Rodape from "./components/Rodape.vue";

  
export default {
  components: {Banner, ConteudoPrincipal, Rodape}
  // Isso foi feito pois o js permite deixar apenas o valor quando valor = componente
  // components: { Banner: Banner }
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
  <Rodape />
</template>