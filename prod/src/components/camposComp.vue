<template>
<div class="form">
<h1>Sistema</h1>
<h5>Cadastre-se para ver fotos e vídeos dos seus amigos.</h5>
    <input type="text" value="text" placeholder="Número de celular ou email">
    <input type="text" value="text" placeholder="Nome completo">
    <input type="text" value="text" placeholder="Senha">
</div>
</template>
<script>
export default {
  name: 'camposComp'
}
</script>
<style scoped>
h1 {
    color: black;
}
h5{
    color: rgb(163, 163, 163);
    margin-right: 30px;
    margin-left: 30px;
}
.form {
    text-align: center;
}

</style>
