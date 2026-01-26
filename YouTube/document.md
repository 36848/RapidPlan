Base Map Bearing底图方位角- when choose map location  a icon to adjust/   chgnage properties + use ctrl to modiify

Auto Template- click next- defind road width/ working area


Selection modes
Selection1 New selection (default)
Selection2 Add to selection (hold Shift key)
Selection3 Remove from selection (hold Alt key)


 keep your control points in a perfectly straight line by holding down the Shift key( like don;t work

 Adding/Deleting a Control Point = click line/shape - edit geometry-- insert control point 


 ## Bezier Geometry（贝塞尔几何）

当一个对象被设置为 **Bezier Geometry** 时，初始外观与 **Line Geometry（直线几何）** 看起来是一样的；
但一旦设置为 Bezier，你就可以在**每一个控制点（Control Point）** 上创建 **最多两个切线点（Tangent Points）**。


## 如何创建切线点（Tangent Point）

在对象已设置为 **Bezier Geometry** 的情况下：

* **按住 `Ctrl` 键**
* **点击并拖动红色控制点**

即可创建切线点并调整曲线形状。

---

## 如何重置（删除）切线点

如果需要移除或重置切线点：

* **右键点击切线点**
* 选择 **“Reset Control Point（重置控制点）”**

切线点将被重置，曲线会恢复为未弯曲状态。


 | 对比项 (Item) | Polyline（折线 / Polyline） | Bezier（贝塞尔 / Bezier Curve） |
|-------------|----------------------------|----------------------------------|
| 线条类型 (Line Type) | 直线 (Straight lines) | 平滑曲线 (Smooth curves) |
| 是否平滑 (Smoothness) |  否 (No) | 是 (Yes) |
| 精确度 (Accuracy) | 高 (High) | 较低 (Lower) |
| 编辑难度 (Editing Difficulty) | 简单 (Easy) | 较复杂 (More complex) |
| 适合用途 (Best Use Cases) | 工程、测量、结构 (Engineering, measurement, structure) | 设计、美观、自然曲线 (Design, visual appeal, natural curves) |
============
still confused on this - document location == Object Geometry
