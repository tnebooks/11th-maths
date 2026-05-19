---
title: 'two-dimensional-analytical-geometry'
weight: 6
---

# Two Dimensional Analytical Geometry

> "My powers are ordinary. Only my application brings me success".
>
> — Sir Isaac Newton

## 6.1 Introduction

Francois Viète (1540-1603) introduced the first systematic algebraic notation and contributed to the theory of equations. Two French mathematicians-philosophers René Descartes and Pierre de Fermat independently founded analytical geometry in the 1630s by adapting Francois Viète's algebra to the study of geometric loci. Descartes established analytical geometry as "a way of visualizing algebraic formulas" and developed the coordinate system as "a device to locate points on a plane". His main achievement was to bridge the gap between algebra and geometry. With regard to algebra, he explained in detail how algebraic equations can be expressed and explained through the use of geometrical shapes. Analytical geometry is a great invention of Descartes and Fermat. Cartesian geometry, the alternative term used for analytical geometry is named after him.

From the 17th century onwards, mathematics is being developed in two directions: pure and applied mathematics. One of the first areas of applied mathematics studied in the 17th century was the motion of an object in a straight line. The straight line graphs can be used in the fields of study as diverse as business, economics, social sciences, physics, and medicine. The problem of the shortest line plays a chief and historically important role in the foundations of geometry.

Given a real-world problem, our first task is to formulate the problem using the language of mathematics. Many techniques are used in the construction of mathematical models. Let us see how linear equations (models) can be constructed from a given set of information and solved using appropriate mathematical techniques. Consider some of the real-world, simple problems as illustrated below:

**Real life situation 6.1:** When a student walks from his house, at an average speed of \(6 \text{ kmph}\), reaches his school by ten minutes before school starts. When his average speed is \(4 \text{ kmph}\), he reaches his school five minutes late. If he starts to walk to school every day at \(8.00 \text{ A.M}\), then how to find (i) the distance between house and the school (ii) the minimum average speed to reach the school on time and time taken to reach the school (iii) the time at which the school starts (iv) the pair of straight lines of his path of walk (Combined equation of two straight lines).

**Real life situation 6.2:** Suppose the Government has decided to erect a new Electrical Power Transmission Substation to provide better power supply to two villages namely \(A\) and \(B\). The substation has to be on the line \(l\). The distances of villages \(A\) and \(B\) from the foot of the perpendiculars \(P\) and \(Q\) on the line \(l\) are \(3 \text{ km}\) and \(5 \text{ km}\) respectively and the distance between \(P\) and \(Q\) is \(6 \text{ km}\). How to calculate the smallest length of cable required to connect the two villages (or the roads that connect the villages as well as the power station) from the power station and to find the equations of the cable lines (or roads) that connect the power station to two villages.

**Figure 6.1**

**Real life situation 6.3:**

**Figure 6.2**

Consider a hollow cylindrical vessel, with circumference \(24 \text{ cm}\) and height \(10 \text{ cm}\). An ant is located on the outside of vessel \(4 \text{ cm}\) from the bottom. There is a drop of honey at the diagrammatically opposite inside of the vessel, \(3 \text{ cm}\) from the top. What is the shortest distance the ant would need to crawl to get the honey? What is the equation of the path traced out by the ant? Here is a picture that illustrates the position of the ant and the honey.

**Real life situation 6.4:** The quantity demanded of a certain type of Compact Disk is 22,000 units when a unit price is ₹8. The customer will not buy the disk, at a unit price of ₹30 or higher. On the other side the manufacturer will not market any disk if the price is ₹6 or lower. However, if the price is ₹14 the manufacturer can supply 24,000 units. Assume that the quantity demanded and quantity supplied are linearly proportional to the price. How to find (i) the demand equation (ii) supply equation (iii) the market equilibrium quantity and price. (iv) The quantity of demand and supply when the price is ₹10.

The equation of the straight line for each of the problems stated above, not only solves the specific case of solutions but also helps us get many information through it. Later, in this chapter, let us try to solve these types of problems by using the concepts of straight lines. In order to understand the straight line, we need to get acquainted with some of its basic concepts. Let us discuss those in detail.

## Learning Objective

On completion of this chapter, the students expected to know

- the equation of a line in different forms
- whether two given lines are parallel or perpendicular;
- the distance of a given point from a given line and between two parallel lines,
- the family of straight lines for a given condition
- the equation of pair of straight lines, angle between them and angle bisectors

## 6.2 Locus of a point

### Definition 6.1

A **point** is an exact position or location on a plane surface.

It is important to understand that a point is not a thing, but a place. We indicate the position of a point by placing a dot. In plane analytical geometry, points are defined as ordered pairs of real numbers, say, \((x, y)\) with reference to the coordinate system.

Generally, a horizontal line is called the \(x\)-axis; and the line vertical to the \(x\)-axis is called the \(y\)-axis. Intersection of these two axes is called the origin. Any point \(P\) in the plane can be located by a unique ordered pair of numbers \((x, y)\) where \(x\) gives the distance between the point \(P\) and the \(y\)-axis and \(y\) denote the distance between the point \(P\) and the \(x\)-axis. Note that if \(x\) is negative it lies left of \(y\)-axis, similarly if \(y\) is negative it lies below the \(x\)-axis. In applications, often letters other than \(x\) and \(y\) are used, and different scales are chosen in the horizontal and vertical directions.

### Definition 6.2

The path traced out by a moving point under certain conditions is called the **locus** of that point. Alternatively, when a point moves in accordance with a geometrical law, its path is called locus. The plural of locus is loci.

The following illustrations shows some cases of loci and its different uses.

**Illustration 6.1:** In cricket, when a ball is bowled by a bowler, the path traced out by the ball is the locus of the ball. Whenever there is dispute between batsmen and the fielders for leg before wicket (LBW) decisions, the locus of the ball solves the crises, raised by the players for review, through the third umpire. The likely path of the ball can be projected forward, through the batsman's legs, to see whether it would have hit the stumps or not. Consultation of the third umpire, for conventional slow motion or Hawk-Eye, the probable decision will be taken. This method is currently sanctioned in international cricket.

**Figure 6.3**

**Illustration 6.2:** Suppose \(P\) be a point on the rim (circumference) of a circular wheel. When the circle is rolling without slipping along a straight line, the locus of the point \(P\) on the rim is shown in figure. The path traced out by the point \(P\) is known as cycloid. (Try yourself by taking a point inside the circle. Find the names of the curve from the web site.)

**Figure 6.4**

**Illustration 6.3:** A missile is launched from the army ship to attack and another from the land to intercept it. The loci of the missiles are shown in figure.

**Figure 6.5**

Locus of missiles play a vital role in many wars. During the Gulf War (2 Aug 1990 - 28 Feb 1991), Iraq attacked Israeli cities with Scud missiles. To defend from Scud attack, Israel used Patriot missiles to shoot down enemy missiles. To launch a satellite or space shuttle successfully, the determination of path plays a crucial role in space research.

An equation in the two variables \(x\) and \(y\) will ordinarily be satisfied by infinitely many pair of real value of \(x\) and \(y\). Every such pair is called a real solution of the equation. Each real solution of the equation will have its graph. The collection of all these graphs is called the locus of the given equation.

The following table shows some important loci in mathematics:

| A moving point \(P\) under the given condition | Graph | Name of the path |
|------------------------------------------------|-------|------------------|
| A point \(P\) moves such that it is equidistant from two fixed points \(A\) and \(B\) | | Perpendicular bisector of the line segment \(AB\) |
| A point \(P\) moves such that it is equidistant from two fixed lines \(ox\) and \(oy\) | | Angle bisector of the angle \(\angle xoy\) |
| A point \(P\) moves equidistant from a fixed point \(O\) | | Circle |

Now let us discuss the ways of finding the locus of the points. The equation of the locus is the relation that exists between the coordinates of all the points strictly lying on the path.

### Procedure for finding the equation of the locus of a point

(i) If we are finding the equation of the locus of a point \(P\), assign coordinates, say \((h, k)\) to \(P\).

(ii) Express the given conditions as equations in terms of the known quantities and unknown parameters.

(iii) Eliminate the parameters, so that the resulting equation contains only \(h, k\) and known quantities.

(iv) Replace \(h\) by \(x\), and \(k\) by \(y\), in the resulting equation. The resulting equation is the equation of the locus of point \(P\).

### Example 6.1

Find the locus of a point which moves such that its distance from the \(x\)-axis is equal to the distance from the \(y\)-axis.

**Solution:**

Let \(P(h, k)\) be a point on the locus.

Let \(A\) and \(B\) be the foot of the perpendiculars drawn from the point \(P\) on the \(x\)-axis and the \(y\)-axis respectively.

Therefore \(P\) is \((OA, OB) = (BP, AP) = (h, k)\). Given that \(AP = BP\)

\[
\Rightarrow k = h
\]

replacing \(h\) and \(k\) by substituting \(h = x\) and \(k = y\). The locus of \(P\) is \(y = x\), is a line passing through the origin.

**Figure 6.9**

### Example 6.2

Find the path traced out by the point \(\left(ct, \frac{c}{t}\right)\), here \(t \neq 0\) is the parameter and \(c\) is a constant.

**Solution:**

Let \(P(h, k)\) be a point on the locus. From the given information, we have \(h = ct\) and \(k = \frac{c}{t}\). To eliminate \(t\), taking product of these two equations

\[
(h)(k) = (ct)\left(\frac{c}{t}\right) \Rightarrow hk = c^2
\]

Therefore, the required locus is \(xy = c^2\).

### Example 6.3

Find the locus of a point \(P\) moves such that its distances from two fixed points \(A(1, 0)\) and \(B(5, 0)\), are always equal.

**Solution:**

Given that \(A(1, 0)\) and \(B(5, 0)\).

Let \(P(h, k)\) be any point on the required path.

From the information we have \(AP = BP\)

That is

\[
\sqrt{(h - 1)^2 + (k - 0)^2} = \sqrt{(h - 5)^2 + (k - 0)^2} \Rightarrow h = 3
\]

Therefore the locus of \(P\) is \(x = 3\), which is a straight line parallel to the \(y\)-axis.

**Figure 6.10**

### Example 6.4

If \(\theta\) is a parameter, find the equation of the locus of a moving point, whose coordinates are \((a\sec\theta, b\tan\theta)\).

**Solution:**

Let \(P(h, k)\) be any point on the required path. From the given information we have

\[
h = a\sec\theta, \quad k = b\tan\theta
\]

To eliminate the parameter \(\theta\), squaring and subtracting, we get

\[
\left(\frac{h}{a}\right)^2 - \left(\frac{k}{b}\right)^2 = \sec^2\theta - \tan^2\theta
\]
\[
\left(\frac{h}{a}\right)^2 - \left(\frac{k}{b}\right)^2 = 1
\]

Therefore the locus of the given point is

\[
\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1.
\]

Whenever the parameters are in trigonometric form, try to use trigonometric identities to eliminate \(\theta\)

\[
\sin^2\theta + \cos^2\theta = 1, \quad \sec^2\theta - \tan^2\theta = 1, \quad \csc^2\theta - \cot^2\theta = 1.
\]

### Example 6.5

A straight rod of length 6 units, slides with its ends \(A\) and \(B\) always on the \(x\) and \(y\) axes respectively. If \(O\) is the origin, then find the locus of the centroid of \(\triangle OAB\).

**Solution:**

Let the coordinates of the points \(O\), \(A\) and \(B\) are \((0, 0)\), \((a, 0)\) and \((0, b)\) respectively.

Observed that the points \(A\) and \(B\) are moving points.

Let \((h, k)\) be a centroid of \(\triangle OAB\).

Centroid of \(\triangle OAB\) is

\[
\left(\frac{0 + a + 0}{3}, \frac{0 + 0 + b}{3}\right) = (h, k).
\]
\[
\frac{a}{3} = h \Rightarrow a = 3h, \quad \frac{b}{3} = k \Rightarrow b = 3k
\]

From right \(\triangle OAB\), \(OA^2 + OB^2 = AB^2\)

\[
(3h)^2 + (3k)^2 = (6)^2 \Rightarrow h^2 + k^2 = 4
\]

Locus of \((h, k)\) is a circle, \(x^2 + y^2 = 4\).

**Figure 6.11**

### Example 6.6

If \(\theta\) is a parameter, find the equation of the locus of a moving point, whose coordinates are \((a(\theta - \sin\theta), a(1 - \cos\theta))\).

**Solution:**

Let \(P(h, k)\) be any point on the required path. From the given information we have

\[
h = a(\theta - \sin\theta)
\]
\[
k = a(1 - \cos\theta)
\]

**Figure 6.12**

Let us find the value of \(\theta\) and \(\sin\theta\) from equation (6.2)

\[
k = a(1 - \cos\theta)
\]
\[
\cos\theta = \frac{a - k}{a} \Rightarrow \theta = \cos^{-1}\left(\frac{a - k}{a}\right) \quad \text{and} \quad \sin\theta = \frac{\sqrt{2ak - k^2}}{a}
\]

Substituting above values in (6.1) we get

\[
h = a\cos^{-1}\left(\frac{a - k}{a}\right) - \sqrt{2ak - k^2}
\]

The locus of \((h, k)\) is

\[
x = a\cos^{-1}\left(\frac{a - y}{a}\right) - \sqrt{2ay - y^2} \tag{6.3}
\]

Though, the parametric form given above is converted to Cartesian form, in some cases the parametric form may be more useful to work with than the cartesian form.

## Exercise 6.1

1. Find the locus of \(P\), if for all values of \(\alpha\), the co-ordinates of a moving point \(P\) is

   (i) \((9\cos\alpha, 9\sin\alpha)\)

   (ii) \((9\cos\alpha, 6\sin\alpha)\).

2. Find the locus of a point \(P\) that moves at a constant distant of

   (i) two units from the \(x\)-axis

   (ii) three units from the \(y\)-axis.

3. If \(\theta\) is a parameter, find the equation of the locus of a moving point, whose coordinates are \(x = a\cos^3\theta\), \(y = a\sin^3\theta\).

4. Find the value of \(k\) and \(b\), if the points \(P(-3, 1)\) and \(Q(2, b)\) lie on the locus of \(x^2 - 5x + ky = 0\).

5. A straight rod of length 8 units slides with its ends \(A\) and \(B\) always on the \(x\) and \(y\) axes respectively. Find the locus of the mid point of the line segment \(AB\).

6. Find the equation of the locus of a point such that the sum of the squares of the distance from the points \((3, 5)\), \((1, -1)\) is equal to 20.

