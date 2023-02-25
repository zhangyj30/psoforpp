## 说明
- 代码在 Python 3.6 中进行编写和测试。
- 用法：python test.py ex1（1、2、3）

```
# 指定目录下运行
python test.py ex1
```
- 可以py中更改起始位置、目标位置和障碍物位置以模拟运动。

`Start`：起点坐标。

`Goal`：终点坐标。

`Limits`：PSO 中地图和搜索空间的上下边界。

`nRun`：运行次数。

`nPts`：定义样条的内部点数。

`nPop`：代理数量

`epochs`：迭代次数。

## 示例

共有2个示例，使用相同的障碍物

### 示例 1:

运行15次  
使用三次样条插值  
随机初始化  
没有越障  

### 示例 2

运行15次  
使用二次样条插值  
初始化为起始位置和目标位置之间的直线   
在第 8、9、13、14 和 15 轮中发生碰撞