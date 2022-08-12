<template>
<div class="register">
<div class="form">
<img src="C:\Users\Usuario\Downloads\github\instagramRegister\prod\src\assets\logo.jpeg"/>
<h1>Sistema</h1>
<h5>Cadastre-se para ver fotos e vídeos dos seus amigos.</h5>
<v-btn class="btn-firt">Entrar com o Google</v-btn>
<br>
<v-divider>ou</v-divider>
<div class="input-form">
    <input type="text" placeholder="Número de celular ou email">
    <input type="text" placeholder="Nome completo">
    <input type="text" placeholder="Senha">
</div>
<div>
    <div class="text-register">Ao se cadastra, você concorda com nossos <b>Termos, Politicas de Privacidade e Politica de Cookies</b></div>
</div>
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
    margin-bottom: 1rem;
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
.text-register, b{
   color: rgb(163, 163, 163);
font-size: 10px;
 margin-right: 25px;
    margin-left: 25px;
    display: inline-table;
}
.v-btn{
    display: flex;
     /* background-color: rgba(1,149,247,255); */
     background-color: rgb(205, 40, 40);
     color: aliceblue;
     height: 1.5rem;
     margin-left: 10px;
     font-size: 10px;
     width: 14rem;
     margin-top: 1rem;
}
.btn-register{
     background-color: rgba(179,223,250,255);
     color: aliceblue;
     transition: .5s;
}
.btn-register:hover{
 background-color: rgba(1,149,247,255);
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
    border:solid rgba(216,216,216,255) 1.3px;
    border-radius: 0.3rem;
    margin: 2px;
    background-color:rgba(250,250,250,255) ;
    width: 14rem;
    height: 2rem;
    color: rgba(216,216,216,255);
    font-size: 12px;
    padding-left: 0.7rem;
}
.input-form{
    padding-top: 1rem;
    padding-bottom: 1rem;
}
</style>
