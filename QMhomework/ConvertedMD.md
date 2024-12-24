### 量子力学作业

------------------------------------------------------------------

### 目录

Homework(1)20240905 Homework(2)20240930 Homework(3) 20241010 Homework(4)20241011 Homework(5)20241014 Homework(6) 20241017 Homework(7) 202410218omework(8)20241024 Homework(9)20241025 Hbmework(10)20241031附录附录1附录2附录3附录4附录5附录6附录7附录8附录9附录10附录11附录12附录13附录14附录15附录16

------------------------------------------------------------------

### 1Homework(1) 20240905

(1) Proof when θ=π $\theta=\pi$ $\theta=\pi,\lambda^{'}-\lambda=\frac{2h}{m_ec}$

![](https://storage.simpletex.cn/view/fNvh51cG1AwzdgE82gW5qpLCgOtzg6Lwa)

由能量守恒：

由动量守恒：

$$h\nu+m_ec^2=h\nu'+mc^2$$

$$\frac{h\nu}{c}_0=\frac{h\nu'}{c}\vec{n}+m\vec{v}$$

$$\vec{n}=-\overrightarrow{n_0}$$

$$E^2=p^2c^2+m_e^2c^4$$

由于

将(1.3)和(1.4)代人(1.2)可得：

$$\frac{h\nu}{c}\overrightarrow{n_0}-\frac{h\nu'}{c}\vec{n}=m\vec{v}$$

$$h^2\nu^2+2h^2\nu\nu'+h^2\nu'^2=p^2c^2$$

对(1.1)进行移项，并对两边取平方可得；

$$h^2\nu^2-2h^2\nu\nu'+h^2\nu'^2=m^2c^4-2m_emc^4+m_e^2c^4$$

联立(1.6)和(1.7)可得；

$$-4h^2\nu\nu'=2m_e^2c^4-2m_emc^4$$

$$\begin{matrix}2h^2\nu\nu'=m_ec^2(mc^2-m_ec^2)\end{matrix}$$

$$\begin{matrix}2h^2\nu\nu'=m_ec^2(h\nu-h\nu')\end{matrix}$$

------------------------------------------------------------------

$$\begin{aligned}\frac{2h}{m_ec^2}=\frac{1}{\nu'}-\frac{1}{\nu'}\end{aligned}$$

$$\frac{2h}{m_ec}=\lambda'-\lambda $$

即当$\theta=\pi$ 时$,\lambda^{\prime}-\lambda=\frac{2h}{m_{e}c}$

$$_{1}\theta\neq\pi,\lambda^{^{\prime}}-\lambda=\frac{h}{m_{e}c}(1-cos\theta)$$

![](https://storage.simpletex.cn/view/fbBaZrST6TQ0t3vgDn2YWpRUaLms14YiE)

由能量守恒：

$$h\nu+m_ec^2=h\nu'+mc^2$$

由动量守恒：

$$\frac{h\nu}{c}_0=\frac{h\nu'}{c}\vec{n}+m\vec{v}$$

由于

$$\frac{\overrightarrow{n_0}\cdot\vec{n}}{|\overrightarrow{n_0}||\vec{n}|}=\overline{n_0}\cdot\vec{n}=cos\:\varphi $$

$$E^2=p^2c^2+m_e^2c^4$$

将(1.15)和(1.16)代入(1.14)可得：

$$(\frac{h\nu}{c}\overrightarrow{n_0}-\frac{h\nu'}{c}\vec{n})^2=p^2$$

$$h^2\nu^2-2h^2\nu\nu'\:cos\:\varphi+h^2\nu'^2=p^2c^2$$

------------------------------------------------------------------

对(1.13)进行移项，并对两边取平方可得：

$$h^2\nu^2-2h^2\nu\nu'+h^2\nu'^2=m^2c^4-2m_emc^4+m_e^2c^4$$

联立(1.18)和(1.19)可得；

$$\begin{matrix}2h^2\nu\nu'(-1+cos\:\varphi)=2m_e^2c^4-2mm_ec^4\end{matrix}$$

$$h^2\nu\nu'(-1+cos\:\varphi)=m_ec^2(m_ec^2-mc^2)$$

$$h^2\nu\nu'(-1+cos\:\varphi)=m_ec^2(h\nu'-h\nu)$$

$$\begin{aligned}\frac{h}{m_ec^2}(1-cos\:\varphi)=\frac{-1}{\nu}+\frac{1}{\nu'}\end{aligned}$$

$$\frac{h}{m_ec}(1-cos\:\varphi)=\lambda'-\lambda $$

即当$\theta\neq\pi$ 时$\lambda ^{\prime }- \lambda = \frac h{m_{c}c}( 1- cos$ $\varphi )$

## 2Homework(2) 20240930

### (1)Dirac $\delta$ function show that

$$\textbf{(a)}\delta\left(cx\right)=\frac{1}{\left|c\right|}\delta\left(x\right)$$

由于

$$\int_{-\infty}^{\infty}\delta(x)dx=1$$

并且对于任何连续函数f(x)有

$$\int_{-\infty}^{\infty}f(x)\delta(x)dx=f(0)$$

令$u=ct$

------------------------------------------------------------------

$$\int_{-\infty}^{\infty}\delta\left(ct\right)f\left(t\right)dt\xrightarrow{u=ct}\int_{-\infty}^{\infty}\delta\left(u\right)f\left(\frac{u}{c}\right)\frac{1}{\left|c\right|}du=\frac{1}{\left|c\right|}f\left(0\right)$$

于是

$$\begin{aligned}\int_{-\infty}^{\infty}f(x)\delta(ax)\:dx=\int_{-\infty}^{\infty}f(x)\frac{1}{|a|}\delta(x)\:dx\end{aligned}$$

由于这对于任意的连续函数$f(x)$ 成立，因此

$$\delta(ax)=\frac{1}{|a|}\delta(x)$$

$$\mathbf{(b)}\delta\left(-x\right)=\delta\left(x\right)$$

对于任何连续函数f(x)有

$$\int_{-\infty}^{\infty}f(x)\delta(x)dx=f(0)$$

令$\tau=-x$

$$\begin{aligned}\int_{-\infty}^{\infty}\delta(-t)f(t)dt=\int_{\infty}^{-\infty}\delta(\tau)f(-\tau)d(-\tau)=\int_{-\infty}^{\infty}\delta(\tau)f(-\tau)d\tau=f(0)\end{aligned}$$

由于这对于任意的连续函数$f(x)$ 成立，因此：

$$\delta(-x)=\delta(x)$$

$(\mathbf{c})\delta[g(x)]=\sum_i\frac{\delta(x-x_i)}{|g^{\prime}(x_i)|}$ where $x_{i}$ are the root of function $\mathbf{g}(\mathbf{x})$

按照定义，

$$\delta[\:g(\:x\:)\:]=\begin{cases}\:0&\quad(\:g(\:x\:)\neq0\:)\:,\\\:\infty&\quad(\:g(\:x\:)=0\:)\:.\end{cases}$$

由于$x_i$ 为$g(\mathbf{x})$ 的根

$$\delta[\:g(\:x\:)\:]=\sum_i\:c_i\delta(\:x-x_i\:)$$

现在要确定这些系数$c_i$ 在第$n$ 个根$x_n$ 的附近取小区间$(x_{n}-\varepsilon,x_{n}+\varepsilon),\varepsilon$ 是如此小， 在这区间上并无别的根.在这区间上进行积分，

------------------------------------------------------------------

$$\int_{x_n-\varepsilon}^{x_n+\varepsilon}\delta[\:g(\:x\:)\:]\:dx\:=\:\sum_i\:c_i\int_{x_n-s}^{x_n+s}\delta(\:x\:-\:x_i\:)\:dx$$

由于

$$\int_{x_n-\varepsilon}^{x_n+\varepsilon}\delta[\:g(\:x\:)\:]\:dx\:=\int_{g(x_n-\varepsilon)}^{g(x_n+\varepsilon)}\delta[g(x)]\frac{1}{g'(x)}dg(x)=\frac{1}{|g'(x_n)|}$$

除$n=i$ 的一项外均为零，于是

$$\displaystyle\sum_{i}\:c_{i}\int_{x_{n}-s}^{x_{n}+s}\delta(\:x\:-\:x_{i}\:)\:dx=c_{n}\int_{x_{n}-\varepsilon}^{x_{n}+\varepsilon}\delta\left(x-x_{n}\right)x=c_{n}$$

综上

$$c_n=\frac{1}{\mid g^{\prime}(x_n)\mid}.$$

因此

$$\delta[g(x)]=\sum_i\frac{\delta(x-x_i)}{\mid g'(x_i)\mid}$$

$$\textbf{(d)}\delta\left(x^2-a^2\right)=\frac{1}{2\left|a\right|}\left[\delta\left(x-a\right)+\delta\left(x+a\right)\right]$$

令$g(x)=x^{2}-a^{2}$, 此时$x=a$ 和$x=-a$ 分别为$g(x)$ 的两个根

而且

$$g'(x)=2x$$

根据公式(2.15)，我们可以得到

$$\delta\left(x^2-a^2\right)=\frac{1}{2\left|g'(x_1)\right|}\delta\left(x-x_1\right)+\frac{1}{2\left|g'(x_2)\right|}\delta\left(x+x_2\right)$$

代人$x_{1}=a$ 和$x_{2}=-a$ 可得

$$\delta\left(x^2-a^2\right)=\frac{1}{2\left|a\right|}\left[\delta\left(x-a\right)+\delta\left(x+a\right)\right]$$

(e)f dx(b-x) (x -a) = (a - b)

对于任何连续函数f(x)有

------------------------------------------------------------------

$$\int_{-\infty}^{\infty}f(x)\delta(x-x_0)dx=f(x_0)$$

于是

$$\begin{aligned}
\int f(a)da\int\delta(a-x)dx\delta(x-b)& =\int\delta(x-b)dx\int f(a)da\delta(a-x) \\
&=\int\delta(x-b)dxf(x)
\end{aligned}$$

令$x=a$

$$\int\delta(x-b)dxf(x)=\int f(a)da\delta(a-b)$$

两边同时除以$\int f(a)da$ ，得到

$$\displaystyle\int_{-\infty}^{\infty}dx\delta\left(b-x\right)\delta\left(x-a\right)=\delta\left(a-b\right)$$

因此

$$\displaystyle\int_{-\infty}^{\infty}dx\delta\left(b-x\right)\delta\left(x-a\right)=\delta\left(a-b\right)$$

### (2)Suppose two operators A and B satisfy

$$A^2=AA=0,\quad AA^\dagger+A^\dagger A=1,\quad B=A^\dagger A$$

### (a)Proof that $B^{2}=B$

由于$B=A^{\dagger}A$

$$B^2=(A^\dagger A)^2=A^\dagger AA^\dagger A$$

由于$AA^\dagger+A^\dagger A=1$

$$AA^\dagger=1-A^\dagger A$$

将(2.25)代人(2.24)可得

$$\begin{aligned}B^2&=A^\dagger(1-A^\dagger A)A\\&=A^\dagger A-A^\dagger(A^\dagger A)A\end{aligned}$$

------------------------------------------------------------------

由于$A^{2}=0$

$$A^\dagger AA=0$$

因此：

$$\begin{matrix}B^2=A^\dagger A-0=A^\dagger A=B\end{matrix}$$

## (b)Find out the matrix representation of A and B

假设A是一个$2\times2$ 的矩阵，其一般形式为

$$A=\begin{pmatrix}a&b\\c&d\end{pmatrix}$$

由于$A^2=0$ ，我们有：

$$A^2=\begin{pmatrix}a&b\\c&d\end{pmatrix}\begin{pmatrix}a&b\\c&d\end{pmatrix}=\begin{pmatrix}a^2+bc&ab+bd\\ca+dc&cb+d^2\end{pmatrix}=\begin{pmatrix}0&0\\0&0\end{pmatrix}$$

从而得到以下条件：

$$a^2+bc=0$$

ab + bd = 0

ca + dc = 0

cb + d² = 0

我们假设$a=0$ 和$d=0$ ，则有：

$$\left\{\begin{array}{c}bc=0\\ab=0\\ca=0\\cb=0\end{array}\right.$$

这意味着b和c之一必须为零，假设$b=1$ 和$c=0$ ，则A和$A^\dagger$ 可以表示为：

------------------------------------------------------------------

$$A=\begin{pmatrix}0&1\\0&0\end{pmatrix},\quad A^\dagger=\begin{pmatrix}0&0\\1&0\end{pmatrix}$$

计算$AA^\dagger$ 和$A^\dagger A$

$$AA^\dagger=\begin{pmatrix}0&1\\0&0\end{pmatrix}\begin{pmatrix}0&0\\1&0\end{pmatrix}=\begin{pmatrix}1&0\\0&0\end{pmatrix}\\A^\dagger A=\begin{pmatrix}0&0\\1&0\end{pmatrix}\begin{pmatrix}0&1\\0&0\end{pmatrix}=\begin{pmatrix}0&0\\0&1\end{pmatrix}$$

因此

$$AA^\dagger+A^\dagger A=\begin{pmatrix}1&0\\0&0\end{pmatrix}+\begin{pmatrix}0&0\\0&1\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}=1$$

因此

$$A=\begin{pmatrix}0&1\\0&0\end{pmatrix}$$

$$B=A^\dagger A=\begin{pmatrix}0&0\\1&0\end{pmatrix}\begin{pmatrix}0&1\\0&0\end{pmatrix}=\begin{pmatrix}0&0\\0&1\end{pmatrix}$$

假设$b=0$ 和$c=1$ ，则A和B可以表示为：

$$A=\begin{pmatrix}0&0\\1&0\end{pmatrix}$$

$$B=A^\dagger A=\begin{pmatrix}0&1\\0&0\end{pmatrix}\begin{pmatrix}0&0\\1&0\end{pmatrix}=\begin{pmatrix}1&0\\0&0\end{pmatrix}$$

(3) Eigenvalues and Eigenvectors-1

Please find out the eigenvalues and eignevectors of following matrices and show the eigenvectors are orthogonal to each other.

$$(\mathbf{a}){\left(\begin{array}{ll}{1}&{2}\\{5}&{4}\end{array}\right)}$$

------------------------------------------------------------------

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$\begin{aligned}
A-\lambda I& =det\begin{pmatrix}1-\lambda&2\\5&4-\lambda\end{pmatrix}  \\
&=(1-\lambda)(4-\lambda)-2\times5 \\
&=(1-\lambda)(4-\lambda)-10 \\
&=4-\lambda-4\lambda+\lambda^{2}-10 \\
&=\lambda^{2}-5\lambda-6
\end{aligned}$$

解这个二次方程：

$$\begin{matrix}(\lambda+1)\cdot(\lambda-6)=0\end{matrix}$$

所以特征值为

$$\begin{aligned}\lambda_1&=6\\\lambda_2&=-1\end{aligned}$$

对于每个特征值$\lambda$, 我们需要找到对应的特征向量v满足：

$$\begin{matrix}(A-\lambda I)v=0\end{matrix}$$

对于$\lambda_{1}=6$

------------------------------------------------------------------

$$\begin{pmatrix}1-6&2\\5&4-6\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}-5&2\\5&-2\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程：

$$\begin{aligned}-5v_1+2v_2&=0\\5v_1-2v_2&=0\end{aligned}$$

所以一个特征向量是：

令$v_1=2$ 可得

$$v_1=\begin{pmatrix}v_1\\\frac{5}{2}v_1\end{pmatrix}$$

$$v_1=\begin{pmatrix}2\\5\end{pmatrix}$$

对于$\lambda_{2}=-1$

$$\begin{pmatrix}1+1&2\\5&4+1\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}2&2\\5&5\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程：

$$\begin{aligned}2u_1+2u_2&=0\\5u_1+5u_2&=0\end{aligned}$$

------------------------------------------------------------------

所以一个特征向量是：

$$v_2=\begin{pmatrix}u_1\\-u_1\end{pmatrix}$$

令$u_{2}=1$ 可得

$$v_2=\begin{pmatrix}1\\-1\end{pmatrix}$$

计算内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =\begin{pmatrix}2\\5\end{pmatrix}\cdot\begin{pmatrix}1\\-1\end{pmatrix}  \\
&=2\cdot1+5\cdot(-1) \\
&=2-5 \\
&=-3
\end{aligned}$$

由于这个内积不是零，因此这两个特征向量$v_1$ 和$v_{2}$ 在实数空间中并不是正交的，

()

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

------------------------------------------------------------------

$$\begin{aligned}
A-\lambda I& =\begin{pmatrix}-6-\lambda&3\\4&5-\lambda\end{pmatrix}  \\
&=(-6-\lambda)(5-\lambda)-4\cdot3 \\
&=(-6-\lambda)(5-\lambda)-12 \\
&=-30+6\lambda-5\lambda-\lambda^2-12 \\
&=\lambda^{2}+\lambda-42
\end{aligned}$$

解这个二次方程

$$\begin{matrix}(\lambda+7)\cdot(\lambda-6)=0\end{matrix}$$

所以特征值为

$$\begin{aligned}\lambda_1&=6\\\lambda_2&=-7\end{aligned}$$

对于$\lambda_1=6$

$$\begin{pmatrix}-6-6&3\\4&5-6\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}-12&3\\4&-1\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}-12v_1+3v_2&=0\\4v_1-v_2&=0\end{aligned}$$

------------------------------------------------------------------

所以一个特征向量是：

令$v_1=1$ 可得

$$v_1=\begin{pmatrix}v_1\\4v_1\end{pmatrix}$$

$$v_1=\begin{pmatrix}1\\4\end{pmatrix}$$

对于$\lambda_{2}=-7$

$$\begin{pmatrix}-6+7&3\\4&5+7\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}1&3\\4&12\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}u_1+3u_2&=0\\4u_1+12u_2&=0\end{aligned}$$

所以一个特征向量是：

令$u_2=1$ 可得

$$v_2=\begin{pmatrix}-3u_2\\u_2\end{pmatrix}$$

$$v_1=\begin{pmatrix}-3\\1\end{pmatrix}$$

计算内积

------------------------------------------------------------------

$$\begin{aligned}
v_{1}\cdot v_{2}& =\begin{pmatrix}1\\4\end{pmatrix}\cdot\begin{pmatrix}-3\\1\end{pmatrix}  \\
&=1\cdot(-3)+4\cdot1 \\
&=-3+4 \\
&=1
\end{aligned}$$

由于这个内积不是零，因此这两个特征向量$v_1$ 和$v_{2}$ 在实数空间中并不是正交的。

()

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$\begin{aligned}
A-\lambda I& =\begin{pmatrix}0-\lambda&1\\-2&3-\lambda\end{pmatrix}  \\
&=(-\lambda)(3-\lambda)-(-2)\cdot1 \\
&=(-\lambda)(3-\lambda)+2 \\
&=\lambda^{2}-3\lambda+2
\end{aligned}$$

解这个二次方程

$$\begin{matrix}(\lambda-2)\cdot(\lambda-1)=0\end{matrix}$$

所以特征值为

------------------------------------------------------------------

$$\begin{aligned}\lambda_1&=2\\\lambda_2&=1\end{aligned}$$

对于$\lambda_{1}=2$

$$\begin{pmatrix}0-2&1\\-2&3-2\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

$$\begin{pmatrix}-2&1\\-2&1\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}7=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}-2v_1+v_2&=0\\-2v_1+v_2&=0\end{aligned}$$

所以一个特征向量是：

令$v_1=1$ 可得

$$v_1=\begin{pmatrix}v_1\\2v_1\end{pmatrix}$$

$$v_1=\begin{pmatrix}1\\2\end{pmatrix}$$

对于$\lambda_{2}=1$

$$\begin{pmatrix}0-1&1\\-2&3-1\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}-1&1\\-2&2\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

------------------------------------------------------------------

$$\begin{aligned}-u_1+u_2&=0\\-2u_1+2u_2&=0\end{aligned}$$

所以一个特征向量是：

$$v_2=\begin{pmatrix}u_1\\u_1\end{pmatrix}$$

令$u_1=1$ 可得

$$v_1=\begin{pmatrix}1\\1\end{pmatrix}$$

计算内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =\begin{pmatrix}1\\2\end{pmatrix}\cdot\begin{pmatrix}1\\1\end{pmatrix}  \\
&=1\cdot1+2\cdot1 \\
&=1+2 \\
&=3
\end{aligned}$$

(2.101)

由于这个内积不是零，因此这两个特征向量$v_1$ 和$v_{2}$ 在实数空间中并不是正交的。

$$(\mathbf{d})\left(\begin{array}{cc}0&-2\\3&4\end{array}\right)$$

要找到特征值$\lambda$, 我们需要解特征方程：

$$det(A-\lambda I)=0$$

对于矩阵$A$, 我们有：

$$A-\lambda I=\begin{pmatrix}0&-2\\3&4\end{pmatrix}-\lambda\begin{pmatrix}1&0\\0&1\end{pmatrix}=\begin{pmatrix}-\lambda&-2\\3&4-\lambda\end{pmatrix}$$

计算行列式

------------------------------------------------------------------

$$\begin{aligned}
det(A-\lambda I)& =det\begin{pmatrix}-\lambda&-2\\3&4-\lambda\end{pmatrix}  \\
&=(-\lambda)(4-\lambda)-(-2)(3) \\
&=-\lambda(4-\lambda)+6 \\
&=-4\lambda+\lambda^{2}+6 \\
&=\lambda^{2}-4\lambda+6
\end{aligned}$$

运用求根公式

$$\lambda=\frac{4\pm\sqrt{16-24}}{2}=\frac{4\pm\sqrt{-8}}{2}=\frac{4\pm2i\:\sqrt{2}}{2}=2\pm i\:\sqrt{2}$$

$$\begin{aligned}\lambda_1&=2+i\:\sqrt{2}\\\lambda_2&=2-i\:\sqrt{2}\end{aligned}$$

对于每个特征值$\lambda$, 我们需要找到对应的特征向量v满足：

$$\begin{matrix}(A-\lambda I)v=0\end{matrix}$$

对于$\lambda _{1}= 2+ i$ $\sqrt {2}$

$$\begin{aligned}
A-\lambda_{1}I& =\begin{pmatrix}0&-2\\3&4\end{pmatrix}-(2+i\:\sqrt{2})\begin{pmatrix}1&0\\0&1\end{pmatrix}  \\
&=\begin{pmatrix}-2-i\:\sqrt{2}&-2\\3&4-(2+i\:\sqrt{2})\end{pmatrix} \\
&=\begin{pmatrix}-2-i\:\sqrt{2}&-2\\3&2-i\:\sqrt{2}\end{pmatrix}
\end{aligned}$$

------------------------------------------------------------------

于是

解方程组

故特征向量为：

