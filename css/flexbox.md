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
    justify-content: center;
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