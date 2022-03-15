<template>
    <div>
        <div id="header">
            <div>
                <img src="../assets/myntra.jpg" alt="" id="image">
            </div>
            <div class="option">
                <a href="" class="options-list">MEN</a>    
                <a href="" class="options-list">WOMEN</a>    
                <a href="" class="options-list">KIDS</a>    
                <a href="" class="options-list">BEAUTY</a>    
                <a href="" class="options-list">STUDIO</a>    
            </div>
            <div>
                <input type="text" name="" value="" id="search">
            </div>
            <div class="option">
                <a href="" class="kart">Profile</a>
                <a href="" class="kart">Wishlist</a>
                <a href="" class="kart">Bag</a>
            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style>
#header, .option {
    display: flex;
    justify-content: space-between ;
}
.options-list, .kart {
    text-decoration: none;
    color: black;
    font-size: 15px;
    margin: 10px;
}
#search {
    font-size: 20px;
    margin: 10px;
}
#image {
    width: 150px;
    height: 150px;
}
</style>