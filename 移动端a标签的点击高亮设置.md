有些浏览器的默认的在点击a标签时候，在处于active状态下，会出现有透明读的灰色的高亮背景色。
但是在一些背景图（而背景图的是圆或者半透明）的a标签这active状态是会影响美观的。
所以一般会给这样的a标签加上一个
```css
    -webkit-tap-highlight-color: rgba( 0 , 0 , 0 , 0);
   /*点击高亮的颜色等于全透明*/
```
