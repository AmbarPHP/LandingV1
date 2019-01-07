<template>
  <div id="app">
    <div class="sticky">
      <Nav></Nav>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto"></div>
      </div>
      <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Feature4></Feature4>
        </div>
      </div>
      <!-- <div class="row">
        <div class="col-lg-12 h-100 text-center text-lg-right my-auto">
          <Embed></Embed>
        </div>
      </div>-->
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
import Feature4 from "./components/Feature4.vue";
import Embed from "./components/Embed.vue";

export default {
  name: "app",
  components: {
    Footer2,
    Nav,
    Contact,
    Feature3,
    Feature4,
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
  background-color: #262e37;
  color: #fff;
  margin-left: 0px;
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

.sticky {
  position: -webkit-sticky;
  position: sticky;
  top: 0;
  //background-color: yellow;
  background-color: #262e37;
  padding: 25px;
  font-size: 20px;
  z-index: 11;
  margin-bottom: 20px;
}
</style>
