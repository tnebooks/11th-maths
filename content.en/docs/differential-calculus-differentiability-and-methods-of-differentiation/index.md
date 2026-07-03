---
title: 'differential calculus differentiability and methods of differentiation'
weight: 10
summary: "This chapter extends the concepts of limits and continuity to differentiability, defining the derivative as the instantaneous rate of change of a function and the slope of the tangent line at a given point, along with the conditions for a function to be differentiable. It covers various methods of differentiation including the product rule, quotient rule, chain rule, and differentiation of implicit functions, parametric functions, and logarithmic functions. The chapter also discusses higher-order derivatives, derivatives of inverse trigonometric functions, and applications such as finding tangents, normals, and rates of change in real-world problems."
---

# Differentiability and Methods of Differentiation

## 10.1 Introduction

In this chapter we discuss the concept of derivative and related concepts and develop tools necessary for solving real life problems. In this connection, let us look at the following problem of finding average velocity.

Almost everyone has an intuitive notion of speed or velocity as a rate at which a distance is covered in a certain length of time. When, say, a bus travels \(60 \text{ km}\) in one hour, the average velocity of the bus must have been \(60 \text{ km/h}\). Of course, it is difficult to maintain this rate of \(60 \text{ km/h}\) for the entire trip because the bus slows down for towns and speeds up when it passes cars. In other words, the velocity changes with time. If a bus company's schedule demands that the bus travel \(60 \text{ km}\) from one town to another in one hour, the driver knows instinctively that he must compensate for velocities or speeds greater than this at other points in the journey. Knowing that the average velocity is \(60 \text{ km/h}\) does not, however, answer the question: What is the velocity of the bus at a particular instant?

In general, this average velocity or average speed of a moving object is the time rate of change of position defined by

$$
V_{\text{ave}} = \frac{\text{distance traveled}}{\text{time of travel}}.
$$

Consider a runner who finishes a \(10 \text{ km}\) race in an elapsed time of \(1 \text{ h } 15 \text{ min}\) (1.25 h). The runner's average velocity or average speed for this race is

$$
V_{\text{ave}} = \frac{10}{1.25} = 8.
$$

But suppose we now wish to determine the runner's exact velocity \(v\) at the instant the runner is one-half into the race. If the distance run in the time interval from \(0 \text{ h}\) to \(0.5 \text{ h}\) is measured to be \(5 \text{ km}\), then

$$
V_{\text{ave}} = \frac{5}{0.5} = 10.
$$

Again this number is not a measure or necessarily such a good indicator, of the instantaneous rate \(v\) at which the runner is moving \(0.5 \text{ h}\) into the race. If we determine that rate at \(0.6 \text{ h}\) the runner is \(5.7 \text{ km}\) from the starting line, then the average velocity from \(0.5 \text{ h}\) to \(0.6 \text{ h}\) is

$$
v_{\text{ave}} = \frac{5.7 - 5}{0.6 - 0.5} = 7 \text{ km/h}.
$$

The latter number is a more realistic measure of the rate \(v\). By "shrinking" the time interval between \(0.5 \text{ h}\) and the time that corresponds to a measured position close to \(5 \text{ km}\) we expect to obtain even better approximations to the runner's velocity at time \(0.5 \text{ h}\).

**Gottfried Wilhelm Leibnitz (1646-1716)**

This problem of finding velocities leads us to deal with the general problem of finding the derivative of a general mathematical model represented by the analytic equation, \(y = f(x)\). Consequently, we will move towards in achieving the following objectives and subsequently deal with the analysis of derivatives.

## Learning Objectives

On completion of this chapter, the students are expected to

- acquire the concept of a derivative as limit of quotients.
- visualise the concept of derivative geometrically.
- understand derivative as a process of measuring changes.
- realise derivative as a tool to measure slopes of tangents to curves / rates of changes.
- understand different methods of differentiation.
- apply calculus as a tool to solve everyday real life problems.

## 10.2 The concept of derivative

Calculus grew out of four major problems that mathematicians were working on during the seventeenth century.

(1) The tangent line problem
(2) The velocity and acceleration problem
(3) The minimum and maximum problem
(4) The area problem

We take up the above problems 1 and 2 for discussion in this chapter while the last two problems are dealt with in the later chapters.

## 10.2.1 The tangent line problem

What does it mean to say that a line is tangent to a curve at a point? For a circle, the tangent line at a point \(P\) is the line that is perpendicular to the radial line at a point \(P\), as shown in fig. 10.1.

For a general curve, however, the problem is more difficult, for example, how would you define the tangent lines shown in the following figures 10.2 to 10.4.

You might say that a line is tangent to a curve at a point \(P\) if it touches, but does not cross, the curve at point \(P\). This definition would work for the first curve (Fig. 10.2), but not for the second (Fig. 10.3). Or you might say that a line is tangent to a curve if the line touches or intersects the curve exactly at one point. This definition would work for a circle but not for more general curves, as the third curve shows (Fig. 10.4).

**Fig. 10.1**

**Fig. 10.2**

**Fig. 10.4**

Essentially, the problem of finding the tangent line at a point \(P\) boils down to the problem of finding the slope of the tangent line at point \(P\). You can approximate this slope using a secant line through the point of tangency and a second point on the curve as in the following Fig. 10.5.

Let \(P(x_0, f(x_0))\) be the point of tangency and \(Q(x_0 + \Delta x, f(x_0 + \Delta x))\) be the second point.

The slope of the secant line through the two points is given by substitution into the slope formula

$$
m = \frac{y_2 - y_1}{x_2 - x_1}
$$

$$
m_{\text{sec}} = \frac{f(x_0 + \Delta x) - f(x_0)}{(x_0 + \Delta x) - x_0} = \frac{\text{change in } y}{\text{change in } x} = \frac{\Delta y}{\Delta x}.
$$

**Fig. 10.5**

That is,

$$
m_{\text{sec}} = \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x},
$$

which is the slope of the secant line.

The right hand side of this equation is a difference quotient. The denominator \(\Delta x\) is the change in \(x\) (increment in \(x\)), and the numerator \(\Delta y = f(x_0 + \Delta x) - f(x_0)\) is the change in \(y\).

The beauty of this procedure is that you can obtain more and more accurate approximations of the slope of the tangent line by choosing points closer and closer to the point of tangency.

**Tangent line approximation**

**Fig. 10.6 to 10.13**

Let us make an attempt to find the slope of the tangent line to the graph of \(f(x) = x^2\) at \((1,1)\).

As a start, let us take \(\Delta x = 0.1\) and find the slope of the secant line through \((1,1)\) and \((1.1, (1.1)^2)\).

\[
\begin{aligned}
\text{(i)} \quad f(1.1) &= (1.1)^2 = 1.21 \\
\text{(ii)} \quad \Delta y &= f(1.1) - f(1) = 1.21 - 1 = 0.21 \\
\text{(iii)} \quad \frac{\Delta y}{\Delta x} &= \frac{0.21}{0.1} = 2.1
\end{aligned}
\]

**Fig. 10.14**

Tabulate the successive values to the right and left of 1 as follows:

| \(\Delta x\) | \(1 + \Delta x\) | \(f(1)\) | \(f(1 + \Delta x)\) | \(\Delta y\) | \(\Delta y / \Delta x\) |
|-------------|-----------------|---------|--------------------|-------------|----------------------|
| 0.1 | 1.1 | 1 | 1.21 | 0.21 | 2.1 |
| 0.01 | 1.01 | 1 | 1.0201 | 0.0201 | 2.01 |
| 0.001 | 1.001 | 1 | 1.002001 | 0.002001 | 2.001 |
| -0.1 | 0.9 | 1 | 0.81 | -0.19 | 1.9 |
| -0.01 | 0.99 | 1 | 0.9801 | -0.0199 | 1.99 |
| -0.001 | 0.999 | 1 | 0.998001 | -0.001999 | 1.999 |

Clearly,

$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = 2, \quad \lim_{\Delta x \to 0^+} \frac{\Delta y}{\Delta x} = 2.
$$

This shows that \(\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = 2\).

Thus the slope of the tangent line to the graph of \(y = x^2\) at \((1,1)\) is \(m_{\text{tan}} = 2\).

On the basis of the Fig.10.6 to 10.13, Illustration 10.1, and our intuition, we are prompted to say that if a graph of a function \(y = f(x)\) has a tangent line \(L\) at a point \(P\), then \(L\) must be the line that is the limit of the secants \(PQ\) through \(P\) and \(Q\) as \(Q \to P (\Delta x \to 0)\). Moreover, the slope \(m_{\text{tan}}\) of \(L\) should be the limiting value of the values \(m_{\text{sec}}\) as \(\Delta x \to 0\). This is summarised as follows:

### Definition 10.1 (Tangent line with slope \(m\))

Let \(f\) be defined on an open interval containing \(x_0\), and if the limit

$$
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} = m_{\text{tan}}
$$

exists, then the line passing through \((x_0, f(x_0))\) with slope \(m\) is the tangent line to the graph of \(f\) at the point \((x_0, f(x_0))\).

The slope of the tangent line at \((x_0, f(x_0))\) is also called the slope of the curve at that point.

The definition implies that if a graph admits tangent line at a point \((x_0, f(x_0))\) then it is unique since a point and a slope determine a single line.

The conditions of the definition can be formulated in 4 steps:

\[
\begin{aligned}
\text{Step 1:} &\quad \text{Evaluate } f \text{ at } x_0 \text{ and } x_0 + \Delta x : f(x_0) \text{ and } f(x_0 + \Delta x) \\
\text{Step 2:} &\quad \text{Compute } \Delta y : \Delta y = f(x_0 + \Delta x) - f(x_0) \\
\text{Step 3:} &\quad \text{Divide } \Delta y \text{ by } \Delta x (\neq 0) : \frac{\Delta y}{\Delta x} = \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} \\
\text{Step 4:} &\quad \text{Compute the limit as } \Delta x \to 0 (\neq 0) : m_{\text{tan}} = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x}
\end{aligned}
\]

The computation of the slope of the graph in the Illustration 10.1 can be facilitated using the definitions.

\[
\begin{aligned}
f(1) &= 1^2 = 1. \quad \text{For any } \Delta x \neq 0, \\
f(1 + \Delta x) &= (1 + \Delta x)^2 = 1 + 2\Delta x + (\Delta x)^2 \\
\Delta y &= f(1 + \Delta x) - f(1) = 2\Delta x + (\Delta x)^2 = \Delta x(2 + \Delta x) \\
\frac{\Delta y}{\Delta x} &= \frac{\Delta x(2 + \Delta x)}{\Delta x} = 2 + \Delta x \\
m_{\text{tan}} &= \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} (2 + \Delta x) = 2 + 0 = 2.
\end{aligned}
\]

### Example 10.1

Find the slope of the tangent line to the graph of \(f(x) = 7x + 5\) at any point \((x_0, f(x_0))\).

**Solution**

Step (i) \(f(x_0) = 7x_0 + 5\).

For any \(\Delta x \neq 0\),

\[
f(x_0 + \Delta x) = 7(x_0 + \Delta x) + 5 = 7x_0 + 7\Delta x + 5
\]
\[
\Delta y = f(x_0 + \Delta x) - f(x_0) = (7x_0 + 7\Delta x + 5) - (7x_0 + 5) = 7\Delta x
\]

Step (ii) \(\displaystyle \frac{\Delta y}{\Delta x} = 7\)

Thus, at any point on the graph of \(f(x) = 7x + 5\), we have

Step (iv) \(\displaystyle m_{\text{tan}} = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} (7) = 7\).

Note that for a linear graph, \(\frac{\Delta y}{\Delta x}\) is a constant, depends neither on \(x_0\) nor on the increment \(\Delta x\).

### Example 10.2

Find the slope of tangent line to the graph of \(f(x) = -5x^2 + 7x\) at \((5, f(5))\).

**Solution**

