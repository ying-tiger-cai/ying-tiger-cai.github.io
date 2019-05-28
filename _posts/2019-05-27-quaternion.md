---
layout: post
title:  Introduction of Quaternions
categories: VIO
tags: quaternion
keywords: quaternion,
description: fundamentals of quaternion number system
---

### <center>Introduction of Quaternions</center>  
Last modified: 2019-05-27 21:00
<br>
### 1 Quaternion definition and properties
Consider two complex numbers $$A=a+bi$$ and $$C=c+di$$, then construct $$Q=A+Cj$$. $$Q=a+bi+cj+dij=a+bi+cj+dk \in \mathbb{H}$$, where $$k\triangleq ij$$, and $$\mathbb{H}$$ is the space of __quaternions__.  
$$\left\{ a,b,c,d \right\} \in \mathbb{R}$$, and $$\left\{ i, j, k \right\}$$ are three imaginary unit numbers defined so that:
\$\$i^{2}=j^{2}=k^{2}=ijk=-1\$\$    
Hence, we can derive: 
<center>$$ij=-ji=k$$ $$jk=-kj=i$$ $$ki=-ik=j$$</center>  
Note that real, imaginary, and complex numbers are indeed quaternions. $$Q=a \in \mathbb{R} \subset \mathbb{H}$$, $$Q=bi \in \mathbb{I} \subset \mathbb{H}$$, $$Q=a+bi \in \mathbb{Z} \subset \mathbb{H}$$.  
Like the pure imaginary numbers in complex numbers, __pure quaternions__ are defined as a subspace of $$\mathbb{H}$$, and may note $$\mathbb{H}_{p}=Im(\mathbb{H})$$.  
<center>$$Q=bi+cj+dk \in \mathbb{H}_{p} \subset \mathbb{H}$$.</center>

<br>
#### Level 4: Images  
```
![Lenna](/assets/img/Lenna.png)
```
![Lenna](/assets/img/Lenna.png)

```
<img src="/assets/img/Lenna.png" alt="Lenna">
```
<img src="/assets/img/Lenna.png" alt="Lenna">

```
<center><img src="/assets/img/Lenna.png" alt="Lenna" height="300"></center>
```
<center><img src="/assets/img/Lenna.png" alt="Lenna" height="300"></center>

```
[Blog of ying-tiger-cai](http://ying-tiger-cai.github.io)
```
[Blog of ying-tiger-cai](http://ying-tiger-cai.github.io)

```
[Other post](/2019/05/19/git-cheat-sheet.html)
```
[Other post](/2019/05/19/git-cheat-sheet.html)

```
##### Level 5: Math Equations
```
##### Level 5: Math Equations
```
This is \$\$i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1\$\$ and $$i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1$$.
```
This is \$\$i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1\$\$ and $$i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1$$.  

Same equation:  
```
\\[
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
\\]
```
\\[
i={\sqrt[{n}]{\left({\frac {FV}{PV}}\right)}}-1
\\]

This is another example:
```
$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$
```
$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

```
Try linline like this:
$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$
```
Try inline like this:
$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$

```
再测试一下行内公式$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$，也可以正常显示，搞定。  
```
再测试一下行内公式$$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$，也可以正常显示，搞定。  

```
<br>
```
<br>
Jekyll also offers powerful support for code snippets:
````
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}
````
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

### Level 3: References and hyper links
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

