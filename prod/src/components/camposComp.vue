<template>
<div class="form">
<h1>Sistema</h1>
<h5>Cadastre-se para ver fotos e vídeos dos seus amigos.</h5>
<button>Entrar com o Facebook</button>
<p>ou</p>
    <input type="text" value="text" placeholder="Número de celular ou email">
    <input type="text" value="text" placeholder="Nome completo">
    <input type="text" value="text" placeholder="Senha">
    <p>Ao se cadastra, você concorda com nossos <b>Termos, Politicas de Privacidade e Politica de Cookies</b></p>
    <button>Cadastre-se</button>
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
p, b{
   color: rgb(163, 163, 163);
font-size: 10px;
}
button{
     background-color: rgb(36, 147, 244);
     color: aliceblue;
}

</style>
