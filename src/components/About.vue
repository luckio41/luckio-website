<template>
  <div class="about">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      msg: 'Acerca de'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about {
  text-align: center;
}
h1, h2 {
  font-weight: normal;
  color: red;
}
</style>
