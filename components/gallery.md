## 相册

Gallery 用于上传图片的预览或展示、幻灯片播放等。

JS 相关部分可使用 [weui.js（点击查看相关文档）](https://github.com/Tencent/weui.js/blob/master/docs/component/gallery.md) 实现，主要配合图片上传使用。

> 注意，`weui-gallery` 的 `display` 属性默认为 `none`

```html
<!-- Gallery -->
<div class="weui-gallery" style="display: block">
    <!-- 图片 -->
    <span class="weui-gallery__img" style="background-image: url(pic_article.png);"></span>
    <!-- 底部操作按钮 -->
    <div class="weui-gallery__opr">
        <a href="#" class="weui-gallery__del">
            <i class="weui-icon-delete weui-icon_gallery-delete"></i>
        </a>
    </div>
</div>
```

![](../images/gallery-1.jpg)