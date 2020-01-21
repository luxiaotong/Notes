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

## 第四节 隐函数及参数方程的导数

### 对数求导法

### 参数方程的导数

$$
\begin{gather}
\begin{cases}
x = \varphi(t) \\
y = \psi(t) \\
\end{cases} \tag{4-3} \\

\frac{\dif{y}}{\dif{x}} = \frac{\frac{\dif{y}}{\dif{t}}}{\frac{\dif{x}}{\dif{t}}} \tag{4-4} \\
\frac{\dif^2{y}}{\dif{x^2}} = \frac{\dif}{\dif{x}}\left(\frac{\dif{y}}{\dif{x}}\right) \cdot \frac{1}{\frac{\dif{x}}{\dif{t}}} \tag{4-5} \\
\end{gather}
$$



## 第五节 微分在近似计算中的应用

### 定义

$$
\begin{gather}
\Delta{y} = f(x_0+\Delta{x}) - f(x_0) \tag{5-1} \\
\dif{y} = f'(x)\Delta{x} \tag{5-2} \\
\end{gather}
$$



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

## 导数公式和法则 微分公式和法则

### 初等函数

| 导数公式                                      | 微分公式                                              |
| :-------------------------------------------- | ----------------------------------------------------- |
| $(x^\mu)' = \mu{x}^{\mu-1}$                   | $\dif(x^\mu) = \mu{x}^{\mu-1}\dif{x}$                 |
| $(\sin{x})' = \cos{x}$                        | $\dif(\sin{x}) = \cos{x}\dif{x}$                      |
| $(\cos{x})' = -\sin{x}$                       | $\dif(\cos{x}) = -\sin{x}\dif{x}$                     |
| $(\tan{x})' = \sec^2{x}$                      | $\dif(\tan{x}) = \sec^2{x}\dif{x}$                    |
| $(\cot{x})' = -\csc^2{x}$                     | $\dif(\cot{x}) = -\csc^2{x}\dif{x}$                   |
| $(\sec{x})'=\sec{x}\tan{x}$                   | $\dif(\sec{x})=\sec{x}\tan{x}\dif{x}$                 |
| $(\csc{x})'=-\csc{x}\cot{x}$                  | $\dif(\csc{x})=-\csc{x}\cot{x}\dif{x}$                |
| $(a^x)' = a^x\ln{a}(a>0且a\neq1)$             | $\dif(a^x) = a^x\ln{a}\dif{x}(a>0且a\neq1)$           |
| $(e^x)' = e^x$                                | $\dif(e^x) = e^x\dif{x}$                              |
| $(\log_ax)' = \frac{1}{x\ln{a}}(a>0且a\neq1)$ | $\dif(log_ax)= \frac{1}{x\ln{a}}\dif{x}(a>0且a\neq1)$ |
| $(\ln{x})' = \frac{1}{x}$                     | $\dif(\ln{x}) = \frac{1}{x}\dif{x}$                   |
| $(\arcsin{x})' = \frac{1}{\sqrt{1-x^2}}$      | $\dif(\arcsin{x}) = \frac{1}{\sqrt{1-x^2}}\dif{x}$    |
| $(\arccos{x})' = -\frac{1}{\sqrt{1-x^2}}$     | $\dif(\arccos{x}) = -\frac{1}{\sqrt{1-x^2}}\dif{x}$   |
| $(\arctan{x})' = \frac{1}{1+x^2}$             | $\dif(\arctan{x}) = \frac{1}{1+x^2}\dif{x}$           |
| $(\text{arccot}{x})' = -\frac{1}{1+x^2}$      | $\dif(\text{arccot}{x}) = -\frac{1}{1+x^2}\dif{x}$    |

### 和差积商

| 和差积商的求导法则                               | 和差积商的微分法                                             |
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



# 第三章 微分中值定理与导数应用

## 第一节 微分中值定理

### 费马引理

设函数$f(x)$在点$x_0$的某邻域$U(x_0)$内有定义，并且在$x_0$处可导，

如果对任意的$x \in U(x_0)$，有$f(x) \leq f(x_0)$，那么
$$
f'(x_0)=0
$$


### 罗尔定理

如果函数$f(x)$满足