$$\begin{aligned}
&\begin{pmatrix}-i\left(\sqrt{2}-2i\right)&-2\\3&-i\left(\sqrt{2}+2i\right)\end{pmatrix}\xrightarrow{r_{1}\leftrightarrow r_{2}} \\
&\begin{pmatrix}1&-\frac{i\left(\sqrt{2}+2i\right)}{3}\\-i\left(\sqrt{2}-2i\right)&-2\end{pmatrix}\xrightarrow{r_{2}+\left(i\left(\sqrt{2}-2i\right)\right)r_{1}} \\
&\begin{pmatrix}1&-\frac{i\left(\sqrt{2}+2i\right)}{3}\\0&0\end{pmatrix}
\end{aligned}$$

$$\begin{pmatrix}1&-\frac{i\left(\sqrt{2}+2i\right)}{3}\\0&0\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

$$v_1-\frac{i\left(\sqrt{2}+2i\right)}{3}v_2=0$$

$$v_1=\begin{pmatrix}\frac{i\left(\sqrt{2}+2i\right)}{3}v_2\\v_2\end{pmatrix}=v_2\begin{pmatrix}\frac{i\left(\sqrt{2}+2i\right)}{3}\\1\end{pmatrix}$$

$$v_1=\begin{pmatrix}\frac{i\left(\sqrt{2}+2i\right)}{3}\\1\end{pmatrix}$$

方程为：

令$v_{2}=1$

对于$\lambda _{2}= 2- i$ $\sqrt {2}$

------------------------------------------------------------------

$$\begin{gathered}
A-\lambda_{2}I =\begin{pmatrix}0&-2\\3&4\end{pmatrix}-(2-i\:\sqrt{2})\begin{pmatrix}1&0\\0&1\end{pmatrix} \\
=\begin{pmatrix}-2+i\:\sqrt{2}&-2\\3&2+i\:\sqrt{2}\end{pmatrix} 
\end{gathered}$$

于是

解方程组

$$\begin{aligned}
&\begin{pmatrix}i\left(\sqrt{2}+2i\right)&-2\\3&i\left(\sqrt{2}-2i\right)\end{pmatrix}\xrightarrow{r_{1}\leftrightarrow r_{2}} \\
&\begin{pmatrix}1&\frac{i\left(\sqrt{2}-2i\right)}{3}\\i\left(\sqrt{2}+2i\right)&-2\end{pmatrix}\xrightarrow{r_{2}+\left(-i\left(\sqrt{2}+2i\right)\right)r_{1}} \\
&\begin{pmatrix}1&\frac{i\left(\sqrt{2}-2i\right)}{3}\\0&0\end{pmatrix}
\end{aligned}$$

$$\begin{pmatrix}1&\frac{i\left(\sqrt{2}-2i\right)}{3}\\0&0\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

$$v_1+\frac{i\left(\sqrt{2}-2i\right)}{3}v_2=0$$

$$v_1=\begin{pmatrix}-\frac{i\left(\sqrt{2}-2i\right)}{3}v_2\\v_2\end{pmatrix}=v_2\begin{pmatrix}-\frac{i\left(\sqrt{2}-2i\right)}{3}\\1\end{pmatrix}$$

方程为

故特征向量为：

令$v_2=1$

------------------------------------------------------------------

$$v_2=\begin{pmatrix}-\frac{i\left(\sqrt{2}-2i\right)}{3}\\1\end{pmatrix}$$

由于两个复数向量$u=\begin{pmatrix}u_1\\u_2\end{pmatrix}$ 和$v=\begin{pmatrix}v_1\\v_2\end{pmatrix}$, 它们的内积定义为;

(2.120)

$$u\cdot v=u_1v_1^*+u_2v_2^*$$

计算内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =\left(-\frac{i(\:\sqrt{2}-2i)}{3}\right)\left(\frac{-i(\:\sqrt{2}-2i)}{3}\right)+1\cdot1  \\
&=\frac{i(\sqrt{2}-2i)}{3}\cdot\frac{i(\sqrt{2}-2i)}{3}+1 \\
&=\frac{i^{2}(\:\sqrt{2}-2i)^{2}}{9}+1 \\
&=\frac{2+4\sqrt{2}i}{9}+1 \\
&=\frac{11+4\:\sqrt{2}i}9 \\
\end{aligned}$$

由于这个内积不是零，因此这两个特征向量$v_1$ 和$v_{2}$ 在复数空间中并不是正交的。

(@()

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

------------------------------------------------------------------

$$\begin{aligned}
A-\lambda I& =\begin{pmatrix}-4-\lambda&-6\\3&5-\lambda\end{pmatrix}  \\
&=(-4-\lambda)(5-\lambda)-(-6)\cdot3 \\
&=(-4-\lambda)(5-\lambda)+18 \\
&=\lambda^{2}-\lambda-20+18 \\
&=\lambda^{2}-\lambda-2
\end{aligned}$$

解这个二次方程

$$\begin{matrix}(\lambda-2)\cdot(\lambda+1)=0\end{matrix}$$

所以特征值为

$$\begin{aligned}\lambda_1&=-2\\\lambda_2&=1\end{aligned}$$

对于$\lambda_{1}=-2$

$$\begin{pmatrix}-4-2&-6\\3&5-2\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}-6&-6\\3&3\end{pmatrix}\begin{pmatrix}v_1\\v_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

------------------------------------------------------------------

$$\begin{aligned}-6v_1-6v_2&=0\\3v_1+3v_2&=0\end{aligned}$$

所以一个特征向量是：

令$v_1=1$ 可得

$$v_1=\begin{pmatrix}v_1\\-v_1\end{pmatrix}$$

$$v_1=\begin{pmatrix}1\\-1\end{pmatrix}$$

对于$\lambda_{2}=1$

$$\begin{pmatrix}-4+1&-6\\3&5+1\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}\\\\\begin{pmatrix}-3&-6\\3&6\end{pmatrix}\begin{pmatrix}u_1\\u_2\end{pmatrix}=\begin{pmatrix}0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}-3u_1-6u_2&=0\\3u_1+6u_2&=0\end{aligned}$$

所以一个特征向量是：

令$u_{1}=2$ 可得

$$v_2=\begin{pmatrix}u_1\\-\frac{1}{2}u_1\end{pmatrix}$$

$$v_1=\begin{pmatrix}2\\-1\end{pmatrix}$$

------------------------------------------------------------------

计算内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =\begin{pmatrix}1\\-1\end{pmatrix}\cdot\begin{pmatrix}2\\-1\end{pmatrix}  \\
&=1\cdot2+(-1)\cdot(-1) \\
&=1+2 \\
&=3
\end{aligned}$$

由于这个内积不是零，因此这两个特征向量$v_1$ 和$v_{2}$ 在实数空间中并不是正交的。

(f)
$$\partial\left(\begin{array}{ccc}{2}&{0}&{0}\\{0}&{4}&{5}\\{0}&{4}&{3}\end{array}\right)$$

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$A-\lambda I=\begin{pmatrix}2-\lambda&0&0\\0&4-\lambda&5\\0&4&3-\lambda\end{pmatrix}$$

$$det(A-\lambda I)=(2-\lambda)\:det\begin{pmatrix}4-\lambda&5\\4&3-\lambda\end{pmatrix}$$

$$\begin{aligned}
det\left(\begin{matrix}{4-\lambda}&{5}\\{4}&{3-\lambda}\\\end{matrix}\right)& =(4-\lambda)(3-\lambda)-4\cdot5  \\
&=12-4\lambda-3\lambda+\lambda^{2}-20 \\
&=\lambda^{2}-7\lambda-8
\end{aligned}$$

------------------------------------------------------------------

得到三次方程

$$\begin{matrix}(2-\lambda)(\lambda^2-7\lambda-8)=0\end{matrix}$$

所以特征值为

$$\begin{aligned}\lambda_1&=2\\\lambda_2&=8\\\lambda_3&=-1\end{aligned}$$

对于$\lambda_1=2$

$$\begin{pmatrix}2-2&0&0\\0&4-2&5\\0&4&3-2\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

$$\begin{pmatrix}0&0&0\\0&2&5\\0&4&1\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}2v_2+5v_3&=0\\4v_2+v_3&=0\end{aligned}$$

所以一个特征向量是：

$$v_1=\begin{pmatrix}v_1\\0\\0\end{pmatrix}$$

令$v_1=1$ 可得

$$v_1=\begin{pmatrix}1\\0\\0\end{pmatrix}$$

------------------------------------------------------------------

对于$\lambda_{2}=8$

$$\begin{pmatrix}2-8&0&0\\0&4-8&5\\0&4&3-8\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

$$\begin{pmatrix}-6&0&0\\0&-4&5\\0&4&-5\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}-4v_2+5v_3&=0\\4v_2-5v_3&=0\end{aligned}$$

所以一个特征向量是：

$$v_2=\begin{pmatrix}0\\v_2\\\frac{4}{5}v_2\end{pmatrix}$$

令$v_2=5$ 可得

$$v_2=\begin{pmatrix}0\\5\\4\end{pmatrix}$$

对于$\lambda_{3}=-1$

------------------------------------------------------------------

$$\begin{pmatrix}2+1&0&0\\0&4+1&5\\0&4&3+1\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

$$\begin{pmatrix}3&0&0\\0&5&5\\0&4&4\end{pmatrix}\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到两个方程

$$\begin{aligned}5v_2+5v_3&=0\\4v_2+4v_3&=0\end{aligned}$$

所以一个特征向量是：

$$v_3=\begin{pmatrix}0\\v_2\\-v_2\end{pmatrix}$$

令$v_2=1$ 可得

$$v_3=\begin{pmatrix}0\\1\\-1\end{pmatrix}$$

计算$v_1$ 和$v_2$ 的内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =\begin{pmatrix}1\\0\\0\end{pmatrix}\cdot\begin{pmatrix}0\\5\\4\end{pmatrix}  \\
&=1\cdot0+0\cdot5+0\cdot4 \\
&=0
\end{aligned}$$

计算$v_1$ 和$v_{3}$ 的内积

------------------------------------------------------------------

(2.170)

$$\begin{aligned}
v_{1}\cdot v_{3}& =\begin{pmatrix}1\\0\\0\end{pmatrix}\cdot\begin{pmatrix}0\\1\\-1\end{pmatrix}  \\
&=1\cdot0+0\cdot1+0\cdot(-1) \\
&=0
\end{aligned}$$

计算$v_{2}$ 和$v_{3}$ 的内积

$$\begin{aligned}
v_{2}\cdot v_{3}& =\begin{pmatrix}0\\[0.3em]5\\[0.3em]4\end{pmatrix}\cdot\begin{pmatrix}0\\[0.3em]1\\[0.3em]-1\end{pmatrix}  \\
&=0\cdot0+5\cdot1+4\cdot(-1) \\
&=0+5-4 \\
&=1
\end{aligned}$$

所以，特征向量$v_1$ 和$v_{2}$ 、 $v_1$ 和$v_3$ 是正交的，但$v_{2}$ 和$v_{3}$ 不是正交的。

