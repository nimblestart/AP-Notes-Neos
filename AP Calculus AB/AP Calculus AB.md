#### 1. Limits and Continuity
- **Limit Definition**: $\lim_{x \to a} f(x) = L$
- **Limit Laws**:
  - Sum/Difference: $\lim_{x \to a} [f(x) \pm g(x)] = \lim_{x \to a} f(x) \pm \lim_{x \to a} g(x)$
  - Product: $\lim_{x \to a} [f(x) \cdot g(x)] = \lim_{x \to a} f(x) \cdot \lim_{x \to a} g(x)$
  - Quotient: $\lim_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim_{x \to a} f(x)}{\lim_{x \to a} g(x)}$ (if $\lim_{x \to a} g(x) \neq 0$)
- **Squeeze Theorem**: If $f(x) \leq g(x) \leq h(x)$ and $\lim_{x \to a} f(x) = \lim_{x \to a} h(x) = L$, then $\lim_{x \to a} g(x) = L$.
- **Continuity**: A function $f(x)$ is continuous at $x = a$ if: $\lim_{x \to a} f(x) = f(a)$
#### 2. Derivatives
- **Definition of Derivative**: $f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}$
- **Basic Derivative Rules**:
  - Power Rule: $\frac{d}{dx} [x^n] = nx^{n-1}$
  - Constant Rule: $\frac{d}{dx} [c] = 0$
  - Sum/Difference: $\frac{d}{dx} [f(x) \pm g(x)] = f'(x) \pm g'(x)$
  - Product Rule: $\frac{d}{dx} [f(x) \cdot g(x)] = f'(x)g(x) + f(x)g'(x)$
  - Quotient Rule: $\frac{d}{dx} \left[\frac{f(x)}{g(x)}\right] = \frac{f'(x)g(x) - f(x)g'(x)}{[g(x)]^2}$
  - Chain Rule: $\frac{d}{dx} [f(g(x))] = f'(g(x)) \cdot g'(x)$
- **Derivatives of Trigonometric Functions**:
  - $\frac{d}{dx} [\sin x] = \cos x$
  - $\frac{d}{dx} [\cos x] = -\sin x$
  - $\frac{d}{dx} [\tan x] = \sec^2 x$
- **Derivatives of Exponential and Logarithmic Functions**:
  - $\frac{d}{dx} [e^x] = e^x$
  - $\frac{d}{dx} [\ln x] = \frac{1}{x}$
- **Implicit Differentiation**: Differentiate both sides of an equation with respect to $x$ and solve for $\frac{dy}{dx}$.
#### 3. Applications of Derivatives
- **Tangent Line Equation**: $y = f(a) + f'(a)(x - a)$
- **Mean Value Theorem**: If $f(x)$ is continuous on $[a, b]$ and differentiable on $(a, b)$, then there exists $c \in (a, b)$ such that: $f'(c) = \frac{f(b) - f(a)}{b - a}$
- **Increasing/Decreasing Functions**:
  - If $f'(x) > 0$, $f(x)$ is increasing.
  - If $f'(x) < 0$, $f(x)$ is decreasing.
- **Concavity**:
  - If $f''(x) > 0$, $f(x)$ is concave up.
  - If $f''(x) < 0$, $f(x)$ is concave down.
- **Optimization**: Find critical points ($f'(x) = 0$ or undefined) and use the First or Second Derivative Test to determine maxima/minima.
#### 4. Integrals
- **Antiderivatives**:  $\int f(x) \, dx = F(x) + C$ where $F'(x) = f(x)$
- **Basic Integration Rules**:
  - Power Rule: $\int x^n \, dx = \frac{x^{n+1}}{n+1} + C$ (for $n \neq -1$)
  - $\int e^x \, dx = e^x + C$
  - $\int \frac{1}{x} \, dx = \ln|x| + C$
- **Definite Integral**: $\int_a^b f(x) \, dx = F(b) - F(a)$
- **Fundamental Theorem of Calculus**: $\frac{d}{dx} \left[ \int_a^x f(t) \, dt \right] = f(x)$
- **Substitution Rule**: $\int f(g(x))g'(x) \, dx = \int f(u) \, du$ where $u = g(x)$
#### 5. Applications of Integrals
- **Area Under a Curve**: $\text{Area} = \int_a^b f(x) \, dx$
- **Area Between Two Curves**:  $\text{Area} = \int_a^b [f(x) - g(x)] \, dx$ where $f(x) \geq g(x)$
- **Volume of Revolution**:
  - Disk Method: $V = \pi \int_a^b [f(x)]^2 \, dx$
  - Washer Method: $V = \pi \int_a^b \left( [f(x)]^2 - [g(x)]^2 \right) \, dx$
- **Average Value of a Function**: $\text{Average Value} = \frac{1}{b - a} \int_a^b f(x) \, dx$
#### 6. Differential Equations
- **Separation of Variables**: $\frac{dy}{dx} = f(x)g(y) \implies \int \frac{1}{g(y)} \, dy = \int f(x) \, dx$
- **Exponential Growth/Decay**: $\frac{dy}{dt} = ky \implies y = y_0 e^{kt}$
#### 7. Miscellaneous
- **L’Hôpital’s Rule**:
  If $\lim_{x \to a} \frac{f(x)}{g(x)}$ is $\frac{0}{0}$ or $\frac{\infty}{\infty}$, then:
  $\lim_{x \to a} \frac{f(x)}{g(x)} = \lim_{x \to a} \frac{f'(x)}{g'(x)}$
- **Intermediate Value Theorem**: If $f(x)$ is continuous on $[a, b]$ and $k$ is between $f(a)$ and $f(b)$, then there exists $c \in (a, b)$ such that $f(c) = k$.
