<template>
  <!-- feature -->
  <section id="Feature3">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-6 px-1">
          <h2 class="text-uppercase">Nuestras Politicas</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-md-6 px-1">
          <ul>
            <li>Calidad</li>
            <li>Atencion</li>
            <li>Responsabilidad</li>
            <li>Iniciativa</li>
            <li>Creatividad</li>
            <li>Higiene</li>
          </ul>
        </div>
        <div class="col-xs-12 col-md-6 px-1">
          <img class="img-responsive fix" src="../assets/images/haden.jpg" alt="Feature img">
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-md-6 px-1">
          <img class="img-responsive fix" src="../assets/images/haden.jpg" alt="Feature img">
        </div>
        <div class="col-xs-12 col-md-6 px-1">
          <h2 class="text-uppercase">Certificaciones de Procesos</h2>
          <p>
            Trabajamos bajo la norma de calidad 9000 y
            proporcionamos a nuestros clientes un producto a la medida
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Feature3",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.text-white {
  color: #fff !important;
}

#feature {
  padding-top: 20px;
  background-color: #164685;
  height: 400px;
  width: 100%;
  top: 0;
  left: 0;
  opacity: 0.3;
  h2 {
    padding-top: 40px;
  }
}
img.fix {
  height: 100%;
  width: 100%;
  align-content: center;
}
</style>