7. Find the equation of the locus of the point \(P\) such that the line segment \(AB\), joining the points \(A(1, -6)\) and \(B(4, -2)\), subtends a right angle at \(P\).

8. If \(O\) is origin and \(R\) is a variable point on \(y^2 = 4x\), then find the equation of the locus of the mid-point of the line segment \(OR\).

9. The coordinates of a moving point \(P\) are \(\left(\frac{a}{2}(\cos\theta + \sin\theta), \frac{b}{2}(\cos\theta - \sin\theta)\right)\), where \(\theta\) is a variable parameter. Show that the equation of the locus \(P\) is \(b^2 x^2 - a^2 y^2 = a^2 b^2\).

10. If \(P(2, -7)\) is a given point and \(Q\) is a point on \(2x^2 + 9y^2 = 18\), then find the equations of the locus of the mid-point of \(PQ\).

11. If \(R\) is any point on the \(x\)-axis and \(Q\) is any point on the \(y\)-axis and \(P\) is a variable point on \(RQ\) with \(RP = b\), \(PQ = a\), then find the equation of locus of \(P\).

12. If the points \(P(6, 2)\) and \(Q(-2, 1)\) and \(R\) are the vertices of a \(\triangle PQR\) and \(R\) is the point on the locus \(y = x^2 - 3x + 4\), then find the equation of the locus of centroid of \(\triangle PQR\).

13. If \(Q\) is a point on the locus of \(x^2 + y^2 + 4x - 3y + 7 = 0\), then find the equation of locus of \(P\) which divides segment \(OQ\) externally in the ratio 3:4, where \(O\) is origin.

14. Find the points on the locus of points that are 3 units from \(x\)-axis and 5 units from the point \((5, 1)\).

15. The sum of the distance of a moving point from the points \((4, 0)\) and \((-4, 0)\) is always 10 units. Find the equation of the locus of the moving point.

## 6.3 Straight Lines

Linear equations can be rewritten using the laws of elementary algebra into several different forms. These equations are often referred to as the "equations of the straight line." In the general form the linear equation is written as:

\[
ax + by + c = 0 \tag{6.4}
\]

where \(a\) and \(b\) are not both equal to zero. The name "linear" comes from the fact that the set of solutions of such an equation forms a straight line in the plane. In this chapter "line", we mean a straight line unless otherwise stated.

There are many ways to write the equation of a line which can all be converted from one to another by algebraic manipulation. These forms are generally named by the type of information (data) about the line that is needed to write down the form. Some of the important data are points, slope, and intercepts.

### 6.3.1 The relationship between the angle of inclination and slope

### Definition 6.3

The **angle of inclination** of a straight line is the angle, say \(\theta\), made by the line with the \(x\)-axis measured in the counter clockwise (positive) direction.

**Figure 6.13**

### Definition 6.4

The **slope** or **gradient** of a straight line is a number that measures its "direction and steepness".

The slope of a line in the plane containing the \(x\) and \(y\) axes, is generally represented by the letter \(m\). It can be measured in many ways as given below:

(i) When \(\theta\) is the angle of inclination of the line with the \(x\)-axis measured in the counter clockwise direction then the slope
\[
m = \tan\theta.
\]
When \(\theta = \frac{\pi}{2}\), then \(m = \tan\frac{\pi}{2}\) is undefined.

(ii) When \((x_1, y_1)\) and \((x_2, y_2)\) are any two points on the line with \(x_2 \neq x_1\), then the slope is the change in the \(y\) coordinate divided by the corresponding change in the \(x\) coordinate. This is described by the following equation.

\[
m = \frac{\Delta y}{\Delta x} = \frac{y_2 - y_1}{x_2 - x_1} = \frac{\text{vertical change}}{\text{horizontal change}}
\]

**Figure 6.14**

(iii) When the general form of the linear equation \(ax + by + c = 0\) is given, then the slope of the line is

\[
m = -\frac{a}{b}, \quad b \neq 0.
\]

\(m\) is undefined when \(b = 0\).

The slope of a line can be a positive or negative or zero or undefined as shown below:

**Figure 6.15**

### Definition 6.5

In a plane three or more points are said to be **collinear** if they lie on a same straight line.

Let \(A\), \(B\) and \(C\) be any three points on a plane. If the slope of \(AB\) is equal to the slope of \(BC\) (or \(AC\)), then they are collinear.

### 6.3.2 Intercepts of a Line

### Definition 6.6

The **intercept** of a line is the point at which the line crosses either the \(x\)-axis or the \(y\)-axis.

The \(x\)-intercept is a point where the \(y\) value is zero, and the \(y\)-intercept is a point where the \(x\)-value is zero.

Therefore the intercepts of a line are the points where the line intersects, or crosses, the horizontal and vertical axes.

Therefore it is clear that

(i) the equation of the \(y\)-axis is \(x = 0\)

(ii) the equation of the \(x\)-axis is \(y = 0\)

In the figure OA is the \(x\)-intercept and \(OB\) is the \(y\)-intercept.

**Figure 6.16**

Different types of \(x\) and \(y\) Intercepts:

**Figure 6.17**

We have learnt the definition and detailed information about the points, slope and intercepts. Using these information, let us recall the different forms of an equation of a straight line.

### 6.3.3 Different Forms of an equation of a straight line

Two conditions are sufficient to determine uniquely the equation of a straight line. Using the combination of any two information from slope, intercepts and points, we can now form different types of straight lines such as

(i) Slope and intercept form

(ii) Point and Slope form

(iii) The two Point form

(iv) Intercepts form

and two more special types are

(v) Normal form

(vi) Parametric form

Now let us look at an important way of describing the relationship between two quantities using the notion of a function.

**(i) Slope and Intercept form**

Proportional linear functions can be written in the form \(y = mx\), where \(m\) is the slope of the line. Non proportional linear functions can be written in the form

\[
y = mx + b, \quad b \neq 0 \tag{6.5}
\]

This is called the slope-intercept form of a straight line because \(m\) is the slope and \(b\) is the \(y\)-intercept.

**Figure 6.18**

(1) when \(b = 0\) and \(m \neq 0\), the line passes through the origin and its equation is \(y = mx\)

(2) when \(b = 0\) and \(m = 0\), the line coincides with the \(x\)-axis and its equation is \(y = 0\)

(3) when \(b \neq 0\) and \(m = 0\), the line is parallel to the \(x\)-axis and its equation is \(y = b\).

**(ii) Point - Slope form:**

Let \(m\) be the slope of the line and \(A(x_1, y_1)\) be the given point on the line. Let \(P(x, y)\) be any point other than \(A\) on the given line. Slope of the line joining \(A(x_1, y_1)\) and

\(P(x, y)\) is given by \(m = \frac{y - y_1}{x - x_1}\)

\[
\Rightarrow y - y_1 = m(x - x_1),
\]

**Figure 6.19**

which is known as point-slope form.

Since, the slope \(m\) is undefined for lines parallel to the \(y\)-axis, the point-slope form of the equation will not give the equation of a line through \(A(x_1, y_1)\) parallel to the \(y\)-axis. However, this presents no difficulty, since for any such line the abscissa of any point on the line is \(x_1\). Therefore, the equation of such a line is \(x = x_1\).

**(iii) Two Points form**

If \((x_1, y_1)\) and \((x_2, y_2)\) are any two points on the line with \(x_2 \neq x_1\) and \(y_1 \neq y_2\), then the slope is \(m = \frac{y_2 - y_1}{x_2 - x_1}\).

The equation using point-slope form, we get

\[
y - y_1 = \frac{y_2 - y_1}{x_2 - x_1}(x - x_1).
\]

Rewriting the above equation, we get

\[
\frac{y - y_1}{y_2 - y_1} = \frac{x - x_1}{x_2 - x_1} \tag{6.7}
\]

This equation is called two points form.

Two points form can also be represented in terms of the determinant as

\[
\begin{vmatrix}
x - x_1 & y - y_1 \\
x_2 - x_1 & y_2 - y_1
\end{vmatrix} = 0.
\]

**Figure 6.20**

**(iv) Intercepts form:**

If the intercepts of a line on the \(x\)-axis and the \(y\)-axis are known then the equation of the line can also be found using intercepts. Suppose \(x\)-intercept \(OA = a\) and \(y\)-intercept \(OB = b\), where \(a\) and \(b\) are non-zero, then the line passes through two points \(A(a, 0)\) and \(B(0, b)\) is

\[
\frac{y - 0}{b - 0} = \frac{x - a}{0 - a} \Rightarrow \frac{x}{a} + \frac{y}{b} = 1
\]

**Figure 6.21**

The above equation is called an intercept form.

Lines that pass through the origin or which are horizontal or vertical or violate the nonzero condition on \(a\) or \(b\) cannot be represented in this form.

In most of the cases this form is used to draw the graph of the line in easy way.

**(v) Normal form:**

Let \(A\) and \(B\) be the intercepts made by the line.

Let \(p\) be the length of the normal \(OP\) drawn from the origin to a line \(AB\), which makes an angle \(\alpha\) with the \(x\)-axis.

In right \(\triangle OPA\), \(\frac{OP}{OA} = \cos\alpha\) and
in right \(\triangle OPB\), \(\frac{OP}{OB} = \cos\left(\frac{\pi}{2} - \alpha\right) = \sin\alpha\)

\[
\Rightarrow \frac{1}{OA} = \frac{\cos\alpha}{p} \quad \text{and} \quad \frac{1}{OB} = \frac{\sin\alpha}{p}
\]

Using the above data in intercepts form

\[
\frac{x}{OA} + \frac{y}{OB} = 1
\]
We get,
\[
\frac{x\cos\alpha}{p} + \frac{y\sin\alpha}{p} = 1
\]
\[
\Rightarrow x\cos\alpha + y\sin\alpha = p
\]

**Figure 6.22**

is called the normal form of equation.

If \(p\) is positive in all positions of the line and if \(\alpha\) is always measured from \(x\)-axis in the positive direction, this equation holds in every case as shown in the figure.

**Figure 6.23**

**(vi) Parametric form:**

Parametric equations of a straight line is of the form

\[
x = ar + x_1 \quad \text{and} \quad y = br + y_1
\]

where \(a\) and \(b\) are constants and \(r\) is the parameter.

\[
\frac{x - x_1}{a} = \frac{y - y_1}{b} = r, \quad (a \neq 0, b \neq 0).
\]

Suppose we have the equation of the line passing through the point \(Q(x_1, y_1)\) and making an angle \(\theta\) with \(x\)-axis. Let \(P(x, y)\) be a point on the line at a distance \(r\) from \(Q\). Drop perpendiculars \(QN\) and \(PM\) respectively from \(Q\) and \(P\) to the \(x\)-axis and perpendicular \(QR\) to \(PM\).

From the right \(\triangle QRP\)

\[
x - x_1 = QR = PQ\cos\theta = r\cos\theta
\]

\[
\text{Therefore } \frac{x - x_1}{\cos\theta} = r \tag{6.10}
\]

Similarly, \(y - y_1 = RP = QP\sin\theta = r\sin\theta\)

\[
\Rightarrow \frac{y - y_1}{\sin\theta} = r \tag{6.11}
\]

From (6.10) and (6.11) we get

\[
\frac{x - x_1}{\cos\theta} = \frac{y - y_1}{\sin\theta} = r \tag{6.12}
\]

where the parameter \(r\) is the distance between \((x_1, y_1)\) and any point \((x, y)\) on the line. This is called the symmetric form or parametric form of the line.

The coordinates of any point on this line can be written as \((x_1 + r\cos\theta, y_1 + r\sin\theta)\). Clearly coordinates of the point depend on the value of \(r\). This variable \(r\) is called parameter. Since \(r\) is a parameter the equations, \(x = x_1 + r\cos\theta\), \(y = y_1 + r\sin\theta\), is called the parametric equations of the line. The value of \(r\) is positive for all points lying on the line one side of the given point and negative for all points lying on the line other side of the given point.

**(vii) The general form** of the equation of the straight line is

\[
ax + by + c = 0, \quad \text{where } a, b \text{ and } c \text{ are all not zeros}
\]

The below table summarizes the types of straight lines related to the given information.

| S.No. | Information given | Equation of the straight line |
|-------|-------------------|------------------------------|
| 1 | Slope \((m)\) and \(y\)-intercept \((b)\) | \(y = mx + b\) |
| 2 | Slope \((m)\) and point \((x_1, y_1)\) | \(y - y_1 = m(x - x_1)\) |
| 3 | Two points \((x_1, y_1)\) and \((x_2, y_2)\) | \(\frac{y - y_1}{y_2 - y_1} = \frac{x - x_1}{x_2 - x_1}\) |
| 4 | \(x\)-intercept \((a)\) and \(y\)-intercept \((b)\) | \(\frac{x}{a} + \frac{y}{b} = 1\) |
| 5 | Normal length \((p)\), angle \((\alpha)\) | \(x\cos\alpha + y\sin\alpha = p\) |
| 6 | Parametric form: parameter-\(r\) | \(\frac{x - x_1}{\cos\theta} = \frac{y - y_1}{\sin\theta} = r\) |
| 7 | The general equation | \(ax + by + c = 0\) |

If we have two variable quantities, then each can be represented by a variable. If the rate of change of one variable with respect to the other variable is constant, then the relationship between them is linear.

In linear equation, the choice of one as independent and other as a dependent may represent the physical reality or may be convenient fiction. The independent variable is normally plotted on the horizontal axis (\(x\)-axis), the dependent variable on the vertical axis (\(y\)-axis). That is the values of \(x\) are always independent and \(y\) is dependent on those values of \(x\).

The number scales on the two axes need not be the same. Indeed, in many applications different quantities are represented by \(x\) and \(y\). For example, \(x\) may represent the number of mobile phones sold and \(y\) the total revenue resulting from the sales. In such cases it is often desirable to choose different number scales to represent the different quantities. However, the zero of both number scales coincide at the origin of the two-dimensional coordinate system.

From the given information, to solve the problem using the concepts of straight lines, we have to select suitably one of the six equations given above.

### Example 6.7

Find the slope of the straight line passing through the points (5, 7) and (7, 5). Also find the angle of inclination of the line with the \(x\)-axis.

**Solution:**

Let \((x_1, y_1)\) and \((x_2, y_2)\) be (5, 7) and (7, 5) respectively. Let \(\theta\) be the angle of inclination of the line with the \(x\)-axis.

Slope of the line

\[
m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{5 - 7}{7 - 5} = -1
\]

We know that \(m = \tan\theta\)

That is, \(\tan\theta = -1 \Rightarrow \theta = \frac{3\pi}{4} \text{ or } 135^\circ\)

