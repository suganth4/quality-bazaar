<template>
    <div id="main">        
        <div v-for="Info in da.men" :key = "Info" class="detail">
            <div>
                <h4>{{ Info.title }}</h4>
                <ul>
                    <li v-for="dress in Info.categories" :key="dress">
                        {{ dress }}
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
import dressInfo from "../data/dressInfo";
export default {
    name: "menData",
    data() {
       return {
            da: dressInfo
       }
    }
}
</script>

<style scoped>
body{
    margin: 0px;
}
h4{
    color: rgb(255, 0, 212);
    margin:8px;
}
ul {
    padding: 5px;
    width: 180px;
}
li {
    padding:5px;
    display:block;
    box-sizing: content-box;
    /* padding-right: 50px; */
    color:rgba(0, 0, 0,0.7);
}
#main{
    background: pink;
    width: 90%;
    margin: auto;
    height: 430px;
    display: flex;
}
</style>