![](https://storage.simpletex.cn/view/fp02sQbebpR4qGDLOtLQABGsOHVDgeFKO)

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$A-\lambda I=\begin{pmatrix}4-\lambda&6&10\\3&10-\lambda&13\\-2&-6&-\lambda-8\end{pmatrix}$$

于是

------------------------------------------------------------------

$$\begin{pmatrix}4-\lambda&6&10\\3&10-\lambda&13\\-2&-6&-\lambda-8\end{pmatrix}\xrightarrow{c_1-2c_2}$$

$$\begin{pmatrix}2-\lambda&6&10\\2\left(\lambda-2\right)&10-\lambda&13\\2-\lambda&-6&-\lambda-8\end{pmatrix}\xrightarrow{r_2+2r_1}$$

$$\begin{pmatrix}2-\lambda&6&10\\0&22-\lambda&33\\0&-12&-\lambda-18\end{pmatrix}$$

按第一列展开

$$\begin{aligned}
&(2-\lambda)\left(\begin{matrix}{22-\lambda}&{33}\\{-12}&{-\lambda-18}\\\end{matrix}\right)\xrightarrow{c_{1}-\frac{6}{11}c_{2}} \\
&(2-\lambda)\begin{pmatrix}4-\lambda&33\\\frac{6(\lambda-4)}{11}&-\lambda-18\end{pmatrix}\xrightarrow{r_{2}+\frac{6}{11}r_{1}} \\
&(2-\lambda)\begin{vmatrix}4-\lambda&33\\0&-\lambda\end{vmatrix}
\end{aligned}$$

得到特征方程

$$-\lambda\left(\lambda-4\right)\left(\lambda-2\right)=0$$

所以特征值为

$$\begin{aligned}\lambda_1&=4\\\lambda_2&=2\\\lambda_3&=0\end{aligned}$$

对于$\lambda_1=4$

------------------------------------------------------------------

$$A-4I=\begin{pmatrix}4-4&6&10\\3&10-4&13\\-2&-6&-8-4\end{pmatrix}=\begin{pmatrix}0&6&10\\3&6&13\\-2&-6&-12\end{pmatrix}$$

$$\begin{pmatrix}0&6&10\\3&6&13\\-2&-6&-12\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$\begin{aligned}
6x_{2}+10x_{3}& =0  \\
3x_{1}+6x_{2}+13x_{3}& =0  \\
-2x_{1}-6x_{2}-12x_{3}& =0 
\end{aligned}$$

所以一个特征向量是：

$$v_1=\begin{pmatrix}\frac{3}{5}x_2\\x_2\\-\frac{3}{5}x_2\end{pmatrix}$$

令$x_2=5$ 可得

$$v_1=\begin{pmatrix}3\\5\\-3\end{pmatrix}$$

对于$\lambda_{2}=2$

------------------------------------------------------------------

$$A-2I=\begin{pmatrix}4-2&6&10\\3&10-2&13\\-2&-6&-8-2\end{pmatrix}=\begin{pmatrix}2&6&10\\3&8&13\\-2&-6&-10\end{pmatrix}$$

$$\begin{pmatrix}2&6&10\\3&8&13\\-2&-6&-10\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$2x_{1}+6x_{2}+10x_{3}=0\\3x_{1}+8x_{2}+13x_{3}=0\\-2x_{1}-6x_{2}-10x_{3}=0$$

所以一个特征向量是：

$$v_2=\begin{pmatrix}x_1\\-2x_1\\x_1\end{pmatrix}$$

令$x_1=1$ 可得

$$v_2=\begin{pmatrix}1\\-2\\1\end{pmatrix}$$

对于$\lambda_{3}=0$

$$A=\begin{pmatrix}4&6&10\\[1ex]3&10&13\\[1ex]-2&-6&-8\end{pmatrix}$$

我们得到三个方程

------------------------------------------------------------------

$$4x_{1}+6x_{2}+10x_{3}=0\\3x_{1}+10x_{2}+13x_{3}=0\\-2x_{1}-6x_{2}-8x_{3}=0$$

所以一个特征向量是：

$$v_3=\begin{pmatrix}x_1\\x_1\\-x_1\end{pmatrix}$$

令$x_1=1$ 可得

$$v_3=\begin{pmatrix}1\\1\\-1\end{pmatrix}$$

计算$v_1$ 和$v_{2}$ 的内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =3\cdot1+5\cdot(-2)+(-3)\cdot1  \\
&=3-10-3 \\
&=-10
\end{aligned}$$

计算$v_1$ 和$v_{3}$ 的内积

$$\begin{aligned}
v_{1}\cdot v_{3}& =3\cdot1+5\cdot1+(-3)\cdot(-1)  \\
&=3+5+3 \\
&=11
\end{aligned}$$

计算$v_{2}$ 和$v_{3}$ 的内积

------------------------------------------------------------------

$$\begin{aligned}
v_{2}\cdot v_{3}& =1\cdot1+(-2)\cdot1+1\cdot(-1)  \\
&=1-2-1 \\
&=-2
\end{aligned}$$

所以，特征向量$v_1$ 和$v_{2}$ 、 $v_1$ 和$v_3$ 、 $v_2$ 和$v_{3}$ 不是正交的。

![](https://storage.simpletex.cn/view/ft3YvGyGmDv6K2M4TqCXGdRpL6DlpszSM)

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$A-\lambda I=\begin{pmatrix}2-\lambda&2&-2\\1&3-\lambda&-1\\-1&1&1-\lambda\end{pmatrix}$$

于是

$$\begin{pmatrix}2-\lambda&2&-2\\1&3-\lambda&-1\\-1&1&1-\lambda\end{pmatrix}\xrightarrow{c_1+c_2}\\\begin{pmatrix}4-\lambda&2&-2\\4-\lambda&3-\lambda&-1\\0&1&1-\lambda\end{pmatrix}\xrightarrow{r_2-r_1}$$

$$\begin{pmatrix}4-\lambda&2&-2\\0&1-\lambda&1\\0&1&1-\lambda\end{pmatrix}$$

------------------------------------------------------------------

按第一列展开

$$\begin{aligned}
&(4-\lambda)\left(\begin{matrix}{1-\lambda}&{1}\\{1}&{1-\lambda}\\\end{matrix}\right)\xrightarrow{c_{1}+c_{2}} \\
&(4-\lambda)\begin{pmatrix}2-\lambda&1\\2-\lambda&1-\lambda\end{pmatrix}\xrightarrow{r_{2}-r_{1}} \\
&(4-\lambda)\begin{pmatrix}2-\lambda&1\\0&-\lambda\end{pmatrix}
\end{aligned}$$

得到特征方程

$$-\lambda\left(\lambda-4\right)\left(\lambda-2\right)=0$$

所以特征值为

$$\begin{aligned}\lambda_1&=4\\\lambda_2&=2\\\lambda_3&=0\end{aligned}$$

对于$\lambda_{1}=4$

$$A-4I=\begin{pmatrix}2-4&2&-2\\1&3-4&-1\\-1&1&1-4\end{pmatrix}=\begin{pmatrix}-2&2&-2\\1&-1&-1\\-1&1&-3\end{pmatrix}$$

$$\begin{pmatrix}-2&2&-2\\[0.3em]1&-1&-1\\[0.3em]-1&1&-3\end{pmatrix}\begin{pmatrix}x_1\\x_2\\[0.3em]x_3\end{pmatrix}=\begin{pmatrix}0\\[0.3em]0\\[0.3em]0\end{pmatrix}$$

我们得到三个方程

------------------------------------------------------------------

$$\begin{aligned}
-2x_{1}+2x_{2}-2x_{3}& =0  \\
x_{1}-x_{2}-x_{3}& =0  \\
-x_{1}+x_{2}-3x_{3}& =0 
\end{aligned}$$

所以一个特征向量是：

$$v_1=\begin{pmatrix}x_1\\[1ex]x_1\\[1ex]0\end{pmatrix}$$

令$x_1=1$ 可得

$$v_1=\begin{pmatrix}1\\[0.3em]1\\[0.3em]0\end{pmatrix}$$

对于$\lambda_{2}=2$

$$A-2I=\begin{pmatrix}2-2&2&-2\\1&3-2&-1\\-1&1&1-2\end{pmatrix}=\begin{pmatrix}0&2&-2\\1&1&-1\\-1&1&-1\end{pmatrix}$$

$$\begin{pmatrix}0&2&-2\\[0.3em]1&1&-1\\[0.3em]-1&1&-1\end{pmatrix}\begin{pmatrix}x_1\\[0.3em]x_2\\[0.3em]x_3\end{pmatrix}=\begin{pmatrix}0\\[0.3em]0\\[0.3em]0\end{pmatrix}$$

我们得到三个方程

$$2x_{2}-2x_{3}=0\\x_{1}+x_{2}-x_{3}=0\\-x_{1}+x_{2}-x_{3}=0$$

所以一个特征向量是：

------------------------------------------------------------------

$$v_2=\begin{pmatrix}0\\x_2\\x_2\end{pmatrix}$$

令$x_2=1$ 可得

$$v_2=\begin{pmatrix}0\\[0.3em]1\\[0.3em]1\end{pmatrix}$$

对于$\lambda_{3}=0$

$$A=\begin{pmatrix}2&2&-2\\1&3&-1\\-1&1&1\end{pmatrix}$$

我们得到三个方程

$$2x_{1}+2x_{2}-2x_{3}=0\\x_{1}+3x_{2}-x_{3}=0\\-x_{1}+x_{2}+x_{3}=0$$

所以一个特征向量是：

$$v_3=\begin{pmatrix}x_1\\0\\x_1\end{pmatrix}$$

令$x_1=1$ 可得

$$v_3=\begin{pmatrix}1\\0\\1\end{pmatrix}$$

计算$v_1$ 和$v_{2}$ 的内积

------------------------------------------------------------------

$$\begin{aligned}v_1\cdot v_2&=1\cdot0+1\cdot1+0\cdot1\\&=0+1+0\\&=1\end{aligned}$$

计算$v_1$ 和$v_{3}$ 的内积

$$\begin{aligned}v_1\cdot v_3&=1\cdot1+1\cdot0+0\cdot1\\&=1+0+0\\&=1\end{aligned}$$

计算$v_{2}$ 和$v_{3}$ 的内积

(2.228)

$$\begin{aligned}
v_{2}\cdot v_{3}& =0\cdot1+1\cdot0+1\cdot1  \\
&=0+0+1 \\
&=1
\end{aligned}$$

所以，特征向量$v_1$ 和$v_2$ 、 $v_1$ 和$v_3$ 、 $v_2$ 和$v_3$ 不是正交的。

![](https://storage.simpletex.cn/view/fR1mc73PBU9PxlwIlH5nSVsqfKSDv3XFC)

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

$$A-\lambda I=\begin{pmatrix}5-\lambda&-10&5\\2&14-\lambda&2\\-4&8&6-\lambda\end{pmatrix}$$

于是

------------------------------------------------------------------

$$\begin{pmatrix}5-\lambda&-10&5\\2&14-\lambda&2\\-4&-8&6-\lambda\end{pmatrix}\xrightarrow{c_2-2c_1}$$

$$\begin{pmatrix}5-\lambda&2\left(\lambda-10\right)&5\\2&10-\lambda&2\\-4&0&6-\lambda\end{pmatrix}\xrightarrow{r_1+2r_2}$$

$$\begin{pmatrix}9-\lambda&0&9\\2&10-\lambda&2\\-4&0&6-\lambda\end{pmatrix}$$

按第二列展开

$$10-\lambda\begin{pmatrix}9-\lambda&9\\-4&6-\lambda\end{pmatrix}$$

得到特征方程

$$-\begin{pmatrix}\lambda-10\end{pmatrix}\begin{pmatrix}\lambda^2-15\lambda+90\end{pmatrix}=0$$

所以特征值为

$$\begin{aligned}
&\lambda_{1} =10  \\
&\lambda_{2} =\frac{15}{2}-\frac{3\sqrt{15}i}{2}  \\
&\lambda_{3} =\frac{15}{2}+\frac{3\sqrt{15}i}{2} 
\end{aligned}$$

对于$\lambda_1=10$

------------------------------------------------------------------

$$A-10I=\begin{pmatrix}5-10&-10&5\\2&14-10&2\\-4&-8&6-10\end{pmatrix}=\begin{pmatrix}-5&-10&5\\2&4&2\\-4&-8&-4\end{pmatrix}$$

$$\begin{pmatrix}-5&-10&5\\2&4&2\\-4&-8&-4\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$-5x_{1}-10x_{2}+5x_{3}=0\\2x_{1}+4x_{2}+2x_{3}=0\\-4x_{1}-8x_{2}-4x_{3}=0$$

所以一个特征向量是：

$$v_1=\begin{pmatrix}-2x_2\\\\x_2\\0\end{pmatrix}$$

令$x_2=1$ 可得

$$v_1=\begin{pmatrix}-2\\[0.3em]1\\[0.3em]0\end{pmatrix}$$

对于$\lambda_{2}=\frac{15}{2}-\frac{3\sqrt{15}i}{2}$

$$A-\lambda_2I=A-\left(\frac{15}{2}-\frac{3\:\sqrt{15}i}{2}\right)I$$

$$A-\lambda_2I=\begin{pmatrix}-\frac{5}{2}+\frac{3\sqrt{15}i}{2}&-10&5\\2&\frac{13}{2}+\frac{3\sqrt{15}i}{2}&2\\-4&-8&-\frac{3}{2}+\frac{3\sqrt{15}i}{2}\end{pmatrix}$$

------------------------------------------------------------------

$$\begin{pmatrix}-\frac{5}{2}+\frac{3\sqrt{15}i}{2}&-10&5\\2&\frac{13}{2}+\frac{3\sqrt{15}i}{2}&2\\-4&-8&-\frac{3}{2}+\frac{3\sqrt{15}i}{2}\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$\begin{gathered}
\left(-\frac52+\frac{3\:\sqrt{15i}}2\right)x_1-10x_2+5x_3 =0 \\
2x_{1}+\left({\frac{13}{2}}+{\frac{3{\sqrt{15}}i}{2}}\right)x_{2}+2x_{3} =0 \\
-4x_{1}-8x_{2}+\left(-\frac{3}{2}+\frac{3\:\sqrt{15i}}{2}\right)x_{3} =0 
\end{gathered}$$

所以一个特征向量是：

$$v_2=\begin{pmatrix}\frac{5}{8}+\frac{3\sqrt{15}i}{8}x_3\\-\frac{1}{2}x_3\\x_3\end{pmatrix}$$

令$x_3=1$ 可得

$$v_2=\begin{pmatrix}\frac{5}{8}+\frac{3\:\sqrt{15}i}{8}\\-\frac{1}{2}\\1\end{pmatrix}$$

对于$\lambda_{3}=\frac{15}{2}+\frac{3\sqrt{15}i}{2}$

$$A-\lambda_3I=A-\left(\frac{15}{2}+\frac{3\:\sqrt{15}i}{2}\right)I$$

$$A-\lambda_3I=\begin{pmatrix}-\frac52-\frac{3\sqrt{15}i}2&-10&5\\2&\frac{13}2-\frac{3\sqrt{15}i}2&2\\-4&-8&-\frac32-\frac{3\sqrt{15}i}2\end{pmatrix}$$

------------------------------------------------------------------

$$\begin{pmatrix}-\frac52-\frac{3\sqrt{15}i}2&-10&5\\2&\frac{13}2-\frac{3\sqrt{15}i}2&2\\-4&-8&-\frac32-\frac{3\sqrt{15}i}2\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$\begin{gathered}
\left(-\frac{5}{2}-\frac{3\:\sqrt{15i}}{2}\right)x_{1}-10x_{2}+5x_{3} =0 \\
2x_{1}+\left({\frac{13}{2}}-{\frac{3{\sqrt{15}}i}{2}}\right)x_{2}+2x_{3} =0 \\
-4x_{1}-8x_{2}+\left(-\frac{3}{2}-\frac{3\:\sqrt{15i}}{2}\right)x_{3} =0 
\end{gathered}$$

所以一个特征向量是：

$$v_2=\begin{pmatrix}\frac{5}{8}-\frac{3\sqrt{15}i}{8}x_3\\-\frac{1}{2}x_3\\x_3\end{pmatrix}$$

令$x_1=1$ 可得

$$v_2=\begin{pmatrix}\frac{5}{8}-\frac{3\sqrt{15}i}{8}\\-\frac{1}{2}\\1\end{pmatrix}$$

计算$v_1$ 和$v_2$ 的内积

$$\begin{aligned}
v_{1}\cdot v_{2}& =(-2)\left(\frac{5}{8}-\frac{3\:\sqrt{15}i}{8}\right)+(1)\left(-\frac{1}{2}\right)+(0)(1)  \\
&=-2\cdot\frac58+2\cdot\frac{3\:\sqrt{15}i}8-\frac12 \\
&=-\frac{10}{8}+\frac{6\:\sqrt{15}i}{8}-\frac12 \\
&=-\frac{7}{4}+\frac{3\:\sqrt{15}i}{4}
\end{aligned}$$

计算$v_1$ 和$v_{3}$ 的内积

------------------------------------------------------------------

$$\begin{aligned}
v_{1}\cdot v_{3}& =(-2)\left(\frac{5}{8}+\frac{3\:\sqrt{15i}}{8}\right)+(1)\left(-\frac{1}{2}\right)+(0)(1) \\
&=-2\cdot\frac58-2\cdot\frac{3\:\sqrt{15}i}8-\frac12 \\
&=-\frac{7}{4}-\frac{3\:\sqrt{15}i}{4}
\end{aligned}$$

计算$v_{2}$ 和$v_{3}$ 的内积

$$\begin{aligned}
v_{2}^{*}\cdot v_{3}& =\left(\frac{5}{8}+\frac{3\:\sqrt{15}i}{8}\right)\left(\frac{5}{8}+\frac{3\:\sqrt{15}i}{8}\right)+\left(-\frac{1}{2}\right)\left(-\frac{1}{2}\right)+(1)(1) \\
&=-\frac{55}{32}+\frac{15\sqrt{15}i}{32}+\frac{1}{4}+1 \\
&=-\frac{15}{32}+\frac{15\:\sqrt{15}i}{32}
\end{aligned}$$

所以，特征向量$v_1$ 和$v_{2}$ 、 $v_1$ 和$v_3$ 、 $v_2$ 和$v_3$ 不是正交的。

### (4) Eigenvalues and Eigenvectors-2

(a) Find out the eigenvalues and eigenvectors of following matrix

$$A=\left(\begin{array}{rrr}2&0&-2\\-2i&i&2i\\1&0&-1\end{array}\right)$$

特征值满足以下特征方程：

$$det(A-\lambda I)=0$$

计算行列式

------------------------------------------------------------------

$$A-\lambda E=\begin{pmatrix}2-\lambda&0&-2\\-2i&i-\lambda&2i\\1&0&-\lambda-1\end{pmatrix}$$

按第二列展开

$$\begin{aligned}
&(i-\lambda)\left(\begin{matrix}{2-\lambda}&{-2}\\{1}&{-\lambda-1}\\\end{matrix}\right)\xrightarrow{c_{1}+c_{2}} \\
&(i-\lambda)\begin{pmatrix}-\lambda&-2\\-\lambda&-\lambda-1\end{pmatrix}\xrightarrow{r_{2}-r_{1}} \\
&(i-\lambda)\begin{pmatrix}-\lambda&-2\\0&1-\lambda\end{pmatrix}
\end{aligned}$$

得到特征方程

$$\lambda\left(i-\lambda\right)\left(\lambda-1\right)=0$$

所以特征值为

$$\begin{aligned}\lambda_1&=0\\\lambda_2&=1\\\lambda_3&=i\end{aligned}$$

对于$\lambda_{1}=0$

$$A=\begin{pmatrix}2&0&-2\\-2i&i&2i\\1&0&-1\end{pmatrix}$$

$$\begin{pmatrix}2&0&-2\\-2i&i&2i\\1&0&-1\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

------------------------------------------------------------------

我们得到三个方程

(2.266)

$$\begin{aligned}
2x_{1}-2x_{3}& =0  \\
-2ix_{1}+ix_{2}+2ix_{3}& =0  \\
x_{1}-x_{3}& =0 
\end{aligned}$$

所以一个特征向量是：

$$v_1=\begin{pmatrix}x_1\\0\\x_1\end{pmatrix}$$

令$x_1=1$ 可得

$$v_1=\begin{pmatrix}1\\0\\1\end{pmatrix}$$

对于$\lambda_{2}=1$

$$A-I=\begin{pmatrix}1&0&-2\\-2i&i-1&2i\\1&0&-2\end{pmatrix}$$

$$\begin{pmatrix}1&0&-2\\-2i&i-1&2i\\1&0&-2\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$\begin{aligned}
x_1-2x_3& =0  \\
-2ix_{1}+(i-1)x_{2}+2ix_{3}& =0  \\
x_1-2x_3& =0 
\end{aligned}$$

所以一个特征向量是：

------------------------------------------------------------------

$$v_2=\begin{pmatrix}2x_3\\\frac{2i}{i-1}x_3\\x_3\end{pmatrix}$$

令$x_3=1$ 可得

$$\begin{pmatrix}2\\\frac{2i}{i-1}\\1\end{pmatrix}$$

对于$\lambda_{3}=i$

$$A-iI=\begin{pmatrix}2-i&0&-2\\-2i&0&2i\\1&0&-i-1\end{pmatrix}$$

$$\begin{pmatrix}2-i&0&-2\\-2i&0&2i\\1&0&-i-1\end{pmatrix}\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}=\begin{pmatrix}0\\0\\0\end{pmatrix}$$

我们得到三个方程

$$\begin{aligned}
(2-i)x_{1}-2x_{3}& =0  \\
-2ix_1-2ix_3& =0  \\
-x_{1}+(-i-1)x_{3}& =0 
\end{aligned}$$

所以一个特征向量是：

$$v_3=\begin{pmatrix}0\\x_2\\0\end{pmatrix}$$

令$x_{2}=1$ 可得

------------------------------------------------------------------

$$v_3=\begin{pmatrix}0\\[0.3em]1\\[0.3em]0\end{pmatrix}$$

## (b) The $2\times2$ rotation matrix in x-y plane can be written as

$$R=\left(\begin{array}{rr}cos\theta&-sin\theta\\sin\theta&cos\theta\end{array}\right)$$

### Show that the rotation matrix R has no real eigenvalues.Find the complex eigenvalue and eigenvector.

特征值满足以下特征方程：

$$det(R-\lambda I)=0$$

计算行列式

$$R-\lambda I=\begin{pmatrix}cos\theta-\lambda&-sin\theta\\sin\theta&cos\theta-\lambda\end{pmatrix}$$

$$\begin{aligned}
det(R-\lambda I)& =\begin{vmatrix}cos\theta-\lambda&-sin\theta\\[0.3em]sin\theta&cos\theta-\lambda\end{vmatrix}  \\
&=cos^{2}\:\theta-2\lambda\cos\theta+\lambda^{2}+sin^{2}\:\theta 
\end{aligned}$$

得到特征方程

$$\lambda^2-2\lambda\cos\theta+1=0$$

得到特征值

$$\begin{aligned}\lambda_1&=cos\theta+i\sin\theta\\\lambda_2&=cos\theta-i\sin\theta\end{aligned}$$

------------------------------------------------------------------

对于$\lambda _{1}= cos$ $\theta + i$ sin $\theta$

$$\begin{pmatrix}-i\sin\theta&-\sin\theta\\sin\theta&-i\sin\theta\end{pmatrix}\begin{pmatrix}v_{1x}\\v_{1y}\end{pmatrix}=0$$

所以一个特征向量为

$$v_1=\begin{pmatrix}v_{1x}\\iv_{1x}\end{pmatrix}$$

令$v_{1x}=1$ 可得

$$v_1=\begin{pmatrix}1\\i\end{pmatrix}$$

对于$\lambda _{2}= \lambda _{2}= cos$ $\theta - i$ sin $\theta$

$$\begin{pmatrix}i\:sin\:\theta&-sin\:\theta\\sin\:\theta&i\:sin\:\theta\end{pmatrix}\begin{pmatrix}v_{1x}\\v_{1y}\end{pmatrix}=0$$

所以一个特征向量为

$$v_1=\begin{pmatrix}v_{2x}\\-iv_{2x}\end{pmatrix}$$

令$v_{2x}=1$ 可得

$$v_1=\begin{pmatrix}1\\-i\end{pmatrix}$$

### 3Homework(320241010

Theorem of simultanoues diagonaligability.Let $A,B\in M_{n}\left(C\right)$ ,the set of all $n\times n$ matrics with complex entries, be diagonaligable.Then $[A,B]=0$ ,if and only if there is an invertible $S\in M_{n}(C)$ such that $SAS^{-1}$ and $SBS^{-1}$ are both diagonal.

假设$[A,B]=0$ ，即$AB=BA$ 。由于$A$ 和$B$ 都是可对角化的矩阵，所以我们可以找到与$A$ 和$B$ 对角化的矩阵。

------------------------------------------------------------------

首先， $A$ 可对角化，存在一个可逆矩阵$P$ 使得$P^{-1}AP$ 是对角矩阵，记作$D_{A}$ 。考虑$B$ 在基底$P$ 下的表示，即$B^{\prime}=P^{-1}BP_{\alpha}$ 由于$AB=BA$ ，我们有：

$$A(PB)=(PB)A$$

$$PA'B=BPA$$

$$A'B'=B'A'$$

即$D_{A}B^{\prime}=B^{\prime}D_{A}$

由于$D_{A}$ 是对角矩阵，这意味着$B^{\prime}$ 可以写成块对角矩阵的形式，其中每个块与$A$ 的特征值对应的特征空间相匹配。进一步地，由于$B$ 也可对角化的性质， $B^{\prime}$ 也可以被对角化。我们可以找到一个新的可逆矩阵$Q$ 使得$Q^{-1}B^{\prime}Q$ 是对角矩阵，记作$D_{B}$

令$S=PQ$ ，则：

$$\begin{aligned}SAS^{-1}&=P(QAQ^{-1})P^{-1}=PD_AP^{-1}\\SBS^{-1}&=P(QBQ^{-1})P^{-1}=PD_BP^{-1}\end{aligned}$$

此时， $SAS^{-1}$ 和$SBS^{-1}$ 都是对角矩阵。

## 4Homework(4) 20241011

# (1) Proof that $[E,t]=i\hbar$ and thus $(\Delta_{\psi}E)(\Delta_{\psi}t)\geq\frac{\hbar}{2}$

由薛定谔方程

$$E\psi(t)=i\hbar\frac{\partial\psi(t)}{\partial t}$$

可得

$$E\to i\hbar\frac{\partial}{\partial t}$$

于是

------------------------------------------------------------------

$$\begin{aligned}
[E,t]\psi(t)& =(E\cdot t-t\cdot E)\psi(t) \\
&=i\hbar\frac{\partial}{\partial t}(t\cdot\psi(t))-t\cdot i\hbar\frac{\partial}{\partial t}\psi(t) \\
&=i\hbar\psi(t)+i\hbar t\frac{\partial\psi(t)}{\partial t}-i\hbar t\frac{\partial\psi(t)}{\partial t} \\
&=i\hbar\psi(t)
\end{aligned}$$

即证明得到

$$[E,t]=i\hbar $$

接着我们定义$\langle A\rangle _{\psi }= \langle \psi | A$ $| \psi \rangle , | \Psi _{A}\rangle = ( A- \langle A\rangle _{\psi })$ $| \psi \rangle$, 且$\langle \psi$ $| \psi \rangle = 1$

$$\begin{aligned}
\langle\psi_{A}\mid\psi_{A}\rangle & =\left\langle\psi\right|\left(A-\left\langle A\right\rangle_{\psi}\right)^{2}\left|\psi\right\rangle  \\
&=\langle\left(A-\langle A\rangle_{\psi}\right)^{2}\rangle_{\psi} \\
&=\left\langle A^{2}\right\rangle_{\psi}-\left\langle A\right\rangle_{\psi}^{2} \\
&=\begin{pmatrix}A_{\psi}A\end{pmatrix}^{2}
\end{aligned}$$

由柯西-施瓦兹不等式

$$\begin{aligned}
\left|\left\langle\psi_{A}\left|\psi_{B}\right\rangle\right|^{2}\right|& \leqslant\langle\psi_{A}\:|\psi_{A}\:\rangle\:\langle\psi_{B}\:|\psi_{B}\rangle  \\
&\leqslant\left(\Delta_{\psi}A\right)^{2}\cdot\left(\Delta_{\psi}B\right)^{2}
\end{aligned}$$

于是

$$\begin{aligned}
\langle\psi_{A}|\psi_{B}\rangle & =\langle\psi\left|\left(A-\langle A\rangle_{\psi}\right)\right|\cdot\left(B-\langle B\rangle_{\psi}\right)|\psi\rangle  \\
&=\left\langle\psi\left|AB-A\left\langle B\right\rangle\right._{\psi}-B\left\langle A\right\rangle_{\psi}+\left\langle A\right\rangle_{\psi}\left\langle B\right\rangle_{\psi}\left|\psi\right\rangle\right. \\
&=\left\langle\psi\left|AB\right|\psi\right\rangle-\left\langle A\right\rangle_{\psi}\left\langle B\right\rangle_{\psi}
\end{aligned}$$

当$A=A^\dagger,B=B^\dagger$ 时， $\langle\psi\left|AB\left|\psi\right\rangle=\left\langle\psi\left|BA\right.\right|\psi\right\rangle^{*}$ 于是

------------------------------------------------------------------

$$\begin{aligned}
\langle\psi|[A-B]\:|\psi\rangle & =\left\langle\psi\right|AB-\left\langle A\right\rangle_{\psi}\left\langle B\right\rangle_{\psi}\left|\psi\right\rangle-\left\langle\psi\right|AB-\left\langle A\right\rangle_{\psi}\left\langle B\right\rangle_{\psi}\left|\psi\right\rangle^{*} \\
&=2iIm\left(\left\langle\psi\right|AB-\left\langle A\right\rangle_{\psi}\left\langle B\right\rangle_{\psi}\left|\psi\right\rangle\right) \\
&=2iIm\left(\langle\psi_{A}|\psi_{B}\rangle\right)
\end{aligned}$$

于是

$$\begin{aligned}
\frac{1}{4}\left|\left\langle\psi\right|[A-B]\left|\psi\right\rangle\right|^{2}& =\left|Im\left(\langle\psi_{A}|\psi_{B}\rangle\right)\right|^{2} \\
&\leqslant|\left(\langle\psi_{A}|\psi_{B}\rangle\right)|^{2}+|\left(\langle\psi_{A}|\psi_{B}\rangle\right)|^{2} \\
&\leqslant\left|\langle\psi_{A}|\psi_{B}\rangle\right|^{2}
\end{aligned}$$

即可得到

$$\frac{1}{4}\left|\left\langle\psi\left|\left[A-B\right]\left|\psi\right\rangle\right|\right.^{2}\leqslant\left(\Delta_{\psi}A\right)^{2}\cdot\left(\Delta_{\psi}B\right)^{2}\right.$$

令$A=E,B-t$, 再对两边开平方，即可得到

$$(\Delta_\psi E)(\Delta_\psi t)\geq\frac{\hbar}{2}$$

### (2) $1-D$ infinite wall

### Consider $1-D$ infinite wall for

$$V(x)=\begin{cases}0&,-\frac{L}{2}\leqslant x\leqslant\frac{L}{2}\\[2ex]\infty&,elsewhere\end{cases}$$

### (a) Work out the wave function and energy spectrum

由薛定谔方程可得

$$i\hbar\frac{\partial\Phi(r,t)}{\partial t}=-\frac{\hbar^2}{2m}\nabla^2\Phi(r,t)+V(r)\Phi(r,t)=E\Phi(r,t)$$

于是

$$\begin{aligned}-\frac{\hbar^2}{2m}\nabla^2\phi(r)+V(r)\psi=E\phi(r)\end{aligned}$$

------------------------------------------------------------------

现考虑一维情况，当$-\frac{L}{2}\leq x\leq\frac{L}{2}$ 时

由于其通解为

于是

$$-\frac{\hbar^2}{2m}\frac{\partial^2\phi}{\partial x^2}=E\phi $$

$$\phi+\frac{2mE}{\hbar^2}\frac{\partial\phi}{\partial x^2}=0$$

$$\phi(x)=a\:sin\:\sqrt{\frac{2mE}{\hbar}}x+b\:cos\:\sqrt{\frac{2mE}{\hbar}}x$$

$$\phi(-\frac{L}{2})=-a\:sin\:\sqrt{\frac{2mE}{\hbar}}\cdot\frac{L}{2}+b\:cos\:\sqrt{\frac{2mE}{\hbar}}\cdot\frac{L}{2}=0$$

$$\phi(\frac{L}{2})=a\:sin\:\sqrt{\frac{2mE}{\hbar}}\cdot\frac{L}{2}+b\:cos\:\sqrt{\frac{2mE}{\hbar}}\cdot\frac{L}{2}=0$$

联立可得$b=0$

那么

得到

进行归一化操作可得

$$\sqrt{\frac{2mE}{\hbar}}\cdot\frac{L}{2}=n\pi\quad(n=0,1,2,3,\cdots)$$

$$E_n=\frac{4n^2\pi^2}{L^2}\cdot\frac{\hbar}{2m}=\frac{2n^2\pi^2\hbar}{mL^2}$$

$$\begin{aligned}\int_{-\infty}^{\infty}a^2\:sin^2\:\sqrt{\frac{2mE}{\hbar}}xdx=\frac{L}{2}a^2=1\end{aligned}$$

得到$a=\sqrt{\frac{2}{L}}$ 得到波函数

### (b) Proof that

$$\phi_n(x)=\sqrt{\frac{2}{L}}\:sin\:\sqrt{\frac{2mE_n}{\hbar}}x$$

$$\int dx\cdot\phi_{n}^{*}\left(x\right)\cdot\phi_{m}\left(x\right)=\delta_{nm}$$

当$n\neq m$ 时

------------------------------------------------------------------

$$\begin{aligned}
\int\phi_{n}^{*}\left(x\right)\cdot\phi_{m}\left(x\right)\cdot dx& =\int\:\sqrt{\frac{2}{L}}\:sin\:\sqrt{\frac{2mE_{n}}{\hbar}}x\cdot\:\sqrt{\frac{2}{L}}\:sin\:\sqrt{\frac{2mE_{m}}{\hbar}}x\cdot dx \\
&=\frac{2}{L}\int sin\:\sqrt{\frac{2mE_{n}}{\hbar}}x\cdot sin\:\sqrt{\frac{2mE_{m}}{\hbar}}x\cdot dx
\end{aligned}$$

令$k_{n}=\sqrt{\frac{2mE_{n}}{\hbar}}$, 由积化和差可得

$$\int_{-\frac{L}{2}}^{\frac{L}{2}}sink_{n}x\cdot sink_{m}x\cdot dx=\frac{1}{2}\left[\frac{sin\left(k_{n}-k_{m}\right)x}{k_{n}-k_{m}}-\frac{sin\left(k_{n}+k_{m}\right)x}{k_{n}+k_{m}}\right]\left|\begin{array}{c}\frac{L}{2}\\-\frac{L}{2}\end{array}\right|$$

由于$k_{n}\frac{L}{2}=n\pi,k_{m}\frac{L}{2}=m\pi$, 则$(n-m)$ 和$(n+m)$ 均为整数于是

$$\int_{-\frac{L}{2}}^{\frac{L}{2}}sin\:k_nx\:sin\:k_mxdx=0$$

当$n=m$ 时

$$\begin{aligned}
\int\phi_{n}^{*}\left(x\right)\cdot\phi_{m}\left(x\right)\cdot dx& =\int\sqrt{\frac{2}{L}}sin\:\sqrt{\frac{2mE_{n}}{\hbar}}x\cdot\:\sqrt{\frac{2}{L}}sin\:\sqrt{\frac{2mE_{n}}{\hbar}}x\cdot dx \\
&=\frac{2}{L}\int(sin\sqrt{\frac{2mE_{n}}{\hbar}}x)^{2}\cdot dx \\
&=1
\end{aligned}$$

(c) Calculate the expectation values (c) $\langle x\rangle$ $\langle x\rangle,\langle x^{2}\rangle,\langle p\rangle,\langle p^{2}\rangle$ (p²) $\langle p^{2}\rangle$ for $\phi_1$ $\phi_1$ $,\phi_2$ $,\phi_2$ $\phi_1,\phi_2,\phi_3$, Φ3 $.\phi_3$ and check the uncertainty principle

位置期望值$\langle x\rangle$

$$\langle x\rangle=\int_{-\frac{L}{2}}^{\frac{L}{2}}x|\phi_n(x)|^2dx$$

由于$sin^{2}\left(\frac{2n\pi x}{L}\right)$ 对称于$x=0.$ 因此： $\langle x\rangle=0$

位置平方期望值$\langle x^{2}\rangle$

------------------------------------------------------------------

$$\begin{aligned}
\langle x^{2}\rangle & =\int_{-\frac{L}{2}}^{\frac{L}{2}}x^{2}|\phi_{n}(x)|^{2}dx  \\
&=\frac{2}{L}\int_{-\frac{L}{2}}^{\frac{L}{2}}x^{2}\:sin^{2}\left(\frac{2n\pi x}{L}\right)dx \\
&=\frac{L^{2}}{12}\left(1-\frac{1}{4n^{2}\pi^{2}}\right)
\end{aligned}$$

动量期望值$\langle p\rangle$

因为动量算符作用在实函数上，结果为纯虚数，积分后为零。

$$\langle p\rangle=0$$

动量平方期望值$\langle p^{2}\rangle$

$$\begin{aligned}
\langle p^{2}\rangle & =\int_{-\frac{L}{2}}^{\frac{L}{2}}\phi_{n}^{*}(x)\left(-\hbar^{2}\frac{\partial^{2}}{\partial x^{2}}\right)\phi_{n}(x)dx  \\
&=\int_{-\frac{L}{2}}^{\frac{L}{2}}\phi_{n}^{*}(x)\left(-\left(\frac{2n\pi}{L}\right)^{2}\phi_{n}(x)\right)\phi_{n}(x)dx \\
&=\frac{4\hbar^{2}n^{2}\pi^{2}}{L^{2}}
\end{aligned}$$

检验测不准原理

$$(\Delta x)^2=\left\langle x^2\right\rangle-\left\langle x\right\rangle^2=\frac{L^2}{12}\left(1-\frac{1}{4n^2\pi^2}\right)$$

$$(\Delta p)^2=\langle p^2\rangle-\langle p\rangle^2=\frac{4\hbar^2n^2\pi^2}{L^2}$$

$$\Delta x\cdot\Delta p=\sqrt{\frac{1}{12}\left(1-\frac{1}{4n^2\pi^2}\right)}\cdot2\hbar n\pi $$

------------------------------------------------------------------

当$n=1$ 时

$$\begin{aligned}
\left\langle x\right\rangle & =0 \\
\langle x^{2}\rangle & =\frac{L^{2}}{12}\left(1-\frac{1}{4\pi^{2}}\right) \\
\left\langle p\right\rangle & =0 \\
\langle p^{2}\rangle & =\frac{4\hbar^{2}\pi^{2}}{L^{2}} \\
\Delta x\cdot\Delta p& =\:\sqrt{\frac{1}{12}\left(1-\frac{1}{4\pi^{2}}\right)}\cdot2\hbar\pi\geq\frac{\hbar}{2} 
\end{aligned}$$

当$n=2$ 时

$$\begin{aligned}
\left\langle x\right\rangle & =0 \\
\langle x^{2}\rangle & =\frac{L^{2}}{12}\left(1-\frac{1}{16\pi^{2}}\right) \\
\left\langle p\right\rangle & =0 \\
\langle p^{2}\rangle & =\frac{16\hbar^{2}\pi^{2}}{L^{2}} \\
\Delta x\cdot\Delta p& =\:\sqrt{\frac1{12}\left(1-\frac1{16\pi^{2}}\right)}\cdot4\hbar\pi\geq\frac\hbar2 
\end{aligned}$$

当$n=3$ 时

$$\begin{aligned}
\left\langle x\right\rangle & =0 \\
\langle x^{2}\rangle & =\frac{L^{2}}{12}\left(1-\frac{1}{36\pi^{2}}\right) \\
\left\langle p\right\rangle & =0 \\
\langle p^{2}\rangle & =\frac{36\hbar^{2}\pi^{2}}{L^{2}} \\
\Delta x\cdot\Delta p& =\:\sqrt{\frac{1}{12}\left(1-\frac{1}{36\pi^{2}}\right)}\cdot6\hbar\pi\geq\frac{\hbar}{2} 
\end{aligned}$$

为解决这个问题我们编写了一个matlab代码（代码见附录2）进行绘制当$n=1$ 时， $\phi _{1}( x) = \sqrt {\frac 2L}$ $sin\left ( \frac {2\pi x}L\right )$

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/f2uwGZtowwCvvgpSYkd8GN0xk6nNEgmbM)

图1: $\phi _{1}( x) = \sqrt {\frac 2L}$ $sin\left ( \frac {2\pi x}L\right )$

当$n=2$ 时， $\phi _{1}( x) = \sqrt {\frac 2L}$ $sin\left ( \frac {4\pi x}L\right )$

![](https://storage.simpletex.cn/view/ff6wr6wIf47R5mS0K5dSQ5Oq3hMRLRTtm)

图2: $\phi _{1}( x) = \sqrt {\frac 2L}$ $sin\left ( \frac {4\pi x}L\right )$

当$n=3$ 时， $\phi _{1}( x) = \sqrt {\frac 2L}$ $sin\left ( \frac {6\pi x}L\right )$

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fcx9a2Wx8tscH4MA2xH4ZCil0hgkdlPig)

## 5 Homework(5) 20241014

### Harmonic Oscillator-I

 One of the expression of the Hermite polynomial is

$$H_n(y)=(-1)^ne^{y^2}(\frac{d}{dy})^ne^{-y^2}$$

(a) Derive $H_{0},H_{1},H_{2},H_{3},H_{4}$

$$\begin{aligned}H_0(y)&=(-1)^0e^{y^2}(\frac{d}{dy})^0e^{-y^2}\\&=1\end{aligned}$$

$$\begin{aligned}
H_{1}(y)& =(-1)^{1}e^{y^{2}}(\frac{d}{dy})^{1}e^{-y^{2}}  \\
&=-e^{y^{2}}(-2y)e^{-y^{2}} \\
&=2y
\end{aligned}$$

------------------------------------------------------------------

$$\begin{aligned}
H_{2}(y)& =(-1)^{2}e^{y^{2}}(\frac{d}{dy})^{2}e^{-y^{2}} \\
&=-e^{y^{2}}(-2y+4y^{2})e^{-y^{2}} \\
&=-2y+4y^{2}
\end{aligned}$$

$$\begin{aligned}
H_{3}(y)& =(-1)^{3}e^{y^{2}}(\frac{d}{dy})^{3}e^{-y^{2}} \\
&=e^{y^{2}}(8y^{3}-12y)e^{-y^{2}} \\
&=8y^{3}-12y
\end{aligned}$$

$$\begin{aligned}
H_{4}(y)& =(-1)^{4}e^{y^{2}}(\frac{d}{dy})^{4}e^{-y^{2}} \\
&=e^{y^{2}}(12-48y^{2}+16y^{4})e^{-y^{2}} \\
&=12-48y^2+16y^4
\end{aligned}$$

### (b) The differential equation of the Hermite polynomial is

$$H_n^{''}(y)-2yH_n^{''}(y)+2nH_n(y)=0$$

It can be written as

$$H_{n+1}(y)=2yH_n(y)-2nH_{n-1}(y)$$

By using

$$\begin{matrix}\frac{\partial H_n(y)}{\partial y}=2nH_{n-1}(y)\end{matrix}$$

Derive $H_{5},H_{6}$

------------------------------------------------------------------

$$\begin{aligned}
H_{5}(y)& =2yH_{4}(y)-8H_{3}(y) \\
&=2y(12-48y^{2}+16y^{4})-8(8y^{3}-12y) \\
&=32y^5-160y^3+120y
\end{aligned}$$

$$\begin{aligned}
H_{6}(y)& =2yH_{5}(y)-10H_{4}(y) \\
&=2y(32y^5-160y^3+120y)-10(12-48y^2+16y^4) \\
&=64y^{5}-480y^{4}+720y^{2}-120
\end{aligned}$$

# (c) Sketch $H_{0},H_{1},......,H_{6}$

为解决这个问题我们编写了一个matlab代码（代码见附录3）进行绘制，并通过美化得到

![](https://storage.simpletex.cn/view/fN04uPsfttxgmZmQUosruGOs23I0mV9wL)

![](https://storage.simpletex.cn/view/fSzr6FGaH6U90WzLX2HZCw7XkdONEn8NW)

(a) $H_0(y)$

(b) $H_1(y)$

![](https://storage.simpletex.cn/view/fwrTWpIYQVnYmIggKsHMHurLVeDpM1QBe)
(c) Hz()

图4: $H_0(y)$ 至$H_2(y)$ 示意图

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fnMDkZ8FA6Hg0mN9u4RrICPRnmG5qsl45)
图5： $H_3(y)$ 至$H_6(y)$ 示意图

### (d) By using normaligation condition, try to find out

$$\psi_n(x)=(\frac{m\omega}{T\hbar})^{\frac{1}{4}}\frac{1}{\sqrt{2^nn!}}H_n(y)e^{-y^2}$$

简谐振子的波函数表示

$$\psi_n(x)=N_nH_n\left(\sqrt{\frac{m\omega}{\hbar}}x\right)e^{-\frac{m\omega x^2}{2\hbar}}$$

由归一化条件

$$\int_{-\infty}^{\infty}|\psi_n(x)|^2dx=1$$

令$y=$ $\sqrt {\frac {m\omega }\hbar }x$ ，则$dx=\sqrt{\frac{\hbar}{m\omega}}dy$

------------------------------------------------------------------

$$\begin{aligned}\int_{-\infty}^{\infty}|N_n|^2|H_n(y)|^2e^{-y^2}\sqrt{\frac{\hbar}{m\omega}}dy=1\end{aligned}$$

$$\begin{aligned}|N_n|^2\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}|H_n(y)|^2e^{-y^2}dy=1\end{aligned}$$

于是

$$\begin{aligned}
\frac1{|N_{n}^{2}|}& =\:\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}e^{-y^{2}}H_{n}^{2}(y)dy \\
&=(-1)^{n}\:\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}H_{n}(y)\frac{d^{n}(e^{-y^{2}})}{dy^{n}}dy \\
&=\frac{\left(-1\right)^{n}}{\alpha}H_{n}(y)\frac{^{n-1}(e^{-y^{2}})}{dy^{n-1}}\Bigg|_{y=-\infty}^{y=+\infty}+\left(-1\right)^{n+1}\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}\frac{dH_{n}(y)}{dy}\frac{d^{n-1}(e^{-y^{2}})}{dy^{n-1}}dy
\end{aligned}$$

