# Vue Smooth Scroll

> Simple vue smooth scroll based on vue-smoothscroll https://github.com/Teddy-Zhu/vue-smoothscroll/blob/master/README.md


## Instalation
``` bash
# install dependency
npm install --save vue-smooth_scroll
``` 

``` javascript
// import on your project (less then 1KB gziped)
import vueSmoothScroll from 'vue-smooth-scroll'
Vue.use(vueSmoothScroll)
```

## Usage 
``` html
<a href="#div-id" v-smooth-scroll="{value: -(height-from-top-integer)}">Anchor</a> 
<div id="div-id"></div> 
```
