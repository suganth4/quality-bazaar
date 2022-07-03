<template>
  <Login msg="Welcome to Your Vue.js App"/>
</template>

<script>
import Login from './components/login-qa.vue';
import axios from 'axios'
export default {
  name: 'App',
  components: {
    Login
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

</style>
