# Markdown and LaTeX introduction

Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML). A Markdown document could contain chunks of embedded graphics, source codes and LaTex formula. LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. A basic knowledge about Markdown and LaTeX could let to create HTML documents such as weblogs or reports very easily. This tutorial provides a quick reference to use Markdown and LaTeX.

# Markdown
The following provides a quick reference to the most commonly used Markdown syntax.

## Headers
### H3
#### H4
##### H5
###### H6

# Emphasis

*Italic* and **Bold**

~~Scratched Text~~

superscript^2^

Markdown doesn't support underline, but we can use <u>HTML Text</u> instead. Also, <b>we</b> can <i>render</i> almost any <span style="color:red;">HTML</span> code that we &nbsp; <kbd>like</kbd> &nbsp; such as superscript<sup>2</sup>.

For manual line or page breaks, we can use following HTML and CSS codes:

Line breaks: `<br />`, Print breaks:
`<p style="page-break-after:always;"></p>`

Lists

- Item 1
- Item 2
    - Item 2a (2 tabs)
    - Item 2b
        - Item 2b-1 (4 tabs)
        - Item 2b-2

1. Item 1
2. Item 2
3. Item 3
    - Item 3a
    - Item 3b

Links

[Github](http://www.github.com/)

Images

<p align="center">
![logo](https://www.raspberrypi.org/app/uploads/2018/03/RPi-Logo-Reg-SCREEN-199x250.png "Raspberry pi")
</p>
Note that here we used an HTML code to align center the image. Also, we can use HTML to add more styles, for example:

<p align="center">
<img src="https://www.raspberrypi.org/app/uploads/2018/03/RPi-Logo-Reg-SCREEN-199x250.png" alt="Raspberry pi" style="width:20%; border:0;">
</p>

Quotes

> Imagination is more important than knowledge.
>
> Albert Einstein

Hlines

Use three dashes `---` to draw an horizontal line like:

---


# Tables

1st Header|2nd Header|3rd Header
---|:---:|---: 
col 1 is|left-aligned|1
col 2 is|center-aligned|2
col 3 is|right-aligned|3

Note that we can use HTML styles to hide tables’ overflow by putting them in a division like:

<div "margin-bottom: 1rem; overflow-x: auto;">
...
</div>

Also, we can use overflow-x: scroll to always scroll or overflow-x: hidden to hide them compeletely.

Code blocks

In Markdown, we can simply add plain code blocks to display (not evaluating) by inserting triple back quote i.e. ```. For example:

```
norm = function(x) {
  sqrt(x%*%x)
}
norm(1:4)
```

` ``r
norm <- function(x) {
  sqrt(x%*%x)
}
norm(1:4)
` ``

For inline plain codes use single back quote before and after the code, for example we defined this codes here in this way.

YAML header

At the top of a Markdown document, we can insert the following meta data such that:

---
title: "Page Title"
subtitle: "Page sub-title"
author: "Author name"
description: "This is a test"
institute: "MU"
date: "20/02/2020"
abstract: "YAML"
keywords: 
  - key1
  - key2
tags:
  - tag1
  - tag2
---

Mathematical formula
We can use LaTeX to write mathematical equations in Markdown. To write inline LaTeX formula use a single \$ before and after the equation and use a double \$ to display equations.

LaTeX

The following provides a quick reference of the most commonly used LaTeX syntax. You may find a more extensive references about mathematical formulas at LaTeX Wikibooks.

LaTeX equations

Inline equation: $equation$

Display equation: $$equation$$

Operators

- $x + y$
- $x - y$
- $x \times y$ 
- $x \div y$
- $\dfrac{x}{y}$
- $\sqrt{x}$

Symbols

- $\pi \approx 3.14159$
- $\pm \, 0.2$
- $\dfrac{0}{1} \neq \infty$
- $0 < x < 1$
- $0 \leq x \leq 1$
- $x \geq 10$
- $\forall \, x \in (1,2)$
- $\exists \, x \notin [0,1]$
- $A \subset B$
- $A \subseteq B$
- $A \cup B$
- $A \cap B$
- $X \implies Y$
- $X \impliedby Y$
- $a \to b$
- $a \longrightarrow b$
- $a \Rightarrow b$
- $a \Longrightarrow b$
- $a \propto b$

- $\bar a$
- $\tilde a$
- $\breve a$
- $\hat a$
- $a^ \prime$
- $a^ \dagger$
- $a^ \ast$
- $a^ \star$
- $\mathcal A$
- $\mathrm a$
- $\cdots$
- $\vdots$
- $\#$
- $\$$
- $\%$
- $\&$
- $\{ \}$
- $\_$

Space

Horizontal space: \quad
Large horizontal space: \qquad
Small space: \,
Medium space: \:
Large space: \;
Negative space: \!

Greek alphabets
Small Letter	Capital Letter	Alternative
 $\alpha	
 A	
 \beta	
 B	
 \gamma	
 \Gamma	
 \delta	
 \Delta	
 \epsilon	
 E	
 \varepsilon
 \zeta	
 Z	
 \eta	
 H	
 \theta	
 \Theta	
 \vartheta
 \zeta	
 I	
 \kappa	
 K	
 \varkappa
 \lambda	
 \Lambda	
 \mu	
 M	
 \nu	
 N	
 \xi	
 \Xi	
 \omicron	
 O	
 \pi	
 \Pi	
 \varpi
 \rho	
 P	
 \varrho
 \sigma	
 \Sigma	
 \varsigma
 \tau	
 T	
 \upsilon	
 \Upsilon	
 \phi	
 \Phi	
 \varphi
 \chi	
 X	
 \psi	
 \Psi	
 \omega	
 \Omega$

 Equations

 $$\mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \}$$

 $$\forall \; x \in X \quad \exists \; y \leq \epsilon$$

$$\color{blue}{X \sim Normal \; (\mu,\sigma^2)}$$
 

$$P \left( A=2 \, \middle| \, \dfrac{A^2}{B}>4 \right)$$
 

$$f(x) = x^2 - x^\frac{1}{\pi}$$

$$f(X,n) = X_n + X_{n-1}$$

$$f(x) = \sqrt[3]{2x} + \sqrt{x-2}$$
 
 

$$\mathrm{e} = \sum_{n=0}^{\infty} \dfrac{1}{n!}$$
 

$$\prod_{i=1}^{n} x_i - 1$$
 
 

$$\lim_{x \to 0^+} \dfrac{1}{x} = \infty$$

$$\int_a^b y \: \mathrm{d}x$$

$$\log_a b = 1$$
 

$$\max(S) = \max_{i:S_i \in S} S_i$$
 

$$\dfrac{n!}{k!(n-k)!} = \binom{n}{k}$$
 

$$\text{$\dfrac{b}{a+b}=3, \:$ therefore we can set $\: a=6$}$$

Functions

$$
f(x)=
\begin{cases}
1/d_{ij} & \quad \text{when $d_{ij} \leq 160$}\\ 
0 & \quad \text{otherwise}
\end{cases}
$$

Matrices

$$
\begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix}
$$
 
 
 
 
 
 
 

$$
M = 
\begin{bmatrix}
\frac{5}{6} & \frac{1}{6} & 0 \\[0.3em]
\frac{5}{6} & 0 & \frac{1}{6} \\[0.3em]
0 & \frac{5}{6} & \frac{1}{6}
\end{bmatrix}
$$
  
 

$$ 
M =
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
$$
  
 

$$ 
M =
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
\begin{pmatrix}
1 & 0 \\
0 & 1
\end{pmatrix}
$$
 

$$
A_{m,n} = 
\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix}
$$

Font sizes

$\Huge Hello!$
$\huge Hello!$
$\LARGE Hello!$
$\Large Hello!$
$\large Hello!$
$\normalsize Hello!$
$\small Hello!$
$\scriptsize Hello!$
$\tiny Hello!$

$$\small \text{Font size is small, eg. $\sum{x_i = 10}$}$$


