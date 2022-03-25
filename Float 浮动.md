Float 浮动

元素的水平方向浮动，意味着元素只能左右移动而不能上下移动。

直到它的外边缘碰到包含框或另一个浮动框的边框为止。

浮动元素之后的元素将围绕它。如果不想让这个之后的元素围绕，可以清除浮动。

浮动元素之前的元素将不会受到影响。

```css
float:right|left
```

~~~html
<div>
    我是浮动的
</div>
<div>
    我是浮动的
</div>
<p>
    我不想浮动
</p>
<div>
    我是浮动的
</div>
<div>
    我是浮动的
</div>

<style>
    div{
        float:right;
        background-color:tan;
    }
    p{
        clear:both;
    }
</style>
~~~



比如p元素上面浮动

p元素下面的元素也浮动

但是中间元素不想浮动

利用浮动制作一个没有表格的网页。效果如下：

![](C:\Users\Elvira\AppData\Roaming\Typora\typora-user-images\image-20220325105059400.png)

布局：

![image-20220325121403880](C:\Users\Elvira\AppData\Roaming\Typora\typora-user-images\image-20220325121403880.png)



