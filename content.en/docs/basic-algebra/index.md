---
title: 'basic algebra'
weight: 2
---


# Basic Algebra

> I see it but I don't believe it.
>
> — Richard Dedekind

## 2.1 Introduction

Algebra is a branch of mathematics in which one expresses relations among quantities by using symbols to represent these quantities. The symbols are called the variables. In this class we shall allow the variables to represent real numbers only. One can carry out manipulations and computations using variables just as one does with numbers. That is, one may substitute real numbers for the variables in the expression and the resulting value will also be a real number. Once a quantity or a mathematical statement is expressed in terms of variables, it is possible to substitute specific numerical values for those variables. This makes algebra a very powerful tool. For this reason the subject of algebra has very wide application, not only within mathematics, but also in other disciplines and in real life. The notion of real numbers is fundamental to the whole of mathematics. The real number system was well understood only in the nineteenth century. The need for extending the rational numbers arose quite early in the history of mathematics. Pythagoreans knew that \( \sqrt{2} \) was not a rational number. Certain constructions involving irrational numbers can be found in Shulbha Sutras, which date back to around 800 BC (BCE). Aryabhata (476-550) had found approximations to \( \pi \).

Indian mathematicians like Brahmagupta (598-670) and Bhaskaracharya (1114-1185) had made contributions to the understanding of the real numbers system and algebra. In his work Brahmagupta had solved the general quadratic equation for both positive and negative roots. Bhaskaracharya solved quadratic equations with more than one unknown and found negative and irrational solutions. The most important real number zero was the contribution by Indians.

Rene Descartes (1596-1650) introduced the term "real" to describe roots of a polynomial distinguishing them from imaginary ones. A rigorous construction of real number system was due to Richard Dedekind (1831-1916).

**Richard Dedekind (1831-1916)**

## Learning Objectives

On completion of this chapter, the students are expected to

- know the concept of real numbers and their properties.
- the absolute value, polynomials, exponents, radicals, logarithms and functions of one variables involving these concepts.
- how to solve equations, inequalities involving above mentioned functions.
- how to solve linear inequalities involving two variables and representing the solutions graphically in the cartesian plane.

## 2.2 Real Number System

First we shall recall how the real number system was developed. We start with natural numbers \( \mathbb{N} \).

### 2.2.1 Rational Numbers

Note that \( \mathbb{N} = \{1,2,3,\ldots\} \) is enough for counting objects. In order to deal with loss or debts, we enlarged \( \mathbb{N} \) to the set of all integers,

$$
\mathbb{Z} = \{\ldots, -4, -3, -2, -1, 0, 1, 2, \ldots\},
$$

which consists of the natural numbers, zero, and the negatives of natural numbers. We call \( \{0,1,2,3,\dots\} \) as the set of whole numbers and denote it by \( \mathbb{W} \). Note that it differs from \( \mathbb{N} \) by just one element, namely, zero. Now imagine dividing a cake into five equal parts, which is equivalent to finding a solution of \( 5x = 1 \). But this equation cannot be solved within \( \mathbb{Z} \). Hence we have enlarged \( \mathbb{Z} \) to the set

$$
\mathbb{Q} = \left\{ \frac{m}{n} : m, n \in \mathbb{Z},\ n \neq 0 \right\}
$$

of ratios; so we call each \( x \in \mathbb{Q} \) as a rational number. Some examples of rational numbers are

$$
-5,\ \frac{-7}{3},\ 0,\ \frac{22}{7},\ 7,\ 12.
$$

We have seen in earlier classes that rational numbers are precisely the set of terminating or infinite periodic decimals. For example,

$$
-5.0,\ -2.333\ldots,\ \frac{25}{99} = 0.252525\ldots,\ \frac{2}{3} = 0.66666\ldots,\ 7.14527836231231231\ldots
$$

are rational numbers.

### 2.2.2 The Number Line

Let us recall "The Number Line". It is a horizontal line with the origin, to represent 0, and another point marked to the right of 0 to represent 1. The distance from 0 to 1 defines one unit of length. Now put 2 one unit to the right of 1. Similarly we put any positive rational number \( x \) to the right of 0 and \( x \) units away. Also, we put a negative rational number \( -r, r > 0 \), to the left of 0 by \( r \) units. Note that for any \( x, y \in \mathbb{Q} \) if \( x < y \), then \( x \) is to the left of \( y \); also \( x < \frac{x + y}{2} < y \) and hence between any two distinct rational numbers there is another rational number between them.

### Question:

Have we filled the whole line with rational numbers?

The answer to the above question is "No" as the following consideration demonstrates. Consider a square whose side has length 1 unit. Then by Pythagoras theorem its diagonal has length \( \sqrt{2} \) units.

**Figure 2.1**

### 2.2.3 Irrational Numbers

### Theorem 2.1

\( \sqrt{2} \) is not a rational number.

**Proof.** Suppose that \( \sqrt{2} \) is a rational number. Let \( \sqrt{2} = \frac{m}{n} \), where \( m \) and \( n \) are positive integers with no common factors greater than 1. Then, we have \( m^2 = 2n^2 \), which implies that \( m^2 \) is even and hence \( m \) is even.

Let \( m = 2k \). Then, we have \( 2n^2 = 4k^2 \) which gives \( n^2 = 2k^2 \).

Thus, \( n \) is also even.

It follows, that \( m \) and \( n \) are even numbers having a common factor 2.

Thus, we arrived at a contradiction.

Hence, \( \sqrt{2} \) is an irrational number.

### Remark:

(i) Note that in the above proof we have assumed the contrary of what we wanted to prove and arrived at a contradiction. This method of proof is called 'proof by contradiction'.

(ii) There are points on the number line that are not represented by rational numbers.

(iii) We call those numbers on the number line that do not correspond to rational numbers as irrational numbers. The set of all irrational numbers is denoted by \( \mathbb{Q}' \) (For number line see Figure 1.2.)

Every real number is either a rational number or an irrational number, but not both. Thus,

$$
\mathbb{R} = \mathbb{Q} \cup \mathbb{Q}' \quad \text{and} \quad \mathbb{Q} \cap \mathbb{Q}' = \emptyset.
$$

As we already knew that every terminating or infinite periodic decimal is a rational number, we see that the decimal representation of an irrational number will neither be terminating nor infinite periodic. The set \( \mathbb{R} \) of real numbers can be visualized as the set of points on the number line such that if \( x < y \), then \( x \) lies to left of \( y \).

Figure 2.2 demonstrates how the square roots of 2 and 3 can be identified on a number line.

**Figure 2.2**

We notice that

$$
\mathbb{N} \subset \mathbb{W} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R}.
$$

As we have already observed, irrational numbers occur in real life situations. Over 2000 years ago people in the Orient and Egypt observed that the ratio of the circumference to the diameter is the same for any circle. This constant was proved to be an irrational number by Johann Heinrich Lambert in 1767. The value of \( \pi \) rounded off to nine decimal places is equal to \( 3.141592654 \). The values \( \frac{22}{7} \) and 3.14, used in calculations (such as area of a circle or volume of a sphere) are only approximate values for \( \pi \).

The number \( \pi \), which is the ratio of the circumference of a circle to its diameter, is an irrational number.

### 2.2.4 Properties of Real Numbers

Now let us recall the properties of the real number system which is the foundation for mathematics.

(i) For any \( a, b \in \mathbb{R} \), \( a + b \in \mathbb{R} \) and \( ab \in \mathbb{R} \)

[Sum of two real numbers is again a real number and multiplication of two real numbers is again a real number.]

(ii) For any \( a, b, c \in \mathbb{R} \), \( (a + b) + c = a + (b + c) \) and \( a(bc) = (ab)c \)

[While adding (or multiplying) finite number of real numbers, we can add (or multiply) by grouping them in any order.]

(iii) For all \( a \in \mathbb{R} \), \( a + 0 = a \) and \( a(1) = a \)

(iv) For every \( a \in \mathbb{R} \), \( a + (-a) = 0 \) and for every \( b \in \mathbb{R} - \{0\} \), \( b\left(\frac{1}{b}\right) = 1 \)

(v) For any \( a, b \in \mathbb{R} \), \( a + b = b + a \) and \( ab = ba \)

(vi) For \( a, b, c \in \mathbb{R} \), \( a(b + c) = ab + ac \)

(vii) For \( a, b \in \mathbb{R} \), \( a < b \) if and only if \( b - a > 0 \)

(viii) For any \( a \in \mathbb{R} \), \( a^2 \geq 0 \)

(ix) For any \( a, b \in \mathbb{R} \) only one of the following holds: \( a = b \) or \( a < b \) or \( a > b \)

(x) If \( a, b \in \mathbb{R} \) and \( a < b \) then \( a + c < b + c \) for all \( c \in \mathbb{R} \)

(xi) If \( a, b \in \mathbb{R} \) and \( a < b \) then \( ax < bx \) for all \( x > 0 \)

(xii) If \( a, b \in \mathbb{R} \) and \( a < b \) then \( ay > by \) for all \( y < 0 \)

## Exercise 2.1

1. Classify each element of \( \left\{\sqrt{7}, \frac{-1}{4}, 0, 3.14, 4, \frac{22}{7}\right\} \) as a member of \( \mathbb{N} \), \( \mathbb{Q} \), \( \mathbb{R} - \mathbb{Q} \) or \( \mathbb{Z} \).

2. Prove that \( \sqrt{3} \) is an irrational number. (Hint: Follow the method that we have used to prove \( \sqrt{2} \notin \mathbb{Q} \).)

3. Are there two distinct irrational numbers such that their difference is a rational number? Justify.

4. Find two irrational numbers such that their sum is a rational number. Can you find two irrational numbers whose product is a rational number.

5. Find a positive number smaller than \( \frac{1}{21000} \). Justify.

## 2.3 Absolute Value

### 2.3.1 Definition and Properties

As we have observed that there is an order preserving one-to-one correspondence between elements of \( \mathbb{R} \) and points on the number line. Note that for each \( x \in \mathbb{R} \), \( x \) and \( -x \) are equal distance from the origin. The distance of the number \( a \in \mathbb{R} \) from 0 on the number line is called the absolute value of the number \( a \) and is denoted by \( |a| \). Thus, for any \( x \in \mathbb{R} \), we have

$$
|x| = \begin{cases}
x, & \text{if } x \geq 0 \\
-x, & \text{if } x < 0
\end{cases}
$$

and hence \( |\cdot| \) defines a function known as absolute value function, from \( \mathbb{R} \) onto \( [0,\infty) \) and the graph of this function is discussed in Chapter 1.

For any \( x \in \mathbb{R} \), we have

(i) \( |x| = |-x| \) and thus, \( |x| = |y| \) if and only if \( x = y \) or \( x = -y \)

(ii) \( |x - a| = r \) if and only if \( r \geq 0 \) and \( x - a = r \) or \( x - a = -r \).

