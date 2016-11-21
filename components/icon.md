## 图标

WeUI 提供了几种常用的图标。

图标使用空的 `i` 标签加上相应的样式类即可，所有图标的默认大小为 23px，在 `i` 标签上追加 `weui-icon_msg` 类，大小变为 93px。

较大尺寸的图标可用于操作提示页面，图标居中显示。

### 成功

用于表示操作成功完成。

```html
<i class="weui-icon-success weui-icon_msg">
```

![](../images/icon-1.jpg)

```html
<i class="weui-icon-success-no-circle weui-icon_msg"></i>
```

![](../images/icon-6.jpg)

### 提示

用于表示信息提示，提示用户所需信息。

```html
<i class="weui-icon-info weui-icon_msg"></i>
```

![](../images/icon-2.jpg)

```html
<i class="weui-icon-info-circle weui-icon_msg"></i>
```

![](../images/icon-9.jpg)

### 普通警告

用于表示操作后会引起一定后果的情况。

注意，普通警告仅有较大尺寸，并且需要将 `weui-icon_msg` 更换为 `weui-icon_msg-primary`。

```html
<i class="weui-icon-warn weui-icon_msg-primary"></i>
```

![](../images/icon-3.jpg)

### 强烈警告

用于表示操作后会引起严重后果的情况。

```html
<i class="weui-icon-warn weui-icon_msg"></i>
```

![](../images/icon-4.jpg)

### 等待

用于表示等待。

```html
<i class="weui-icon-waiting weui-icon_msg"></i>
```

![](../images/icon-5.jpg)

### 圆圈

仅一个灰色的圆圈而已。

```html
<i class="weui-icon-circle weui-icon_msg"></i>
```

![](../images/icon-7.jpg)

### 下载

用于表示下载。

```html
<i class="weui-icon-download weui-icon_msg"></i>
```

![](../images/icon-8.jpg)

### 取消

用于表示取消。

```html
<i class="weui-icon-cancel weui-icon_msg"></i>
```

![](../images/icon-10.jpg)

### 搜索

```html
<i class="weui-icon-search weui-icon_msg"></i>
```

![](../images/icon-11.jpg)