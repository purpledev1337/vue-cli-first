<template>
  <header class="hello">
    <h2>La mia prima app con Vue CLI!</h2>    
    <div class="loading"></div>
  </header>
</template>

<script>
export default {
  name: 'Title',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.loading {
  border-radius: 50%;
  border-top: 100px solid white;
  border-right: 100px solid black;
  border-bottom: 100px solid white;
  border-left: 100px solid black;
  width: 0px;
  height: 0px;
  animation: spin 2s linear infinite;
}

@keyframes spin {
  100% { transform: rotate(360deg); }
}
</style>