\[
\begin{aligned}
\text{(i)} \quad f(5) &= -5(5)^2 + 7 \times 5 = -125 + 35 = -90. \\
\text{For any } \Delta x \neq 0, \\
f(5 + \Delta x) &= -5(5 + \Delta x)^2 + 7(5 + \Delta x) = -90 - 43\Delta x - 5(\Delta x)^2. \\
\Delta y &= f(5 + \Delta x) - f(5) = -90 - 43\Delta x - 5(\Delta x)^2 + 90 = -43\Delta x - 5(\Delta x)^2 \\
&= \Delta x[-43 - 5\Delta x]. \\
\frac{\Delta y}{\Delta x} &= -43 - 5\Delta x \\
m_{\text{tan}} &= \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = -43.
\end{aligned}
\]

## 10.2.2 Velocity of Rectilinear motion

Suppose an object moves along a straight line according to an equation of motion \(s = f(t)\), where \(s\) is the displacement (directed distance) of the object from the origin at time \(t\). The function \(f\) that describes the motion is called the position function of the object. In the time interval from \(t = t_0\) to \(t = t_0 + \Delta t\), the change in position is \(f(t_0 + \Delta t) - f(t_0)\). The average velocity over this time interval is

$$
v_{\text{avg}} = \frac{\text{displacement}}{\text{time}} = \frac{f(t_0 + \Delta t) - f(t_0)}{\Delta t} = \frac{\text{Change in } s}{\text{Change in } t} = \frac{\Delta s}{\Delta t}
$$

secant line \(PQ\) in fig. 10.16.

**Fig. 10.15**

**Fig. 10.16**

In this time interval \(\Delta t\) (from \(t_0\) to \(t_0 + \Delta t\)) the motion may be of entirely different types for the same distance covered (traversed). This is illustrated graphically by the fact that we can draw entirely different curves \(C_1, C_2, C_3, \dots\) between the points \(P\) and \(Q\) in the plane. These curves are the graphs of quite different motions in the given time intervals, all the motions having the same average velocity \(\frac{\Delta s}{\Delta t}\).

**Fig. 10.17**

Now suppose we compute the average velocities over shorter and shorter time intervals \([t_0, t_0 + \Delta t]\). In other words, we let \(\Delta t\) approach 0. Then we define the velocity (or instantaneous velocity) \(v(t_0)\) at time \(t = t_0\) as the limit of these average velocities.

$$
v(t_0) = \lim_{\Delta t \to 0} \frac{f(t_0 + \Delta t) - f(t_0)}{\Delta t} = \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t}.
$$

This means that the velocity at time \(t = t_0\) is equal to the slope of the tangent line at \(P\).

### Illustration 10.2

The distance \(s\) travelled by a body falling freely in a vacuum and the time \(t\) of descent are variables. They depend on each other. This dependence is expressed by the law of the free fall:

$$
s = \frac{1}{2} gt^2 \quad \text{(absence of initial velocity), } g \text{ is the gravitational constant}.
$$

\[
\begin{aligned}
\text{Step (i)} \quad f(t_0 + \Delta t) &= \frac{1}{2} g(t_0 + \Delta t)^2 = \frac{1}{2} g(t_0^2 + 2t_0\Delta t + (\Delta t)^2) \\
\text{Step (ii)} \quad \Delta s &= f(t_0 + \Delta t) - f(t_0) \\
&= \frac{1}{2} g[t_0^2 + 2t_0\Delta t + (\Delta t)^2] - \frac{1}{2} g t_0^2 \\
&= g\Delta t\left[t_0 + \frac{1}{2}\Delta t\right] \\
\text{Step (iii)} \quad \frac{\Delta s}{\Delta t} &= \frac{g\Delta t\left[t_0 + \frac{1}{2}\Delta t\right]}{\Delta t} = g\left[t_0 + \frac{1}{2}\Delta t\right] \\
\text{Step (iv)} \quad v(t_0) &= \lim_{\Delta t \to 0} \frac{\Delta s}{\Delta t} = g t_0.
\end{aligned}
\]

It is clear from this that the velocity is completely defined by the instant \(t_0\). It is proportional to the time of motion (of the fall).

## 10.2.3 The derivative of a Function

We have now arrived at a crucial point in the study of calculus. The limit used to define the slope of a tangent line or the instantaneous velocity of a freely falling body is also used to define one of the two fundamental operations of calculus — differentiation.

### Definition 10.2

Let \(f\) be defined on an open interval \(I \subseteq \mathbb{R}\) containing the point \(x_0\), and suppose that

$$
\lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

exists. Then \(f\) is said to be differentiable at \(x_0\) and the derivative of \(f\) at \(x_0\), denoted by \(f'(x_0)\), is given by

$$
f'(x_0) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}.
$$

For all \(x\) for which this limit exists,

$$
f'(x) = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}
$$

is a function of \(x\).

Be sure you see that the derivative of a function of \(x\) is also a function of \(x\). This "new" function gives the slope of the tangent line to the graph of \(f\) at the point \((x, f(x))\), provided the graph has a tangent line at this point.

The process of finding the derivative of a function is called differentiation. A function is differentiable at \(x\) if its derivative exists at \(x\) and is differentiable on an open interval \((a, b)\) if it is differentiable at every point in \((a, b)\).

In addition to \(f'(x)\), which is read as '\(f\) prime of \(x\)' or '\(f\) dash of \(x\)', other notations are used to denote the derivative of \(y = f(x)\). The most common notations are

$$
f'(x), \quad \frac{dy}{dx}, \quad y', \quad \frac{d}{dx}[f(x)], \quad D_x[y] \text{ or } Dy \text{ or } y_1.
$$

Here \(\frac{d}{dx}\) or \(D\) is the differential operator.

The notation \(\frac{dy}{dx}\) is read as "derivative of \(y\) with respect to \(x\)" or simply "\(dy-dx\)", or we should rather read it as "Dee \(y\) Dee \(x\)" or "Dee Dee \(x\) of \(y\)". But it is cautioned that we should not regard \(\frac{dy}{dx}\) as the quotient \(dy \div dx\) and should not refer it as "\(dy\) by \(dx\)". The symbol \(\frac{dy}{dx}\) is known as Leibnitz symbol.

## 10.2.4 One sided derivatives (left hand and right hand derivatives)

For a function \(y = f(x)\) defined in an open interval \((a, b)\) containing the point \(x_0\), the left hand and right hand derivatives of \(f\) at \(x = x_0\) are respectively denoted by \(f'(x_0^-)\) and \(f'(x_0^+)\), are defined as

$$
f'(x_0^-) = \lim_{\Delta x \to 0^-} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$
and
$$
f'(x_0^+) = \lim_{\Delta x \to 0^+} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x},
$$

provided the limits exist.

That is, the function is differentiable from the left and right. As in the case of the existence of limits of a function at \(x_0\), it follows that \(f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}\) exists if and only if both \(f'(x_0^-) = \lim_{\Delta x \to 0^-} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}\) and \(f'(x_0^+) = \lim_{\Delta x \to 0^+} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}\) exist and \(f'(x_0^-) = f'(x_0^+)\).

Therefore \(f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}\) if and only if \(f'(x_0^-) = f'(x_0^+)\).

If any one of the condition fails then \(f\) is not differentiable at \(x_0\).

In terms of \(h = \Delta x > 0\),

$$
f'(x_0^+) = \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h}
$$
and
$$
f'(x_0^-) = \lim_{h \to 0} \frac{f(x_0 - h) - f(x_0)}{-h}.
$$

A function \(f\) is said to be differentiable in the closed interval \([a, b]\) if it is differentiable on the open interval \((a, b)\) and at the end points \(a\) and \(b\)

$$
f'(a) = \lim_{\Delta x \to 0^+} \frac{f(a + \Delta x) - f(a)}{\Delta x} = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}, \; h > 0
$$
$$
f'(b) = \lim_{\Delta x \to 0^-} \frac{f(b + \Delta x) - f(b)}{\Delta x} = \lim_{h \to 0} \frac{f(b - h) - f(b)}{-h}, \; h > 0.
$$

If \(f\) is differentiable at \(x = x_0\), then \(f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0}\), where \(x = x_0 + \Delta x\) and \(\Delta x \to 0\) is equivalent to \(x \to x_0\). This alternative form is some times more convenient to be used in computations.

