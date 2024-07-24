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
Vactor.dot((1, 2, 3),(4, 5, 6))
```
## cross
> [!NOTE]
> **The outer product of the vector.**

$$
\vec{v} × \vec{u}
$$

```py
Vactor.cross((1, 2, 3),(4, 5, 6))
```
