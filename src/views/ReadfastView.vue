<template>
  <div class="Contenedor">
    <textarea name="text_container" id="text_container" cols="30" rows="10" placeholder="Introduce your text"></textarea>
    <div id="radio_button_container">
      <div id="radio_container">
        <div><input type="radio" id="velocidad1" name="velocidad_text" value="10ms" />
        <label for="velocidad1">Velocidad 1: Palabra * 10 Milisegundos</label></div>
        <div><input type="radio" id="velocidad2" name="velocidad_text" value="20ms" />
        <label for="velocidad2">Velocidad 2: Palabra * 20 Milisegundos</label></div>
        <div><input type="radio" id="velocidad3" name="velocidad_text" value="30ms" />
        <label for="velocidad3">Velocidad 3: Palabra * 30 Milisegundos</label></div>  
      </div>
      <Button >red</Button>
    </div>  
      
  </div>
</template>

<script lang="ts">
export default {
    data() {
      return {
        
      }
    },
    methods: {
      greet() {
        console.log("heasad")
      }
    }
}

</script>
<style>
.Contenedor{
  width: 100%;
  min-height: 100px;
  height: 90vh;
  background-color: #2c3e50;
  display: flex;
  align-items: center;
}
#text_container{
  width: 50%;
  height: 95%;
  resize: none;
  border-radius: 10px;
  padding: 1rem;
}
button{
  background-color: red;
  cursor: pointer;
}
button:hover{
  background-color: #2c3e50;
}
#radio_container{
  height: 100px;
  background-color: antiquewhite;
  border-radius: 10px;
  margin: 1rem;
  padding: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
#radio_container > div{
  display: flex;
}
#radio_button_container{
  width: 50%;
  height: auto;
}
</style>



