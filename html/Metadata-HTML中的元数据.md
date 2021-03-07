# Metadata-HTML中的元数据

### 添加标题

`  <title>`可以为文档添加标题。`<h1>` 元素，是为 body 添加标题的。有时候 `<h1>`也叫作网页标题。但是二者并不相同。

元数据就是描述数据的数据，而HTML有一个“官方的”方式来为一个文档添加元数据——  `<meta>`元素。

许多`<meta>` 元素包含了`name` 和 `content` 特性：

- `name` 指定了meta 元素的类型； 说明该元素包含了什么类型的信息。
- `content` 指定了实际的元数据内容。

### 增加自定义图标

页面添加图标的方式有：

1. 将其保存在与网站的索引页面相同的目录中，以.ico格式保存（大多数浏览器将支持更通用的格式，如.gif或.png，但使用ICO格式将确保它能在如Internet Explorer 6一样久远的浏览器显示）
2. 将以下行添加到HTML `<head>`中以引用它：

```
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

