<!-- Create un nuovo progetto utilizzando Vite, aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!" -->

<!-- Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron. -->





<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue"

export default {
  components: {
    AppTitle,
    AppHero

  },
}
</script>


<template>
  <AppTitle />
  <AppHero />
</template>




<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: yellow;
}
</style>