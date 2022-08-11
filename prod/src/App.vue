<template>
  <v-app>
    <v-main>
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
></v-sheet>
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
</style>
