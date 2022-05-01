<template>
<!-- <div class="container">
  <h2>Dropdowns</h2>
  <p>The .dropdown class is used to indicate a dropdown menu.</p>
  <p>Use the .dropdown-menu class to actually build the dropdown menu.</p>
  <p>To open the dropdown menu, use a button or a link with a class of .dropdown-toggle and data-toggle="dropdown".</p>                                          
  <div class="dropdown">
    <button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">Dropdown Example
    <span class="caret"></span></button>
    <h1 class="text">suganth</h1>
    <ul class="dropdown-menu">
      <li><a href="#">HTML</a></li>
      <li><a href="#">CSS</a></li>
      <li><a href="#">JavaScript</a></li>
    </ul>
  </div> -->
<!-- </div> -->
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
                        <a href="" id="beauty-menu">BEAUTY</a>
                        <div id="beauty">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>    
                    <li id="options-list-5">
                        <a href="" id="studio-menu">STUDIO</a>
                       <div id="studio">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>
                </ul>    
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
    margin-top: 5px;
        border: 1px solid black;
}
.option {
    padding-top:10px ;
}
.menu {
    list-style-type:none;
    margin: 0px;
    margin-top:5px ;
}
.menu li {
    display: inline-block;
}
li {
    padding: 10px;
}
#options-list-1 a,#options-list-2 a,#options-list-3 a,#options-list-4 a,#options-list-5 a,.kart {
    text-decoration: none;
    font-size: 15px;
    margin: 5px;
    font-weight: 600;
    color: black;
}
#men a, #women a, #kids a, #beauty a, #studio a {
    display: block;
}
#men, #women, #kids, #beauty, #studio{
    display: none;
}
#options-list-1:hover #men, #options-list-2:hover #women, #options-list-3:hover #kids, #options-list-4:hover #beauty, #options-list-5:hover #studio {
    display: block;
    position: absolute;
    top:80px;
}
#options-list-1:hover, #options-list-2:hover, #options-list-3:hover, #options-list-4:hover, #options-list-5:hover{
    border-bottom: solid 5px rgb(255, 0, 179);
}
#options-list-1:hover #men, #options-list-2:hover #women, #options-list-3:hover #kids, #options-list-4:hover #beauty, #options-list-5:hover #studio {
    display: block;
}
#search {
    font-size: 10px;
    margin: 10px;
    width: 350px;
    height: 20px;
    padding: 10px;
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
#image {
    width: 150px;
    height: 150px;
}
</style>