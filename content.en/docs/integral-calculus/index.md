---
title: 'integral calculus'
weight: 11
summary: "This chapter introduces integral calculus as the reverse process of differentiation, focusing on indefinite integrals (antiderivatives) and definite integrals, which are used to compute areas, volumes, and accumulations of quantities over an interval. It covers various methods of integration, including substitution, integration by parts, partial fractions, and standard integral formulas, along with the properties of definite integrals and the fundamental theorem of calculus. The chapter also discusses applications such as finding the area under curves, area between curves, and average value of functions, providing essential tools for solving real-world problems in physics, engineering, and economics."
---

# 11. Integral Calculus

## 11.1 Introduction

Gottfried Wilhelm Leibniz (1646-1716) and Sir Isaac Newton (1643-1727) independently discovered calculus in the mid-17th century. Leibniz, a German philosopher, mathematician, and political adviser, importantly both as a metaphysician and as a logician, was a distinguished independent inventor of the Differential and Integral Calculus. Sir Isaac Newton had created an expression for the area under a curve by considering a momentary increase at a point.

In effect, the fundamental theorem of calculus was built into his calculations. His work and discoveries were not limited to mathematics; he also developed theories in optics and gravitation.

One cannot imagine a world without differentiation and integration. In this century, we witnessed remarkable scientific advancement owing to the ingenious application of these two basic components of Mathematics. Calculus serve as unavoidable tool for finding solutions to the variety of problems that arise in physics, astronomy, engineering, chemistry, geology, biology, and social sciences.

Calculus deals principally with two geometric problems.

(i) The problem of finding SLOPE of the tangent line to the curve, is studied by the limiting process known as differentiation and (ii) Problem of finding the AREA of a region under a curve is studied by another limiting process called Integration.

In chapters 9 and 10, we have studied the differential calculus. In this chapter let us study some fundamentals of integration.

Consider some simple situations illustrated below.

### Situation 1

The shortest distance between two points \(A\) and \(B\) in a plane is the line segment joining the straight line \(A\) and \(B\). Suppose it is required to find the line connecting two points \(A\) and \(B\) that do not lie on a vertical line such that a moving particle slides down on this line from \(A\) to \(B\) in the shortest time (minimum time). Most of us believe that the shortest distance path will take the shortest time.

Certainly this route is not the shortest time route joining the points \(A\) and \(B\), because the velocity of the motion in the straight line will be comparatively slow; whereas it take a curve that is steeper near \(A\), even though the path becomes longer, a considerable portion of the distance will be covered at a greater speed. The solution to this problem is solved by Integral calculus. This is called Brachistochrone problem which initiates the study of calculus of variation using integral tool.

### Situation 2

In elementary geometry we have learnt to evaluate the measure of the following regular shape of the figures given below by using known formulae.

How can the measure of the following figures given by functions be calculated?

Though the problems look so difficult, integral calculus solves it without any difficulties.

### Situation 3

At a particular moment, a student needs to stop his speedy bike to avoid a collision with the barrier ahead at a distance 40 metres away from him. Immediately he slows (acceleration) down the bike applying brake at a rate of 8 meter/second². If the bike is moving at a speed of \(24\mathrm{m/s}\), when the brakes are applied, will it stop before collision?

Also look at the following problems that occur naturally in our life.

1. What speed has to be applied to fire a satellite upward so that it never returns to the earth?
2. What is the radius of the smallest circular disk that can cover every isosceles triangle of given perimeter \(P\)
3. What volume of material is removed from a solid sphere of radius \(2r\) if a hole of radius \(r\) is drilled through the centre?
4. If a strain of bacteria grows at a rate proportional to the amount present and if the population doubles in one hour, how much will it increase at the end of two hours?

Integration will answer for all the above problems.

### Learning Objectives

On completion of this chapter, the students are expected to

- understand the definition of an indefinite integral as a result of reversing the process of differentiation
- find the indefinite integrals of sums, differences and constant multiples of certain elementary functions.
- use the appropriate techniques to find the indefinite integrals of composite functions.
- apply integration to find the function, when the rate of change of function is given.

## 11.2 Newton-Leibnitz Integral

Integral calculus is mainly divided into indefinite integrals and definite integrals. In this chapter, we study indefinite integration, the process of obtaining a function from its derivative.

We are already familiar with inverse operations. \((+,-), (x,\div), \left((\cdot)^{n}, \sqrt[n]{}\right)\) are some pairs of inverse operations. Similarly differentiation and integrations \((d, \int)\) are also inverse operations. In this section we develop the inverse operation of differentiation called 'antidifferentiation'.

### Definition 11.1

A function \(F(x)\) is called an **antiderivative** (Newton-Leibnitz integral or primitive) of a function \(f(x)\) on an interval \(I\) if

\[
F^{\prime}(x) = f(x), \text{ for every value of } x \text{ in } I
\]

If \(F(x) = x^{2} + 5\) then

\[
F^{\prime}(x) = 2x.
\]

Thus if \(f(x)\) is defined by

\[
f(x) = 2x, \text{ then}
\]

we say that \(f(x)\) is the derivative of \(F(x)\) and that \(F(x)\) is an antiderivative of \(f(x)\)

Consider the following table

| F(x) | F'(x) = f(x) | Antiderivative of f(x) = 2x |
|------|--------------|----------------------------|
| P(x) = x² + 0 | P'(x) = 2x | F(x) = x² + ? |
| Q(x) = x² + 2 | Q'(x) = 2x | |
| H(x) = x² - 1 | H'(x) = 2x | |

We can see that the derivative of \(F(x), P(x), Q(x)\) and \(H(x)\) is \(f(x)\) but in reverse the antiderivatives of \(f(x) = 2x\) is not unique. That is the antiderivatives of \(f(x)\) is a family of infinitely many functions.

### Theorem 11.1

If \(F(x)\) is a particular antiderivative of a function \(f(x)\) on an interval \(I\) then every antiderivative of \(f(x)\) on \(I\) is given by

\[
\int f(x)dx = F(x) + c
\]

where \(c\) is called an **arbitrary constant**, and all antiderivatives of \(f(x)\) on \(I\) can be obtained by assigning particular value to \(c\).

- The function \(f(x)\) is called **Integrand**.
- The variable \(x\) in \(dx\) is called **variable of integration** or **integrator**.
- The process of finding the integral is called **integration** or **antidifferentiation** (Newton-Leibnitz integral).

The peculiar integral sign \(\int\) originates in an elongated S (like \(\Sigma\)) which stands for sum.

Often in applications involving differentiation it is desired to find a particular integral antiderivative that satisfies certain conditions called **initial condition** or **boundary conditions**.

For instance, if an equation involving \(\frac{dy}{dx}\) is given as well as the initial condition that \(y = y_{1}\) when \(x = x_{1}\), then after the set of all antiderivatives is found, if \(x\) and \(y\) are replaced by \(x_{1}\) and \(y_{1}\), a particular value of the arbitrary constant is determined. With this value of \(c\) a particular antiderivative is obtained.

### Illustration 11.2

Suppose we wish to find the particular antiderivative satisfying the equation

\[
\frac{dy}{dx} = 2x
\]

and the initial condition that \(y = 10\) when \(x = 2\). From the given equation

\[
\frac{dy}{dx} = 2x
\]
\[
y = \int 2x \, dx
\]
\[
y = x^{2} + c
\]

We substitute \(y = 10\) when \(x = 2\), in the above equation

\[
10 = 2^{2} + c \Rightarrow c = 6
\]

When this value \(c = 6\) is substituted we obtain

\[
y = x^{2} + 6
\]

which gives the particular antiderivative desired.

## 11.3 Basic Rules of Integration

### Standard results:

Since integration is the reverse process of differentiation, the basic integration formulae given below can be derived directly from their corresponding derivative formulae.

| Derivatives | Antiderivatives |
|-------------|------------------|
| \(\frac{d}{dx}(c) = 0\), where \(c\) is a constant | \(\int 0 \, dx = c\), where \(c\) is a constant |
| \(\frac{d}{dx}(kx) = k\), where \(k\) is a constant | \(\int k \, dx = kx + c\) where \(c\) is a constant |
| \(\frac{d}{dx}\left(\frac{x^{n+1}}{n+1}\right) = x^{n}\) | \(\int x^{n} dx = \frac{x^{n+1}}{n+1} + c, n \neq -1\) (Power rule) |
| \(\frac{d}{dx}(\log x) = \frac{1}{x}\) | \(\int \frac{1}{x} dx = \log|x| + c\) |
| \(\frac{d}{dx}(-\cos x) = \sin x\) | \(\int \sin x \, dx = -\cos x + c\) |
| \(\frac{d}{dx}(\sin x) = \cos x\) | \(\int \cos x \, dx = \sin x + c\) |
| \(\frac{d}{dx}(\tan x) = \sec^{2} x\) | \(\int \sec^{2} x \, dx = \tan x + c\) |

Integrate the following with respect to \(x\).

\[
\frac{1}{\cos^{2}x} \qquad \text{(ii)} \qquad \frac{\cot x}{\sin x} \qquad \text{(iii)} \qquad \frac{\sin x}{\cos^{2}x} \qquad \text{(iv)} \qquad \frac{1}{\sqrt{1 - x^{2}}}
\]

**Solution**

\[
\int \frac{1}{\cos^{2}x} dx = \int \sec^{2} x \, dx = \tan x + c
\]
\[
\int \frac{\cot x}{\sin x} dx = \int \csc x \cot x \, dx = -\csc x + c
\]
\[
\int \frac{\sin x}{\cos^{2}x} dx = \int \frac{\sin x}{\cos x} \cdot \frac{1}{\cos x} dx = \int \tan x \sec x \, dx = \sec x + c
\]
\[
\int \frac{1}{\sqrt{1 - x^{2}}} dx = \sin^{-1}x + c
\]

### Example 11.3

Integrate the following with respect to \(x\):

\[
\frac{1}{e^{-x}} \qquad \text{(ii)} \qquad \frac{x^{2}}{x^{3}} \qquad \text{(iii)} \qquad \frac{1}{x^{3}} \qquad \text{(iv)} \qquad \frac{1}{1 + x^{2}}
\]

**Solution**

\[
\int \frac{1}{e^{-x}} dx = \int e^{x} dx = e^{x} + c
\]
\[
\int \frac{x^{2}}{x^{3}} dx = \int \frac{1}{x} dx = \log |x| + c
\]
\[
\int \frac{1}{x^{3}} dx = \int x^{-3} dx = \frac{x^{-3 + 1}}{-3 + 1} + c = -\frac{1}{2x^{2}} + c
\]
\[
\int \frac{1}{1 + x^{2}} dx = \tan^{-1}x + c
\]

## Exercise 11.1

Integrate the following with respect to \(x\):

(1) (i) \(x^{11}\) (ii) \(\frac{1}{x^{7}}\) (iii) \(\sqrt[3]{x^{4}}\) (iv) \((x^{5})^{\frac{1}{8}}\)