Slope and angle of inclination of the line with the \(x\)-axis are respectively \(m = -1\) and \(\theta = \frac{3\pi}{4}\).

**Figure 6.25**

### Example 6.8

Find the equation of a straight line cutting an intercept of 5 from the negative direction of the \(y\)-axis and is inclined at an angle \(150^\circ\) to the \(x\)-axis.

**Solution:**

Given that the negative \(y\) intercept is 5 i.e., \(b = -5\) and \(\theta = 150^\circ\).

Slope \(m = \tan 150^\circ = \tan(180^\circ - 30^\circ) = -\tan 30^\circ = -\frac{1}{\sqrt{3}}\)

Slope and intercept form of the equation is \(y = mx + b\)

That is \(y = -\frac{1}{\sqrt{3}}x - 5\)

\[
x + \sqrt{3}y + 5\sqrt{3} = 0
\]

**Figure 6.26**

### Example 6.9

Show the points \(\left(0, -\frac{3}{2}\right)\), \((1, -1)\) and \(\left(2, -\frac{1}{2}\right)\) are collinear.

**Solution:**

Let \(A, B\) and \(C\) be \(\left(0, -\frac{3}{2}\right)\), \((1, -1)\) and \(\left(2, -\frac{1}{2}\right)\) respectively.

The slope of \(AB\) is \(\frac{-1 + \frac{3}{2}}{1 - 0} = \frac{1}{2}\).

The slope of \(BC\) is \(\frac{-\frac{1}{2} + 1}{2 - 1} = \frac{1}{2}\).

Thus, the slope of \(AB\) is equal to slope of \(BC\). Hence, \(A, B\) and \(C\) are lying on the same line.

If the rate of change of one variable with respect to the other variable is constant, then this constant rate of change can be taken as slope (such as speed, constant increase or constant decrease...). Also equations of straight lines depend on the coordinate axes how we define it. Thus in real world problems the equations are not necessarily identical but the path and distance will always be the same.

### Example 6.10

The Pamban Sea Bridge is a railway bridge of length about 2065 m constructed on the Palk Strait, which connects the Island town of Rameswaram to Mandapam, the main land of India. The Bridge is restricted to a uniform speed of only \(12.5 \text{ m/s}\). If a train of length \(560 \text{ m}\) starts at the entry point of the bridge from Mandapam, then

(i) find an equation of the motion of the train.

(ii) when does the engine touch island

(iii) when does the last coach cross the entry point of the bridge

(iv) what is the time taken by a train to cross the bridge.

**Solution:**

Let the \(x\)-axis be the time in seconds the \(y\)-axis be the distance in metres. Let the engine be at the origin \(O\). Therefore the length of the train \(560 \text{ m}\) is the negative \(y\)-intercept.

The uniform speed \(12.5 \text{ m/s}\) is the slope of the motion of the train. \(\left(\text{speed} = \frac{\text{distance}}{\text{time}}\right)\)

Since we are given slope and \(y\)-intercept, the equation of the line is

\[
y = mx + b \tag{6.13}
\]

**Figure 6.27**

(i) The equation of the motion of the train, when \(m = 12.5\) and \(b = -560\), is

\[
y = 12.5x - 560
\]

(ii) When the engine touches the other side of the bridge (island)

\[
y = 2065 \quad \text{and} \quad b = 0
\]
\[
2065 = 12.5x
\]
\[
x = 165.2 \text{ seconds}.
\]

(iii) When \(y = 0\), the last coach cross the entry point of the bridge,

\[
0 = 12.5x - 560
\]
\[
x = 44.8 \text{ seconds}.
\]

(iv) When \(y = 2065\), the time taken for the train to cross the other end of the bridge is given by

\[
2065 = 12.5x - 560
\]
\[
x = 210 \text{ seconds}.
\]

(One may take the tail of the train as the origin and can find the equation of the straight line. It need not be identical with the above equation, but the path traced out by the train, distance, time, etc., will be the same. Try it.)

### Example 6.11

Find the equations of the straight lines, making the \(y\)-intercept of 7 and angle between the line and the \(y\)-axis is \(30^\circ\).

**Solution:**

There are two straight lines making \(30^\circ\) with the \(y\)-axis.

They make \(60^\circ\) and \(120^\circ\) with the \(x\)-axis.

Let \(m_1\) be \(\tan 60^\circ = \sqrt{3}\) and
\(m_2\) be \(\tan 120^\circ = \tan(180^\circ - 60^\circ) = -\tan 60^\circ = -\sqrt{3}\)

\[
m_1 = \sqrt{3}, \quad m_2 = -\sqrt{3} \quad \text{and} \quad b = 7
\]

Equations of lines are \(y = m_1x + b\) and \(y = m_2x + b\)

\[
y = \sqrt{3}x + 7 \quad \text{and} \quad y = -\sqrt{3}x + 7
\]

**Figure 6.28**

Whenever two points are given, one can apply two points form or point and slope form. Also when two intercepts are given, one can apply intercepts form or two points form. The following example, is solved in Chapter V, using the concepts of sequence and series. Let us solve this problem here, using the concepts of straight lines.

### Example 6.12

The seventh term of an arithmetic progression is 30 and tenth term is 21.

(i) Find the first three terms of an A.P.

(ii) Which term of the A.P. is zero (if exists)

(iii) Find the relationship between Slope of the straight line and common difference of A.P.

**Solution:**

Since there is a constant increase or decrease in arithmetic progression, it is a linear function. Let the \(x\)-axis be the number of the term and the \(y\)-axis be the value of the term. Let \((x_1, y_1)\) and \((x_2, y_2)\) be (7, 30) and (10, 21) respectively, using the equation

\[
\begin{aligned}
y - y_1 &= m(x - x_1) \\
y - 30 &= \frac{21 - 30}{10 - 7}(x - 7) \\
y &= -3x + 51
\end{aligned} \tag{6.14}
\]

(i) Substituting \(x = 1, 2\) and \(3\) in the equation we get the first three terms of AP as 48, 45, and 42.

(ii) Substituting \(y = 0\) in equation we get

\[
0 = -3x + 51 \Rightarrow x = 17.
\]

That is seventeenth term of A.P. is zero.

(iii) Clearly the slope of the line \(-3\) is equal to the common difference A.P.

From this example, slope of the line is equal to common difference of A.P. (Try to prove it)

### Example 6.13

The quantity demanded of a certain type of Compact Disk is 22,000 units when a unit price is ₹8. The customer will not buy the disk, at a unit price of ₹30 or higher. On the other side the manufacturer will not market any disk if the price is ₹6 or lower. However, if the price ₹14 the manufacturer can supply 24,000 units. Assume that the quantity demanded and quantity supplied are linearly proportional to the price. Find (i) the demand equation (ii) supply equation (iii) the market equilibrium quantity and price. (iv) The quantity of demand and supply when the price is ₹10.

**Solution:**

Let the \(x\)-axis represent the number of units in thousands and the \(y\)-axis represent the price in rupees per unit.

(i) For demand function, let \((x_1, y_1)\) and \((x_2, y_2)\) be (22, 8) and (0, 30) respectively.

Using two point form, we get the demand function as

\[
\frac{y - 8}{30 - 8} = \frac{x - 22}{0 - 22} \Rightarrow y_D = -x + 30 \quad (\text{demand function})
\]

**Figure 6.29**

(ii) For supply function, let \((x_1, y_1)\) and \((x_2, y_2)\) be (0, 6) and (24, 14) respectively.

Using two point form, we get the supply function as

\[
\frac{y - 6}{14 - 6} = \frac{x - 0}{24 - 0} \Rightarrow y_S = \frac{1}{3}x + 6 \quad (\text{supply function})
\]

(iii) At the market equilibrium the demand equals to supply,

That is, \(y_D = y_S \Rightarrow -x + 30 = \frac{1}{3}x + 6\)

\[
x = 18 \quad \text{and} \quad y = 12.
\]

Market equilibrium price is ₹12 and number of quantity is 18,000 units.

(iv) When the price \(y = 10\), from the demand function \(y_D = -x + 30\), we get \(x = 20\).

That is, the demand is 20,000 units.

Similarly from the supply function \(y_S = \frac{1}{3}x + 6\), we get \(x = 12\). Hence, the supply is 12,000 units.

### Example 6.14

Find the equation of the straight line passing through \((-1, 1)\) and cutting off equal intercepts, but opposite in signs with the two coordinate axes.

**Solution:**

Let the intercepts cut off from the axes be of lengths \(a\) and \(-a\).

Equation of the line is of the form \(\frac{x}{a} - \frac{y}{a} = 1 \Rightarrow x - y = a\).

Since it passes through \((-1, 1)\)

\[
\Rightarrow (-1) - (1) = a \Rightarrow a = -2.
\]

Equation of the line is \(x - y + 2 = 0\).

**Figure 6.30**

### Example 6.15

A straight line \(L\) with negative slope passes through the point (9, 4) cuts the positive coordinate axes at the points \(P\) and \(Q\). As \(L\) varies, find the minimum value of \(|OP| + |OQ|\), where \(O\) is the origin.

**Solution:**

Let \(m\) be the slope of the line \(L\). Since it passes through the point (9, 4) the equation of the line \(L\) is \(y - 4 = m(x - 9)\).

The points \(P\) and \(Q\) are respectively \(\left(9 - \frac{4}{m}, 0\right)\) and \((0, 4 - 9m)\).

\[
(m < 0) \quad |OP| + |OQ| = \left|9 - \frac{4}{m}\right| + |4 - 9m|
\]
\[
= \left|9 + \frac{4}{k}\right| + |4 + 9k| \quad (m < 0, \text{ take } m = -k, k > 0)
\]
\[
= \left(9 + \frac{4}{k}\right) + (4 + 9k) \quad (\text{all terms are positive})
\]
\[
= (4 + 9) + \left(\frac{4}{k} + 9k\right)
\]
\[
\geq 13 + 2\sqrt{\frac{4}{k} \times 9k} \quad (\text{Arithmetic mean} \geq \text{Geometric mean})
\]
\[
|OP| + |OQ| \geq 25
\]

Therefore, the minimum absolute value of \(|OP| + |OQ|\) is 25.

### Example 6.16

The length of the perpendicular drawn from the origin to a line is 12 and makes an angle \(150^\circ\) with positive direction of the \(x\)-axis. Find the equation of the line.

**Solution:**

Here, \(p = 12\) and \(\alpha = 150^\circ\). So the equation of the required line is of the form

\[
x\cos\alpha + y\sin\alpha = p
\]
That is,
\[
x\cos 150^\circ + y\sin 150^\circ = 12
\]
\[
\Rightarrow \sqrt{3}x - y + 24 = 0
\]

### Example 6.17

Area of the triangle formed by a line with the coordinate axes, is 36 square units. Find the equation of the line if the perpendicular drawn from the origin to the line makes an angle of \(45^\circ\) with positive the \(x\)-axis.

**Solution:**

Let \(p\) be the length of the perpendicular drawn from the origin to the required line. The perpendicular makes \(45^\circ\) with the \(x\)-axis. The equation of the required line is of the form,

\[
x\cos\alpha + y\sin\alpha = p
\]
\[
\Rightarrow x\cos 45^\circ + y\sin 45^\circ = p
\]
\[
\Rightarrow x + y = \sqrt{2}p
\]

This equation cuts the coordinate axes at \(A(\sqrt{2}p, 0)\) and \(B(0, \sqrt{2}p)\). Area of the \(\triangle OAB\) is

\[
\frac{1}{2} \times \sqrt{2}p \times \sqrt{2}p = 36 \Rightarrow p = 6 \quad (\because p \text{ is positive})
\]

Therefore the equation of the required line is

\[
x + y = 6\sqrt{2}
\]

### Example 6.18

Find the equation of the lines make an angle \(60^\circ\) with positive \(x\)-axis and at a distance \(5\sqrt{2}\) units measured from the point \((4, 7)\), along the line \(x - y + 3 = 0\).

**Solution:**

The angle of inclination of the line \(x - y + 3 = 0\) is \(45^\circ\), and a point on the line is \((4, 7)\). Using parametric form

\[
\frac{x - x_1}{\cos\theta} = \frac{y - y_1}{\sin\theta} = r,
\]

the above equation can be written as

\[
\frac{x - 4}{\frac{1}{\sqrt{2}}} = \frac{y - 7}{\frac{1}{\sqrt{2}}} = \pm 5\sqrt{2} \quad (\text{for either side of } (4, 7) \text{ at a distance } r = \pm 5\sqrt{2})
\]

That is \(x - 4 = y - 7 = \pm 5\).

The points on the lines at a distance \(5\sqrt{2}\) units either side of \((4, 7)\) are \((4 + 5, 7 + 5)\) and \((4 - 5, 7 - 5)\).

The points on the lines are \((9, 12)\) and \((-1, 2)\) and the given slope is \(m = \tan 60^\circ = \sqrt{3}\).

Therefore the required equations, using slope and a point form, we get

\[
\sqrt{3}x - y + (12 - 9\sqrt{3}) = 0 \quad \text{and} \quad \sqrt{3}x - y + (2 + \sqrt{3}) = 0
\]

### 6.3.4 General form to other forms

\(Ax + By + C = 0\), where \(A, B\) and \(C\) being real numbers and \(A\) and \(B\) cannot be simultaneously equal to zero, can be expressed in terms of \(A, B\) and \(C\) of the general form into other forms.

(i) **Slope and intercept form:** \((B \neq 0)\): The given equation can be written as

\[
y = -\frac{A}{B}x - \frac{C}{B} \quad \Rightarrow \quad \text{slope} = -\frac{A}{B} \quad \text{and} \quad y\text{-intercept} = -\frac{C}{B}
\]

(ii) **Intercepts form:** The given equation can be written as

\[
-\frac{A}{C}x - \frac{B}{C}y = 1 \quad \text{or} \quad \frac{x}{-C/A} + \frac{y}{-C/B} = 1
\]

Comparing with intercept form, we get

\[
x\text{-intercept}(a) = -\frac{C}{A} \quad \text{and} \quad y\text{-intercept}(b) = -\frac{C}{B}
\]

(iii) **Normal form:** Here \(A\) and \(B\) are not equal to zero,

Comparing \(Ax + By + C = 0\), with \(x\cos\alpha + y\sin\alpha = p\)

We get
\[
\frac{-A}{\sqrt{A^2 + B^2}}x + \frac{-B}{\sqrt{A^2 + B^2}}y = \frac{|C|}{\sqrt{A^2 + B^2}}
\]
Here \(\cos\alpha = \frac{-A}{\sqrt{A^2 + B^2}}\), \(\sin\alpha = \frac{-B}{\sqrt{A^2 + B^2}}\) and \(p = \frac{|C|}{\sqrt{A^2 + B^2}}\)

