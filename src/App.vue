<template>
  <div id="app">
    <AppTitle />
    <AppJumbotron />
    <h2>Ciao, sono un'altro h2</h2>
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
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

a {
  text-decoration: none;
}
</style>
