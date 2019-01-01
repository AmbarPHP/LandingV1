<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>

    <div class="container">
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Nav></Nav>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Footer></Footer>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Footer from "./components/Footer.vue";
import Nav from "./components/Nav.vue";

export default {
  name: "app",
  components: {
    Footer,
    Nav
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1,
h2 {
  font-weight: normal;
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
</style>
