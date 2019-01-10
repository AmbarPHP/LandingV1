<template>
  <section id="Nav">
    <img class="img-responsive fix" src="../assets/images/logo6.png" alt="Feature img">
    <nav class="navbar bg-verde navbar-expand-lg">
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active">
            <a class="nav-link" href="#">
              Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </section>
</template>

<script>
export default {
  name: "Nav",
  props: {
    msg: String
  }
};
</script>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:800');

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#Nav {
  font-family: "Open Sans", sans-serif; //'Montserrat', sans-serif;
  .bg-verde {
    color: #00d496;
    height: 90px;
    font-size: 24px;
  }
}
</style>
