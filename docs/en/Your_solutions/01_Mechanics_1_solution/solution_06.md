 # Task 06 – Variable Velocity

## Problem Statement

Given velocity:

$$
v(t) = t^2 + 2t - 5
$$

Initial condition:

$$
x(0) = 4
$$

Find position and acceleration at $t = 3$.

## Theory

Position is obtained by integration:

$$
x(t) = \int v(t) dt
$$

Acceleration is the derivative:

$$
a(t) = \frac{dv}{dt}
$$

## Step-by-Step Solution

### Position Function

$$
x(t) = \int (t^2 + 2t - 5) dt
$$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

Apply initial condition:

$$
4 = C
$$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

### Position at $t=3$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 7
$$

### Acceleration

$$
a(t) = 2t + 2
$$

$$
a(3) = 8
$$

## Final Result

- Position: $x(3) = 7$
- Acceleration: $a(3) = 8 \, \text{m/s}^2$

## Interpretation

The object experiences increasing acceleration due to the quadratic velocity term.