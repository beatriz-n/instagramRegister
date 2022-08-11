<template>
  <v-app>
    <v-main>
      <v-sheet class="box-container"
  color="white"
  height="250"
  width="137"
>
<v-sheet
  color="white"
  elevation="1"
  height="400"
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
  margin-left: 40%;
  margin-top: 3%;
}
.box-bottom{
  margin-top: 1rem;
  margin-bottom: 2rem;
}
a{
  color: rgb(36, 147, 244);
}
p{
  text-align: center;
  font-size: small;
  padding-top: 1.3rem;
}
.box-container{
  background-color: rgb(66, 120, 120);
}
</style>
