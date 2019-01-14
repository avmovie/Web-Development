# border

`border属性是一个复合属性`

-------------------

1. 复合属性

> ```css
> border的复合属性
> border:border-width border-style border-color
> border-left的复合属性
> border-left:border-widht border-style border-color
> such as:
> border:1px solid black;
> ```

2. 单一属性

> 1. border-width:边框的宽度
>
>    medium：定义默认厚度的边框。计算值为3px
>    thin：定义比默认厚度细的边框。计算值为1px
>    thick：定义比默认厚度粗的边框。计算值为5px
>
> 2. border-style:边框样式
>
>    solid,dotted,dashed...
>
> 3. border-color:边框的颜色

3. 用边框的特性画三角形

```html
html文件
<body>
        <div>
        </div>
</body>
```

```css
css文件
div{
    /* 利用border画三角形 */
    width: 0px;
    height: 0px;
    border:100px solid black;
    border-left-color: black;
    border-right-color: transparent;
    border-top-color: transparent;
    border-bottom-color: transparent;
}
```