由于第一项结果为0，对第二项进行$(n-1)$ 次分部积分可得

$$\frac{1}{|N_n^2|}=\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}\frac{d^n{}_n(y)}{dy^n}e^{-y^2}dy$$

$H_{n}(y)$ 中最高次项$y^n$ 的系数是$2^n$, 所以

$$\begin{aligned}\frac{1}{|N_n^2|}=2^nn!\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}e^{-y^2}dy=2^nn!\sqrt{\frac{\hbar\pi}{m\omega}}\end{aligned}$$

$$N_n=\left(\frac{m\omega}{\pi\hbar}\right)^{1/4}\frac{1}{\sqrt{2^nn!}}$$

于是

$$\psi_n(x)=\left(\frac{m\omega}{\pi\hbar}\right)^{1/4}\frac{1}{\sqrt{2^nn!}}H_n\left(\sqrt{\frac{m\omega}{\hbar}}x\right)e^{-\frac{m\omega x^2}{2\hbar}}$$

## (e) Please verify the cthogonal condition

$$\int dx\psi_n^*(x)\psi_m(x)=\delta_{nm}$$

------------------------------------------------------------------

$$\psi_n(x)=\left(\frac{m\omega}{\pi\hbar}\right)^{1/4}\frac{1}{\sqrt{2^{nn!}}}H_n\left(\sqrt{\frac{m\omega}{\hbar}}x\right)e^{-\frac{m\omega x^2}{2\hbar}}$$

$$\psi_m(x)=\left(\frac{m\omega}{\pi\hbar}\right)^{1/4}\frac{1}{\sqrt{2^mm!}}H_m\left(\sqrt{\frac{m\omega}{\hbar}}x\right)e^{-\frac{m\omega x^2}{2\hbar}}$$

于是

### 6Homework(6) 20241017

### Harmonic Oscillator-II

(1) By using

$$(a_+a_-+\frac{1}{2}\hbar\omega)\psi(x)=E\psi(x)$$

$$(a_-a_+-\frac{1}{2}\hbar\omega)\psi(x)=E\psi(x)$$

And normaligation condition

$$\int dx\left|\psi_{n}\left(x\right)\right|^{2}=1\textbf{,for all}n$$

$$\begin{aligned}
\int_{-\infty}^{\infty}\psi_{n}^{*}(x)\psi_{m}(x)dx& =\left(\frac{m\omega}{\pi\hbar}\right)^{1/2}\frac{1}{\sqrt{2^{n}m!2^{m}m!}}\sqrt{\frac{\hbar}{m\omega}}\int_{-\infty}^{\infty}H_{n}(y)H_{m}(y)e^{-y^{2}}dy  \\
&=\left(\frac{m\omega}{\pi\hbar}\right)^{1/2}\frac{1}{\sqrt{2^{n}n!2^{m}m!}}\sqrt{\frac{\hbar}{m\omega}}2^{n}n!\:\sqrt{\pi}\delta_{nm} \\
&=\left(\frac{m\omega}{\pi\hbar}\right)^{1/2}\:\sqrt{\frac{\hbar}{m\omega}}\:\sqrt{\pi}\delta_{nm} \\
&=\delta_{nm}
\end{aligned}$$

------------------------------------------------------------------

### (a) Show that

And thus

由于

$$\int|a_+\psi_n(x)|^2dx=(n+1)\hbar\omega $$

$$\int|a_-\psi_n(x)|^2dx=n\hbar\omega $$

$$a_+|\psi_n(x)\rangle=i\:\sqrt{(n+1)\hbar\omega}|\psi_{n+1}(x)\rangle $$

$$a_-|\psi_n(x)\rangle=-i\sqrt{n\hbar\omega}|\psi_{n-1}(x)\rangle $$

$$\begin{aligned}H&=(a_-a_+-\frac{1}{2}\hbar\omega)\psi(x)\\H&=(a_+a_-+\frac{1}{2}\hbar\omega)\psi(x)\end{aligned}$$

$$H\psi_{n}(x)=(a_{+}a_{-}+\frac{1}{2}\hbar\omega)\psi_{n}(x)=E_{n}\psi_{n}(x)\\H\psi_{n}(x)=(a_{-}a_{+}-\frac{1}{2}\hbar\omega)\psi_{n}(x)=E_{n}\psi_{n}(x)$$

$$E_n=(n+\frac{1}{2})\hbar\omega $$

$$(a_{+}a_{-}+\frac12\hbar\omega)\psi_{n}(x)=(n+\frac12)\hbar\omega\psi_{n}(x)\\(a_{-}a_{+}-\frac12\hbar\omega)\psi_{n}(x)=(n+\frac12)\hbar\omega\psi_{n}(x)$$

于是

由于

于是

可得

$$\begin{aligned}&a_{+}a_{-}\psi_{n}(x)=n\hbar\omega\psi_{n}(x)\\&a_{-}a_{+}\psi_{n}(x)=(n+1)\hbar\omega\psi_{n}(x)\end{aligned}$$

------------------------------------------------------------------

于是

$$\begin{aligned}
\int|a_{+}\psi_{n}(x)|^{2}dx& =\int(a_{+}\psi_{n}(x))^{*}(a_{+}\psi_{n}(x))dx  \\
&=\int(a_{-}\psi_{n}^{*}(x))(a_{+}\psi_{n}(x))dx \\
&=(n+1)\hbar\omega 
\end{aligned}$$

$$\begin{aligned}
\int|a_{-}\psi_{n}(x)|^{2}dx& =\int(a_{-}\psi_{n}(x))^{*}(a_{-}\psi_{n}(x))dx  \\
&=\int(a_{+}\psi_{n}^{*}(x))(a_{-}\psi_{n}(x))dx \\
&=n\hbar\omega 
\end{aligned}$$

由于

$$a_-a_+-a_+a_-=\hbar\omega $$

故

$$a_-a_+|\psi_n\rangle=(a+a-+\hbar w)|\psi_n\rangle $$

令$a_{+ }| \psi _{n}\rangle = C_{n}| \psi _{n+ 1}\rangle$ , $a_{- }| \psi _{n}\rangle = D_{n}| \psi _{n- 1}\rangle$

$$H=a_-a_+-\frac{1}{2}\hbar w$$

$$H|\psi_n\rangle=E|\psi_n\rangle $$

$$(a_-a_+-\frac{1}{2}\hbar\omega)|\psi_n\rangle=(n+\frac{1}{2})\hbar\omega|\psi_n\rangle $$

$$a_-a_+|\psi_n\rangle=(n+1)\hbar w|\psi_n\rangle $$

同理可得

$$a_+a_-|\psi_n\rangle=n\hbar w|\psi_n\rangle $$

由于

$$\langle\psi_n|a_-a_+|\psi_n\rangle=(n+1)\hbar\omega\langle\psi_n|\psi_n\rangle $$

------------------------------------------------------------------



------------------------------------------------------------------

对$\psi_{0}(x)=Ae^{-\frac{m\omega x^{2}}{2h}}$ 进行归一化处理可得

$$\begin{aligned}
\int_{-\infty}^{\infty}|\psi_{0}(x)|^{2}dx& =1 \\
A^{2}\int_{-\infty}^{\infty}e^{-{\frac{m\omega x^{2}}{h}}}dx& =1 \\
A^{2}\:\sqrt{\frac{\pi\hbar}{m\omega}}& =1 
\end{aligned}$$

得到

$$A=\left(\frac{m\omega}{\pi\hbar}\right)^{\frac{1}{4}}$$

综上所述

$$C=\left(\frac{m\omega}{\pi\hbar}\right)^{\frac{1}{4}}\frac{(-1)^n}{\sqrt{n!(\hbar\omega)^n}}$$

(2) Harmonic Oscillator in 3D

### consider harmonic oscillator in 3D

$$E\psi(x_1,x_2,x_3)=-\frac{\hbar}{2m}\nabla^2\psi+\frac{1}{2}m\omega^2r^2\psi $$

$$r^2=x_1^2+x_2^2+x_3^2$$

### (1) Try to find out the wave function and energy of ground state byusing

$$a_{i_{\pm}}=\frac{1}{\sqrt{2m}}\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}\pm im\omega x_{i}\right),i=1,2,3$$

$$E\psi(x_1,x_2,x_3)=-\frac{\hbar}{2m}\nabla^2\psi+\frac{1}{2}m\omega^2r^2\psi $$

------------------------------------------------------------------

$$-\frac{\hbar}{2m}\nabla^{2}\psi=\frac{-\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x_{1}^{2}}\psi(x_{1},x_{2},x_{3})+\frac{-\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x_{2}^{2}}\psi(x_{1},x_{2},x_{3})+\frac{-\hbar^{2}}{2m}\frac{\partial^{2}}{\partial x_{3}^{2}}\psi(x_{1},x_{2},x_{3})$$

$$\begin{aligned}\frac{1}{2}m\omega^2r^2\psi=\frac{1}{2}m\omega^2(x_1)^2\psi+\frac{1}{2}m\omega^2(x_2)^2\psi+\frac{1}{2}m\omega^2(x_3)^2\psi\end{aligned}$$

由于

$$\left.\left\{\begin{array}{l}a_{1_-}|\psi_0\rangle=\frac{1}{\sqrt{2m}}(\frac{\hbar}{i}\frac{\partial}{\partial x_1}-im\omega x_1)\psi_0\\\\a_{2_-}|\psi_0\rangle=\frac{1}{\sqrt{2m}}(\frac{\hbar}{i}\frac{\partial}{\partial x_2}-im\omega x_2)\psi_0\\\\a_{3_-}|\psi_0\rangle=\frac{1}{\sqrt{2m}}(\frac{\hbar}{i}\frac{\partial}{\partial x_3}-im\omega x_3)\psi_0\end{array}\right.\right.$$

解得

$$\begin{aligned}
\psi_{0}& =Ce^{-\frac{m\omega({x_{1}}^{2}+{x_{2}}^{2}+{x_{3}}^{2})}{2\hbar}}  \\
&=Ce^{-\frac{m\omega r^{2}}{2\hbar}}
\end{aligned}$$

(2) Workout
$$:[a_{i_{-}},a_{j_{+}}],[a_{i_{-}},a_{j_{-}}],[a_{i_{+}},a_{j_{+}}]$$

由于

$$a_{i_{\pm}}=\frac{1}{\sqrt{2m}}(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}\pm im\omega x_{i})$$

