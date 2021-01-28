## Html5

---

### <font color=#56b981>\#</font> 语义化标签

| 标签名  | 语义             |
| ------- | ---------------- |
| header  | 头部             |
| nav     | 导航             |
| article | 内容             |
| section | 定义文档某个区域 |
| aside   | 侧边栏           |
| footer  | 尾部             |

### <font color=#56b981>\#</font> 媒体

- <strong>视频:</strong> <font color=#cd69a1>video</font>

```html
<video width="320" height="240" controls>
  <source
    src="https://www.runoob.com/try/demo_source/movie.mp4"
    type="video/mp4"
  />
  您的浏览器不支持 HTML5 video 标签。
</video>
```

<video width="320" height="240" controls>
  <source src="https://www.runoob.com/try/demo_source/movie.mp4"  type="video/mp4">
  您的浏览器不支持 HTML5 video 标签。
</video>

- <strong>音频:</strong> <font color=#cd69a1>audio</font>

```html
<audio src="https://www.w3school.com.cn/i/horse.ogg" controls="controls">
  Your browser does not support the audio element.
</audio>
```

<audio src="https://www.w3school.com.cn/i/horse.ogg" controls="controls">Your browser does not support the audio element.</audio>

### <font color=#56b981>\#</font> 表单元素

- <strong>搜索:</strong> <font color=#cd69a1>search</font>

- <strong>邮件:</strong> <font color=#cd69a1>email</font>

- <strong>网址:</strong> <font color=#cd69a1>url</font>

- <strong>日期:</strong> <font color=#cd69a1>date</font>

- <strong>时间:</strong> <font color=#cd69a1>time</font>

- <strong>月:</strong> <font color=#cd69a1>month</font>

- <strong>周:</strong> <font color=#cd69a1>week</font>

- <strong>数字:</strong> <font color=#cd69a1>number</font>

- <strong>电话:</strong> <font color=#cd69a1>tel</font>

- <strong>颜色:</strong> <font color=#cd69a1>color</font>

| 属性名       | 描述                |
| ------------ | ------------------- |
| required     | 必填                |
| placeholder  | 提示水印文字        |
| autofocus    | 自动获取焦点        |
| autocomplete | off/on 历史输入记录 |
| multiple     | 可以多选文件提交    |

```html
搜索 <input type="search" /><br />
邮件 <input type="email" /><br />
网址 <input type="url" /><br />
日期 <input type="date" /><br />
时间 <input type="time" /><br />
月份 <input type="month" /><br />
一周 <input type="week" /><br />
数字 <input type="number" /><br />
电话 <input type="tel" /><br />
颜色 <input type="color" /><br />
```

搜索 <input type="search"/><br/>
邮件 <input type="email"/><br/>
网址 <input type="url"/><br/>
日期 <input type="date"/><br/>
时间 <input type="time"/><br/>
月份 <input type="month"/><br/>
一周 <input type="week"/><br/>
数字 <input type="number"/><br/>
电话 <input type="tel"/><br/>
颜色 <input type="color"/><br/>
