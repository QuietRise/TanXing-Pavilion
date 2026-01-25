---
title: 高等数学（上）必背公式与记忆技巧整理
date: 2026-01-24T01:47:58+08:00
categories:
    - 数学
tags:
    - 笔记
mathjax: true
---

## 1. 导数公式

### 基本求导公式

<div align="center">

$$
(C)' = 0 \qquad (x^\mu)' = \mu x^{\mu-1}
$$
</div>

<div align="center">

$$
(\sin x)' = \cos x \qquad (\cos x)' = -\sin x
$$
</div>

<div align="center">

$$
(\tan x)' = \sec^2 x \qquad (\cot x)' = -\csc^2 x
$$
</div>

<div align="center">

$$
(\sec x)' = \sec x \tan x \qquad (\csc x)' = -\csc x \cot x
$$
</div><!--more-->

<div align="center">

$$
(a^x)' = a^x \ln a \qquad (e^x)' = e^x
$$
</div>

<div align="center">

$$
(\log_a x)' = \frac{1}{x \ln a} \qquad (\ln x)' = \frac{1}{x}
$$
</div>

<div align="center">

$$
(\arcsin x)' = \frac{1}{\sqrt{1-x^2}} \qquad (\arccos x)' = -\frac{1}{\sqrt{1-x^2}}
$$
</div>

<div align="center">

$$
(\arctan x)' = \frac{1}{1+x^2} \qquad (\text{arccot } x)' = -\frac{1}{1+x^2}
$$
</div>

### 求导法则

<div align="center">

$$
(u \pm v)' = u' \pm v' \qquad (uv)' = u'v + uv'
$$
</div>

<div align="center">

$$
y'_x = \frac{1}{x'_y} \qquad y'_x = y'_u \cdot u'_x
$$
</div>

**商法则：**
<div align="center">

$$
\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}
$$
</div>

---

## 2. 常用等价无穷小

**条件：当 $x \to 0$ 时**

<div align="center">

$$
\sin x \sim x \qquad \tan x \sim x
$$
</div>

<div align="center">

$$
\arcsin x \sim x \qquad \arctan x \sim x
$$
</div>

<div align="center">

$$
e^x - 1 \sim x \qquad \ln(1+x) \sim x
$$
</div>

<div align="center">

$$
1 - \cos x \sim \frac{1}{2}x^2 \qquad (1+x)^\alpha - 1 \sim \alpha x
$$
</div>

<div align="center">

$$
a^x - 1 \sim x \ln a \qquad \log_a(1+x) \sim \frac{x}{\ln a}
$$
</div>

---

## 3. 积分公式表

### 基本积分公式

<div align="center">

$$
\int k \, dx = kx + C \qquad \int x^\mu \, dx = \frac{x^{\mu+1}}{\mu+1} + C
$$
</div>

<div align="center">

$$
\int \frac{1}{x} \, dx = \ln|x| + C \qquad \int e^x \, dx = e^x + C
$$
</div>

<div align="center">

$$
\int \cos x \, dx = \sin x + C \qquad \int \sin x \, dx = -\cos x + C
$$
</div>

<div align="center">

$$
\int \sec^2 x \, dx = \tan x + C \qquad \int \csc^2 x \, dx = -\cot x + C
$$
</div>

<div align="center">

$$
\int \sec x \tan x \, dx = \sec x + C \qquad \int \csc x \cot x \, dx = -\csc x + C
$$
</div>

<div align="center">

$$
\int a^x \, dx = \frac{a^x}{\ln a} + C \qquad \int \frac{1}{1+x^2} \, dx = \arctan x + C
$$
</div>

<div align="center">

$$
\int \frac{1}{\sqrt{1-x^2}} \, dx = \arcsin x + C
$$
</div>

### 拓展积分公式

<div align="center">

$$
\int \tan x \, dx = -\ln|\cos x| + C \qquad \int \cot x \, dx = \ln|\sin x| + C
$$
</div>

<div align="center">

$$
\int \sec x \, dx = \ln|\sec x + \tan x| + C \qquad \int \csc x \, dx = \ln|\csc x - \cot x| + C
$$
</div>

<div align="center">

$$
\int \frac{dx}{a^2+x^2} = \frac{1}{a} \arctan \frac{x}{a} + C \qquad \int \frac{dx}{\sqrt{a^2-x^2}} = \arcsin \frac{x}{a} + C
$$
</div>

**长公式：**

<div align="center">

$$
\int \frac{1}{x^2-a^2} \, dx = \frac{1}{2a} \ln \left| \frac{x-a}{x+a} \right| + C
$$
</div>

