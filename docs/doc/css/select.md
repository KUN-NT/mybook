## 基础选择器

---

- <strong>标签选择器:</strong> <font color=#cd69a1>div{} </font> => \<div></div>

- <strong>类选择器:</strong> <font color=#cd69a1>.test{} </font> => \<div class="test"></div>

- <strong>Id 选择器:</strong> <font color=#cd69a1>.test{} </font> => \<div id="test"></div>

- <strong>通配符选择器:</strong> <font color=#cd69a1>\*</font> => 所有元素

## 复合选择器

---

- <strong>后代选择器:</strong> <font color=#cd69a1>ol li{}</font> 可以是儿子 也可以是孙子 后代就行

- <strong>子选择器:</strong> <font color=#cd69a1>div>a{}</font> 只选儿子

- <strong>并集选择器:</strong> <font color=#cd69a1>p,span{}</font> p、span 都选

- <strong>伪类选择器:</strong>

链接伪类

| 伪类名   | 状态           |
| -------- | -------------- |
| :link    | 未被访问       |
| :visited | 已访问         |
| :hover   | 鼠标位于其上   |
| :active  | 鼠标按下未弹起 |

> input:focus 选取获得焦点的表单元素
