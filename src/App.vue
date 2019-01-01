<template>
  <div id="app">
    <div class="col-xs-12 col-md-12 px-1">
      <img src="assets/logo.jpg" alt="Lights" style="width:100%">
    </div>

    <h1>{{ msg }}</h1>

    <div class="container">
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Nav></Nav>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Gallery></Gallery>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Feature3></Feature3>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Contact></Contact>
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
import Contact from "./components/Contact.vue";
import Feature3 from "./components/Feature3.vue";
import Gallery from "./components/Gallery.vue";

export default {
  name: "app",
  components: {
    Footer,
    Nav,
    Contact,
    Feature3,
    Gallery
  },
  data() {
    return {
      msg: "Welcome to Manglar Fruit"
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
