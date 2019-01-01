<template>
  <!-- feature -->
  <section id="Feature">
    <div class="container">
      <div class="row">
        <div class="card" style="width:50%">
          <img
            class="card-img-top"
            src="../assets/images/haden.jpg"
            alt="Card image"
            style="width:100%"
          >
          <div class="card-body">
            <h4 class="card-title">Certificaciones de Procesos</h4>
            <p>
              Trabajamos bajo la norma de calidad 9000 y
              proporcionamos a nuestros clientes un producto a la medida
            </p>
            <a href="#" class="btn btn-primary">Ver mas</a>
          </div>
        </div>

        <div class="card" style="width:50%">
          <div class="card-body">
            <h4 class="card-title">Nuestras Politicas</h4>
            <ul class="list-group">
              <li class="list-group-item">Calidad</li>
              <li class="list-group-item">Atencion</li>
              <li class="list-group-item">Responsabilidad</li>
              <li class="list-group-item">Iniciativa</li>
              <li class="list-group-item">Creatividad</li>
              <li class="list-group-item">Higiene</li>
            </ul>
            <a href="#" class="btn btn-primary">Ver mas</a>
          </div>
          <img
            class="card-img-bottom"
            src="../assets/images/haden.jpg"
            alt="Card image"
            style="width:100%"
          >
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Feature",
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