（1）在$[a, b]$上连续；

（2）在$(a, b)$内可导；

（3）$f(a) = f(b)$，

那么在$(a, b)$内至少一点$\xi(a<\xi<b)$，使得
$$
f'(\xi)=0
$$


### 拉格朗日中值定理

如果函数$f(x)$满足：

（1）在$[a, b]$上连续；

（2）在$(a, b)$内可导，

那么在$(a, b)$内至少一点$\xi(a<\xi<b)$，使得
$$
f(b)-f(a)=f'(\xi)(b-a)
$$

### 柯西中值定理

如果函数$f(x)$满足：

（1）在$[a, b]$上连续；

（2）在$(a, b)$内可导；

（3）对$\forall x \in (a,b)$，$F'(x) \neq 0$，

那么在$(a, b)$内至少一点$\xi(a<\xi<b)$，使得
$$
\frac{f(b)-f(a)}{F(b)-F(a)} = \frac{f'(\xi)}{f'(\xi)}
$$

## 第二节 洛必达法则

### 不定式

如果当$x\rightarrow{a}$（或$x\rightarrow\infty$）时，两个函数$f(x)与$F(x)都趋于零或都趋于无穷大，那么
$$
\lim_{\substack{x\rightarrow{a} \\ (x\rightarrow\infty)}}\frac{f(x)}{F(x)}
$$
可能存在，也可能不存在。通常把这种极限叫做都未定式，并简记为$\frac{0}{0}$或$\frac{\infty}{\infty}$

### 定理1

设

（1）当$x\rightarrow{a}$时，函数$f(x)$及$F(x)$都趋于零；

（2）在点$a$的某去心邻域内，$f'(x)$及$F'(x)$都存在且$F'(x) \neq 0$；

（3）${\lim_{x\rightarrow{a}}}\frac{f'(x)}{F'(x)}$存在（或为无穷大），则
$$
\lim_{x\rightarrow{a}}\frac{f(x)}{F(x)}=\lim_{x\rightarrow{a}}\frac{f'(x)}{F'(x)}
$$

### 定理2

设

（1）当$x\rightarrow{\infty}$时，函数$f(x)$及$F(x)$都趋于零；

（2）当$|x|>N$时$f'(x)$及$F'(x)$都存在且$F'(x) \neq 0$；

（3）${\lim_{x\rightarrow{\infty}}}\frac{f'(x)}{F'(x)}$存在（或为无穷大），则
$$
\lim_{x\rightarrow{\infty}}\frac{f(x)}{F(x)}=\lim_{x\rightarrow{\infty}}\frac{f'(x)}{F'(x)}
$$

### 注意

如果不是未定式，就不能应用洛必达法则。



## 第三节 泰勒公式

### n阶泰勒公式

$$
f(x) = f(x_0)+f'(x_0)(x-x_0)+\frac{f''(x_0)}{2!}(x-x_0)^2+\cdots+\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n+R_n(x) \tag{3-3} \\
$$

### 佩亚诺余项

$$
R_n(X)=o((x-x_0)^n) \tag{3-4} \\
$$

### 拉格朗日余项

$$
R_n(x) = \frac{f^{(n+1)}(\xi)}{(n+1)!}(x-x_0)^{n+1} \tag{3-6}
$$

### 误差估计式

$$
|R_n(x)|=\left|\frac{f^{(n+1)}(\xi)}{(n+1)!}\right| \leq \frac{M}{(n+1)!}|x-x_0|^{n+1} \tag{3-7}
$$



### 带有佩亚诺余项的麦克劳林公式

$$
f(x) = f(0)+f'(0)x+\cdots+\frac{f^{(n)}}{n!}x^n+o(x^n) \tag{3-8}
$$

### 带有拉格朗日余项的麦克劳林公式

$$
f(x) = f(0)+f'(0)x+\frac{f''(0)}{2!}x^2+\cdots+\frac{f^{(n)}(0)}{n!}+\frac{f^{(n+1)}(\theta{x})}{(n+1)!}x^{n+1} \qquad (0<\theta<1) \tag{3-9}
$$

### 近似公式

$$
f(x) \approx f(0) + f'(0)x + \frac{f''(0)}{2!}x^2+\cdots+\frac{f^{(n)}(0)}{n!}x^n
$$

