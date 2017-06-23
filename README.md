# wow.js

有的页面在向下滚动的时候，有些元素会产生细小的动画效果。虽然动画比较小，但却能吸引你的注意。WOW.js 依赖 animate.css，所以它支持 animate.css 多达 60 多种的动画效果，能满足您的各种需求。

此插件不能实现div容器里面滚动,所以修改了wow.js的监听事件,添加初始参数。

### [使用方法 ➫](https://github.com/matthieua/WOW)

wowjs的用法

- JavaScript

```javascript
var wow = new WOW({
    boxClass: 'wow',
    animateClass: 'animated',
    offset: 0,
    mobile: true,
    live: true,
    forms:window    //此处增加一个初始参数,可修改为$(".div") 容器里面的监听 
});
wow.init();
```

修改之后 [here in](http://drinthing.xyz/evo)!


## BUG或者建议

如果你发现BUG或者你有其他建议,请告诉我 [here on Github](https://github.com/LKCheng/wow.js)!



