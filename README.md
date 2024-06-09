# 3D-GS-paper

## SplaTAM

### 论文框架：

![alt text](splaTAM.png)

Step (1) estimates the camera pose for the new image, using silhouette-guided differentiable rendering.
Step (2) increases the map capacity by adding new Gaussians based on the rendered silhouette and input depth. 
Step (3) updates the underlying Gaussian map with differentiable rendering.

### 论文创新点：

1. Fast rendering and dense optimization
2. Maps with explicit spatial extent
3. Direct optimization of scene parameters

**其实是使用了类似光流法进行了位姿估计** ：具体估计公式 ![alt text](eq-1.png)


### 论文现有缺点：

1. 在定位性能上依旧是稀疏特征点方法更好一些
2. 对运动模糊、大尺度噪声、侵略性旋转效果不好


### 代码地址：
https://github.com/spla-tam/SplaTAM

## Gaussian Splatting SLAM

论文框架：

论文创新点：

论文现有缺点：

代码地址：https://github.com/muskie82/MonoGS
