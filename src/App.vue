<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './components/HomePage.vue'
export default {
  name: "App",
  components: {
    Home
  }
};
</script>

<style>
body {
  font-weight: normal;
  font-style: normal;
}

a:focus {
  text-decoration: none;
}

a:focus,
a:hover {
  text-decoration: none;
}

a,
button {
  color: #1f1f1f;
  outline: medium none;
}

h1,
h2,
h3,
h4,
h5 {
  color: #191d34;
}

h1 a,
h2 a,
h3 a,
h4 a,
h5 a,
h6 a {
  color: inherit;
}

ul {
  margin: 0px;
  padding: 0px;
}

li {
  list-style: none;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.full-height {
  min-height: 100vh;
}
</style>