(2) (i) \(\frac{1}{\sin^{2}x}\) (ii) \(\frac{\tan x}{\cos x}\) (iii) \(\frac{\cos x}{\sin^{2}x}\) (iv) \(\frac{1}{\cos^{2}x}\)

(3) (i) \(12^{3}\) (ii) \(\frac{x^{24}}{x^{25}}\) (iii) \(e^{x}\)

(4) (i) \((1 + x^{2})^{-1}\) (ii) \((1 - x^{2})^{-\frac{1}{2}}\)

## 11.4 Integrals of the Form \(\int f(ax + b)dx\)

We know that

\[
\frac{d}{dx}\left[\frac{(x - a)^{10}}{10}\right] = (x - a)^{9} \Rightarrow \int (x - a)^{9} dx = \frac{(x - a)^{10}}{10} + c
\]
\[
\frac{d}{dx}\left[\sin (x + k)\right] = \cos (x + k) \Rightarrow \int \cos (x + k) dx = \sin (x + k) + c
\]

It is clear that whenever a constant is added or subtracted with the independent variable \(x\), the fundamental formulae remain the same.

But

\[
\frac{d}{dx}\left[\frac{1}{a}\sin (ax + b)\right] = \cos (ax + b) \Rightarrow \int \cos (ax + b) dx = \frac{1}{a}\sin (ax + b) + c
\]

Here, if any constant is multiplied with the independent variable \(x\), then the same fundamental formula can be used after dividing it by the coefficient of \(x\)

That is, if \(\int f(x)dx = g(x) + c\), then \(\int f(ax + b)dx = \frac{1}{a} g(ax + b) + c\)

The above formula can also be derived by using substitution method, which will be studied later.

### Example 11.4

Evaluate the following with respect to \(x\):

(i) \(\int (4x + 5)^{6} dx\) (ii) \(\int \sqrt{(15 - 2x)} dx\) (iii) \(\int \frac{1}{(3x + 7)^{4}} dx\)

**Solution**

\[
\int (4x + 5)^{6} dx = \frac{1}{4}\frac{(4x + 5)^{6 + 1}}{6 + 1} = \frac{(4x + 5)^{7}}{28} + c
\]

\[
\int \sqrt{(15 - 2x)} dx = \int (15 - 2x)^{\frac{1}{2}} dx = \left(\frac{1}{-2}\right)\frac{(15 - 2x)^{\frac{3}{2}}}{\frac{3}{2}} = -\frac{(15 - 2x)^{\frac{3}{2}}}{3} + c
\]

\[
\int \frac{1}{(3x + 7)^{4}} dx = \int (3x + 7)^{-4} dx = \frac{1}{3}\frac{(3x + 7)^{-4 + 1}}{-4 + 1} = -\frac{1}{9(3x + 7)^{3}} + c
\]

### Example 11.5

Integrate the following with respect to \(x\):

(i) \(\sin (2x + 4)\) (ii) \(\sec^{2}(3 + 4x)\) (iii) \(\csc(ax + b)\cot(ax + b)\)

**Solution**

\[
\int \sin (2x + 4) dx = \left(\frac{1}{2}\right)\left(-\cos (2x + 4)\right) + c = -\frac{1}{2}\cos (2x + 4) + c
\]
\[
\int \sec^{2}(3 + 4x) dx = \frac{1}{4}\tan (3 + 4x) + c
\]
\[
\int \csc(ax + b)\cot(ax + b) dx = \left(\frac{1}{a}\right)\left(-\csc(ax + b)\right) + c = -\frac{1}{a}\csc(ax + b) + c
\]

### Example 11.6

Integrate the following with respect to \(x\):

(i) \(e^{3x}\) (ii) \(e^{5 - 4x}\) (iii) \(\frac{1}{(3x - 2)}\) (iv) \(\frac{1}{(5 - 4x)}\)

**Solution**

\[
\int e^{3x} dx = \frac{1}{3} e^{3x} + c
\]
\[
\int e^{5 - 4x} dx = -\frac{e^{5 - 4x}}{4} + c
\]
\[
\int \frac{1}{(3x - 2)} dx = \frac{1}{3}\log |(3x - 2)| + c
\]
\[
\int \frac{1}{(5 - 4x)} dx = -\frac{1}{4}\log |(5 - 4x)| + c
\]

### Example 11.7

Integrate the following with respect to \(x\):

(i) \(\frac{1}{1 + (2x)^{2}}\) (ii) \(\frac{1}{\sqrt{1 - (9x)^{2}}}\) (iii) \(\frac{1}{\sqrt{1 - 25x^{2}}}\)

**Solution**

\[
\int \frac{1}{1 + (2x)^{2}} dx = \frac{1}{2}\tan^{-1}(2x) + c
\]
\[
\int \frac{1}{\sqrt{1 - (9x)^{2}}} dx = \frac{1}{9}\sin^{-1}(9x) + c
\]
\[
\int \frac{1}{\sqrt{1 - 25x^{2}}} dx = \int \frac{1}{\sqrt{1 - (5x)^{2}}} dx = \frac{1}{5}\sin^{-1}(5x) + c
\]

## Exercise 11.2

Integrate the following functions with respect to \(x\):

(1) (i) \((x + 5)^{6}\) (ii) \(\frac{1}{(2 - 3x)^{4}}\) (iii) \(\sqrt{3x + 2}\)

(2) (i) \(\sin 3x\) (ii) \(\cos (5 - 11x)\) (iii) \(\csc^{2}(5x - 7)\)

(3) (i) \(e^{3x - 6}\) (ii) \(e^{8 - 7x}\) (iii) \(\frac{1}{6 - 4x}\)

(4) (i) \(\sec^{2}\frac{x}{5}\) (ii) \(\csc(5x + 3)\cot(5x + 3)\) (iii) \(\sec(2 - 15x)\tan(2 - 15x)\)

(5) (i) \(\frac{1}{\sqrt{1 - (4x)^{2}}}\) (ii) \(\frac{1}{\sqrt{1 - 81x^{2}}}\) (iii) \(\frac{1}{1 + 36x^{2}}\)

## 11.5 Properties of Integrals

1. If \(k\) is any constant, then \(\int k f(x) dx = k \int f(x) dx\)

2. \(\int (f_{1}(x) \pm f_{2}(x)) dx = \int f_{1}(x) dx \pm \int f_{2}(x) dx\)

**Note 11.1**

The above two properties can be combined and extended as

\[
\int (k_{1}f_{1}(x) \pm k_{2}f_{2}(x) \pm k_{3}f_{3}(x) \pm \dots \pm k_{n}f_{n}(x)) dx
\]
\[
= k_{1}\int f_{1}(x) dx \pm k_{2}\int f_{2}(x) dx \pm k_{3}\int f_{3}(x) dx \pm \dots \pm k_{n}\int f_{n}(x) dx.
\]

That is, the integration of the linear combination of a finite number of functions is equal to the linear combination of their integrals.

### Example 11.8

Integrate the following with respect to \(x\):

(i) \(5x^{4}\) (ii) \(5x^{2} - 4 + \frac{7}{x} + \frac{2}{\sqrt{x}}\) (iii) \(2\cos x - 4\sin x + 5\sec^{2}x + \csc^{2}x\)

**Solution**

\[
\int 5x^{4} dx = 5\int x^{4} dx = 5\frac{x^{4 + 1}}{4 + 1} = 5\frac{x^{5}}{5} = x^{5} + c.
\]

\[
\int \left(5x^{2} - 4 + \frac{7}{x} + \frac{2}{\sqrt{x}}\right) dx = 5\int x^{2} dx - 4\int dx + 7\int \frac{1}{x} dx + 2\int \frac{1}{\sqrt{x}} dx
\]
\[
= 5\frac{x^{2 + 1}}{2 + 1} - 4x + 7\log |x| + 2\frac{x^{\frac{1}{2} + 1}}{-\frac{1}{2} + 1} + c
\]
\[
= \frac{5}{3}x^{3} - 4x + 7\log |x| + 4\sqrt{x} + c
\]

\[
\int (2\cos x - 4\sin x + 5\sec^{2}x + \csc^{2}x) dx
\]
\[
= 2\int \cos x \, dx - 4\int \sin x \, dx + 5\int \sec^{2}x \, dx + \int \csc^{2}x \, dx
\]
\[
= 2\sin x + 4\cos x + 5\tan x - \cot x + c
\]

### Example 11.9

Evaluate the following integrals:

(i) \(\frac{12}{(4x - 5)^{3}} + \frac{6}{3x + 2} + 16e^{4x + 3}\) (ii) \(\frac{15}{\sqrt{5x - 4}} - 8\cot(4x + 2)\csc(4x + 2)\)

**Solution**

\[
\int \left(\frac{12}{(4x - 5)^{3}} + \frac{6}{3x + 2} + 16e^{4x + 3}\right) dx
\]
\[
= 12\int \frac{1}{(4x - 5)^{3}} dx + 6\int \frac{1}{3x + 2} dx + 16\int e^{4x + 3} dx
\]
\[
= 12\left(\frac{1}{4}\right)\left(-\frac{1}{2(4x - 5)^{2}}\right) + 6\left(\frac{1}{3}\right)\log|3x + 2| + 16\left(\frac{1}{4}\right)e^{4x + 3} + c
\]
\[
= -\frac{3}{2(4x - 5)^{2}} + 2\log|3x + 2| + 4e^{4x + 3} + c.
\]

\[
\int \left(\frac{15}{\sqrt{5x - 4}} - 8\cot(4x + 2)\csc(4x + 2)\right) dx
\]
\[
= 15\int \frac{1}{\sqrt{5x - 4}} dx - 8\int \cot(4x + 2)\csc(4x + 2) dx
\]
\[
= 15\left(\frac{1}{5}\right)\left(2\sqrt{5x - 4}\right) - 8\left(\frac{1}{4}\right)\left(-\csc(4x + 2)\right) + c
\]
\[
= 6\sqrt{5x - 4} + 2\csc(4x + 2) + c.
\]

## Exercise 11.3

Integrate the following with respect to \(x\):

(1) \((x+4)^{5} + \frac{5}{(2-5x)^{4}} - \csc^{2}(3x-1)\)

(2) \(4\cos(5-2x) + 9e^{3x-6} + \frac{24}{6-4x}\)

(3) \(\sec^{2}\frac{x}{5} + 18\cos 2x + 10\sec(5x+3)\tan(5x+3)\)

(4) \(\frac{8}{\sqrt{1-(4x)^{2}}} + \frac{27}{\sqrt{1-9x^{2}}} - \frac{15}{1+25x^{2}}\)

(5) \(\frac{6}{1+(3x+2)^{2}} - \frac{12}{\sqrt{1-(3-4x)^{2}}}\)

(6) \(\frac{1}{3}\cos\left(\frac{x}{3}-4\right) + \frac{7}{7x+9} + e^{\frac{x}{5}+3}\)

## 11.6 Simple applications

So far in this section we have been using \(x\) as the variable of integration. In the case of applications, it is often convenient to use a different variable. For instance in the equation of motion the independent variable is time and the variable of integration is \(t\).

