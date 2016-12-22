# JavaScript-parabola-trajectory
parabola trajectory implement by JavaScript

JavaScript实现的抛物线轨迹工具

在不超出屏幕范围的前提下，尽量抛得更高

# DEMO

[See Demo!](http://codepen.io/musiq/pen/EgvdyE)

# options

`options` Object


`options.startPos` Object 起始位置 (必需)

`options.startPos.left` Number 起始X位置

`options.startPos.top` Number 起始Y位置


`options.endPos` Object 结束位置 (必需)

`options.endPos.left` Number 结束X位置

`options.endPos.top` Number 结束Y位置


`options.duration` Number 动画持续时间 (默认为2000ms)

`options.timingFunction` String 动画效果 可选值 `easeIn` `easeOut` `easeInOut` `linear` (默认linear)

`options.onStep` Function 动画过程每帧回调 接受当前计算出的位置参数

`options.onFinish` Function 动画完成回调 接受当前计算出的位置参数

# methods

`start` 开始抛物线动画

# 更新记录

# 2016-10-08
* 添加缓动函数效果