### Example 6.19

Express the equation \(\sqrt{3}x - y + 4 = 0\) in the following equivalent form:

(i) Slope and Intercept form

(ii) Intercept form

(iii) Normal form

**Solution:**

(i) **Slope and intercept form:** It is given that

\[
\sqrt{3}x - y + 4 = 0 \Rightarrow y = \sqrt{3}x + 4 \tag{6.15}
\]

Comparing the above equation with the equation \(y = mx + b\), we have

\[
\text{Slope} = \sqrt{3} \quad \text{and} \quad y\text{-intercept} = 4
\]

(ii) **Intercept form:**

\[
\sqrt{3}x - y + 4 = 0 \Rightarrow \sqrt{3}x - y = -4
\]
\[
\frac{-\sqrt{3}}{4}x + \frac{y}{4} = 1
\]
That is,
\[
\frac{x}{\left(-\frac{4}{\sqrt{3}}\right)} + \frac{y}{4} = 1
\]

Comparing the above equation with the equation \(\frac{x}{a} + \frac{y}{b} = 1\)

We get, \(x\)-intercept = \(-\frac{4}{\sqrt{3}}\) and \(y\)-intercept = \(4\).

(iii) **Normal form:**

\[
\sqrt{3}x - y + 4 = 0 \Rightarrow (-\sqrt{3})x + y = 4 \tag{6.17}
\]

Comparing the above equation with the equation \(Ax + By + C = 0\).

Here \(A = -\sqrt{3}\), and \(B = 1\), \(\sqrt{A^2 + B^2} = 2\)

Therefore, dividing the above equation by 2, we get

\[
\frac{-\sqrt{3}x}{2} + \frac{y}{2} = 2 \tag{6.18}
\]

Comparing the above equation with the equation \(x\cos\alpha + y\sin\alpha = p\)

If we take
\[
\cos\alpha = \frac{-\sqrt{3}}{2}, \quad \sin\alpha = \frac{1}{2} \quad \text{and} \quad p = 2
\]
\[
\Rightarrow \alpha = 150^\circ = \frac{5\pi}{6} \quad \text{and length of the normal } (p) = 2
\]

The normal form is \(x\cos\frac{5\pi}{6} + y\sin\frac{5\pi}{6} = 2\).

To express the given equation to the required form, sometimes, it is more convenient to use property the proportionality of the coefficients of like terms.

### Example 6.20

Rewrite \(\sqrt{3}x + y + 4 = 0\) into normal form.

**Solution:**

The required form \(x\cos\alpha + y\sin\alpha = p\)

Given form \(-\sqrt{3}x - y = 4\) (\(\because p\) is always positive)

Since both represent the same equation, the coefficients are proportional. We get,

\[
\frac{\cos\alpha}{-\sqrt{3}} = \frac{\sin\alpha}{-1} = \frac{p}{4}
\]
\[
\frac{\cos\alpha}{-\sqrt{3}} = \frac{\sin\alpha}{-1} = \frac{p}{4} = \frac{\sqrt{\cos^2\alpha + \sin^2\alpha}}{\sqrt{(-\sqrt{3})^2 + (-1)^2}} = \frac{1}{2}
\]
(When a term is squared, it should be square rooted.)

\[
\cos\alpha = \frac{-\sqrt{3}}{2}, \quad \sin\alpha = \frac{-1}{2} \quad \text{and} \quad p = \frac{4}{2}
\]
\[
\alpha = 210^\circ = \frac{7\pi}{6} \quad \text{and} \quad p = 2
\]

Normal form of the equation is

\[
x\cos\frac{7\pi}{6} + y\sin\frac{7\pi}{6} = 2
\]

Finding the shortest path between two points on a curved surface can often be difficult. However, the length of a path on the surface of a cylinder is not changed if the curved surface is flattened. For the following problem, by unrolling the hollow cylinder and flattening it into a rectangle, a single reflection allows us to determine the ant's path.

### Example 6.21

Consider a hollow cylindrical vessel, with circumference \(24 \text{ cm}\) and height \(10 \text{ cm}\). An ant is located on the outside of vessel \(4 \text{ cm}\) from the bottom. There is a drop of honey at the diagrammatically opposite inside of the vessel, \(3 \text{ cm}\) from the top.

(i) What is the shortest distance the ant would need to crawl to get the honey drop?

(ii) Equation of the path traced out by the ant.

(iii) Where the ant enter in to the cylinder? Here is a picture that illustrates the position of the ant and the honey.

**Figure 6.31**

**Solution:**

By unrolling the hollow cylinder and flattening it into a rectangle, and with a single reflection allows us to determine the ant's path, as shown the figure. Let the base line \(x\)-axis in cm and the vertical line through \(A\) (initial position of the ant) be the \(y\)-axis. Let \(H\) be the position of honey drop and \(E\) be the entry point of ant inside the vessel. From the given information we have Let \(A(x_1, y_1)\) and \(H(x_2, y_2)\) be (0, 4) and (12, 13) respectively.

**Figure 6.32**

(i) The shortest distance between \(A\) and \(H\) is

\[
\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} = \sqrt{12^2 + 9^2} = 15
\]

The ant would need to crawl \(15 \text{ cm}\) to get the honey.

(ii) The equation of the path \(AH\) is

\[
\frac{y - 4}{13 - 4} = \frac{x - 0}{12 - 0} \Rightarrow y = 0.75x + 4 \tag{6.19}
\]

(iii) At the entry point \(E\), \(y = 10 \Rightarrow x = 8\)

\[
E = (8, 10)
\]

Taking the origin at different location, different form of equation can be obtained, but the path and distance are the same as above.

## Exercise 6.2

1. Find the equation of the lines passing through the point (1, 1)

   (i) with \(y\)-intercept \((-4)\)

   (ii) with slope 3

   (iii) and \((-2, 3)\)

   (iv) and the perpendicular from the origin makes an angle \(60^\circ\) with \(x\)-axis.

2. If \(P(r, c)\) is mid point of a line segment between the axes, then show that \(\frac{x}{r} + \frac{y}{c} = 2\).

3. Find the equation of the line passing through the point \((1, 5)\) and also divides the co-ordinate axes in the ratio 3:10.

4. If \(p\) is length of perpendicular from origin to the line whose intercepts on the axes are \(a\) and \(b\), then show that \(\frac{1}{p^2} = \frac{1}{a^2} + \frac{1}{b^2}\).

5. The normal boiling point of water is \(100^\circ C\) or \(212^\circ F\) and the freezing point of water is \(0^\circ C\) or \(32^\circ F\).

   (i) Find the linear relationship between \(C\) and \(F\).

   (ii) Find the value of \(C\) for \(98.6^\circ F\) and

   (iii) the value of \(F\) for \(38^\circ C\).

6. An object was launched from a place \(P\) in constant speed to hit a target. At the 15th second it was \(1400 \text{ m}\) away from the target and at the 18th second \(800 \text{ m}\) away. Find

   (i) the distance between the place and the target

   (ii) the distance covered by it in 15 seconds.

   (iii) time taken to hit the target.

7. Population of a city in the years 2005 and 2010 are 1,35,000 and 1,45,000 respectively. Find the approximate population in the year 2015. (assuming that the growth of population is constant)

8. Find the equation of the line, if the perpendicular drawn from the origin makes an angle \(30^\circ\) with \(x\)-axis and its length is 12.

9. Find the equation of the straight lines passing through (8, 3) and having intercepts whose sum is 1.

10. Show that the points (1, 3), (2, 1) and \(\left(\frac{1}{2}, 4\right)\) are collinear, by using (i) concept of slope (ii) using a straight line and (iii) any other method.

11. A straight line is passing through the point \(A(1, 2)\) with slope \(\frac{5}{12}\). Find points on the line which are 13 units away from \(A\).

12. A \(150 \text{ m}\) long train is moving with constant velocity of \(12.5 \text{ m/s}\). Find

    (i) the equation of the motion of the train,

    (ii) time taken to cross a pole.

    (iii) The time taken to cross the bridge of length \(850 \text{ m}\) is?

13. A spring was hung from a hook in the ceiling. A number of different weights were attached to the spring to make it stretch, and the total length of the spring was measured each time is shown in the following table.

    | Weight (kg) | 2 | 4 | 5 | 8 |
    |-------------|---|---|---|---|
    | Length (cm) | 3 | 4 | 4.5 | 6 |

    (i) Draw a graph showing the results.

    (ii) Find the equation relating the length of the spring to the weight on it.

    (iii) What is the actual length of the spring.

    (iv) If the spring has to stretch to \(9 \text{ cm}\) long, how much weight should be added?

    (v) How long will the spring be when 6 kilograms of weight on it?

14. A family is using Liquefied petroleum gas (LPG) of weight \(14.2 \text{ kg}\) for consumption. (Full weight \(29.5 \text{ kg}\) includes the empty cylinders tare weight of \(15.3 \text{ kg}\).) If it is used with constant rate then it lasts for 24 days. Then the new cylinder is replaced.

    (i) Find the equation relating the quantity of gas in the cylinder to the days.

    (ii) Draw the graph for first 96 days.

15. In a shopping mall there is a hall of cuboid shape with dimension \(800 \times 800 \times 720\) units, which needs to be added the facility of an escalator in the path as shown by the dotted line in the figure. Find

    (i) the minimum total length of the escalator.

    (ii) the heights at which the escalator changes its direction.

    (iii) the slopes of the escalator at the turning points.

**Figure 6.33**

## 6.4 Angle between two straight lines

Two straight lines in a plane would either be parallel or coincide or intersect. Normally when two straight lines intersect, they form two angles at the point of intersection. One is an acute angle and another is an obtuse angle or equal. Both these angles would be supplements (Sum equals \(180^\circ\)) of each other. By definition, when we say 'angle between two straight lines' we mean the acute angle between the two lines.

Let \(y = m_1x + c_1\) and \(y = m_2x + c_2\) be the equations of two straight lines and let these two lines make angles \(\theta_1\) and \(\theta_2\) with \(x\)-axis.

Then \(m_1 = \tan\theta_1\) and \(m_2 = \tan\theta_2\).

If \(\phi\) is the angle between these two straight lines, then

\[
\phi = \theta_2 - \theta_1 \Rightarrow \tan\phi = \tan(\theta_2 - \theta_1)
\]
\[
\Rightarrow \tan\phi = \frac{m_2 - m_1}{1 + m_1m_2}
\]
\[
\Rightarrow \phi = \tan^{-1}\frac{m_2 - m_1}{1 + m_1m_2}
\]

**Figure 6.34**

If \(\frac{m_2 - m_1}{1 + m_1m_2}\) is positive then \(\phi\) is the acute angle and if it is negative \(\phi\) is the obtuse angle between the two lines. Therefore, the acute angle \(\phi\) is

\[
\tan^{-1}\left|\frac{m_2 - m_1}{1 + m_1m_2}\right|
\]

### 6.4.1 Condition for Parallel Lines

Lines in the same plane that do not intersect are called parallel lines. Let \(y = m_1x + c_1\) and \(y = m_2x + c_2\) be the equations of two straight lines. If these two lines are parallel, then the angle between lines is zero or \(\pi\). If \(\phi\) is the angle between the lines then, \(\phi = 0 \Rightarrow \tan\phi = 0\)

\[
\Rightarrow \frac{m_2 - m_1}{1 + m_1m_2} = 0 \Rightarrow m_2 - m_1 = 0 \Rightarrow m_2 = m_1
\]

That is parallel lines have the same slope. If two nonvertical lines have the same slope, then they are parallel. All vertical lines are parallel.

If the equation of the two lines are in general form as \(a_1x + b_1y + c_1 = 0\) and \(a_2x + b_2y + c_2 = 0\) then the condition for lines to be parallel is

\[
\frac{a_1}{a_2} = \frac{b_1}{b_2} \quad \text{or} \quad a_1b_2 = a_2b_1
\]

(i) The lines parallel to \(ax + by + c = 0\) are of the form \(ax + by = k\).

(ii) The line parallel to \(ax + by + c = 0\) and passing through a point \((x_1, y_1)\), then its equation is \(ax + by = ax_1 + by_1\).

**Figure 6.35**

### 6.4.2 Condition for Perpendicular Lines

If the lines \(y = m_1x + c_1\) and \(y = m_2x + c_2\) are perpendicular, then the angle between lines is \(\frac{\pi}{2}\).

If \(\phi\) is the angle between the lines then

\[
\tan\frac{\pi}{2} = \infty \Rightarrow 1 + m_1m_2 = 0 \Rightarrow m_1m_2 = -1
\]

**Figure 6.36**

If the equation of the two lines are in general form as \(a_1x + b_1y + c_1 = 0\) and \(a_2x + b_2y + c_2 = 0\), then the condition for lines to be perpendicular is

\[
a_1a_2 + b_1b_2 = 0
\]

(i) The perpendicular line to \(ax + by + c = 0\) are of the form \(bx - ay = k\).

(ii) The perpendicular line to \(ax + by + c = 0\) and passes through the point \((x_1, y_1)\), then the required equation is \(bx - ay = bx_1 - ay_1\).

| Form of lines | Condition for parallel | Condition for perpendicular |
|---------------|------------------------|-----------------------------|
| \(y = m_1x + c_1\) and \(y = m_2x + c_2\) | \(m_2 = m_1\) | \(m_1m_2 = -1\) |
| \(a_1x + b_1y + c_1 = 0\) and \(a_2x + b_2y + c_2 = 0\) | \(a_1b_2 = a_2b_1\) | \(a_1a_2 + b_1b_2 = 0\) |

### 6.4.3 Position of a point with respect to a straight line

Any line \(ax + by + c = 0\) (\(c \neq 0\)), divides the whole plane into two parts:

(i) one containing the origin called origin side of the line and

(ii) the other not containing the origin called non-origin side of the line.

A point \(P(x_1, y_1)\) is on the origin side or non-origin side of the line \(ax + by + c = 0\) (\(c \neq 0\)) according as \(ax_1 + by_1 + c\) and \(c\) are of the same sign or opposite sign. If \(c > 0\), then \(P(x_1, y_1)\) is on the origin side or non-origin side of the line \(ax + by + c = 0\) according as \(ax_1 + by_1 + c\) is positive or negative.

After rewriting the equations \(a_1x + b_1y + c_1 = 0\) and \(a_2x + b_2y + c_2 = 0\), such that both \(c_1 > 0\) and \(c_2 > 0\), and if

