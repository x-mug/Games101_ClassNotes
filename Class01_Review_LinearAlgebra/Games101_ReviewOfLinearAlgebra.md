<!--
 * @Author: xmug
 * @Date: 2021-03-30 23:05:12
 * @LastEditors: x-mug
 * @LastEditTime: 2021-03-31 01:42:01
 * @FilePath: \Games101\Games101_ReviewOfLinearAlgebra.md
-->

# Game101 线性代数复习笔记

## 1. 向量的点乘

#### 标准定义
$$
    \vec{a} \cdot \vec{b} = ||\vec{a}|| ||\vec{b}|| \cos\theta
$$

#### 一些公式

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
  
- 二维
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
    
  同理，三维中
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
#### 延申使用

1. 

## 2. 向量的叉乘