<div align="center">

$$
\int \frac{1}{\sqrt{x^2+a^2}} \, dx = \ln(x + \sqrt{x^2+a^2}) + C
$$
</div>

<div align="center">

$$
\int \frac{1}{\sqrt{x^2-a^2}} \, dx = \ln|x + \sqrt{x^2-a^2}| + C
$$
</div>

---

## 4. 常见泰勒公式 (麦克劳林)

<div align="center">

$$
e^x = 1 + x + \frac{x^2}{2!} + \cdots + \frac{x^n}{n!} + o(x^n)
$$
</div>

<div align="center">

$$
\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots + (-1)^{m-1}\frac{x^{2m-1}}{(2m-1)!} + o(x^{2m})
$$
</div>

<div align="center">

$$
\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots + (-1)^m\frac{x^{2m}}{(2m)!} + o(x^{2m+1})
$$
</div>

<div align="center">

$$
\ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \cdots + (-1)^{n-1}\frac{x^n}{n} + o(x^n)
$$
</div>

<div align="center">

$$
(1+x)^\alpha = 1 + \alpha x + \frac{\alpha(\alpha-1)}{2!}x^2 + \cdots + \frac{\alpha(\alpha-1)\cdots(\alpha-n+1)}{n!}x^n + o(x^n)
$$
</div>

---

## 5. 三角恒等变换

### 1. 和角与差角公式

<div align="center">

$$
\sin(\alpha \pm \beta) = \sin\alpha\cos\beta \pm \cos\alpha\sin\beta
$$
</div>
<div align="center">

$$
\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta
$$
</div>
<div align="center">

$$
\tan(\alpha \pm \beta) = \frac{\tan\alpha \pm \tan\beta}{1 \mp \tan\alpha\tan\beta}
$$
</div>

### 2. 二倍角公式

<div align="center">

$$
\sin 2\alpha = 2\sin\alpha\cos\alpha \qquad \tan 2\alpha = \frac{2\tan\alpha}{1 - \tan^2\alpha}
$$
</div>

<div align="center">

$$
\cos 2\alpha = \cos^2\alpha - \sin^2\alpha = 2\cos^2\alpha - 1 = 1 - 2\sin^2\alpha
$$
</div>

### 3. 半角公式

<div align="center">

$$
\sin^2\frac{\alpha}{2} = \frac{1-\cos\alpha}{2} \qquad \cos^2\frac{\alpha}{2} = \frac{1+\cos\alpha}{2}
$$
</div>

<div align="center">

$$
\tan\frac{\alpha}{2} = \pm\sqrt{\frac{1-\cos\alpha}{1+\cos\alpha}} = \frac{\sin\alpha}{1+\cos\alpha} = \frac{1-\cos\alpha}{\sin\alpha}
$$
</div>

### 4. 万能公式 (令 $t = \tan\frac{\alpha}{2}$)

<div align="center">

$$
\sin\alpha = \frac{2t}{1+t^2} \qquad \cos\alpha = \frac{1-t^2}{1+t^2}
$$
</div>

<div align="center">

$$
\tan\alpha = \frac{2t}{1-t^2}
$$
</div>

### 5. 积化和差

<div align="center">

$$
\sin\alpha\cos\beta = \frac{1}{2}[\sin(\alpha+\beta) + \sin(\alpha-\beta)]
$$
</div>
<div align="center">

$$
\cos\alpha\sin\beta = \frac{1}{2}[\sin(\alpha+\beta) - \sin(\alpha-\beta)]
$$
</div>
<div align="center">

$$
\cos\alpha\cos\beta = \frac{1}{2}[\cos(\alpha+\beta) + \cos(\alpha-\beta)]
$$
</div>
<div align="center">

$$
\sin\alpha\sin\beta = -\frac{1}{2}[\cos(\alpha+\beta) - \cos(\alpha-\beta)]
$$
</div>

### 6. 和差化积

<div align="center">

$$
\sin A + \sin B = 2\sin\frac{A+B}{2}\cos\frac{A-B}{2}
$$
</div>
<div align="center">

$$
\sin A - \sin B = 2\cos\frac{A+B}{2}\sin\frac{A-B}{2}
$$
</div>
<div align="center">

$$
\cos A + \cos B = 2\cos\frac{A+B}{2}\cos\frac{A-B}{2}
$$
</div>
<div align="center">

$$
\cos A - \cos B = -2\sin\frac{A+B}{2}\sin\frac{A-B}{2}
$$
</div>