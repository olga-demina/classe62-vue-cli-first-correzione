<template>
  <div>
      <h1>{{ titleText }}</h1>
      <a class="title-link" href="">Ciao</a>
  </div>
</template>

<script>
export default {
    name: "AppTitle",
    data: function() {
        return {
            titleText: 'Ciao mondo'
        }
    }
}
</script>

<style scoped lang="scss">
@import "../style/variables.scss";

.title-link {
    color: $brand-primary-color;
    background-color: $brand-secondary-color;
}
</style>