As a matter of convenience, if we let \(h = \Delta x\), then \(f'(x) = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}\), provided the limit exists.

## 10.3 Differentiability and Continuity

### Illustration 10.3

Test the differentiability of the function \(f(x) = |x - 2|\) at \(x = 2\).

**Solution**

We know that this function is continuous at \(x = 2\).

But

\[
\begin{aligned}
f'(2^-) &= \lim_{x \to 2^-} \frac{f(x) - f(2)}{x - 2} = \lim_{x \to 2^-} \frac{|x - 2| - 0}{x - 2} = \lim_{x \to 2^-} \frac{-(x - 2)}{(x - 2)} = -1 \\
f'(2^+) &= \lim_{x \to 2^+} \frac{f(x) - f(2)}{x - 2} = \lim_{x \to 2^+} \frac{|x - 2| - 0}{x - 2} = \lim_{x \to 2^+} \frac{(x - 2)}{(x - 2)} = 1
\end{aligned}
\]

**Fig. 10.18**

Since the one sided derivatives \(f'(2^-)\) and \(f'(2^+)\) are not equal, \(f'(2)\) does not exist. That is, \(f\) is not differentiable at \(x = 2\). At all other points, the function is differentiable.

If \(x_0 \neq 2\) is any other point then

\[
f'(x_0) = \lim_{x \to x_0} \frac{|x - 2| - |x_0 - 2|}{x - x_0} = 1 \text{ or } -1.
\]

The fact that \(f'(2)\) does not exist is reflected geometrically in the fact that the curve \(y = |x - 2|\) does not have a tangent line at \((2, 0)\). Note that the curve has a sharp edge at \((2, 0)\).

### Illustration 10.4

Examine the differentiability of \(f(x) = x^{\frac{1}{3}}\) at \(x = 0\).

**Solution**

Let \(f(x) = x^{\frac{1}{3}}\). Clearly, there is no hole (or break) in the graph of this function and hence it is continuous at all points of its domain.

Let us check whether \(f'(0)\) exists.

\[
\begin{aligned}
\text{Now } f'(0) &= \lim_{x \to 0} \frac{f(x) - f(0)}{x - 0} = \lim_{x \to 0} \frac{x^{\frac{1}{3}} - 0}{x} \\
&= \lim_{x \to 0} x^{\frac{-2}{3}} = \lim_{x \to 0} \frac{1}{x^{\frac{2}{3}}} \to \infty
\end{aligned}
\]

**Fig. 10.19**

Therefore, the function is not differentiable at \(x = 0\). From the Fig. 10.19, further we conclude that the tangent line is vertical at \(x = 0\). So \(f\) is not differentiable at \(x = 0\).

If a function is continuous at a point, then it is not necessary that the function is differentiable at that point.

### Example 10.3

Show that the greatest integer function \(f(x) = \lfloor x \rfloor\) is not differentiable at any integer.

**Solution**

The greatest integer function \(f(x) = \lfloor x \rfloor\) is not continuous at every integer point \(n\), since \(\lim_{x \to n^-} \lfloor x \rfloor = n - 1\) and \(\lim_{x \to n^+} \lfloor x \rfloor = n\). Thus \(f'(n)\) does not exist.

What can you say about the differentiability of this function at other points?

### Illustration 10.5

Let
$$
f(x) = \begin{cases}
x, & x \leq 0 \\
1 + x, & x > 0
\end{cases}
$$
Compute \(f'(0)\) if it exists.

**Solution**

Look at the graph drawn.

\[
\begin{aligned}
f'(0^-) &= \lim_{\Delta x \to 0^-} \frac{f(0 + \Delta x) - f(0)}{\Delta x} = \lim_{\Delta x \to 0^-} \frac{f(\Delta x)}{\Delta x} = \lim_{\Delta x \to 0^-} \frac{\Delta x}{\Delta x} = 1 \\
f'(0^+) &= \lim_{\Delta x \to 0^+} \frac{f(0 + \Delta x) - f(0)}{\Delta x} = \lim_{\Delta x \to 0^+} \frac{f(\Delta x)}{\Delta x} = \lim_{\Delta x \to 0^+} \frac{1 + \Delta x}{\Delta x} \to \infty
\end{aligned}
\]

**Fig. 10.20**

Therefore \(f'(0)\) does not exist.

Here we observe that the graph of \(f\) has a jump at \(x = 0\). That is \(x = 0\) is a jump discontinuity.

The above illustrations and examples can be summarised to have the following conclusions.

A function \(f\) is not differentiable at a point \(x_0\) belonging to the domain of \(f\) if one of the following situations holds:

(i) \(f\) has a vertical tangent at \(x_0\).

(ii) The graph of \(f\) comes to a point at \(x_0\) (either a sharp edge \(\lor\) or a sharp peak \(\land\))

(iii) \(f\) is discontinuous at \(x_0\).

**Fig. 10.21** **Fig. 10.22** **Fig. 10.23**

We have seen in illustration 10.3 and 10.4, the function \(f(x) = |x - 2|\) and \(f(x) = x^{\frac{1}{3}}\) are respectively continuous at \(x = 2\) and \(x = 0\) but not differentiable there, whereas in Example 10.3 and Illustration 10.5, the functions \(f(x) = \lfloor x \rfloor\) and
$$
f(x) = \begin{cases}
x, & x \leq 0 \\
1 + x, & x > 0
\end{cases}
$$
are respectively not continuous at any integer \(x = n\) and \(x = 0\) respectively and not differentiable too.

The above argument can be condensed and encapsuled to state: **Discontinuity implies non-differentiability.**

### Theorem 10.1 (Differentiability implies continuity)

If \(f\) is differentiable at a point \(x = x_0\), then \(f\) is continuous at \(x_0\).

**Proof**

Let \(f(x)\) be a differentiable function on an interval \((a, b)\) containing the point \(x_0\). Then

$$
f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
$$

exists, in the sense that \(f'(x_0)\) is a unique real number.

Now
\[
\begin{aligned}
\lim_{\Delta x \to 0} [f(x_0 + \Delta x) - f(x_0)] &= \lim_{\Delta x \to 0} \left[ \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} \times \Delta x \right] \\
&= \lim_{\Delta x \to 0} \left[ \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x} \right] \times \lim_{\Delta x \to 0} (\Delta x) \\
&= f'(x_0) \times 0 = 0.
\end{aligned}
\]

This implies, \(f\) is continuous at \(x = x_0\).

### Derivatives from first principle

The process of finding the derivative of a function using the conditions stated in the definition of derivatives is known as derivatives from first principle.

## EXERCISE 10.1

1. Find the derivatives of the following functions using first principle.

   (i) \(f(x) = 6\)

   (ii) \(f(x) = -4x + 7\)

   (iii) \(f(x) = -x^2 + 2\)

2. Find the derivatives from the left and from the right at \(x = 1\) (if they exist) of the following functions. Are the functions differentiable at \(x = 1\)?

   (i) \(f(x) = |x - 1|\)

   (ii) \(f(x) = \sqrt{1 - x^2}\)

3. Determine whether the following function is differentiable at the indicated values.

   (i) \(f(x) = x|x|\) at \(x = 0\)

   (ii) \(f(x) = |x^2 - 1|\) at \(x = 1\)

   (iii) \(f(x) = |x| + |x - 1|\) at \(x = 0\)

   (iv) \(f(x) = \sin|x|\) at \(x = 0\)

4. Show that the following functions are not differentiable at the indicated value of \(x\).

   (i) \(f(x) = \begin{cases} -x, & x < 0 \\ x^2, & x \ge 0 \end{cases}\) at \(x = 0\)

   (ii) \(f(x) = \begin{cases} x\sin\frac{1}{x}, & x \neq 0 \\ 0, & x = 0 \end{cases}\) at \(x = 0\)

5. The graph of \(f\) is shown below. State with reasons that \(x\) values (the numbers), at which \(f\) is not differentiable.

   **Fig. 10.24**

6. If \(f(x) = |x + 100| + x^2\), test whether \(f'(-100)\) exists.

7. Examine the differentiability of functions in \(\mathbb{R}\) by drawing the diagrams.

   (i) \(|\sin x|\)  (ii) \(|\cos x|\)

## 10.4 Differentiation Rules

If \(f\) is a real valued function of a real variable defined on an open interval \(I\) and if \(y = f(x)\) is a differentiable function of \(x\), then \(\frac{dy}{dx} = f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}\). In general finding such direct derivatives using first principle is extremely laborious and difficult operation in the majority of cases. But if we know, once and for all, the derivatives of all the basic elementary functions, together with rules of differentiating the algebra of functions and functions of a function, we can find the derivative of any element — any function without carrying out limit process each time. Hence the operation of differentiation can be made automatic for the class of functions that concern us.

Now we divert our attention to the rules for differentiation of a sum, product and quotient.

### Theorem 10.2 (Sum Rule)

The derivative of the sum of two (or more) differentiable functions is equal to the sum of their derivatives. That is, if \(u\) and \(v\) are two differentiable functions then

$$
\frac{d}{dx}(u + v) = \frac{d}{dx}u + \frac{d}{dx}v.
$$

**Proof**

Let \(u\) and \(v\) be two real valued functions defined and differentiable on an open interval \(I \subseteq \mathbb{R}\). Let \(y = u + v\), then \(y = f(x)\) is a function defined on \(I\), and by hypothesis

\[
u'(x) = \frac{du}{dx} = \lim_{\Delta x \to 0} \frac{u(x + \Delta x) - u(x)}{\Delta x}
\]
\[
v'(x) = \frac{dv}{dx} = \lim_{\Delta x \to 0} \frac{v(x + \Delta x) - v(x)}{\Delta x} \quad \text{exist.}
\]

Now,

\[
f(x + \Delta x) = u(x + \Delta x) + v(x + \Delta x)
\]
\[
f(x + \Delta x) - f(x) = u(x + \Delta x) - u(x) + v(x + \Delta x) - v(x).
\]
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{u(x + \Delta x) - u(x)}{\Delta x} + \frac{v(x + \Delta x) - v(x)}{\Delta x}.
\]

This implies,
\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = \lim_{\Delta x \to 0} \frac{u(x + \Delta x) - u(x)}{\Delta x} + \lim_{\Delta x \to 0} \frac{v(x + \Delta x) - v(x)}{\Delta x}.
\]

That is,
\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = u'(x) + v'(x).
\]

That is, \(f'(x) = u'(x) + v'(x)\).

or \((u + v)'(x) = u'(x) + v'(x)\).

That is,
\[
\frac{d}{dx}(u + v) = \frac{d}{dx}u + \frac{d}{dx}v.
\]

This can be extended to finite number of differentiable functions \(u_1, u_2, \dots, u_n\) and

\[
(u_1 + u_2 + \dots + u_n)' = u_1' + u_2' + \dots + u_n'.
\]

### Theorem 10.3 (Product Rule)

Let \(u\) and \(v\) be two differentiable functions. Then

$$
\frac{d}{dx}(uv) = u\frac{dv}{dx} + v\frac{du}{dx}.
$$

**Proof**

Let \(u\) and \(v\) be the given two differentiable functions so that

\[
\lim_{\Delta x \to 0} \frac{u(x + \Delta x) - u(x)}{\Delta x} = \frac{du}{dx} \quad \text{and} \quad \lim_{\Delta x \to 0} \frac{v(x + \Delta x) - v(x)}{\Delta x} = \frac{dv}{dx}.
\]

Let \(y = f(x) = u(x)v(x)\).

\[
\begin{aligned}
f(x + \Delta x) - f(x) &= u(x + \Delta x)v(x + \Delta x) - u(x)v(x) \\
&= v(x + \Delta x)[u(x + \Delta x) - u(x)] + u(x)[v(x + \Delta x) - v(x)].
\end{aligned}
\]

This implies,
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = u(x) \left[ \frac{v(x + \Delta x) - v(x)}{\Delta x} \right] + v(x + \Delta x) \left[ \frac{u(x + \Delta x) - u(x)}{\Delta x} \right].
\]

\[
\begin{aligned}
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} &= u(x) \lim_{\Delta x \to 0} \frac{v(x + \Delta x) - v(x)}{\Delta x} \\
&\quad + \lim_{\Delta x \to 0} v(x + \Delta x) \lim_{\Delta x \to 0} \frac{u(x + \Delta x) - u(x)}{\Delta x} \\
&= u(x)v'(x) + v(x)u'(x) \quad (\text{since } v \text{ is continuous}, \lim_{\Delta x \to 0} v(x + \Delta x) = v(x)).
\end{aligned}
\]

Similarly \((uvw)' = uvw' + uv'w + u'vw\).

This can be extended to a finite number of differentiable functions \(u_1, u_2, \dots, u_n\) using induction:

\[
(u_1 u_2 \cdots u_n)' = u_1 u_2 \cdots u_{n-1} u_n' + u_1 u_2 \cdots u_{n-1}' u_n + \cdots + u_1' u_2 \cdots u_n.
\]

### Theorem 10.4 (Quotient Rule)

Let \(u\) and \(v\) be two differentiable functions with \(v(x) \neq 0\). Then

$$
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^2}.
$$

**Proof**

Let \(y = f(x) = \frac{u}{v}\), \(u\) and \(v\) are differentiable functions of \(x\) and where \(v(x) \neq 0\).

Now \(f(x + \Delta x) = \frac{u(x + \Delta x)}{v(x + \Delta x)}\).

This implies,
\[
\begin{aligned}
f(x + \Delta x) - f(x) &= \frac{u(x + \Delta x)}{v(x + \Delta x)} - \frac{u(x)}{v(x)} \\
&= \frac{v(x)u(x + \Delta x) - u(x)v(x + \Delta x)}{v(x + \Delta x)v(x)}.
\end{aligned}
\]

\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{v(x)\frac{u(x + \Delta x) - u(x)}{\Delta x} - u(x)\frac{v(x + \Delta x) - v(x)}{\Delta x}}{v(x + \Delta x)v(x)}.
\]

\[
\begin{aligned}
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} &= \frac{v(x) \lim_{\Delta x \to 0} \frac{u(x + \Delta x) - u(x)}{\Delta x} - u(x) \lim_{\Delta x \to 0} \frac{v(x + \Delta x) - v(x)}{\Delta x}}{v(x) \lim_{\Delta x \to 0} v(x + \Delta x)} \\
&= \frac{v(x)u'(x) - u(x)v'(x)}{v(x) \cdot v(x)} \quad \left( \because \lim_{\Delta x \to 0} v(x + \Delta x) = v(x) \right).
\end{aligned}
\]

Thus
\[
\frac{d}{dx}\left(\frac{u}{v}\right) = \frac{v\frac{du}{dx} - u\frac{dv}{dx}}{v^2}.
\]

### Theorem 10.5 (Chain Rule / Composite Function Rule or Function of a Function Rule)

Let \(y = f(u)\) be a function of \(u\) and in turn let \(u = g(x)\) be a function of \(x\) so that \(y = f(g(x)) = (f \circ g)(x)\). Then

$$
\frac{d}{dx}(f(g(x))) = f'(g(x)) g'(x).
$$

**Proof**

In the above function \(u = g(x)\) is known as the inner function and \(f\) is known as the outer function. Note that, ultimately, \(y\) is a function of \(x\).

Now \(\Delta u = g(x + \Delta x) - g(x)\).

Therefore,
\[
\frac{\Delta y}{\Delta x} = \frac{\Delta y}{\Delta u} \times \frac{\Delta u}{\Delta x} = \frac{f(u + \Delta u) - f(u)}{\Delta u} \times \frac{g(x + \Delta x) - g(x)}{\Delta x}.
\]

Note that \(\Delta u \to 0\) as \(\Delta x \to 0\).

Therefore,
\[
\begin{aligned}
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} &= \lim_{\Delta x \to 0} \left( \frac{\Delta y}{\Delta u} \times \frac{\Delta u}{\Delta x} \right) \\
&= \lim_{\Delta u \to 0} \left( \frac{\Delta y}{\Delta u} \right) \lim_{\Delta x \to 0} \left( \frac{\Delta u}{\Delta x} \right) \\
&= \lim_{\Delta u \to 0} \frac{f(u + \Delta u) - f(u)}{\Delta u} \times \lim_{\Delta x \to 0} \frac{g(x + \Delta x) - g(x)}{\Delta x} \\
&= f'(u) \times u'(x) \\
&= f'(g(x)) g'(x).
\end{aligned}
\]

