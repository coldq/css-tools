### 基于FlexBox的栅格系统

几十行`css` , 简单的栅格系统。

将页面分成12分，从1-12 : 分别为 `col-n `。

针对`IE9` 以及下版本不支持`Flex`，将`col-n` 用浮动 + 百分制简单 `hack` 了一下。但对自动适应等 `flex` 特性没有实现。

#### 使用：

```html
<div class="grid">
     <div class="grid-cell">均分</div>
     <div class="grid-cell">均分</div>
     <div class="grid-cell">均分</div>
     <div class="grid-cell">均分</div>       
</div>
<div class="grid">
      <div class="grid-cell col-3">3/12</div>
      <div class="grid-cell col-2">2/12</div>
      <div class="grid-cell">自适应</div>
      <div class="grid-cell col-6">6/12</div>       
</div>
```

#### demo

[demo](https://coldq.github.io/css-tools)

####  兼容测试

`FF √ ` 

` Chrome √`

`Edge √`

`IE10+ √`