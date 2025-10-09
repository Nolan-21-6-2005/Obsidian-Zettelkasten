---
tags:
  - AI/Caculus
---
> Grandient là [[Drivative|đạo hàm]] riêng của một hàm nhiều biến $f(x,x_1,x_2, ... x_n)$

$$
\nabla f = \left(\frac{\partial f}{​\partial x_1}​, \frac{\partial f}​{\partial x_2}​,…,\frac{\partial f}​{\partial x_n}​\right)
$$
# Gradient Descent
Mục đích: Tối ưu [[Loss Function|hàm mất mát]].
$$
θ_{k+1}​=θ_k​−η⋅∇f(θ_k​)
$$
- $θ_{k+1}$ vector tham số mới.
- $θ_{k}$ vector tham số cũ.
- $∇f(θ_k​)$ loss function với tham số là vector tham số cũ.
