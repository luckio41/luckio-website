<template>
  <div class="about">
    <h1>{{ msg }}</h1>
    <img src="http://media.pagina7.cl/2017/06/000_PY86L-700x457.jpg" />
    <audio class="wp-audio-shortcode" id="audio-3282943-1" preload="none" style="width: 100%;" controls="controls"><source type="audio/mpeg" src="http://media.biobiochile.cl/wp-content/uploads/2017/06/963-cuna-aborto-objecion-conciencia-maturana.mp3?_=1"><a href="http://media.biobiochile.cl/wp-content/uploads/2017/06/963-cuna-aborto-objecion-conciencia-maturana.mp3">http://media.biobiochile.cl/wp-content/uploads/2017/06/963-cuna-aborto-objecion-conciencia-maturana.mp3</a></audio>
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