于是

$$\begin{aligned}
a_{i_{-}}a_{j_{+}}\psi & =\frac{1}{2m}(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}-im\omega x_{i})(\frac{\hbar}{i}\frac{\partial}{\partial x_{j}}+im\omega x_{j})\psi   \\
&=\frac{1}{2m}[-\hbar\frac{\partial^{2}}{\partial x_{i}\partial x_{j}}\psi+\hbar m\omega\frac{\partial}{\partial x_{i}}(x_{j}\psi)-\hbar m\omega x_{i}\frac{\partial}{\partial x_{j}}\psi+(m\omega)^{2}x_{i}x_{j}\psi]
\end{aligned}$$

------------------------------------------------------------------

当$i=j$ 时

$$\begin{aligned}
a_{i_{-}}a_{j_{+}}\psi & =\frac{1}{2m}[-\hbar\frac{\partial^{2}}{\partial{x_{i}}^{2}}\psi+\hbar m\omega\frac{\partial x_{i}}{\partial x_{i}}\psi+\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{i}}-\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{i}}+(mwx_{i})^{2}\psi]  \\
&=\{\frac1{2m}[(\frac\hbar i\frac\partial{\partial x_i})^2+(m\omega x_i)^2]+\frac12\hbar\omega\}\psi  \\
&=[H_{i}+\frac{1}{2}\hbar\omega]\psi 
\end{aligned}$$

当$i\neq j$ 时

$$\begin{gathered}
a_{i_{-}}a_{j_{+}}\psi  =\frac{1}{2m}[-\hbar\frac{\partial^{2}\psi}{\partial x_{i}\partial x_{j}}+\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}+\hbar m\omega\frac{\partial x_{j}}{\partial x_{i}}\psi-\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{j}}+(m\omega)^{2}x_{i}x_{j} \\
=\frac{1}{2m}[-\hbar\frac{\partial^{2}\psi}{\partial x_{i}\partial x_{j}}+\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}-\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{j}}+(m\omega)^{2}x_{i}x_{j}\psi] 
\end{gathered}$$

同理可得

当$i=j$ 时

$$a_{i_+}a_{j_-}\psi=[H_i-\frac{1}{2}\hbar\omega]\psi $$

当$i\neq j$ 时

$$a_{i_+}a_{j_-}\psi=\frac{1}{2m}[-\hbar\frac{\partial^2\psi}{\partial x_j\partial x_i}+\hbar m\omega x_i\frac{\partial\psi}{\partial x_j}-\hbar m\omega x_j\frac{\partial\psi}{\partial x_i}+(m\omega)^2x_ix_j\psi]$$

于是

$$[a_{i_-},a_{j_+}]=\begin{cases}\:\hbar\omega&i=j\\\:\frac{1}{m}[\hbar m\omega x_j\frac{\partial}{\partial x_i}-\hbar m\omega x_i\frac{\partial}{\partial x_j}]&i\neq j\end{cases}$$

$$\begin{aligned}
\iota_{i_{-}}a_{j_{-}}\psi & =\frac{1}{2m}(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}-im\omega x_{i})(\frac{\hbar}{i}\frac{\partial}{\partial x_{j}}-im\omega x_{j})\psi   \\
&=\frac{1}{2m}[-\hbar\frac{\partial^{2}}{\partial x_{i}\partial x_{j}}\psi-\hbar m\omega\frac{\partial}{\partial x_{i}}(x_{j}\psi)-\hbar m\omega x_{i}\frac{\partial}{\partial x_{j}}\psi-(m\omega)^{2}x_{i}x_{j}\psi] \\
&=\frac{1}{2m}[-\hbar\frac{\partial^{2}}{\partial x_{i}\partial x_{j}}\psi-\hbar m\omega\frac{\partial x_{j}}{\partial x_{i}}\psi-\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}-\hbar m\omega x_{i}\frac{\partial}{\partial x_{j}}\psi-(m\omega)^{2}x_{i}]
\end{aligned}$$

------------------------------------------------------------------

$$\begin{aligned}
a_{i}\:\psi & =\frac{1}{2m}\left(\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{j}}-im\omega x_{j}\right)\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}-im\omega x_{i}\right)\right)\psi \\
&=\frac{1}{2m}\left(-\hbar^{2}\frac{\partial^{2}\psi}{\partial x_{j}\partial x_{i}}-\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{i}}-\hbar m\omega\frac{\partial x_{i}}{\partial x_{j}}\psi-\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}-m^{2}\omega^{2}x_{i}x_{j}\psi\right)
\end{aligned}$$

于是

$$[a_{i_-},a_{j_-}]=0$$

$$\begin{aligned}
a_{i_{+}}a_{j_{+}}\psi & =\frac{1}{2m}\left(\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}+im\omega x_{i}\right)\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{j}}+im\omega x_{j}\right)\right)\psi \\
&=\frac{1}{2m}\left(-\hbar^{2}\frac{\partial^{2}\psi}{\partial x_{i}\partial x_{j}}+i\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}+i\hbar m\omega\frac{\partial x_{i}}{\partial x_{j}}\psi+i\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{j}}-m^{2}\omega^{2}\right)
\end{aligned}$$

$$\begin{aligned}
j_{+}a_{i_{+}}& =\frac{1}{2m}\left(\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{j}}+im\omega x_{j}\right)\left(\frac{\hbar}{i}\frac{\partial}{\partial x_{i}}+im\omega x_{i}\right)\right)\psi \\
&=\frac{1}{2m}\left(-\hbar^{2}\frac{\partial^{2}\psi}{\partial x_{j}\partial x_{i}}+i\hbar m\omega x_{i}\frac{\partial\psi}{\partial x_{j}}+i\hbar m\omega x_{j}\frac{\partial\psi}{\partial x_{i}}+i\hbar m\omega\psi\frac{\partial x_{j}}{\partial x_{i}}-m^{2}\omega^{2}x_{i}x\right)
\end{aligned}$$

$$[a_{i_+},a_{j_+}]=0$$

### 7Homework(7) 20241021

### Try to verify

$$\textbf{(a)}[A+B,C]=[A,C]+[B,C]$$

------------------------------------------------------------------

$$\begin{aligned}
[A+B,C]& =(A+B)C-C(A+B)  \\
&=AC+BC-CA-CB \\
&=[A,C]+[B,C]
\end{aligned}$$

$$(\mathbf{b})[A,[B,C]]+[B,[C,A]]+[C,[A,B]]=0$$

$$\begin{aligned}
&[A,[B,C]] =[A,(BC-CB)]  \\
&=ABC-ACB-BCA+CBA \\
&[B,[C,A] =[B,(CA-AC)]  \\
&=BCA-BAC-CAB+ACB \\
&[C,[A,B]] =[C,(AB-BA)]  \\
&=CAB-CBA-ABC+BAC
\end{aligned}$$

$$[A,[B,C]]+[B,[C,A]]+[C,[A,B]]=0$$

$$(\mathbf{c})[A,BC]=[A,B]C+B[A,C]$$

$$\begin{aligned}
[A,BC]& =ABC-BCA  \\
&=ABC-BAC+BAC-BCA \\
&=[A,B]C+B[A,C]
\end{aligned}$$

------------------------------------------------------------------

$$(\mathbf{d})[AB,C]=A[B,C]+[A,C]B$$

$$\begin{aligned}
[AB,C]& =ABC-CAB \\
&=ABC-ACB+ACB-CAB \\
&=A[B,C]+[A,C]B
\end{aligned}$$

$$\textbf{(e)}[A,BCD]=[A,B]CD+B[A,C]D+BC[A,D]$$

$$\begin{aligned}
&[A,BCD] =ABCD-BCDA \\
&[A,B]CD =ABCD-BACD \\
&B[A,C]D =BACD-BCAD \\
&BC[A,D] =BCAD-BCDA \\
&[A,BCD] =[A,B]CD+B[A,C]D+BC[A,D] 
\end{aligned}$$
(7.12)

$$\mathbf{f})[ABC,D]=AB[C,D]+A[B,D]C+[A,D]BC$$

(7.13) (7.14) (7.15)
$$\begin{aligned}
&[ABC,D] =ABCD-DABC \\
&AB[C,D] =ABCD-ABDC \\
&A[B,D]C =ABDC-ADBC \\
&[A,D]BC =ADBC-DABC \\
&[ABC,D] =AB[C,D]+A[B,D]C+[A,D]BC 
\end{aligned}$$
(7.16) (7.17)

### 8Homework(8) 20241024

### (1)Consider $\delta$ function potential

$$V(x)=\alpha\delta(x)$$

### work out the reflection coefficient $R$ and transmission coefficient $T$

Notice that ,even if $E<V_{max},T\neq0$

------------------------------------------------------------------

为解决这个问题我们编写了一个 matab 代码（代码见附录4）进行绘制，并通过美化得到以下示例图

