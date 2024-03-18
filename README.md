# imgDragZoom
img preview，zoom，drag demo

mobile-trans是最终优化版本，并且clientX的计算已经很简洁，没有优化必要

movementX，movementY，offsetX，offsetY是MouseEvent专有，touchEvent没有，无法使用。

movementX 是只读属性，它提供了当前事件和上一个mousemove事件之间鼠标在水平方向上的移动值
movementY 只读属性提供了当前事件和上一个 mousemove 事件之间鼠标在竖直方向上的移动值
offsetX 规定了事件对象与目标节点的内填充边（padding edge）在 X 轴方向上的偏移量
offsetY 规定了事件对象与目标节点的内填充边（padding edge）在 Y 轴方向上的偏移量

1. mobile-jquery 
使用jquery, 支持移动端

2. mobile-left   
拖动使用left,top坐标，支持移动端

3. pc-trans
拖动使用transform，只支持PC端

4. mobile-trans
拖动使用transform，支持移动端