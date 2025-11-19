https://developer.mozilla.org/zh-CN/docs/Web/SVG/Reference/Attribute/d

path 


MoveTo：M、m
LineTo：L、l、H、h、V、v
三次贝塞尔曲线：C、c、S、s
二次贝塞尔曲线：Q、q、T、t
椭圆曲线：A、a
ClosePath：Z、z


大写是绝对坐标  小写是当前位置的相对坐标

LineTo  L 是 x y eg. L 10 20 从当前位置画线到 10 20的位置
LineTo  H 是 代表 画线水平到哪里   eg. H 10 从当前位置画线到 水平10的位置 纵向保持不变
LineTo  V 是 代表 画线垂直到哪里   eg. V 10 从当前位置画线到 垂直10的位置 横向保持不变
