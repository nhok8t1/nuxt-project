<template>
    <div class="about">
      <h1>Hello {{ their_name }}, this is an about page</h1>
      <p>BTVN Frontend - Vuejs</p>
    </div>
</template>

<script>
export default {
    name: 'about',
    data() {
        return {
            their_name: this.$route.params.name
        }
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:400,700');

body {
  background-color: #EEEEEE;
  font-family: 'Montserrat', sans-serif;
  display: grid;
  grid-template-rows: auto;
  justify-items: center;
  padding-top: 50px;
}
body, html {
  margin: 0;
  height: 100%;
}
</style>