### 2.3.2 Equations Involving Absolute Value

Note that a real number \( a \) is said to be a solution of an equation or an inequality, if the statement obtained after replacing the variable by \( a \) is true. Next we shall learn solving equations involving absolute value.

### Example 2.1

Solve \( |2x - 17| = 3 \) for \( x \).

**Solution:**

\( |2x - 17| = 3 \). Then, we have \( 2x - 17 = \pm 3 \) which implies \( x = 10 \) or \( x = 7 \).

### Example 2.2

Solve \( 3|x - 2| + 7 = 19 \) for \( x \).

**Solution:**

\( 3|x - 2| + 7 = 19 \). So that we have, \( |x - 2| = \frac{19 - 7}{3} = 4 \).

Thus, we have either \( x - 2 = 4 \) or \( x - 2 = -4 \).

Therefore the solutions are \( x = -2 \) and \( x = 6 \).

### Example 2.3

Solve \( |2x - 3| = |x - 5| \).

**Solution:**

We know that \( |u| = |v| \) if and only if \( u = v \) or \( u = -v \).

Therefore, \( |2x - 3| = |x - 5| \) implies \( 2x - 3 = x - 5 \) or \( 2x - 3 = 5 - x \).

Solving these two equations, we get \( x = -2 \) and \( x = \frac{8}{3} \).

Hence, both \( x = -2 \) and \( x = \frac{8}{3} \) are solutions.

### 2.3.3 Some Results For Absolute Value

(i) If \( x, y \in \mathbb{R} \), \( |y + x| = |x - y| \), then \( xy = 0 \)

(ii) For any \( x, y \in \mathbb{R} \), \( |xy| = |x||y| \)

(iii) \( \left|\frac{x}{y}\right| = \frac{|x|}{|y|} \) for all \( x, y \in \mathbb{R} \) and \( y \neq 0 \)

(iv) For any \( x, y \in \mathbb{R} \), \( |x + y| \leq |x| + |y| \)

### 2.3.4 Inequalities Involving Absolute Value

Here we shall learn to solve inequalities involving absolute values. First we analyze very simple inequalities such as (i) \( |x| < r \) and (ii) \( |x| > r \).

(i) Let us prove that \( |x| < r \) if and only if \( -r < x < r \). Note that \( r > 0 \) as \( |x| \geq 0 \)

There are two possibilities to consider depending on the sign of \( x \).

Case (1): If \( x \geq 0 \), then \( |x| = x \), so \( |x| < r \) implies \( x < r \).

Case (2): If \( x < 0 \), then \( |x| = -x \), so \( |x| < r \) implies \( -x < r \) that is, \( x > -r \).

Therefore we have, \( |x| < r \) if and only if \( -r < x < r \), that is \( x \in (-r, r) \).

(ii) Let us prove that \( |x| > r \) if and only if \( x < -r \) or \( x > r \). Consider \( |x| > r \). If \( r < 0 \), then every \( x \in \mathbb{R} \) satisfies the inequality. For \( r \geq 0 \), there are two possibilities to consider.

Case (1). If \( x \geq 0 \), then \( |x| = x > r \).

Case (2). If \( x < 0 \), then \( |x| = -x > r \), that is, \( x < -r \).

So we have \( |x| > r \), if and only if \( x < -r \) or \( x > r \), that is, \( x \in (-\infty, -r) \cup (r, \infty) \).

### Remark:

(i) For any \( a \in \mathbb{R} \), \( |x - a| \leq r \) if and only if \( -r \leq x - a \leq r \) if and only if \( x \in [a - r, a + r] \)

(ii) For any \( a \in \mathbb{R} \), \( |x - a| \geq r \) is equivalent to \( x - a \leq -r \) or \( x - a \geq r \) if and only if \( x \in (-\infty, a - r] \cup [a + r, \infty) \).

### Example 2.4

Solve \( |x - 9| < 2 \) for \( x \).

**Solution:**

\( |x - 9| < 2 \) implies \( -2 < x - 9 < 2 \). Thus, \( 7 < x < 11 \).

### Example 2.5

Solve \( \left|\frac{2}{x - 4}\right| > 1, x \neq 4 \).

**Solution:**

From the given inequality, we have that \( 2 > |x - 4| \).

That is, \( -2 < x - 4 < 2 \) and \( x \neq 4 \).

Adding 4 throughout the inequality, we obtain \( 2 < x < 6 \) and \( x \neq 4 \).

So the solution set is \( (2,4) \cup (4,6) \).

## Exercise 2.2

1. Solve for \( x \)

   (i) \( |3 - x| < 7 \)

   (ii) \( |4x - 5| \geq -2 \)

   (iii) \( \left|3 - \frac{3}{4}x\right| \leq \frac{1}{4} \)

   (iv) \( |x| - 10 < -3 \)

2. Solve \( \frac{1}{|2x - 1|} < 6 \) and express the solution using the interval notation.

3. Solve \( -3|x| + 5 \leq -2 \) and graph the solution set in a number line.

4. Solve \( 2|x + 1| - 6 \leq 7 \) and graph the solution set in a number line.

5. Solve \( \frac{1}{5}|10x - 2| < 1 \)

6. Solve \( |5x - 12| < -2 \)

## 2.4 Linear Inequalities

Recall that a function of the form \( f(x) = ax + b \), \( a, b \in \mathbb{R} \) are constants, is called a linear function, because its graph is a straight line. Here \( a \) is the slope of the line and \( b \) is the \( y \)-intercept. If \( a \neq 0 \) then \( x \)-intercept \( x = \frac{-b}{a} \) is obtained by solving \( f(x) = ax + b = 0 \).

But there are situations where we need to consider linear inequalities.

For example to describe a statement like "A tower is not taller than fifty feet."

If \( x \) denotes the height of the tower in feet, then the above statement can be expressed as \( x \leq 50 \).

### Example 2.6

Our monthly electricity bill contains a basic charge, that is independent of units consumed and a charge that depends on the units consumed. Let us say Electricity Board charges Rs.110 as basic charge and charges Rs.4 for each unit we use. If a person wants to keep his electricity bill below Rs.250, then what should be his electricity usage?

**Solution:**

Let \( x \) denote the number of units used. Note that \( x \geq 0 \). Then, his electricity bill is Rs. \( 110 + 4x \). The person wants his bill to be below Rs.250. Let us solve the inequality \( 110 + 4x < 250 \). Thus, \( 4x < 140 \); which gives \( 0 \leq x < 35 \). The person should keep his usage below 35 units in order to keep his bill below Rs.250.

### Example 2.7

Solve \( 3x - 5 \leq x + 1 \) for \( x \).

**Solution:**

We have \( 3x - 5 \leq x + 1 \); which is equivalent to \( 2x \leq 6 \). Hence we have \( x \leq 3 \); the solution set is \( (-\infty, 3] \).

We can also solve the above inequality graphically. Let us consider the graphs of \( f(x) = 3x - 5 \) and \( g(x) = x + 1 \) (See Figure 2.3). Now, find all the \( x \)-values for which the graph of \( f \) is below the graph of \( g \).

**Figure 2.3**

### Example 2.8

Solve the following system of linear inequalities. \( 3x - 9 \geq 0 \), \( 4x - 10 \leq 6 \).

**Solution:**

Note that \( 3x - 9 \geq 0 \) implies \( 3x \geq 9 \), by multiplying both sides by \( 1/3 \) we get \( x \geq 3 \). Similarly, \( 4x - 10 \leq 6 \) implies \( 4x \leq 16 \) and hence \( x \leq 4 \).

So the solution set of \( 3x - 9 \geq 0 \), \( 4x - 10 \leq 6 \) is the intersection of \( [3, \infty) \) and \( (-\infty, 4] \). Clearly, the intersection of these intervals give \( [3, 4] \).

### Example 2.9

A girl \( A \) is reading a book having 446 pages and she has already finished reading 271 pages. She wants to finish reading this book within a week. What is the minimum number of pages she should read per day to complete reading the book within a week?

**Solution:**

Let \( x \) denote the number of pages the girl should read per day. Then we need our \( x \) to satisfy \( 7x + 271 \geq 446 \). Hence \( x \geq 25 \); which implies that she should read at least 25 pages per day.

In all the above examples observe that each inequality has more than one solution. Inequalities in general give rise to a range of solutions.

## Exercise 2.3

1. Represent the following inequalities in the interval notation:

   (i) \( x \geq -1 \) and \( x < 4 \)

   (ii) \( x \leq 5 \) and \( x \geq -3 \)

   (iii) \( x < -1 \) or \( x < 3 \)

   (iv) \( -2x > 0 \) or \( 3x - 4 < 11 \)

2. Solve \( 23x < 100 \) when (i) \( x \) is a natural number, (ii) \( x \) is an integer.

3. Solve \( -2x \geq 9 \) when (i) \( x \) is a real number, (ii) \( x \) is an integer, (iii) \( x \) is a natural number.

4. Solve: (i) \( \frac{3(x - 2)}{5} \leq \frac{5(2 - x)}{3} \). (ii) \( \frac{5 - x}{3} < \frac{x}{2} - 4 \).

5. To secure \( A \) grade one must obtain an average of 90 marks or more in 5 subjects each of maximum 100 marks. If one scored 84, 87, 95, 91 in first four subjects, what is the minimum mark one scored in the fifth subject to get \( A \) grade in the course?

6. A manufacturer has 600 litres of a 12 percent solution of acid. How many litres of a 30 percent acid solution must be added to it so that the acid content in the resulting mixture will be more than 15 percent but less than 18 percent?

7. Find all pairs of consecutive odd natural numbers both of which are larger than 10 and their sum is less than 40.

8. A model rocket is launched from the ground. The height \( h \) reached by the rocket after \( t \) seconds from lift off is given by \( h(t) = -5t^2 + 100t, 0 \leq t \leq 20 \). At what time the rocket is 495 feet above the ground?

9. A plumber can be paid according to the following schemes: In the first scheme he will be paid rupees 500 plus rupees 70 per hour, and in the second scheme he will be paid rupees 120 per hour. If he works \( x \) hours, then for what value of \( x \) does the first scheme give better wages?

10. \( A \) and \( B \) are working on similar jobs but their monthly salaries differ by more than Rs 6000. If B earns rupees 27000 per month, then what are the possibilities of A's salary per month?

## 2.5 Quadratic Functions

In earlier classes we have learnt that for any \( z \in \mathbb{R} \) and \( n \in \mathbb{N} \), \( z^n = z \cdot z \cdots z \) (\( n \)-times).

A function of the form \( P(x) = ax^2 + bx + c \), where \( a, b, c \in \mathbb{R} \) are constants and \( a \neq 0 \), is called a quadratic function. If \( P(t) = 0 \) for some \( t \in \mathbb{R} \), then we say \( t \) is a zero of \( P(x) \).

### 2.5.1 Quadratic Formula

