<template>
    <div class="container">
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Nombre y Apellido</label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Nombre y Apellido">
        </div>
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="nombre@email.com">
        </div>
        <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label">Mensaje</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
    </div>

</template>

<script>
export default {
}
</script>

<style scoped>
.container{
    margin: 100px 30px;
}
</style>