<template>
  <div id="app">
    <AppTitle />
    <AppJumbotron />
    <h2>Ciao, sono un'altro h2</h2>
    <div class="primary-title">
      <h3>Questo è un titolo primario</h3>
    </div>
    <div class="secondary-title">
      <p>Un piccolo sottotitolo</p>
    </div>

    <div class="buttons-container">
      <a class="my-link" href="">Questo è il link</a>
      <button class="my-btn">Questo è il bottone</button>

      <button class="my-btn my-btn-primary">Primario</button>
    </div>
  </div>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppJumbotron from "./components/AppJumbotron.vue";

export default {
  name: "App",
  components: {
    AppTitle,
    AppJumbotron,
  },
};
</script>

<style lang="scss">
@import "./style/variables.scss";
@import "./style/mixins.scss";
@import "./style/common.scss";
@import "./style/general.scss";
</style>
