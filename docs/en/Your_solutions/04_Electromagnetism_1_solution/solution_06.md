# Task 06 – Electric Field of Two Charges

## Problem Statement

Charges:
- $+q$ at $(-a,0)$
- $+2q$ at $(a,0)$

Find $\vec{E}(x,y)$ and special conditions.

## Theory

Electric field:

$$
\vec{E} = k \frac{q}{r^2} \hat{r}
$$

## Step-by-Step Solution

General position:

$$
\vec{E} = \vec{E}_1 + \vec{E}_2
$$

Components:

$$
E_x = kq \left( \frac{x+a}{r_1^3} + \frac{2(x-a)}{r_2^3} \right)
$$

$$
E_y = kq \left( \frac{y}{r_1^3} + \frac{2y}{r_2^3} \right)
$$

Where:

$$
r_1 = \sqrt{(x+a)^2 + y^2}, \quad r_2 = \sqrt{(x-a)^2 + y^2}
$$

### Zero field condition

Occurs where vector sum cancels:

$$
\vec{E} = 0
$$

Requires solving nonlinear equations.

### Numerical example

Given:

$$
a = 0.2, \quad y = 0.3, \quad q = 2 \times 10^{-6}
$$

Field can be computed numerically.

### Limit $y \gg a$

$$
\vec{E} \approx k \frac{3q}{y^2} \hat{y}
$$

## Final Result

Field behaves like a single charge $3q$ far away.

## Interpretation

At large distances, system behaves like a point charge equal to total charge.