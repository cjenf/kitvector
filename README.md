# Vector
### This package has basic Vector operations (not suitable for machine learning).
```py
pip install kitvector
```
> [!NOTE]
> **This module is just some basic vector operations.**
## Usage
### Suppose you have: 

$$
 \vec{v}=(v_1, v_2, v_3)<br>
$$
 
$$
 \quad and
$$
 
$$
 \vec{u}=(u_1, u_2, u_3)
$$
```py
import kitvector
v=kitvector.Vector((1, 2, 3))
u=kitvector.Vector((4, 5, 6))
```
## mul_k
> [!NOTE]
> **Multiply the vector u by a scalar k.**

$$
 \vec{u}=(u_1, u_2, u_3)⋅𝑘
$$
```py
v.mul_k(3) # output: Vector(3, 6, 9)
```
## dot
> [!NOTE]
> **The inner product of the vector.**

$$
\vec{v} \cdot \vec{u}
$$

```py
Vactor.dot(v, u)
```
## cross
> [!NOTE]
> **The outer product of the vector.**

$$
\vec{v} × \vec{u}
$$

```py
Vactor.cross(v, u)
```
## magnitude
> [!NOTE]
> **The size of the vector.**

$$
∥\vec{v}∥
$$

```py
v.magnitude # output: 3.7416573867739413
```
## unit_vector
> [!NOTE]
> **Unit Vector.**

$$
\vec{v}^
$$

```py
v.unit_vector
```
