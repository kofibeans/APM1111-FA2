FA2
================
Leiana Mari D. Aquino
2023-09-12

### **Instructions**

Answer Exercises 3.49, 3.51, and 3.90.

You may submit Python, R, Latex, or any file as long as proofs of 3.49
and 3.51 are clear and in good formatting.

------------------------------------------------------------------------

#### **Exercise 3.49**

Prove that
$\Sigma_{j=1}^N (X_j-1)^2 = \Sigma_{j=1}^N X_j^2-2\Sigma_{j=1}^N X_j+N$

$$
\begin{aligned}
\text{LHS} &= \Sigma_{j=1}^N (X_j-1)^2 \\\\\\
& = \Sigma_{j=1}^N (X_j^2-2X_j+1) \\\\\\
& = \Sigma_{j=1}^N X_j^2-\Sigma_{j=1}^N2X_j+\Sigma_{j=1}^N \\\\\\
& = \Sigma_{j=1}^N X_j^2-2(\Sigma_{j=1}^N)X_j+N \\\\\\
& =\text{RHS } \square
\end{aligned}$$

------------------------------------------------------------------------

#### **Exercise 3.51**

Two variables, $U$ and $V$, assume the values $U_1=3$, $U_2=-2$,
$U_3=5$, and $V_1=-4$, $V_2=-1$, $V_3=6$, respectively. Calculate the
following:

1.  $\Sigma UV$

$$
\begin{aligned}
\Sigma UV &= U_1V_1 + U_2V_2 + U_3V_3 \\\\\\
& = (3)(-4) + (-2)(-1) + (5)(6) \\\\\\
& = -12 + 2 + 30 \\\\\\
& = 20
\end{aligned}$$

2.  $\Sigma (U+3)(V-4)$

$$
\begin{aligned}
\Sigma (U+3)(V-4) &= (U_1+3)(V_1-4) + (U_2+3)(V_2-4) + (U_3+3)(V_3-4) \\\\\\
& = (3+3)(-4-4) + (-2+3)(-1-4) + (5+3)(6-4)  \\\\\\
& = 6(-8) + 1(-5) + 8(2) \\\\\\
& = -37
\end{aligned}$$

3.  $\Sigma V^2$

$$
\begin{aligned}
\Sigma V^2 &= V_1^2 + V_2^2 + V_3^2 \\\\\\
& = (-4)^2 + (-1)^2 + (6)^2 \\\\\\
& = 16 + 1 + 36  \\\\\\
& = 53
\end{aligned}$$

4.  $(\Sigma U)(\Sigma V)^2$
   
$$
\begin{aligned}
\Sigma (\Sigma U)(\Sigma V)^2 &= (U_1 + U_2 + U_3)(V_1 + V_2 + V_3)^2  \\\\\\
& = (3 - 2 + 5)(-4 - 1 + 6)^2  \\\\\\
& = 6(1)^2  \\\\\\
& = 6
\end{aligned}$$

5.  $\Sigma UV^2$

$$
\begin{aligned}
\Sigma UV^2 &= U_1V_1^2 + U_2V_2^2 + U_3V_3^2  \\\\\\
& = (3)((-4)^2) + (-2)(-1^2) + (5)(6^2)  \\\\\\
& = 48 - 2 + 180 \\\\\\
& = 226
\end{aligned}$$

6.  $\Sigma (U^2 - 2V^2+2)$

$$
\begin{aligned}
\Sigma (U^2 - 2V^2+2) &= (U_1^2 - 2V_1^2 + 2) + (U_2^2 - 2V_2^2 + 2) + (U_3^2 - 2V_3^2 + 2)  \\\\\\
& = (3^2 - 2(-4)^2 + 2) + (-2^2 - 2(-1)^2 + 2) + (5^2 - 2(6)^2 + 2 \\\\\\
& = (9 - 32 + 2) + (4 - 2 + 2) + (25 - 72 + 2) \\\\\\
& = -21 + 4 - 45 \\\\\\
& = -62
\end{aligned}$$

7.  $\Sigma (U/V)$

$$
\begin{aligned}
\Sigma (U/V) &= U_1/V_1 + U_2/V_2 + U_3/V_3 \\\\\\
& = -\frac{3}{4} + 2 + \frac{5}{6}  \\\\\\
& = \frac{-9+24+10}{12} \\\\\\
& = \frac{25}{12}
\end{aligned}$$

------------------------------------------------------------------------

#### **Exercise 3.90**

Find the geometric mean of the sets (a) 3, 5, 8, 3, 7, 2 and (b) 28.5,
73.6, 47.2, 31.5, 64.8.

1.  $\sqrt[6]{(3)(5)(8)(3)(7)(2)} = 4.14$
2.  $\sqrt[5]{(28.5)(73.6)(47.2)(31.5)(64.8)} = 45.83$
