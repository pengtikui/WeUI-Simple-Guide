## 快速上手

首先需要说明，WeUI 仅仅是一个样式库而已，其核心文件是 `weui.css` ，所以与 JS 相关的功能需要自己实现，此入门指南所讲内容也仅限于 `weui.css` ，jQuery 版、Vue.js 版、React 版等均不在本文范围内，具体请参阅相应的文档。

> 与 JS 相关功能推荐使用微信官方的 weui.js，具体介绍及文档请参阅：https://github.com/Tencent/weui.js

### 1.0 改动

WeUI 1.0 版本相比于 0.4.x 版本增加了一些组件，比如 Flex 布局、Footer 等。但比较大的变化是采用了 BEM 命名规范，绝大多数的类名都变了，这也是重写这个入门指南的原因。

> BEM 命名规范不在本文讲述范围内，请自行搜索了解、学习。

### 相关链接：

* GitHub：https://github.com/Tencent/weui
* 官方 Wiki：https://github.com/Tencent/weui/wiki
* 下载地址：https://github.com/Tencent/weui/releases
* Demo：https://weui.io
* 官方 QQ 群：478234996

### 下载

可以通过上述下载地址下载最新版的 WeUI，而且每个版本都会有简略的更新日志。

本文以目前的最新版本 1.0.2 为例，下载后我们使用 `dist/style` 文件中的 `weui.css` 和 `weui.min.css` 两个文件。`weui.min.css` 是 `weui.css` 压缩后的版本，体积更小，建议在生产环境使用。

> 如果你需要修改一些样式，建议新建一个 css 文件覆盖原样式而不是修改原文件。

### 基本模板

将下载后得到的 `weui.min.css` 放在你项目的任意位置，然后在页面内引用即可，比如我将其放在根目录下的 `css` 文件夹内，下面给出一个简单的 HTML 模板。

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=0">
    <title>WeUI</title>
    <link rel="stylesheet" href="css/weui.min.css">
</head>
<body ontouchstart>
    <!-- Your Code -->
</body>
</html>
```

> 注意不要忘了 viewport 的 meta 标签和 body 的 `ontouchstart` 属性。