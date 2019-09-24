# 第一章 函数与极限

## 第一节 函数

### 三角函数

https://zhuanlan.zhihu.com/p/20102140

基本定义
$$
\sin\alpha=y \qquad
\cos\alpha=x \qquad
\tan\alpha=\frac{y}{x} \\

\csc\alpha=\frac{1}{y} \qquad
\sec\alpha=\frac{1}{x} \qquad
\cot\alpha=\frac{x}{y} \\
$$
基本关系
$$
\frac{\sin\alpha}{\cos\alpha} = \tan\alpha = \frac{\sec\alpha}{\csc\alpha} \\
\frac{\cos\alpha}{\sin\alpha} = \cot\alpha = \frac{\csc\alpha}{\sec\alpha} \\
$$
和差角公式
$$
\sin({x}\pm{y}) = \sin{x}\cos{y} \pm \cos{x}\sin{y} \\
\cos({x}\pm{y}) = \cos{x}\cos{y} \mp \sin{x}\sin{y} \\
$$
倍角公式
$$
\sin{2x} = 2\sin{x}\cos{x} \\
\cos{2x} = \cos^2{x}-\sin^2{x}
$$
积化和差公式
$$
\sin{x}\cos{y} = \frac{\sin(x+y)+\sin(x-y)}{2} \\
\cos{x}\sin{y} = \frac{\sin(x+y)-\sin(x-y)}{2} \\
\cos{x}\cos{y} = \frac{\cos(x+y)+\cos(x-y)}{2} \\
\sin{x}\sin{y} = \frac{\cos(x-y)-\cos(x+y)}{2} \\
$$
和差化积公式
$$
u = x + y, \quad v = x - y \\
\Downarrow \\
x = \frac{u+v}{2}, \quad y = \frac{u-v}{2} \\
$$

$$
\sin{u} + \sin{v} = 2\sin{\frac{u+v}{2}}\cos{\frac{u-v}{2}} \\
\sin{u} - \sin{v} = 2\cos{\frac{u+v}{2}}\sin{\frac{u-v}{2}} \\
\cos{u} + \cos{v} = 2\cos{\frac{u+v}{2}}\cos{\frac{u-v}{2}} \\
\cos{u} - \cos{v} = (-2)\sin{\frac{u+v}{2}}\sin{\frac{u-v}{2}} \\
$$

### 反三角函数

### 双曲函数

https://zhuanlan.zhihu.com/p/20042215









## 第三节 函数的极限

### 函数极限的定义

1.自变量趋于有限值时
$$
\lim_{x\rightarrow{x_0}} {f(x)}=A \Leftrightarrow \forall\epsilon>0,\exists\delta>0,当0<|x-x_0|<\delta时，有|f(x)-A|<\epsilon
$$
2.自变量趋于无穷大时
$$
\lim_{x\rightarrow\infty} {f(x)}=A \Leftrightarrow \forall\epsilon>0,\exists{X}>0,当|x|>X时，有|f(x)-A|<\epsilon
$$

## 第四节 无穷大与无穷小

### 无穷小

定义1 如果函数$f(x)$极限为零，称$f(x)$无穷小。
$$
\lim_{x\rightarrow{x_0}}f(x) = 0 \Leftrightarrow \forall\epsilon>0,\exists\delta>0,当0<|x-x_0|<\delta时，有|f(x)|<\epsilon
\\
\lim_{x\rightarrow\infty}f(x) = 0 \Leftrightarrow \forall\epsilon>0,\exists{X}>0,当|x|>X时，有|f(x)|<\epsilon
\\
$$

### 无穷大

定义2


$$
\lim_{x\rightarrow{x_0}} f(x) = \infty \Leftrightarrow \forall{M}>0,\exists\delta>0,使当0<|x-x_0|<\delta时，即有|f(x)|>M
\\
\lim_{x\rightarrow\infty} f(x) = \infty \Leftrightarrow \forall{M}>0,\exists{X}>0,使当|x|>X时，即有|f(x)>M
$$



### 习题1-4的第5题

