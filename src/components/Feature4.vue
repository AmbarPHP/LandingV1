<template>
  <!-- feature -->
  <section id="Feature4">
    <div class="container">
      <div class="row">
        <div class="col-xs-12">
          <div class="text-welcome">
            <span class="text-title">Fresh</span>
            <p class="text-space">
              When you picture yourself a traditional American farm in it classic, idyllic perception, this is what the Latify farm actually looks like!.
              Charming nature that surrounds all of our farming facilities haunts our farm guests and inspires and refreshes them.
              All in all, we simply love growing food and taking care of our cattle, all seasons, any season long!
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Feature4",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#Feature4 {
  margin-top: 20px;
  height: 440px;
  width: 100%;
  background-color: #262e37;
  background-image: url("../assets/images/haden.jpg"); // no-repeat ;
  background-repeat: no-repeat;
  background-size: 100%;
  margin-bottom: 20px;
}
.text-welcome {
  text-align: center;
  color: #fff !important;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  font-size: 1.5em;
}
.text-title {
  padding-bottom: 20px;
  font-size: 2.5em;
}
</style>