![](https://storage.simpletex.cn/view/fREpcWMDloIZgRwsUKgkhCt5c0ImzUzs6)

图6: $\alpha\delta(x)$ 函数势

$$E\psi(x)=-\frac{\hbar^2}{2m}\frac{\partial^2\psi(x)}{\partial x^2}+\alpha\delta(x)\psi(x)$$

从左边进行考虑，可得

$$\left\{\begin{array}{ll}\psi_1(x)=Ae^{ikx}+Be^{-ikx}&,x<0\\\psi_2(x)=Ce^{ikx}&,x>0\end{array}\right.$$

在$x=0$ 处波函数的连续性：

$$\psi(0^-)=\psi(0^+)\quad\Rightarrow\quad A+B=C$$

在$x=0$ 处由于$\delta$ 函数势导致的波函数导数的不连续性：

$$\left.\frac{d\psi}{dx}\right|_{0^+}-\left.\frac{d\psi}{dx}\right|_{0^-}=\frac{2m\alpha}{\hbar^2}\psi(0)$$

------------------------------------------------------------------

$$\left.\frac{d\psi}{dx}\right|_{0^-}=ik(A-B)\\\left.\frac{d\psi}{dx}\right|_{0^+}=ikC$$

$$\begin{aligned}
ikC-ik(A-B)& =\frac{2m\alpha}{\hbar^{2}}(A+B) \\
ik(C-A+B)& =\frac{2m\alpha}{\hbar^{2}}(A+B) \\
\text{B}& =\frac{m\alpha/\hbar^{2}}{ik-m\alpha/\hbar^{2}}A 
\end{aligned}$$

$$\begin{aligned}B&=\frac{m\alpha/\hbar^2}{ik-m\alpha/\hbar^2}A\\C&=\frac{ik}{ik-m\alpha/\hbar^2}A\end{aligned}$$

$$R=\left|\frac{m\alpha/\hbar^2}{ik-m\alpha/\hbar^2}\right|^2=\frac{(m\alpha/\hbar^2)^2}{k^2+(m\alpha/\hbar^2)^2}$$

$$T=\left|\frac{ik}{ik-m\alpha/\hbar^2}\right|^2=\frac{k^2}{k^2+(m\alpha/\hbar^2)^2}$$

$$R+T=1$$

### (2)Consider double delta function potential

$$V(x)=-\alpha\left(\delta(x+a)+\delta(x-a)\right)$$

where $\alpha$ and $a$ are positive and real (a)Sketch the potential

------------------------------------------------------------------

为解决这个问题我们编写了一个matlab代码（代码见附录5）进行绘制，并通过美化得到

![](https://storage.simpletex.cn/view/fzEGQzXGka06QZpmPlg1KdtV65SMvSazc)

图7： $\alpha(\delta(x-a)+\delta(x+a))$ 函数势

(b) Consider a plane wave travel from $-x-axies$ to the $+x-$ acies direction , find out the reflection rate and transition rate### for theregions

$$\begin{aligned}&=Ae^{ikx}+Be^{-ikx},&&-\infty<x<-a,\\&=Ce^{ikx}+De^{-ikx},&&-a<x<a,\\&=Fe^{-ikx},&&a<x<\infty.\end{aligned}$$

于是

$$\begin{aligned}&Ae^{-ika}+Be^{ika}=Ce^{-ika}+De^{ika},\\&Ce^{ika}+De^{-ika}=Fe^{ika},\end{aligned}$$

$$(Ae^{-ika}-Be^{ika})-(Ce^{-ika}-De^{ika})=\frac{2m\alpha}{ik\hbar^{2}}\left(Ce^{-ika}+De^{ika}\right),\\(Ce^{ika}-De^{-ika})-Fe^{ika}=\frac{2m\alpha}{ik\hbar^{2}}Fe^{ika}.$$

------------------------------------------------------------------

令$\beta=2m\alpha/k\hbar^{2}$

$$\left(\begin{array}{c}A\\B\end{array}\right)=\left(\begin{array}{cc}1+\beta/2&(\beta/2)e^{i2ka}\\-(\beta/2)e^{-i2ka}&1-\beta/2\end{array}\right)\left(\begin{array}{c}C\\D\end{array}\right)$$

$$\left(\begin{array}{c}C\\D\end{array}\right)=\left(\begin{array}{cc}1+\beta/2&0\\-(\beta/2)e^{i2ka}&0\end{array}\right)\left(\begin{array}{c}F\\0\end{array}\right)$$

$$\left(\begin{array}{c}A\\B\end{array}\right)=\left(\begin{array}{cc}1+\beta/2&(\beta/2)e^{i2ka}\\-(\beta/2)e^{-i2ka}&1-\beta/2\end{array}\right)\left(\begin{array}{c}(1+\beta/2)F\\-(\beta/2)e^{i2ka}F\end{array}\right)$$

于是在$-\infty<x<-a$ 时，

$$|\frac{B}{A}|^2=R_1=\frac{\beta^2\left[(1+\frac{\beta}{2})^2+(1-\frac{\beta}{2})^2+2(1-\frac{\beta}{2})(1+\frac{\beta}{2})\:cos(3ka)\right]}{4\left[\left(1+\frac{\beta}{2}\right)^4-\left(\frac{\beta}{4}\right)^4-2\left(1+\frac{\beta}{2}\right)^2\left(\frac{\beta}{4}\right)^2cos(4ka)\right]}$$

于是在$-a<x<a$ 时

$$T_1=\left|\frac{C}{A}\right|^2=\frac{\left(\frac{\beta}{2}+1\right)^2}{\left(1+\frac{\beta}{2}\right)^4-\left(\frac{\beta}{4}\right)^4-2\left(1+\frac{\beta}{2}\right)^2\left(\frac{\beta}{4}\right)^2cos(4ka)}$$

$$R_2=\left|\frac{D}{C}\right|^2=\frac{\beta^2}{4\left(\frac{\beta}{2}+1\right)^2}$$

于是在$a<x<\infty$ 时

$$T_2=\left|\frac{E}{C}\right|^2=\frac{1}{\left(\frac{\beta}{2}+1\right)^2}$$

令

$$g=-/\beta=\hbar^2k/2m\alpha,\quad\psi=4ka$$

$$T_\text{总}=\left|\frac{A}{E}\right|^2=\frac{8g^4}{8g^4+4g^2+1+(4g^2-1)\cos\varphi-4g\sin\varphi}$$

(c)How many bound state does it possess? Find out the allowed

------------------------------------------------------------------

# energies for $\alpha=\frac{\hbar^2}{4ma}$ and for $\alpha=\frac{\hbar^2}{ma}$ and Sketch the wave function

$$\left[-\frac{\hbar^2}{2m}\frac{d^2}{dx^2}+V(x)\right]\psi\left(x\right)=E\psi\left(x\right)$$

由于波函数在$x\to\pm\infty$ 时应为有限，可得

$$\begin{aligned}&=Ae^{\kappa x}&&-\infty<x<-a\\&=Be^{\kappa x}+Ce^{-\kappa x}&&-a<x<a\\&=De^{-\kappa x}&&a<x<\infty,\end{aligned}$$

其中， $\kappa\equiv\sqrt{\frac{-2mE}{\hbar^2}}$

$$\begin{aligned}Ae^{-ka}&=Be^{-ka}+e^{ka}\\De^{-ka}&=Be^{ka}+e^{-ka}\end{aligned}$$

当$x=-a$ 时，

$$\int_{-a-\varepsilon}^{-a+\varepsilon}\left[-\frac{\hbar^{2}}{2m}\frac{2}{x^{2}}+V(x)\right]\psi\left(x\right)x=\int_{-a-\varepsilon}^{-a+\varepsilon}E\psi\left(x\right)x,$$

$$-\frac{\hbar^2}{2m}\lim\limits_{\varepsilon\to0}\frac{d\psi}{dx}\bigg|_{-a-\varepsilon}^{-a+\varepsilon}=+\alpha\psi(-a)$$

同理，当$x=a$ 时

$$\left.-\frac{\hbar^2}{2m}\lim\limits_{\varepsilon\to0}\frac{d\psi}{dx}\right|_{+a-\varepsilon}^{+a+\varepsilon}=\alpha\psi\left(a\right)$$

于是

$$\begin{aligned}
kAe^{-ka}-k\left(Be^{-ka}-Ce^{ka}\right)& =\frac{2m\alpha}{\hbar^{2}}Ae^{-ka}  \\
kDe^{-ka}+k\left(Be^{ka}-Ce^{-ka}\right)& =\frac{2m\alpha}{\hbar^{2}}De^{-ka}  \\
Ae^{-ka}& =Be^{-ka}+Ce^{ka}  \\
De^{-ka}& =Be^{ka}+Ce^{-ka} 
\end{aligned}$$

令$\beta\equiv\frac{2m\alpha}{\hbar^{2}k}$ ，整理可得

------------------------------------------------------------------

$$\begin{aligned}
(1-\beta)e^{-ka}A-e^{-ka}B+e^{ka}C+0& =0 \\
0+e^{ka}B-e^{-ka}C+(1-\beta)e^{-ka}D& =0 \\
e^{-ka}A-e^{-ka}B-e^{ka}C+0& =0 \\
0+-e^{ka}B-e^{-ka}C+e^{-ka}D& =0 
\end{aligned}$$

$$\left|\begin{array}{cccc}(1-\beta)e^{-ka}&-e^{-ka}&e^{ka}&0\\0&e^{ka}&-e^{-ka}&(1-\beta)e^{-ka}\\e^{-ka}&-e^{-ka}&-e^{ka}&0\\0&-e^{ka}&-e^{-ka}&e^{-ka}\end{array}\right|=0$$

于是

$$\begin{aligned}4-4\beta+\beta^2\left(1-e^{-4ka}\right)&=0\\\left[\beta e^{-2ka}-(2-\beta)\right]\left[\beta e^{-2ka}+(2-\beta)\right]&=0\end{aligned}$$

对于$\alpha=\frac{\hbar^{2}}{ma}\rightarrow\beta=\frac{2}{ka}$

$$\begin{aligned}e^{(-2\kappa_-a)}&=k_-a-1\\e^{(-2\kappa_+a)}&=1-k_+a\end{aligned}$$

代人编程软件进行计算可得$k\_a=1.108858,k_{+}a=0.796814$ 得到能量

$$E_-=-\frac{\left(1.109\right)^2\hbar^2}{2ma^2}$$

$$E_+=-\frac{\left(0.797\right)^2\hbar^2}{2ma^2}$$

对于$\alpha=\frac{\hbar^{2}}{4ma}\to\beta=\frac{1}{k2a}$

------------------------------------------------------------------

$$\begin{aligned}e^{(-2\kappa_-a)}&=4k_-a-1\\e^{(-2\kappa_+a)}&=1-4k_+a\end{aligned}$$

代人编程软件进行计算可得$k\_a=0.369418,k_{+}a=0.000000$ 得到能量

$$E_-=-\frac{\left(0.369\right)^2\hbar^2}{2ma^2}$$

$$E_+=0(\text{舍去})$$

$$\begin{aligned}
&\text{一} B=(1-\beta/2)A  \\
&C=(\beta/2)\:e^{-2ka}A \\
&\text{1} O=(1-\beta/2)e^{2ka}A+(\beta/2)e^{-2ka}A 
\end{aligned}$$

情况1，当$\alpha=\frac{\hbar^{2}}{ma}\rightarrow\beta=\frac{2}{ka}$ 时， $e^{(-2k_-a)}=k_-a-1$

$$A=D,\quad B=C=\frac{e^{-k_-a}}{e^{k_-a}+e^{-k_-a}}A$$

$$\begin{aligned}&=Ae^{kx}&&-\infty<x<-a\\&=\frac{e^{-k-a}}{e^{k-a}+e^{-k-a}}A\left(e^{kx}+e^{-kx}\right)&&-a<x<a\\&=Ae^{-kx}&&a<x<\infty\end{aligned}$$

归一化可得

$$^{2}\left[\int_{-\infty}^{-a}e^{2k_{-}x}dx+\frac{e^{-2k_{-}a}}{\left(e^{k_{-}a}+e^{-k_{-}a}\right)^{2}}\int_{-a}^{a}\left(e^{\kappa_{-}x}+e^{-k_{-}x}\right)^{2}dx+\int_{a}^{\infty}e^{-2k_{-}x}dx\right]=1$$

$$|A|^2\left[\frac{e^{-2k_-a}}{k_-}+\frac{e^{-2k_-a}}{\left(e^{k_-a}+e^{-k_-a}\right)^2}\left(\frac{e^{2k_-a}}{k_-}+4a-\frac{e^{-2k_-a}}{k_-}\right)\right]=1$$

------------------------------------------------------------------

解得

$$A=\sqrt{\frac{4\left(k_-a+1/2\right)\left(k_-a-1\right)}{k_-\left(k_-a\right)}}$$

情况2，当$\alpha=\frac{\hbar^{2}}{ma}\rightarrow\beta=\frac{2}{ka}$ 时， $e^{(-2k_-a)}=1-k_+a$

$$A=-D,\quad B=-C=-\frac{e^{-k_+a}}{e^{k_+a}-e^{-k_+a}}A$$

$$\begin{aligned}&=Ae^{kx}&&-\infty<x<-a\\&=-\frac{e^{-k_{+}a}}{e^{k_{+}a}-e^{-k_{+}a}}A\left(e^{kx}-e^{-kx}\right)&&-a<x<a\\&=-Ae^{-kx}&&a<x<\infty\end{aligned}$$

归一化可得

=1 (8.63)
$$|A|^{2}\left[\int_{-\infty}^{-a}e^{2k_{+}x}dx+\frac{e^{-2k_{+}a}}{\left(e^{k_{+}a}-e^{-k_{+}a}\right)^{2}}\int_{-a}^{a}\left(e^{k_{+}x}-e^{-k_{+}x}\right)^{2}dx+\int_{a}^{\infty}e^{-2k_{+}x}dx\right]=$$

解得

$$A=\sqrt{\frac{4\left(k_{+}a-1/2\right)\left(1-k_{+}a\right)}{k_{+}\left(k_{+}a\right)}}$$

情况3，当$\alpha=\frac{\hbar^{2}}{4ma}\rightarrow\beta=\frac{1}{2ka}$ 时， $e^{(-2k_-a)}=4k_-a-1$

$$B=C=\frac{4k_-a-1}{4k_-a}A=\frac{e^{-k_-a}}{e^{k_-a}+e^{-k_-a}}A,\quad D=A$$

$$\begin{aligned}&=Ae^{kx}&&-\infty<x<-a\\&=\frac{e^{-k-a}}{e^{k-a}+e^{-k-a}}A\left(e^{kx}+e^{-kx}\right)&&-a<x<a\\&=Ae^{-kx}&&a<x<\infty\end{aligned}$$

归一化解得

$$A=\sqrt{\frac{4\left(k_-a+1/2\right)\left(k_-a-1\right)}{k_-\left(k_-a\right)}}$$

------------------------------------------------------------------

我们编写了一个matlab代码（代码见附录6）和附录7）进行绘制，

![](https://storage.simpletex.cn/view/fMnQzen0Zi79UAz0NlyQl9Rg1mNbHsUEg)

图8：波函数示意图

综上所述，有两个束缚态，一个是偶的，另一个是奇的。

# 9Homework(9) 20241025

为研究透射率与反射率的变化规律，我们编写了一个matlab代码（代码见附录8）进行绘制，我们定义并采用如下参量或常量

<table>
	<tbody>
		<tr>
			<th>参量</th>
			<th>意义</th>
			<th>数值</th>
		</tr>
		<tr>
			<td>$m_{t}$ $'e$</td>
			<td>电子质量(kg)</td>
			<td>$9.10938356\times10^{-31}$</td>
		</tr>
		<tr>
			<td>$m_{p}$</td>
			<td>质子质量(kg)</td>
			<td>$1.6726219\times10^{-27}$</td>
		</tr>
		<tr>
			<td>$m.$ $^{\prime}\alpha$</td>
			<td>$\alpha$粒子质量(kg)</td>
			<td>$6.64465675\times10^{-27}$</td>
		</tr>
		<tr>
			<td>$\hbar$</td>
			<td>约化普朗克常数(J$\cdot s)$</td>
			<td>$1.0545718\times10^{-34}$</td>
		</tr>
		<tr>
			<td>$V$</td>
			<td>势能 (J)</td>
			<td>$1\times10^{-10}$</td>
		</tr>
		<tr>
			<td>$L$</td>
			<td>长度(m)</td>
			<td>$1\times10^{-9}$</td>
		</tr>
		<tr>
			<td>$E$</td>
			<td>能量范围(J)</td>
			<td>$(0.1\times10^{-10},2\times10^{-10}$</td>
		</tr>
	</tbody>
</table>

------------------------------------------------------------------

并采用以下方程进行求解

$$\begin{aligned}
k_{0}& =\:\sqrt{\frac{2mE}{\hbar^{2}}}  \\
k_{v}& =\:\sqrt{\frac{2m(E-V)}{\hbar^{2}}}  \\
\left|\frac{C_r}{A_r}\right|^2& =\frac{16k_{0}^{2}k_{v}^{2}}{16k_{0}^{2}k_{v}^{2}+4(k_{0}^{2}-k_{0}^{2})^{2}\sin^{2}k_{v}L}  \\
\left|\frac{A_{l}}{A_{r}}\right|^{2}& =\frac{(k_{0}^{2}-k_{v}^{2})^{2}4\:sin^{2}\:k_{v}L}{16k_{0}^{2}k_{v}^{2}+4(k_{0}^{2}-k_{v}^{2})^{2}\:sin^{2}\:k_{v}L} 
\end{aligned}$$

![](https://storage.simpletex.cn/view/f5C9wuEpbQcsZuftG7szwK5xuBx5CHZsW)

(b)电子反射率随能量变化示意图

![](https://storage.simpletex.cn/view/fFeXg1T0GniRnGaeGpE7u2gaBSavFO9W6)

(a)电子透射率随能量变化示意图

图9:电子透射率、反射率随能量变化示意图

![](https://storage.simpletex.cn/view/fuhA9v3YEyHDFuwlDnoI8LEiv9VIFypSo)

(a)质子透射率随能量变化示意图

![](https://storage.simpletex.cn/view/fArlsAzUxkmLGgBhHV6rHXdZK9mnUdEnG)

(b)质子反射率随能量变化示意图

图10:质子透射率、反射率随能量变化示意图

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fg47ZH2opzoMFAKVrnn0RYi963TwRCgkK)

![](https://storage.simpletex.cn/view/fNOYSfKoRssnQAEGL37R04PkEn7SW7nYK)

(a) $\alpha$ 粒子透射率随能量变化示意图

(b) $\alpha$ 反射率随能量变化示意图

图11： $\alpha$ 透射率、反射率随能量变化示意图

通过调整能量范围我们可以得到电子、质子、 $\alpha$ 粒子的反射率随着能量的增加，虽然有所波动，但在总体趋势上是减小的，透射率随着能量的增加，虽然有所波动，但在总体趋势上是增大的，而且我们可以发现在$E=[V,V+\varepsilon]$ 很小的一段区间，三种粒子的透射率较大，反射率较小，当我们对能量范围进行调整，我们可以发现，当E远大于V时，粒子的透射率趋近于1，当E小于或等于$V$ 时，粒子的反射率趋近于1。

为研究质量是否对反射率与透射率有较大影响，我们编写了一个matlab代码（代码见附录9）进行绘制，我们令$E$ = $2\times$ $10^{- 10}, V$ = $1\times$ $10^{- 10}$, .并设置质量范围分别为$(0.5\times$ $9.10938356\times10^{-31},2\times9.10938356\times10^{-31})$ 、 $(0.5\times1.4\times10^{-10},2\times1.6\times10^{-10})$ 、 $(0.5\times$ $1.4\times10^{10},2\times1.6^{\times}1010)$ ，可以得到

![](https://storage.simpletex.cn/view/fbiX7ymFrT7XBzr8UdKz5KeyvRuHBvZgt)

![](https://storage.simpletex.cn/view/fva3X0YvfSZXOQFLaFiDDGzGoGcRqeh1S)

(a)透射率随质量变化示意图

(b）反射率随能量变化示意图

图12:透射率、反射率随质量变化示意图$((\times10^{-31})$ ）

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fccNQsRNAfnRnnmgrS26AsF07TSmd86C5)

(b）反射率随能量变化示意图

![](https://storage.simpletex.cn/view/f7azQsWhfHkLXBgyEyg3KV7QGwQ60dNe6)

(a)透射率随质量变化示意图

图13:透射率、反射率随质量变化示意图$(\times10^{-10}$

![](https://storage.simpletex.cn/view/fzevxkGyQeefs6agyoMdp19EU7LmZxZ5u)

![](https://storage.simpletex.cn/view/f8GL6zoH55yuh838BXY2XuGZeWclUAoCF)

(a)透射率随质量变化示意图

(b）反射率随能量变化示意图

图14:透射率、反射率随质量变化示意图$(\times10^{10}$

通过上面几组图像，我们可以得知，在能量和势能不变的情况下，即使质量的变化会使反射率与折射率的数值有所波动，但仍然保持在一个固定的范围内，以以上几组图像为例，质量的变化，总体上使保持透射率在$12\%$ 以下，而反射率保持在$88\%$ 以上，这说明粒子质量的变化不会使透射率与折射率有太大的变化。

为研究$\delta$ 势阱的长度是否对反射率与透射率有较大影响，由于编程软件无法直接绘制宽度为0的图像，我们采用$L$ 趋近于0进行近似，我们编写了一个matlab代码（代码见附录10）进行绘制由于在上文的研究中我们研究了能量的变化对透射率与反射率的影响，故在这部分我们设置固定的能量与势能， $E=1.5\times10^{-16},V=1\times10^{-18}$ $V=1\times10^{-18}$ V = 1 x 10-18 ，并设置长度范围为
$$(0.5\times10^{-9},5\times10^{-9}),\:(0.5\times10^{-19},5\times10^{-19}),\:(0.5\times10^{-31},5\times10^{-31})。$$

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fvuAp9nWgb8nx3L256VHXfOAqGGa88kgG)

(b)反射率随长度变化示意图

![](https://storage.simpletex.cn/view/fIeZDGZuSfWWFMnuqfXFWPxDPnMk7QZvH)

(a)透射率随长度变化示意图

图15:透射率、反射率随长度变化示意图$(\times10^{-9}$

![](https://storage.simpletex.cn/view/fgtv2lAAyez6iBacUYCu1wuqybrTNgF0F)

(a)透射率随长度变化示意图

![](https://storage.simpletex.cn/view/fR0CM6qBEp6ePvn0sZV2H0ZawDltXhM9S)

(b)反射率随长度变化示意图

图16:透射率、反射率随长度变化示意图$(\times10^{-19}$

![](https://storage.simpletex.cn/view/fGXwTrs6tse9IPvt48Eqawk78MvK0Swgh)

![](https://storage.simpletex.cn/view/fpy9kaXuQIGgFpBkSd20OdlMysADfRgbh)

(a)透射率随长度变化示意图

(b)反射率随长度变化示意图

图17:透射率、反射率随长度变化示意图$(\times10^{-31}$ )

通过上面几组图像，我们可以得知，在能量和势能不变的情况下，即使长度的量级在$\times10^{-9}$ ）时，长度的变化会使反射率与折射率的数值有所波动，但透射率的量级在$\times10^{-5}$ )，

------------------------------------------------------------------

趋近于0，反射率虽然有所波动，但趋近于1，而长度量级在$\times10^{-19}$ )和$\times10^{-31}$ )时，透射率的量级进一步减小，虽然整体上看与长度呈现正相关的关系，但数值几平可认为为0，而反射率的数值几乎等于1，这说明势阱长度的越小会使透射率越，无限趋近于0，使折射率无限趋近于1。

现在我们考虑一个特殊情况，来“解答”人为什么不能穿墙，我们假设在穿墙的过程中， 墙不会被破坏，现在我们在附录8代码的基础上进行修改，由于编程软件的限制，我们无法能量设置为无穷大，这部分我们设置固定的能量与势能， $E=1.5\times10^{50},V=1\times10^{-18}$ ， 令质量为$m=9.10938356\times10^{31}$ 并设置长度范围为(0.5,5)。

![](https://storage.simpletex.cn/view/fNMGpDFYRInQd7Q5GGR25mnKr2rsnkARz)

图18:透射率、反射率随长度变化示意图$E=1.5\times10^{50}$

从上图可以看出即使能量远大于势能，物体质量较大的情况下，对于一堵长度范围为$(0.5m,5m)$ 的墙，物体的穿透率几乎为0，物体的反射率几乎为1，可见人穿墙的几率是非常小的，穿墙概率几乎为0。

综上所述，其他因素不变的情况下，能量越大，透射率越大，反射率越小，其他因素不变的情况下，质量对透射率与反射率没有太大的影响，在其他因素不变的情况下，势阱的长度越小，透射率越低，趋近于0，反射率越高，趋近于1，此外，即使能量远大于势能， 物体质量较大的情况下，物体穿透对于一堵长度范围为$(0.5m,5m)$ 的墙，物体的穿透率几乎为0，物体的反射率几乎为1。

以上研究基于matlab 编程进行开展，难免会有没有考虑到的地方，考虑的情况也比较理想，以上结论仅仅代表作者个人观点，无任何学术权威性，本文的观点仅为抛砖引玉，如若想要探讨这方面的问题，还望参考更加权威的学术期刊，如若本文有不恰当的观点，还望读者能够对此进行指正。

------------------------------------------------------------------

# 10Homework(10) 20241031

为研究透射率与反射率在一维有限势阱的变化规律，我们编写了一个matlab代码（代码见附录11）进行绘制，我们定义并采用如下参量或常量

<table>
	<tbody>
		<tr>
			<th>参量</th>
			<th>意义</th>
			<th>数值</th>
		</tr>
		<tr>
			<td>$m.$ e</td>
			<td>电子质量(kg)</td>
			<td>$9.11\times10^{-31}$</td>
		</tr>
		<tr>
			<td>$\hbar$</td>
			<td>约化普朗克常数(J$\cdot s)$</td>
			<td>$1.0545718\times10^{-34}$</td>
		</tr>
		<tr>
			<td>$V$</td>
			<td>势能 (J)</td>
			<td>$1.60218\times10^{-19}$</td>
		</tr>
		<tr>
			<td>$L$</td>
			<td>长度(m)</td>
			<td>$1\times10^{-9}$</td>
		</tr>
		<tr>
			<td>$E$</td>
			<td>能量范围(J)</td>
			<td>$(0,V)$</td>
		</tr>
	</tbody>
</table>

并采用以下方程进行求解

$$\begin{aligned}&=\frac{4k_{0}^{2}k_{v}^{2}}{4k_{0}^{2}k_{v}^{2}+(k_{0}^{2}+k_{v}^{2})^{2}\:sinh^{2}\:k_{v}L}&&E<V\\&=\frac{4}{4+k_{0}^{2}L}&&E=V\\&=\frac{16k_{0}^{2}k_{v}^{2}}{16k_{0}^{2}k_{v}^{2}+4(k_{0}^{2}-k_{v}^{2})^{2}\:sin^{2}k_{v}L}&&E>V\end{aligned}$$

其中， $k_{v}=$ $\sqrt {\frac {2m| E- V| }{\hbar ^{2}}}, k_{0}=$ $\sqrt {\frac {2mE}{\hbar ^{2}}}$

![](https://storage.simpletex.cn/view/fg0wFXpKpc2ta0mUaHG9kwkpMEfWiDikQ)

![](https://storage.simpletex.cn/view/fg2plWCyFsZSMLG4wf5Aplq8KGUQ7r5Xm)

(a)透射率随能量变化示意图(完整范围)

(b)反射率随能量变化示意图(完整范围)

图19:透射率、反射率随能量变化示意图(完整范围)

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fdVX48I4EqKwHBiMGcAlvgvVXFOAcNdww)
(b)透射率随能量变化示意图$(E>V$

![](https://storage.simpletex.cn/view/f9e6rHODkcWEIilNtpZK0DwIZ4IGul1w7)
(a)透射率随能量变化示意图(E< V,

图20:透射率随能量变化示意图

![](https://storage.simpletex.cn/view/fGBtTx9Z5rZa002cP7O81qOzlFi4pSq5e)
(a) 反射率随能量变化示意图(E< V)

![](https://storage.simpletex.cn/view/fUk4YGySy5eugkTw2Sd3nmxlgXngKTHEV)

(b)反射率随能量变化示意图(E>V

图21:反射率随能量变化示意图

在能量小于势垒高度(E< V) 的情况下： (a)人射粒子的透射率呈现出峰值的形状，随着能量的增加而先增加后减少。这是由于

量子隧穿效应导致的。(b)人射粒子的反射率则是随着能量的增加而先减少后增加。

在能量大于势垒高度(E> V) 的情况下：

(a)人射粒子的透射率随着能量的增加而逐渐减小。这是因为量子隧穿效应在高能量下

变得不太明显。(b)人射粒子的反射率则随着能量的增加而逐渐增大。

现在，我们仍然采用以上的参数与条件，我们对$E<V$ 的情况进行处理（代码见附录12)，

由于

------------------------------------------------------------------

$$\begin{aligned}
sin\:h^{2}kvL& =(\frac{e^{k_{v}L}-e^{-k_{v}L}}{2})^{2}  \\
&=\frac{1}{4}[e^{2k_{v}L}-2+e^{-2k_{v}L}] \\
&\cong\frac{1}{4}e^{2k_{v}L} \\
&=\frac{1}{4}e^{\sqrt{8m(V-E)}\frac{L}{\hbar}}
\end{aligned}$$

于是

$$T\cong\frac{1}{1+\frac{1}{16}\frac{V^2}{E(V-E)}e^{\sqrt{8m(V-E)}\frac{L}{\hbar}}}$$

并计算其误差

$$error=|T_{exact}-T_{approx}|$$

![](https://storage.simpletex.cn/view/fWWDpbA5Z3Vga1WGunmrGxgfb28rwkMwk)

(a)近似透射率随能量变化示意图(E< V)

![](https://storage.simpletex.cn/view/fiai1mt0Ru3gpvq3rViYX9yMOGmzx1umE)

(b)精确透射率随能量变化示意图(E< V,

图22:近似、精确透射率随能量变化示意图(E< V)

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/ffa2Dxbchw7aS9onOTA22DIVEP5naEhta)

![](https://storage.simpletex.cn/view/fgNd3YxGiumy18F8zMNhU8EksO4gyrx2Z)

(a)透射率随能量变化对比示意图(E< V)

(b)透射率随能量变化误差示意图(E< V,

图23：近似、精确透射率随能量对比及误差变化示意图(E< V)

通过上面几组图像，我们可以得知，在忽略高阶小量的情况下，透射率随能量变化在能量小于势能的情况下，差别不大，误差趋近于0，在能量与势能相接近的情况下，精确透射率与近似透射率的差别较为明显，但误差小于0.07，说明高阶小量对透射率的影响不大。

现在，我们仍然保持以上条件，我们对$T\cong\frac{1}{1+\frac{1}{16}\frac{V^{2}}{E(V-E)}e^{\sqrt{8m(V-E)}\frac{L}{\hbar}}}$ 进行级数展开（代码见附录13)， 令

$$x=16\frac{E(V-E)}{V^2}e^{-\sqrt{8m(V-E)\frac{L}{\hbar}}}$$

由于

$$\begin{aligned}\frac{1}{1+\frac{1}{x}}=\frac{x}{1+x}=\sum_{n=0}^{\infty}(-1)^nx^{n+1}\end{aligned}$$

进行级数展开，分别展开到第一项、第二项、第三项

$$\begin{gathered}
T\cong16{\frac{E(V-E)}{V^{2}}}e^{-{\sqrt{8m(V-E)}}{\frac{L}{\hbar}}} \\
T\cong16{\frac{E(V-E)}{V^{2}}}e^{-{\sqrt{8m(V-E)}}{\frac{L}{\hbar}}} \\
-(16\frac{E(V-E)}{V^{2}}e^{-\sqrt{8m(V-E)}\frac{L}{\hbar}})^{2} \\
T\cong16{\frac{E(V-E)}{V^{2}}}e^{-{\sqrt{8m(V-E)}}{\frac{L}{\hbar}}} \\
-\:(16\frac{E(V-E)}{V^{2}}e^{-\:\sqrt{8m(V-E)}\frac{L}{\hbar}})^{2} \\
+(16\frac{E(V-E)}{V^{2}}e^{-\sqrt{8m(V-E)}\frac{L}{\hbar}})^{3} 
\end{gathered}$$

------------------------------------------------------------------

并计算其误差

$$error=|T_{exact}-T_{approx}|$$

![](https://storage.simpletex.cn/view/femn7lgvYKCS4eIOZx1VIxkzl1ZoFalsK)

(a)透射率随能量变化对比（级数展开） 小透图(E< V) 能量变化误差（级数展开

示意图(E< V)

图24:近似、精确透射率随能量对比及误差变化（级数展开）示意图(E< V)

通过上面几组图像，我们可以得知，在保留第一项、前两项、前三项的情况下，透射率随能量变化在能量小于势能的情况下，差别不大，三条曲线非常接近，误差趋近于0，在能量与势能相接近的情况下，保留第一项与保留前两项、前三项的差别较为明显，但整体相差较小，保留前两项与保留前三项几乎没有区别，在进行级数展开后，三条曲线与精确透射率的误差均小于0.07，因此，为方便研究我们只需将级数展开到第一项。

为研究一维有限势阱的长度是否对反射率与透射率有较大影响，我们编写了一个matlab 代码（代码见附录14）进行绘制由于在上文的研究中我们研究了能量的变化对透射率与反射率的影响，故在这部分我们设置固定的能量与势能， $E=0.5ev,V=1ev$, 并设置长度范围为$(0.1\times10^{-9},5\times10^{-9})$ ， $(0.1\times10^{-19},5\times10^{-19})$ ， $(0.1\times10^{9},5\times10^{9})$

![](https://storage.simpletex.cn/view/fZHD5FOIoYy1DqvXUmUGRQYSr1ENIrpmG)

图25:透射率、反射率随长度变化示意图( $\times10^{-9}$ ）

------------------------------------------------------------------

![](https://storage.simpletex.cn/view/fEUGxphohe9Asnu27eDQiCiG1BQGUE1Wz)

(选达率随长度变化透谢率、反射率随长度变化示意围$(\times10^{-19}$ 度

![](https://storage.simpletex.cn/view/f2R6z2OFzdxoU4sr4ZPggnCGu6bhYdVVG)

(b)反射率随长度变化示意图

![](https://storage.simpletex.cn/view/fgGDuNSlSNGUwEyUttCgqxdCuab00gA8r)

![](https://storage.simpletex.cn/view/fY16l3yXog0Rq0ARur79EMHKDEi9lcfBa)

（a）透射率随长度变化示意图图271:透射率、反射率随长度变化示意图$(\times10^9$

(b）反射率随长度变化示意图

通过上面几组图像，我们可以得知，在其他因素不变的情况下，透射率随着长度的增加而减小，反射率随着长度的增加而增加。以上研究基于matlab 编程进行开展，难免会有没有考虑到的地方，考虑的情况也比较

理想，以上结论仅仅代表作者个人观点，无任何学术权威性，本文的观点仅为抛砖引玉，如若想要探讨这方面的问题，还望参考更加权威的学术期刊，如若本文有不恰当的观点，还望读者能够对此进行指正。

------------------------------------------------------------------

## 附录

### 支撑材料

<table>
	<tbody>
		<tr>
			<th>文件</th>
			<th>作用</th>
		</tr>
		<tr>
			<td>homework20241011.m</td>
			<td>附录 2matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241014.m</td>
			<td>附录 3matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241024a.m</td>
			<td>附录 4matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241024b.m</td>
			<td>附录 5matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241024c.m</td>
			<td>附录 6matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241024d.m</td>
			<td>附录 7matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241025a.m</td>
			<td>附录 8matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241025b.m</td>
			<td>附录 9matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241025c.m</td>
			<td>附录 10matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241031a.m</td>
			<td>附录 11matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241031b. m</td>
			<td>附录 12matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241031c.m</td>
			<td>附录 13matlab 源代码</td>
		</tr>
		<tr>
			<td>homework20241031d.m</td>
			<td>:14matlab 源代码 价示</td>
		</tr>
	</tbody>
</table>

### 附录2

### homework20241011.m

介绍：用于绘制Homework(4)20241011的问题(2)的第(d)小问

![](https://storage.simpletex.cn/view/fqeprF4Ps1lSHNoHIKRuPFfs1hIqEGTgz)

------------------------------------------------------------------

11
$$\mathrm{phi1}\:=\:\mathrm{sqrt}\:(2/\mathrm{L})\:*\:\mathrm{sin}\:(2\:*\:\mathrm{n}1\:*\:\mathrm{pi}\:*\:\mathrm{x}\:/\:\mathrm{L})\:;\\\mathrm{phi2}\:=\:\mathrm{sqrt}\:(2/\mathrm{L})\:*\:\mathrm{sin}\:(2\:*\:\mathrm{n}2\:*\:\mathrm{pi}\:*\:\mathrm{x}\:/\:\mathrm{L})\:;\\\mathrm{phi3}\:=\:\mathrm{sqrt}\:(2/\mathrm{L})\:*\:\mathrm{sin}\:(2\:*\:\mathrm{n}3\:*\:\mathrm{pi}\:*\:\mathrm{x}\:/\:\mathrm{L})\:;$$
1213

14 $\%$ 设置图像属性

15 lineWidth =2.5

16 fontSize =14

17markerSize =8 ：

1s markerEdgeWidth =1.5 ； $\%$ 标记边框宽度

19

20 $\%$ 标记点21 markerIndices = 1:50:length(x); $\%$ 增加标记点的数量2223 $\%$ 绘制图像n=1

24 figure;

25 plot(x, phil, 'b-','LineWidth', lineWidth); 26hold on

27plot (x(markerIndices), phi1(markerIndices),'bo','MarkerSize' markerSize ,'MarkerFaceColor', 'b', 'MarkerEdgeColor', 'k', LineWidth', markerEdgeWidth);

title('Wave Function \phi_1(x) for. n=1 ,'FontSize',fontSize,. 'Interpreter', 'none');.

xlabel('x', 'FontSize', fontSize, 'Interpreter', 'none');.

ylabel('phi_1(x)', 'FontSize', fontSize, 'Interpreter', 'none )；

31 grid on;

32xlim[-L/2L/2] 33ylim[-1.51.5];

34 setgca,'FontSize',fontSize

35

36 $\%$ 绘制图像n=2

37 figure;

3s plot(x,phi2,'r-','LineWidth',lineWidth); hold on;

plot(x(markerIndices) phi2(markerIndices),'rs','MarkerSize' markerSize, 'MarkerFaceColor', 'r', 'MarkerEdgeColor', 'k', LineWidth', markerEdgeWidth);

------------------------------------------------------------------

title('Wave Function \phi_2(x) for n=2 ,'FontSize',fontSize,. 'Interpreter', 'none');

2 xlabel('x', 'FontSize', fontSize, 'Interpreter', 'none');

43 ylabel('phi_2(x)', 'FontSize', fontSize, 'Interpreter', 'none )；

44grid on;

45xlim[-L/2L/2] 46 ylim ([-1.5，1.5]);

47 set(gca,'FontSize', fontSize)

49 $\%$ 绘制图像n=3

so figure ; 5 plot(x, phi3,'g-','LineWidth', lineWidth); s2 hold on;

53 plot(x(markerIndices), phi3(markerIndices),'g^','MarkerSize' markerSize, 'MarkerFaceColor', 'g', 'MarkerEdgeColor', 'k', LineWidth', markerEdgeWidth);

title('Wave Function \phi_3(x) for. n= 3 ,'FontSize',fontSize, 'Interpreter', 'none');

xlabel('x', 'FontSize', fontSize, 'Interpreter', 'none');.

ylabel('phi_3(x)', 'FontSize', fontSize, 'Interpreter', 'none' ）；

s7grid on;

58xlim[-L/2L/2]

59ylim[-1.51.5];

60 set(gca,'FontSize',fontSize).

# 附录3

### homework20241014.m

## 介绍：用于绘制Homework(5)20241014的第（c)小问

，%定义Hermite多项式2 H1 $=@($y) $2^*$y ： H2=@y4*y.^2-2

------------------------------------------------------------------

$$\begin{aligned}&\mathrm{H3}\:=\:@(\:\mathrm{y}\:)\:8^{*}\mathrm{y}\:.\:\uparrow3\:-\:12^{*}\mathrm{y}\:;\\&\mathrm{H4}\:=\:@(\:\mathrm{y}\:)\:16^{*}\:\mathrm{y}\:.\:\uparrow4\:-\:48^{*}\:\mathrm{y}\:.\:\uparrow2\:+\:12\:;\\&\mathrm{H5}\:=\:@(\:\mathrm{y}\:)\:32^{*}\:\mathrm{y}\:.\:\uparrow5\:-\:160^{*}\:\mathrm{y}\:.\:\uparrow3\:+\:120^{*}\:\mathrm{y}\:;\\&\mathrm{H6}\:=\:@(\:\mathrm{y}\:)\:64^{*}\:\mathrm{y}\:.\:\uparrow6\:-\:480^{*}\:\mathrm{y}\:.\:\uparrow4\:+\:720^{*}\:\mathrm{y}\:.\:\uparrow\end{aligned}$$

9 $\%$ 生成 y的值

10 $y$ = linspace(-3,3,400) 1112 $\%$ 设置图形属性13lineWidth =3 ： $\%$ 增加线条宽度14fontSize =1415 xLimits = = = [ -3 .5 , 3 .5 ] ： 1yLimitsCommon = [-150,150] $\%$ 通用y轴范围1718 $\%$ 单独绘制HO

figure;

19

20 plot(y,ones(size(y)),'b-,'LineWidth', lineWidth);

title ( $^{\prime }$H$\_$0( y) = 1 ','FontSize', fontSize); xlabel('y','FontSize', fontSize);

212223 ylabel('H_0(y)','FontSize',fontSize); 24 xlimxLimits; 25ylim[-22]) $\%$ 对H_0单独调整y轴范围

26 grid on; 27 set(gca,'FontSize', fontSize);

2829 $\%$ 打开其他图窗口并绘制每个多项式30figure: 3 ploty,H1y'b-,'LineWidth'lineWidth); 32 title('H_1(y)','FontSize',fontSize); 33 xlabel('y','FontSize', fontSize); 34 ylabel('H_1(y)','FontSize', fontSize); 35xlimxLimits 3 ylim[-1010] $\%$ 对H_1单独调整y轴范围37grid on; 3s set(gca, 'FontSize', fontSize) 39 figure ;

------------------------------------------------------------------

4ploty,H2y'b-'LineWidth'lineWidth); 4 title('H_2(y),'FontSize',fontSize); 4 xlabel('y','FontSize', fontSize); 44 ylabel('H_2(y)','FontSize', fontSize); 45xlimxLimits; 46ylim[-2020] $\%$ 对H_2单独调整y轴范围47grid on; 4s set(gca,'FontSize',fontSize) 49

# so figure;

51ploty,H3y'b-','LineWidth'lineWidth); 52 title('H_3(y),'FontSize',fontSize); 53 xlabel('y','FontSize', fontSize) 54 ylabel('H_3(y)','FontSize', fontSize) 55xlimxLimits 56ylim-5050] $\%$ 对H_3单独调整y轴范围s7 grid on; s set(gca,'FontSize', fontSize); 59

## figure ;

61 plot(y,H4(y),'b-','LineWidth',lineWidth); 62 title('H_4(y)','FontSize', fontSize); 63 xlabel('y','FontSize', fontSize); 64 ylabel('H_4(y)','FontSize', fontSize); 65xlimxLimits; 66ylim[-100100] $\%$ 对H_4单独调整y轴范围67grid on; 6s set(gca, 'FontSize', fontSize) 69

# o figure;

7 plot(y,H5(y)'b-','LineWidth',lineWidth); 72 title('H_5(y)','FontSize',fontSize); 73 xlabel('y','FontSize', fontSize); 74 ylabel('H 5(y)','FontSize', fontSize) 75xlimxLimits; 76ylim (yLimitsCommon) 77grid on;

------------------------------------------------------------------

set(gca,'FontSize', fontSize);.

figure ;

title('H_6(y)','FontSize', fontSize);

s xlabel('y','FontSize',fontSize):

s1 plot(y,H6(y),'b-','LineWidth',lineWidth); 8284 ylabel('H_6(y)','FontSize', fontSize) 85xlimxLimits; 86ylim(yLimitsCommon); 87 grid on ss set(gca,'FontSize',fontSize);

# 附录4

## homework20241024a.m

介绍：用于绘制Homework(8)20241024的第1题的示例图像

1 $\%$ 定义X轴上的点2 x= linspace(-1,1,1000);

4 $\operatorname{sigma}=0.01$ ： $\%$ 高斯函数的标准差5 delta_approx = = =(1/ sigma*sqrt2*pi*exp-x.^2/2 * sigma ～2)); 7%绘制图像figure; 9 plotx,delta_approx,'LineWidth',2); 10 xlabel('x','Interpreter','latex');. ylabel('y', 'Interpreter','latex'); 12title（’\delta函数势’，'Interpreter’，*tex’）； 13 grid on;

------------------------------------------------------------------

# 附录5

## homework20241024b.m

# 介绍：用于绘制Homework(8)20241024的第2题的第（a)小问

1 $\%$ 定义X轴上的点2 x= linspace(-2,2,1000); 4 $\%$ 定义一个很窄的高斯函数来近似函数5sigma = 0.02; $\%$ 高斯函数的标准差7 $\%$ 定义（x－a）和( x + a ) 的位置8 a =0.510 $\%$ 近似（x－a）和( x + a ) 的高斯函数delta_x_a =- 1/sigma*sqrt2*pi* exp-x-a.^2/ (2 * sigma~$^{\sim}2))$ ： 12 delta_x_neg_a = -(1/(sigma *sqrt(2 *pi))）*exp（-(x + a）. 2 / $( 2\:^{* }$ sigma~~2)) ； 1314 $\%$
$$\begin{aligned}&\text{计算 (x - a) + (x + a)}\\&\mathrm{lta_sum~=~delta_x_a~+~delta_x_neg_a~;}\end{aligned}$$
151617%创建图像is figure; 1920 $\%$ 绘制(x- a) + ( x + a ) (x+a) ( x + a ) 的近似图像2 plot(x, delta_sum,'LineWidth',2); 2 xlabel('x', 'Interpreter','latex'); 2 ylabel('y', 'Interpreter', 'latex'); 24 title('\delta(x - a) + \delta (х+а) 函数势’，‘Interpreter’， tex'); 25 grid on;

------------------------------------------------------------------

# 附录6

## homework20241024c.m

## 介绍：用于绘制Homework(8)20241024的第2题的第（c)小问的情况1

1 $\%$ 定义常量

2hbar = 1.0545718e-34; $\%$ 普朗克常数的约简形式（单位： $J^{*}S$ 3 m=9.10938356e-31 ： $\%$ 电子质量（单位：kg) 4 a =2 ： $\%$ 位宽（单位：m)，根据具体问题调整sk_minus=0.55456k_plus = 0.3985

# 8 $\%$ 计算归－化常数A

9 $A=$ sqrt(4 *(k_minus *a + 1/2*(k_minus *a-1)/ k_minus*k_minus*a

11 $\%$ 定义区域

12 xl = linspace $(-5^*$a -a10013 x2 = linspace-a,a, 100); 14 x3 = linspace(a,5*a,100)

15

16 $\%$ 定义波函数

17psil =A * exp(k_minus *xl); 1s psi2=exp-k_minus *a/expk_minus *a+ exp-k_minus * a*A*expk_minus *x2+exp-k_minus*x219 psi3=A* exp-k_minus *x3

20

21%绘图

22 figure;

23hold on;

24 plotx1psil,'b','LineWidth',2;

25 plotx2,psi2,'r,'LineWidth'2);

26 plotx3psi3,'g'LineWidth2;

27 xline(-a,'--k','LineWidth', 1.5); $\%$ 标记$x=-a$

2s xline(a,'--k','LineWidth', 1.5); $\%$ 标记x= a 29hold off

------------------------------------------------------------------

31 $\%$ 设置图形属性

32 xlabel(*x*); 3 ylabel('\psi(x)'); 34 title'Wave Function \psi(x)' 35legend{'\psi_1x)'\psi_2x)''\psi_3x'x=-a''x=a $^{,}\}$ ,'Location', 'best'); grid on;

# 附录7

## homework20241024d.m

## 介绍：用于绘制Homework(8)20241024的第2题的第（c)小问的情况2

1 $\%$ 定义常量

2hbar =1.0545718e-34 ； $\%$ 普朗克常数的约简形式（单位： $J^{*}S$ 3 ${\mathrm{m}}=9.10938356$e-31 : $\%$ 电子质量（单位：kg) 4 a =1 ； $\%$ 位宽（单位：m)，根据具体问题调整s k_minus =1.1096k_plus = 0.7977 k = $k_{- }$plus ：

9 $\%$ 计算归一化常数A

10A=-sqrt4*k_plus *a-1/2*1-k_plus*a/k_plus *(k_plus *a)));

11

12 $\%$ 定义区域

13 xl = linspace $(-5^*$a -a50014 x2 = linspace-a,a,500); 15 x3 = linspace(a,5*a,500)

16

17 $\%$ 定义波函数

18 psil $=\mathrm{A}^{*}$ exp$(\mathrm{k}^{*}$ x1) 19psi2 = -exp-k_plus *a/expk_plus*a-exp-k_plus *a )*A*expk*x2-exp-k*x2 psi3 =-A*exp（-k *x3）；

------------------------------------------------------------------

21

22%绘图

24hold on; 25 plot(x1,psil,'b,'LineWidth',2); 26 plot(x2, psi2,'r','LineWidth',2); 27 plot(x3,psi3,'g''LineWidth',2); 2s xline-a,'--k','LineWidth',1.5); $\%$ 标记x $=-a$ 29 xline(a,'--k','LineWidth', 1.5); $\%$ 标记x= a 30hold off;

23 figure; 3132%设置图形属性3 xlabel(*x*); 34 ylabel('\psi(x)'); 35 title('Wave Function \psi(x)'); 36legend{'\psi_1x'\psi_2x)'\psi_3x'x=-a''x=a '}, 'Location', 'best');. grid on;

# 附录8

## homework20241025a.m

介绍：用于绘制Homework(9)20241025反射率、透射率随能量变化

，%定义常量

%电子质量（kg) 2 m$\_$e= 9. 10938356e- 31 $\%$ 质子质量 (kg) 3 m$\_$p= 1. 6726219e- 274m_alpha=6.64465675e-27;%粒子质量（kg） 5hbar=1.0545718e-34 %约化普朗克常数(J$\cdot$s) 6 V= 1e- 18 : %势能 (J) %长度 (m) 7 L=1e-9 : 9 $\%$ 定义能量范围 (J)

10 $E=$ linspace(0.1e-18, 2e-18, 1000)

11

------------------------------------------------------------------

$$\begin{aligned}
&\mathrm{k0_e~=~sqrt~(2~*~m_e~*~E~/~hbar~2)~;} \\
&\mathrm{kv_e~=~sqrt~(2~*~m_e~*~(E~-~V)~/~hbar~2)~;} \\
&\mathrm{k0_p~=~sqrt~(2~*~m_p~*~E~/~hbar~2)~;} \\
&\mathrm{kv_p~=~sqrt~(2~*~m_p~*~(E~-~V)~/~hbar~2)~;} \\
&\mathrm{k0_alpha~=~sqrt~(2~*~m_alpha~*~E~/~hbar~2)}
\end{aligned}$$

131415161718

19

20 $\%$ 计算反射率和透射率
$$\begin{aligned}
&\mathrm{T}_{-}\mathrm{e} \\
&\begin{array}{ccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccc}\end{array} \\
&\text{:} \mathrm{R_e}\:=\:1\:-\:\mathrm{T_e}\:; \\
&\text{:} \\
&\begin{array}{ccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccc}\end{array} \\
&\text{.} \mathrm{R_p\:=\:1\:-\:T_p\:;} \\
&\mathrm{kv_alpha}^{*}\:\mathrm{L}\:)\:.^{\uparrow}2\:)\:; \\
&\text{:} \mathrm{R_alpha~=~1~-~T_alpha~;} 
\end{aligned}$$

21222324252627

28 $\%$ 创建图像1：电子的透射率

figure ;

plot(E,T_e,'LineWidth,2);

3 hold on; 32 xline(V, 'r--','LineWidth', 2,'DisplayName','\$E=V\$')

hold off:

34 xlabel('Energy (J)', 'Interpreter', 'latex');

35 ylabel('T_e', 'Interpreter','latex');

36title（"电子的透射率’，'Interpreter’，‘latex’）;

37 legend('Interpreter','latex'); 38grid on;

39

40 $\%$ 创建图像2：电子的反射率

41

figure ; 42plotER_e'LineWidth'2; 43 hold on;

44 xline(V,'r--,'LineWidth',2,'DisplayName','\$E-V\$')

------------------------------------------------------------------

xlabel('Energy (J)', 'Interpreter', 'latex'):.

47 ylabel('R_e', 'Interpreter', 'latex');

title（*电子的反射率’，"Interpreter”，"latex’）；

legend('Interpreter','latex'):. grid on;

52%创建图像3：质子的透射率，带局部放大

hold off; 51 s3 figure; 54 plotE,T_p,'LineWidth2; ss hold on; 56 xline(V, 'r--','LineWidth,2,'DisplayName','\$E=V\$') hold off; ss xlabel('Energy (J)','Interpreter', 'latex'); 59 ylabel('T_p','Interpreter','latex'); title（*质子的透射率’，"Interpreter”，“latex”）； 61 legend('Interpreter','latex');. 62grid on; 63 axes'Position',[.55 .15 .3 .3]); 64box on; 65 plot(E,T_p,'LineWidth',2); 66 xlim[1.0e-18 1.1e-18] 67ylim ([0 0.5]); 6s xlabel('Energy (J)','Interpreter','latex'); 69 ylabel('T_p', 'Interpreter', 'latex'): title（"局部放大’，*Interpreter’，"latex"）； 1 grid on; 7273 $\%$ 创建图像4：质子的反射率，带局部放大74 figure; 75 plot(E,R_p,'LineWidth',2); hold on; xline(V,'r--,'LineWidth',2,'DisplayName','\$E-V\$') hold off ; 79 xlabel('Energy (J)','Interpreter','latex'); ylabel('R_p', 'Interpreter', 'latex'); 8title（*质子的反射率’，‘Interpreter’，‘latex’）；

------------------------------------------------------------------

legend('Interpreter','latex'):

gridon ;

83

84 axes'Position'[5.5.3 .3])

85box on

s6 plotE,R_p,'LineWidth'2; 87 xlim[1.0e-18 1.1e-18]); ss ylim[0 0.5]);

89 xlabel('Energy (J)','Interpreter','latex');

o ylabel('R_p', 'Interpreter', 'latex');

91

title（*局部放大’，‘Interpreter’，"latex’）; gridon;

93

94 $\%$ 创建图像 5:

粒子的透射率，带局部放大

figure : plot(E,T_alpha,'LineWidth',2; hold on; xline(V, 'r--,'LineWidth',2,'DisplayName','\$E=V\$') hold off;

xlabel('Energy (J)','Interpreter','latex'); ylabel('T_\alpha','Interpreter','latex');

101

title（’粒子的透射率’，"Interpreter’，‘latex"）;

legend('Interpreter','latex');.

grid on;

axes'Position',[.55 .15 .3 .3]); box on;

107

plot(E,T_alpha,'LineWidth',2); xlim[1.0e-18 1.1e-18]) 109 ylim[0 0.5];

108

110

xlabel('Energy (J)','Interpreter','latex'); II ylabel(T_\alpha', 'Interpreter', 'latex');.

title（"局部放大’，*Interpreter’，"latex"）;

112

grid on;

113

114

115 $\%$ 创建图像6：粒子的反射率，带局部放大

16 figure; 117 plot(E,R_alpha,'LineWidth'2); s hold on;

------------------------------------------------------------------

119 xline(V, 'r--','LineWidth',2,'DisplayName','\$E-V\$')

120

xlabel('Energy (J)', 'Interpreter', 'latex');

122 ylabel('R_\alpha', 'Interpreter', 'latex');.

123title（’粒子的反射率’，‘Interpreter’，‘latex’);

124 legend('Interpreter','latex'):

hold off; 121125 grid on; 126 axes'Position[5 .5 .3.3]); 127box on; 128 plot(E,R_alpha,'LineWidth'2); 129 xlim[1.0e-181.1e-18130 ylim[0 0.5]; 131 xlabel('Energy (J)','Interpreter','latex') 132 ylabel('R_\alpha', 'Interpreter', 'latex'); 133title（"局部放大’，*Interpreter’，"latex"）； 134 grid on;

# 附录9

### homework20241025b.m

介绍：用于绘制Homework(9)20241025反射率、透射率随质量变化

，%定义常量2hbar = 1.0545718e-34; %约化普朗克常数$(J\cdot s)$ 3 L=1e-9 %长度 (m) 4 $V=1$e-10 %势能 (J) %能量 (J) 5 E=2e-10

7 $\%$ 定义不同的质量范围（kg) s mass_values = linspace(0.5 * 9.10938356e-31, 2 * 9.10938356e -31,100); 10 $\%$ 预分配数组111 $R=$ zerossize(mass_values)); 12 T= zeros(size(mass_values));

------------------------------------------------------------------

1314for $j=1:$ length (mass_values) 15 mass = mass_valuesj 161718
$$\begin{aligned}&\%计算k0和kv\\&\mathrm{k0~=~sqrt~(2~*~mass~*~E~/~hbar~2)\:;}\\&\mathrm{kv~=~sqrt~(2~*~mass~*~(E~-~V)~/~hbar~2)\:;}\end{aligned}$$
1920 $\%$ 计算反射率和透射率212223
$$\begin{aligned}
&\mathrm{R(j)} \\
&\text{)2 ) ;} \\
&\mathrm{T}(\mathrm{~j~}) \begin{array}{rcl}=&(16&*&\text{k}0^{\uparrow}2&*&\text{k}\text{v}^{\uparrow}2)&/&\ldots\end{array} \\
&(16^*k0^*2^*kv^*2+4^*(k0^*2^*-kv^*2)^*2^*\sin(kv^*L \\
&\left(\uparrow2\right);
\end{aligned}$$
242526end 27

28 $\%$ 绘制反射率与质量的关系图像

29figure 

plotmass_values,R,'LineWidth',2;

31 xlabel('Mass (kg)','Interpreter','latex'):

32 ylabel('R','Interpreter','latex');

title（"反射率R与质量的关系’，*Interpreter’，"latex’）;

gridon;

36 $\%$ 绘制透射宰与质量的关系图像

37 figure; plotmass_values,T,'LineWidth',2)

xlabel('Mass (kg)', 'Interpreter','latex');

ylabel( $^{,,}$T$^$, ,'Interpreter', 'latex');

41title（*透射率T与质量的关系’，"Interpreter’，"latex"）； 42grid on;

# 附录10

homework20241025c.m

------------------------------------------------------------------

## 1%定义常量

2 m = 9.10938356e-31; $\%$ 电子质量 (kg) 3hbar = 1.0545718e-34; $\%$ 约化普朗克常数(J$\cdot$s) $\%$ 势能 (J) 4 $V=1$e-18 : $\%$ 固定能量 (J) 5 E=1.5e-16

# 7 $\%$ 定义长度范围 (m)

sL=linspace0.5e-95e-9;

# 10 $\%$ 计算kO和kv

1 k0= $k0$ = $\mathrm{k0~=~sqrt~(2~*~m~*~E~/~hbar~}^{\sim}2);$ ~2 $^{\sim}2$ 12kv=sqrt2*m*E-V/hbar^2;

13

14 $\%$ 计算反射率和透射率

15R=16*k0^2*kv^2/16*k0^2*kv^2+4*k0^2-kv ~2 $^{\sim}2$ $~^{\sim}2).^{\sim}2$ .*sinkv.*L).^216T=4*k0^2-kv^2.2.*sinkv.*L.^2/16*k0^2* kv^2+4*k0^2-kv^2.^2.*sinkv.*L.^2

18 $\%$ 创建图像1：反射率

19figure

2 plot(L, R, 'LineWidth',2);

22 ylabel('R','Interpreter','latex');.

21 xlabel('Length (m)','Interpreter','latex'); 23title（*反射率R'，*Interpreter’，"latex'）； 24grid on; 25

26%创建图像2：透射率

27 figure;

2s plot(L, T, 'LineWidth', 2);

29 xlabel('Length (m)','Interpreter','latex');.

30 ylabel('T','Interpreter','latex');.

title（*透射率T'，*Interpreter’，'latex’）;

31

32

grid on;

------------------------------------------------------------------

## homework20241031b.m

介绍：用于绘制Homework(10)20241031反射率、透射率随能量变化

1 $\%$ 参数定义

2 ${\mathrm{m}}=9.11$e-31 : $\%$ 电子质量（kg) 3hbar = 1.0545718e-34; $\%$ 约化普朗克常数(J$\cdot$s) 4 $V=1$ ； $\%$ 势垒高度（eV) 5 L=1e-9 ： $\%$ 势垒宽度 (m) 7 $\%$ 能量范围8 $E=$ linspace(0,2, 1000); $\%$ 能量范围从0到2eV 10 $\%$ 单位换算11 $V_{-}J=V$ *1.60218e-19 $\%$ 从eV转换为J 12 E$\_$J= E *1.60218e-19; $\%$ 从eV转换为J 1314 $\%$ 初始化透射率15 T= zerossizeE); 16171819202122
$$\begin{aligned}
&\begin{array}{rl}{=}&{1:\mathrm{length}\left(\mathrm{E}\right)}\end{array} \\
&\mathrm{E_J(i)}<\mathrm{V_J} \\
&\mathrm{kv~=~sqrt~(2^*m^*abs~(E_J(~i~)-V_J)~)/hbar;} \\
&\mathrm{k0~=~sqrt~(2^*m^*E_J(~i~))/hbar;} \\
&\sinh\left(\mathrm{kv}^{*}\mathrm{L}\right)^{\uparrow}2\:)\:; \\
&\text{:} {\textrm{e i f}}{\textrm{E}}_{-}\mathrm{J}({\textrm{i}})=\mathrm{V}_{-}\mathrm{J} \\
&\mathrm{k0~=~s\:qrt~(2^{*}m^{*}E_J(~i~))/hbar;} \\
&\mathrm{T(~i)~=~4~/~(4~+~k0~2~*~L)~;} \\
&\text{e} \\
&\mathrm{kv~=~sqrt~(2^{*}m^{*}abs~(E_J(~i~)-V_J))/hbar;} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J(~i~)~)/hbar~;} \\
&\mathrm{T(~i)~=~(16^{*}k0^{\frown}2^{*}kv^{\frown}2)~/~(16^{*}k0^{\frown}2^{*}kv^{\frown}2~+~4^{*}(k0^{\frown}2~-~kv} \\
&^{\frown}2)^{\frown}2^{*}\:\sin{(\mathrm{kv}^{*}\mathrm{L})}^{\frown}2\:)\:;
\end{aligned}$$
2324 else 25262728 end 29 end

------------------------------------------------------------------

3 132 $\%$ 计算反射率33 $R=1$ -T; 3435 $\%$ 绘制完整的T vs E图36 figure; 37plotET 38xlabel（能量（eV）*）; 39ylabel（*透射率T'）； title（透射率与能量的关系（完整范围）‘)： 41 grid on; 4243 $\%$ 绘制RVsE图44figure: 4s plotER); 46xlabel（*能量(eV)*); 47ylabel（*反射率R'）； title（'反射率与能量的关系（完整范围）） gridon; 51 $\%$ 绘制$E<V$ 的透射率情况52figure; 53plot $(\operatorname{E}(\operatorname{E}<\operatorname{V})$ ， T$( \mathbf{E} \_$J$<\mathbf{V}\_\mathbf{J}))$ 54xlabel（能量（eV）*）; 55ylabel（*透射率T'）; title（'透射率与能量的关系（E<V）')： 57 grid on; 59 $\%$ 绘制$E>V$ 的透射率情况figure; 6lplot( $(\operatorname{E}(\operatorname{E}>\operatorname{V})$ ， T(E$\_$J > V$\_$J)) ： 62xlabel（*能量（eV）*); 63ylabel（*透射率T')； 64title（*透射率与能量的关系（E>V）')： 65grid on; 6667 $\%$ 绘制$E<V$ 的反射率情况

------------------------------------------------------------------

figure ; plot $(\operatorname{E}(\operatorname{E}<\operatorname{V})$ ， $\operatorname{R}(\operatorname{E\_}$J$<\operatorname{V\_J})$ ： xlabel（*能量(eV)*); 71ylabel（*反射率R'）； title（*反射率与能量的关系（E<V）') 7273grid on; 7475 $\%$ 绘制$E>V$ 的反射率情况figure; 77plot( $\operatorname{E}($E>V) ， $\operatorname{R}(\operatorname{E\_}$J$>\operatorname{V\_J})$ ： xlabel（能量（eV）*); 79ylabel（*反射率R'）： title（'反射率与能量的关系（ E > V ）） 81grid on;

# 附录12

# homework20241031b.m

介绍：用于绘制Homework(10)20241031透射率随能量变化E<V

1 $\%$ 参数定义%参数定义

2 ${\mathrm{m}}=9.11$e-31 ： $\%$ 电子质量 (kg) 3hbar = 1.0545718e-34; $\%$ 约化普朗克常数(J$\cdot$s) 4 $V=1$ ： $\%$ 势垒高度 (eV) 5 L=1e-9 ： $\%$ 势垒宽度 (m) 7 $\%$ 能量范围8 $E=$ linspace(0, V, 100): $\%$ 能量范围从O到VeV（即$E<V$ 10 $\%$ 单位换算111 $V\_J=V$ *1.60218e-19 $\%$ 从eV转换为J 12 E$\_$J= E * 1.60218e-19; $\%$ 从eV转换为J 1314 $\%$ 计算近似透射率15T_approx = zerossizeE

------------------------------------------------------------------

16for i = 1:length(E) exponent = sqrt8*m*V_J-E_Ji*L^2/ hbar 17 T$\_$approx( i) = 1 / ( 1 + ( 1/ 16) * ( $V^{\sim }$2 / ( E( i) * ( V - E( i ) ) ) ) . 18 *expexponent)

19end 2021 $\%$ 计算精确透射率22 T_exact = zeros(size(E) 23for $i=1$ :length(E) 2425
$$\begin{aligned}
&\mathrm{kv~=~sqrt~(2^{*}m^{*}(V_{-}J~-~E_{-}J(~i~)))/hbar;} \\
&\mathrm{k0~=~s\:qrt~(2^{*}m^{*}E_J(~i~))/hbar}\:; \\
&^{*}\:\sinh\left(\:\mathrm{kv}^{*}\mathrm{L}\:\right)^{\uparrow}2\:)\:;
\end{aligned}$$
2627end 28

# 29 $\%$ 计算误差

error = absT_exact-T_approx

30

31

32 $\%$ 绘制近似透射率图

33

figure; 34plot（E，T_approx，*b’，‘DisplayName”，'近似透射率"）

xlabel（*能量（eV）*）：

ylabel（*透射率T');

title（'近似透射率与能量的关系(E<V) , gridon;

40 $\%$ 绘制精确透射率图

41figure 42plot（E，T_exact，‘r’，"DisplayName’，'精确透射率"）；

43xlabel（*能量（eV）*);

44ylabel（*透射率T');

45title（*精确透射率与能量的关系(E$< V)$ , ） 46 grid on

47

48 $\%$ 绘制对比图

49 figure; plot（E，T_approx，‘b’，‘DisplayName’，'近似透射率’)

------------------------------------------------------------------

holdon; 52plot（E，T_exact，‘r--’，‘DisplayName’，‘精确透射率"） s3xlabel（*能量(eV)*); 54ylabel（'透射率T'); title（'透射率的比较(E<V) , )： 56legend show; 57 grid on;

5859 $\%$ 绘制误差图60figure 6lplot(E，error，‘g’，'DisplayName’，‘误差"）; 62xlabel（能量（eV）*); 63ylabel（误差"）； 64title（近似与精确透射率之间的误差”）： 65grid on;

# 附录13

## homework20241031c.m

介绍：用于绘制Homework(10)20241031透射率随能量变化E<V(级数展开）

1 $\%$ 参数定义

2 ${\mathrm{m}}=9.11$e-31 ： $\%$ 电子质量（kg) 3hbar = 1.0545718e -34; $\%$ 约化普朗克常数(J$\cdot$s) 4 $V=1$ ； $\%$ 势垒高度 (eV) 5 L=1e-9 ： $\%$ 势垒宽度 (m) 7 $\%$ 能量范围8 $E=$ linspace(0, V, 100): $\%$ 能量范围从O到VeV（即$E<V$ 10 $\%$ 单位换算111 $V_{-}J=V$ *1.60218e-19 $07_0$ 从eV转换为J 12 E$\_$J= E *1.60218e-19 $\%$ 从eV转换为J 1314%计算X

------------------------------------------------------------------

is x = zeros(size(E));

for $i=1$ : length (E)

16

exponent = sqrt8*m*VJ-E_Ji*L^2/hbar 1718 x( i ) = 16 x(i) = 16 x(i)=16*(E(i)*(V-E(i$)))/V^\sim2*$exp(-exponent) 19end

20

21 $\%$ 计算保留不同项数的T

22 T$\_$1st = x = X =x ； $\%$ 只保留第一项

23 T$\_$2nd=x-x.$^{\sim}2$ ： $\%$ 保留前两项

24 = X =x T$\_$3rd = x - x. $ ^{\sim }$2 + x. $ ^{\sim }$3 ： $\%$ 保留前三项

25

# 26 $\%$ 计算精确透射率

27T_exact = zerossizeE 28for $i=1$ :length (E) kv = sqrt ( $2^* m^*$( $V_J$ - E$\_$J( i) ) ) / hbar 2930 k0 = sqrt ( $2^{* }m^{* }$E$\_$J( i) ) / hbar T_exact(i)=4*k0^2*kv^2)/ 4*k0^2*kv^2+ (k0^2+ kv^2)^231 *sinh(kv*L)^2; 32end

33

34 $\%$ 计算误差
$$\begin{array}{rcl}\text{error_1st}&=&\text{abs}\left(\text{T_exact}&-&\text{T_1st}\right);\\\text{error_2nd}&=&\text{abs}\left(\text{T_exact}&-&\text{T_2nd}\right);\\\text{error_3rd}&=&\text{abs}\left(\text{T_exact}&-&\text{T_3rd}\right);\end{array}$$

3536

39 $\%$ 绘制透射率图

figure; 41plot(E，T_lst，“b’，"DisplayName’，’第一项") 42hold on; 43plot(E，T_2nd，‘r’，'DisplayName′，‘前两项*); 44plot(E，T_3rd，‘g’，‘DisplayName’，‘前三项"); 45xlabel（*能量（eV）*）; 46ylabel（*透射率T'); 47title（用级数展开逼近透射率）： 4slegend show; 49 grid on

------------------------------------------------------------------

51 $\%$ 绘制误差图

52 figure; 53plot（E，error_1st，"b”，“DisplayName’，‘第一项误差"） 54hold on; ssplot（E，error_2nd，‘r”，“DisplayName’，‘前两项误差"） s6plot（E，error_3rd，‘g’，“DisplayName’，‘前三项误差"） 57xlabel（*能量（eV）*）； 58ylabel（*误差"）； title（透射率逼近的误差')； legend show; 61 grid on

# 附录14

## homework20241031d.m

介绍：用于绘制Homework(10)20241031透射率随长度变化

1 $\%$ 参数定义

8 $L=$ linspace（0.1e9，5e9，100)；%势垒宽度从0.1mm到5mm

2 ${\mathrm{m}}=9.11$e-31 : $\%$ 电子质量（kg) 3hbar = 1.0545718e-34; $\%$ 约化普朗克常数(J$\cdot$s) 4 $V=1$ ： $\%$ 势垒高度 (eV) 5E_fixed = 0.5 ： $\%$ 固定能量 (eV) 7 $\%$ 势垒宽度范围10 $\%$ 单位换算11V_J=V * 1.60218e-19; $\%$ 从eV转换为J 12 E$\_$J= E$\_$ fixed * 1.60218e-19; $\%_0$ 从eV转换为J 1314 $\%$ 初始化透射率15 T= zeros(sizeL); 1617for i = 1:length (L) if $E\_J<V\_J$ 18

------------------------------------------------------------------

1920212223
$$\begin{aligned}
&\mathrm{kv~=~sqrt~(2^{*}m^{*}abs~(E_J-V_J)~)/hbar;} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J)/hbar~;} \\
&\sinh\left(\mathrm{kv}^{*}\mathrm{L}(\mathrm{~i})\right)^{\uparrow}2\:)\:; \\
&\text{se} \mathrm{if~E_J}=\mathrm{V_J} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J)/hbar~;} \\
&\mathrm{T(~i)~=~4~/~(4~+~k0~2~*~L(~i~)~)~;} \\
&\text{e} \\
&\mathrm{kv~=~sqrt~(2^{*}m^{*}abs~(E_J-V_J)~)/hbar~;} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J)/hbar~;} \\
&\Gamma(\textrm{i})\:=\:(16^{*}\textrm{k}0^{\frown}2^{*}\textrm{k}\textrm{v}^{\frown}2)\:/\:(16^{*}\textrm{k}0^{\frown}2^{*}\textrm{k}\textrm{v}^{\frown}2\:+\:4^{*}(\textrm{k}0^{\frown}2\:-\:\textrm{k} \\
&\uparrow2)^{\uparrow}2^{*}\:\sin\left(\mathrm{kv}^{*}\mathrm{L}\left(\mathrm{~i~}\right)\right)^{\uparrow}2\:)\:;
\end{aligned}$$
24 else 25262728 end 29 end 3132 $\%$ 计算反射率

33 $R=1$ -T； 3435 $\%$ 绘制TVSL图figure: 37plot $(\mathrm{L}^{*}1$e9 ，T)： xlabel（*势垒宽度（mm）"）； 39ylabel（*透射率T'); title（'透射率与势垒宽度的关系")； 41 grid on 4243 $\%$ 绘制RVSL图44figure; 45plot $(\mathrm{L}^*1$e9 ，R); 46xlabel（*势垒宽度（mm）*）; 4ylabel（'反射率R'）； title（"反射率与势垒宽度的关系"); gridon;

------------------------------------------------------------------

## homework20241031c.m

介绍：用于绘制Homework(10)20241031透射率随能量变化E<V(级数展开）

# 1 $\%$ 参数定义

2 ${\mathrm{m}}=9.11$e-31 : $\%$ 电子质量（kg) 3hbar = 1.0545718e-34; $\%$ 约化普朗克常数(J$\cdot$s) 4 $V=1$ ； $\%$ 势垒高度（eV)

5 L=1e-9 ： $\%$ 势垒宽度 (m)

7 $\%$ 能量范围

8 $E=$ linspace(0,V,100) $\%$ 能量范围从0到VeV（即$E<V$

10 $\%$ 单位换算

11 $V_{-}J=V$ * 1.60218e-19; $\%$ 从eV转换为J 12 E$\_$J= E *1.60218e-19; $\%$ 从eV转换为J

13

14 $\%$ 计算 X

15 x= zeros(size(E));

16for $i=1$ :length (E) exponent = sqrt8*m*VJ-E_Ji*L^2/hbar 1718

19end

20

21 $\%$ 计算保留不同项数的T

22 T$\_$1st = x =x = X ； $\%$ 只保留第一项

23 T$\_$2nd=x-x.$^{\sim}2$ ~2 $\stackrel{\sim}2$ ： $\%$ 保留前两项

24 =X =x T$\_$3rd = x - x. $ ^{\sim }$2 + x. $ ^{\sim }$3 $\mathbf{x} . ^{ }2$ + $\mathbf{x} . ^{ }3$ $\mathbf{x} . ^{ }2$ + $\mathbf{x} . ^{ }3$ ： $\%$ 保留前三项

25

26 $\%$ 计算精确透射率

27T_exact = zeros(size(E)

28for $i=1$ : length (E) kv = sqrt ( $2^* m^*$( $V_J$ - $E_J$( i) ) ) / hbar: 2930 k0 = sqrt ( $2^* m^*$E$\_$J( i) ) / hbar T_exacti=4*k0^2*kv^2/4*k0^2*kv^2+k0^2+ kv^2231 *sinh(kv*L)^2);

------------------------------------------------------------------

end

33

34 $\%$ 计算误差

35 error_1st = absT_exact-T_1st 36 error_2nd = abs(T_exact - T_2nd); 37 error_3rd = absT_exact-T_3rd;

## $\%$ 绘制透射率图

figure; 4plot(E，T_lst，"b’，*DisplayName’，‘第一项"）; 42 hold on; 43plot(E，T_2nd，‘r’，‘DisplayName’，‘前两项") 4plot(E，T_3rd，'g’，*DisplayName’，‘前三项"); 45xlabel（*能量（eV）*); ylabel（*透射率T'）; title（用级数展开逼近透射率）； legend show; gridon；

51%绘制误差图52figure; plot（E，error_lst，“b’，"DisplayName’，*第一项误差")； 54hold on; plot（E，error_2nd，*r’，"DisplayName”，‘前两项误差"); plot（E，error_3rd，‘g”，"DisplayName’，‘前三项误差"）； xlabel（能量（eV）*); 58ylabel（*误差"）; 59title（'透射率逼近的误差)； $f_{r}(0)$ legend show; 6lgrid on;

# 附录16

## homework20241031d.m

------------------------------------------------------------------

## 1 $\%$ 参数定义

3 ${\mathrm{m}}=9.11$e-31 : $\%$ 电子质量 (kg) 4hbar =1.0545718e-34 : $\%$ 约化普朗克常数(J$\cdot$s) 5 $V=1$ ： $\%$ 势垒高度 (eV) 6 E_fixed = 0.5 ： $\%$ 固定能量 (eV)

8 $\%$ 势垒宽度范围

11 $\%$ % $\%$ 单位换算

## 15 $\%$ 初始化透射率

2 $\%$ 参数定义9 $\mathcal{L}=$ linspace(0.1e-9, 5e-9, 100); $\%$ 势垒宽度从0.1mm到5mm 12V_J=V*1.60218e-19 $\%$ 从eV转换为J 13 E$\_$J= E$\_$ fixed * 1.60218e-19; $\%$ 从eV转换为J 1416 T= zerossize(L) 17181920212223
$$\begin{aligned}
&\begin{array}{rl}{=}&{1:\mathrm{length}\left(\mathrm{L}\right)}\end{array} \\
&\mathrm{E_J}<\mathrm{V_J} \\
&\mathrm{kv~=~sqrt~(2^*m^*abs~(E_J-V_J)~)/hbar;} \\
&\mathrm{k0~=~sqrt~(2^*m^*E_J)/hbar~;} \\
&\mathrm{T(i)}\:=\:(4^{*}\mathrm{k}0^{\uparrow}2^{*}\mathrm{k}\mathrm{v}^{\uparrow}2)\:/\:(4^{*}\mathrm{k}0^{\uparrow}2^{*}\mathrm{k}\mathrm{v}^{\uparrow}2\:+\:(\mathrm{k}0^{\uparrow}2\:+ \\
&sinh(kv*L(i))^{\uparrow}2)\:; \\
&\text{se} {\textrm{i f}}{\textrm{E}}_{-}\mathrm{J}=\mathrm{V}_{-}\mathrm{J} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J)/hbar~;} \\
&\mathrm{T(~i)~=~4~/~(4~+~k0~2~*~L(~i~)~)~;} \\
&\text{e} \\
&\mathrm{kv~=~sqrt~(2^{*}m^{*}abs~(E_J-V_J))/hbar;} \\
&\mathrm{k0~=~sqrt~(2^{*}m^{*}E_J)/hbar~;} \\
&\mathrm{T(~i~)~=~(16^{*}k0^{\uparrow}2^{*}kv^{\uparrow}2)~/} \\
&^{\frown}2)^{\frown}2^{*}\:\sin\left(\mathrm{kv}^{*}\mathrm{L}\left(\mathrm{~i}\right)\right)^{\frown}2\:)\:;
\end{aligned}$$
2425 else 26272829 end 3031end 3233 $\%$ 计算反射率34 $R=1$ -T;

------------------------------------------------------------------

$\%$ 绘制TVsL图figure: 38plot $\langle\mathrm{L}^{*}1$e9 ，T); 39xlabel（势垒宽度（mm））； ylabel（'透射率T')： 4title（'透射率与势垒宽度的关系")； 42 grid on; 4344 $\%$ 绘制RVsL图45figure; 46plot $(\mathrm{L}^*1$e9 ，R); 47xlabel（*势垒宽度（nm）*）； 48vlabel（反射率R'）： 49title（*反射率与势垒宽度的关系） gridon: