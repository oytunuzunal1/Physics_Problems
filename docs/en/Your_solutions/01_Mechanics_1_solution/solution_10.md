# Task 10 – Kinematics in 3D

## Problem Statement

Given:

$$
\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)
$$

Find trajectory and path length.

## Theory

Helical motion combines circular motion with linear translation.

## Step-by-Step Solution

### Trajectory

Eliminate $t$:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

Thus, projection is an ellipse.

### Velocity

$$
\vec{v}(t) = (-a\omega \sin(\omega t), b\omega \cos(\omega t), b)
$$

Speed:

$$
|\vec{v}| = \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}
$$

### Path Length

$$
s = \int_0^{t_0} |\vec{v}(t)| dt
$$

## Final Result

Trajectory is a helix with elliptical base.

## Interpretation

Special case $a=b$ gives circular helix.