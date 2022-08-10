<template>
    <div class="container">
         <CamposComp></CamposComp>
         <hr>
    </div>
</template>
<script>
import CamposComp from './components/camposComp.vue'
export default {
  name: 'messageComp',
  props: {
    msg: String
  },
  components: { CamposComp }
}
</script>

<style scoped>
.container {
  display: flex;
    color: #d6d6d6;
    border: 2px solid #afafaf;
    border-radius: 5px;
    width: 250px;
    height: 450px;
    align-items: center;
    margin-left: 40%;
  }
</style>
