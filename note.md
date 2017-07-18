
变形(transform)、转换(transition)和动画(animation)

transform的几个属性
旋转rotate
移动translate
矩阵matrix
扭曲skew
缩放scale
改变元素基点transform-origin

transition的几个属性
执行变换的属性：transition-property,
变换延续的时间：transition-duration,
在延续时间段，变换的速率变化transition-timing-function,
变换延迟时间transition-delay。

animation-name: 申明动画@keyframes的名称.
animation-duration: 动画在多久内完成一个周期.
animation-timing-function: 设置预加速度曲线动画,例如 ease 或者linear.
animation-delay: 动画延迟执行的时间.
animation-direction: 设定动画执行完成后的方向.默认是起始开始执行.
animation-iteration-count: 动画执行的次数.
animation-fill-mode:设定动画是执行之前还是之后.
animation-play-state: 开始或者暂停动画


:before和:after这两个主要用来给元素的前面或后面插入内容

css实现超出文本框变成省略号
white-space: nowrap;  
overflow: hidden;  
text-overflow: ellipsis;
浏览器默认情况下令1em === 16px

首字下沉
.raised-cap::first-letter { initial-letter: 3 1; }第一个值表示的行高，第二个表示沉度