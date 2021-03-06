## 关键字：this
#### this的概念
this 是js预先定义好的变量。它的值是不固定的，会随着执行环境（上下文）的改变而改变。

#### 函数中this的值
在函数被调用时，决定this的值。
1. 直接调用 this => window
2. 触发事件调用 this => 触发事件的元素

## 事件
与文档元素或浏览器发生的一些特定的交互瞬间，会产生事件。事件由系统事先设定的、能被对象识别和响应的动作，如果click、mouseover、keyup……可以绑定一个事件处理函数，当事件发生时，执行相对应的代码。

js的全部事件：
事件 | 描述
---|---
onabort | 图像加载被中断
onblur | 元素失去焦点
onchange | 用户改变域的内容
onclick | 鼠标点击某个对象
ondblclick | 鼠标双击某个对象
onerror | 当加载文档或图像时发生某个错误
onfocus | 元素获得焦点
onkeydown | 某个键盘的键被按下
onkeypress | 某个键盘的键被按下或按住
onkeyup | 某个键盘的键被松开
onload | 某个页面或图像被完成加载
onmousedown | 某个鼠标按键被按下
onmousemove | 鼠标被移动
onmouseout | 鼠标从某元素移开
onmouseover | 鼠标被移到某元素之上
onmouseup | 某个鼠标按键被松开
onreset | 重置按钮被点击
onresize | 窗口或框架被调整尺寸
onselect | 文本被选定
onsubmit | 提交按钮被点击
onunload | 用户退出页面