### 误差估计式

$$
|R_n(x)| leq \frac{M}{(n+1)!}|x|^{n+1} \tag{3-10}
$$

## 第四节 单调性、凹凸性、拐点

### 单调性

单调增加：$f'(x) \geq 0$

单调减少：$f'(x) \leq 0$

### 凹凸性

凹：$f''(x) > 0$

凸：$f''(x) < 0$

### 拐点

定义：改变凹凸性的点

## 第五节 极值与最值

### 必要条件

极值$\Rightarrow f'(x)=0$

### 第一充分定理

极大值：在$x_0$左侧，$f'(x)>0$；在$x_0$右侧，$f'(x)<0$

极小值：在$x_0$左侧，$f'(x)<0$；在$x_0$右侧，$f'(x)>0$

### 第二充分定理

极大值：$f'(x)=0, f''(x)<0$

极小值：$f'(x)=0, f''(x)>0$

### 最值问题



## 第六节 函数图形的描绘

利用导数描绘函数图形的一般步骤：

第一步，求定义域，函数性质（奇偶、周期）。求出$f'(x), f''(x)$。

第二步，求$f'(x)$和$f''(x)$的零点，求$f(x)$的间断点，$f'(x), f''(x)$的不存在点。划分区间。

第三步，求各区间内$f'(x),f''(x)$的符号，确定单调性、凹凸性、拐点。

第四步，水平、铅直渐近线。

第五步，计算第二步中各个点的$(x, y)$值，结合第三、四步结果，联结各点画出图形。

## 第七节 曲率

### 弧微分公式