In this section we discuss how integration is used to find the position and velocity of an object, given its acceleration and similar types of problems. Mathematically, this means that, starting with the derivative of a function, we must find the original function. Many common word which indicate derivative such as rate, growth, decay, marginal, change, varies, increase, decrease etc.

### Example 11.10

If \(f^{\prime}(x) = 3x^{2} - 4x + 5\) and \(f(1) = 3\), then find \(f(x)\).

**Solution**

Given that \(f^{\prime}(x) = \frac{d}{dx}\left(f(x)\right) = 3x^{2} - 4x + 5\)

Integrating on both sides with respect to \(x\), we get

\[
\int f^{\prime}(x) dx = \int (3x^{2} - 4x + 5) dx
\]
\[
f(x) = x^{3} - 2x^{2} + 5x + c
\]

To determine the constant of integration \(c\), we have to apply the given information \(f(1) = 3\)

\[
f(1) = 3 \Rightarrow 3 = (1)^{3} - 2(1)^{2} + 5(1) + c \Rightarrow c = -1
\]

Thus \(f(x) = x^{3} - 2x^{2} + 5x - 1\).

### Example 11.11

A train started from Madurai Junction towards Coimbatore at 3pm (time \(t = 0\)) with velocity \(v(t) = 20t + 50\) kilometre per hour, where \(t\) is measured in hours. Find the distance covered by the train at 5pm.

**Solution**

In calculus terminology, velocity \(v = \frac{ds}{dt}\) is rate of change of position with time, where \(s\) is the distance. The velocity of the train is given by \(v(t) = 20t + 50\)

\[
\frac{ds}{dt} = 20t + 50
\]

To find the distance function \(s\) one has to integrate the derivative function.

That is, \(s = \int (20t + 50) dt\)
\[
s = 10t^{2} + 50t + c
\]

The distance covered by the train is zero when time is zero. Let us use this initial condition \(s = 0\) at \(t = 0\) to determine the value \(c\) of the constant of integration.

\[
\Rightarrow s = 10t^{2} + 50t + c \Rightarrow c = 0
\]

Therefore, \(s = 10t^{2} + 50t\)

The distance covered by the train in 2 hours (5pm - 3pm) is given by substituting \(t = 2\) in the above equation, we get

\[
s = 10(2)^{2} + 50(2) = 140 \text{ km}.
\]

### Example 11.12

The rate of change of weight of person \(w\) in kg with respect to their height \(h\) in centimetres is given approximately by \(\frac{dw}{dh} = 4.364 \times 10^{-5} h^{2}\). Find weight as a function of height. Also find the weight of a person whose height is \(150 \text{ cm}\).

**Solution**

The rate of change of weight with respect to height is

\[
\frac{dw}{dh} = 4.364 \times 10^{-5} h^{2}
\]
\[
w = \int 4.364 \times 10^{-5} h^{2} dh
\]
\[
w = 4.364 \times 10^{-5} \left(\frac{h^{3}}{3}\right) + c
\]

One can obviously understand that the weight of a person is zero when height is zero.

Let us find the value \(c\) of the constant of integration by substituting the initial condition \(w = 0\) at \(h = 0\), in the above equation

\[
w = 4.364 \times 10^{-5}\left(\frac{h^{3}}{3}\right)
\]

When the height \(h = 150 \text{ cm}\)

\[
w = 4.364 \times 10^{-5}\left(\frac{150^{3}}{3}\right) \approx 49 \text{ kg}
\]

Therefore, the weight of the person whose height \(150 \text{ cm}\) is \(49 \text{ kg}\).

### Example 11.13

A tree is growing so that, after \(t\) years its height is increasing at a rate of \(\frac{18}{\sqrt{t}} \text{ cm}\) per year. Assume that when \(t = 0\), the height is \(5 \text{ cm}\).

(i) Find the height of the tree after 4 years. (ii) After how many years will the height be \(149 \text{ cm}\)?

**Solution**

The rate of change of height \(h\) with respect to time \(t\) is the derivative of \(h\) with respect to \(t\).

\[
\text{Therefore}, \frac{dh}{dt} = \frac{18}{\sqrt{t}} = 18t^{-\frac{1}{2}}
\]

So, to get a general expression for the height, integrating the above equation with respect to \(t\).

\[
h = \int 18t^{-\frac{1}{2}} dt = 18(2t^{\frac{1}{2}}) + c = 36\sqrt{t} + c
\]

Given that when \(t = 0\), the height \(h = 5 \text{ cm}\).

\[
5 = 0 + c \Rightarrow c = 5
\]
\[
h = 36\sqrt{t} + 5.
\]

(i) To find the height of the tree after 4 years.

When \(t = 4\) years,
\[
h = 36\sqrt{4} + 5 = 72 + 5 = 77
\]

The height of the tree after 4 years is \(77 \text{ cm}\)

(ii) When \(h = 149 \text{ cm}\)

\[
h = 36\sqrt{t} + 5 \Rightarrow 149 = 36\sqrt{t} + 5
\]
\[
\sqrt{t} = \frac{149 - 5}{36} = 4 \Rightarrow t = 16
\]

Thus after 16 years the height of the tree will be \(149 \text{ cm}\).

### Example 11.14

At a particular moment, a student needs to stop his speedy bike to avoid a collision with the barrier ahead at a distance 40 metres away from him. Immediately he slows (retardation) the bike under braking at a rate of 8 metre/second². If the bike is moving at a speed of \(24 \text{ m/s}\), when the brakes are applied, would it stop before collision?

**Solution**

Let \(a\) be the acceleration, \(v\) be the velocity of the car, and \(s\) be the distance.

Stated in calculus terminology, velocity, \(v = \frac{ds}{dt}\), is the rate of change of position with time, and acceleration, \(a = \frac{dv}{dt}\), is rate of change of velocity with time.

The acceleration is negative because if you take the direction of movement to be positive, then for a bike that is slowing down, its acceleration vector will be oriented in the opposite direction of its motion (retardation).

Given that the retardation of the car is 8 meter/second².

\[
a = \frac{dv}{dt} = -8 \text{ meter/second}^{2}.
\]

\[
v = \int a \, dt = \int -8 \, dt = -8t + c_{1}
\]
\[
v = -8t + c_{1}.
\]

When the brakes are applied,
\[
t = 0, \text{ and } v = 24 \text{ m/s}.
\]

So, \(24 = -8(0) + c_{1} \Rightarrow c_{1} = 24\)

Therefore, \(v = -8t + 24\)

\[
\frac{ds}{dt} = -8t + 24.
\]

It is required to find the distance, not the velocity, so need more integration in order.

\[
s = \int v \, dt = \int (-8t + 24) dt
\]
\[
s = -4t^{2} + 24t + c_{2}
\]

To determine \(c_{2}\), the stopping distance \(s\) is measured from where, and when, the brakes are applied so that at \(t = 0\), \(s = 0\).

\[
s = -4t^{2} + 24t + c_{2} \Rightarrow 0 = -4(0)^{2} + 24(0) + c_{2} \Rightarrow c_{2} = 0
\]
\[
s = -4t^{2} + 24t
\]

The stopping distance \(s\) could be evaluated if we knew the braking time. The time can be determined from the speed statement.

The bike stops when \(v = 0\), \(\Rightarrow v = -8t + 24 \Rightarrow 0 = -8t + 24 \Rightarrow t = 3\).

When \(t = 3\), we get

\[
s = -4t^{2} + 24t \Rightarrow s = -4(3)^{2} + 24(3)
\]
\[
s = 36 \text{ metres} < 40 \text{ metres}
\]

The bike stops at a distance 4 metres to the barrier.

## Exercise 11.4

(1) If \(f^{\prime}(x) = 4x - 5\) and \(f(2) = 1\), find \(f(x)\).

(2) If \(f^{\prime}(x) = 9x^{2} - 6x\) and \(f(0) = -3\), find \(f(x)\).

(3) If \(f^{\prime\prime}(x) = 12x - 6\) and \(f(1) = 30\), \(f^{\prime}(1) = 5\) find \(f(x)\).

(4) A ball is thrown vertically upward from the ground with an initial velocity of \(39.2 \text{ m/sec}\). If the only force considered is that attributed to the acceleration due to gravity, find (i) how long will it take for the ball to strike the ground? (ii) the speed with which will it strike the ground? and (iii) how high the ball will rise?

(5) A wound is healing in such a way that \(t\) days since Sunday the area of the wound has been decreasing at a rate of \(\frac{6}{(t + 2)^{2}} \text{ cm}^{2}\) per day where \(0 < t \leq 8\). If on Monday the area of the wound was \(1.4 \text{ cm}^{2}\) (i) What was the area of the wound on Sunday? (ii) What is the anticipated area of the wound on Thursday if it continues to heal at the same rate?

## 11.7 Methods of Integration

Integration is not as easy as differentiation. This is first due to its nature. Finding a derivative of a given function is facilitated by the fact that the differentiation itself has a constructive character. A derivative is simply defined as

\[
\lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}
\]

Suppose we are asked to find the derivative of \(\log x\), we know in all details how to proceed in order to obtain the result.

When we are asked to find the integral of \(\log x\), we have no constructive method to find integral or even how to start.

In the case of differentiation we use the laws of differentiation of several functions in order to find derivatives of their various combinations, like their sum, product, quotient, composition of functions etc.

There are very few such rules available in the theory of integration and their application is rather restricted. But the significance of these methods of integration is very great.

In every case one must learn to select the most appropriate method and use it in the most convenient form. This skill can only be acquired after long practice.

Already we have seen two important properties of integration. The following are the four important methods of integrations.

(1) Integration by decomposition into sum or difference.
(2) Integration by substitution.
(3) Integration by parts
(4) Integration by successive reduction.

Here we discuss only the first three methods of integration and the other will be studied in higher classes.

### 11.7.1 Decomposition method

Sometimes it is very difficult to integrate the given function directly. But it can be integrated after decomposing it into a sum or difference of number of functions whose integrals are already known.

For example \((1 - x^{3})^{2}\), \(\frac{x^{2} - x + 1}{x^{3}}\), \(\cos 5x \sin 3x\), \(\cos^{3}x\), \(\frac{e^{2x} - 1}{e^{x}}\) do not have direct formulae to integrate. But these functions can be decomposed into a sum or difference of functions, whose individual integrals are known. In most of the cases the given integrand will be any one of the algebraic, trigonometric or exponential forms, and sometimes combinations of these functions.

### Example 11.15

Integrate the following with respect to \(x\):

(i) \((1 - x^{3})^{2}\) (ii) \(\frac{x^{2} - x + 1}{x^{3}}\)

**Solution**

\[
\int (1 - x^{3})^{2} dx = \int (1 - 2x^{3} + x^{6}) dx
\]
\[
= \int dx - 2\int x^{3} dx + \int x^{6} dx
\]
\[
= x - \frac{x^{4}}{2} + \frac{x^{7}}{7} + c.
\]

