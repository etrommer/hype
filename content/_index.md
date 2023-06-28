+++
+++
The [Hyde](https://github.com/getzola/hyde) for [Zola](https://getzola.org) derivative with a few extra features (heavily inspired by [Hydeout](https://github.com/fongandrew/hydeout)):
- has a dedicated welcome page
- moves [blog](/blog) to a subsection
- delightful social icons via [fontawesome](https://fontawesome.com)
- light color gradient in sidebar
- render maths via [KaTeX](https://katex.org):
{% katex() %}
\begin{aligned}
\hat{f} (\xi) &=\int_{-\infty}^{\infty}f(x)e^{-2\pi ix\xi}dx\\
A &= \begin{bmatrix}a&b\\c&d \end{bmatrix}
\end{aligned}
{% end %}
- also works for inline \\(e = m \cdot c^2 \\) equations