(i) \(a_1a_2 + b_1b_2 < 0\), then the angle between them is acute

(ii) \(a_1a_2 + b_1b_2 > 0\), then the angle between them is obtuse.

### 6.4.4 Distance Formulas

Let us develop formulas to find the distance between

(i) two points

(ii) a point to a line

(iii) two parallel lines

(i) The distance between two points \((x_1, y_1)\) and \((x_2, y_2)\) is given by the formula

\[
D = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
\]

The above formula was already proved in lower class.

(ii) The distance from a point \(P(x_1, y_1)\) to a line \(ax + by + c = 0\) is

\[
\left|\frac{ax_1 + by_1 + c}{\sqrt{a^2 + b^2}}\right|
\]

**Proof.** Let \(AB\) be the given line,

\[
ax + by + c = 0 \tag{6.20}
\]

\(P(x_1, y_1)\) be the given point.

Draw a line \(CD\) parallel to \(AB\) through \(P\) and drop a perpendicular from \(P(x_1, y_1)\) to \(AB\) to meet at \(M\). Also drop a perpendicular from the origin to the line \(AB\) to meet at \(R\) and meeting \(CD\) at \(Q\).

Let \(\angle AOR = \alpha\)

Therefore the normal form of the line \(AB\) is

\[
x\cos\alpha + y\sin\alpha = p \tag{6.21}
\]

**Figure 6.37**

Since the equations (6.20) and (6.21) represent the same equations the coefficients of like terms are proportional.

\[
\frac{\cos\alpha}{a} = \frac{\sin\alpha}{b} = \frac{p}{-c} \Rightarrow \frac{\cos\alpha}{a} = \frac{\sin\alpha}{b} = \frac{p}{-c} = \frac{\sqrt{\cos^2\alpha + \sin^2\alpha}}{\pm\sqrt{a^2 + b^2}}
\]

\[
\cos\alpha = \frac{\pm a}{\sqrt{a^2 + b^2}}, \quad \sin\alpha = \frac{\pm b}{\sqrt{a^2 + b^2}} \quad \text{and} \quad p = \frac{\mp c}{\sqrt{a^2 + b^2}}
\]

Normal equation of \(CD\) is

\[
x\cos\alpha + y\sin\alpha = p' \tag{6.22}
\]

