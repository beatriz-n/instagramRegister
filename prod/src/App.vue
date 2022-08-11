<template>
  <v-app>
    <v-main class="body">
      <v-sheet class="box-container"
  height="640"
  width="270"
>
<v-sheet
  color="white"
  elevation="1"
  height="450"
  width="250"
>
<CamposComp></CamposComp>
</v-sheet>
<v-sheet class="box-bottom"
  color="white"
  elevation="1"
  height="60"
  width="250"
>
<p>Tem uma conta? <a href="#"> Conecte-se</a></p>
</v-sheet>
<p>obtenha o aplicativo</p>
</v-sheet>
    </v-main>
  </v-app>
</template>

<script>
import CamposComp from './components/camposComp.vue'

export default {
  name: 'App',

  components: {
    CamposComp
  },
  data: () => ({
    //
  })
}
</script>
<style scoped>
.v-sheet{
  margin-left: 4%;
  margin-top: 3%;
  padding-top: 1%;
}
.box-bottom{
  margin-top: 1rem;
  margin-bottom: 2rem;
}
a{
  color: rgba(170,239,255,255);
}
p{
  text-align: center;
  font-size: small;
  padding-top: 1.3rem;
}
.box-container{
  background-color:rgba(250,250,250,255);
  margin-left: 40%;
}
.body{
  background-color: rgba(245,245,245,255);
}
</style>
