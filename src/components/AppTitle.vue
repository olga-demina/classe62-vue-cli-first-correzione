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

<style scoped>
.title-link {
    color: green;
}
</style>