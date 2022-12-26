<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <h2 id="text"> text...</h2>
  </div>
</template>



<script lang="ts">
import HelloWorld from '@/components/HelloWorld.vue';

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  },
  data(){
    return {
    }
  },
  mounted(){
    var text_to_procesar = "Hola mundo, mi nombre es marcelo".split(" ");
    document.getElementById("text")!.innerHTML = text_to_procesar.toString()
  }
}

</script>
