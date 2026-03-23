# Solutions goes here
# Task 01 – Projectile Motion

## Problem Statement

A projectile is launched from the ground with initial speed $v_0 = 100 \, \text{m/s}$ at an angle $\theta = 37^\circ$ above the horizontal. Air resistance is neglected.

Determine:

- Differential equations of motion
- Time of flight
- Maximum height
- Range

## Theory

Projectile motion under constant gravitational acceleration is governed by:

- Horizontal motion: constant velocity
- Vertical motion: constant acceleration $-g$

Newton’s second law gives:

$$
\vec{a} = (0, -g)
$$

## Step-by-Step Solution

### Decomposition of Initial Velocity

$$
v_{0x} = v_0 \cos \theta
$$

$$
v_{0y} = v_0 \sin \theta
$$

### Equations of Motion

Horizontal:

$$
\frac{d^2 x}{dt^2} = 0
$$

Vertical:

$$
\frac{d^2 y}{dt^2} = -g
$$

Integrating:

$$
x(t) = v_{0x} t
$$

$$
y(t) = v_{0y} t - \frac{1}{2} g t^2
$$

### Time of Flight

At landing, $y(T)=0$:

$$
v_{0y} T - \frac{1}{2} g T^2 = 0
$$

$$
T = \frac{2 v_{0y}}{g}
$$

$$
T = \frac{2 \cdot 100 \sin 37^\circ}{9.81}
$$

$$
T \approx 12.3 \, \text{s}
$$

### Maximum Height

At peak: $v_y = 0$

$$
H = \frac{v_{0y}^2}{2g}
$$

$$
H = \frac{(100 \sin 37^\circ)^2}{2 \cdot 9.81}
$$

$$
H \approx 184 \, \text{m}
$$

### Range

$$
R = v_{0x} T
$$

$$
R = 100 \cos 37^\circ \cdot 12.3
$$

$$
R \approx 981 \, \text{m}
$$

## Final Result

- Time of flight: $T \approx 12.3 \, \text{s}$
- Maximum height: $H \approx 184 \, \text{m}$
- Range: $R \approx 981 \, \text{m}$

## Interpretation

The motion separates cleanly into horizontal and vertical components. The vertical motion determines the time of flight, while horizontal motion determines the range.
...