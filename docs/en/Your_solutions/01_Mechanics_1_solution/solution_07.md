# Task 07 – Elimination of Time and Acceleration Analysis

## Problem Statement

Given:

$$
x(t) = 2t^2, \qquad y(t) = 3t^3
$$

Determine trajectory, velocity, and acceleration.

## Theory

Eliminate $t$ and compute derivatives.

## Step-by-Step Solution

### Eliminate Parameter

$$
t = \sqrt{\frac{x}{2}}
$$

Substitute:

$$
y = 3 \left(\frac{x}{2}\right)^{3/2}
$$

### Velocity

$$
\vec{v}(t) = (4t, 9t^2)
$$

Magnitude:

$$
|\vec{v}| = \sqrt{16t^2 + 81t^4}
$$

### Acceleration

$$
\vec{a}(t) = (4, 18t)
$$

Magnitude:

$$
|\vec{a}| = \sqrt{16 + 324t^2}
$$

## Final Result

Trajectory:

$$
y = 3 \left(\frac{x}{2}\right)^{3/2}
$$

## Interpretation

Acceleration is not constant due to dependence on $t$.