$$
ds = \sqrt{1+y'^2} \tag{7-1}
$$

### 曲率计算公式

$$
\begin{gather}
K = \lim_{\Delta{s}\rightarrow0}\left|\frac{\Delta{\alpha}}{\Delta{s}}\right|
或
K = \left|\frac{\dif{\alpha}}{\dif{s}}\right| \tag{7-2} \\

K = \frac{|y''|}{(1+y'^2)^{3/2}} \tag{7-3} \\

K = \frac{|\varphi'(x)\psi''(x)-\varphi''(t)\psi(x)|}{[\varphi'^2(t)+\phi'^2(t)]^{3/2}} \tag{7-4} \\

K = \frac{|y''|}{(1+y'^2)^{3/2}} \approx |y''| \\
\end{gather}
$$

### 曲率半径

$$
\rho = \frac{1}{K}
$$

## 第八节

### 隔离区间

### 二分法

### 切线法

$$
x_{n+1} = x_{n} - \frac{f(x_{n})}{f'(x_{n})}
$$



### 割线法

计算导数困难时，使用割线法替代切线法。
$$
x_{n+1} = x_n - \frac{x_n - x_{n-1}}{f(x_n)-f(x_{n-1})} f(x_n)
$$

# 第四章 不定积分

## 第一节 概念与性质

### 含义：导函数的原函数+常数项

$$
\int{f(x)}\dif{x} = F(x)+C
$$

### 基础积分表（熟记）

$$
\begin{align*}
& \int{k}\dif{x} = kx + C (k是常数) \\
& \int{x^\mu}\dif{x} = \frac{x^{\mu+1}}{\mu+1} + C \\
& \int\frac{1}{x}\dif{x} = \ln{x} + C \\
& \int\frac{1}{1+x^2}\dif{x} = \arctan{x} + C \\
& \int\frac{1}{\sqrt{1-x^2}}\dif{x} = \arcsin{x} + C \\
& \int\cos{x}\dif{x} = \sin{x} + C \\
& \int\sin{x}\dif{x} = -\cos{x} + C \\
& \int\frac{1}{\cos^2{x}}\dif{x} = \int\sec^2{x}\dif{x} = \tan{x} + C \\
& \int\frac{1}{\sin^2{x}}\dif{x} = \int\csc^2{x}\dif{x} = -\cot{x} + C \\
& \int\sec{x}\tan{x}\dif{x} = \sec{x} + C \\
& \int\csc{x}\cot{x}\dif{x} = -\csc{x} + C \\
& \int{e^x}\dif{x} = e^x + C \\
& \int{a^x}\dif{x} = \frac{a^x}{\ln{a}} + C \\
\end{align*}
$$



## 第二节 换元积分法

### 含义：求复合函数积分

### 第一类换元法

$$
{\int}f([\varphi(x)])\varphi'(x)\dif{x} = \left[{\int}f(u)\dif{u}\right]_{u=\varphi(x)} \tag{2-1}
$$



### 第二类换元法

$$
{\int}f(x)\dif{x} = \left[{\int}f[\psi(x)]\psi'(t)\dif{t}\right]_{t=\psi^{-1}(x)} \tag{2-2}
$$



### 常用积分表

$$
\begin{align*}
& \int\sinh{x}\dif{x} = \cosh{x} + C \\
& \int\cosh{x}\dif{x} = \sinh{x} + C \\
& \int\tan{x}\dif{x} = -\ln|\cos{x}| + C \\
& \int\cot{x}\dif{x} = \ln|\sin{x}| + C \\
& \int\sec{x}\dif{x} = \ln|\sec{x}+\tan{x}| + C \\
& \int\csc{x}\dif{x} = \ln|\csc{x}-\cot{x}| + C \\
& \int\frac{1}{a^2+x^2}\dif{x} = \frac{1}{a} \arctan{\frac{x}{a}} + C \\
& \int\frac{1}{x^2-a^2}\dif{x} = \frac{1}{2}\ln\left|\frac{x-a}{x+a}\right| = C\\
& \int\frac{1}{\sqrt{a^2-x^2}}\dif{x} = \arcsin\frac{x}{a} + C \\
& \int\frac{1}{\sqrt{x^2+a^2}}\dif{x} = \ln(x + \sqrt{x^2+a^2}) + C \\
& \int\frac{1}{\sqrt{x^2-a^2}}\dif{x} = \ln|x + \sqrt{x^2-a^2}| + C \\
\end{align*}
$$





## 第三节 分部积分法

含义用两个函数乘积的求导法则，推得另一个求积分的基本方法
$$
\int{u}\dif{v} = uv - \int{v}\dif{u} \tag{3-2}
$$
选取恰当的$u$和$\dif{v}$：

（1）$v$要容易求得。

（2）$\int{v}\dif{u}$比$\int{u}\dif{v}$容易计算。



# 第五章 定积分

## 第一节 概念与性质

### 定义

$$
\int_a^bf(x)\dif{x} = \lim_{\lambda\rightarrow{0}}\sum_{i=1}^nf(\xi_i)\Delta{x_i} \tag{1-2}
$$

### 定理

定理1：连续 => 可积

定理2：有界，有限间断点 => 可积


$$
1^2+2^2+\cdots+n^2 = \frac{1}{6}n(n+1)(2n+1)
$$

### 近似计算

矩形法公式
$$
\int_a^bf(x)\dif(x) \approx \frac{b-a}{n}(y_1+y_2+\cdots+y_n) \tag{1-4}
$$
矩形法几何意义：用窄条矩形的面积作为窄条梯形面积的近似值

梯形法

抛物线法

### 性质

$$
\begin{align*}
\tag{0.2} & b = a \Rightarrow \int_a^bf(x)\dif{x} \\
\tag{0.1} & b \gt a \Rightarrow \int_a^bf(x)\dif{x} = -\int_b^af(x)\dif{x} \\
\tag{1} & \int_a^b[{\alpha}f(x) + {\beta}f(x)]\dif{x} = \alpha\int_a^bf(x)\dif{x} + \beta\int_a^bf(x)\dif{x} \\
\tag{2} & a \lt c \lt b, \int_a^bf(x)\dif{x} = \int_a^cf(x)\dif{x} + \int_c^bf(x)\dif{x} \\
\tag{3} & f(x) \equiv 1, \int_a^b1\dif{x} = \int_a^b\dif{x} = b-a \\
\tag{4} & f(x) \geq 0, \int_a^bf(x) \geq 0 \quad (a < b) \\
\tag{4.1} & f(x) \leq g(x), \int_a^bf(x)\dif{x} \leq \int_a^bg(x)\dif{x} \\
\tag{4.2} & f(x) \leq g(x), \int_a^bf(x)\dif{x} \leq \int_a^bg(x)\dif{x} \quad (a < b) \\
\tag{5} & f(x) \left|\int_a^bf(x)\dif{x}\right| \leq \int_a^b|f(x)|\dif{x} \quad (a<b) \\
\end{align*}
$$

定积分中值定理
$$
\int_a^bf(x)\dif{x} = f(\xi)(b-a) \quad (a\leq\xi\leq{b}) \tag{6}
$$

## 第二节 微积分基本公式

### 牛顿-莱布尼茨公式

这个公式揭示了定积分与被积函数的原函数或不定积分之间的联系。

一个连续函数在区间[a,b]上的定积分等于它的任一个原函数在区间上的增量。
$$
\int_a^bf(x)\dif{x} = F(b) - F(a) \tag{2-4}
$$

# 第九章

## 第二节 偏导数

### 一阶偏导

$$
\begin{align*}
& f_x(x_0, y_0) = \lim_{x\rightarrow{x_0}}\frac{f(x_0+\Delta{x}, y_0)-f(x_0, y_0)}{\Delta{x}} \tag{2-2} \\
& f_y(x_0, y_0) = \lim_{y\rightarrow{y_0}}\frac{f(x_0, y_0+\Delta{y})-f(x_0, y_0)}{\Delta{y}} \tag{2-3} \\
\end{align*}
$$

偏导数的记号是一个整体记号，不能看作分子与分母之商。

### 高阶偏导

$$
\begin{align*}
& \frac{\partial}{\partial{x}}\left(\frac{\partial{z}}{\partial{x}}\right) = \frac{\partial^2z}{\partial{x}^2}=f_{xx}(x, y) \\
& \frac{\partial}{\partial{y}}\left(\frac{\partial{z}}{\partial{x}}\right) = \frac{\partial^2z}{\partial{x}\partial{y}}=f_{xy}(x, y) \\
& \frac{\partial}{\partial{x}}\left(\frac{\partial{z}}{\partial{y}}\right) = \frac{\partial^2z}{\partial{y}\partial{x}}=f_{yx}(x, y) \\
& \frac{\partial}{\partial{y}}\left(\frac{\partial{z}}{\partial{y}}\right) = \frac{\partial^2z}{\partial{y}^2}=f_{yy}(x, y) \\
\end{align*}
$$

高阶混合偏导数在偏导连续的条件下与求导的次序无关。

### 拉普拉斯方程

$$
\begin{align*}
& \frac{\partial^2z}{\partial{x}^2} + \frac{\partial^2z}{\partial{y}^2} = 0 \\
& \frac{\partial^2u}{\partial{x}^2} + \frac{\partial^2u}{\partial{y}^2} + \frac{\partial^2u}{\partial{z}^2} = 0 \\
\end{align*}
$$

## 第三节 全微分

### 定义

全增量
$$
\Delta{z} = f(x+\Delta{x}, y+\Delta{y})-f(x,y)
$$
全微分
$$
\begin{align*}
& \dif{z} = \frac{\partial{z}}{\partial{x}}\Delta{x} + \frac{\partial{z}}{\partial{y}}\Delta{y} \\
& \dif{z} = \frac{\partial{z}}{\partial{x}}\dif{x} + \frac{\partial{z}}{\partial{y}}\dif{y} \\
& \dif{u} = \frac{\partial{u}}{\partial{x}}\dif{x} + \frac{\partial{u}}{\partial{y}}\dif{y}  + \frac{\partial{u}}{\partial{z}}\dif{z} \\
\end{align*}
$$

### 充分必要条件

各偏导数存在 <= 可微分

各偏导数连续 => 可微分

## 第四节 多元复合函数的求导法则

### 一元函数与多元函数 复合的情形

$$
u=\varphi(t), v=\psi(t), z = f[\varphi(t),\psi(t)] \\
\frac{\dif{z}}{\dif{t}} = \partial
$$



### 多元函数与多元函数 复合的情形

# 附录

## 自定义LaTeX符号

### 定义dif

参考：https://liam.page/2017/05/01/the-correct-way-to-use-differential-operator/
$$
\newcommand{\dif}{\mathop{}\!\mathrm{d}}\dif
$$




