<template>
    <div>
        <div id="header">
            <div class="option">
                <a href="" class="options-list">MEN</a>    
                <a href="" class="options-list">WOMEN</a>    
                <a href="" class="options-list">KIDS</a>    
                <a href="" class="options-list">BEAUTY</a>    
                <a href="" class="options-list">STUDIO</a>    
            </div>
            <div>
                <input type="text" name="" value="" placeholder="Search for products, brands and more"  id="search">
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
    font-size: 10px;
    margin: 10px;
    width: 200px;
    height: 20px;
    color: black;
    opacity: 0.5;
    padding: 10px;
}
#image {
    width: 150px;
    height: 150px;
}
</style>