<template>
{{mensaje}}
<button type="button" name="cargar" @click="increment">
  cargar
</button>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      mensaje: 0
    };
  },
  methods:{
    increment(){
      this.mensaje++;
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
