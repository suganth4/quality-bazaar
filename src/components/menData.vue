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
    color: rgb(255, 0, 212)
}
#main{
    background: green;
    width: 800px;
    height: 350px;
    padding-left: 30px;
    padding-right:30px ;
    padding-bottom:30px ;
    display: flex;
}
</style>