Thus, to differentiate a function of a function \(y = f(g(x))\), we have to take the derivative of the outer function \(f\) regarding the argument \(g(x) = u\), and multiply the derivative of the inner function \(g(x)\) with respect to the independent variable \(x\). The variable \(u\) is known as intermediate argument.

### Theorem 10.6 (Constant Multiple Rule)

Let \(f(x)\) be a differentiable function and let \(y = k f(x)\), \(k \neq 0\). Then

$$
\frac{d}{dx}(k f(x)) = k \frac{d}{dx} f(x).
$$

**Proof**

Since \(f\) is differentiable,
\[
f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}.
\]

Let \(y = h(x) = k f(x)\).

\[
h(x + \Delta x) = k f(x + \Delta x)
\]
\[
h(x + \Delta x) - h(x) = k f(x + \Delta x) - k f(x) = k[f(x + \Delta x) - f(x)]
\]
\[
\frac{h(x + \Delta x) - h(x)}{\Delta x} = k \frac{f(x + \Delta x) - f(x)}{\Delta x}.
\]

This implies,
\[
\lim_{\Delta x \to 0} \frac{h(x + \Delta x) - h(x)}{\Delta x} = k \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = k f'(x).
\]

Thus
\[
\frac{d}{dx}(k f(x)) = k \frac{d}{dx} f(x).
\]

### 10.4.1 Derivatives of basic elementary functions

We shall now find the derivatives of all the basic elementary functions; we start with the constant function.

**(1) The derivative of a constant function is zero.**

Let \(y = f(x) = k\), \(k\) is a constant.

Then \(f(x + \Delta x) = k\) and

\(f(x + \Delta x) - f(x) = k - k = 0\).

This implies,
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = 0.
\]

This implies,
\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = 0.
\]

That is, \(f'(x) = 0\).

or
\[
\frac{d}{dx}(k) = 0.
\]

**(2) The power function \(y = x^n\), \(n > 0\) is an integer.**

Let \(f(x) = x^n\).

Then, \(f(x + \Delta x) = (x + \Delta x)^n\) and
\[
f(x + \Delta x) - f(x) = (x + \Delta x)^n - x^n.
\]

This implies,
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{(x + \Delta x)^n - x^n}{(x + \Delta x) - x}.
\]

This implies,
\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = \lim_{\Delta x \to 0} \frac{(x + \Delta x)^n - x^n}{(x + \Delta x) - x} = \lim_{y \to x} \frac{y^n - x^n}{y - x} = nx^{n-1},
\]
where \(y = x + \Delta x\) and \(y \to x\) as \(\Delta x \to 0\).

That is,
\[
\frac{d}{dx} f(x) = nx^{n-1} \quad \text{or} \quad \frac{d}{dx}(x^n) = nx^{n-1}.
\]

**Corollary 10.1**

When \(n = \frac{p}{q}\), \((p, q) = 1\),
\[
\frac{d}{dx}\left(x^{\frac{p}{q}}\right) = \frac{p}{q} x^{\frac{p}{q} - 1}.
\]

**Corollary 10.2**

For any real number \(\alpha\),
\[
\frac{d}{dx}(x^\alpha) = \alpha x^{\alpha - 1}.
\]

For instance,

(1) \(\frac{d}{dx}(5) = 0\) since 5 is a constant.

(2) \(\frac{d}{dx}(x^3) = 3x^2\), by power function rule.

(3) \(\frac{d}{dx}\left(\sqrt{x^3}\right) = \frac{d}{dx}\left(x^{\frac{3}{2}}\right) = \frac{3}{2} x^{\frac{3}{2} - 1} = \frac{3}{2} x^{\frac{1}{2}}\), by power function rule.

(4) \(\frac{d}{dx}\left(x^{\sqrt{2}}\right) = \sqrt{2} x^{\sqrt{2} - 1}\), by power function rule.

(5) \(\frac{d}{dx}\left(\sqrt[3]{x^2}\right) = \frac{d}{dx}\left(x^{\frac{2}{3}}\right) = \frac{2}{3} x^{\frac{2}{3} - 1} = \frac{2}{3} x^{-\frac{1}{3}}\), \((x \neq 0)\), by power function rule.

(6) \(\frac{d}{dx}(100x^9) = 100 \frac{d}{dx}(x^9) = 100 \times 9x^{9-1} = 900x^8\) by theorem 10.6.

**(3) Derivative of the logarithmic function**

The natural logarithm of \(x\) is denoted by \(\log_e x\) or \(\log x\) or \(\ln x\).

Let \(y = f(x) = \log x\).

Now \(f(x + \Delta x) = \log (x + \Delta x)\) and

\[
f(x + \Delta x) - f(x) = \log (x + \Delta x) - \log x = \log \left( \frac{x + \Delta x}{x} \right) = \log \left(1 + \frac{\Delta x}{x}\right).
\]

\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{\log \left(1 + \frac{\Delta x}{x}\right)}{\Delta x}.
\]

We know that \(\lim_{\alpha \to 0} \frac{\log(1 + \alpha)}{\alpha} = 1\).

Therefore,
\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = \lim_{\Delta x \to 0} \frac{\log \left(1 + \frac{\Delta x}{x}\right)}{\Delta x} = \frac{1}{x}.
\]

That is,
\[
\frac{d}{dx}(\log x) = \frac{1}{x}.
\]

**Corollary 10.3**

If \(y = f(x) = \log_a x\) then
\[
f'(x) = \frac{1}{(\log a)x}.
\]

We have
\[
f(x) = \log_a x = \log_a e \times \log_e x = (\log_a e) \log x.
\]

\[
\frac{d}{dx}(f(x)) = \frac{d}{dx}(\log_a e \times \log x) = (\log_a e) \frac{d}{dx}(\log x) = \log_a e \cdot \frac{1}{x} = \frac{1}{(\log a)x}.
\]

**(4) Derivative of the exponential function**

Let \(y = a^x\).

Then
\[
f(x + \Delta x) - f(x) = a^{x + \Delta x} - a^x = a^x(a^{\Delta x} - 1)
\]

and
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = a^x \left( \frac{a^{\Delta x} - 1}{\Delta x} \right).
\]

We know that \(\lim_{\Delta x \to 0} \frac{a^{\Delta x} - 1}{\Delta x} = \log a\).

\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = a^x \lim_{\Delta x \to 0} \left( \frac{a^{\Delta x} - 1}{\Delta x} \right) = a^x \times \log a.
\]

or
\[
\frac{d}{dx}(a^x) = a^x \log a.
\]

In particular,
\[
\frac{d}{dx}(e^x) = e^x \log e = e^x.
\]

**(5) The derivatives of the Trigonometric functions**

**(i) The sine function, \(\sin x\)**

Let \(y = f(x) = \sin x\).

Then \(f(x + \Delta x) = \sin (x + \Delta x)\) and

\[
f(x + \Delta x) - f(x) = \sin (x + \Delta x) - \sin x = 2 \sin \frac{\Delta x}{2} \cos \left( x + \frac{\Delta x}{2} \right).
\]

Now
\[
\frac{f(x + \Delta x) - f(x)}{\Delta x} = \frac{\sin \left( \frac{\Delta x}{2} \right)}{\left( \frac{\Delta x}{2} \right)} \cos \left( x + \frac{\Delta x}{2} \right).
\]

\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x} = \lim_{\Delta x \to 0} \frac{\sin \left( \frac{\Delta x}{2} \right)}{\left( \frac{\Delta x}{2} \right)} \cdot \lim_{\Delta x \to 0} \cos \left( x + \frac{\Delta x}{2} \right) = 1 \times \cos x = \cos x.
\]

That is,
\[
\frac{d}{dx}(\sin x) = \cos x.
\]

**(ii) The cosine function, \(\cos x\)**

Let \(y = \cos x = \sin \left( x + \frac{\pi}{2} \right)\).

Then,
\[
\frac{dy}{dx} = \frac{d}{dx} \sin \left( x + \frac{\pi}{2} \right).
\]

Let \(u = x + \frac{\pi}{2}\). Then \(\frac{du}{dx} = 1 + 0 = 1\).

Therefore,
\[
\frac{dy}{dx} = \frac{d}{dx} (\sin u) = \frac{d}{du} (\sin u) \frac{du}{dx} \quad \text{by Chain rule}
\]
\[
= \cos u \times 1 = \cos u = \cos \left( x + \frac{\pi}{2} \right) = -\sin x.
\]

That is,
\[
\frac{d}{dx}(\cos x) = -\sin x.
\]

**(iii) The tangent function, \(\tan x\)**

Let \(y = f(x) = \tan x = \frac{\sin x}{\cos x}\).

\[
\begin{aligned}
\frac{d}{dx}(\tan x) &= \frac{d}{dx}\left( \frac{\sin x}{\cos x} \right) \\
&= \frac{\cos x \frac{d}{dx}(\sin x) - \sin x \frac{d}{dx}(\cos x)}{\cos^2 x} \\
&= \frac{\cos x (\cos x) - \sin x (-\sin x)}{\cos^2 x} \\
&= \frac{\cos^2 x + \sin^2 x}{\cos^2 x} = \frac{1}{\cos^2 x}.
\end{aligned}
\]

That is,
\[
\frac{d}{dx}(\tan x) = \sec^2 x.
\]

**(iv) The secant function, \(\sec x\)**

Let \(y = \sec x = \frac{1}{\cos x} = (\cos x)^{-1}\).

Then
\[
\frac{dy}{dx} = (-1)(\cos x)^{-2}(-\sin x) \quad \text{(by chain rule)}
\]
\[
= \frac{\sin x}{\cos^2 x} = \frac{1}{\cos x} \cdot \frac{\sin x}{\cos x} = \sec x \tan x.
\]

That is,
\[
\frac{d}{dx}(\sec x) = \sec x \tan x.
\]

**(v) The cosecant function, \(\csc x\)**

Let \(y = \csc x = \frac{1}{\sin x} = (\sin x)^{-1}\).

\[
\frac{dy}{dx} = (-1)(\sin x)^{-2}(\cos x) \quad \text{(by chain rule)}
\]
\[
= -\frac{\cos x}{\sin^2 x} = -\frac{1}{\sin x} \cdot \frac{\cos x}{\sin x} = -\csc x \cot x.
\]

That is,
\[
\frac{d}{dx}(\csc x) = -\csc x \cot x.
\]

**(vi) The cotangent function, \(\cot x\)**

Let \(y = \cot x = \frac{\cos x}{\sin x}\).

\[
\begin{aligned}
\frac{dy}{dx} &= \frac{d}{dx}\left( \frac{\cos x}{\sin x} \right) \\
&= \frac{\sin x \frac{d}{dx}(\cos x) - \cos x \frac{d}{dx}(\sin x)}{\sin^2 x} \\
&= \frac{\sin x (-\sin x) - \cos x (\cos x)}{\sin^2 x} \\
&= \frac{-\sin^2 x - \cos^2 x}{\sin^2 x} = -\frac{1}{\sin^2 x} = -\csc^2 x.
\end{aligned}
\]

That is,
\[
\frac{d}{dx}(\cot x) = -\csc^2 x.
\]

**(6) The derivatives of the inverse trigonometric functions**

**(i) The derivative of \(\arcsin x\) or \(\sin^{-1} x\)**

Let \(y = f(x) = \sin^{-1} x\).

Then \(y + \Delta y = f(x + \Delta x) = \sin^{-1}(x + \Delta x)\).

This implies, \(x = \sin y\) and \(x + \Delta x = \sin(y + \Delta y)\).

\[
\Delta x = \sin(y + \Delta y) - \sin y.
\]

\[
\frac{\Delta y}{\Delta x} = \frac{\Delta y}{\sin(y + \Delta y) - \sin y}.
\]

