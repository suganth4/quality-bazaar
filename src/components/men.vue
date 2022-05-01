<template>
    <div>        
        <div v-for="Info in dressInfo.MEN" :key = "Info">
            <h4>{{ Info.title }}</h4>
            <div v>

            </div>
        </div>
    </div>
</template>

<script>
import dressInfo from "../data/dressInfo";
</script>

<style scoped>

</style>