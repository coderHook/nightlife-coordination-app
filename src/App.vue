<template>
  <div id="app">
    <app-header></app-header>
  </div>
</template>

<script>
import Header from './components/Header.vue';

export default {
  name: 'app',
  data () {
    return {

    }
  },
  components: {
    appHeader: Header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ECECEA;
  margin-top: 60px;
}

body {
  background-color: #74AFAD;
  color: white;
  margin: 100px;
}

h1 {
  font-size: 60px;
}
h2 {
  font-size: 30px;
}

h1, h2 {
  font-weight: bolder;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

.icon {
  font-size: 45px;
  margin: 20px;
}
.icon:hover {
  font-size: 60px;
}

</style>