As \(\Delta x \to 0\), \(\Delta y \to 0\) also, so that

\[
\frac{dy}{dx} = \lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \lim_{\Delta y \to 0} \frac{1}{\frac{\sin(y + \Delta y) - \sin y}{\Delta y}} = \frac{1}{\cos y}.
\]

\[
= \frac{1}{\sqrt{1 - \sin^2 y}} = \frac{1}{\sqrt{1 - x^2}}.
\]

That is,
\[
\frac{d}{dx}(\sin^{-1} x) = \frac{1}{\sqrt{1 - x^2}}.
\]

**(ii) The derivative of \(\arccos x\) or \(\cos^{-1} x\)**

We know the identity:
\[
\sin^{-1} x + \cos^{-1} x = \frac{\pi}{2}.
\]

Differentiating both sides,
\[
\frac{d}{dx}(\sin^{-1} x) + \frac{d}{dx}(\cos^{-1} x) = 0
\]
\[
\Rightarrow \frac{d}{dx}(\cos^{-1} x) = -\frac{d}{dx}(\sin^{-1} x) = -\frac{1}{\sqrt{1 - x^2}}.
\]

or
\[
\frac{d}{dx}(\cos^{-1} x) = -\frac{1}{\sqrt{1 - x^2}}.
\]

**(iii) The derivative of \(\arctan x\) or \(\tan^{-1} x\)**

Let \(y = f(x) = \tan^{-1} x\).

Then \(x = \tan y\) and \(x + \Delta x = \tan(y + \Delta y)\).

This implies,
\[
\Delta x = \tan(y + \Delta y) - \tan y.
\]

Therefore,
\[
\frac{\Delta y}{\Delta x} = \frac{\Delta y}{\tan(y + \Delta y) - \tan y}.
\]

As \(\Delta x \to 0\), \(\Delta y \to 0\) also, so that

\[
\lim_{\Delta x \to 0} \frac{\Delta y}{\Delta x} = \frac{1}{\lim_{\Delta y \to 0} \frac{\tan(y + \Delta y) - \tan y}{\Delta y}} = \frac{1}{\frac{d}{dy}(\tan y)} = \frac{1}{\sec^2 y}.
\]

\[
= \frac{1}{1 + \tan^2 y} = \frac{1}{1 + x^2}.
\]

That is,
\[
\frac{d}{dx}(\tan^{-1} x) = \frac{1}{1 + x^2}.
\]

**(iv) The derivative of \(\arccot x\) or \(\cot^{-1} x\)**

We know the identity
\[
\tan^{-1} x + \cot^{-1} x = \frac{\pi}{2}.
\]

Differentiating,
\[
\frac{d}{dx}(\tan^{-1} x) + \frac{d}{dx}(\cot^{-1} x) = 0
\]
\[
\Rightarrow \frac{d}{dx}(\cot^{-1} x) = -\frac{d}{dx}(\tan^{-1} x) = -\frac{1}{1 + x^2}.
\]

That is,
\[
\frac{d}{dx}(\cot^{-1} x) = -\frac{1}{1 + x^2}.
\]

**(v) The derivative of \(\operatorname{arcsec} x\) or \(\sec^{-1} x\)**

\[
\frac{d}{dx}(\sec^{-1} x) = \frac{1}{x\sqrt{x^2 - 1}}.
\]

**(vi) The derivative of \(\operatorname{arccsc} x\) or \(\csc^{-1} x\)**

\[
\frac{d}{dx}(\csc^{-1} x) = -\frac{1}{x\sqrt{x^2 - 1}}.
\]

The proofs of (v) and (vi) are left as exercises.

### Example 10.7

Differentiate the following with respect to \(x\):

(i) \(y = x^3 + 5x^2 + 3x + 7\)

(ii) \(y = e^x + \sin x + 2\)

(iii) \(y = 4\csc x - \log x - 2e^x\)

(iv) \(y = \left(x - \frac{1}{x}\right)^2\)

(v) \(y = x e^x \log x\)

(vi) \(y = \frac{\cos x}{x^3}\)

(vii) \(y = \frac{\log x}{e^x}\)

(viii) Find \(f'(3)\) and \(f'(5)\) if \(f(x) = |x - 4|\).

**Solution**

(i) \(\frac{dy}{dx} = 3x^2 + 10x + 3\).

(ii) \(\frac{dy}{dx} = e^x + \cos x\).

(iii) \(\frac{dy}{dx} = -4\csc x \cot x - \frac{1}{x} - 2e^x\).

(iv) \(y = x^2 + \frac{1}{x^2} - 2 = x^2 + x^{-2} - 2\)

\(\frac{dy}{dx} = 2x - 2x^{-3} = 2x - \frac{2}{x^3}\).

(v) \(y = x e^x \log x\)

\[
\frac{dy}{dx} = x e^x \cdot \frac{1}{x} + e^x \log x \cdot 1 + x \log x \cdot e^x = e^x + e^x \log x + x e^x \log x = e^x(1 + \log x + x \log x).
\]

(vi) \(y = \frac{\cos x}{x^3}\)

\[
\frac{dy}{dx} = \frac{x^3(-\sin x) - \cos x(3x^2)}{x^6} = \frac{-x^2(x\sin x + 3\cos x)}{x^6} = -\frac{x\sin x + 3\cos x}{x^4}.
\]

(vii) \(y = \frac{\log x}{e^x} = e^{-x} \log x\)

\[
\frac{dy}{dx} = e^{-x} \cdot \frac{1}{x} + \log x \cdot e^{-x}(-1) = e^{-x} \left( \frac{1}{x} - \log x \right).
\]

(viii) \(f(x) = |x - 4| = \begin{cases} -(x - 4), & x < 4 \\ (x - 4), & x \ge 4 \end{cases}\)

For \(x < 4\), \(f'(x) = -1\). For \(x > 4\), \(f'(x) = 1\).

Therefore, \(f'(3) = -1\) and \(f'(5) = 1\).

## EXERCISE 10.2

Find the derivatives of the following functions with respect to corresponding independent variables:

1. \(f(x) = x - 3\sin x\)

2. \(y = \sin x + \cos x\)

3. \(f(x) = x \sin x\)

4. \(y = \cos x - 2\tan x\)

5. \(g(t) = t^3 \cos t\)

6. \(g(t) = 4\sec t + \tan t\)

7. \(y = e^x \sin x\)

8. \(y = \frac{\tan x}{x}\)

9. \(y = \frac{\sin x}{1 + \cos x}\)

10. \(y = \frac{x}{\sin x + \cos x}\)

11. \(y = \frac{\tan x - 1}{\sec x}\)

12. \(y = \frac{\sin x}{x^2}\)

13. \(y = \tan \theta (\sin \theta + \cos \theta)\)

14. \(y = \csc x \cot x\)

15. \(y = x \sin x \cos x\)

16. \(y = e^{-x} \cdot \log x\)

17. \(y = (x^2 + 5)\log(1 + x)e^{-3x}\)

18. \(y = \sin x^\circ\)

19. \(y = \log_{10} x\)

