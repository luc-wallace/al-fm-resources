# Further Maths Formulae

Below is a list of FM formulae that is not included in the formula book. 

### Volumes of revolution

$$
\Large
\begin{flalign}
y = f(x)&&
\end{flalign}
$$

Rotation $2\pi$ radians about the x-axis between $x = a$ and $x = b$:

$$
\Large
\begin{flalign}
V = \int_{a}^{b} y^2 \ dx&&
\end{flalign}
$$

Rotation $2\pi$ radians about the y-axis between $y = a$ and $y = b$:

$$
\Large
\begin{flalign}
V = \int_{a}^{b} x^2 \ dy&&
\end{flalign}
$$

In parametric form, where $y = f(t)$ and $x = g(t)$:
$$
\Large
\begin{flalign}
V = \int_{a}^{b} y^2 \frac{dx}{dt} \ dt&&
\end{flalign}
$$

### Simpson's rule

$$
\Large
\begin{flalign}
\int_{a}^{b}y \ dx \ = \frac{h}{3} [ y_0 + y_n + 4(y_1+y_3+ \dots + y_{n-1}) + 2(y_2+y_4+\dots+y_{n-2})]&&
\end{flalign}
$$
where 
$$
\Large
\begin{flalign}
h = \frac{b - a}{2}&&
\end{flalign}
$$

### Taylor series solutions to differential equations

$$
\Large
\begin{flalign}
y \approx y_0+(x-x_0)\frac{dy}{dx}|_{x_0} + \frac{(x-x_0)^2}{2!}\frac{d^2y}{dx^2}|_{x_0} + \frac{(x-x_0)^3}{3!}\frac{d^3y}{dx^3}|_{x_0}  + \ \dots&& \end{flalign}
$$
where
$$\Large \begin{flalign} \frac{dy}{dx} = f(x,y)&&\ \end{flalign}$$

### Leibnitz' theorem

$$
\Large
\begin{flalign}
\frac{d^n}{dx^n} (u v) = \sum_{r=0}^{n} \binom{n}{r} u^{(r)} v^{(n-r)}&&
\end{flalign}
$$

where
$$
\Large
\begin{flalign}
y = uv&&
\end{flalign}
$$

### L'hôpital's rule

where
$$
\Large
\begin{flalign}
\lim_{x \to \infty} \frac{f(x)}{g(x)}=\frac{\infty}{\infty}&&
\end{flalign}
$$
or

$$
\Large
\begin{flalign}
\lim_{x \to \infty} \frac{f(x)}{g(x)}=\frac{0}{0}&&
\end{flalign}
$$

then
$$
\Large
\begin{flalign}
\lim_{x \to \infty} \frac{f(x)}{g(x)}=\lim_{x \to \infty} \frac{f'(x)}{g'(x)}
&&
\end{flalign}
$$
### Weierstrass subsitution

where $$
\Large
\begin{flalign}
t = tan(\frac{x}{2})&&
\end{flalign}
$$then
$$
\Large
\begin{flalign}
sin(x) = \frac{2t}{1+t^2}&&
\end{flalign}
$$$$
\Large
\begin{flalign}
cos(x) = \frac{1-t^2}{1+t^2}&&
\end{flalign}
$$
$$
\Large
\begin{flalign}
tan(x) = \frac{2t}{1-t^2}&&
\end{flalign}
$$