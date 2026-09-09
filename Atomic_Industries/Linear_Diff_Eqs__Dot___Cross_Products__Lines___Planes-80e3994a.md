# Linear Differential Equations, Dot & Cross Products, Lines & Planes

## Linear Differential Equations

A first-order linear differential equation has the form:
\[
\frac{\mathrm{d}y}{\mathrm{d}x} + P(x)y = Q(x)
\]
where \(P(x)\) and \(Q(x)\) are continuous functions.

Example:
\[
x y^2 + y = 2x
\]

Another example:
\[
\frac{\mathrm{d}y}{\mathrm{d}x} + \frac{y}{x} = z
\]

### Solving Linear Differential Equations

To solve linear differential equations, multiply both sides by the integrating factor:
\[
e^{\int P(x) \, dx}
\]
and then differentiate.

---

## Dot and Cross Products

### Dot Product

For vectors \(a\) and \(b\):
\[
\frac{\mathrm{d} \cdot b}{1a(1b)} = \cos \theta
\]
(This appears to be an OCR artifact; the dot product formula is \(a \cdot b = |a||b|\cos \theta\).)

### Cross Product

To find a vector \(c\) that is perpendicular to both \(a\) and \(b\), the dot products of \(c\) with \(a\) and \(b\) must be zero:
\[
c \cdot a = 0, \quad c \cdot b = 0
\]

The cross product vector \(c = a \times b\) is given by:
\[
c = \langle a_2 b_3 - a_3 b_2, \quad a_3 b_1 - a_1 b_3, \quad a_1 b_2 - a_2 b_1 \rangle
\]

---

## Lines and Planes

### Line Equation

A line passing through point \(r_0\) with direction vector \(b\) is:
\[
r = r_0 + t b
\]
where \(t\) is a scalar parameter.

### Plane Equation

The equation of a plane with normal vector \(\mathbf{n} = (a, b, c)\) passing through point \((x_0, y_0, z_0)\) is:
\[
a(x - x_0) + b(y - y_0) + c(z - z_0) = 0
\]

Alternatively, the plane can be written as:
\[
d + a x + b y + c z = 0
\]
where \(d\) is a constant.

The normal vector \(\mathbf{n} = (a, b, c)\) is perpendicular to the plane.