Is it possible to write the general quadratic function \( P(x) = ax^2 + bx + c \) in the form \( a(x - k)^2 + d \)? The answer is yes. We can do this by the method called "completing the square." We shall rewrite the function \( P(x) \) as follows:

\[
\begin{aligned}
P(x) &= ax^2 + bx + c \\
&= a\left(x^2 + 2x\frac{b}{2a} + \frac{c}{a}\right) \\
&= a\left(x^2 + 2x\frac{b}{2a} + \left(\frac{b}{2a}\right)^2 - \frac{b^2}{4a^2} + \frac{c}{a}\right) \\
&= a\left(x + \frac{b}{2a}\right)^2 - a\frac{b^2}{4a^2} + c \\
&= a\left(x + \frac{b}{2a}\right)^2 + \left(a\left(\frac{b}{2a}\right)^2 - b\frac{b}{2a} + c\right).
\end{aligned}
\]

Thus,

$$
P(x) = a\left(x + \frac{b}{2a}\right)^2 + P\left(\frac{-b}{2a}\right).
$$

Now, to find the \( x \)-intercepts of the curve described by \( P(x) \), let us solve for \( P(x) = 0 \).

Considering \( P(x) = 0 \) from (1) it follows that

$$
a\left(x + \frac{b}{2a}\right)^2 + P\left(\frac{-b}{2a}\right) = 0.
$$

This gives

$$
a\left(x + \frac{b}{2a}\right)^2 = -P\left(\frac{-b}{2a}\right) = \frac{b^2}{4a} - c.
$$

So

$$
x = \frac{\sqrt{b^2 - 4ac}}{2a} - \frac{b}{2a} \quad \text{or} \quad x = -\frac{\sqrt{b^2 - 4ac}}{2a} - \frac{b}{2a}.
$$

Hence,

$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

which is called the quadratic formula.

### Remark:

Note that \( \sqrt{u} \) is defined as a non negative real number for \( u \geq 0 \).

Note that \( P(x) = 0 \) has two distinct real solutions if \( b^2 - 4ac > 0 \), the roots are real and equal if \( b^2 - 4ac = 0 \), and no real root if \( b^2 - 4ac < 0 \).

Thus the curve intersects \( x \)-axis in two places if \( b^2 - 4ac > 0 \), touches \( x \)-axis at only one point if \( b^2 - 4ac = 0 \), and does not intersect \( x \)-axis at any point if \( b^2 - 4ac < 0 \).

That is why \( D = b^2 - 4ac \) is called the discriminant of the quadratic function \( P(x) = ax^2 + bx + c \).

(i) If \( \alpha \) and \( \beta \) are roots of \( ax^2 + bx + c = 0 \), then \( \alpha + \beta = \frac{-b}{a} \) and \( \alpha\beta = \frac{c}{a} \).

(ii) If the discriminant \( b^2 - 4ac \) is negative, then the quadratic equation \( ax^2 + bx + c = 0 \), has no real roots. In this case, we have complex roots given by

$$
\alpha = \frac{-b + i\sqrt{4ac - b^2}}{2a}, \quad \beta = \frac{-b - i\sqrt{4ac - b^2}}{2a}, \quad \text{where } i^2 = -1,
$$

which we will study in Higher Secondary Second year.

(iii) For example, let us look at the graph of \( y = x^2 - 4x + 5 \). (See Figure 2.4.)

Since the graph does not intersect the \( x \)-axis, \( x^2 - 4x + 5 = 0 \) has no real roots.

**Figure 2.4**

(iv) We have the following table describing the nature of the roots of a quadratic equation and the sign of the discriminant \( D = b^2 - 4ac \).

| Discriminant | Nature of roots | Parabola |
|--------------|-----------------|----------|
| Positive | real and distinct | intersects x-axis at two points |
| Zero | real and equal | touches x-axis at one point |
| Negative | no real roots | does not meet x-axis |

### Example 2.10

If \( a \) and \( b \) are the roots of the equation \( x^2 - px + q = 0 \), find the value of \( \frac{1}{a} + \frac{1}{b} \).

**Solution:**

Given that \( a \) and \( b \) are the roots of \( x^2 - px + q = 0 \). Then, \( a + b = p \) and \( ab = q \). Thus,

$$
\frac{1}{a} + \frac{1}{b} = \frac{a + b}{ab} = \frac{p}{q}.
$$

### Example 2.11

Find the complete set of values of \( a \) for which the quadratic \( x^2 - ax + a + 2 = 0 \) has equal roots.

**Solution:**

The quadratic equation \( x^2 - ax + a + 2 = 0 \) has equal roots. So, its discriminant is zero. Thus,

$$
D = b^2 - 4ac = a^2 - 4a - 8 = 0.
$$

So, \( a = \frac{4 \pm \sqrt{48}}{2} \) which gives \( a = 2 + \sqrt{12},\ 2 - \sqrt{12} \).

### Example 2.12

Find the number of solutions of \( x^2 + |x - 1| = 1 \).

**Solution:**

Case (1). For \( x \geq 1 \), \( |x - 1| = x - 1 \).

Then the given equation reduces to \( x^2 + x - 2 = 0 \). Factoring we get \( (x + 2)(x - 1) = 0 \), which implies \( x = -2 \) or 1. As \( x \geq 1 \), we obtain \( x = 1 \).

Case (2). For \( x < 1 \), \( |x - 1| = 1 - x \).

Then the given equation becomes \( x^2 + 1 - x = 1 \). Thus we have \( x(x - 1) = 0 \) which implies \( x = 0 \) or \( x = 1 \). As \( x < 1 \), we have to choose \( x = 0 \).

Thus, the solution set is \( \{0, 1\} \). Hence, the equation has two solutions.

## Exercise 2.4

1. Construct a quadratic equation with roots 7 and \( -3 \).

2. A quadratic polynomial has one of its zeros \( 1 + \sqrt{5} \) and it satisfies \( p(1) = 2 \). Find the quadratic polynomial.

3. If \( \alpha \) and \( \beta \) are the roots of the quadratic equation \( x^2 + \sqrt{2}x + 3 = 0 \), form a quadratic polynomial with zeroes \( \frac{1}{\alpha}, \frac{1}{\beta} \).

4. If one root of \( k(x - 1)^2 = 5x - 7 \) is double the other root, show that \( k = 2 \) or \( -25 \).

5. If the difference of the roots of the equation \( 2x^2 - (a + 1)x + a - 1 = 0 \) is equal to their product, then prove that \( a = 2 \).

6. Find the condition that one of the roots of \( ax^2 + bx + c \) may be (i) negative of the other, (ii) thrice the other, (iii) reciprocal of the other.

7. If the equations \( x^2 - ax + b = 0 \) and \( x^2 - ex + f = 0 \) have one root in common and if the second equation has equal roots, then prove that \( ae = 2(b + f) \).

8. Discuss the nature of roots of (i) \( -x^2 + 3x + 1 = 0 \), (ii) \( 4x^2 - x - 2 = 0 \), (iii) \( 9x^2 + 5x = 0 \).

9. Without sketching the graphs, find whether the graphs of the following functions will intersect the \( x \)-axis and if so in how many points. (i) \( y = x^2 + x + 2 \), (ii) \( y = x^2 - 3x - 7 \), (iii) \( y = x^2 + 6x + 9 \).

10. Write \( f(x) = x^2 + 5x + 4 \) in completed square form.

### 2.5.2 Quadratic Inequalities

Here we shall learn to solve the quadratic inequalities \( ax^2 + bx + c < 0 \) or \( ax^2 + bx + c > 0 \).

### Steps to Solve Quadratic Inequalities:

(i) First solve \( ax^2 + bx + c = 0 \).

(ii) If there are no real solutions, then one of the above inequality holds for all \( x \in \mathbb{R} \).

(iii) If there are real solutions, which are called critical points, then label those points on the number line.

(iv) Note that these critical points divide the number line into disjoint intervals. (It is possible that there may be only one critical point.)

(v) Choose one representative number from each interval.

(vi) Substitute these representative numbers in the inequality.

(vii) Identify the intervals where the inequality is satisfied.

### Example 2.13

Solve \( 3x^2 + 5x - 2 \leq 0 \).

**Solution:**

On factorizing the quadratic polynomial we get \( 3(x + 2)\left(x - \frac{1}{3}\right) \leq 0 \). Draw the number line. Mark the critical points \( -2 \) and \( \frac{1}{3} \) where the factors vanish (See Figure 2.5). On each sub-interval check the sign of \( (x + 2)\left(x - \frac{1}{3}\right) \). To do this pick an arbitrary point anywhere in the interval. Whatever sign the resulting value has, the polynomial has the same sign throughout the whole corresponding interval. (Otherwise, there would be another critical point within the interval.) This process is easily organized in the following table.

**Figure 2.5**

| Interval | Sign of \( (x + 2) \) | Sign of \( \left(x - \frac{1}{3}\right) \) | Sign of \( 3x^2 + 5x - 2 \) |
|----------|----------------------|------------------------------------------|---------------------------|
| \( (-\infty, -2) \) | - | - | + |
| \( (-2, \frac{1}{3}) \) | + | - | - |
| \( (\frac{1}{3}, \infty) \) | + | + | + |

You can see the inequality is satisfied in \( [-2, \frac{1}{3}] \).

### Example 2.14

Solve \( \sqrt{x + 14} < x + 2 \).

**Solution:**

The function \( \sqrt{x + 14} \) is defined for \( x + 14 \geq 0 \). Therefore \( x \geq -14 \). Also \( x + 2 > 0 \) implies \( x > -2 \).

\( (x + 14) < (x + 2)^2 \) gives \( x^2 + 3x - 10 > 0 \).

Hence, \( (x + 5)(x - 2) > 0 \). Dividing the number line with the critical points \( x = -5 \) and \( x = 2 \), substituting a reference point in the sub-interval we get the solution set to be \( x < -5 \) and \( x > 2 \).

Since \( x > -2 \), we have the solution to be \( x > 2 \).

### Example 2.15

Solve the equation \( \sqrt{6 - 4x - x^2} = x + 4 \).

**Solution:**

The given equation is equivalent to the system

\( x + 4 \geq 0 \) and \( 6 - 4x - x^2 = (x + 4)^2 \).

This implies \( x \geq -4 \) and \( x^2 + 6x + 5 = 0 \). Thus, \( x = -1, -5 \).

But only \( x = -1 \) satisfies both the conditions. Hence, \( x = -1 \).

## Exercise 2.5

1. Solve \( 2x^2 + x - 15 \leq 0 \).

2. Solve \( -x^2 + 3x - 2 \geq 0 \).

3. Solve \( x^2 + 3x + 1 > 0 \).

4. Solve \( 2x^2 - 5x + 3 \geq 0 \).

5. Solve \( -2x^2 + 5x - 2 \geq 0 \).

## 2.6 Polynomial Functions

