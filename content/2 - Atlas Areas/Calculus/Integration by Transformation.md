# Case I
Product of the form $\sin(au)\cdot \sin(bu)$, $\sin (au)\cdot \cos(bu)$, and $\cos(au)\cdot \cos(bu)$, where $a$ and $b$ are constants and can be integrated by the use of transformations. 

$$
\begin{aligned}
\sin A\sin B&=\frac{1}{2}\cos(A-B)-\frac{1}{2}\cos(A+B) \\[1.5ex] 
\sin A\cos B&=\frac{1}{2}\sin(A-B)+\frac{1}{2}\sin(A+B) \\[1.5ex]
\cos A\cos B&=\frac{1}{2}\cos(A-B)+\frac{1}{2}\cos(A+B)
\end{aligned}
$$
![[Calculus#^group=yXcQIMAl4T8-WJm4K_Y7V|700]]
# Case II
A product of the term $\sin^m u\cos^n u$, where either $m$ or $n$ is a positive integer, can be integrated by the use of trigonometric identities.
$$
\tag{2}
\begin{aligned}
\sin^2u&=1-\cos^2u \\[1.25ex]
\cos^2u&=1-\sin^2u
\end{aligned}
$$
If one exponent is **odd**:
- $\int{\sin^2x\cos^3xdx}$
# Case III
A product of the term $\sin^m u\cos^n u$, where either $m$ and $n$ are both positive **even** integers, can be integrated by the use of trigonometric identities.
$$
\tag{3}
\begin{aligned}
\cos^2{u}&=\frac{1}{2}+\frac{1}{2}\cos{2u} \\[1.25ex]
\sin^2u&=\frac{1}{2}-\frac{1}{2}\cos{2u}
\end{aligned}
$$
If both exponents are **even**.
- $\int{\cos^2x\sin^2xdx}$
# Case IV
A power of the form $\tan^n{u}$ or $\cot^n{u}$, where $n$ is a positive **odd** integer, can be integrated by use of transformation.
$$
\begin{aligned}
\tan^2u&=\sec^2u-1 \\[1.25ex]
\cot^2u&=\csc^2u-1
\end{aligned}
$$
If integrating a **single** $\tan$ or $\cot$ function with an **odd** exponent.
- $\int{\tan^3xdx}$

# Case V
A power of the form $\sec^n{u}$ or $\csc^n{u}$, where $n>2$ is a positive **even** integer, can be integrated by use of transformation.
$$
\begin{aligned}
\sec^2u&=\tan^2u+1 \\[1.25ex]
\csc^2u&=\cot^2u+1
\end{aligned}
$$
If integrating a **single** $\sec$ or $\csc$ function with an **even** exponent.
- $\int{\sec^4xdx}$

# Case VI
A product of the form $\tan^m u\sec^n u$ or $\cot^m u\csc^n u$, where $m$ and $n$ are positive integers, can be integrated:
1. If $n$ is **even**, then apply Case V
2. If $m$ is **odd**, isolate one $\sec u\tan u$ or $\csc u\cot u$, and use trigonometric identities.
$$
\begin{aligned}
\tan^2u&=\sec^2u-1 \\[1.25ex]
\cot^2 u&=\csc^2 u-1
\end{aligned}
$$
If integrating a **double** $\tan \sec$ or $\csc \cot$ function.
- $\int{\tan^2x\sec^4xdx}$, apply **Case IV**.
- $\int{\tan^3x\sec^3xdx}$, apply **Case V**.