\[
\int \frac{x^{2} - x + 1}{x^{3}} dx = \int \left(\frac{x^{2}}{x^{3}} - \frac{x}{x^{3}} + \frac{1}{x^{3}}\right) dx
\]
\[
= \int \frac{1}{x} dx - \int \frac{1}{x^{2}} dx + \int \frac{1}{x^{3}} dx
\]
\[
= \log|x| + \frac{1}{x} - \frac{1}{2x^{2}} + c.
\]

### Example 11.16

Integrate the following with respect to \(x\):

(i) \(\cos 5x \sin 3x\) (ii) \(\cos^{3}x\)

**Solution**

\[
\int \cos 5x \sin 3x \, dx = \frac{1}{2} \int 2\cos 5x \sin 3x \, dx
\]
\[
= \frac{1}{2} \int (\sin 8x - \sin 2x) dx
\]
\[
= \frac{1}{2} \left(-\frac{\cos 8x}{8} + \frac{\cos 2x}{2}\right) + c.
\]

\[
\int \cos^{3}x \, dx = \frac{1}{4} \int (3\cos x + \cos 3x) dx
\]
\[
= \frac{1}{4} \left(3\sin x + \frac{\sin 3x}{3}\right) + c
\]

### Example 11.17

Integrate the following with respect to \(x\):

(i) \(\frac{e^{2x} - 1}{e^{x}}\) (ii) \(e^{3x}(e^{2x} - 1)\)

**Solution**

(i)
\[
\int \frac{e^{2x} - 1}{e^{x}} dx = \int \left(\frac{e^{2x}}{e^{x}} - \frac{1}{e^{x}}\right) dx
\]
\[
= \int (e^{x} - e^{-x}) dx = e^{x} + e^{-x} + c.
\]

(ii)
\[
\int e^{3x}(e^{2x} - 1) dx = \int (e^{5x} - e^{3x}) dx = \frac{e^{5x}}{5} - \frac{e^{3x}}{3} + c.
\]

### Example 11.18

Evaluate: \(\int \frac{1}{\sin^{2}x \cos^{2}x} dx\).

**Solution**

\[
\int \frac{1}{\sin^{2}x \cos^{2}x} dx = \int \frac{\sin^{2}x + \cos^{2}x}{\sin^{2}x \cos^{2}x} dx
\]
\[
= \int \frac{1}{\cos^{2}x} dx + \int \frac{1}{\sin^{2}x} dx
\]
\[
= \int \sec^{2}x \, dx + \int \csc^{2}x \, dx
\]
\[
= \tan x - \cot x + c.
\]

### Example 11.19

Evaluate: \(\int \frac{\sin x}{1 + \sin x} dx\).

**Solution**

\[
\int \frac{\sin x}{1 + \sin x} dx = \int \left(\frac{\sin x}{1 + \sin x}\right)\left(\frac{1 - \sin x}{1 - \sin x}\right) dx
\]
\[
= \int \frac{\sin x - \sin^{2}x}{1 - \sin^{2}x} dx = \int \frac{\sin x - \sin^{2}x}{\cos^{2}x} dx = \int \frac{\sin x}{\cos^{2}x} dx - \int \frac{\sin^{2}x}{\cos^{2}x} dx
\]
\[
= \int \tan x \sec x \, dx - \int \tan^{2}x \, dx
\]
\[
= \int \tan x \sec x \, dx - \int (\sec^{2}x - 1) dx
\]
\[
= \sec x - \tan x + x + c.
\]

### Example 11.20

Evaluate: \(\int \sqrt{1 + \cos 2x} \, dx\).

**Solution**

\[
\int \sqrt{1 + \cos 2x} \, dx = \int \sqrt{2\cos^{2}x} \, dx = \sqrt{2} \int \cos x \, dx = \sqrt{2} \sin x + c
\]

### Example 11.21

Evaluate: \(\int \frac{(x - 1)^{2}}{x^{3} + x} dx\).

**Solution**

\[
\int \frac{(x - 1)^{2}}{x^{3} + x} dx = \int \frac{x^{2} + 1 - 2x}{x(x^{2} + 1)} dx
\]
\[
= \int \left(\frac{(x^{2} + 1)}{x(x^{2} + 1)} - \frac{2x}{x(x^{2} + 1)}\right) dx
\]
\[
= \int \frac{1}{x} dx - 2\int \frac{1}{1 + x^{2}} dx
\]
\[
= \log|x| - 2\tan^{-1}x + c.
\]

### Example 11.22

Evaluate: \(\int (\tan x + \cot x)^{2} dx\).

**Solution**

\[
\int (\tan x + \cot x)^{2} dx = \int [\tan^{2}x + 2\tan x \cot x + \cot^{2}x] dx
\]
\[
= \int [(\sec^{2}x - 1) + 2 + (\csc^{2}x - 1)] dx
\]
\[
= \int (\sec^{2}x + \csc^{2}x) dx
\]
\[
= \tan x + (-\cot x) + c = \tan x - \cot x + c.
\]

### Example 11.23

Evaluate: \(\int \frac{1 - \cos x}{1 + \cos x} dx\).

**Solution**

\[
\int \frac{1 - \cos x}{1 + \cos x} dx = \int \frac{2\sin^{2}\frac{x}{2}}{2\cos^{2}\frac{x}{2}} dx = \int \tan^{2}\frac{x}{2} dx
\]
\[
= \int (\sec^{2}\frac{x}{2} - 1) dx = \frac{\tan\frac{x}{2}}{\frac{1}{2}} - x + c
\]
\[
= 2\tan\frac{x}{2} - x + c.
\]

### Example 11.24

Evaluate: \(\int \sqrt{1 + \sin 2x} \, dx\).

**Solution**

\[
\int \sqrt{1 + \sin 2x} \, dx = \int \sqrt{\cos^{2}x + \sin^{2}x + 2\sin x \cos x} \, dx
\]

### Example 11.29

Evaluate: (i) \(\int \frac{3x + 7}{x^{2} - 3x + 2} dx\) (ii) \(\int \frac{x + 3}{(x + 2)^{2}(x + 1)} dx\)

**Solution**

(i)
\[
\int \frac{3x + 7}{x^{2} - 3x + 2} dx = \int \frac{13}{x - 2} dx - \int \frac{10}{x - 1} dx
\]
\[
= 13\log|x - 2| - 10\log|x - 1| + c
\]

(ii)
\[
\int \frac{x + 3}{(x + 2)^{2}(x + 1)} dx = \int \frac{-2}{x + 2} dx - \int \frac{1}{(x + 2)^{2}} dx + \int \frac{2}{x + 1} dx
\]
\[
= -2\int \frac{1}{x + 2} dx - \int (x + 2)^{-2} dx + 2\int \frac{1}{x + 1} dx
\]
\[
= -2\log|x + 2| + \frac{1}{x + 2} + 2\log|x + 1| + c.
\]

## Exercise 11.5

Integrate the following functions with respect to \(x\):

(1) \(\frac{x^{3}+4x^{2}-3x+2}{x^{2}}\)

(4) \(\cot^{2}x + \tan^{2}x\)

(7) \(\frac{3+4\cos x}{\sin^{2}x}\)

(10) \(\cos 3x \cos 2x\)

(13) \(e^{x\log a} e^{x}\)

(16) \(\frac{1}{\sqrt{x+3} - \sqrt{x-4}}\)

(19) \(\frac{3x-9}{(x-1)(x+2)(x^{2}+1)}\)

### 11.7.2 Decomposition by Partial Fractions

One of the important methods to evaluate integration is partial fractions. If the integrand is in the form of an algebraic fraction and the integral cannot be evaluated by simple methods, then the fraction need to be expressed in partial fractions before integration takes place. We will assume that we have a rational function \(\frac{p(x)}{q(x)}\), \((q(x) \neq 0)\) in which degree of \(p(x) < \text{degree of } q(x)\). If this is not the case, we can always perform long division.

### 11.7.3 Method of substitution or change of variable

The method of substitution in integration is similar to finding the derivative of function of function in differentiation. By using a suitable substitution, the variable of integration is changed to new variable of integration which will be integrated in an easy manner.

