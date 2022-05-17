<template>
  <div class="jumbotron-container">
    <img
      class="jumbotron-container-img"
      src="../assets/img/milano.jpg"
      alt=""
    />
    <h2 class="title active">Che bella Milano</h2>
    <a href="">Clicca per sapere di più</a>
  </div>
  <!-- <div class="jumbotron-img"></div> -->
</template>

<script>
export default {
  name: "AppJumbotron",
};
</script>

<style scoped lang="scss">
// .jumbotron-container .title
// .jumbotron-container a

.jumbotron-container {
  position: relative;

  // .jumbotron-container-img
  &-img {
    filter: grayscale(1);
  }

  // .title.active
  .title {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: green;
    text-transform: uppercase;
    font-size: 2rem;

    &.active {
      background-color: rgba(255, 255, 255, 0.5);

      //.jumbotron-container .title.active:hover
      &:hover {
        color: red;
      }
    }
  }

  a {
    color: red;
  }
}

/* .jumbotron-img {
    width: 100%;
    height: 300px;
    background-image: url("../assets/img/footer-montagne-bottom.jpg");
    background-repeat: no-repeat;
    background-size: contain;
} */
</style>