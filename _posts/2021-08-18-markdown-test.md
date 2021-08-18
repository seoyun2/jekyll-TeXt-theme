---
title: "Jekyll Github 블로그에 MathJax로 수학식 표시하기"
tags:
  - Blog
  - MathJax
  - Jekyll
  - LaTeX
use_math: true
---

likelihood를 최대화하는 파라미터를 $\mathbf{\theta}_{ML}$(ML: maximum likelihood)이라고 하면,
 
<br>

$$\begin{align*}
\mathbf{\theta}_{ML}&=arg~\max_\mathbf{\theta}~log~p(Y|\theta, X)\\
&=arg~\max_\mathbf{\theta}\bigg(\frac{1}{2\sigma^2}\sum_n(-(y_n-\theta^\top\mathbf{x}_n)^2)+constatnt\bigg)
\end{align*}$$
 
<br>

$\mathbf{\theta}$와 관계없는 부분을 빼고 식을 정리하면 다음과 같습니다.
 
<br>

손실 함수를 최소화하는 관점에서, log likelihood를 최대화하는 대신 negative log likelihood $(-\log p(Y\|\mathbf{\theta}, X))$를 최소화하는 식으로 나타내기도 합니다.