|                       | $f(x)\rightarrow{A}$                                         | $f(x)\rightarrow\infty$                                      | $f(x)\rightarrow+\infty$ | $f(x)\rightarrow-\infty$ |
| --------------------- | :----------------------------------------------------------- | ------------------------------------------------------------ | ------------------------ | ------------------------ |
| $x\rightarrow{x_0}$   | $\forall\epsilon>0,\exists\delta>0,$<br/>使当$0<|x-x_0|<\delta$时，<br/>即有$|f(x)-A|<\epsilon$ | $\forall{M}>0,\exists\delta>0,$<br/>当$0<|x-x_0|<\delta$时，<br/>即有$|f(x)|>M$ |                          |                          |
| $x\rightarrow{x_0^+}$ | $\forall\epsilon>0,\exists\delta>0,$<br/>使当$0<x-x_0<\delta$时，<br/>即有$|f(x)-A|<\epsilon$ |                                                              |                          |                          |
| $x\rightarrow{x_0^-}$ | $\forall\epsilon>0,\exists\delta>0,$<br/>使当$-\delta<x-x_0<0$时，<br/>即有$|f(x)-A|<\epsilon$ |                                                              |                          |                          |
| $x\rightarrow\infty$  | $\forall\epsilon>0,\exists{X}>0,$<br/>当$|x|>X$时，<br/>即有$|f(x)-A|<\epsilon$ | $\forall{M}>0,\exists{X}>0,$<br>当$|x|>X$时，<br/>有$|f(x)|>M$ |                          |                          |
| $x\rightarrow+\infty$ |                                                              |                                                              |                          |                          |
| $x\rightarrow-\infty$ |                                                              |                                                              |                          |                          |



## 第六节 极限存在准则 两个重要极限

### 极限存在准则

### 两个重要极限

$$
\lim_{x\rightarrow0}\frac{\sin{x}}{x}=1 \\
\lim_{x\rightarrow\infty}(1+\frac{1}{x})^x=e
$$



## 第七节 无穷小的比较

### 同阶无穷小

$$
\lim_{x\rightarrow0}\frac{\log_a(1+x)}{x} = \frac{1}{\ln{a}} \\
\lim_{x\rightarrow0}\frac{a^x-1}{x} = \ln{a}  \\
\lim_{x\rightarrow0}\frac{(1+x)^\alpha-1}{x} = \alpha \\
$$



### K阶无穷小

$$
\lim_{x\rightarrow0}\frac{1-\cos{x}}{x^2}=\frac{1}{2} \\
$$

### 等价无穷小

$$
\tan{2x}\sim{2x} \\
\sin{2x}\sim{2x} \\
\ln(1+x)\sim{x}({x}\rightarrow{0}) \\
e^x-1\sim{x}({x}\rightarrow{0}) \\
(1+x)^\alpha-1\sim\alpha{x}({x}\rightarrow{0}) \\
$$

# 第二章 导数

## 第一节 导数概念

### 非均速直线运动的速度和切线的斜率

$$
\lim_{x\rightarrow{x_0}}\frac{f(x)-f(x_0)}{x-x_0}
$$



### 定义

$$
f'(x_0) 
= \lim_{\Delta{x}\rightarrow{0}}\frac{\Delta{y}}{\Delta{x}}
= \lim_{\Delta{x_0}\rightarrow{0}}\frac{f(x_0+\Delta{x}) - f(x_0)}{\Delta{x}} \\

也可记作：
y'|_{x=x_0}, \quad \frac{dy}{dx}|_{x=x_0}, \quad \frac{df(x)}{dx}|_{x=x_0}
$$



### 几何意义

切线方程:  $y - y_0 = f'(x_0)(x-x_0)$

