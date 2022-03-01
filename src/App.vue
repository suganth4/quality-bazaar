<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>

  {{ count }}
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import axios from 'axios'
export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data: ()=> {
   return{ count:0
   }
  },
  mounted:  async function () {
    axios.get('http://localhost:5000/')
    .then((response) => {
      console.log(response);
    }).catch(()=>{
      console.log("sdfsd");
    })
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