Since it passes through \(P(x_1, y_1)\), (6.22) \(\Rightarrow p' = x_1\cos\alpha + y_1\sin\alpha\)

Required distance \(= |PM| = |QR| = |OQ - OR| = |p' - p|\)

\[
= |(x_1\cos\alpha + y_1\sin\alpha) - p|
\]
\[
= \left| \frac{\pm ax_1}{\sqrt{a^2 + b^2}} + \frac{\pm by_1}{\sqrt{a^2 + b^2}} \pm \frac{c}{\sqrt{a^2 + b^2}} \right| = \left| \frac{\pm(ax_1 + by_1 + c)}{\sqrt{a^2 + b^2}} \right|
\]

Required distance \(= \left| \frac{ax_1 + by_1 + c}{\sqrt{a^2 + b^2}} \right|\)

(iii) The distance between two parallel lines \(a_1x + b_1y + c_1 = 0\) and \(a_1x + b_1y + c_2 = 0\) is

\[
D = \frac{|c_2 - c_1|}{\sqrt{a_1^2 + b_1^2}}
\]

(It can be proved using above result by taking point \((x_1, y_1)\) as the origin)

- The coordinates of the nearest point \(Q\) (foot of the perpendicular) on the line \(ax + by + c = 0\) from the point \(P(x_1, y_1)\) can be found from

\[
\frac{x - x_1}{a} = \frac{y - y_1}{b} = -\frac{ax_1 + by_1 + c}{a^2 + b^2} \tag{6.23}
\]

(using parametric form)

- The coordinates of the image of the point \(\bar{P}(x_1, y_1)\) with respect to the line \(ax + by + c = 0\) are given by

\[
\frac{x - x_1}{a} = \frac{y - y_1}{b} = -\frac{2(ax_1 + by_1 + c)}{a^2 + b^2} \tag{6.24}
\]

**Figure 6.38**

### Example 6.22

Find the equations of a parallel line and a perpendicular line passing through the point \((1, 2)\) to the line \(3x + 4y = 7\).

**Solution:**

Parallel line to \(3x + 4y = 7\) is of the form \(3x + 4y = 3x_1 + 4y_1\). Let \((x_1, y_1)\) be \((1, 2)\)

\[
\Rightarrow 3x + 4y = 3(1) + 4(2) \Rightarrow 3x + 4y = 11
\]

Perpendicular line to \(3x + 4y = 7\) is of the form

\[
4x - 3y = 4x_1 - 3y_1
\]

Here \((x_1, y_1) = (1, 2)\)

\[
\Rightarrow 4x - 3y = 4(1) - 3(2) \Rightarrow 4x - 3y = -2
\]

### Example 6.23

Find the distance

(i) between two points (5, 4) and (2, 0)

(ii) from a point (1, 2) to the line \(5x + 12y - 3 = 0\)

(iii) between two parallel lines \(3x + 4y = 12\) and \(6x + 8y + 1 = 0\)

**Solution:**

(i) Distance between two points \((x_1, y_1) = (5, 4)\) and \((x_2, y_2) = (2, 0)\) is

\[
D = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} = \sqrt{3^2 + 4^2} = 5 \text{ Units}
\]

(ii) Distance between the point \((x_1, y_1)\) and the line \(ax + by + c = 0\) is

\[
D = \left|\frac{ax_1 + by_1 + c}{\sqrt{a^2 + b^2}}\right|
\]

The distance between the point (1, 2) and the line \(5x + 12y - 3 = 0\) is

\[
D = \left|\frac{5(1) + 12(2) - 3}{\sqrt{5^2 + 12^2}}\right| = \left|\frac{5 + 24 - 3}{\sqrt{25 + 144}}\right| = \left|\frac{26}{13}\right| = 2
\]

(iii) Distance between two parallel lines \(a_1x + b_1y + c_1 = 0\) and \(a_1x + b_1y + c_2 = 0\) is

\[
D = \frac{|c_2 - c_1|}{\sqrt{a_1^2 + b_1^2}}
\]

Given lines can be written as \(3x + 4y - 12 = 0\) and \(3x + 4y + \frac{1}{2} = 0\)

Here \(a_1 = 3, b_1 = 4, c_1 = -12, c_2 = \frac{1}{2}\)

\[
D = \frac{\left|\frac{1}{2} - (-12)\right|}{\sqrt{3^2 + 4^2}} = \frac{\left|\frac{1}{2} + 12\right|}{5} = \frac{\left|\frac{25}{2}\right|}{5} = \frac{25}{10} = 2.5 \text{ units}
\]

### Example 6.24

Find the nearest point on the line \(2x + y = 5\) from the origin.

**Solution:**

The required point is the foot of the perpendicular from the origin on the line \(2x + y = 5\).

The line perpendicular to the given line, through the origin is \(x - 2y = 0\).

Solving the equations \(2x + y = 5\) and \(x - 2y = 0\), we get \(x = 2, y = 1\).

Hence the nearest point on the line from the origin is \((2, 1)\).

Using the formula (6.23)

\[
\frac{x - x_1}{a} = \frac{y - y_1}{b} = -\frac{ax_1 + by_1 + c}{a^2 + b^2}
\]
\[
\frac{x - 0}{2} = \frac{y - 0}{1} = -\frac{2(0) + 1(0) - 5}{2^2 + 1^2}
\]
\[
\Rightarrow \frac{x}{2} = \frac{y}{1} = 1 \Rightarrow (2, 1)
\]

### Example 6.25

Find the equation of the bisector of the acute angle between the lines \(3x + 4y + 2 = 0\) and \(5x + 12y - 5 = 0\).

**Solution:**

First, let us make the constant term positives in both the equations. The angle bisectors of the given equations are

\[
\frac{3x + 4y + 2}{\sqrt{3^2 + 4^2}} = \pm \frac{-5x - 12y + 5}{\sqrt{5^2 + 12^2}}
\]
(moving point is equidistance from the lines)

Since \(a_1a_2 + b_1b_2 = -15 - 48 < 0\), the equation of bisector of the acute angle between the lines is

\[
\frac{3x + 4y + 2}{5} = +\frac{-5x - 12y + 5}{13} \Rightarrow 64x + 112y + 1 = 0
\]

### Example 6.26

Find the points on the line \(x + y = 5\), that lie at a distance 2 units from the line \(4x + 3y - 12 = 0\).

**Solution:**

Any point on the line \(x + y = 5\) is \(x = t, y = 5 - t\). The distance from \((t, 5 - t)\) to the line \(4x + 3y - 12 = 0\) is given by 2 units.

\[
\therefore \frac{|4(t) + 3(5 - t) - 12|}{\sqrt{4^2 + 3^2}} = 2
\]
\[
\Rightarrow \frac{|t + 3|}{5} = 2
\]
\[
\Rightarrow t + 3 = \pm 10 \Rightarrow t = -13, t = 7
\]

The points are \((-13, 18)\) and \((7, -2)\).

### Example 6.27

A straight line passes through a fixed point (6, 8). Find the locus of the foot of the perpendicular drawn to it from the origin \(O\).

**Solution:**

Let the point \((x_1, y_1)\) be (6, 8) and \(P(h, k)\) be a point on the required locus.

Family of equations of the straight lines passing through the fixed point \((x_1, y_1)\) is

\[
y - y_1 = m(x - x_1) \Rightarrow y - 8 = m(x - 6) \tag{6.25}
\]

### 6.4.5 Family of lines

All lines follow a specific condition are called a family of lines. The following example shows some families of straight lines (where \(m, h\), and \(k\) are arbitrary constants).

**Figure 6.39**

It may seem that the equation of a straight line \(ax + by + c = 0\) contains three arbitrary constants. In fact, it is not so. On dividing it by \(b\) (or \(a\), whichever is non-zero), we get

\[
\frac{a}{b}x + y + \frac{c}{b} = 0,
\]

which can be written as \(Ax + y + C = 0\) where \(A = \frac{a}{b}\) and \(C = \frac{c}{b}\).

The above equation can be written as slope and intercept form.

It follows that the equation of a straight line contains two arbitrary constants, and the number of these arbitrary constants cannot be decreased further. Thus, the equation of every straight line contains two arbitrary constants; consequently, two conditions are needed to determine the equation of a straight line uniquely.

One condition yields a linear relation among two arbitrary constants and hence each arbitrary constant determines the other. Therefore, the lines which satisfy one condition contain a single arbitrary constant. Such a system of lines is called one parameter family of lines and the unknown arbitrary constant is called the parameter.

Let us now discuss the three types of families of straight lines, using \(y = mx + b\). First two types are one parameter families and third one is two parameters families.

(i) when \(m\) is arbitrary and \(b\) is a fixed constant.

(ii) when \(b\) is arbitrary and \(m\) is a fixed constant.

(iii) when both \(m\) and \(b\) are arbitrary.

### 6.4.6 One parameter families

**(i) when \(m\) is arbitrary and \(b\) is a fixed constant**

**Figure 6.40**

Let us find the family of equations of straight lines for the line \(y = mx + b\) by considering \(m\) is arbitrary constant and \(b\) is a fixed constant say \(b = 5\). Therefore the equation, for different real values of \(m\), represents a family of lines with \(y\)-intercept 5 units. A few members of this family are shown in figure. For example, in this diagram the slope \(m\) takes \(-1, -2, \frac{1}{3}, 1\) and 4.

### Example 6.28

Find the equations of the straight lines in the family of the lines \(y = mx + 2\), for which \(m\) and the \(x\)-coordinate of the point of intersection of the lines with \(2x + 3y = 10\) are integers.

**Solution:**

To find the equations of straight lines for the family of line \(y = mx + 2\), we have to determine the values of the parameter \(m\).

The point of intersection of the lines \(y = mx + 2\) and \(2x + 3y = 10\) is

\[
\left(\frac{4}{3m + 2}, \frac{10m + 4}{3m + 2}\right)
\]

It is given that the slope \(m\) and the \(x\)-coordinate are integers.

\[
\therefore \frac{4}{3m + 2} \text{ is an integer} \Rightarrow 3m + 2 \text{ is a divisor of } 4 (\pm 1, \pm 2 \text{ and } \pm 4)
\]
\[
\therefore 3m + 2 = \pm 1, \quad 3m + 2 = \pm 2, \quad 3m + 2 = \pm 4, \quad \text{where } m \text{ is an integer}
\]

Solving we get, \(m = \{-2, -1, 0\}\).

The equations are, \(y = -2x + 2\), \(y = -x + 2\) and \(y = 2\).

**(ii) when \(b\) is arbitrary and \(m\) is a fixed constant**

As discussed above, suppose \(b\) is arbitrary constant and \(m\) is a fixed constant say \(m = -2\), the equation \(y = mx + b\) becomes \(y = -2x + b\). For different real values of \(b\), a family of lines can be obtained with slope \(-2\). A few members of this family are shown in the figure. For example, in this diagram \(b\) can take values \(-3, -1, 0, 1, 2, 3\) and 4.

**Figure 6.41**

Two special cases family of parallel lines and family of perpendicular lines are given below.

**Family of parallel lines:** Family of parallel lines to \(ax + by + c = 0\) is of the form \(ax + by + \lambda = 0\). For different values of \(\lambda\) (call it lambda), we get different lines parallel to \(ax + by + c = 0\).

**Family of perpendicular lines:** Family of perpendicular lines to \(ax + by + c = 0\) is of the form \(bx - ay + \lambda = 0\). For different values of \(\lambda\), we get different lines perpendicular to \(ax + by + c = 0\).

### 6.4.7 Two parameters families

**(iii) when both \(m\) and \(b\) are arbitrary**

Suppose both \(m\) and \(b\) are arbitrary constants in \(y = mx + b\) we cannot visualize the family easily in graph. But some cases like \(y - y_1 = m(x - x_1)\) for different real values of \(m\), a family of lines can be visualized. Suppose the slope \(m\) takes \(-2, -4, \frac{1}{3}, 1\) and 3, lines which pass through the fixed point \((x_1, y_1)\) except the vertical line \(x = x_1\) as shown in the diagram.

**Figure 6.42**

### 6.4.8 The family of equation of straight lines through the point of intersection of the two given lines

Let \(L_1 \equiv a_1x + b_1y + c_1 = 0\) and \(L_2 \equiv a_2x + b_2y + c_2 = 0\), be the equation of two given lines. The family of equations of straight lines through the point of intersection of the above lines is \(L_1 + \lambda L_2 = 0\) where \(\lambda\) is a parameter. That is, for different real values of \(\lambda\) we get different equations.

**Figure 6.43**

### Example 6.29

Find the equation of the line through the intersection of the lines \(3x + 2y + 5 = 0\) and \(3x - 4y + 6 = 0\) and the point \((1, 1)\).

**Solution:**

The family of equations of straight lines through the point of intersection of the lines is of the form

\[
(a_1x + b_1y + c_1) + \lambda(a_2x + b_2y + c_2) = 0
\]

That is, \((3x + 2y + 5) + \lambda(3x - 4y + 6) = 0\)

Since the required equation passes through the point \((1, 1)\), the point satisfies the above equation. Therefore

\[
\{3 + 2(1) + 5\} + \lambda\{3(1) - 4(1) + 6\} = 0 \Rightarrow \lambda = -2
\]

Substituting \(\lambda = -2\) in the above equation we get the required equation as \(3x - 10y + 7 = 0\).

(Verify the above problem by using two points form.)

### Example 6.30

Suppose the Government has decided to erect a new Electrical Power Transmission Substation to provide better power supply to two villages namely \(A\) and \(B\). The substation has to be on the line \(l\). The distances of villages \(A\) and \(B\) from the foot of the perpendiculars \(P\) and \(Q\) on the line \(l\) are \(3 \text{ km}\) and \(5 \text{ km}\) respectively and the distance between \(P\) and \(Q\) is \(6 \text{ km}\).

(i) What is the smallest length of cable required to connect the two villages.

(ii) Find the equations of the cable lines that connect the power station to two villages.

(Using the knowledge in conjunction with the principle of reflection allows for approach to solve this problem.)

**Figure 6.44**

**Solution:**

Take conveniently \(PQ\) as \(x\)-axis, \(PA\) as \(y\)-axis and \(P\) is the origin (instead of conventional origin \(O\)). Therefore, the coordinates are \(P(0, 0)\), \(A(0, 3)\) and \(B(6, 5)\).

If the image of \(A\) about the \(x\)-axis is \(\bar{A}\), then \(\bar{A}\) is \((0, -3)\).

The required \(R\) is the point of intersection of the line \(\bar{A}B\) and \(x\)-axis.

\(AR\) and \(BR\) are the path of the cable (road).

The shortest length of the cable is \(AR + BR = BR + R\bar{A} = B\bar{A} = \sqrt{(6 - 0)^2 + (5 + 3)^2} = 10 \text{ km}\).

Equation of the line \(\bar{A}B\) is

\[
y - (-3) = \frac{5 - (-3)}{6 - 0}(x - 0) \Rightarrow 4x - 3y = 9
\]

**Figure 6.45**

When \(y = 0\), \(R\) is \(\left(\frac{9}{4}, 0\right)\).

That is the substation should be located at a distance of \(2.25 \text{ km}\) from \(P\).

The equation of \(AR\) is \(4x + 3y = 9\).

The equations of the cable lines (roads) of \(RA\) and \(RB\) are

\[
4x - 3y = 9 \quad \text{and} \quad 4x + 3y = 9.
\]

### Example 6.31

A car rental firm has charges ₹25 with 1.8 free kilometers, and ₹12 for every additional kilometer. Find the equation relating the cost \(y\) to the number of kilometers \(x\). Also find the cost to travel 15 kilometers.

**Solution:**

Given that up to 1.8 kilometers the fixed rent is ₹25.

The corresponding equation is

\[
y = 25, \quad 0 \leq x \leq 1.8 \tag{6.26}
\]

Also ₹12 for every additional kilometer after 1.8 kilometers.

**Figure 6.46**

The corresponding equation is

\[
y = 25 + 12(x - 1.8), \quad x > 1.8 \tag{6.27}
\]

The combined equation of (6.26) and (6.27), we get

\[
y = \begin{cases}
25, & 0 \leq x \leq 1.8 \\
25 + 12(x - 1.8), & x > 1.8
\end{cases} \tag{6.28}
\]

When \(x = 15\), from (6.27), we get cost to travel 15 kilometers is ₹183.40.

### Example 6.32

If a line joining two points (3, 0) and (5, 2) is rotated about the point (3, 0) in counter clockwise direction through an angle \(15^\circ\), then find the equation of the line in the new position.

**Solution:**

Let \(P(3, 0)\) and \(Q(5, 2)\) be the given points.

Slope of \(PQ = \frac{y_2 - y_1}{x_2 - x_1} = 1 \Rightarrow\) the angle of inclination of the line \(PQ = \tan^{-1}(1) = \frac{\pi}{4} = 45^\circ\).

The slope of the line in new position is

\[
m = \tan(45^\circ + 15^\circ) \Rightarrow \text{Slope} = \tan 60^\circ = \sqrt{3}
\]

Equation of the straight line passing through (3, 0) and with the slope \(\sqrt{3}\) is

**Figure 6.47**

\[
y - 0 = \sqrt{3}(x - 3) \Rightarrow \sqrt{3}x - y - 3\sqrt{3} = 0
\]

## Exercise 6.3

1. Show that the lines \(3x + 2y + 9 = 0\) and \(12x + 8y - 15 = 0\) are parallel lines.

2. Find the equation of the straight line parallel to \(5x - 4y + 3 = 0\) and having \(x\)-intercept 3.

3. Find the distance between the line \(4x + 3y + 4 = 0\), and a point (i) \((-2, 4)\) (ii) \((7, -3)\).

4. Write the equation of the lines through the point \((1, -1)\)

   (i) parallel to \(x + 3y - 4 = 0\)

   (ii) perpendicular to \(3x + 4y = 6\).

5. If \((-4, 7)\) is one vertex of a rhombus and if the equation of one diagonal is \(5x - y + 7 = 0\), then find the equation of another diagonal.

6. Find the equation of the lines passing through the point of intersection lines \(4x - y + 3 = 0\) and \(5x + 2y + 7 = 0\), and

   (i) through the point \((-1, 2)\)

   (ii) Parallel to \(x - y + 5 = 0\)

   (iii) Perpendicular to \(x - 2y + 1 = 0\).

7. Find the equations of two straight lines which are parallel to the line \(12x + 5y + 2 = 0\) and at a unit distance from the point \((1, -1)\).

8. Find the equations of straight lines which are perpendicular to the line \(3x + 4y - 6 = 0\) and are at a distance of 4 units from \((2, 1)\).

9. Find the equation of a straight line parallel to \(2x + 3y = 10\) and which is such that the sum of its intercepts on the axes is 15.

10. Find the length of the perpendicular and the co-ordinates of the foot of the perpendicular from \((-10, -2)\) to the line \(x + y - 2 = 0\).

11. If \(p_1\) and \(p_2\) are the lengths of the perpendiculars from the origin to the straight lines \(x\sec\theta + y\csc\theta = 2a\) and \(x\cos\theta - y\sin\theta = a\cos2\theta\), then prove that \(p_1^2 + p_2^2 = a^2\).

12. Find the distance between the parallel lines

    (i) \(12x + 5y = 7\) and \(12x + 5y + 7 = 0\)

    (ii) \(3x - 4y + 5 = 0\) and \(6x - 8y - 15 = 0\).

13. Find the family of straight lines

    (i) Perpendicular

    (ii) Parallel to \(3x + 4y - 12 = 0\).

14. If the line joining two points A(2, 0) and B(3, 1) is rotated about A in anticlockwise direction through an angle of \(15^\circ\), then find the equation of the line in new position.

15. A ray of light coming from the point (1, 2) is reflected at a point A on the \(x\)-axis and it passes through the point (5, 3). Find the co-ordinates of the point A.

16. A line is drawn perpendicular to \(5x = y + 7\). Find the equation of the line if the area of the triangle formed by this line with co-ordinate axes is 10 sq. units.

17. Find the image of the point \((-2, 3)\) about the line \(x + 2y - 9 = 0\).

18. A photocopy store charges ₹1.50 per copy for the first 10 copies and ₹1.00 per copy after the 10th copy. Let \(x\) be the number of copies, and let \(y\) be the total cost of photocopying.

    (i) Draw graph of the cost as \(x\) goes from 0 to 50 copies.

    (ii) Find the cost of making 40 copies.

19. Find at least two equations of the straight lines in the family of the lines \(y = 5x + b\), for which \(b\) and the \(x\)-coordinate of the point of intersection of the lines with \(3x - 4y = 6\) are integers.

20. Find all the equations of the straight lines in the family of the lines \(y = mx - 3\), for which \(m\) and the \(x\)-coordinate of the point of intersection of the lines with \(x - y = 6\) are integers.

## 6.5 Pair of Straight Lines

The equations of two or more lines can be expressed together by an equation of degree higher than one. As we see that a linear equation in \(x\) and \(y\) represents a straight line, the product of two linear equations represent two straight lines, that is a pair of straight lines. Hence we study pair of straight lines as a quadratic equations in \(x\) and \(y\).

Let \(L_1 \equiv a_1x + b_1y + c_1 = 0\) and \(L_2 \equiv a_2x + b_2y + c_2 = 0\), be separate equations of two straight lines. If \(P(x_1, y_1)\) is a point on \(L_1\), then it satisfies the equation \(L_1 = 0\). Similarly, if \(P(x_1, y_1)\) is on \(L_2\) then \(L_2 = 0\). If \(P(x_1, y_1)\) lies either on \(L_1 = 0\) or \(L_2 = 0\), then \(P(x_1, y_1)\) satisfies the equation \((L_1)(L_2) = 0\), and no other point satisfies \(L_1 \cdot L_2 = 0\). Therefore the equation \(L_1 \cdot L_2 = 0\) represents the pair of straight lines \(L_1 = 0\) and \(L_2 = 0\).

For example, consider the two equations

\[
y + \sqrt{3}x = 0 \quad \text{and} \quad y - \sqrt{3}x = 0.
\]

The above two equations represent the equation of two straight lines passing through the origin with slopes \(-\sqrt{3}\) and \(\sqrt{3}\) respectively.

Combining the above equation, we get

\[
(y + \sqrt{3}x)(y - \sqrt{3}x) = 0 \Rightarrow y^2 - 3x^2 = 0,
\]

represents the pair of straight lines.

**Figure 6.48**

### 6.5.1 Pair of Lines Passing through the Origin

We first consider a simple case. Both the lines in this pair pass through the origin. Thus, their equations can be written as

\[
y - m_1x = 0, \quad y - m_2x = 0
\]

Combined equation of these two lines is

\[
(y - m_1x)(y - m_2x) = 0 \Rightarrow y^2 - (m_1 + m_2)xy + m_1m_2x^2 = 0 \tag{6.29}
\]

**Figure 6.49**

The above equation suggests that the general equation of a pair of straight lines passing through the origin with slopes \(m_1\) and \(m_2\), \(ax^2 + 2hxy + by^2 = 0\) is a homogeneous equation of degree two, implying that the degree of each term is 2.

Nature of the homogeneous equations tells us whether the lines pass through the origin.

### Example 6.33

Separate the equations \(5x^2 + 6xy + y^2 = 0\).

**Solution:**

We factorize this equation straight away as

\[
5x^2 + 6xy + y^2 = 0
\]
\[
5x^2 + 5xy + xy + y^2 = 0
\]
\[
5x(x + y) + y(x + y) = 0
\]
\[
(5x + y)(x + y) = 0
\]

So that the lines are \(5x + y = 0\) and \(x + y = 0\).

**Alternate method:** since the given equation is a homogeneous equation, divide the given equation

\[
5x^2 + 6xy + y^2 = 0 \text{ by } x^2
\]
\[
\text{We get } 5 + 6\left(\frac{y}{x}\right) + \left(\frac{y}{x}\right)^2 = 0
\]
\[
\text{Substitute } \frac{y}{x} = m \text{ (slope of the lines for homogeneous equation)}
\]

The above equation becomes \(m^2 + 6m + 5 = 0\)

\[
(m + 5)(m + 1) = 0 \Rightarrow m = -5, m = -1
\]

That is, the lines are \(x + y = 0\) and \(5x + y = 0\).

### Example 6.34

If exists, find the straight lines by separating the equations \(2x^2 + 2xy + y^2 = 0\).

**Solution:**

Since the given equation is a homogeneous equation, divide the given equation \(2x^2 + 2xy + y^2 = 0\) by \(x^2\) and substituting \(\frac{y}{x} = m\)

\[
2 + 2m + m^2 = 0 \Rightarrow m = \frac{-2 \pm \sqrt{4 - 8}}{2} = \frac{-2 \pm \sqrt{-4}}{2}
\]

which is not real. Hence the given equation does not represent a pair of straight lines.

### 6.5.2 Angle between Pair of Straight Lines

Consider the equation of a pair of straight lines passing through the origin as:

\[
ax^2 + 2hxy + by^2 = 0 \tag{6.30}
\]

Let \(m_1\) and \(m_2\) be the slopes of these two lines.

By dividing (6.30) by \(x^2\) and substituting \(\frac{y}{x} = m\)

we get,
\[
b m^2 + 2h m + a = 0
\]

This quadratic in \(m\) will have its roots as \(m_1\) and \(m_2\).

Thus,
\[
m_1 + m_2 = \frac{-2h}{b} \quad \text{and} \quad m_1m_2 = \frac{a}{b}
\]

If the angle between the two lines is \(\theta\), then

\[
\tan\theta = \left|\frac{m_2 - m_1}{1 + m_2m_1}\right|
\]
\[
= \left|\frac{\sqrt{(m_1 + m_2)^2 - 4m_1m_2}}{1 + m_1m_2}\right|
\]
\[
= \left|\frac{\sqrt{\left(-\frac{2h}{b}\right)^2 - 4\frac{a}{b}}}{1 + \frac{a}{b}}\right|
\]
\[
\tan\theta = \left|\frac{2\sqrt{h^2 - ab}}{a + b}\right|
\]

As a consequence of this formula, we can conclude that

1. The lines are real and distinct, if \(m_1\) and \(m_2\) are real and distinct, that is if \(h^2 - ab > 0\).

2. The lines are real and coincident, if \(m_1\) and \(m_2\) are real and equal, that is if \(h^2 - ab = 0\).

3. The lines are not real (imaginary), if \(m_1\) and \(m_2\) are not real, that is if \(h^2 - ab < 0\).

Also, we see that the lines represented by (6.30), are parallel (since both pass through the origin, the lines are coincident lines) if \(\tan\theta = 0\), that is \(h^2 - ab = 0\), and perpendicular if \(\cot\theta = 0\) that is \(a + b = 0\).

| Pair of straight lines | Condition for parallel | Condition for perpendicular |
|------------------------|------------------------|-----------------------------|
| \(ax^2 + 2hxy + by^2 = 0\) | \(h^2 - ab = 0\) | \(a + b = 0\) |

### Example 6.35

Find the equation of the pair of lines through the origin and perpendicular to the pair of lines \(ax^2 + 2hxy + by^2 = 0\).

**Solution:**

Let \(m_1\) and \(m_2\) be the slopes of these two lines.

\[
y - m_1x = 0 \quad \text{and} \quad y - m_2x = 0 \tag{6.31}
\]

Combined equation of these two lines is

\[
(y - m_1x)(y - m_2x) = 0 \Rightarrow y^2 - (m_1 + m_2)xy + m_1m_2x^2 = 0 \tag{6.32}
\]

Given that

\[
ax^2 + 2hxy + by^2 = 0 \tag{6.33}
\]

Thus,
\[
m_1 + m_2 = \frac{-2h}{b} \quad \text{and} \quad m_1m_2 = \frac{a}{b} \tag{6.34}
\]

The lines perpendicular to (6.31) are

\[
y + \frac{1}{m_1}x = 0 \quad \text{and} \quad y + \frac{1}{m_2}x = 0
\]

The combined equation is

\[(m_1y + x)(m_2y + x) = 0
\]
\[
m_1m_2y^2 + (m_1 + m_2)xy + x^2 = 0
\]

By using (6.34)
\[
\frac{a}{b}y^2 - \frac{2h}{b}xy + x^2 = 0
\]

The required equation is
\[
ay^2 - 2hxy + bx^2 = 0 \tag{6.35}
\]

### 6.5.3 Equation of the bisectors of the angle between the lines \(ax^2 + 2hxy + by^2 = 0\)

Let the equations of the two straight lines be \(y - m_1x = 0\) and \(y - m_2x = 0\).

\[
\therefore m_1 + m_2 = -\frac{2h}{b} \quad \text{and} \quad m_1m_2 = \frac{a}{b}
\]

We know that the equation of bisectors is the locus of points from which the perpendicular drawn to the two straight lines are equal.

Let \(P(p, q)\) be any point on the locus of bisectors.

The perpendiculars from \(P(p, q)\) to the line \(y - m_1x = 0\) is equal to the perpendicular from \(P(p, q)\) to \(y - m_2x = 0\).

\[
\pm \frac{q - m_1p}{\sqrt{1 + m_1^2}} = \pm \frac{q - m_2p}{\sqrt{1 + m_2^2}}
\]
That is,
\[
(q - m_1p)^2(1 + m_2^2) = (q - m_2p)^2(1 + m_1^2)
\]

Simplifying we get
\[
p^2 - q^2 = 2pq\left(\frac{1 - m_1m_2}{m_1 + m_2}\right)
\]
\[
\Rightarrow p^2 - q^2 = 2pq\left(\frac{1 - \frac{a}{b}}{-\frac{2h}{b}}\right)
\]

That is
\[
p^2 - q^2 = 2pq\left(\frac{\frac{b - a}{b}}{-\frac{2h}{b}}\right) = \frac{2pq(b - a)}{-2h} = \frac{pq(a - b)}{h}
\]

\[
\frac{p^2 - q^2}{a - b} = \frac{pq}{h}
\]

\[
\therefore \text{The locus of } P(p, q) \text{ is } \frac{x^2 - y^2}{a - b} = \frac{xy}{h} \tag{6.36}
\]

### Example 6.36

Show that the straight lines \(x^2 - 4xy + y^2 = 0\) and \(x + y = 3\) form an equilateral triangle.

**Solution:**

Let the line \(x + y = 3\) intersect the pair of line \(x^2 - 4xy + y^2 = 0\) at \(A\) and \(B\).

The angle between the lines \(x^2 - 4xy + y^2 = 0\) is

\[
\tan\theta = \left|\frac{2\sqrt{h^2 - ab}}{a + b}\right| = \frac{2\sqrt{4 - 1}}{2} = \sqrt{3}
\]
\[
\Rightarrow \theta = \tan^{-1}\sqrt{3} = 60^\circ
\]

The angle bisectors of the angle \(AOB\) are given by
\[
\frac{x^2 - y^2}{a - b} = \frac{xy}{h} \Rightarrow x^2 - y^2 = 0 \Rightarrow x + y = 0 \text{ and } x - y = 0
\]

The angle bisector \(x - y = 0\) is perpendicular to the given line through \(AB\), that is \(x + y = 3\). Therefore \(\triangle OAB\) is isosceles.
\[
\Rightarrow \angle ABO = \angle BAO = 60^\circ
\]

Therefore the given lines form an equilateral triangle.

**Figure 6.50**

### Example 6.37

If the pair of lines represented by \(x^2 - 2cxy - y^2 = 0\) and \(x^2 - 2dxy - y^2 = 0\) be such that each pair bisects the angle between the other pair, prove that \(cd = -1\).

**Solution:**

Given that the pair of straight lines,

\[
x^2 - 2cxy - y^2 = 0 \tag{6.37}
\]
\[
x^2 - 2dxy - y^2 = 0 \tag{6.38}
\]

Therefore equations

\[
x^2 - 2dxy - y^2 = 0
\]
\[
cx^2 + 2xy - cy^2 = 0
\]

represent the same equation as the angle bisector of (6.37)

Comparing the like terms of the above two equations, we get

\[
\frac{1}{c} = \frac{-2d}{2} = \frac{-1}{-c} \Rightarrow cd = -1
\]

### 6.5.4 General form of Pair of Straight Lines

Consider the equations of two arbitrary lines \(l_1x + m_1y + n_1 = 0\) and \(l_2x + m_2y + n_2 = 0\). The combined equation of the two lines is

\[
(l_1x + m_1y + n_1)(l_2x + m_2y + n_2) = 0
\]

If we multiply the above two factors together, we get a more general equation to a pair of straight lines has the form

\[
ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0 \tag{6.40}
\]

The above equation is a non homogeneous equation of degree two.

An equation of the form (6.40) will always represent a pair of straight lines, provided it must able to be factorized into two linear factors of the form \(l_1x + m_1y + n_1 = 0\) and \(l_2x + m_2y + n_2 = 0\).

### Condition that the general second degree equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) should represent a pair of straight lines

Let us rearrange the equation of the pair of straight lines \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) as a quadratic in \(x\), we have