So far we have understood about linear functions and quadratic functions. Now we shall generalize these ideas. We call an expression of the form

$$
a_n x^n + a_{n-1} x^{n-1} + \dots + a_0
$$

is called a polynomial in the variable \( x \), where \( a_i \in \mathbb{R} \), \( i = 0,1,2,\dots,n \). Here \( n \) is a non-negative integer. When \( a_n \neq 0 \) we say that the polynomial has degree \( n \). The numbers \( a_0, a_1, \ldots, a_n \in \mathbb{R} \) are called the coefficients of the polynomial. The number \( a_0 \) is called the constant term and \( a_n \) is called the leading coefficient (when it is non-zero). It is clear that:

(i) \( 100x^7 - \pi x^5 + 20\sqrt{2} x^2 + 7x + 1.22 \) is a polynomial of degree 7.

(ii) \( (17x - 3)(x + 3)(2x - \sqrt{\pi})(x + 2.3) \) is a polynomial of degree 4.

(iii) \( (x^2 + x + 1)(x^3 + 2x + 2)(x^5 - 5x + \sqrt{3}) \) is a polynomial of degree 10.

One may substitute specific values for \( x \), say \( x = c \) and obtain \( a_n c^n + a_{n-1} c^{n-1} + \dots + a_1 c + a_0 \). A function of the form

