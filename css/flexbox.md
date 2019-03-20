# Flex Navigation Menu
===
#### HTML
```html
<!--Navigation Menu-->
<nav class="main-nav">
    <ul class="nav">
        <li class="nav-item"><a href="#">Home</a></li>
        <li class="nav-item"><a href="#">About</a></li>
        <li class="nav-item"><a href="#">Contact</a></li>
        <li class="nav-item"><a href="#">Demo</a></li>
        <li class="nav-item"><a href="#">Download</a></li>
    </ul>
</nav>
```
#### CSS
```css
.nav{
    display: flex;
    justify-content: center | space-between | space-around | space-evenly;
    align-items: center;
    list-style: none;
}

.nav>.nav-item{
    padding: 10px 15px;
}

.nav>.nav-item > a {
    color: #ffffff;
    text-decoration: none;
}
```

#### Flexbox Grids
----------
```
    /**
   *Flexbox Grids
   */
   
   .container{
       width: 1200px;
       margin: 0 auto;
       background: greenyellow;
   }
   
   .columns{
       display: flex;
       flex-wrap: wrap;
   }
   
   .column{
       flex: 1; /*For evenly spaced*/
       flex: none; /*For apply width of children (parent{flex-wrap:wrap})*/
   }
   
   .col-6{
       width: 50%;
   }
   .col-12{
       width: 100%;
   }
   
   .box{
       padding: 20px;
       border: 1px solid #ddd;
   }
   ```