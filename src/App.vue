<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <h1>suhganth</h1>
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
   return{ payload:{"name":"suganth"}
   }
  },
  mounted:  async function () {
    axios.post('http://localhost:5000/', {
      name: "rasu",
      age: 35
    })
    .then((response) => {
      console.log(response.data);
    }).catch(()=>{
      console.log("sdfsd");
    })
    console.log("suganth")
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
