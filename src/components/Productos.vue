<template>
    <section class="container mt-5" id="productos">
    <div class="row">
      <!-- primera -->
      <div class="col-sm-4 col-12 px-5 mb-4">

        <div class="card">
          <img src="../assets/img/colaciones.jpg" class="card-img-top" alt="colaciones" />
          <div class="card-body">
            <h5 class="card-title fw-bold">Desayunos</h5>
            <p class="card-text">
              Contamos con desayunos nutritivos y deliciosos.
            </p>
          </div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item">Precio: ${{ precio }}</li>
            <li class="list-group-item">Cantidad: Para {{ cantidad }} personas</li>
          </ul>
          <div class="card-body">
            <a href="#" class="card-link">Ver más</a>
            <a href="#" class="card-link">Comprar</a>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
    name:'Productos',
    data(){
        return{
            precio:"2.000",
            cantidad: "dos",
        }
    }
}
</script>