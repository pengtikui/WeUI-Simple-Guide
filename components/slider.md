## 滑块

滑块可用于用户输入数值的一种方式，WeUI 中仅包含 CSS 样式，JS 部分可自行实现或使用 [weui.js（点击查看相关文档）](https://github.com/weui/weui.js/blob/master/docs/component/slider.md)。

```html
<!-- 滑块 -->
<div class="weui-slider-box">
    <div class="weui-slider">
        <div class="weui-slider__inner">
            <div class="weui-slider__track" style="width: 62%;"></div>
            <div class="weui-slider__handler" style="left: 62%;"></div>
        </div>
    </div>
    <!-- 显示数值，可选 -->
    <div class="weui-slider-box__value">62</div>
</div>
```

`weui-slider__track` 的 `width` 属性和 `weui-slider__handler` 的 `left` 属性表示滑块的进度，且两者的值相同。

![](../images/slider-1.jpg)