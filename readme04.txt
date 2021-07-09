<label> 标签为 input 元素定义标注（标记）。

label 元素不会向用户呈现任何特殊效果。不过，它为鼠标用户改进了可用性。如果您在 label 元素内点击文本，就会触发此控件。就是说，当用户选择该标签时，浏览器就会自动将焦点转到和标签相关的表单控件上。

<label> 标签的 for 属性应当与相关元素的 id 属性相同。


如
<label for="pwd">密码</label>
<input id="pwd" type="password" placeholder="请输入密码">

opacity: 0.3;透明度
z-index: 9999;设置优先级，值越大，越优先
display: none;不显示
overflow: auto;当内容超出显示框就会自动显示滚动条
    {position: absolute;
    top: 0px;
    bottom: 0px;
    left: 0px;
    right: 0px;}百分比网站居中