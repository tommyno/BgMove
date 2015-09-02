# BgMove


## Demo
Link goes here


## About

Interactive background image. Fullscreen. Background image moves with mouse cursor.

No dependencies. No jQuery needed.

Uses css "background-size: scale" to fill screen.

Uses css transform scale + translate to move background image.


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

3. Add css
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
