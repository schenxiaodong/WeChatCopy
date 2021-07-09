CSS 选择器
    类选择器：
        给标签指明class属性
            .类名{
                css代码
            }

    后代选择器：
           祖先元素 后代元素{
                css代码
           }

    通配符选择器：选中所有的标签
               *{
                    css代码
               }



CSS样式

    width:      宽度 可以是百分比，可以是像素px
    height：     高度 可以是百分比，可以是像素px
        如果取百分比，取的是父容器的百分比，body默认宽为整个页面的宽，高为0

    我们在样式后给四个值，例如margin:10px 20px 30px 40px 分别是10上 20右 30下 40左
    我们在样式后给三个值，例如margin:10px 20px 30px 分别是10上 20左右 30下
    我们在样式后给两个值，例如margin:10px 20px 分别是10上下 20左右
    我们在样式后给一个值，例如margin:10px 分别是10上下左右


    边框border
        border:1px solid red;
        border:边框的宽度 边框的样式 边框的颜色
            也可以只设置某一边的边框
                border-top|left|right|bottom:上左右下

        box-sizing:content-box
            一个盒子真正的大小 = 盒子的大小 + 边框的大小
        box-sizing:border-box
            一个盒子真正的大小 = 盒子的大小

    边距：
        padding ：内边距
            padding-top:距离内部上边的边距
                    bottom:距离内部下边的边距
                    left:距离内部左边的边距
                    right:距离内部右边的边距
            margin ：外边距
                盒子离父级容器的边距

    背景：
        background-color:背景色
        color: 前景色

    定位：
        position:static|absolute|relative|fixed
            static：默认样式，不设置定位，设置定位无法使用偏移量
            absolute：开启绝对定位，脱离文本流，不依赖父元素
            relative：开启相对定位，相对于原来的位置进行偏移，会保留原来的位置
            fixed：开启绝对定位（固定定位），跟absolute定位方式一样，但是会固定在一个地方不懂（广告）

    偏移量：
        top|left|right|bottom:上左右下

    浮动：
        float：left|right
            left：向右浮动
            right：向左浮动


    列表
        list-style:none  取消的ul或者ol前边的标签

    text-decoration: none;取消a标签默认的下划线
    text-align: 设置文字的对齐方式
    line-height: 设置行高，文字默认的高度为文字大小的高度，如果要让文字在盒子中垂直居中
                 需要把行高设置成父容器的高度
    background-repeat: no-repeat; 背景图片默认会重复显示，设置成norepeat就不会重复显示
    background-size: contain;设置背景图片自适应盒子的大小，会随着盒子的大小而改变
    margin: 0px auto;寻找到水平范围的中间部分，用于设置盒子居中显示