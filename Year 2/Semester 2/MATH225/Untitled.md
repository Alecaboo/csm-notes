$$
y''-8y'+16=0
$$
$$
y_{1}(x)=e^{4x}, y_{1}'=4e^{4x}, y_{1}''=16e^{4x}
$$
$$
\cancel{ 16e^{4x}-32e^{4x}+16e^{4x }}=0= \text{True}
$$
$$
y_{2}(x)=xe^{4x}, y_{2}'=4xe^{4x},y_{2}''=16xe^{4x}
$$
$$
\cancel{ 16ex^{4x}-32ex^{4x}+16ex^{4x }}=0= \text{True}
$$
---
$$
\begin{vmatrix}
e^{4x} & xe^{4x} \\
4e^{4x} & (4x+1)e^{4x}
\end{vmatrix} = e^{8x}(4x+1)-(4x)e^{8x}\neq 0 \therefore \text{Linearly indep}
$$

---
$$
r^{2}-8r+16 =0 = (r-4)(r-4)
$$
$$
y(x)=c_{1}e^{4x}+c_{2}xe^{4x}
$$
---
$$
1 = c_{1}e^{0}+0(c_{2}e^{0})=c_{1}
$$
$$
0 = 4e^{0}+(\cancel{ 4x }+1)c_{2}e^{0}=4+c_{2}=0, c_{2}=-4$$
$$
y=e^{4x}-4xe^{4x}
$$
----

$$
-r+3=0
$$
$$
r=3
$$
$$
y=c_{1}e^{3t}+\underbrace{ \cancel{ c_{2}xe^{3t} } }_{ \text{First order so this term is gone?} }
$$
$$
2=c_{1}e^{0}, c_{1}=2
$$
$$
y=2e^{3t}
$$

----
$$
r^{2}-3-4=0
$$
$$
(r+4)(r-1)=0
$$
$$
y=c_{1}e^{4x}+c_{2}e^{-x}
$$
$$
5= c_{1}+c_{2}
$$
$$
0=4c_{1}e^{4x}-c_{2}e^{-x}
$$
$$
c_{2} = \frac{4c_{1}e^{4x}}{e^{-x}}
$$
$$
c_{2}=4c_{1}
$$
$$
5=5c_{1}, c_{1}=1, c_{2}=4
$$
$$
y=e^{4x}+4e^{-x}
$$
-----
$$
-y'' + 3y'=0
$$
$$
r^{2}-3r-0=0
$$
$$
r^{2}=3r, r=3
$$
$$
y=c_{1}e^{3x}+c_{2}xe^{3x}
$$
---

$$
r^{2}+8r+16=0
$$
$$
(r+4)(r+4)=0
$$
$$
y=c_{1}e^{-4x}+c_{2}xe^{-4x}
$$

---
$$
r^{2}+16=0
$$
$$
r=\sqrt{ -4 }= 2i
$$
$$
y=c_{1}\cos(2x)+c_{2}\sin(2x)
$$
$$
1=c_{1}(1)+c_{2}(0), c_{1}=1
$$
$$
8=-2\sin(2x)+2c_{2}\cos(2x)
$$
$$
4=c_{2}(1), c_{2}=4
$$
$$
y=\cos(2x)+4\sin(2x)
$$
----
$$
y''+8y'+20y=0
$$
$$
r^{2}+8r+20=0
$$
$$
r= \frac{-8\pm \sqrt{ 8^{2}-80 }}{2}= \frac{-8\pm \sqrt{ -16 }}{2}= \frac{-8\pm 4i}{2}= -4\pm 2i
$$
$$
y=c_{1}e^{-4x}\cos(2x)+c_{2}e^{-4x}\sin(2x)
$$
----
$$
y''-y=5\cos(2x)-10\sin(2x)
$$
$$
r^{2}-1=0, r=1
$$
$$
y=c_{1}e^{x}+c_{2}xe^{x}
$$
$$
y_{p}=A\cos(2x)+B\sin(2x)
$$
$$
y_{p}'=-2A\sin(2x)+2B\cos(2x)
$$
$$
y_{p}''=-4A\cos(2x)-4B\cos(2x)
$$
$$
-4A\cos(2x)-4B\cos(2x)-A\cos(2x)-B\sin(2x) = 5\cos(2x)-10\sin(2x)
$$
$$
-5A\cos(2x)-5B\sin(2x)=5\cos(2x)-10\sin(2x)
$$
$$
-5A=5, A=-1 \ \ \ \ -5B = -10, B=2
$$
$$
y_{p}=-\cos(2x)+2\sin(2x)
$$
$$
y=c_{1}e^{x}+c_{2}xe^{x}-\cos(2x)+2\sin(2x)
$$
$$
0=c_{1}-1
$$
$$
c_{1}=1
$$
$$
y(0)'=0 = e^{x}+(c_{2}x+c_{2})e^{x}+2\sin(2x)+4\cos(2x)
$$
$$
0 = 1+c_{2}+4, c_{2}=-5
$$
$$
y=e^{x}-5xe^{x}-\cos(2x)+2\sin(2x)
$$