法线方程: $y-y_0 = -\frac{1}{f'(x_0)}(x-x_0)$



## 第三节 高阶导数

### 几个初等函数n阶导数

$$
(e^x)^{(n)}=e^x \\
(\sin{x})^{(n)} = \sin(x + n \cdot \frac{\pi}{2}) \\
(\cos{x})^{(n)} = \cos(x + n \cdot \frac{\pi}{2}) \\
{[\ln(1+x)]}^{(n)} = (-1)^{n-1}\frac{(n-1)!}{(1+x)^n} \\
(x^\mu)^{(n)} = \mu(\mu-1)(\mu-2)\cdots(\mu-n+1)x^{\mu-n} \\
({u}\pm{v})^{(n)} = {u^{(n)}}\pm{v^{(n)}}
$$



### 莱布尼茨公式

$$
(uv)^{(n)} = {\sum_{k=0}^n}{C_n^k}{u^{(n-k)}}{v^(k)}
$$

## 第二、五节 导数公式和法则 微分公式和法则

LaTex 定义dif: (https://liam.page/2017/05/01/the-correct-way-to-use-differential-operator/)
$$
\newcommand{\dif}{\mathop{}\!\mathrm{d}}

\dif
$$

### 初等函数

| 导数公式                                      | 微分公式                                              |
| :-------------------------------------------- | ----------------------------------------------------- |
| $(x^\mu)' = \mu{x}^{\mu-1}$                   | $\dif(x^\mu) = \mu{x}^{\mu-1}\dif{x}$                 |
| $(\sin{x})' = \cos{x}$                        | $\dif(\sin{x}) = \cos{x}\dif{x}$                      |
| $(\cos{x})' = -\sin{x}$                       | $\dif(\cos{x}) = -\sin{x}\dif{x}$                     |
| $(\tan{x})' = \sec^2{x}$                      | $\dif(\tan{x}) = \sec^2{x}\dif{x}$                    |
| $(\cot{x})' = -\csc^2{x}$                     | $\dif(\cot{x}) = -\csc^2{x}\dif{x}$                   |
| $(a^x)' = a^x\ln{a}(a>0且a\neq1)$             | $\dif(a^x) = a^x\ln{a}\dif{x}(a>0且a\neq1)$           |
| $(e^x)' = e^x$                                | $\dif(e^x) = e^x\dif{x}$                              |
| $(\log_ax)' = \frac{1}{x\ln{a}}(a>0且a\neq1)$ | $\dif(log_ax)= \frac{1}{x\ln{a}}\dif{x}(a>0且a\neq1)$ |
| $(\ln{x})' = \frac{1}{x}$                     | $\dif(\ln{x}) = \frac{1}{x}\dif{x}$                   |
| $(\arcsin{x})' = \frac{1}{\sqrt{1-x^2}}$      | $\dif(\arcsin{x}) = \frac{1}{\sqrt{1-x^2}}\dif{x}$    |
| $(\arccos{x})' = -\frac{1}{\sqrt{1-x^2}}$     | $\dif(\arccos{x}) = -\frac{1}{\sqrt{1-x^2}}\dif{x}$   |
| $(\arctan{x})' = \frac{1}{1+x^2}$             | $\dif(\arctan{x}) = \frac{1}{1+x^2}\dif{x}$           |
| $(\text{arccot}{x})' = -\frac{1}{1+x^2}$      | $\dif(\text{arccot}{x}) = -\frac{1}{1+x^2}\dif{x}$    |

### 和差积商

| 和差积商的求导法则                               | 和差积商的微分法则                                           |
| ------------------------------------------------ | ------------------------------------------------------------ |
| $(u \pm v)' = u' \pm v'$                         | $\dif(u \pm v) = \dif{u} \pm \dif{v}$                        |
| $(Cu)' = Cu'$                                    | $\dif(Cu) = C\dif{u}$                                        |
| $(uv)' = u'v + v'u$                              | $\dif(uv) = v\dif{u} + u\dif{v}$                             |
| $(\frac{u}{v})' = \frac{u'v-v'u}{v^2}(v \neq 0)$ | $\dif(\frac{u}{v}) = \frac{v\dif{u}-u\dif{v}}{v^2}(v \neq 0)$ |

### 反函数求导法则

$$
[f^{-1}(x)]' = \frac{1}{f'(y)} 或 \frac{\dif{y}}{\dif{x}} = \frac{1}{\frac{\dif{x}}{\dif{y}}}
$$

### 复合函数

| 复合函数的求导法则$y=f(u),u=g(x)$ | 复合函数的微分法则$y=f(u),u=g(x)$                            |
| --------------------------------- | ------------------------------------------------------------ |
| $y'(x) = f'(u)\cdot{g'(x)}$       | $\newcommand*{\dif}{\mathop{}\!\mathrm{d}}y = f'(u)g'(x)\newcommand*{\dif}{\mathop{}\!\mathrm{d}}x$ 或 $\newcommand*{\dif}{\mathop{}\!\mathrm{d}}y = f'(u)\newcommand*{\dif}{\mathop{}\!\mathrm{d}}u$ |

## 第五节 微分在近似计算中的应用

### 近似计算公式

$$
\begin{gather}
\Delta{y} = f(x_0+\Delta{x}) - f(x_0) \approx f'(x_0)\Delta{x} \tag{5-4} \\
f(x_0+\Delta{x}) \approx f(x_0) + f'(x_0)\Delta{x} \tag{5-5} \\
f(x) \approx f(x_0) + f'(x_0)(x-x_0) \tag{5-6} \\
\end{gather}
$$

### 近似计算实质

近似计算的实质是用$x$的线性函数$f(x_0)+f'(x_0)(x-x_0)$来近似表达函数$f(x)$

### 工程中常用近似公式

$$
(1+x)^\alpha \approx 1+\alpha{x}(\alpha \in \mathbb{R}) \\
\sin(x) \approx x (x用弧度单位) \\
\tan(x) \approx x (x用弧度单位) \\
e^x \approx 1 + x \\
\ln(1+x) \approx x \\
$$
