<template>
<div class="container">
  <h2>Dropdowns</h2>
  <p>The .dropdown class is used to indicate a dropdown menu.</p>
  <p>Use the .dropdown-menu class to actually build the dropdown menu.</p>
  <p>To open the dropdown menu, use a button or a link with a class of .dropdown-toggle and data-toggle="dropdown".</p>                                          
  <div class="dropdown">
    <button class="btn btn-primary dropdown-toggle" type="button" data-toggle="dropdown">Dropdown Example
    <span class="caret"></span></button>
    <ul class="dropdown-menu">
      <li><a href="#">HTML</a></li>
      <li><a href="#">CSS</a></li>
      <li><a href="#">JavaScript</a></li>
    </ul>
  </div>
</div>
    <div>
        <div id="header">
            <div class="option">
                <a href="" class="options-list">MEN</a>    
                <a href="" class="options-list">WOMEN</a>    
                <a href="" class="options-list">KIDS</a>    
                <a href="" class="options-list">BEAUTY</a>    
                <a href="" class="options-list">STUDIO</a>    
            </div>
            <ul id="men">
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
                <li>suganth</li>
            </ul>
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
.options-list, .kart {
    text-decoration: none;
    color: black;
    font-size: 15px;
    margin: 10px;
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