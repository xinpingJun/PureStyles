# 安装

----

## 使用 npm 安装

推荐使用 `npm` 的方式进行开发 

```bash
npm install pure-styles
 
```

## 浏览器标签引入

可以采用传统的 `<script>` 和 `<link>` 标签的方式引入资源，并且全局使用 `pure-styles`。

可以在 [jsDelivr]() 上找到最新版本的资源文件，然后在页面中直接引入

```html
 
<!-- 引入样式 -->
<link rel="stylesheet" href="//unpkg.com/pure-styles@0.0.1/css/pure.css">
 
```

#### 示例：

通过浏览器资源标签引入的方式，我们可以迅速用 `AT-UI` 写出一个 DEMO 页面，可复制下列代码或者直接查看 [示例页面]()

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>pure-styles Example</title>
  <link rel="stylesheet" href="//unpkg.com/pure-styles@0.0.1/css/pure.css">
</head>
<body>
  <button class="pure-btn pure-btn--default" >
    <span class="pure-btn__text">default</span>
  </button>
</body>
</html>
```
