# Vector Functions

\[
r(t) = c f(t), \quad g(t), \quad h(t)^2 = f(t), \quad g(t), \quad j + h(t)k
\]

\[
\frac{dr}{dt} = r'(t) = \lim_{h \to 0} \frac{r(t+h) - r(t)}{h}
\]

\[
r'(t) = f'(t), \quad g'(t), \quad j + h'(t)k
\]

Same 4 integrals apply.

## Partial Derivatives

A function \( f \) is a rule that assigns a value \( a \) to each pair of real numbers or \( a \in \mathbb{R}^d \) in the domain.

\[
\lim_{(x,y) \to (a,b)} f(x,y) = L \quad \text{if} \quad \epsilon \to 0, \quad s \in \mathbb{R}^d
\]

If \((x,y) \to 0\) and \(0 < v(x - a) \to y - 0\),

then \( f(x,y) = L \).

\[
f_x(x,y) = \lim_{h \to 0} \frac{f(x+h,y) - f(x,y)}{h}
\]

## Chain Rule

Variation 2:

\[
\frac{dz}{dt} = \frac{\partial f}{\partial x} \cdot \frac{dx}{dt} + \frac{\partial f}{\partial y} \cdot \frac{dy}{dt}
\]

When \( x = g(t) \), \( y = h(t) \), and the variables are different, then the chain rule applies as above.