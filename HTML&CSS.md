### HTML

#### 注释

1. 格式`<!-- 注释内容 -->`
2. vscode 中的快捷键`ctrl + /`

#### 元素

1. 元素 = 起始标记 + 元素属性 + 元素内容 + 结束标记
   - `<a href="http://www.baidu.com">百度一下</a>`
   - `<div class="wrapper"></div>`
2. 有些元素是没有结束标记的
   - `<meta charset="UTF-8" />`
   - `<img src="" alt="">`
3. 不同的元素有不同的功能

##### a 标签

##### html 标签（根标签）

根元素，一个页面最多只能有一个，并且该元素是所有其他元素的父元素或者祖先元素
html5 版本中没有强制要求书写该元素（仅作为了解）

```html
<html lang="en"></html>
```

- lang 属性：language，全局属性，表示该元素内部使用的文字是使用哪一种自然语言书写而成的。
  - 改为使用汉语，`<html lang="zh-CN"></html>`，或者`<html lang="cmn-hans"></html>`，其实现在应该使用的是`lang="cmn-hans"`

##### head 标签

文档头，文档头部的内容，不会显示到页面上。

```html
<head></head>
```

##### meta 标签

文档的元数据：附加信息

```html
<!-- 告诉浏览器，网页使用的编码格式为 UTF-8 -->
<meta charset="UTF-8" />

<!-- 适配移动端 -->
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<!-- 告诉浏览器，如果当前是 ie 浏览器，使用 edge 这个内核来渲染 -->
<meta http-equiv="X-UA-Compatible" content="ie=edge" />
```

#### 属性

##### 局部属性

某些标签特有的属性

##### 全局属性

所有元素通用

1. title
   鼠标 hover 上去（移上去）的时候有个提示效果

   ```html
   <div title="学习html的第一天">把鼠标移上来试试看</div>
   ```

   **效果图**：
   ![效果图](assets/火星图片_20200808_151556.png)

#### 未分类

1. `<!DOCTYPE html>`，文档声明，作用是告诉浏览器，当前文档使用的 HTML 的标准是 HTML5，不写文档声明，将导致浏览器进入怪异渲染模式

### CSS
