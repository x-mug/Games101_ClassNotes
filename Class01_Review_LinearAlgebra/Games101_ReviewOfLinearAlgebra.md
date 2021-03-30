<!--
 * @Author: xmug
 * @Date: 2021-03-30 23:05:12
 * @LastEditors: x-mug
 * @LastEditTime: 2021-03-31 01:56:53
 * @FilePath: \Games101\Games101_ReviewOfLinearAlgebra.md
-->

# Game101 线性代数学习笔记

## 1. 向量的点乘

### 标准定义
$$
    \vec{a} \cdot \vec{b} = ||\vec{a}|| ||\vec{b}|| \cos\theta
$$

### 一些公式

- $$
    \cos \theta = \frac {
        \vec{a} \vec{b}
    }{
        ||\vec{a}|| ||\vec{b}||
    }
  $$

- $$
    \cos \theta  = \hat{a} \hat{b}
  $$
  (hint: $\hat{a}$ 和 $\hat{b}$ 代表单位向量。且单位向量可以是任意向量，方向不必垂直)
  
- **二维**
  $$
    \vec{a} \cdot \vec{b} = 
    \begin{pmatrix}
        x_a \\ y_a 
    \end{pmatrix}
    \cdot
    \begin{pmatrix}
        x_b \\ y_b 
    \end{pmatrix}
    = x_a x_b + y_a y_b
  $$
  (hint: $x$与$y$在笛卡尔坐标系中互相垂直，因此$\cos\theta=\cos\frac{\pi}{2}=0$)
    
  **同理，三维中**
  $$
    \vec{a} \cdot \vec{b} = 
    \begin{pmatrix}
        x_a \\ y_a \\ z_a
    \end{pmatrix}
    \cdot
    \begin{pmatrix}
        x_b \\ y_b \\ z_b
    \end{pmatrix}
    = x_a x_b + y_a y_b + z_a z_b
  $$

### 由此得来的一些性质
- **向量投影**
- **获取向量夹角**
- **获取向量投影的垂直向量**(非法向量)
### 延申使用（在计算机图形学上的应用）

1. 判断向量前后
2. 判断向量距离（进行碰撞检测，范围检测）

## 2. 向量的叉乘