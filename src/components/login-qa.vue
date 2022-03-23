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
                        <a href="" >MEN</a>
                        <div id="men">
                            <a href="">T-shirt</a>
                            <a href="">Casual Shirt</a>
                            <a href="">Formal Shirt</a>
                        </div>
                    </li>    
                    <li>
                        <a href="" id="options-list-2">WOMEN</a>
                    </li>    
                    <li>
                        <a href="" id="options-list-3">KIDS</a>
                    </li>    
                    <li>
                        <a href="" id="options-list-4">BEAUTY</a>
                    </li>    
                    <li>
                        <a href="" id="options-list-5">STUDIO</a>
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
    margin-top: 10px;
}
.menu {
    list-style-type:none;
}
.menu li {
    display: inline-block;
}
#options-list-1 a,#options-list-2,#options-list-3,#options-list-4,#options-list-5,.kart {
    text-decoration: none;
    color: black;
    font-size: 15px;
    margin: 10px;
}
#men a {
    display: block;
}
#men {
    visibility: hidden;
    position: relative;
    top:200px;
}
#options-list-1:hover a{
    border-bottom: solid 5px rgb(255, 0, 179);
}
#options-list-1:hover #men {
    display: block;
}
#search {
    font-size: 10px;
    margin: 10px;
    width: 300px;
    height: 15px;
    color: black;
    opacity: 0.5;
    padding: 10px;
}
#image {
    width: 150px;
    height: 150px;
}
</style>