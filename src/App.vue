<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
html, body {
  margin: 0;
  padding: 0;
}
body {
  background-image: url(assets/stars.gif)
}
.container {
  display: block;
  margin: 0 auto;
  width: 900px;
}
h1 {
  color: yellow;
  text-align: center;
}
.menu-table {
  margin: 0 auto;
}
.menu-table, .menu-table td {
  
}
table, tr, td {
    border-color: white;
    border-style: ridge;
    border-width: thin;
}
.menu-table td a {
  color: blue;
  padding: 1rem;
}
</style>
