<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Nav></Nav>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Embed></Embed>
        </div>
      </div>

      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Feature3></Feature3>
        </div>
      </div>

      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Footer2></Footer2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Footer2 from "./components/Footer2.vue";
import Nav from "./components/Nav.vue";
import Contact from "./components/Contact.vue";
import Feature3 from "./components/Feature3.vue";
import Embed from "./components/Embed.vue";

export default {
  name: "app",
  components: {
    Footer2,
    Nav,
    Contact,
    Feature3,
    Embed
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
  background-color: #262e37;
  margin-top: 60px;
  color: #fff;
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
