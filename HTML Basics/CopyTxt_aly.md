# 分析Event.html
[copyTxt.html](copyTxt.html)
### type标签属性
#### 作用
规定要显示的 input 元素的类型

### id 标签属性
#### 作用
规定HTML元素的唯一id
id必须是**唯一**的
id属性可用作链表锚（link anchor），通过JavaScript 或者CSS为带有指定id 的元素添加样式

### button
#### 作用
<button>标签定义一个按钮</button>
#### value属性
规定了 form 中<button>button</button>的**初始值**

### 补充
#### 全局事件

- **windows 窗口事件**
  - onload: 在网页加载后添加
  - onunload: 在用户从页面离开时触发，如单击跳转、页面重载、关闭浏览器创库等

- **Form 表单事件**
  - onblur: 当元素失去焦点时触发。
  - onchange: 当元素的元素值被改变时触发。
  - onfocus: 当元素获得焦点时触发。
  - onreset: 当表单中的重置按钮被单击时触发。
  - onselect: 在元素中文本被选中是触发。
  - onsubmit: 在提交表单时触发。

- **keyboard**
  - onkeydown: 在用户按下按钮是触发。
  - onkeypress: 在用户按下按钮后，按着按钮时触发。该属性不会对所有按键生效，如：alt、ctrl、shift、esc


- **mouse**
  - onclick:     当在元素上单击鼠标时触发
  - ondblclick:  当在元素上双击鼠标时触发
  - onmousedown: 当在元素上按下鼠标按钮时触发
  - onmousemove: 当鼠标指针移动到元素上方时触发
  - onmouseout:  当鼠标移出元素时触发
  - onmouseover: 当鼠标移动到元素上时触发
  - onmouseup:   当在元素上释放鼠标按钮时触发
- **media**
- onabort:当退出媒体播放器时触发。
- onwaiting:当媒体已停止播放当打算继续播放时触发。
