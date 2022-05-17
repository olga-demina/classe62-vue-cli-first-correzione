<template>
  <div class="jumbotron-container">
    <img src="../assets/img/milano.jpg" alt="" />
    <h2>Che bella Milano</h2>
    <a href="">Clicca per sapere di più</a>
  </div>
  <!-- <div class="jumbotron-img"> -->

  <!-- </div> -->
</template>

<script>
export default {
  name: "AppJumbotron",
};
</script>

<style scoped>
.jumbotron-container {
    position: relative;
}

h2 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    text-transform: uppercase;
    font-size: 2rem;
}

/* .jumbotron-img {
    width: 100%;
    height: 300px;
    background-image: url("../assets/img/footer-montagne-bottom.jpg");
    background-repeat: no-repeat;
    background-size: contain;
} */
</style>