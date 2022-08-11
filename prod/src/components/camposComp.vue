<template>
<div class="register">
<div class="form">
<h1>Sistema</h1>
<h5>Cadastre-se para ver fotos e vídeos dos seus amigos.</h5>
<v-btn>Entrar com o Facebook</v-btn>
<br>
<v-divider>ou</v-divider>
<div class="input-form">
    <input type="text" placeholder="Número de celular ou email">
    <input type="text" placeholder="Nome completo">
    <input type="text" placeholder="Senha">
</div>
    <p>Ao se cadastra, você concorda com nossos <b>Termos, Politicas de Privacidade e Politica de Cookies</b></p>
    <v-btn class="btn-register"
>Cadastre-se</v-btn>
</div>
</div>
</template>
<script>
export default {
  name: 'camposComp'
}
</script>
<style scoped>
.register{
    align-items: center;
}
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
    margin-top: 2rem;
}
p, b{
   color: rgb(163, 163, 163);
font-size: 10px;
}
.v-btn{
    display: flex;
     background-color: rgb(36, 147, 244);
     color: aliceblue;
     height: 1.5rem;
     margin-left: 10px;
     font-size: 10px;
     width: 14rem;
     margin-top: 1rem;
}
.btn-register{
     background-color: rgb(140, 191, 227);
     color: aliceblue;
}
.v-divider{
margin-left: 10px;
margin-right: 10px;
}
.v-text-field{
    display: flex;
}
input{
    border:solid rgb(208, 208, 208) 1.3px;
    border-radius: 0.3rem;
    margin: 2px;
    background-color:rgb(246, 246, 246) ;
    width: 14rem;
    height: 2rem;
    color: rgb(188, 188, 188);
    font-size: 12px;
    padding-left: 0.7rem;
}
.input-form{
    padding-top: 1rem;
    padding-bottom: 1rem;
}
</style>
