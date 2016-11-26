## 页脚

页脚主要用于在页面底部显示相关版权信息和相关链接等。

WeUI 提供的页脚主要有三种样式。

### 样式一

只有一行文字，无链接。

```html
<div class="weui-footer">
    <p class="weui-footer__text">Copyright © 2016 Paranoid_K</p>
</div>
```

![](../images/footer-1.jpg)

### 样式二

一行文字和一个链接。

```html
<div class="weui-footer">
    <p class="weui-footer__links">
        <a href="#" class="weui-footer__link">底部链接</a>
    </p>
    <p class="weui-footer__text">Copyright © 2016 Paranoid_K</p>
</div>
```

![](../images/footer-2.jpg)

### 样式三

一行文字和多个链接，链接数建议不要过多，以免影响页面美观度。

```html
<div class="weui-footer">
    <p class="weui-footer__links">
        <a href="#" class="weui-footer__link">底部链接</a>
        <a href="#" class="weui-footer__link">底部链接</a>
    </p>
    <p class="weui-footer__text">Copyright © 2016 Paranoid_K</p>
</div>
```

![](../images/footer-3.jpg)

如果页面内容不足以撑起整个屏幕高度，又想让页脚在屏幕最底部，可以添加一个 `weui-footer_fixed-bottom` 样式类使页脚固定在屏幕底部。

```html
<div class="weui-footer weui-footer_fixed-bottom">
    <p class="weui-footer__links">
        <a href="#" class="weui-footer__link">底部链接</a>
    </p>
    <p class="weui-footer__text">Copyright © 2016 Paranoid_K</p>
</div>
```
