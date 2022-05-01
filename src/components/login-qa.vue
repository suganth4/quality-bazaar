<template>
    <div>
        <div id="header">
            <div class="option">
                <ul class="menu">
                    <li id="options-list-1">
                        <a href="" id="men-menu">MEN</a>
                        <div id="men">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>    
                    <li id="options-list-2">
                        <a href="" id="women-menu">WOMEN</a>
                        <div id="women">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>    
                    <li id="options-list-3">
                        <a href="" id="kids-menu">KIDS</a>
                        <div id="kids">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>
                    <li id="options-list-4">
                        <a href="" id="homeAndLiving-menu">HOME & LIVING</a>
                        <div id="home">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>  
                    <li id="options-list-5">
                        <a href="" id="beauty-menu">BEAUTY</a>
                        <div id="beauty">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>        
                    <li id="options-list-6">
                        <a href="" id="studio-menu">STUDIO</a>
                       <div id="studio">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>
                </ul>    
            </div>

            <div class="search">
                <i class="fas fa-search"></i>
                <input type="text" name="" value="" placeholder="Search for products, brands and more"  id="search">
            </div>
            <div class="options right">
                <div class="kart-options">
                    <i class="fa fa-user" aria-hidden="true"></i>
                    <div >
                        <a href="" class="kart">Profile</a>
                    </div>
                </div>
                <div class="kart-options">   
                    <i class="fa fa-heart-o"></i>
                    <div>
                        <a href="" class="kart">Wishlist</a>
                    </div>
                </div>
                <div class="kart-options">
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>
                    <div>
                        <a href="" class="kart">Bag</a>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>

<style>
#header, .options {
    display: flex;
    justify-content: space-between ;
    /* border: 1px solid red; */
}
.right {
    padding: 10px;
    padding-top:5px ;
}
.menu {
    list-style-type:none;
    margin: 0px;
    margin-top:5px ;
    /* border: 1px solid red; */
}
.menu li {
    display: inline-block;
}
li {
    padding: 10px;
}
#options-list-1 a,#options-list-2 a,#options-list-3 a,#options-list-4 a,#options-list-5, #options-list-6, a,.kart {
    text-decoration: none;
    font-size: 15px;
    margin: 5px;
    font-weight: 600;
    color: black;
}
.fa-user{
    margin-bottom: 5px;
    margin-left: 18px;
}
.fa-heart-o {
    margin-bottom: 5px;
    margin-left: 22px;
}
.fa-shopping-bag {
    margin-bottom: 5px;
    margin-left: 10px;  
}
.kart-options {
    margin: 10px;
}
#men a, #women a, #kids a, #beauty a, #studio a, #home a {
    display: block;
}
#men, #women, #kids, #beauty, #studio , #home{
    display: none;
}
#options-list-1:hover #men, #options-list-2:hover #women, #options-list-3:hover #kids,#options-list-4:hover #home, #options-list-5:hover #beauty, #options-list-6:hover #studio {
    display: block;
    position: absolute;
    top:80px;
}
#options-list-1:hover, #options-list-2:hover, #options-list-3:hover,#options-list-4:hover #home, #options-list-5:hover, #options-list-6:hover{
    border-bottom: solid 5px rgb(255, 0, 179);
}
#options-list-1:hover #men, #options-list-2:hover #women, #options-list-3:hover #kids,#options-list-4:hover #home, #options-list-5:hover #beauty, #options-list-6:hover #studio {
    display: block;
}
#search {
    font-size: 10px;
    margin: 10px;
    width: 300px;
    height: 20px;
    padding: 10px;
    padding-left: 40px;
    border: 0.1px solid rgba(189, 179, 179,0.3);
    outline: none;
    border-radius: 5px;
    background: #f5f5f6;
    font-size: 13px;
    color: rgb(0, 0, 0);
    
}
#search:focus {
       background: white; 
}
.search {
    position: relative;
    margin-left: 100px;
    /* border: 1px solid red; */
}
.fa-search {
    position: absolute;
    top: 23px;
    left: 20px;
    opacity: 0.5;
}
#image {
    width: 150px;
    height: 150px;
}
</style>