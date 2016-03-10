# BgMove


## Demo 
http://tommyno.github.io/BgMove/


## About

Interactive background image.

No dependencies.

Uses css cover, scale and transform.

Works in all modern browsers. Including IE9.


## How to use

1) Include bgmove.js
```html
<script src="js/bgmove.js"></script>
```

2) Add html wrappers
```html
<div class="bgwrap">   
    <div class="bgmove"></div>
</div>
```

3) Add css
```css
.bgwrap {
    width: 100%;
    height: 100vh;
    overflow: hidden;
    position: relative;
}

.bgmove {
    background: url(img/bg.jpg);
    background-size: cover;
    background-position: center center;
    width: 100%;
    height: 100%;
    /* remove flicker in webkit */
    -webkit-backface-visibility: hidden; 
}
```
