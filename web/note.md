# 笔记

## 1.div

盒子标签，内部用来放置一些其他HTML标签
可以通过"width: 1400px;height: 150px;"来设置盒子的大小

```css
width:设置盒子的宽度
height:设置盒子的高度
border:solid 1px red; 设置边框线
margin:auto;设置盒子相对父容器或网页水平居中
line-height:让div中的文字垂直居中
text-align:让div中的文字水平居中
background:url(img/ver_jy.png) no-repeat;设置背景图片,并且不重复
margin-left: 10px;让div距离左边的距离为10px
font-size: 14px;设置字体大小
color: #fff;设置字体颜色
background-position: 0px 0px;设置背景图片的位置
list-style:none;去掉列表前面的小圆点
```

## 2.内间距

容器(div,li,ul)与里面元素的距离

```css
padding: 0px 0px 0px 0px;上右下左
padding: 10px 20px;第一个值代表上下，第二个值代表左右
margin: 0px 0px 0px 0px;外间距 上右下左
```

## 3.CSS

```css
/*修饰的对象是:
    class="nav_ul"对象中的第三个子对象
    */
    .nav_ul > li:nth-child(3){
        border-bottom: solid 6px rgb(51,99,160);
    }
        .search{
            margin-right: 0px;
            width: 30px;
            height: 30px;
            border-radius: 50%;     /* 显示为圆形*/
            transition: 1s;     /*动画效果时间*/
            text-align: center;     /* 让li中的img水平居中*/
            line-height: 30px;      /* 让li中的img垂直居中*/
        }
            position: absolute; 绝对定位
```
```