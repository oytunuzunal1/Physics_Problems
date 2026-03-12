# The Classic Bicycle and Fly Problem: Logic vs. Infinite Series

## The Problem Statement
A bicycle is $10\text{ m}$ from a wall and moves towards it at a constant speed of $1\text{ m/s}$. A fly starts from the bicycle's front wheel and flies towards the wall at $2\text{ m/s}$. When it hits the wall, it instantly turns back and flies to the bicycle, and so on. 

**Question:** What is the total distance the fly travels before being crushed?

---

## Solution 1: The Elegant Logical Approach (Time-Based)

This problem is famous for tricking people into doing complicated math when a simple logical realization is all that is needed. Instead of calculating the distance of each individual back-and-forth flight, we can solve this by looking at **time**.

**Step 1: Determine the total time of the event.**
The entire scenario ends when the bicycle reaches the wall. 
* **Initial Distance ($D$):** $10\text{ m}$
* **Bicycle Speed ($v_b$):** $1\text{ m/s}$

Using the basic physics formula for time ($t = \frac{D}{v}$), we can calculate how long the bicycle is in motion:
$$t = \frac{10\text{ m}}{1\text{ m/s}} = 10\text{ s}$$

**Step 2: Calculate the fly's total distance.**
We now know that the fly is flying continuously for exactly $10\text{ seconds}$ before the bicycle hits the wall. Because the fly flies at a constant speed, its constant turning does not affect its total distance covered.
* **Total Time ($t$):** $10\text{ s}$
* **Fly Speed ($v_f$):** $2\text{ m/s}$

Using the distance formula ($D = v \times t$):
$$D_f = 2\text{ m/s} \times 10\text{ s} = 20\text{ m}$$

**Answer:** The fly travels a total distance of **$20\text{ meters}$**.

---

## Solution 2: The Infinite Series Approach (The Hard Way)

Why is this considered a trick question? Because our brains naturally try to calculate the sequence of the fly's individual trips, which creates an infinite geometric series. 

If we attempt to solve it this way, we have to calculate each leg of the journey:

1.  **First leg (to the wall):** The fly travels $10\text{ m}$ at $2\text{ m/s}$. It takes $5\text{ s}$. Meanwhile, the bicycle has moved $5\text{ m}$ forward.
2.  **Second leg (back to the bike):** The fly and the bicycle are now $5\text{ m}$ apart, moving towards each other at a combined relative speed of $3\text{ m/s}$ ($2\text{ m/s} + 1\text{ m/s}$). They meet in $\frac{5}{3}\text{ seconds}$. The fly travels $2 \times (\frac{5}{3}) = \frac{10}{3}\text{ m}$.
3.  **Third leg (back to the wall):** The distance to the wall is now less, and the process repeats.

This creates an infinite series of distances:
$$D_{total} = 10 + \frac{10}{3} + \frac{10}{9} + \frac{10}{27} + ... $$

This is a convergent infinite geometric series. If you sum this series to infinity, it perfectly converges to **$20\text{ meters}$**. 

### The John von Neumann Anecdote
This specific puzzle was famously posed to the brilliant mathematician John von Neumann. Upon hearing the problem, he paused for a fraction of a second and answered, "$20$." 
The person who asked it was disappointed and said, "Oh, you saw the trick. Most people try to sum the infinite series." 
Von Neumann replied, "What trick? I summed the infinite series." 

## Conclusion
While the infinite series proves the mathematics are sound, the **time-based logical approach** is the most efficient and elegant way to solve the problem. 

**Final Result: $20\text{ meters}$**