$$
P(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_0
$$

is called a polynomial function which is defined from \( \mathbb{R} \) to \( \mathbb{R} \). We shall treat polynomial and polynomial function as one and the same.

A polynomial with degree 1 is called a linear polynomial. A polynomial with degree 2 is called a quadratic polynomial. A cubic polynomial is one that has degree three. Likewise, degree 4 and degree 5 polynomials are called quartic and quintic polynomials respectively. Note that any constant \( a \neq 0 \) is a polynomial of degree zero!

Two polynomials

$$
f(x) = a_n x^n + a_{n-1} x^{n-1} + \dots + a_0,\ a_n \neq 0
$$

and

$$
g(x) = b_m x^m + b_{m-1} x^{m-1} + \dots + b_0,\ b_m \neq 0
$$

are equal if and only if \( f(x) = g(x) \) for all \( x \in \mathbb{R} \). It can be proved that \( f(x) = g(x) \) if and only if \( n = m \) and \( a_k = b_k \), \( k = 0,1,2,\dots n \). Given two polynomials, one can form their sum and product. For example if \( P(x) = 2x^3 + 7x^2 - 5 \) and \( Q(x) = x^4 - 2x^3 + x^2 + x + 1 \), then

$$
P(x) + Q(x) = x^4 + 8x^2 + x - 4
$$

(by adding the corresponding coefficients of the like powers of \( x \)) and

$$
P(x)Q(x) = 2x^7 + 3x^6 - 12x^5 + 4x^4 + 19x^3 + 2x^2 - 5x - 5
$$

by multiplying each term of \( P(x) \) by every term of \( Q(x) \). It is easy to see that the degree of \( P(x)Q(x) \) is the sum of the degrees of \( P(x) \) and \( Q(x) \), whereas the degree of \( P(x) + Q(x) \) is at most the maximum of degrees of \( P(x) \) and \( Q(x) \). Here is an example of the graph of a cubic polynomial function.

**Figure 2.6**

Suppose that \( f(x) \) and \( g(x) \) are polynomials where \( g(x) \) is not zero. The quotient \( \frac{f(x)}{g(x)} \) is called a rational function, which is defined for all \( x \in \mathbb{R} \) such that \( g(x) \neq 0 \). In general, a rational function need not be a polynomial.

### 2.6.1 Division Algorithm

Given two polynomials \( f(x) \) and \( g(x) \), where \( g(x) \) is not the zero polynomial, there exist two polynomials \( q(x) \) and \( r(x) \) such that

$$
f(x) = q(x)g(x) + r(x)
$$

where degree of \( r(x) < \) degree of \( g(x) \). Here, \( q(x) \) is called the quotient polynomial, and \( r(x) \) is called the remainder polynomial. If \( r(x) \) is the zero polynomial, then \( q(x) \), \( g(x) \) are factors of \( f(x) \) and \( f(x) = q(x)g(x) \). These terminologies are similar to terminologies used in division done with integers.

If \( g(x) = x - a \), then the remainder \( r(x) \) should have degree zero and hence \( r(x) \) is a constant. To determine the constant, write \( f(x) = (x - a)q(x) + c \). Substituting \( x = a \) we get \( c = f(a) \).

### Remainder Theorem

If a polynomial \( f(x) \) is divided by \( x - a \), then the remainder is \( f(a) \). Thus the remainder \( c = f(a) = 0 \) if and only if \( x - a \) is a factor for \( f(x) \).

### Definition 2.1

A real number \( a \) is said to be a zero of the polynomial \( f(x) \) if \( f(a) = 0 \). If \( x = a \) is a zero of \( f(x) \), then \( x - a \) is a factor for \( f(x) \).

In general, if we can express \( f(x) \) as \( f(x) = (x - a)^k g(x) \) where \( g(a) \neq 0 \), then the value of \( k \), which depends on \( a \), cannot exceed the degree of \( f(x) \). The value \( k \) is called the multiplicity of the zero \( a \).

(i) A polynomial function of degree \( n \) can have at most \( n \) distinct real zeros. It is also possible that a polynomial function like \( P(x) = x^2 + 1 \) has no real zeros at all.

(ii) Suppose that \( P(x) \) is a polynomial function having rational coefficients. If \( a + b\sqrt{p} \) where \( a, b \in \mathbb{Q} \), \( p \) a prime, is a zero of \( P(x) \), then its conjugate \( a - b\sqrt{p} \) is also a zero.

Two important problems relating to polynomials are

(i) Finding zeros of a given polynomial function; and hence factoring the polynomial into linear factors and

(ii) Constructing polynomials with the given zeros and/or satisfying some additional conditions.

To address the problem of finding zeros of a polynomial function, some well known algebraic identities are useful.

### What is an identity?

An equation is said to be an identity if that equation remains valid for all values in its domain. An equation is called conditional equation if it is true only for some (not all) of values in its domain. Let us recall the following identities.

### 2.6.2 Important Identities

For all \( x, a, b \in \mathbb{R} \) we have

1. \( (x + a)^3 = (x + a)^2(x + a) = x^3 + 3x^2a + 3xa^2 + a^3 = x^3 + 3xa(x + a) + a^3 \)

2. \( (x - b)^3 = x^3 - 3x^2b + 3xb^2 - b^3 = x^3 - 3xb(x - b) - b^3 \) (taking \( a = -b \) in (1))

3. \( x^3 + a^3 = (x + a)(x^2 - xa + a^2) \)

4. \( x^3 - b^3 = (x - b)(x^2 + xb + b^2) \) (taking \( a = -b \) in (3))

5. \( x^n - a^n = (x - a)(x^{n-1} + x^{n-2}a + \dots + x^{n-k-1}a^k + \dots + a^{n-1}),\ n \in \mathbb{N} \)

6. \( x^n + b^n = (x + b)(x^{n-1} - x^{n-2}b + \dots + x^{n-k-1}(-b)^k + \dots + (-b)^{n-1}),\ n \in \mathbb{N} \)

### Method of Undetermined Coefficients

Now let us focus on constructing polynomials with the given information using the method of undetermined coefficients. That is, we shall determine coefficients of the required polynomial using the given conditions. The main idea here is that two polynomials are equal if and only if the coefficients of same powers of the variables in the two polynomials are equal.

### Example 2.16

Find a quadratic polynomial \( f(x) \) such that, \( f(0) = 1 \), \( f(-2) = 0 \) and \( f(1) = 0 \).

**Solution:**

Let \( f(x) = ax^2 + bx + c \) be the polynomial satisfying the given conditions.

\( f(0) = a(0)^2 + b(0) + c = 1 \), implies that \( c = 1 \). Now the other two conditions \( f(-2) = 0 \), \( f(1) = 0 \) give

$$
4a - 2b + c = 0 \quad \text{and} \quad a + b + c = 0.
$$

Using \( c = 1 \), we get \( 4a - 2b = -1 \) and \( a + b = -1 \). Solving these two equations we get \( a = b = -\frac{1}{2} \) and thus, we have

$$
f(x) = -\frac{1}{2}x^2 - \frac{1}{2}x + 1.
$$

The above problem can also be solved in another way. \( x = -2 \), \( x = 1 \) are zeros of \( f(x) \). Thus, \( f(x) = d(x + 2)(x - 1) \) for some constant \( d \). Now using \( f(0) = 1 \) gives \( -2d = 1 \), hence \( d = -\frac{1}{2} \). So,

$$
f(x) = -\frac{1}{2}(x + 2)(x - 1) = -\frac{1}{2}x^2 - \frac{1}{2}x + 1.
$$

### Example 2.17

Construct a cubic polynomial function with rational coefficients having zeros at \( x = \frac{2}{5} \), \( 1 + \sqrt{3} \) such that \( f(0) = -8 \).

**Solution:**

Given that \( \frac{2}{5} \) and \( 1 + \sqrt{3} \) are zeros of \( f(x) \). Thus, \( 1 - \sqrt{3} \) is also a zero of \( f(x) \). Let

$$
f(x) = a\left(x - \frac{2}{5}\right)[(x - (1 + \sqrt{3}))][x - (1 - \sqrt{3})] = a\left(x - \frac{2}{5}\right)[(x - 1)^2 - 3].
$$

Using \( f(0) = -8 \), we have \( \left(-\frac{2}{5}a\right)(-2) = -8 \) which gives \( a = -10 \). Thus the required polynomial is

$$
f(x) = (-10)\left(x - \frac{2}{5}\right)[x^2 - 2x - 2] = -10x^3 + 24x^2 + 12x - 8.
$$

### Example 2.18

Prove that \( ap + q = 0 \) if \( f(x) = x^3 - 3px + 2q \) is divisible by \( g(x) = x^2 + 2ax + a^2 \).

**Solution:**

Note that the degree of \( f(x) \) is 3 and the leading coefficient is 1. Since \( g(x) \) divides \( f(x) \), we have \( f(x) = (x + b)g(x) \), for some \( b \in \mathbb{R} \). Thus,

$$
x^3 - 3px + 2q = (x + b)(x^2 + 2ax + a^2).
$$

Equating like coefficients on both sides, we have

$$
2a + b = 0,\quad a^2 + 2ab = -3p,\quad 2q = ba^2.
$$

Thus, \( b = -2a \), \( p = a^2 \), and \( q = -a^3 \).

Now, \( q = -a^3 = -a(a^2) = -ap \), which gives \( ap + q = 0 \).

### Example 2.19

Use the method of undetermined coefficients to find the sum of \( 1 + 2 + 3 + \dots + (n-1) + n \), \( n \in \mathbb{N} \).

**Solution:**

Let us assume that \( S(n) = a + bn + cn^2 \) for some constants \( a, b, c \).

We know that \( S(1) = 1 \), \( S(2) = 3 \), and \( S(3) = 6 \).

Now,

\[
\begin{aligned}
S(n+1) - S(n) &= [a + b(n+1) + c(n+1)^2] - [a + bn + cn^2] \\
&= b + 2cn + c.
\end{aligned}
\]

But also \( S(n+1) - S(n) = n + 1 \).

Thus, \( b + 2cn + c = n + 1 \).

Equating like coefficients, we get \( 2c = 1 \) and \( b + c = 1 \), which give \( c = \frac{1}{2} \), \( b = \frac{1}{2} \).

Now, \( S(1) = a + b + c = 1 \) gives \( a = 0 \).

Hence,

$$
S(n) = \frac{1}{2}n + \frac{1}{2}n^2 = \frac{n(n+1)}{2},\ n \in \mathbb{N}.
$$

### Example 2.20

Find the roots of the polynomial equation \( (x - 1)^3(x + 1)^2(x + 5) = 0 \) and state their multiplicity.

**Solution:**

Let \( f(x) = (x - 1)^3(x + 1)^2(x + 5) = 0 \). Clearly, we have \( x = 1, -1, -5 \). Hence, the roots are 1 with multiplicity 3, \( -1 \) with multiplicity 2 and \( -5 \) with multiplicity 1.

When the root has multiplicity 1, it is called a simple root.

### Example 2.21

Solve \( x = \sqrt{x + 20} \) for \( x \in \mathbb{R} \).

**Solution:**

By the definition of square root, \( \sqrt{x + 20} \geq 0 \).

Since \( x = \sqrt{x + 20} \), \( x \) is positive.

Now squaring we get \( x^2 = x + 20 \), \( x^2 - x - 20 = 0 \).

\( (x - 5)(x + 4) = 0 \), which gives \( x = 5 \), \( x = -4 \).

Since \( x \) is positive, the required solution is \( x = 5 \).

### Example 2.22

The equations \( x^2 - 6x + a = 0 \) and \( x^2 - bx + 6 = 0 \) have one root in common. The other root of the first and the second equations are integers in the ratio 4 : 3. Find the common root.

**Solution:**

Let \( \alpha \) be the common root.

Let \( \alpha, 4\beta \) be the roots of \( x^2 - 6x + a = 0 \).

Let \( \alpha, 3\beta \) be the roots of \( x^2 - bx + 6 = 0 \).

Then, \( 4\alpha\beta = a \) and \( 3\alpha\beta = 6 \) which give \( \alpha\beta = 2 \) and \( a = 8 \).

The roots of \( x^2 - 6x + 8 = 0 \) are 2, 4.

If \( \alpha = 2 \), then \( \beta = 1 \).

If \( \alpha = 4 \), then \( \beta = \frac{1}{2} \) which is not an integer.

Hence, the common root is 2.

### Example 2.23

Find the values of \( p \) for which the difference between the roots of the equation \( x^2 + px + 8 = 0 \) is 2.

**Solution:**

Let \( \alpha \) and \( \beta \) be the roots of the equation \( x^2 + px + 8 = 0 \).

Then, \( \alpha + \beta = -p \), \( \alpha\beta = 8 \) and \( |\alpha - \beta| = 2 \).

Now, \( (\alpha + \beta)^2 - 4\alpha\beta = (\alpha - \beta)^2 \), which gives \( p^2 - 32 = 4 \). Thus, \( p = \pm 6 \).

## Exercise 2.6

1. Find the zeros of the polynomial function \( f(x) = 4x^2 - 25 \).

2. If \( x = -2 \) is one root of \( x^3 - x^2 - 17x = 22 \), then find the other roots of equation.

3. Find the real roots of \( x^4 = 16 \).

4. Solve \( (2x + 1)^2 - (3x + 2)^2 = 0 \).

## Exercise 2.7

1. Factorize: \( x^4 + 1 \). (Hint: Try completing the square.)

2. If \( x^2 + x + 1 \) is a factor of the polynomial \( 3x^3 + 8x^2 + 8x + a \), then find the value of \( a \).

## 2.7 Rational Functions

A rational expression of \( x \) is defined as the ratio of two polynomials in \( x \), say \( P(x) \) and \( Q(x) \) where \( Q(x) \neq 0 \). Examples of rational expressions are

$$
\frac{2x + 1}{x^2 + x + 1},\ \frac{x^4 + 1}{x^2 + 1},\ \frac{x^2 + x}{x^2 - 5x + 6}.
$$

If the degree of the numerator \( P(x) \) is equal to or larger than that of the denominator \( Q(x) \), then we can write

$$
P(x) = f(x)Q(x) + r(x)
$$

where \( r(x) = 0 \) or the degree of \( r(x) \) is less than that of \( Q(x) \).

So

$$
\frac{P(x)}{Q(x)} = f(x) + \frac{r(x)}{Q(x)}.
$$

### 2.7.1 Rational Inequalities

### Example 2.24

Solve \( \frac{x + 1}{x + 3} < 3 \).

**Solution:**

Subtracting 3 from both sides we get

$$
\frac{x + 1}{x + 3} - 3 < 0.
$$

$$
\frac{x + 1 - 3(x + 3)}{x + 3} < 0 \implies \frac{-2x - 8}{x + 3} < 0 \implies \frac{x + 4}{x + 3} > 0.
$$

Thus, \( x + 4 \) and \( x + 3 \) are both positive or both negative.

So let us find out the signs of \( x + 3 \) and \( x + 4 \) as follows

| \( x \) | \( x+3 \) | \( x+4 \) | \( \frac{x+4}{x+3} \) |
|--------|----------|----------|----------------------|
| \( x < -4 \) | - | - | + |
| \( -4 < x < -3 \) | - | + | - |
| \( x > -3 \) | + | + | + |

So the solution set is given by \( (-\infty, -4) \cup (-3, \infty) \).

The above type of rational inequality problem can also be solved by plotting the signs of various factors on the intervals of the number line.

## Exercise 2.8

1. Find all values of \( x \) for which \( \frac{x^3(x - 1)}{(x - 2)} > 0 \).

2. Find all values of \( x \) that satisfies the inequality \( \frac{2x - 3}{(x - 2)(x - 4)} < 0 \).

3. Solve \( \frac{x^2 - 4}{x^2 - 2x - 15} \leq 0 \).

### 2.7.2 Partial Fractions

A rational expression \( \frac{f(x)}{g(x)} \) is called a proper fraction if the degree of \( f(x) \) is less than degree of \( g(x) \) where \( g(x) \) can be factored into linear factors and quadratic factors without real zeros. Now \( \frac{f(x)}{g(x)} \) can be expressed in simpler terms, namely, as a sum of expressions of the form

(i) \( \frac{A_1}{(x - a)} + \frac{A_2}{(x - a)^2} + \cdots + \frac{A_k}{(x - a)^k} \) if \( x - a \) divides \( g(x) \) and

(ii) \( \frac{B_1 x + C_1}{(x^2 + ax + b)} + \frac{B_2 x + C_2}{(x^2 + ax + b)^2} + \cdots + \frac{B_k x + C_k}{(x^2 + ax + b)^k} \) if \( x^2 + ax + b \) has no real zeros and \( (x^2 + ax + b)^k \) divides \( g(x) \).

The resulting expression of \( \frac{f(x)}{g(x)} \) is called the partial fraction decomposition. Such a decomposition is unique for a given rational function. This method is useful in doing Integral calculus. So let us discuss some examples.

### Example 2.25

Resolve into partial fractions: \( \frac{x}{(x + 3)(x - 4)} \).

**Solution:**

Let \( \frac{x}{(x + 3)(x - 4)} = \frac{A}{x + 3} + \frac{B}{x - 4} \) where \( A \) and \( B \) are constants. Then,

$$
\frac{x}{(x + 3)(x - 4)} = \frac{A(x - 4) + B(x + 3)}{(x + 3)(x - 4)},
$$

which gives \( x = A(x - 4) + B(x + 3) \). When \( x = 4 \), we have \( B = \frac{4}{7} \). When \( x = -3 \), we have \( A = \frac{3}{7} \). Hence,

$$
\frac{x}{(x + 3)(x - 4)} = \frac{3}{7(x + 3)} + \frac{4}{7(x - 4)}.
$$

The above procedure can be carried out if the denominator has all its zeros in \( \mathbb{R} \) which are all distinct.

### Example 2.26

Resolve into partial fractions: \( \frac{2x}{(x^2 + 1)(x - 1)} \).

**Solution:**

In this case, note that the denominator has a factor \( x^2 + 1 \) which does not have real zeros.

$$
\frac{2x}{(x^2 + 1)(x - 1)} = \frac{A}{(x - 1)} + \frac{Bx + C}{x^2 + 1}
$$

where \( A, B, C \) are constants.

We have, \( 2x = A(x^2 + 1) + (Bx + C)(x - 1) \).

When \( x = 1 \), we get \( A = 1 \).

When \( x = 0 \), we have \( A - C = 0 \) and hence \( A = C = 1 \).

When \( x = -1 \), we have \( 2A - 2(C - B) = -2 \), which gives \( B = -1 \).

Thus,

$$
\frac{2x}{(x^2 + 1)(x - 1)} = \frac{1}{(x - 1)} + \frac{1 - x}{x^2 + 1}.
$$

We now illustrate the situation when denominator has a real zeros with multiplicity more than one.

### Example 2.27

Resolve into partial fractions: \( \frac{x + 1}{x^2(x - 1)} \).

**Solution:**

$$
\frac{x + 1}{x^2(x - 1)} = \frac{A}{x} + \frac{B}{x^2} + \frac{C}{x - 1}.
$$

Then, \( x + 1 = Ax(x - 1) + B(x - 1) + Cx^2 \).

When \( x = 0 \), we have \( B = -1 \) and when \( x = 1 \), we get \( C = 2 \).

When \( x = -1 \), we have \( 2A - 2B + C = 0 \) which gives \( A = -2 \).

Thus,

$$
\frac{x + 1}{x^2(x - 1)} = \frac{-2}{x} - \frac{1}{x^2} + \frac{2}{x - 1}.
$$

## Exercise 2.9

Resolve into partial fractions:

1. \( \frac{1}{x^2 - a^2} \)

2. \( \frac{3x + 1}{(x - 2)(x + 1)} \)

3. \( \frac{x}{(x^2 + 1)(x - 1)(x + 2)} \)

4. \( \frac{x}{(x - 1)^3} \)

5. \( \frac{1}{x^4 - 1} \)

6. \( \frac{(x - 1)^2}{x^3 + x} \)

7. \( \frac{x^2 + x + 1}{x^2 - 5x + 6} \)

8. \( \frac{x^3 + 2x + 1}{x^2 + 5x + 6} \)

9. \( \frac{x + 12}{(x + 1)^2(x - 2)} \)

10. \( \frac{6x^2 - x + 1}{x^3 + x^2 + x + 1} \)

11. \( \frac{2x^2 + 5x - 11}{x^2 + 2x - 3} \)

12. \( \frac{7 + x}{(1 + x)(1 + x^2)} \)

### 2.7.3 Graphical Representation of Linear Inequalities

A straight line \( ax + by = c \) divides the Cartesian plane into two parts. Each part is an half plane. A vertical line \( x = c \) will divide the plane in left and right half planes and a horizontal line \( y = k \) will divide the plane into upper and lower half planes.

A point in the cartesian plane which is not on the line \( ax + by = c \) will lie in exactly one of the two half planes determined by the line and satisfies one of the inequalities \( ax + by < c \) or \( ax + by > c \).

To identify the half plane represented by \( ax + by < c \), choose a point \( P \) in any one of the half planes and substitute the coordinates of \( P \) in the inequality.

If the inequality is satisfied, then the required half plane is the one that contains \( P \); otherwise the required half plane is the one that does not contain \( P \). When \( c \neq 0 \), it is most convenient to take \( P \) to be the origin.

### Example 2.28

Shade the region given by the inequality \( x \geq 2 \).

**Solution:**

First we consider equation \( x = 2 \). It is a line parallel to \( y \)-axis at a distance of 2 units from it. This line divides the cartesian plane into two parts. Substituting \( (0,0) \) in the inequality we get \( 0 \geq 2 \) which is false. Hence the region which does not contain the origin is represented by the inequality \( x \geq 2 \). The shaded region is the required solution set of the given inequality. Since \( x \geq 2 \), the points on the line \( x = 2 \) are also solutions.

### Example 2.29

Shade the region given by the linear inequality \( x + 2y > 3 \).

**Solution:**

The line \( x + 2y = 3 \) divides the cartesian plane into two half planes. To find the half plane represented by \( x + 2y > 3 \) substitute a point in one of the half planes in the inequality and check whether it is satisfied. Let us substitute \( (0,0) \) in the inequality. We get \( 0 > 3 \) which is false. Hence, the region given by \( x + 2y > 3 \) is the half plane which does not contain the origin.

### Example 2.30

Solve the linear inequalities and exhibit the solution set graphically:

$$
x + y \geq 3,\quad 2x - y \leq 5,\quad -x + 2y \leq 3.
$$

**Solution:**

Observe that a straight line can be drawn if we identify any two points on it. For example, \( (3,0) \) and \( (0,3) \) can be easily identified as two points on the straight line \( x + y = 3 \). Draw the three straight lines \( x + y = 3 \), \( 2x - y = 5 \) and \( -x + 2y = 3 \). Now \( (0,0) \) does not satisfy \( x + y \geq 3 \). Thus, the half plane bounded by \( x + y = 3 \), not containing the origin, is the solution set of \( x + y \geq 3 \).

Similarly, the half-plane bounded by \( 2x - y \leq 5 \) containing the origin represents the solution set of \( 2x - y \leq 5 \).

The region represented by \( -x + 2y \leq 3 \) is the half space bounded by the straight line \( -x + 2y = 3 \) that contains the origin.

The region common to the above three half planes represents the solution set of the given linear inequalities.

## Exercise 2.10

Determine the region in the plane determined by the inequalities:

(1) \( x \leq 3y \), \( x \geq y \)

(2) \( y \geq 2x \), \( -2x + 3y \leq 6 \)

(3) \( 3x + 5y \geq 45 \), \( x \geq 0 \), \( y \geq 0 \)

(4) \( 2x + 3y \leq 35 \), \( y \geq 2 \), \( x \geq 5 \)

(5) \( 2x + 3y \leq 6 \), \( x + 4y \leq 4 \), \( x \geq 0 \), \( y \geq 0 \)

(6) \( x - 2y \geq 0 \), \( 2x - y \leq -2 \), \( x \geq 0 \), \( y \geq 0 \)

(7) \( 2x + y \geq 8 \), \( x + 2y \geq 8 \), \( x + y \leq 6 \)

## 2.8 Exponents and Radicals

First we shall consider exponents.

### 2.8.1 Exponents

Let \( n \in \mathbb{N} \), \( a \in \mathbb{R} \). Then \( a^n = a \cdot a \cdots a \) (\( n \) times). If \( m \) is a negative integer and the real number \( a \neq 0 \), then \( a^m = \frac{1}{a^{-m}} \).

Note that for any \( a \neq 0 \), we have \( \frac{a}{a} = a^{1-1} = a^0 = 1 \). It is also easy to see the following properties.

### Properties of Exponents

(i) For \( m, n \in \mathbb{Z} \) and \( a \neq 0 \), we have \( a^m a^n = a^{m+n} \)

(ii) For \( m, n \in \mathbb{Z} \) and \( a \neq 0 \), we have \( \frac{a^m}{a^n} = a^{m-n} \)

### 2.8.2 Radicals

### Question:

For \( a \neq 0 \) and \( r \in \mathbb{Q} \), is it possible to define \( a^r \)?

First let us consider the case when \( r = \frac{1}{n} \), \( n \in \mathbb{N} \). Suppose there is a real number \( y \in \mathbb{R} \) such that \( y = a^{\frac{1}{n}} \). Then we must have \( y^n = a \).

This problem is basically to finding inverse function of \( y = x^n \). In order to understand better let us consider the graphs of the following functions:

(i) \( f(x) = x^{2n} \), \( n \in \mathbb{N} \)

(ii) \( g(x) = x^{2n+1} \), \( n \in \mathbb{N} \)

From these two figures it is clear that the function \( g : \mathbb{R} \to \mathbb{R} \) given by \( g(x) = x^{2n+1} \), \( n \in \mathbb{N} \) is one-to-one and onto and hence its inverse function from \( \mathbb{R} \) onto \( \mathbb{R} \) exists. But \( f : \mathbb{R} \to [0,\infty) \) given by \( f(x) = x^{2n} \), \( n \in \mathbb{N} \) is onto but not one-to-one. However, \( f \) is one-to-one and onto if we restrict its domain to \( [0,\infty) \). This is helpful in understanding \( n \)th root of a real number. So we have two cases:

**Case 1** When \( n \) is even.

In this case \( y^n = a \) is not meaningful when \( a < 0 \). So no such \( y \) exists when \( a < 0 \).

Assume that \( a > 0 \). If \( y \) is a solution to \( x^n = a \), then \( -y \) is also solution to \( x^n = a \).

**Case 2** When \( n \) is odd.

In this case no such problem arises as in Case 1. For \( y \in \mathbb{R} \), there is a unique \( x \in \mathbb{R} \) such that \( y = x^n \).

Based on the above observation we define radicals as follow.

### Definition 2.2

(i) For \( n \in \mathbb{N} \), \( n \) even, and \( b > 0 \), there is a unique \( a > 0 \) such that \( a^n = b \).

(ii) For \( n \in \mathbb{N} \), \( n \) odd, \( b \in \mathbb{R} \), there is a unique \( a \in \mathbb{R} \) such that \( a^n = b \).

In both cases \( a \) is called the \( n \)th root of \( b \) or radical and is denoted by \( b^{1/n} \) or \( \sqrt[n]{b} \).

(i) If \( n = 2 \), then \( n \)th root is called the square root; if \( n = 3 \), then it is called cube root.

(ii) Observe that the equation \( x^2 = a^2 \), has two solutions \( x = a \), \( x = -a \); but \( \sqrt{a^2} = |a| \).

(iii) Properties of exponents given above are still valid for radicals provided each of the individual terms are defined.

(iv) Note that for \( n \in \mathbb{N} \) and \( a \neq 0 \) we have

$$
\sqrt[n]{a^n} = \begin{cases}
a, & \text{if } n \text{ is odd} \\
|a|, & \text{if } n \text{ is even}
\end{cases}
$$

For example, \( \sqrt[4]{(-2)^4} = 16^{1/4} = 2 \), \( 343^{1/3} = 7 \) and \( (-1000)^{\frac{1}{3}} = -10 \).

For any rational \( r = \frac{m}{n} \), \( m \in \mathbb{Z} \), \( n \in \mathbb{N} \), with \( \gcd(m,n) = 1 \) and for \( a > 0 \) we define

$$
a^r = a^{\frac{m}{n}} = (a^{1/n})^m.
$$

For example, \( 49^{3/2} = (49^{1/2})^3 = 7^3 = 343 \). But \( (-49)^{3/2} \) has no meaning in real number system because there is no real number \( x \) such that \( x^2 = (-49)^3 \).

### 2.8.3 Exponential Function

Observe that for any \( a > 0 \) and \( x \in \mathbb{R} \), \( a^x \) can be defined. If \( a = 1 \), we define \( 1^x = 1 \). So we shall consider \( a^x \), \( x \in \mathbb{R} \) for \( 0 < a \neq 1 \). Here \( a^x \) is called exponential function with base \( a \). Note that \( a^x \) may not be defined if \( a < 0 \) and \( x = \frac{1}{m} \) for even \( m \in \mathbb{N} \). This is why we restrict to \( a > 0 \). Also, \( a^x > 0 \) for all \( x \in \mathbb{R} \). It does also satisfy the following:

### Properties of Exponential Function

For \( a, b > 0 \) and \( a \neq 1 \neq b \)

(i) \( a^{x+y} = a^x a^y \) for all \( x, y \in \mathbb{R} \)

(ii) \( \frac{a^x}{a^y} = a^{x-y} \) for all \( x, y \in \mathbb{R} \)

1. Let us consider \( f(x) = a^x \), \( x \in \mathbb{R} \) where \( a = 2 \). Now \( f(x) = 2^x \), \( x \in \mathbb{R} \). Let us show that \( f \) is one-to-one and onto. Suppose \( f(u) = f(v) \) for some \( u, v \in \mathbb{R} \). Then, we have \( 2^u = 2^v \), which implies that \( \frac{2^u}{2^v} = 1 \), \( \Rightarrow 2^{u-v} = 1 \). So, \( u - v = 0 \) and hence \( u = v \). Thus \( f \) is a one-to-one function.

**Figure 2.7: \( f(x) = 2^x \)**

From the graph it is clear that values of \( f(x) = 2^x \) increase as \( x \) values increase and the range of \( f \) is \( (0,\infty) \). So as \( 2^0 = 1 \), we have \( 2^x > 1 \) for all \( x > 0 \) and \( 2^x < 1 \) for all \( x < 0 \). Observe that \( f : \mathbb{R} \to (0,\infty) \) is onto.

2. Let us consider \( a = \frac{1}{2} \). Let \( g(x) = \left(\frac{1}{2}\right)^x = \frac{1}{2^x} \), \( x \in \mathbb{R} \).

From the graph it is clear that the values of \( g(x) = \left(\frac{1}{2}\right)^x \) decrease as \( x \) values increase and \( g(\mathbb{R}) = (0,\infty) \). Also, \( g(0) = 1 \) we have \( g(x) > 1 \) for all \( x < 0 \) and \( g(x) < 1 \) for all \( x > 0 \).

**Remark:** Exactly same arguments as above would show that an exponential function \( f(x) = a^x \), for any base \( 0 < a \neq 1 \), is one-to-one and onto with domain \( \mathbb{R} \) and codomain \( (0,\infty) \).

### A Special Exponential Function

Among all exponential functions, \( f(x) = e^x \), \( x \in \mathbb{R} \) is the most important one as it has applications in many areas like mathematics, science and economics. Then what is this \( e \)? The following illustration from compounding interest problem leads to the constant \( e \).

### Illustration

#### 2.8.3.1 Compound Interest

Recall that if \( P \) is the principal, \( r = \frac{\text{interest rate}}{100} \), \( n \) is the number of compounding periods in a year and \( t \) is the number of years, then

$$
A = P\left(1 + \frac{r}{n}\right)^{nt}
$$

gives the total amount after \( t \) years. If \( n = 4 \), then it is compounded quarterly (the interest is added to the existing principal for three months in a year). If \( n = 12 \), then compounded monthly, \( n = 365 \) means compounded daily. We can compound every hour, every minute etc. We know that if \( P \) and \( r \) are fixed and the number of compounding periods in a year increases, then the total amount also increases. Let us consider the case with \( P = 1 \), \( r = 1 \) and \( t = 1 \). Then, we have

$$
A_n = \left(1 + \frac{1}{n}\right)^n.
$$

We want to understand how big it gets as \( n \) gets really large. Let us make a table with different values of \( n = 10, 100, 10000, 100000, 100000000 \).

| \( n \) | \( A_n \) |
|--------|-----------|
| 10 | 2.593742460 |
| 100 | 2.704813829 |
| 10000 | 2.718145927 |
| 10000000 | 2.718268237 |
| 100000000 | 2.718281815 |

We notice that as \( n \) gets really large, \( A_n \) values seem to be getting closer to 2.718281815... Actually \( A_n \) values approach a real number \( e \), an irrational number. 2.718281815 is an approximation to \( e \). So the compound interest formula becomes

$$
A = Pe^{rt},
$$

where \( r \) is the interest rate and \( P \) is the principal and \( t \) is the number of years. This is called Continuous Compounding.

### Example 2.31

(i) Simplify: \( (x^{1/2}y^{-3})^{1/2} \); where \( x, y \geq 0 \)

(ii) Simplify: \( \sqrt{x^2 - 10x + 25} \).

**Solution:**

(i) Since \( x, y \geq 0 \), we have \( (x^{1/2}y^{-3})^{1/2} = x^{1/4}/y^{3/2} \).

(ii) Observe that \( \sqrt{x^2 - 10x + 25} = \sqrt{(x-5)^2} = |x-5| \).

### Example 2.32

Rationalize the denominator of \( \frac{\sqrt{5}}{(\sqrt{6} + \sqrt{2})} \).

**Solution:**

Multiplying both numerator and denominator by \( (\sqrt{6} - \sqrt{2}) \), we get

$$
\frac{\sqrt{5}}{(\sqrt{6} + \sqrt{2})} = \frac{\sqrt{5}(\sqrt{6} - \sqrt{2})}{(\sqrt{6} + \sqrt{2})(\sqrt{6} - \sqrt{2})} = \frac{(\sqrt{30} - \sqrt{10})}{4}.
$$

### Example 2.33

Find the square root of \( 7 - 4\sqrt{3} \).

**Solution:**

Let \( \sqrt{7 - 4\sqrt{3}} = a + b\sqrt{3} \) where \( a, b \) are rationals. Squaring on both sides, we get

$$
7 - 4\sqrt{3} = a^2 + 3b^2 + 2ab\sqrt{3}.
$$

So, \( a^2 + 3b^2 = 7 \) and \( 2ab = -4 \).

Therefore \( a = -2/b \). From \( a^2 + 3b^2 = 7 \), we get \( (-2/b)^2 + 3b^2 = 7 \), which gives

$$
\frac{4}{b^2} + 3b^2 = 7 \quad \text{or} \quad 3b^4 - 7b^2 + 4 = 0.
$$

Solving for \( b^2 \) we get

$$
b^2 = \frac{7 \pm \sqrt{49 - 48}}{6},
$$

which gives \( b^2 = 1 \) or \( b^2 = \frac{4}{3} \).

Thus, \( b = \pm 1 \) or \( b = \pm \frac{2}{\sqrt{3}} \). Since \( b \) is rational, we have \( b = \pm 1 \) and hence the corresponding values of \( a \) are \( \mp 2 \). Since \( \sqrt{7 - 4\sqrt{3}} > 0 \), we have

$$
\sqrt{7 - 4\sqrt{3}} = 2 - \sqrt{3}.
$$

It is not always possible to express square roots of \( u + v\sqrt{b} \) where \( u, v \) are rationals, in the form \( x + y\sqrt{b} \) with \( x, y \) rationals. For example, the square root of \( 1 + \sqrt{2} \) is not of the form \( a + b\sqrt{2} \) with \( a, b \) rationals.

## Exercise 2.11

1. Simplify:

   (i) \( (125)^{\frac{2}{3}} \)

   (ii) \( 16^{\frac{-3}{4}} \)

   (iii) \( (-1000)^{\frac{-2}{3}} \)

   (iv) \( (3^{-6})^{\frac{1}{3}} \)

   (v) \( \frac{27^{\frac{-2}{3}}}{27^{\frac{-1}{3}}} \)

2. Evaluate \( \left((256)^{-1/2}\right)^{\frac{-1}{4}} \).

3. If \( (x^{1/2} + x^{-1/2})^2 = \frac{9}{2} \), then find the value of \( (x^{1/2} - x^{-1/2}) \) for \( x > 1 \).

4. Simplify and hence find the value of \( n \): \( \frac{3^{2n}9^{2}3^{-n}}{3^{3n}} = 27 \).

5. Find the radius of the spherical tank whose volume is \( \frac{32\pi}{3} \) units.

6. Simplify by rationalising the denominator: \( \frac{7 + \sqrt{6}}{3 - \sqrt{2}} \).

7. Simplify:

   $$
   \frac{1}{3 - \sqrt{8}} - \frac{1}{\sqrt{8} - \sqrt{7}} + \frac{1}{\sqrt{7} - \sqrt{6}} - \frac{1}{\sqrt{6} - \sqrt{5}} + \frac{1}{\sqrt{5} - 2}.
   $$

8. If \( x = \sqrt{2} + \sqrt{3} \) find \( \frac{x^2 + 1}{x^2 - 2} \).

## 2.9 Logarithm

We have seen that, with a base \( 0 < a \neq 1 \), the exponential function \( f(x) = a^x \) is defined on \( \mathbb{R} \) having range \( (0,\infty) \). We also observed that \( f(x) \) is a bijection, hence it has an inverse. We call this inverse function as logarithmic function and is denoted by \( \log_a(\cdot) \). Let us discuss this function further. Note that if \( f(x) \) takes \( x \) to \( y = a^x \), then \( \log_a(\cdot) \) takes \( y \) to \( x \). That is, for \( 0 < a \neq 1 \), we have

$$
y = a^x \quad \text{is equivalent to} \quad \log_a y = x.
$$

For example, since \( 3^4 = 81 \) we have \( \log_3(81) = 4 \). In other words, with fixed \( a \), given a real number \( y \), logarithm finds the exponent \( x \) satisfying \( a^x = y \). This is useful in addressing practical problems like, "how long will it take for certain investment to reach a fixed amount?" Logarithm is also very useful in multiplying very small or big numbers.

(i) Note that exponential function \( a^x \) is defined for all \( x \in \mathbb{R} \) and \( a^x > 0 \) and so \( \log_a(\cdot) \) defined only for positive real numbers.

(ii) Also, \( a^0 = 1 \) for any base \( a \) and hence \( \log_a(1) = 0 \) for any base \( a \).

### 2.9.1 Properties of Logarithm

(i) \( a^{\log_a x} = x \) for all \( x \in (0,\infty) \) and \( \log_a(a^y) = y \) for all \( y \in \mathbb{R} \)

(ii) For any \( x, y > 0 \), \( \log_a(xy) = \log_a x + \log_a y \). (Product Rule)

(iii) For any \( x, y > 0 \), \( \log_a\left(\frac{x}{y}\right) = \log_a x - \log_a y \). (Quotient Rule)

(iv) For any \( x > 0 \) and \( r \in \mathbb{R} \), \( \log_a x^r = r \log_a x \). (Power Rule)

(v) For any \( x > 0 \), with \( a \) and \( b \) as bases, \( \log_a x = \frac{\log_b x}{\log_b a} \). (Change of base formula)

**Proof.** Since exponential function with base \( a \) and logarithm function with base \( a \) are inverse of each other, (i) follows by using the definitions.

(ii) For \( x, y > 0 \) let \( \log_a x = u \), \( \log_a y = v \), and \( \log_a(xy) = w \). Rewriting these in the exponential form we obtain \( a^u = x \), \( a^v = y \), and \( a^w = xy \). So,

$$
a^w = xy = a^u a^v = a^{u+v};
$$

thus \( w = u + v \). Hence, we obtain \( \log_a(xy) = \log_a x + \log_a y \).

(iii) Let \( \log_a x = u \), \( \log_a y = v \), and \( \log_a \frac{x}{y} = w \). Then \( a^u = x \), \( a^v = y \) and \( a^w = \frac{x}{y} \). Hence,

$$
a^w = \frac{x}{y} = \frac{a^u}{a^v} = a^{u-v};
$$

which implies \( w = u - v \). Thus, we obtain \( \log_a\left(\frac{x}{y}\right) = \log_a x - \log_a y \).

(iv) Let \( \log_a x = u \). Then \( a^u = x \) and therefore, \( x^r = (a^u)^r = a^{ru} \). Thus, \( \log_a x^r = ru = r \log_a x \).

(v) Let \( \log_b x = v \). We have \( b^v = x \). Taking logarithm with base \( a \) on both sides we get

$$
\log_a b^v = \log_a x.
$$

On the other hand \( \log_a b^v = v \log_a b \) by the Power rule. Therefore, \( v \log_a b = \log_a x \). Hence

$$
\log_b x = \frac{\log_a x}{\log_a b},\ b > 0.
$$

This completes the proof.

### Remark:

(i) If \( a = 10 \), then the corresponding logarithmic function \( \log_{10} x \) is called the common logarithm.

(ii) If \( a = e \), (an irrational number, approximately equal to 2.718), then the corresponding logarithmic function \( \log_e x \) is called the natural logarithm. It is denoted by \( \ln x \). These above particular cases of logarithmic functions are used very much in other sciences and engineering. Particularly, the natural logarithm occurs very naturally. When we write \( \log x \) we mean \( \log_e x \).

(iii) If \( a = 2 \), then the corresponding logarithmic function \( \log_2 x \) called the binary logarithm, which is used in computer science.

### Example 2.34

Express \( \log_a 35 \) in terms of \( \log_a 5 \) and \( \log_a 7 \).

**Solution:**

\( \log_a 35 = \log_a(7 \times 5) = \log_a 7 + \log_a 5 \).

### Example 2.35

Compute \( \log_3 5 \cdot \log_{25} 27 \).

**Solution:**

$$
\log_3 5 \cdot \log_{25} 27 = \log_3 5 \cdot \log_{25} 3^3 = \log_3 5 \times 3 \log_{25} 3 = 3 \log_{25} 5 = \frac{3}{\log_5 25} = \frac{3}{2}.
$$

### Example 2.36

Given that \( \log_{10} 2 = 0.30103 \), \( \log_{10} 3 = 0.47712 \) (approximately), find the number of digits in \( 2^8 \cdot 3^{12} \).

**Solution:**

Suppose that \( N = 2^8 3^{12} \) has \( n+1 \) digits. Then \( N \) can be written as \( 10^n \times b \) where \( 1 \leq b < 10 \). Taking logarithm to the base 10, we get

$$
\log_{10} N = \log_{10}(10^n b) = n \log_{10} 10 + \log_{10} b = n + \log_{10} b.
$$

On the other hand,

$$
\log_{10} N = \log_{10}(2^8 3^{12}) = 8 \log_{10} 2 + 12 \log_{10} 3 = 8 \times 0.30103 + 12 \times 0.47712 = 8.13368.
$$

Thus, we get \( n + \log_{10} b = 8.13368 \). Since \( 1 \leq b < 10 \), the number of digits is 9.

### Example 2.37

Solve \( \log_3 x = 2 \).

**Solution:**

By definition, \( \log_3 x = 2 \) means \( 3^2 = x \), so \( x = 9 \).

### Example 2.38

Solve \( x^{\log_3 x} = 9 \).

**Solution:**

Let \( \log_3 x = y \). Then \( x = 3^y \) and so, \( (3^y)^y = 9 \), i.e., \( 3^{y^2} = 3^2 \). Thus, \( y^2 = 2 \), which implies \( y = \sqrt{2} \) or \( -\sqrt{2} \). Hence, \( x = 3^{\sqrt{2}} \) or \( 3^{-\sqrt{2}} \).

## Exercise 2.12

1. Let \( b > 0 \) and \( b \neq 1 \). Express \( y = b^x \) in logarithmic form. Also state the domain and range of the logarithmic function.

2. Compute \( \log_9 27 - \log_{27} 9 \).

3. Solve \( \log_8 x + \log_4 x + \log_2 x = 11 \).

4. Solve \( \log_4 2^{8x} = 2^{\log_2 8} \).

5. If \( a^2 + b^2 = 7ab \), show that \( \log \frac{a + b}{3} = \frac{1}{2}(\log a + \log b) \).

6. Prove \( \log \frac{a^2}{bc} + \log \frac{b^2}{ca} + \log \frac{c^2}{ab} = 0 \).

7. Prove that

$$
\log_{10} 2 + 16 \log_{10} \frac{16}{15} + 12 \log_{10} \frac{25}{24} + 7 \log_{10} \frac{81}{80} = 1.
$$

8. Prove \( \log_{a^2} a \cdot \log_{b^2} b \cdot \log_{c^2} c = \frac{1}{8} \).

9. Prove \( \log a + \log a^2 + \log a^3 + \dots + \log a^n = \frac{n(n+1)}{2} \log a \).

10. If \( \frac{\log x}{y - z} = \frac{\log y}{z - x} = \frac{\log z}{x - y} \), then prove that \( xyz = 1 \).

11. Solve \( \log_2 x - 3 \log_{\frac{1}{2}} x = 6 \).

12. Solve \( \log_{5-x}(x^2 - 6x + 65) = 2 \).

## 2.10 Application of Algebra in Real Life

Algebra is used in many aspects of life. Financial planning is an area in daily life where algebra is used. Algebra concepts are used to calculate interest rates by bankers and as well as for calculating loan repayments. They are used to predict growth of money. Physical fitness is another area where calculations are made to determine the right amount of food intake for an individual taking into consideration such as the height, body mass of the person etc. Doctors use algebra in measuring drug dosage depending on age and weight of an individual. Architects depend on algebra to design buildings while civil engineers use it to design roads, bridges and tunnels. Algebra is needed to convert items to scale so that the structures designed have the correct proportions. It is used to programme computers and phones. Let us see some examples. Because of the extraordinary range of sensitivity of the human ear (a range of over 1000 million millions to one), it is useful to use logarithmic scale to measure sound intensity over this range. The unit of measure decibel is named after the inventor of the telephone Alexander Graham Bell.

If we know the population in the world today, the growth, which is rapid, can be measured by approximating to an exponential function. The radioactive carbon-14 is an organism which decays according to an exponential formula.

## Exercise 2.13

Choose the correct or the most suitable answer.

1. If \( |x + 2| \leq 9 \), then \( x \) belongs to

   (1) \( (-\infty, -7) \cup (11, \infty) \)

   (2) \( (-11, 7) \)

   (3) \( (-\infty, -7) \cup [11, \infty) \)

   (4) \( (-11, 7) \)

2. Given that \( x, y \) and \( b \) are real numbers \( x < y \), \( b > 0 \), then

   (1) \( xb < yb \)

   (2) \( xb > yb \)

   (3) \( xb \leq yb \)

   (4) \( \frac{x}{b} \geq \frac{y}{b} \)

3. If \( \frac{|x - 2|}{x - 2} \geq 0 \), then \( x \) belongs to

   (1) \( [2, \infty) \)

   (2) \( (2, \infty) \)

   (3) \( (-\infty, 2) \)

   (4) \( (-2, \infty) \)

4. The solution of \( 5x - 1 < 24 \) and \( 5x + 1 > -24 \) is

   (1) \( (4,5) \)

   (2) \( (-5, -4) \)

   (3) \( (-5,5) \)

   (4) \( (-5,4) \)

5. The solution set of the following inequality \( |x - 1| \geq |x - 3| \) is

   (1) \( [0,2] \)

   (2) \( [2, \infty) \)

   (3) \( (0,2) \)

   (4) \( (-\infty, 2) \)

6. The value of \( \log_{\sqrt{2}} 512 \) is

   (1) 16

   (2) 18

   (3) 9

   (4) 12

7. The value of \( \log_3 \frac{1}{81} \) is

   (1) \( -2 \)

   (2) \( -8 \)

   (3) \( -4 \)

   (4) \( -9 \)

8. If \( \log_{\sqrt{x}} 0.25 = 4 \), then the value of \( x \) is

   (1) 0.5

   (2) 2.5

   (3) 1.5

   (4) 1.25

9. The value of \( \log_a b \cdot \log_b c \cdot \log_c a \) is

   (1) 2

   (2) 1

   (3) 3

   (4) 4

10. If 3 is the logarithm of 343, then the base is

    (1) 5

    (2) 7

    (3) 6

    (4) 9

11. Find \( a \) so that the sum and product of the roots of the equation \( 2x^2 + (a - 3)x + 3a - 5 = 0 \) are equal is

    (1) 1

    (2) 2

    (3) 0

    (4) 4

12. If \( a \) and \( b \) are the roots of the equation \( x^2 - kx + 16 = 0 \) and satisfy \( a^2 + b^2 = 32 \), then the value of \( k \) is

    (1) 10

    (2) \( -8 \)

    (3) \( -8, 8 \)

    (4) 6

13. The number of solutions of \( x^2 + |x - 1| = 1 \) is

    (1) 1

    (2) 0

    (3) 2

    (4) 3

14. The equation whose roots are numerically equal but opposite in sign to the roots of \( 3x^2 - 5x - 7 = 0 \) is

    (1) \( 3x^2 - 5x - 7 = 0 \)

    (2) \( 3x^2 + 5x - 7 = 0 \)

    (3) \( 3x^2 - 5x + 7 = 0 \)

    (4) \( 3x^2 + x - 7 = 0 \)

15. If 8 and 2 are the roots of \( x^2 + ax + c = 0 \) and 3, 3 are the roots of \( x^2 + dx + b = 0 \), then the roots of the equation \( x^2 + ax + b = 0 \) are

    (1) 1, 2

    (2) \( -1, 1 \)

    (3) 9, 1

    (4) \( -1, 2 \)

16. If \( a \) and \( b \) are the real roots of the equation \( x^2 - kx + c = 0 \), then the distance between the points \( (a,0) \) and \( (b,0) \) is

    (1) \( \sqrt{k^2 - 4c} \)

    (2) \( \sqrt{4k^2 - c} \)

    (3) \( \sqrt{4c - k^2} \)

    (4) \( \sqrt{k - 8c} \)

17. If \( \frac{kx}{(x + 2)(x - 1)} = \frac{2}{x + 2} + \frac{1}{x - 1} \), then the value of \( k \) is

    (1) 1

    (2) 2

    (3) 3

    (4) 4

18. If \( \frac{1 - 2x}{3 + 2x - x^2} = \frac{A}{3 - x} + \frac{B}{x + 1} \), then the value of \( A + B \) is

    (1) \( \frac{-1}{2} \)

    (2) \( \frac{-2}{3} \)

    (3) \( \frac{1}{2} \)

    (4) \( \frac{2}{3} \)

19. The number of roots of \( (x + 3)^4 + (x + 5)^4 = 16 \) is

    (1) 4

    (2) 2

    (3) 3

    (4) 0

20. The value of \( \log_3 11 \cdot \log_{11} 13 \cdot \log_{13} 15 \cdot \log_{15} 27 \cdot \log_{27} 81 \) is

    (1) 1

    (2) 2

    (3) 3

    (4) 4

## Summary

- \( \pi \) and \( \sqrt{p} \), where \( p \) is a prime number, are some irrational numbers.

- \( |x - a| = r \) if and only if \( r \geq 0 \) and \( x - a = \pm r \)

- \( |x - a| \leq r \) if and only if \( -r \leq x - a \leq r \) or \( a - r \leq x \leq a + r \)

- \( |x - a| > r \) implies \( x < a - r \) and \( x > a + r \) (or) \( x \in (-\infty, a - r) \cup (a + r, \infty) \)

- Inequalities, in general, have more than one solution.

- The nature of roots of \( ax^2 + bx + c = 0 \) is determined by the discriminant \( D = b^2 - 4ac \)

- A real number \( a \) is a zero of a polynomial function \( f(x) \) if and only if \( (x - a) \) is a factor of \( f(x) \)

- If degree of \( f(x) \) is less than the degree of \( g(x) \), then \( \frac{f(x)}{g(x)} \) can be written as sum of its partial fractions.

- In general exponential functions and logarithmic functions are inverse functions to each other.