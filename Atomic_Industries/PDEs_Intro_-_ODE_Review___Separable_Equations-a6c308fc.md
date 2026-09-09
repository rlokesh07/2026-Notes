# Partial Differential Equations (PDEs) Intro

A PDE is an equation involving an unknown function of two or more variables and certain of its partial derivatives.

## Calculus 3

### ODE Example

Hooke's Law:  
\[ F = -kx \]

Newton's Second Law:  
\[ F = m q \]

Combining these:  
\[
a = \frac{d^2 x}{dt^2}, \quad m \frac{d^2 x}{dt^2} = -kx \quad \Rightarrow \quad \frac{d^2 x}{dt^2} = \frac{-kx}{m}
\]

Since acceleration is the second derivative of position.

---

A differential equation contains an unknown function and one or more of its derivatives.

A function \( f \) is a solution if the equation is satisfied when \( y = f(x) \).

For example:  
\[
y = xy, \quad y = f(x), \quad f'(x) = x f(x)
\]

Example solutions:  
\[
y = x^3, \quad y = \frac{xy}{4} + C \quad \leftarrow \text{general solution}
\]

---

### Separable Equations

A separable equation is one where \(\frac{dy}{dx}\) can be factored as a function of \(x\) times a function of \(y\):

\[
\frac{dy}{dx} = f(y) g(x) \quad \text{or} \quad h(y) \, dy = g(x) \, dx
\]

Since the \(y\)'s are grouped together, integrate both sides separately.