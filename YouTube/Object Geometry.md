## Bezier Geometry（贝塞尔几何）


当一个对象被设置为 **Bezier Geometry** 时，初始外观与 **Line Geometry（直线几何）** 看起来是一样的；
但一旦设置为 Bezier，你就可以在**每一个控制点（Control Point）** 上创建 **最多两个切线点（Tangent Points）**。

每个控制点最多可有 2 个切线点（蓝色），Ctrl+拖动创建，右键 > 重置删除


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


| Item                | Line                       | Spline            | Bezier                     |
| ------------------------- | ---------------------------------------------- | ------------------------------------------ | ----------------------------------------------- |
| 线条类型 (Line Type)          | 直线 (Straight line)                             | 平滑曲线 (Smoothed curve)                      | 可控曲线 (Controlled curve)                         |
| 是否平滑 (Smoothness)         | 否 (No)                                         | 是，受张力影响 (Yes, tension adjustable)          | 是，可用切线精确控制 (Yes, tangent-controlled)            |
| 精确度 (Accuracy)            | 高 (High)                                       | 中等 (Medium)                                | 高，可精确调整 (High, precise control)                 |



