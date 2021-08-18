---
title: "Jekyll Github 블로그에 MathJax로 수학식 표시하기"
tags:
  - Blog
  - MathJax
  - Jekyll
  - LaTeX
use_math: true
---

$p(X=x|\mathbf{\theta})$


 
<br>

$$
\begin{align}
log_p(Y|\theta,X) &= log\prod_n p(y_n|\theta,~\mathbf{x}_n)\\
&=\sum_n log p(y_n|\theta, \mathbf{x}_n)\\
&=\sum_n log\bigg(\frac{1}{\sqrt{2\pi\sigma^2}}exp\bigg(-\frac{(y_n-\theta^\top\mathbf{x}_n)^2}{2\sigma^2}\bigg)\bigg)\\
&=\sum_n log \frac{1}{\sqrt{2\pi\sigma^2}}+\sum_n log ~ exp \bigg(-\frac{(y_n-\theta^\top\mathbf{x}_n)^2}{2\sigma^2}\bigg)\\
&=\sum_n log \frac{1}{\sqrt{2\pi\sigma^2}}+\sum_n\bigg(-\frac{(y_n-\theta^\top\mathbf{x}_n)^2}{2\sigma^2}\bigg)\\
&=constant+\frac{1}{2\sigma^2}\sum_n(-(y_n-\theta^\top\mathbf{x})^2)
\end{align}
$$
