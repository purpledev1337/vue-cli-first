<template>
  <div class="jumbo">
    <img src="https://media.gcflearnfree.org/content/5e31ca08bc7eff08e4063776_01_29_2020/ProgrammingIllustration.png" alt="">
    <span>Oh yeah, this is a jumbotron!</span>
  </div>
</template>

<script>
export default {
  name: 'Jumbotron',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo {
    margin: 50px auto;
    width: 70%;
    height: 300px;
    position: relative;
}

img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

span {
    font-size: 2em;
    width: 150px;
    position: absolute;
    top: 80px;
    right: 50px;
}

</style>