\[
ax^2 + 2(hy + g)x + (by^2 + 2fy + c) = 0
\]
\[
x = \frac{-(hy + g) \pm \sqrt{(hy + g)^2 - a(by^2 + 2fy + c)}}{a}
\]
\[
ax + hy + g = \pm \sqrt{(hy + g)^2 - a(by^2 + 2fy + c)}
\]
\[
ax + hy + g = \pm \sqrt{(h^2 - ab)y^2 + 2(gh - af)y + g^2 - ac}
\]

The equation will represent a pair of straight lines if the expression under the square root is a perfect square. This condition is

\[
(gh - af)^2 - 4(h^2 - ab)(g^2 - ac) = 0
\]

Simplifying and dividing by \(a\), we get

\[
abc + 2fgh - af^2 - bg^2 - ch^2 = 0
\]

or
\[
\begin{vmatrix}
a & h & g \\
h & b & f \\
g & f & c
\end{vmatrix} = 0
\]

(Expansion of Determinant will be studied in the next chapter)

### Results without Proof:

(i) Two straight lines represented by the equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) are parallel if
\[
bg^2 = af^2 \quad \text{or} \quad h^2 = ab
\]

(ii) If \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) represents a pair of parallel straight lines, then the distance between them is
\[
2\sqrt{\frac{g^2 - ac}{a(a + b)}} \quad \text{or} \quad 2\sqrt{\frac{f^2 - bc}{b(a + b)}}
\]

The relationship between the equations of pair of straight lines

\[
ax^2 + 2hxy + by^2 = 0 \tag{6.41}
\]
\[
ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0 \tag{6.42}
\]

The slopes of the above pair of straight lines (6.41) and (6.42) depend only on the coefficients of \(x^2\), \(xy\) and \(y^2\).

**Figure 6.51**

(i) If the equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) represents a pair of straight lines, then \(ax^2 + 2hxy + by^2 = 0\) represents a pair of straight lines through the origin parallel to the first pair. The point of intersection (6.41) is \((0, 0)\) and the point of intersection (6.42) is

\[
P\left(\frac{hf - bg}{ab - h^2}, \frac{gh - af}{ab - h^2}\right)
\]

(ii) If \(\theta\) be the angle between the straight lines represented by the equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\), then it will have the same value as the angle between the two lines represented by \(ax^2 + 2hxy + by^2 = 0\).

Thus
\[
\theta = \tan^{-1}\left|\frac{2\sqrt{h^2 - ab}}{a + b}\right|
\]

(iii) If the two straight lines represented by the equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) are at right angles, then the two lines represented by \(ax^2 + 2hxy + by^2 = 0\) are also at right angles and the condition is \(a + b = 0\).

### Example 6.38

If the equation \(\lambda x^2 - 10xy + 12y^2 + 5x - 16y - 3 = 0\) represents a pair of straight lines, find

(i) the value of \(\lambda\) and the separate equations of the lines

(ii) point of intersection of the lines

(iii) angle between the lines

**Solution:**

(i) General equation is \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\).

Given equation is \(\lambda x^2 - 10xy + 12y^2 + 5x - 16y - 3 = 0\).

Comparing the given equation with the general equation of the second degree we have

\[
a = \lambda, \quad b = 12, \quad c = -3, \quad h = -5, \quad g = \frac{5}{2}, \quad f = -8
\]

Now applying the condition for pair of straight lines

\[
abc + 2fgh - af^2 - bg^2 - ch^2 = 0
\]
i.e.,
\[
\lambda(12)(-3) + 2(-8)\left(\frac{5}{2}\right)(-5) - \lambda(-8)^2 - 12\left(\frac{5}{2}\right)^2 - (-3)(-5)^2 = 0
\]
\[
\Rightarrow -36\lambda + 200 - 64\lambda - 75 + 75 = 0 \Rightarrow \lambda = 2
\]

The equation is \(2x^2 - 10xy + 12y^2 + 5x - 16y - 3 = 0\).

Let us first factorize the terms of second degree terms from the above equation,

we get
\[
2x^2 - 10xy + 12y^2 \equiv (x - 2y)(2x - 6y)
\]
\[
\therefore 2x^2 - 10xy + 12y^2 + 5x - 16y - 3 \equiv (x - 2y + c_1)(2x - 6y + c_2)
\]

Equating like terms, we get
\[
2c_1 + c_2 = 5, \quad 3c_1 + c_2 = 8, \quad c_1c_2 = -3
\]

Solving first two equation, we get \(c_1 = 3\), \(c_2 = -1\).

The separate equations of the lines are
\[
x - 2y + 3 = 0 \quad \text{and} \quad 2x - 6y - 1 = 0
\]

(ii) Point of intersection of the lines is given by solving the two equations of the lines, we get

\[
x = -\frac{19}{2}, \quad y = -\frac{11}{4}
\]

(iii) Angle between the lines is given by

\[
\theta = \tan^{-1}\left|\frac{2\sqrt{h^2 - ab}}{a + b}\right| = \tan^{-1}\left|\frac{2\sqrt{(-5)^2 - (2)(12)}}{2 + 12}\right| = \tan^{-1}\left|\frac{2\sqrt{25 - 24}}{14}\right| = \tan^{-1}\left(\frac{2}{14}\right)
\]
\[
\Rightarrow \theta = \tan^{-1}\left(\frac{1}{7}\right)
\]

### Example 6.39

A student when walks from his house, at an average speed of 6 kmph, reaches his school ten minutes before the school starts. When his average speed is 4 kmph, he reaches his school five minutes late. If he starts to school every day at 8.00 A.M, then find

(i) the distance between his house and the school

(ii) the minimum average speed to reach the school on time and time taken to reach the school

(iii) the time the school gate closes

(iv) the pair of straight lines of his path of walk.

**Solution:**

Let \(x\)-axis be the time in hours and \(y\)-axis be the distance in kilometre. From the given information, we have

\[
y = 6\left(x - \frac{10}{60}\right) \Rightarrow y = 6x - 1
\]
\[
y = 4\left(x + \frac{5}{60}\right) \Rightarrow y = 4x + \frac{1}{3} \tag{6.44}
\]

Solving the above two equations, we get \((x, y) = \left(\frac{2}{3}, 3\right)\).

\[
x = \frac{2}{3} \text{ hour} = 40 \text{ minutes}, \quad y = 3 \text{ km}
\]

(i) The distance between house and the school is \(3 \text{ km}\).

(ii) The minimum average speed to reach the school on time is

\[
\frac{60}{40} \times 3 = 4.5 \text{ kmph}
\]

and time taken is \(\frac{2}{3}\) hours or 40 minutes.

(iii) The school gate closes at 8.40 AM.

(iv) The pair of straight lines of his path of walk to school is

\[
(6x - y - 1)\left(4x - y + \frac{1}{3}\right) = 0
\]
\[
72x^2 - 30xy + 3y^2 - 6x + 2y - 1 = 0 \tag{6.45}
\]

### Example 6.40

If one of the straight lines of \(ax^2 + 2hxy + by^2 = 0\) is perpendicular to \(px + qy = 0\) then show that \(ap^2 + 2hpq + bq^2 = 0\).

**Solution:**

Let \(m_1\) and \(m_2\) be the slopes of the pair of lines \(ax^2 + 2hxy + by^2 = 0\) and \(m\) be the slope of \(px + qy = 0\).

\[
m_1 + m_2 = -\frac{2h}{b}, \quad m_1m_2 = \frac{a}{b} \quad \text{and} \quad m = -\frac{p}{q}
\]

Since one of the straight lines of \(ax^2 + 2hxy + by^2 = 0\) is perpendicular to \(px + qy = 0\).

Let \(m_1 = -\frac{1}{m} = \frac{q}{p}\).

Since \(m_1\) is a root of \(bm^2 + 2hm + a = 0\), we have

\[
b\left(\frac{q}{p}\right)^2 + 2h\left(\frac{q}{p}\right) + a = 0
\]
\[
\frac{bq^2}{p^2} + \frac{2hq}{p} + a = 0
\]

Multiplying by \(p^2\), we get

\[
bq^2 + 2hpq + ap^2 = 0
\]

## Exercise 6.4

1. Find the separate equations of the straight lines represented by the following equations:

   (i) \(3x^2 + 2xy - y^2 = 0\)

   (ii) \(6(x - 1)^2 + 5(x - 1)(y - 2) - 4(y - 2)^2 = 0\)

   (iii) \(2x^2 - xy - 3y^2 - 6x + 19y - 20 = 0\)

