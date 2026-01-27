## Base Map Bearing (旋转)
- When choosing a map location, an icon appears to **adjust/change angle**.  
- Use **Ctrl** to modify.


## Auto Template
1. Click **Next**.  
2. Define: Road width  / Working area  


## Selection Modes
| Mode | Action | Shortcut |
|------|--------|---------|
| Selection 1 | New selection (default) | - |
| Selection 2 | Add to selection | Hold **Shift** |
| Selection 3 | Remove from selection | Hold **Alt** |

 ###Holding down **Shift** should keep control points in a perfectly straight直线 line. ( like don't work


## Control Points and Snapping

### Adding and Deleting Control Points
- **Add Control Point:** Click on the line/shape → **Edit Geometry** → **Insert Control Point**  
- **Delete Control Point:** Select point → **Right-Click** → **Remove Control Point**

### Control Point Snapping
- Two objects' geometry will **automatically align and merge**.  两个对象的几何形状就会自动对齐并合并
- **Ctrl**: Snap within the same layer  
- **Ctrl + Alt**: Snap across multiple layers  
- **Alt**: Create reference lines for tangent, vertical, and midpoint alignment切线、垂直线以及几何体中点的参考线


## Offsetting Geometry
- **Edit Geometry → Offset Geometry**  
- Options:  
  - **Move**: Shift the object  
  - **Round Corners**: Smooth curves when offsetting 偏移对象时平滑曲线 
  - **Copy**: Duplicate the geometry while offsetting

## Dimensions Input Panel
When drawing
- Distance [D], d : Enter a distance, e.g., x m, press Enter → a red circle appears.
- Angle [A], a :Enter an angle, press Enter → shows the angle direction.
- Offset [O], use (x,y) move x,y   
   - X：水平方向的偏移距离Y：垂直方向的偏移距离
   - Offset 工具就是：从上一个控制点出发，用 X、Y 数值精确“平移”出下一个控制点


no need have a drawing object 
- Point [P] (x,y)
- Coordinates [C] (35.1561, -90.0519) - latitude and longitude

## resizing objkects
| 对比 / Comparison           | **Control Points (控制点缩放)**                                       | **Resize Handles (缩放手柄)**                                         |
| ------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------- |
| **作用 / Effect**           | 改变对象形状 / Change object shape                                     | 只改变大小，不改变形状 / Change size only                                    |
| **内部元素 / Internal parts** | 可以增加或减少（例如轨枕数量） / Can add/remove parts                           | 保持不变 / Stay the same                                              |
| **比例 / Proportion**       | 局部可变 / Local can change                                          | 可锁定比例 / Can lock proportion                                       |
| **示例 / Example**          | 5 根轨枕 → 移动控制点 → 11 根轨枕 / 5 sleepers → moved points → 11 sleepers | 5 根轨枕 → 缩放手柄 → 仍然 5 根轨枕 / 5 sleepers → resized → still 5 sleepers |


hold **Shift** while you resize, the length to width ratio of your object will be maintained

**ctrl + alt** - resize on 3d

## Setting Custom Scale and Rotation Points
first select object
 
Transform → Scale → Point/Center: choose scale point or center

Transform → Rotate → Select Rotation Point → 90°/180°/custom angle



## Moving, Flipping and Rotating Objects Moving Objects

- Moving Objects: Hold Shift for orthogonal movement (like AutoCAD)

- Rotating Objects:

  - Ctrl + R: rotate 90°

  - Ctrl + Alt + R: micro rotate clockwise

  - Ctrl + Alt + E: micro rotate counter-clockwise


## Grouping Objects

 Group: select objects → Ctrl + G

Ungroup: select group → Ctrl + U

### Cropping Objects: Edit → Cropping

 
