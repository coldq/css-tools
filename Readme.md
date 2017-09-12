### 基于FlexBox的栅格系统

简单的栅格系统。

将页面分成12分，从1-12 : 分别为 `col-n `。

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

[demo](https://coldq.github.io/grid/index.html)