We know that, if \(u\) is a function of \(x\) then \(\frac{du}{dx} = u'\)

Hence we can write \(\int f(u) u' dx = \int f(u) du\)

Thus, \(\int f[g(x)] g'(x) dx = \int f(u) du\), where \(u = g(x)\)

The success of the above method depends on the selection of suitable substitution either \(x = \phi(u)\) or \(u = g(x)\).

**Note 11.2**

The substitution for the variable of integration is in trigonometric function, use a rough diagram to find the re-substitution value for it. Suppose the variable of integration \(x\) is substituted as \(x = \tan \theta\). After integration suppose the solution is \(\sec \theta + \cos \theta\).

For example, if \(x = \tan \theta\), then \(\sec \theta = \sqrt{1 + x^{2}}\).

### Example 11.30

Evaluate the following integrals:

(i) \(\int 2x\sqrt{1 + x^{2}} dx\) (ii) \(\int e^{-x^{2}} x \, dx\) (iii) \(\int \frac{\sin x}{1 + \cos x} dx\) (iv) \(\int \frac{1}{1 + x^{2}} dx\) (v) \(\int x(a - x)^{8} dx\)

**Solution**

(i) \(\int 2x\sqrt{1 + x^{2}} dx\)

Putting \(1 + x^{2} = u\), then \(2x dx = du\)

\[
\int 2x\sqrt{1 + x^{2}} dx = \int \sqrt{u} du = \int u^{\frac{1}{2}} du = \frac{u^{\frac{3}{2}}}{\frac{3}{2}} + c = \frac{2}{3} u^{\frac{3}{2}} + c = \frac{2}{3}(1 + x^{2})^{\frac{3}{2}} + c.
\]

(ii) \(\int e^{-x^{2}} x \, dx\)

Putting \(x^{2} = u\), then \(2x dx = du \Rightarrow x dx = \frac{du}{2}\)

\[
\int e^{-x^{2}} x \, dx = \int e^{-u} \frac{du}{2} = \frac{1}{2} \int e^{-u} du = -\frac{1}{2} e^{-u} + c = -\frac{1}{2} e^{-x^{2}} + c.
\]

(iii) \(\int \frac{\sin x}{1 + \cos x} dx\)

Putting \(1 + \cos x = u\), then \(-\sin x dx = du \Rightarrow \sin x dx = -du\)

\[
\int \frac{\sin x}{1 + \cos x} dx = \int \frac{-du}{u} = -\log|u| + c = -\log|1 + \cos x| + c.
\]

(iv) \(\int \frac{1}{1 + x^{2}} dx\)

Putting \(x = \tan u\), then \(dx = \sec^{2}u du\)

\[
\int \frac{1}{1 + x^{2}} dx = \int \frac{\sec^{2}u}{1 + \tan^{2}u} du = \int \frac{\sec^{2}u}{\sec^{2}u} du = \int du = u + c = \tan^{-1}x + c.
\]

(v) \(\int x(a - x)^{8} dx\)

Putting \(a - x = u\), then \(-dx = du \Rightarrow dx = -du\), \(x = a - u\)

\[
\int x(a - x)^{8} dx = \int (a - u)(u)^{8} (-du) = \int (-a u^{8} + u^{9}) du
\]
\[
= -a \int u^{8} du + \int u^{9} du = -a \frac{u^{9}}{9} + \frac{u^{10}}{10} + c
\]
\[
= \frac{(a - x)^{10}}{10} - \frac{a(a - x)^{9}}{9} + c.
\]

### 11.7.4 Important Results

\[
\int \frac{f^{\prime}(x)}{f(x)} dx = \log |f(x)| + c
\]
\[
\int f^{\prime}(x)[f(x)]^{n} dx = \frac{[f(x)]^{n+1}}{n+1} + c, \quad n \neq -1
\]

**Proof**

(1) Let \(I = \int \frac{f^{\prime}(x)}{f(x)} dx\)

Putting \(f(x) = u\) then \(f^{\prime}(x) dx = du\)

Thus, \(I = \int \frac{du}{u} = \log |u| + c\)

Therefore, \(\int \frac{f^{\prime}(x)}{f(x)} dx = \log |f(x)| + c\).

(2) Let \(I = \int f^{\prime}(x)[f(x)]^{n} dx\)

Putting \(f(x) = u\) then \(f^{\prime}(x) dx = du\)

Thus, \(I = \int u^{n} du = \frac{u^{n+1}}{n+1} + c\)

Therefore, \(\int f^{\prime}(x)[f(x)]^{n} dx = \frac{[f(x)]^{n+1}}{n+1} + c\).

### Example 11.31

Integrate the following with respect to \(x\)

(i) \(\int \tan x \, dx\) (ii) \(\int \cot x \, dx\)

**Solution**

(i) \(\int \tan x \, dx = \int \frac{\sin x}{\cos x} dx\)

Putting \(\cos x = u\) then \(-\sin x dx = du\)

Thus, \(I = \int -\frac{1}{u} du = -\log|u| + c = -\log|\cos x| + c = \log|\sec x| + c\).

(ii) \(\int \cot x \, dx = \int \frac{\cos x}{\sin x} dx\)

Putting \(\sin x = u\) then \(\cos x dx = du\)

Thus, \(I = \int \frac{1}{u} du = \log|u| + c = \log|\sin x| + c\).

### 11.7.5 Integration by parts

Integration by parts method is generally used to find the integral when the integrand is a product of two different types of functions or a single logarithmic function or a single inverse trigonometric function or a function which is not integrable directly. From the formula for derivative of product of two functions we obtain this useful method of integration.

If \(u\) and \(v\) are two differentiable functions then we have

\[
d(uv) = v du + u dv
\]
\[
u dv = d(uv) - v du
\]

Integrating

\[
\int u dv = \int d(uv) - \int v du
\]
\[
\int u dv = uv - \int v du
\]

\(\int u dv\) in terms of another integral \(\int v du\) and does not give a final expression for the integral \(\int u dv\). It only partially solves the problem of integrating the product \(u dv\). Hence the term 'Partial Integration' has been used in many European countries. The term "Integration by Parts" is used in many other countries as well as in our own.

The success of this method depends on the proper choice of \(u\)

(i) If integrand contains any non integrable functions directly from the formula, like \(\log x\), \(\tan^{-1}x\) etc., we have to take these non integrable functions as \(u\) and other as \(dv\)

(ii) If the integrand contains both the integrable function, and one of these is \(x^{n}\) (where \(n\) is a positive integer) then take \(u = x^{n}\)

(iii) For other cases the choice of \(u\) is ours.

### Example 11.33

Evaluate the following integrals

(i) \(\int xe^{x} dx\) (ii) \(\int x\cos x dx\) (iii) \(\int \log x dx\) (iv) \(\int \sin^{-1}x dx\)

**Solution**

(i) Let \(I = \int xe^{x} dx\)

Since \(x\) is an algebraic function and \(e^{x}\) is an exponential function, so take \(u = x\) then \(du = dx\)

\(dv = e^{x} dx \Rightarrow v = e^{x}\)

Applying Integration by parts, we get

\[
\int u dv = uv - \int v du
\]
\[
\Rightarrow \int xe^{x} dx = xe^{x} - \int e^{x} dx = xe^{x} - e^{x} + c.
\]

(ii) Let \(I = \int x\cos x dx\)

Since \(x\) is an algebraic function and \(\cos x\) is a trigonometric function.

### 11.7.6 Bernoulli's formula for Integration by Parts

If \(u\) and \(v\) are functions of \(x\), then the Bernoulli's rule is

\[
\int u \, dv = uv - u'v_{1} + u''v_{2} - \dots
\]

where \(u', u'', u''', \dots\) are successive derivatives of \(u\) and \(v, v_{1}, v_{2}, v_{3}, \dots\) are successive integrals of \(dv\)

Bernoulli's formula is advantageously applied when \(u = x^{n}\) (\(n\) is a positive integer)

For the following problems we have to apply the integration by parts two or more times to find the solution. In this case Bernoulli's formula helps to find the solution easily.

### Example 11.35

Integrate the following with respect to \(x\)

(i) \(x^{2} e^{5x}\) (ii) \(x^{3} \cos x\) (iii) \(x^{3} e^{-x}\)

**Solution**

(i) \(\int x^{2} e^{5x} dx\).

Applying Bernoulli's formula \(\int u dv = uv - u'v_{1} + u''v_{2} - \dots\)

\[
\int x^{2} e^{5x} dx = (x^{2})\left(\frac{e^{5x}}{5}\right) - (2x)\left(\frac{e^{5x}}{5^{2}}\right) + (2)\left(\frac{e^{5x}}{5^{3}}\right) + c
\]
\[
= \frac{x^{2} e^{5x}}{5} - \frac{2x e^{5x}}{25} + \frac{2e^{5x}}{125} + c.
\]

(ii) \(\int x^{3} \cos x dx\)

Applying Bernoulli's formula

\[
\int x^{3} \cos x dx = (x^{3})(\sin x) - (3x^{2})(-\cos x) + (6x)(-\sin x) - (6)(\cos x) + c
\]
\[
= x^{3} \sin x + 3x^{2} \cos x - 6x \sin x - 6 \cos x + c.
\]

(iii) \(\int x^{3} e^{-x} dx\)

Applying Bernoulli's formula

\[
\int x^{3} e^{-x} dx = (x^{3})(-e^{-x}) - (3x^{2})(e^{-x}) + (6x)(-e^{-x}) - (6)(e^{-x}) + c
\]
\[
= -x^{3} e^{-x} - 3x^{2} e^{-x} - 6x e^{-x} - 6 e^{-x} + c.
\]

## Exercise 11.7

Integrate the following with respect to \(x\):

(1) (i) \(xe^{3x}\) (ii) \(x \sin 3x\) (iii) \(xe^{-5x}\) (iv) \(x \sec x \tan x\)

(2) (i) \(x \log x\) (ii) \(2x^{2} e^{3x}\) (iii) \(x^{2} \cos x\) (iv) \(x^{3} \sin x\)

(3) (i) \(\frac{x \sin^{-1}x}{\sqrt{1-x^{2}}}\) (ii) \(x^{2} e^{5x}\) (iii) \(\frac{\tan^{-1}\left(\frac{x}{2}\right)}{1+16x^{2}}\) (iv) \(\frac{\sin^{-1}\left(\frac{2x}{1+x^{2}}\right)}{1+x^{2}}\)

### 11.7.8 Integrals of the form (i) \(\int e^{ax} \sin bx \, dx\) (ii) \(\int e^{ax} \cos bx \, dx\)

The following examples illustrate that there are some integrals whose integration continues forever. Whenever we integrate function of the form \(e^{ax} \cos bx\) or \(e^{ax} \sin bx\), we have to apply the Integration by Parts rule twice to get the similar integral on both sides to solve.

**Result 11.1**

(i) \(\int e^{ax} \sin bx \, dx = \frac{e^{ax}}{a^{2} + b^{2}} [a \sin bx - b \cos bx] + c\)

(ii) \(\int e^{ax} \cos bx \, dx = \frac{e^{ax}}{a^{2} + b^{2}} [a \cos bx + b \sin bx] + c\)

## Exercise 11.8

Integrate the following with respect to \(x\)

(1) (i) \(e^{ax} \cos bx\) (ii) \(e^{2x} \sin x\) (iii) \(e^{-x} \cos 2x\)

(2) (i) \(e^{-3x} \sin 2x\) (ii) \(e^{-4x} \sin 2x\) (iii) \(e^{-3x} \cos x\)

**Result 11.2**

\[
\int e^{x}[f(x) + f^{\prime}(x)] dx = e^{x} f(x) + c
\]

**Proof**

Let \(I = \int e^{x}[f(x) + f^{\prime}(x)] dx = \int e^{x} f(x) dx + \int e^{x} f^{\prime}(x) dx\)

Take \(u = f(x)\); \(du = f^{\prime}(x) dx\), in the first integral \(dv = e^{x}\); \(v = e^{x}\),

That is, \(I = e^{x} f(x) - \int e^{x} f^{\prime}(x) dx + \int e^{x} f^{\prime}(x) dx + c = e^{x} f(x) + c\).

### Example 11.37

Evaluate the following integrals

(i) \(\int e^{x}\left(\frac{1}{x} - \frac{1}{x^{2}}\right) dx\) (ii) \(\int e^{x}(\sin x + \cos x) dx\) (iii) \(\int e^{x}\left(\frac{1 - x}{1 + x^{2}}\right)^{2} dx\)

**Solution**

(i) Take \(f(x) = \frac{1}{x}\), then \(f^{\prime}(x) = -\frac{1}{x^{2}}\)

Therefore, \(\int e^{x}\left(\frac{1}{x} - \frac{1}{x^{2}}\right) dx = e^{x} \cdot \frac{1}{x} + c\).

(ii) Take \(f(x) = \sin x\), then \(f^{\prime}(x) = \cos x\)

Therefore, \(\int e^{x}(\sin x + \cos x) dx = e^{x} \sin x + c\).

(iii) \(\int e^{x}\left(\frac{1 - x}{1 + x^{2}}\right)^{2} dx = \int e^{x} \frac{(1 - x)^{2}}{(1 + x^{2})^{2}} dx\)

\[
= \int e^{x} \frac{(1 + x^{2} - 2x)}{(1 + x^{2})^{2}} dx = \int e^{x} \left(\frac{1}{1 + x^{2}} - \frac{2x}{(1 + x^{2})^{2}}\right) dx
\]

If \(f(x) = \frac{1}{1 + x^{2}}\), then \(f^{\prime}(x) = -\frac{2x}{(1 + x^{2})^{2}}\)

Therefore, \(\int e^{x}\left(\frac{1 - x}{1 + x^{2}}\right)^{2} dx = e^{x} \cdot \frac{1}{1 + x^{2}} + c\).

## Exercise 11.9

Integrate the following with respect to \(x\):

(1) \(e^{x}(\tan x + \log \sec x)\)

(2) \(e^{x}\left(\frac{x - 1}{2x^{2}}\right)\)

(3) \(e^{x} \sec x(1 + \tan x)\)

(4) \(e^{x}\left(\frac{2 + \sin 2x}{1 + \cos 2x}\right)\)

(5) \(e^{\tan^{-1}x}\left(\frac{1 + x + x^{2}}{1 + x^{2}}\right)\)

(6) \(\frac{\log x}{(1 + \log x)^{2}}\)

### 11.7.9 Integration of Rational Algebraic Functions

In this section we are going to discuss how to integrate the rational algebraic functions whose numerator and denominator contains some positive integral powers of \(x\) with constant coefficients.

## Type I

\[
\int \frac{dx}{a^{2} \pm x^{2}}, \quad \int \frac{dx}{x^{2} - a^{2}}, \quad \int \frac{dx}{\sqrt{a^{2} \pm x^{2}}}, \quad \int \frac{dx}{\sqrt{x^{2} - a^{2}}}
\]

\[
\int \frac{dx}{a^{2} - x^{2}} = \frac{1}{2a} \log \left|\frac{a + x}{a - x}\right| + c
\]

\[
\int \frac{dx}{x^{2} - a^{2}} = \frac{1}{2a} \log \left|\frac{x - a}{x + a}\right| + c
\]

\[
\int \frac{dx}{a^{2} + x^{2}} = \frac{1}{a} \tan^{-1}\left(\frac{x}{a}\right) + c
\]

\[
\int \frac{dx}{\sqrt{a^{2} - x^{2}}} = \sin^{-1}\left(\frac{x}{a}\right) + c
\]

\[
\int \frac{dx}{\sqrt{x^{2} - a^{2}}} = \log \left|x + \sqrt{x^{2} - a^{2}}\right| + c
\]

\[
\int \frac{dx}{\sqrt{x^{2} + a^{2}}} = \log \left|x + \sqrt{x^{2} + a^{2}}\right| + c
\]

**Proof**

(i) Let \(I = \int \frac{dx}{a^{2} - x^{2}}\).

\[
I = \int \frac{dx}{(a-x)(a+x)} = \frac{1}{2a} \int \left[\frac{1}{a+x} + \frac{1}{a-x}\right] dx
\]
\[
= \frac{1}{2a} [\log|a+x| - \log|a-x|] + c = \frac{1}{2a} \log \left|\frac{a+x}{a-x}\right| + c
\]

(ii) Let \(I = \int \frac{dx}{x^{2} - a^{2}}\).

\[
I = \int \frac{dx}{(x-a)(x+a)} = \frac{1}{2a} \int \left[\frac{1}{x-a} - \frac{1}{x+a}\right] dx
\]
\[
= \frac{1}{2a} [\log|x-a| - \log|x+a|] + c = \frac{1}{2a} \log \left|\frac{x-a}{x+a}\right| + c
\]

(iii) Let \(I = \int \frac{dx}{a^{2} + x^{2}}\).

Putting \(x = a \tan \theta \Rightarrow \theta = \tan^{-1}\frac{x}{a}\), \(dx = a \sec^{2}\theta \, d\theta\)

\[
I = \int \frac{a \sec^{2}\theta}{a^{2} + a^{2}\tan^{2}\theta} d\theta = \int \frac{a \sec^{2}\theta}{a^{2}(1 + \tan^{2}\theta)} d\theta = \int \frac{a \sec^{2}\theta}{a^{2} \sec^{2}\theta} d\theta = \frac{1}{a} \int d\theta
\]
\[
= \frac{1}{a} \theta + c = \frac{1}{a} \tan^{-1}\left(\frac{x}{a}\right) + c
\]

(iv) Let \(I = \int \frac{dx}{\sqrt{a^{2} - x^{2}}}\).

Putting \(x = a \sin \theta \Rightarrow \theta = \sin^{-1}\left(\frac{x}{a}\right)\), \(dx = a \cos \theta \, d\theta\)

\[
I = \int \frac{a \cos \theta}{\sqrt{a^{2} - a^{2}\sin^{2}\theta}} d\theta = \int \frac{a \cos \theta}{\sqrt{a^{2}(1 - \sin^{2}\theta)}} d\theta = \int \frac{a \cos \theta}{a \cos \theta} d\theta = \int d\theta = \theta + c = \sin^{-1}\left(\frac{x}{a}\right) + c
\]

(v) Let \(I = \int \frac{dx}{\sqrt{x^{2} - a^{2}}}\).

Putting \(x = a \sec \theta \Rightarrow \theta = \sec^{-1}\left(\frac{x}{a}\right)\), \(dx = a \sec \theta \tan \theta \, d\theta\)

\[
I = \int \frac{a \sec \theta \tan \theta}{\sqrt{a^{2}\sec^{2}\theta - a^{2}}} d\theta = \int \frac{a \sec \theta \tan \theta}{\sqrt{a^{2}(\sec^{2}\theta - 1)}} d\theta = \int \frac{a \sec \theta \tan \theta}{a \tan \theta} d\theta = \int \sec \theta \, d\theta
\]
\[
= \log |\sec \theta + \tan \theta| + c = \log \left|\frac{x}{a} + \frac{\sqrt{x^{2} - a^{2}}}{a}\right| + c = \log \left|x + \sqrt{x^{2} - a^{2}}\right| - \log a + c
\]
\[
= \log \left|x + \sqrt{x^{2} - a^{2}}\right| + c_{1} \quad \text{where } c_{1} = c - \log a
\]

(vi) Let \(I = \int \frac{dx}{\sqrt{a^{2} + x^{2}}}\).

Putting \(x = a \tan \theta \Rightarrow \theta = \tan^{-1}\left(\frac{x}{a}\right)\), \(dx = a \sec^{2}\theta \, d\theta\)

\[
I = \int \frac{a \sec^{2}\theta}{\sqrt{a^{2}\tan^{2}\theta + a^{2}}} d\theta = \int \frac{a \sec^{2}\theta}{\sqrt{a^{2}(\tan^{2}\theta + 1)}} d\theta = \int \frac{a \sec^{2}\theta}{a \sec \theta} d\theta = \int \sec \theta \, d\theta
\]
\[
= \log |\sec \theta + \tan \theta| + c = \log \left|\frac{x}{a} + \sqrt{\frac{x^{2}}{a^{2}} + 1}\right| + c
\]
\[
= \log \left|x + \sqrt{x^{2} + a^{2}}\right| - \log a + c = \log \left|x + \sqrt{x^{2} + a^{2}}\right| + c_{1}
\]

**Remark:** Remember the following useful substitution of the given integral as a functions of \(a^{2} - x^{2}\), \(a^{2} + x^{2}\) and \(x^{2} - a^{2}\).

| Given | Substitution |
|-------|--------------|
| \(a^{2} - x^{2}\) | \(x = a \sin \theta\) |
| \(a^{2} + x^{2}\) | \(x = a \tan \theta\) |
| \(x^{2} - a^{2}\) | \(x = a \sec \theta\) |

### Example 11.38

Evaluate the following integrals

(i) \(\int \frac{1}{(x - 2)^{2} + 1} dx\) (ii) \(\int \frac{x^{2}}{x^{2} + 5} dx\) (iii) \(\int \frac{1}{\sqrt{1 + 4x^{2}}} dx\) (iv) \(\int \frac{1}{\sqrt{4x^{2} - 25}} dx\)

**Solution**

(i) Let \(I = \int \frac{1}{(x - 2)^{2} + 1} dx = \int \frac{1}{(x - 2)^{2} + 1^{2}} dx\)

Putting \(x - 2 = t \Rightarrow dx = dt\)

Thus, \(I = \int \frac{1}{t^{2} + 1^{2}} dt = \tan^{-1}(t) + c = \tan^{-1}(x - 2) + c\)

(ii) Let \(I = \int \frac{x^{2}}{x^{2} + 5} dx = \int \frac{x^{2} + 5 - 5}{x^{2} + 5} dx = \int \left(1 - \frac{5}{x^{2} + 5}\right) dx = \int dx - \int \frac{5}{x^{2} + 5} dx\)
\[
= x - 5 \int \frac{1}{x^{2} + (\sqrt{5})^{2}} dx = x - 5 \cdot \frac{1}{\sqrt{5}} \tan^{-1}\left(\frac{x}{\sqrt{5}}\right) + c
\]

(iii) Let \(I = \int \frac{1}{\sqrt{1 + 4x^{2}}} dx = \int \frac{1}{\sqrt{1 + (2x)^{2}}} dx\)

Putting \(2x = t \Rightarrow 2dx = dt \Rightarrow dx = \frac{1}{2} dt\)

Thus, \(I = \frac{1}{2} \int \frac{1}{\sqrt{1^{2} + t^{2}}} dt = \frac{1}{2} \log \left|t + \sqrt{t^{2} + 1}\right| + c = \frac{1}{2} \log \left|2x + \sqrt{4x^{2} + 1}\right| + c\)

(iv) Let \(I = \int \frac{1}{\sqrt{4x^{2} - 25}} dx = \int \frac{1}{\sqrt{(2x)^{2} - 25}} dx\)

Putting \(2x = t \Rightarrow 2dx = dt \Rightarrow dx = \frac{1}{2} dt\)

\[
I = \frac{1}{2} \int \frac{1}{\sqrt{t^{2} - 5^{2}}} dt = \frac{1}{2} \log \left|t + \sqrt{t^{2} - 25}\right| + c = \frac{1}{2} \log \left|2x + \sqrt{4x^{2} - 25}\right| + c
\]

## Type II

Integrals of the form \(\int \frac{dx}{ax^{2} + bx + c}\) and \(\int \frac{dx}{\sqrt{ax^{2} + bx + c}}\)

First we express \(ax^{2} + bx + c\) as sum or difference of two square terms that is, any one of the forms to Type I. The following rule is used to express the expression \(ax^{2} + bx + c\) as a sum or difference of two square terms.

(1) Make the coefficient of \(x^{2}\) as unity.

(2) Completing the square by adding and subtracting the square of half of the coefficient of \(x\).

That is,
\[
ax^{2} + bx + c = a \left[x^{2} + \frac{b}{a}x + \frac{c}{a}\right] = a \left[\left(x + \frac{b}{2a}\right)^{2} + \frac{4ac - b^{2}}{4a^{2}}\right]
\]

### Example 11.39

Evaluate the following integrals

(i) \(\int \frac{1}{x^{2} - 2x + 5} dx\) (ii) \(\int \frac{1}{x^{2} + 12x + 11} dx\) (iii) \(\int \frac{1}{\sqrt{12 + 4x - x^{2}}} dx\)

**Solution**

(i) \(\int \frac{1}{x^{2} - 2x + 5} dx = \int \frac{1}{(x-1)^{2} + 2^{2}} dx = \frac{1}{2} \tan^{-1}\left(\frac{x-1}{2}\right) + c\)

(ii) \(\int \frac{1}{x^{2} + 12x + 11} dx = \int \frac{1}{(x+6)^{2} - 5^{2}} dx = \frac{1}{2 \cdot 5} \log \left|\frac{x+6-5}{x+6+5}\right| + c = \frac{1}{10} \log \left|\frac{x+1}{x+11}\right| + c\)

(iii) \(\int \frac{1}{\sqrt{12 + 4x - x^{2}}} dx = \int \frac{1}{\sqrt{12 - (x^{2} - 4x)}} dx = \int \frac{1}{\sqrt{12 - \{(x-2)^{2} - 4\}}} dx\)
\[
= \int \frac{1}{\sqrt{4^{2} - (x-2)^{2}}} dx = \sin^{-1}\left(\frac{x-2}{4}\right) + c
\]

## Exercise 11.10

Find the integrals of the following:

(1) (i) \(\frac{1}{4 - x^{2}}\) (ii) \(\frac{1}{25 - 4x^{2}}\) (iii) \(\frac{1}{9x^{2} - 4}\)

(2) (i) \(\frac{1}{6x - 7 - x^{2}}\) (ii) \(\frac{1}{(x+1)^{2} - 25}\) (iii) \(\frac{1}{\sqrt{x^{2} + 4x + 2}}\)

(3) (i) \(\frac{1}{\sqrt{(2+x)^{2} - 1}}\) (ii) \(\frac{1}{\sqrt{x^{2} - 4x + 5}}\) (iii) \(\frac{1}{\sqrt{9 + 8x - x^{2}}}\)

## Type III

Integrals of the form \(\int \frac{px + q}{ax^{2} + bx + c} dx\) and \(\int \frac{px + q}{\sqrt{ax^{2} + bx + c}} dx\)

To evaluate the above integrals, first we write

\[
px + q = A \frac{d}{dx}(ax^{2} + bx + c) + B = A(2ax + b) + B
\]

Calculate the values of \(A\) and \(B\), by equating the coefficients of like powers of \(x\) on both sides

(i) The given first integral can be written as

\[
\int \frac{px + q}{ax^{2} + bx + c} dx = \int \frac{A(2ax + b) + B}{ax^{2} + bx + c} dx
\]
\[
= A \int \frac{2ax + b}{ax^{2} + bx + c} dx + B \int \frac{1}{ax^{2} + bx + c} dx
\]

The first integral is of the form \(\int \frac{f'(x)}{f(x)} dx\)

\[
= A \log |ax^{2} + bx + c| + B \int \frac{1}{ax^{2} + bx + c} dx
\]

The second term on the right hand side can be evaluated using the previous types.

(ii) The given second integral can be written as

\[
\int \frac{px + q}{\sqrt{ax^{2} + bx + c}} dx = \int \frac{A(2ax + b) + B}{\sqrt{ax^{2} + bx + c}} dx
\]
\[
= A \int \frac{2ax + b}{\sqrt{ax^{2} + bx + c}} dx + B \int \frac{1}{\sqrt{ax^{2} + bx + c}} dx
\]

The first integral is of the form \(\int f'(x)[f(x)]^{n} dx\)

\[
= A \left(2\sqrt{ax^{2} + bx + c}\right) + B \int \frac{1}{\sqrt{ax^{2} + bx + c}} dx
\]

The second term on the right hand side can be evaluated using the previous types.

### Example 11.40

Evaluate the following integrals

(i) \(\int \frac{3x + 5}{x^{2} + 4x + 7} dx\) (ii) \(\int \frac{x + 1}{x^{2} - 3x + 1} dx\) (iii) \(\int \frac{2x + 3}{\sqrt{x^{2} + x + 1}} dx\) (iv) \(\int \frac{5x - 7}{\sqrt{3x - x^{2} + 2}} dx\)

**Solution**

(i) Let \(I = \int \frac{3x + 5}{x^{2} + 4x + 7} dx\)

Write \(3x + 5 = A \frac{d}{dx}(x^{2} + 4x + 7) + B = A(2x + 4) + B\)

Comparing the coefficients of like terms, we get \(2A = 3 \Rightarrow A = \frac{3}{2}\), \(4A + B = 5 \Rightarrow 4\left(\frac{3}{2}\right) + B = 5 \Rightarrow 6 + B = 5 \Rightarrow B = -1\)

\[
I = \int \frac{\frac{3}{2}(2x + 4) - 1}{x^{2} + 4x + 7} dx = \frac{3}{2} \int \frac{2x + 4}{x^{2} + 4x + 7} dx - \int \frac{1}{x^{2} + 4x + 7} dx
\]
\[
= \frac{3}{2} \log |x^{2} + 4x + 7| - \int \frac{1}{(x+2)^{2} + (\sqrt{3})^{2}} dx
\]
\[
= \frac{3}{2} \log |x^{2} + 4x + 7| - \frac{1}{\sqrt{3}} \tan^{-1}\left(\frac{x+2}{\sqrt{3}}\right) + c
\]

## Exercise 11.11

Integrate the following with respect to \(x\):

(1) (i) \(\frac{3x+4}{x^{2}+12x+2}\) (ii) \(\frac{5x+2}{2x^{2}+2x+2}\) (iii) \(\frac{3x+1}{2x^{2}+3x+2}\)

(2) (i) \(\frac{2x+1}{\sqrt{9+4x-x^{2}}}\) (ii) \(\frac{x+2}{\sqrt{x^{2}+1}}\) (iii) \(\frac{2x+3}{\sqrt{x^{2}+4x+1}}\)

## Type IV

Integrals of the form \(\int \sqrt{a^{2} + x^{2}} dx\), \(\int \sqrt{x^{2} - a^{2}} dx\)

**Result 11.3**

(1) \(\int \sqrt{a^{2} - x^{2}} dx = \frac{x}{2} \sqrt{a^{2} - x^{2}} + \frac{a^{2}}{2} \sin^{-1}\left(\frac{x}{a}\right) + c\)

(2) \(\int \sqrt{x^{2} - a^{2}} dx = \frac{x}{2} \sqrt{x^{2} - a^{2}} - \frac{a^{2}}{2} \log \left|x + \sqrt{x^{2} - a^{2}}\right| + c\)

(3) \(\int \sqrt{x^{2} + a^{2}} dx = \frac{x}{2} \sqrt{x^{2} + a^{2}} + \frac{a^{2}}{2} \log \left|x + \sqrt{x^{2} + a^{2}}\right| + c\)

### Example 11.41

Evaluate the following:

(i) \(\int \sqrt{4 - x^{2}} dx\) (ii) \(\int \sqrt{25x^{2} - 9} dx\) (iii) \(\int \sqrt{x^{2} + x + 1} dx\) (iv) \(\int \sqrt{(x-3)(5-x)} dx\)

**Solution**

(i) Let \(I = \int \sqrt{4 - x^{2}} dx = \int \sqrt{2^{2} - x^{2}} dx\)
\[
= \frac{x}{2} \sqrt{2^{2} - x^{2}} + \frac{2^{2}}{2} \sin^{-1}\left(\frac{x}{2}\right) + c = \frac{x}{2} \sqrt{4 - x^{2}} + 2 \sin^{-1}\left(\frac{x}{2}\right) + c
\]

(ii) Let \(I = \int \sqrt{25x^{2} - 9} dx = \int \sqrt{(5x)^{2} - 3^{2}} dx\)

Putting \(5x = t \Rightarrow 5dx = dt \Rightarrow dx = \frac{1}{5} dt\)

\[
I = \frac{1}{5} \int \sqrt{t^{2} - 3^{2}} dt = \frac{1}{5} \left[ \frac{t}{2} \sqrt{t^{2} - 9} - \frac{9}{2} \log |t + \sqrt{t^{2} - 9}| \right] + c
\]
\[
= \frac{1}{5} \left[ \frac{5x}{2} \sqrt{25x^{2} - 9} - \frac{9}{2} \log |5x + \sqrt{25x^{2} - 9}| \right] + c
\]

(iii) Let \(I = \int \sqrt{x^{2} + x + 1} dx = \int \sqrt{\left(x + \frac{1}{2}\right)^{2} + \left(\frac{\sqrt{3}}{2}\right)^{2}} dx\)
\[
= \frac{x + \frac{1}{2}}{2} \sqrt{\left(x + \frac{1}{2}\right)^{2} + \left(\frac{\sqrt{3}}{2}\right)^{2}} + \frac{\left(\frac{\sqrt{3}}{2}\right)^{2}}{2} \log \left| x + \frac{1}{2} + \sqrt{\left(x + \frac{1}{2}\right)^{2} + \left(\frac{\sqrt{3}}{2}\right)^{2}} \right| + c
\]
\[
= \frac{2x + 1}{4} \sqrt{x^{2} + x + 1} + \frac{3}{8} \log \left| x + \frac{1}{2} + \sqrt{x^{2} + x + 1} \right| + c
\]

(iv) Let \(I = \int \sqrt{(x-3)(5-x)} dx = \int \sqrt{8x - x^{2} - 15} dx = \int \sqrt{1^{2} - (x-4)^{2}} dx\)
\[
= \frac{x-4}{2} \sqrt{1^{2} - (x-4)^{2}} + \frac{1}{2} \sin^{-1}(x-4) + c = \frac{x-4}{2} \sqrt{8x - x^{2} - 15} + \frac{1}{2} \sin^{-1}(x-4) + c
\]

## Exercise 11.12

Integrate the following functions with respect to \(x\):

(1) (i) \(\sqrt{x^{2} + 2x + 10}\) (ii) \(\sqrt{x^{2} - 2x - 3}\) (iii) \(\sqrt{(6-x)(x-4)}\)

(2) (i) \(\sqrt{9 - (2x+5)^{2}}\) (ii) \(\sqrt{81 + (2x+1)^{2}}\) (iii) \(\sqrt{(x+1)^{2} - 4}\)

## Exercise 11.13

Choose the correct or the most suitable answer from given four alternatives.

(1) If \(\int f(x) dx = g(x) + c\), then \(\int f(x) g'(x) dx\)

(1) \(\int (f(x))^{2} dx\) (2) \(\int f(x) g(x) dx\) (3) \(\int f'(x) g(x) dx\) (4) \(\int (g(x))^{2} dx\)

(2) If \(\int \frac{3^{x}}{x^{2}} dx = k(3^{x}) + c\), then the value of \(k\) is

(1) \(\log 3\) (2) \(-\log 3\) (3) \(-\frac{1}{\log 3}\) (4) \(\frac{1}{\log 3}\)

(3) If \(\int f'(x) e^{x^{2}} dx = (x-1)e^{x^{2}} + c\), then \(f(x)\) is

(1) \(2x^{3} - \frac{x^{2}}{2} + x + c\) (2) \(\frac{x^{3}}{2} + 3x^{2} + 4x + c\) (3) \(x^{3} + 4x^{2} + 6x + c\) (4) \(\frac{2x^{3}}{3} - x^{2} + x + c\)

(4) The gradient (slope) of a curve at any point \((x,y)\) is \(\frac{x^{2} - 4}{x^{2}}\). If the curve passes through the point (2,7), then the equation of the curve is

(1) \(y = x + \frac{4}{x} + 3\) (2) \(y = x + \frac{4}{x} + 4\) (3) \(y = x^{2} + 3x + 4\) (4) \(y = x^{2} - 3x + 6\)

(5) \(\int \frac{e^{x}(1+x)}{\cos^{2}(xe^{x})} dx\) is

(1) \(\cot(xe^{x}) + c\) (2) \(\sec(xe^{x}) + c\) (3) \(\tan(xe^{x}) + c\) (4) \(\cos(xe^{x}) + c\)

(6) \(\int \frac{\sqrt{\tan x}}{\sin 2x} dx\) is

(1) \(\sqrt{\tan x} + c\) (2) \(2\sqrt{\tan x} + c\) (3) \(\frac{1}{2}\sqrt{\tan x} + c\) (4) \(\frac{1}{4}\sqrt{\tan x} + c\)

(7) \(\int \sin^{3}x dx\) is

(1) \(-\frac{3}{4}\cos x - \frac{\cos 3x}{12} + c\) (2) \(\frac{3}{4}\cos x + \frac{\cos 3x}{12} + c\)

(3) \(-\frac{3}{4}\cos x + \frac{\cos 3x}{12} + c\) (4) \(-\frac{3}{4}\sin x - \frac{\sin 3x}{12} + c\)

(8) \(\int \frac{e^{6\log x} - e^{5\log x}}{e^{4\log x} - e^{3\log x}} dx\) is

(1) \(x + c\) (2) \(\frac{x^{3}}{3} + c\) (3) \(\frac{3}{x^{3}} + c\) (4) \(\frac{1}{x^{2}} + c\)

(9) \(\int \frac{\sec x}{\sqrt{\cos 2x}} dx\) is

(1) \(\tan^{-1}(\sin x) + c\) (2) \(2\sin^{-1}(\tan x) + c\) (3) \(\tan^{-1}(\cos x) + c\) (4) \(\sin^{-1}(\tan x) + c\)

(10) \(\int \tan^{-1}\sqrt{\frac{1 - \cos 2x}{1 + \cos 2x}} dx\) is

(1) \(x^{2} + c\) (2) \(2x^{2} + c\) (3) \(\frac{x^{2}}{2} + c\) (4) \(-\frac{x^{2}}{2} + c\)

(11) \(\int 2^{3x+5} dx\) is

(1) \(\frac{3(2^{3x+5})}{\log 2} + c\) (2) \(\frac{2^{3x+5}}{2\log(3x+5)} + c\) (3) \(\frac{2^{3x+5}}{2\log 3} + c\) (4) \(\frac{2^{3x+5}}{3\log 2} + c\)

(12) \(\int \frac{\sin^{8}x - \cos^{8}x}{1 - 2\sin^{2}x\cos^{2}x} dx\) is

(1) \(\frac{1}{2}\sin 2x + c\) (2) \(-\frac{1}{2}\sin 2x + c\) (3) \(\frac{1}{2}\cos 2x + c\) (4) \(-\frac{1}{2}\cos 2x + c\)

(13) \(\int \frac{e^{x}(x^{2}\tan^{-1}x + \tan^{-1}x + 1)}{x^{2} + 1} dx\) is

(1) \(e^{x}\tan^{-1}(x+1) + c\) (2) \(\tan^{-1}(e^{x}) + c\) (3) \(e^{x}\frac{(\tan^{-1}x)^{2}}{2} + c\) (4) \(e^{x}\tan^{-1}x + c\)

(14) \(\int \frac{x^{2} + \cos^{2}x}{x^{2} + 1} \csc^{2}x dx\) is

(1) \(\cot x + \sin^{-1}x + c\) (2) \(-\cot x + \tan^{-1}x + c\) (3) \(-\tan x + \cot^{-1}x + c\) (4) \(-\cot x - \tan^{-1}x + c\)

(15) \(\int x^{2}\cos x dx\) is

(1) \(x^{2}\sin x + 2x\cos x - 2\sin x + c\) (2) \(x^{2}\sin x - 2x\cos x - 2\sin x + c\)

(3) \(-x^{2}\sin x + 2x\cos x + 2\sin x + c\) (4) \(-x^{2}\sin x - 2x\cos x + 2\sin x + c\)

(16) \(\int \sqrt{\frac{1-x}{1+x}} dx\) is

(1) \(\sqrt{1-x^{2}} + \sin^{-1}x + c\) (2) \(\sin^{-1}x - \sqrt{1-x^{2}} + c\)

(3) \(\log|x + \sqrt{1-x^{2}}| - \sqrt{1-x^{2}} + c\) (4) \(\sqrt{1-x^{2}} + \log|x + \sqrt{1-x^{2}}| + c\)

(17) \(\int \frac{dx}{e^{x} - 1}\) is

(1) \(\log|e^{x}| - \log|e^{x} - 1| + c\) (2) \(\log|e^{x}| + \log|e^{x} - 1| + c\)

(3) \(\log|e^{x} - 1| - \log|e^{x}| + c\) (4) \(\log|e^{x} + 1| - \log|e^{x}| + c\)

(18) \(\int e^{-4x} \cos x dx\) is

(1) \(\frac{e^{-4x}}{17}[4\cos x - \sin x] + c\) (2) \(\frac{e^{-4x}}{17}[-4\cos x + \sin x] + c\)

(3) \(\frac{e^{-4x}}{17}[4\cos x + \sin x] + c\) (4) \(\frac{e^{-4x}}{17}[-4\cos x - \sin x] + c\)

(19) \(\int \frac{\sec^{2}\frac{x}{2}}{\tan\frac{x}{2}} dx\) is

(1) \(2\log\left|\tan\frac{x}{2}\right| + c\) (2) \(\log\left|\tan\frac{x}{2}\right| + c\)

(3) \(\frac{1}{2}\log\left|\tan\frac{x}{2}\right| + c\) (4) \(2\log\left|\tan\frac{x}{2}\right| + c\)

(20) \(\int e^{7x} \sin 5x dx\) is

(1) \(\frac{e^{7x}}{74}[7\sin 5x - 5\cos 5x] + c\) (2) \(\frac{e^{7x}}{74}[7\sin 5x + 5\cos 5x] + c\)

(3) \(\frac{e^{7x}}{74}[-7\sin 5x + 5\cos 5x] + c\) (4) \(\frac{e^{7x}}{74}[-7\sin 5x - 5\cos 5x] + c\)

(21) \(\int x^{2} 2^{x} dx\) is

(1) \(\frac{x^{2}2^{x}}{\log 2} - \frac{2x2^{x}}{(\log 2)^{2}} + \frac{2^{x+1}}{(\log 2)^{3}} + c\) (2) \(\frac{x^{2}2^{x}}{\log 2} - \frac{2x2^{x}}{(\log 2)^{2}} + \frac{2^{x+1}}{(\log 2)^{3}} + c\)

(22) \(\int \frac{x^{2} + 2}{x^{2} - 1} dx\) is

(1) \(x + \frac{1}{2}\log\left|\frac{x-1}{x+1}\right| + c\) (2) \(\sin^{-1}x + \frac{1}{2}\log\left|\frac{x-1}{x+1}\right| + c\)

(23) \(\int \frac{dx}{x(\log x)^{5}}\) is

(1) \(-\frac{1}{4(\log x)^{4}} + c\) (2) \(\frac{1}{4(\log x)^{4}} + c\)

(24) \(\int x \sin x dx\) is

(1) \(-x \cos x + \sin x + c\) (2) \(x \cos x - \sin x + c\) (3) \(x \sin x - \cos x + c\) (4) \(x \sin x + \cos x + c\)

(25) \(\int e^{x^{2}} x dx\) is

(1) \(2(1 + x^{2}) e^{x^{2}} + c\) (2) \(2(x^{2} - 1) e^{x^{2}} + c\) (3) \(2(1 - x^{2}) e^{x^{2}} + c\) (4) \(2(x^{2} + 1) e^{x^{2}} + c\)

## Summary

(1) If \(k\) is any constant, then \(\int k f(x) dx = k \int f(x) dx\)

(2) \(\int (f_{1}(x) \pm f_{2}(x)) dx = \int f_{1}(x) dx \pm \int f_{2}(x) dx\)

If \(\int f(x) dx = g(x) + c\), then \(\int f(ax + b) dx = \frac{1}{a} g(ax + b) + c\)

(1) \(\int \tan x dx = \log |\sec x| + c\) (2) \(\int \cot x dx = \log |\sin x| + c\)

(3) \(\int \csc x dx = \log |\csc x - \cot x| + c\) (4) \(\int \sec x dx = \log |\sec x + \tan x| + c\)

**Bernoulli's formula for integration by Parts:**

If \(u\) and \(v\) are functions of \(x\), then the Bernoulli's rule is

\[
\int u dv = uv - u'v_{1} + u''v_{2} - \dots
\]

where \(u', u'', u''', \dots\) are successive derivatives of \(u\) and \(v, v_{1}, v_{2}, v_{3}, \dots\) are successive integrals of \(dv\)

\[
\int e^{ax} \sin bx dx = \frac{e^{ax}}{a^{2} + b^{2}} [a \sin bx - b \cos bx] + c
\]
\[
\int e^{ax} \cos bx dx = \frac{e^{ax}}{a^{2} + b^{2}} [a \cos bx + b \sin bx] + c
\]

\[
\int \frac{dx}{a^{2} - x^{2}} = \frac{1}{2a} \log \left|\frac{a+x}{a-x}\right| + c, \quad \int \frac{dx}{\sqrt{a^{2} - x^{2}}} = \sin^{-1}\left(\frac{x}{a}\right) + c
\]
\[
\int \frac{dx}{x^{2} - a^{2}} = \frac{1}{2a} \log \left|\frac{x-a}{x+a}\right| + c, \quad \int \frac{dx}{\sqrt{x^{2} - a^{2}}} = \log |x + \sqrt{x^{2} - a^{2}}| + c
\]
\[
\int \frac{dx}{a^{2} + x^{2}} = \frac{1}{a} \tan^{-1}\left(\frac{x}{a}\right) + c, \quad \int \frac{dx}{\sqrt{x^{2} + a^{2}}} = \log |x + \sqrt{x^{2} + a^{2}}| + c
\]

\[
\int \sqrt{a^{2} - x^{2}} dx = \frac{x}{2} \sqrt{a^{2} - x^{2}} + \frac{a^{2}}{2} \sin^{-1}\left(\frac{x}{a}\right) + c
\]
\[
\int \sqrt{x^{2} - a^{2}} dx = \frac{x}{2} \sqrt{x^{2} - a^{2}} - \frac{a^{2}}{2} \log |x + \sqrt{x^{2} - a^{2}}| + c
\]
\[
\int \sqrt{x^{2} + a^{2}} dx = \frac{x}{2} \sqrt{x^{2} + a^{2}} + \frac{a^{2}}{2} \log |x + \sqrt{x^{2} + a^{2}}| + c
\]