20. Draw the function \(f'(x)\) if \(f(x) = 2x^2 - 5x + 3\)

## 10.4.2 Examples on Chain Rule

### Example 10.8

Find \(F'(x)\) if \(F(x) = \sqrt{x^2 + 1}\).

**Solution**

Take \(u = g(x) = x^2 + 1\) and \(f(u) = \sqrt{u}\).

\(\therefore F(x) = (f \circ g)(x) = f(g(x))\).

Since \(f'(u) = \frac{1}{2}u^{-\frac{1}{2}} = \frac{1}{2\sqrt{u}}\) and \(g'(x) = 2x\), we get

\[
F'(x) = f'(g(x)) g'(x) = \frac{1}{2\sqrt{x^2 + 1}} \cdot 2x = \frac{x}{\sqrt{x^2 + 1}}.
\]

### Example 10.9

Differentiate: (i) \(y = \sin(x^2)\)  (ii) \(y = \sin^2 x\)

**Solution**

(i) The outer function is the sine function and the inner function is the squaring function.

Let \(u = x^2\). That is, \(y = \sin u\).

Therefore,
\[
\frac{dy}{dx} = \frac{dy}{du} \times \frac{du}{dx} = \cos u \times 2x = 2x \cos(x^2).
\]

(ii) Let \(u = \sin x\) so that \(y = u^2\).

\[
\frac{dy}{dx} = \frac{dy}{du} \times \frac{du}{dx} = 2u \times \cos x = 2 \sin x \cos x = \sin 2x.
\]

### Example 10.10

Differentiate \(y = \cos(\tan x)\).

**Solution**

Let \(u = \tan x\), then \(y = \cos u\).

\[
\frac{dy}{dx} = \frac{dy}{du} \times \frac{du}{dx} = -\sin u \times \sec^2 x = -\sec^2 x \sin(\tan x).
\]

### Example 10.11

Differentiate \(\sqrt{\tan \sqrt{x}}\).

**Solution**

Let \(y = \sqrt{\tan \sqrt{x}}\).

Let \(u = \sqrt{x}\), so that \(y = \sqrt{\tan u}\).

Let \(v = \tan u\), so that \(y = \sqrt{v}\).

\[
\frac{dy}{dx} = \frac{dy}{dv} \cdot \frac{dv}{du} \cdot \frac{du}{dx} = \frac{1}{2\sqrt{v}} \cdot \sec^2 u \cdot \frac{1}{2\sqrt{x}} = \frac{\sec^2(\sqrt{x})}{4\sqrt{x} \sqrt{\tan \sqrt{x}}}.
\]

### Example 10.12

Differentiate \(y = \left(\frac{t - 2}{2t + 1}\right)^9\).

**Solution**

Let \(u = \frac{t - 2}{2t + 1}\), so that \(y = u^9\).

\[
\frac{dy}{dx} = 9u^8 \cdot \frac{du}{dt} = 9\left(\frac{t - 2}{2t + 1}\right)^8 \left[ \frac{(2t + 1) \cdot 1 - (t - 2) \cdot 2}{(2t + 1)^2} \right]
\]
\[
= 9\left(\frac{t - 2}{2t + 1}\right)^8 \left[ \frac{2t + 1 - 2t + 4}{(2t + 1)^2} \right] = \frac{45(t - 2)^8}{(2t + 1)^{10}}.
\]

### Example 10.13

Differentiate \((2x + 1)^5 (x^3 - x + 1)^4\).

**Solution**

Let \(u = 2x + 1\), \(v = x^3 - x + 1\) so that \(y = u^5 v^4\).

\[
\frac{dy}{dx} = u^5 \cdot \frac{d}{dx}(v^4) + v^4 \cdot \frac{d}{dx}(u^5)
\]
\[
= u^5 \cdot 4v^3 \cdot \frac{dv}{dx} + v^4 \cdot 5u^4 \cdot \frac{du}{dx}
\]
\[
= 4u^5 v^3 (3x^2 - 1) + 5v^4 u^4 \cdot 2
\]
\[
= 4(2x + 1)^5 (x^3 - x + 1)^3 (3x^2 - 1) + 10(x^3 - x + 1)^4 (2x + 1)^4
\]
\[
= (2x + 1)^4 (x^3 - x + 1)^3 \left[ 4(2x + 1)(3x^2 - 1) + 10(x^3 - x + 1) \right]
\]
\[
= 2(2x + 1)^4 (x^3 - x + 1)^3 (17x^3 + 6x^2 - 9x + 3).
\]

### Example 10.14

Differentiate \(y = e^{\sin x}\).

**Solution**

Take \(u = \sin x\) so that \(y = e^u\).

\[
\frac{dy}{dx} = \frac{d(e^u)}{du} \times \frac{du}{dx} = e^u \times \cos x = \cos x \, e^{\sin x}.
\]

### Example 10.15

Differentiate \(2^x\).

**Solution**

Let \(y = 2^x = e^{x \log 2}\).

Take \(u = (\log 2)x\) so that \(y = e^u\).

\[
\frac{dy}{dx} = \frac{dy}{du} \times \frac{du}{dx} = e^u \times \log 2 = \log 2 \, e^{x \log 2} = (\log 2) 2^x.
\]

By using the differentiation formula for \(a^x\), one can find the derivative directly.

### Example 10.16

If \(y = \tan^{-1} \left( \frac{1 + x}{1 - x} \right)\), find \(y'\).

**Solution**

Let \(\frac{1 + x}{1 - x} = t\). Then \(y = \tan^{-1} t\).

\[
\frac{dy}{dx} = \frac{d}{dt}(\tan^{-1} t) \frac{dt}{dx}
\]
\[
= \frac{1}{1 + t^2} \cdot \frac{(1 - x) \cdot 1 - (1 + x)(-1)}{(1 - x)^2}
\]
\[
= \frac{1}{1 + \left( \frac{1 + x}{1 - x} \right)^2} \cdot \frac{(1 - x) + (1 + x)}{(1 - x)^2} = \frac{1}{1 + x^2}.
\]

Alternatively, let \(x = \tan \theta\). Then \(\frac{1 + x}{1 - x} = \frac{1 + \tan \theta}{1 - \tan \theta} = \tan \left( \frac{\pi}{4} + \theta \right)\).

\[
y = \tan^{-1} \left[ \tan \left( \frac{\pi}{4} + \theta \right) \right] = \frac{\pi}{4} + \theta = \frac{\pi}{4} + \tan^{-1} x
\]
\[
\Rightarrow \frac{dy}{dx} = \frac{1}{1 + x^2}.
\]

## EXERCISE 10.3

Differentiate the following:

1. \(y = (x^2 + 4x + 6)^5\)

2. \(y = \tan 3x\)

3. \(y = \cos (\tan x)\)

4. \(y = \sqrt[3]{1 + x^3}\)

5. \(y = e^{\sqrt{x}}\)

6. \(y = \sin(e^x)\)

7. \(F(x) = (x^3 + 4x)^7\)

8. \(h(t) = \left( t - \frac{1}{t} \right)^{\frac{3}{2}}\)

9. \(f(t) = \sqrt[3]{1 + \tan t}\)

10. \(y = \cos(a^3 + x^3)\)

11. \(y = e^{-mx}\)

12. \(y = 4\sec 5x\)

13. \(y = (2x - 5)^4 (8x^2 - 5)^{-3}\)

14. \(y = (x^2 + 1) \sqrt[3]{x^2 + 2}\)

15. \(y = x e^{-x^2}\)

16. \(s(t) = \sqrt[4]{\frac{t^3 + 1}{t^3 - 1}}\)

17. \(f(x) = \frac{x}{\sqrt{7 - 3x}}\)

18. \(y = \tan(\cos x)\)

19. \(y = \frac{\sin^2 x}{\cos x}\)

20. \(y = 5^{\frac{-1}{x}}\)

21. \(y = \sqrt{1 + 2\tan x}\)

22. \(y = \sin^3 x + \cos^3 x\)

23. \(y = \sin^2(\cos kx)\)

24. \(y = (1 + \cos^2 x)^6\)

25. \(y = \frac{e^{3x}}{1 + e^x}\)

26. \(y = \sqrt{x + \sqrt{x}}\)

27. \(y = e^{x \cos x}\)

28. \(y = \sqrt{x + \sqrt{x + \sqrt{x}}}\)

29. \(y = \sin \left( \tan \left( \sqrt{\sin x} \right) \right)\)

30. \(y = \sin^{-1} \left( \frac{1 - x^2}{1 + x^2} \right)\)

## 10.4.3 Implicit Differentiation

A function in which the dependent variable is expressed solely in terms of the independent variable \(x\), namely, \(y = f(x)\), is said to be an explicit function. For instance, \(y = \frac{1}{2}x^3 - 1\) is an explicit function, whereas an equivalent equation \(2y - x^3 + 2 = 0\) is said to define the function implicitly or \(y\) is an implicit function of \(x\).

Now, as we know, the equation

\[
x^2 + y^2 = 4 \tag{1}
\]

describes a circle of radius 2 centered at the origin. Equation (1) is not a function since for any choice of \(x\) in the interval \(-2 < x < 2\) there correspond two values of \(y\), namely

\[
f(x) = \sqrt{4 - x^2}, \quad -2 \le x \le 2 \tag{2}
\]
\[
g(x) = -\sqrt{4 - x^2}, \quad -2 \le x \le 2 \tag{3}
\]

(2) represents the top half of the circle (1) and (3) represents the bottom half of the circle (1). By considering either the top half or bottom half, of the circle, we obtain a function. We say that (1) defines at least two implicit functions of \(x\) on the interval \(-2 \le x \le 2\).

**Fig. 10.25 Fig. 10.26**

Note that both equations
\[
x^2 + [f(x)]^2 = 4 \quad \text{and} \quad x^2 + [g(x)]^2 = 4
\]
are identities on the interval \(-2 \le x \le 2\).

In general, if an equation \(F(x, y) = 0\) defines a function \(f\) implicitly on some interval, then \(F(x, f(x)) = 0\) is an identity on the interval. The graph of \(f\) is a portion (or all) of the graph of the equation \(F(x, y) = 0\).

A more complicated equation such as \(x^4 + x^3 y^3 - y^5 = 2x + 1\) may determine several implicit functions on a suitably restricted interval of the \(x\)-axis and yet it may not be possible to solve for \(y\) in terms of \(x\). However, in some cases we can determine the derivative \(\frac{dy}{dx}\) by a process known as implicit differentiation. This process consists of differentiating both sides of an equation with respect to \(x\), using the rules of differentiation and then solving for \(\frac{dy}{dx}\). Since we think of \(y\) as being determined by the given equation as a differentiable function, the chain rule, in the form of the power rule for functions, gives the result.

\[
\frac{d}{dx}(y^n) = n y^{n-1} \frac{dy}{dx},
\]
where \(n\) is an integer.

### Example 10.17

Find \(\frac{dy}{dx}\) if \(x^2 + y^2 = 1\).

**Solution**

We differentiate both sides of the equation,

\[
\frac{d}{dx}(x^2) + \frac{d}{dx}(y^2) = \frac{d}{dx}(1)
\]
\[
2x + 2y \frac{dy}{dx} = 0
\]

Solving for the derivative yields

\[
\frac{dy}{dx} = -\frac{x}{y}.
\]

### Example 10.18

Find the slopes of the tangent lines to the graph of \(x^2 + y^2 = 4\) at the points corresponding to \(x = 1\).

**Solution**

Substituting \(x = 1\) into the given equation yields \(1 + y^2 = 4 \Rightarrow y^2 = 3\) or \(y = \pm \sqrt{3}\).

Hence, there are tangent lines at \((1, \sqrt{3})\) and \((1, -\sqrt{3})\). Although \((1, \sqrt{3})\) and \((1, -\sqrt{3})\) are points on the graphs of two different implicit functions, we got the correct slope of each point.

We have
\[
\frac{dy}{dx} = -\frac{x}{y}.
\]

\[
\left. \frac{dy}{dx} \right|_{(1, \sqrt{3})} = -\frac{1}{\sqrt{3}} \quad \text{and} \quad \left. \frac{dy}{dx} \right|_{(1, -\sqrt{3})} = -\frac{1}{-\sqrt{3}} = \frac{1}{\sqrt{3}}.
\]

### Example 10.19

Find \(\frac{dy}{dx}\) if \(x^4 + x^2 y^3 - y^5 = 2x + 1\).

**Solution**

Differentiating implicitly, we have

\[
\frac{d}{dx}(x^4) + \frac{d}{dx}(x^2 y^3) - \frac{d}{dx}(y^5) = \frac{d}{dx}(2x + 1)
\]
\[
4x^3 + \left( x^2 \cdot 3y^2 \frac{dy}{dx} + y^3 \cdot 2x \right) - 5y^4 \frac{dy}{dx} = 2
\]
\[
4x^3 + 3x^2 y^2 \frac{dy}{dx} + 2xy^3 - 5y^4 \frac{dy}{dx} = 2
\]

This implies,
\[
(3x^2 y^2 - 5y^4) \frac{dy}{dx} = 2 - 4x^3 - 2xy^3
\]

or
\[
\frac{dy}{dx} = \frac{2 - 4x^3 - 2xy^3}{3x^2 y^2 - 5y^4}.
\]

### Example 10.20

Find \(\frac{dy}{dx}\) if \(\sin y = y \cos 2x\).

**Solution**

We have \(\sin y = y \cos 2x\).

Differentiating,
\[
\frac{d}{dx}(\sin y) = \frac{d}{dx}(y \cos 2x)
\]
\[
\cos y \frac{dy}{dx} = y(-2\sin 2x) + \cos 2x \frac{dy}{dx}
\]

This implies,
\[
(\cos y - \cos 2x) \frac{dy}{dx} = -2y \sin 2x
\]

or
\[
\frac{dy}{dx} = \frac{-2y \sin 2x}{\cos y - \cos 2x}.
\]

## 10.4.4 Logarithmic Differentiation

By using the rules for differentiation and the table of derivatives of the basic elementary functions, we can now find automatically the derivatives of any elementary function, except for one type, the simplest representative of which is the function \(y = x^x\). Such functions are described as power-exponential and include, in general, any function written as a power whose base and index both depend on the independent variable.

In order to find by the general rules the derivative of the power-exponential function \(y = x^x\), we take logarithms on both sides to get

\[
\log y = x \log x, \quad x > 0.
\]

Since this is an identity, the derivative of the left-hand side must be equal to the derivative of the right, we obtain by differentiating with respect to \(x\) (keeping in mind the fact that the left hand side is a function of function):

\[
\frac{1}{y} \frac{dy}{dx} = \log x + 1
\]
\[
\text{Hence} \quad \frac{dy}{dx} = y(\log x + 1) = x^x (\log x + 1).
\]

The operation consists of first taking the logarithm of the function \(f(x)\) (to base \(e\)) then differentiating is called logarithmic differentiation and its result

\[
\frac{d}{dx} (\log f(x)) = \frac{f'(x)}{f(x)}
\]

is called the logarithmic derivative of \(f(x)\).

The advantage in this method is that the calculation of derivatives of complicated functions involving products, quotients or powers can often be simplified by taking logarithms.

### Example 10.21

Find the derivative of \(y = \sqrt{x^2 + 4} \cdot \sin^2 x \cdot 2^x\).

**Solution**

Taking logarithm on both sides and using the law of logarithm,

\[
\log y = \frac{1}{2} \log(x^2 + 4) + 2 \log(\sin x) + x \log 2.
\]

This implies,
\[
\frac{y'}{y} = \frac{1}{2} \cdot \frac{2x}{x^2 + 4} + 2 \cdot \frac{\cos x}{\sin x} + \log 2 = \frac{x}{x^2 + 4} + 2\cot x + \log 2.
\]

Therefore,
\[
y' = \frac{dy}{dx} = y \left( \frac{x}{x^2 + 4} + 2\cot x + \log 2 \right).
\]

### Example 10.22

Differentiate: \(y = \frac{x^3 \sqrt{x^2 + 1}}{(3x + 2)^5}\).

**Solution**

Taking logarithm on both sides of the equation and using the rules of logarithm we have,

\[
\log y = 3 \log x + \frac{1}{2} \log(x^2 + 1) - 5 \log(3x + 2).
\]

Differentiating implicitly

\[
\frac{y'}{y} = \frac{3}{x} + \frac{1}{2} \cdot \frac{2x}{x^2 + 1} - 5 \cdot \frac{3}{3x + 2} = \frac{3}{x} + \frac{x}{x^2 + 1} - \frac{15}{3x + 2}.
\]

Therefore,
\[
\frac{dy}{dx} = y' = \frac{x^3 \sqrt{x^2 + 1}}{(3x + 2)^5} \left( \frac{3}{x} + \frac{x}{x^2 + 1} - \frac{15}{3x + 2} \right).
\]

**Steps in Logarithmic Differentiation:**

(1) Take natural logarithm on both sides of an equation \(y = f(x)\) and use the law of logarithms to simplify.

(2) Differentiate implicitly with respect to \(x\).

(3) Solve the resulting equation for \(y'\).

In general there are four cases for exponents and bases.

(1) \(\frac{d}{dx}(a^b) = 0\) (\(a\) and \(b\) are constants).

(2) \(\frac{d}{dx}[f(x)]^b = b[f(x)]^{b-1} f'(x)\)

(3) \(\frac{d}{dx}[a^{g(x)}] = a^{g(x)} (\log a) g'(x)\)

(4) \(\frac{d}{dx}[f(x)]^{g(x)} = [f(x)]^{g(x)} \left[ \frac{g(x) f'(x)}{f(x)} + \log f(x) \cdot g'(x) \right]\)

### Example 10.23

Differentiate \(y = x^{\sqrt{x}}\).

**Solution**

Take logarithm:

\[
\log y = \sqrt{x} \log x.
\]

Differentiating implicitly,

\[
\frac{y'}{y} = \sqrt{x} \cdot \frac{1}{x} + \frac{1}{2\sqrt{x}} \log x = \frac{\log x + 2}{2\sqrt{x}}.
\]

Therefore,
\[
\frac{d}{dx}(x^{\sqrt{x}}) = y' = x^{\sqrt{x}} \left( \frac{\log x + 2}{2\sqrt{x}} \right).
\]

## 10.4.5 Substitution method

It is very much useful in some processes of differentiation, in particular the differentiation involving inverse trigonometrical functions.

Consider \(f(x) = \tan^{-1} \left( \frac{2x}{1 - x^2} \right)\).

For this function \(f'(x)\) can be found out by using function of a function rule. But it is laborious. Instead we can use the substitution method.

Take \(x = \tan \theta\). Then \(\frac{2x}{1 - x^2} = \frac{2\tan\theta}{1 - \tan^2\theta} = \tan 2\theta\) and

\(f(x) = \tan^{-1}(\tan 2\theta) = 2\theta = 2\tan^{-1} x\).

\(f'(x) = \frac{2}{1 + x^2}\).

### Example 10.24

If \(y = \tan^{-1} \left( \frac{1 + x}{1 - x} \right)\), find \(y'\).

**Solution**

Let \(x = \tan \theta\).

Then \(\frac{1 + x}{1 - x} = \frac{1 + \tan \theta}{1 - \tan \theta} = \tan \left( \frac{\pi}{4} + \theta \right)\).

\[
\tan^{-1} \left( \frac{1 + x}{1 - x} \right) = \tan^{-1} \left[ \tan \left( \frac{\pi}{4} + \theta \right) \right] = \frac{\pi}{4} + \theta = \frac{\pi}{4} + \tan^{-1} x.
\]

Thus \(y = \frac{\pi}{4} + \tan^{-1} x\).

\[
y' = \frac{1}{1 + x^2}.
\]

### Example 10.25

Find \(f'(x)\) if \(f(x) = \cos^{-1}(4x^3 - 3x)\).

**Solution**

Let \(x = \cos \theta\).

Then \(4x^3 - 3x = 4\cos^3 \theta - 3\cos \theta = \cos 3\theta\) and

\[
f(x) = \cos^{-1}(\cos 3\theta) = 3\theta = 3\cos^{-1} x.
\]

Therefore,
\[
f'(x) = 3 \left( \frac{-1}{\sqrt{1 - x^2}} \right) = \frac{-3}{\sqrt{1 - x^2}}.
\]

## 10.4.6 Derivatives of variables defined by parametric equations

Consider the equations \(x = f(t)\), \(y = g(t)\).

These equations give a functional relationship between the variables \(x\) and \(y\). Given the value of \(t\) in some domain \([a, b]\), we can find \(x\) and \(y\).

If two variables \(x\) and \(y\) are defined separately as a function of an intermediating (auxiliary) variable \(t\), then the specification of a functional relationship between \(x\) and \(y\) is described as parametric and the auxiliary variable is known as parameter.

The operation of finding the direct connection between \(x\) and \(y\) without the presence of the auxiliary variable \(t\) is called elimination of the parameter. The question as to why should we deal with parametric equations is that two or more variables are reduced to a single variable, \(t\).

For example, the equation of a circle with centre \((0, 0)\) and radius \(r\) is \(x^2 + y^2 = r^2\). This equation describes the relationship between \(x\) and \(y\) and the equations

\(x = r \cos t\), \(y = r \sin t\) are parametric equations.

Conversely, if we eliminate \(t\), we get \(x^2 + y^2 = r^2\).

If \(y\) is regarded as a function of \(x\) then

\[
\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{g'(t)}{f'(t)}.
\]

If we regard \(x\) as a function of \(y\), then the derivative of \(x\) with respect to \(y\) is,

\[
\frac{dx}{dy} = \frac{\frac{dx}{dt}}{\frac{dy}{dt}} = \frac{f'(t)}{g'(t)}.
\]

In the case of the circle, then \(\frac{dy}{dx}\) is the slope of the tangent to the circle namely

\[
\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{r \cos t}{-r \sin t} = -\cot t.
\]

### Example 10.26

Find \(\frac{dy}{dx}\) if \(x = at^2\), \(y = 2at\), \(t \neq 0\).

**Solution**

We have \(x = at^2\), \(y = 2at\).

\[
\frac{dy}{dx} = \frac{y'(t)}{x'(t)} = \frac{2a}{2at} = \frac{1}{t}.
\]

### Example 10.27

Find \(\frac{dy}{dx}\) if \(x = a(t - \sin t)\), \(y = a(1 - \cos t)\).

**Solution**

We have \(x = a(t - \sin t)\), \(y = a(1 - \cos t)\).

Now \(\frac{dx}{dt} = a(1 - \cos t)\), \(\frac{dy}{dt} = a \sin t\).

Therefore,
\[
\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{a \sin t}{a(1 - \cos t)} = \frac{\sin t}{1 - \cos t}.
\]

## 10.4.7 Differentiation of one function with respect to another function

If \(y = f(x)\) is differentiable, then the derivative of \(y\) with respect to \(x\) is

\[
\frac{dy}{dx} = \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}.
\]

If \(f\) and \(g\) are differentiable functions of \(x\) and if \(\frac{dg}{dx} = g'(x) \neq 0\), then

\[
\frac{df}{dg} = \frac{\frac{df}{dx}}{\frac{dg}{dx}} = \frac{f'(x)}{g'(x)}.
\]

### Example 10.28

Find the derivative of \(x^x\) with respect to \(x \log x\).

**Solution**

Let \(u = x^x\), \(v = x \log x\).

\[
\log u = x \log x
\]
\[
\frac{1}{u} \frac{du}{dx} = x \cdot \frac{1}{x} + 1 \cdot \log x = 1 + \log x
\]
\[
\frac{du}{dx} = u(1 + \log x) = x^x (1 + \log x)
\]
\[
\frac{dv}{dx} = 1 + \log x
\]
\[
\frac{d(x^x)}{d(x \log x)} = \frac{du}{dv} = \frac{du/dx}{dv/dx} = x^x.
\]

Note that when \(g\) is the identity function \(g(x) = x\) then \(\frac{df}{dg}\) reduces to \(\frac{df}{dx} = f'(x)\).

### Example 10.29

Find the derivative of \(\tan^{-1}(1 + x^2)\) with respect to \(x^2 + x + 1\).

**Solution**

Let \(f(x) = \tan^{-1}(1 + x^2)\), \(g(x) = x^2 + x + 1\).

\[
\frac{df}{dg} = \frac{f'(x)}{g'(x)}.
\]

\[
f'(x) = \frac{1}{1 + (1 + x^2)^2} \cdot 2x = \frac{2x}{1 + (1 + 2x^2 + x^4)} = \frac{2x}{x^4 + 2x^2 + 2}
\]
\[
g'(x) = 2x + 1
\]
\[
\frac{df}{dg} = \frac{2x}{(x^4 + 2x^2 + 2)(2x + 1)}.
\]

### Example 10.30

Differentiate \(\sin(ax^2 + bx + c)\) with respect to \(\cos(lx^2 + mx + n)\).

**Solution**

Let \(u = \sin(ax^2 + bx + c)\), \(v = \cos(lx^2 + mx + n)\).

\[
\frac{du}{dv} = \frac{u'(x)}{v'(x)}.
\]

\[
u'(x) = \cos(ax^2 + bx + c)(2ax + b)
\]
\[
v'(x) = -\sin(lx^2 + mx + n)(2lx + m)
\]
\[
\frac{du}{dv} = \frac{u'(x)}{v'(x)} = \frac{(2ax + b) \cos(ax^2 + bx + c)}{-(2lx + m) \sin(lx^2 + mx + n)}.
\]

## 10.4.8 Higher order Derivatives

If \(s = s(t)\) is the position function (displacement) of an object that moves in a straight line, we know that its first derivative has the simple physical interpretation as the velocity \(v(t)\) of the object as a function of time:

\[
v(t) = s'(t) = \lim_{\Delta t \to 0} \frac{f(t + \Delta t) - f(t)}{\Delta t} = \frac{ds}{dt}.
\]

The instantaneous rate of change of velocity with respect to time is called the acceleration \(a(t)\) of the object. Then, the acceleration function is the derivative of the velocity function and is therefore the second derivative of the position function:

\[
a(t) = v'(t) = \lim_{\Delta t \to 0} \frac{v(t + \Delta t) - v(t)}{\Delta t} = \frac{d}{dt}(v(t)) = \frac{d}{dt}\left( \frac{ds}{dt} \right) = \frac{d^2 s}{dt^2} = s''(t).
\]

Thus, if \(f\) is a differentiable function of \(x\), then its first derivative \(f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}\) has a very simple geometrical interpretation as the slope of a tangent to the graph of \(y = f(x)\). Since \(f'\) is also a function of \(x\), \(f'\) may have a derivative of its own, and if it exists, denoted by \((f')' = f''\) is,

\[
f''(x) = \lim_{\Delta x \to 0} \frac{f'(x + \Delta x) - f'(x)}{\Delta x} = \frac{d}{dx}(f'(x)) = \frac{d}{dx}\left( \frac{d}{dx} f(x) \right) = \frac{d^2 f}{dx^2} = \frac{d^2 y}{dx^2}.
\]

Other notations are \(D^2 f(x) = D^2 y = y_2 = y''\).

We can interpret a second derivative as a rate of change of a rate of change. But its geometrical interpretation is not so simple. However, there is a close connection exists between the second derivative \(f''(x)\) and the radius of curvature of the graph of \(y = f(x)\) which you will learn in higher classes.

Similarly, if \(f''\) exists, it might or might not be differentiable. If it is, then the derivative of \(f''\) is called third derivative of \(f\) and is denoted by

\[
f'''(x) = \frac{d^3 y}{dx^3} = y''' = y_3.
\]

We can interpret the third derivative physically in case when the function is the position function \(f(t)\) of an object that moves along a straight line. Because \(s'' = (s')' = a'(t)\), the third derivative of the position function is the derivative of the acceleration function and is called the jerk:

\[
j = \frac{da}{dt} = \frac{d^3 s}{dt^3}.
\]

Thus, jerk is the rate of change of acceleration.

It is aptly named because a large jerk means a sudden change in acceleration, which causes an abrupt movement in a vehicle.

### Example 10.31

Find \(y'\), \(y''\) and \(y'''\) if \(y = x^3 - 6x^2 - 5x + 3\).

**Solution**

We have,
\[
y = x^3 - 6x^2 - 5x + 3,
\]
\[
y' = 3x^2 - 12x - 5,
\]
\[
y'' = 6x - 12,
\]
\[
y''' = 6.
\]

### Example 10.32

Find \(y''\) if \(y = \frac{1}{x}\).

**Solution**

We have,
\[
y = \frac{1}{x} = x^{-1},
\]
\[
y' = -1x^{-2} = -\frac{1}{x^2},
\]
\[
y'' = (-1)(-2)x^{-3} = \frac{2}{x^3}.
\]

### Example 10.33

Find \(y''\) if \(y = \sin 3x\).

**Solution**

We have,
\[
y = \sin 3x,
\]
\[
y' = \cos 3x \times 3 = 3\cos 3x,
\]
\[
y'' = 3(-\sin 3x) \times 3 = -9\sin 3x.
\]

### Example 10.34

Find \(y'''\) if \(y = e^{ax} \sin bx\).

**Solution**

\[
y' = e^{ax} [a \sin bx + b \cos bx],
\]
\[
y'' = e^{ax} [(a^2 - b^2) \sin bx + 2ab \cos bx],
\]
\[
y''' = e^{ax} [(a^3 - 3ab^2) \sin bx + (3a^2b - b^3) \cos bx].
\]

### Example 10.35

Find \(\frac{d^2 y}{dx^2}\) if \(x = a\cos t\), \(y = a\sin t\).

**Solution**

Differentiating the function implicitly with respect to \(x\), we get

\[
\frac{dy}{dx} = \frac{\frac{dy}{dt}}{\frac{dx}{dt}} = \frac{a\cos t}{-a\sin t} = -\frac{\cos t}{\sin t}.
\]

\[
\frac{d^2 y}{dx^2} = \frac{d}{dx}\left( \frac{dy}{dx} \right) = \frac{d}{dx}\left( -\frac{\cos t}{\sin t} \right) = \frac{d}{dt}\left( -\frac{\cos t}{\sin t} \right) \frac{dt}{dx}
\]
\[
= -[-\csc^2 t] \times \frac{1}{x'(t)} = \csc^2 t \times \frac{1}{-a\sin t} = -\frac{\csc^3 t}{a}.
\]

### Example 10.36

Find \(\frac{d^2 y}{dx^2}\) if \(x^2 + y^2 = 4\).

**Solution**

We have \(x^2 + y^2 = 4\).

As before, \(\frac{dy}{dx} = -\frac{x}{y}\).

Hence, by the quotient rule

\[
\frac{d^2 y}{dx^2} = -\frac{d}{dx}\left( \frac{x}{y} \right) = -\frac{y \cdot 1 - x \cdot \frac{dy}{dx}}{y^2} = -\frac{y - x\left( -\frac{x}{y} \right)}{y^2}
\]
\[
= -\frac{y + \frac{x^2}{y}}{y^2} = -\frac{\frac{x^2 + y^2}{y}}{y^2} = -\frac{x^2 + y^2}{y^3} = -\frac{4}{y^3}.
\]

## EXERCISE 10.4

Find the derivatives of the following (1 - 18):

1. \(y = x^{\cos x}\)

2. \(y = x \log x + (\log x)^x\)

3. \(xy = e^{(x - y)}\)

4. \(x^y = y^x\)

5. \(\sqrt{\log(\cos x)}\)

6. \(\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1\)

7. \(\tan^{-1}\left( \frac{y}{x} \right) = \frac{x^2 + y^2}{x}\)

8. \(\tan(x + y) + \tan(x - y) = x\)

9. If \(\cos(xy) = x\), show that \(\frac{dy}{dx} = -\frac{1 + y \sin(xy)}{x \sin(xy)}\)

10. \(\tan^{-1} \left( \frac{\sqrt{1 - \cos x}}{\sqrt{1 + \cos x}} \right)\)

11. \(\tan^{-1} \left( \frac{6x}{1 - 9x^2} \right)\)

12. \(\cos \left( 2\tan^{-1} \sqrt{\frac{1 - x}{1 + x}} \right)\)

13. \(x = a\cos^3 t\), \(y = a\sin^3 t\)

14. \(x = a(\cos t + t\sin t)\), \(y = a(\sin t - t\cos t)\)

15. \(x = \frac{2t}{1 + t^2}\), \(y = \frac{1 - t^2}{1 + t^2}\)

16. \(\cos^{-1} \left( \frac{1 - x^2}{1 + x^2} \right)\)

17. \(\sin^{-1}(3x - 4x^3)\)

18. \(\tan^{-1} \left( \frac{1 - \cos x}{\sin x} \right)\)

19. Find the derivative of \(\sin x^2\) with respect to \(x^2\).

20. Find the derivative of \(\sin^{-1} \left( \frac{2x}{1 + x^2} \right)\) with respect to \(\tan^{-1} x\).

21. If \(u = \tan^{-1} \left( \frac{x}{\sqrt{1 - x^2}} \right)\) and \(v = \sin^{-1}(2x\sqrt{1 - x^2})\), find \(\frac{du}{dv}\).

22. Find the derivative with \(\tan^{-1} \left( \frac{\sin x}{1 + \cos x} \right)\) with respect to \(\tan^{-1} \left( \frac{\cos x}{1 + \sin x} \right)\).

23. If \(y = \sin^{-1} x\) then find \(y''\).

24. If \(y = e^{\tan^{-1} x}\), show that \((1 + x^2)y'' + (2x - 1)y' = 0\).

25. If \(y = \frac{\sin^{-1} x}{\sqrt{1 - x^2}}\), show that \((1 - x^2)y'' - 3xy' - y = 0\).

26. If \(x = a(\theta + \sin\theta)\), \(y = a(1 - \cos\theta)\) then prove that at \(\theta = \frac{\pi}{2}\), \(y'' = \frac{1}{a}\).

27. If \(\sin y = x \sin(a + y)\), then prove that \(\frac{dy}{dx} = \frac{\sin^2(a + y)}{\sin a}\), \(a \neq n\pi\).

28. If \(y = (\cos^{-1} x)^2\), prove that \((1 - x^2) \frac{d^2 y}{dx^2} - x \frac{dy}{dx} - 2 = 0\). Hence find \(y''\) when \(x = 0\).

## EXERCISE 10.5

Choose the correct or the most suitable answer from the given four alternatives.

1. \(\frac{d}{dx}\left( \frac{2}{\pi} \sin x^\circ \right)\) is

   (1) \(\frac{\pi}{180} \cos x^\circ\) (2) \(\frac{1}{90} \cos x^\circ\) (3) \(\frac{\pi}{90} \cos x^\circ\) (4) \(\frac{2}{\pi} \cos x^\circ\)

2. If \(y = f(x^2 + 2)\) and \(f'(3) = 5\), then \(\frac{dy}{dx}\) at \(x = 1\) is

   (1) 5 (2) 25 (3) 15 (4) 10

3. If \(y = \frac{1}{4}u^4\), \(u = \frac{2}{3}x^3 + 5\), then \(\frac{dy}{dx}\) is

   (1) \(\frac{1}{27}x^2(2x^3 + 15)^3\) (2) \(\frac{2}{27}x(2x^3 + 5)^3\)

   (3) \(\frac{2}{27}x^2(2x^3 + 15)^3\) (4) \(-\frac{2}{27}x(2x^3 + 5)^3\)

4. If \(f(x) = x^2 - 3x\), then the points at which \(f(x) = f'(x)\) are

   (1) both positive integers (2) both negative integers

   (3) both irrational (4) one rational and another irrational

5. If \(y = \frac{1}{a - z}\), then \(\frac{dz}{dy}\) is

   (1) \((a - z)^2\) (2) \(-(z - a)^2\) (3) \((z + a)^2\) (4) \(-(z + a)^2\)

6. If \(y = \cos(\sin x^2)\), then \(\frac{dy}{dx}\) at \(x = \sqrt{\frac{\pi}{2}}\) is

   (1) \(-2\) (2) \(2\) (3) \(-2\sqrt{\frac{\pi}{2}}\) (4) \(0\)

7. If \(y = mx + c\) and \(f(0) = f'(0) = 1\), then \(f(2)\) is

   (1) 1 (2) 2 (3) 3 (4) \(-3\)

8. If \(f(x) = x\tan^{-1} x\), then \(f'(1)\) is

   (1) \(1 + \frac{\pi}{4}\) (2) \(\frac{1}{2} + \frac{\pi}{4}\) (3) \(\frac{1}{2} - \frac{\pi}{4}\) (4) \(2\)

9. \(\frac{d}{dx}(e^{x + 5\log x})\) is

   (1) \(e^x x^4 (x + 5)\) (2) \(e^x x (x + 5)\) (3) \(e^x + \frac{5}{x}\) (4) \(e^x - \frac{5}{x}\)

10. If the derivative of \((ax - 5)e^{3x}\) at \(x = 0\) is \(-13\), then the value of \(a\) is

    (1) 8 (2) \(-2\) (3) 5 (4) 2

11. If \(x = \frac{2t}{1 + t^2}\), \(y = \frac{1 - t^2}{1 + t^2}\), then \(\frac{dy}{dx}\) is

    (1) \(-\frac{y}{x}\) (2) \(\frac{y}{x}\) (3) \(-\frac{x}{y}\) (4) \(\frac{x}{y}\)

12. If \(x = a\sin\theta\) and \(y = b\cos\theta\), then \(\frac{d^2 y}{dx^2}\) is

    (1) \(\frac{a}{b^2} \sec^2\theta\) (2) \(-\frac{b}{a^2} \sec^3\theta\) (3) \(\frac{b}{a^2} \sec^2\theta\) (4) \(-\frac{b}{a^2} \sec^3\theta\)

13. The differential coefficient of \(\log_{10} x\) with respect to \(\log_{10} e\) is

    (1) \(1\) (2) \(-(\log_{10} x)^2\) (3) \((\log_e 10)^2\) (4) \(x^2 \log_{10} e\)

14. If \(f(x) = x + 2\), then \(f'(f(x))\) at \(x = 4\) is

    (1) 8 (2) 1 (3) 4 (4) 5

15. If \(y = (1 - x)^2\), then \(\frac{d^2 y}{dx^2}\) is

    (1) \(2\) (2) \(-2\) (3) \(2 - 2x\) (4) \(2 - 4x\)

16. If \(pv = 81\), then \(\frac{dp}{dv}\) at \(v = 9\) is

    (1) 1 (2) \(-1\) (3) 2 (4) \(-2\)

17. If \(f(x) = \begin{cases} x - 5 & \text{if } x \le 1 \\ 4x^2 - 9 & \text{if } 1 < x < 2 \\ 3x + 4 & \text{if } x \ge 2 \end{cases}\), then the right hand derivative of \(f(x)\) at \(x = 2\) is

    (1) 0 (2) 2 (3) 3 (4) 4

18. It is given that \(f'(a)\) exists, then \(\lim_{x \to a} \frac{x f(a) - a f(x)}{x - a}\) is

    (1) \(f(a) - a f'(a)\) (2) \(f'(a)\) (3) \(-f'(a)\) (4) \(f(a) + a f'(a)\)

19. If \(f(x) = \begin{cases} x + 1 & \text{when } x < 2 \\ 2x - 1 & \text{when } x \ge 2 \end{cases}\), then \(f'(2)\) is

    (1) 0 (2) 1 (3) 2 (4) does not exist

20. If \(g(x) = (x^2 + 2x + 1)f(x)\) and \(f(0) = 5\) and \(\lim_{x \to 0} \frac{f(x) - 5}{x} = 4\), then \(g'(0)\) is

    (1) 20 (2) 14 (3) 18 (4) 12

## Summary

- Non-existence of the derivative of \(y = f(x)\) at \(x = x_0\) implies that the graph of \(y = f(x)\) fails to admit tangent at \((x_0, f(x_0))\).

- Geometrically, if the graph of \(y = f(x)\) admits cups (\(\lor\)) or caps (\(\land\)) at \(x = x_0\) then derivative at \(x = x_0\) does not exist.

- Derivative should be understood as a process not as a set of rules.

- Differentiability implies continuity, but the converse is not true.

- The sum, difference, product and composite of differentiable function is differentiable, and the quotient of two differentiable function is differentiable wherever it is defined.

\[
\begin{aligned}
\frac{d}{dx}(f(x) \pm g(x)) &= \frac{d}{dx}f(x) \pm \frac{d}{dx}g(x) \\
\frac{d}{dx}(f(x)g(x)) &= f(x)\frac{dg}{dx} + g(x)\frac{df}{dx} \\
\frac{d}{dx}((f \circ g)(x)) &= f'(g(x)) g'(x) \\
\frac{d}{dx}\left( \frac{f(x)}{g(x)} \right) &= \frac{g(x)f'(x) - f(x)g'(x)}{g^2(x)}, \quad \text{where } g(x) \neq 0.
\end{aligned}
\]
