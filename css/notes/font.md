# font

1.  font-size 

> 属性:描述字体大小
>
> 属性值:lighter;normal;bold;bolder;
>
> notice:决定字体大小的字体的高度;

2. font-weight

> 属性:描述字体宽度
>
> 属性值:lighter,normal,bold,bolder
>
> notice:可以用数字来描述字体的宽度(100-900),其中,normal相当于400,bold相当于700

3. font-style

> 属性:描述字体使用的样式
>
> 属性值:normal;italic(斜体);
>
> notice:italic相当于<em>标签

4. font-family

> 属性:描述使用的字体
>
> 属性值:arial(jobs)
>
> notice:字体的宽度属性值是否其作用在于该字体样式是否有对应的样式(such as :bold)

5. color

> 属性:设置字体的颜色
>
> 属性值:字体颜色值
>
> > 1. 土鳖式:red,green...
> > 2. 颜色代码式:#ffffff->#fff(只有两两相同的可以简写成一位)
> > 3. 颜色函数式:rgb(0-255,0-255,0-255)

6. 如何使文本居中?

> 1. 水平方向:`text-align:center`
>
> 2. 垂直方向: 使文本所占的高度等于容器的高度
>
>    `line-height`:单行文本所占的高度

7. 如何进行文本缩进?

> ```css
> text-indent:2em;
> ```
>
> em=1*font-size;