2. If the equation \(12x^2 + 7xy - py^2 - 18x + qy + 6 = 0\) represents a pair of perpendicular lines, find the values of \(p\) and \(q\).

3. Find the value of \(k\), if the following equation represents a pair of straight lines. Further, find whether these lines are parallel or intersecting.

   (i) \(12x^2 + 7xy - 12y^2 - x + 7y + k = 0\)

   (ii) \(x^2 + 2xy + 2y^2 + 4x + 2y + k = 0\)

4. For what value of \(k\) does the equation \(12x^2 + 2kxy + 2y^2 + 11x - 5y + 2 = 0\) represent two straight lines.

5. Show that the equation \(9x^2 - 24xy + 16y^2 - 12x + 16y - 12 = 0\) represents a pair of parallel lines. Find the distance between them.

6. Show that the equation \(4x^2 + 4xy + y^2 - 6x - 3y - 4 = 0\) represents a pair of parallel lines. Find the distance between them.

7. If the slope of one of the straight lines \(ax^2 + 2hxy + by^2 = 0\) is twice that of the other, show that \(8h^2 = 9ab\).

8. The slope of one of the straight lines \(ax^2 + 2hxy + by^2 = 0\) is three times the other, show that \(3h^2 = 4ab\).

9. A \(\triangle OPQ\) is formed by the pair of straight lines \(x^2 - 4xy + y^2 = 0\) and the line \(PQ\). The equation of \(PQ\) is \(x + y - 2 = 0\). Find the equation of the median of the triangle \(\triangle OPQ\) drawn from the origin \(O\).

10. If one of the straight lines given by \(ax^2 + 2hxy + by^2 = 0\) bisects the angle between the co-ordinate axes, then prove that \((a + b)^2 = 4h^2\).

11. If the pair of straight lines \(x^2 - 2pxy - y^2 = 0\) and \(x^2 - 2qxy - y^2 = 0\) bisect the angle between the other pair, show that \(pq = -1\).

12. Prove that the straight lines joining the origin to the points of intersection of \(3x^2 + 5xy - 3y^2 + 2x + 3y = 0\) and \(3x - 2y - 1 = 0\) are at right angles.

## Exercise 6.5

### Choose the correct or most suitable answer

1. The equation of the locus of the point whose distance from \(y\)-axis is half the distance from origin is

   (1) \(x^2 + 3y^2 = 0\)

   (2) \(x^2 - 3y^2 = 0\)

   (3) \(3x^2 + y^2 = 0\)

   (4) \(3x^2 - y^2 = 0\)

2. Which of the following equation is the locus of \((at^2, 2at)\)

   (1) \(\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1\)

   (2) \(\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1\)

   (3) \(x^2 + y^2 = a^2\)

   (4) \(y^2 = 4ax\)

3. Which of the following point lie on the locus of \(3x^2 + 3y^2 - 8x - 12y + 17 = 0\)

   (1) \((0, 0)\)

   (2) \((-2, 3)\)

   (3) \((1, 2)\)

   (4) \((0, -1)\)

4. If the point \((8, -5)\) lies on the locus \(\frac{x^2}{16} - \frac{y^2}{25} = k\), then the value of \(k\) is

   (1) 0

   (2) 1

   (3) 2

   (4) 3

5. Straight line joining the points (2, 3) and \((-1, 4)\) passes through the point \((\alpha, \beta)\) if

   (1) \(\alpha + 2\beta = 7\)

   (2) \(3\alpha + \beta = 9\)

   (3) \(\alpha + 3\beta = 11\)

   (4) \(3\alpha + \beta = 11\)

6. The slope of the line which makes an angle \(45^\circ\) with the line \(3x - y = -5\) are

   (1) \(1, -1\)

   (2) \(\frac{1}{2}, -2\)

   (3) \(1, \frac{1}{2}\)

   (4) \(2, -\frac{1}{2}\)

7. Equation of the straight line that forms an isosceles triangle with coordinate axes in the I-quadrant with perimeter \(4 + 2\sqrt{2}\) is

   (1) \(x + y + 2 = 0\)

   (2) \(x + y - 2 = 0\)

   (3) \(x + y - \sqrt{2} = 0\)

   (4) \(x + y + \sqrt{2} = 0\)

8. The coordinates of the four vertices of a quadrilateral are \((-2, 4)\), \((-1, 2)\), \((1, 2)\) and \((2, 4)\) taken in order. The equation of the line passing through the vertex \((-1, 2)\) and dividing the quadrilateral in the equal areas is

   (1) \(x + 1 = 0\)

   (2) \(x + y = 1\)

   (3) \(x + y + 3 = 0\)

   (4) \(x - y + 3 = 0\)

9. The intercepts of the perpendicular bisector of the line segment joining \((1, 2)\) and \((3, 4)\) with coordinate axes are

   (1) \(5, -5\)

   (2) \(5, 5\)

   (3) \(5, 3\)

   (4) \(5, -4\)

10. The equation of the line with slope 2 and the length of the perpendicular from the origin equal to \(\sqrt{5}\) is

    (1) \(x - 2y = \sqrt{5}\)

    (2) \(2x - y = \sqrt{5}\)

    (3) \(2x - y = 5\)

    (4) \(x - 2y - 5 = 0\)

11. A line perpendicular to the line \(5x - y = 0\) forms a triangle with the coordinate axes. If the area of the triangle is 5 sq. units, then its equation is

    (1) \(x + 5y \pm 5\sqrt{2} = 0\)

    (2) \(x - 5y \pm 5\sqrt{2} = 0\)

    (3) \(5x + y \pm 5\sqrt{2} = 0\)

    (4) \(5x - y \pm 5\sqrt{2} = 0\)

12. Equation of the straight line perpendicular to the line \(x - y + 5 = 0\), through the point of intersection of the \(y\)-axis and the given line

    (1) \(x - y - 5 = 0\)

    (2) \(x + y - 5 = 0\)

    (3) \(x + y + 5 = 0\)

    (4) \(x + y + 10 = 0\)

13. If the equation of the base opposite to the vertex \((2, 3)\) of an equilateral triangle is \(x + y = 2\), then the length of a side is

    (1) \(\sqrt{\frac{3}{2}}\)

    (2) \(6\)

    (3) \(\sqrt{6}\)

    (4) \(3\sqrt{2}\)

14. The line \((p + 2q)x + (p - 3q)y = p - q\) for different values of \(p\) and \(q\) passes through the point

    (1) \(\left(\frac{3}{2}, \frac{5}{2}\right)\)

    (2) \(\left(\frac{2}{5}, \frac{2}{5}\right)\)

    (3) \(\left(\frac{3}{5}, \frac{3}{5}\right)\)

    (4) \(\left(\frac{2}{5}, \frac{3}{5}\right)\)

15. The point on the line \(2x - 3y = 5\) is equidistant from \((1, 2)\) and \((3, 4)\) is

    (1) \((7, 3)\)

    (2) \((4, 1)\)

    (3) \((1, -1)\)

    (4) \((-2, 3)\)

16. The image of the point \((2, 3)\) in the line \(y = -x\) is

    (1) \((-3, -2)\)

    (2) \((-3, 2)\)

    (3) \((-2, -3)\)

    (4) \((3, 2)\)

17. The length of perpendicular from the origin to the line \(\frac{x}{3} - \frac{y}{4} = 1\) is

    (1) \(\frac{11}{5}\)

    (2) \(\frac{5}{12}\)

    (3) \(\frac{12}{5}\)

    (4) \(-\frac{5}{12}\)

18. The \(y\)-intercept of the straight line passing through \((1, 3)\) and perpendicular to \(2x - 3y + 1 = 0\) is

    (1) \(\frac{3}{2}\)

    (2) \(\frac{9}{2}\)

    (3) \(\frac{2}{3}\)

    (4) \(\frac{2}{9}\)

19. If the two straight lines \(x + (2k - 7)y + 3 = 0\) and \(3kx + 9y - 5 = 0\) are perpendicular then the value of \(k\) is

    (1) \(k = 3\)

    (2) \(k = \frac{1}{3}\)

    (3) \(k = \frac{2}{3}\)

    (4) \(k = \frac{3}{2}\)

20. If a vertex of a square is at the origin and its one side lies along the line \(4x + 3y - 20 = 0\), then the area of the square is

    (1) \(20 \text{ sq. units}\)

    (2) \(16 \text{ sq. units}\)

    (3) \(25 \text{ sq. units}\)

    (4) \(4 \text{ sq. units}\)

21. If the lines represented by the equation \(6x^2 + 41xy - 7y^2 = 0\) make angles \(\alpha\) and \(\beta\) with \(x\)-axis, then \(\tan\alpha \tan\beta =\)

    (1) \(-\frac{6}{7}\)

    (2) \(\frac{6}{7}\)

    (3) \(-\frac{7}{6}\)

    (4) \(\frac{7}{6}\)

22. The area of the triangle formed by the lines \(x^2 - 4y^2 = 0\) and \(x = a\) is

    (1) \(2a^2\)

    (2) \(\frac{\sqrt{3}}{2}a^2\)

    (3) \(\frac{1}{2}a^2\)

    (4) \(\frac{2}{\sqrt{3}}a^2\)

23. If one of the lines given by \(6x^2 - xy + 4cy^2 = 0\) is \(3x + 4y = 0\), then \(c\) equals to

    (1) \(-3\)

    (2) \(-1\)

    (3) \(3\)

    (4) \(1\)

24. \(\theta\) is acute angle between the lines \(x^2 - xy - 6y^2 = 0\), then \(\frac{2\cos\theta + 3\sin\theta}{4\sin\theta + 5\cos\theta}\) is

    (1) \(1\)

    (2) \(-\frac{1}{9}\)

    (3) \(\frac{5}{9}\)

    (4) \(\frac{1}{9}\)

25. One of the equation of the lines given by \(x^2 + 2xy\cot\theta - y^2 = 0\) is

    (1) \(x - y\cot\theta = 0\)

    (2) \(x + y\tan\theta = 0\)

    (3) \(x\cos\theta + y(\sin\theta + 1) = 0\)

    (4) \(x\sin\theta + y(\cos\theta + 1) = 0\)

## Summary

The types of straight lines related to the information.

| S.No. | Information given | Equation of the line |
|-------|-------------------|----------------------|
| 1 | Slope \((m)\) and \(y\)-intercept \((b)\) | \(y = mx + b\) |
| 2 | Slope \((m)\) and point \((x_1, y_1)\) | \(y - y_1 = m(x - x_1)\) |
| 3 | Two points \((x_1, y_1)\) and \((x_2, y_2)\) | \(\frac{y - y_1}{y_2 - y_1} = \frac{x - x_1}{x_2 - x_1}\) |
| 4 | \(x\)-intercept \((a)\) and \(y\)-intercept \((b)\) | \(\frac{x}{a} + \frac{y}{b} = 1\) |
| 5 | Normal length \((p)\), angle \((\alpha)\) | \(x\cos\alpha + y\sin\alpha = p\) |
| 6 | Parametric form: parameter-\(r\) | \(\frac{x - x_1}{\cos\theta} = \frac{y - y_1}{\sin\theta} = r\) |
| 7 | The general equation | \(ax + by + c = 0\) |

| Form of lines | Condition for parallel | Condition for perpendicular |
|---------------|------------------------|-----------------------------|
| \(y = m_1x + c_1\) and \(y = m_2x + c_2\) | \(m_2 = m_1\) | \(m_1m_2 = -1\) |
| \(a_1x + b_1y + c_1 = 0\) and \(a_2x + b_2y + c_2 = 0\) | \(a_1b_2 = a_2b_1\) | \(a_1a_2 + b_1b_2 = 0\) |

A point \(P(x_1, y_1)\) is on the origin side or non origin side of the line \(ax + by + c = 0\) (\(c \neq 0\)), according as \(ax_1 + by_1 + c\) and \(c\) are of the same sign or opposite sign.

The distance between two points \((x_1, y_1)\) and \((x_2, y_2)\) is given by the formula

\[
D = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
\]

The distance from a point \(P(x_1, y_1)\) to a line \(ax + by + c = 0\) is

\[
\left|\frac{ax_1 + by_1 + c}{\sqrt{a^2 + b^2}}\right|
\]

The distance between two parallel lines \(a_1x + b_1y + c_1 = 0\) and \(a_1x + b_1y + c_2 = 0\) is

\[
\left|\frac{c_2 - c_1}{\sqrt{a_1^2 + b_1^2}}\right|
\]

The line parallel to \(ax + by + c = 0\) through a point \((x_1, y_1)\), is \(ax + by = ax_1 + by_1\) and the perpendicular line is \(bx - ay = bx_1 - ay_1\).

The coordinates of the image of the point \((x_1, y_1)\) with respect to the line \(ax + by + c = 0\) can be obtained by the line

\[
\frac{x - x_1}{a} = \frac{y - y_1}{b} = -\frac{2(ax_1 + by_1 + c)}{a^2 + b^2}
\]

| Pair of straight lines | Condition for parallel | Condition for perpendicular |
|------------------------|------------------------|-----------------------------|
| \(ax^2 + 2hxy + by^2 = 0\) | \(h^2 - ab = 0\) | \(a + b = 0\) |

The equation of the bisectors of the angle between the lines \(ax^2 + 2hxy + by^2 = 0\) is

\[
\frac{x^2 - y^2}{a - b} = \frac{xy}{h}
\]

The condition that the general second degree equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) should represent a pair of straight lines is

\[
abc + 2fgh - af^2 - bg^2 - ch^2 = 0
\]

(i) The angle between them is

\[
\theta = \tan^{-1}\left|\frac{2\sqrt{h^2 - ab}}{a + b}\right|
\]

If \(a + b = 0\), then the lines are perpendicular.

(ii) The point of intersection is

\[
\left(\frac{hf - bg}{ab - h^2}, \frac{gh - af}{ab - h^2}\right)
\]

(iii) Two straight lines represented by the equation \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) are parallel if

\[
\frac{a}{h} = \frac{h}{b} = \frac{g}{f} \quad \text{or} \quad bg^2 = af^2 \quad \text{or} \quad h^2 = ab
\]

(iv) If \(ax^2 + 2hxy + by^2 + 2gx + 2fy + c = 0\) represents a pair of parallel straight lines, then the distance between them is

\[
2\sqrt{\frac{g^2 - ac}{a(a + b)}} \quad \text{or} \quad 2\sqrt{\frac{f^2 - bc}{b(a + b)}}
\]
