---
title: 'differential calculus limits and continuity'
weight: 9
---

# Chapter 9: Limits and Continuity

## 9.1 Introduction

Calculus is about rates of change. Rates of change occur in all the sciences. A mathematician is interested in measuring the rate of change of the deviations of a straight line at a point on a curve, while a physicist is interested in the rate of change of displacement, and the velocity of a moving object. A chemist wants to know the rate of a chemical reaction that would result in the formation of one or more substances (called products) from one or more starting materials (called reactants).

A biologist would like to analyse the changes that take place in the number of individuals in an animal population or plant population at any time; he would also want to know the rate at which blood flows through a blood vessel, such as a vein or artery and the part of the vessel / artery in which this flow is lowest or highest.

An economists also studies marginal demand, marginal revenue, and marginal profit, which are drawn from rates of change (that is, derivatives) of this demand, revenue and profit functions.

A geologist is interested in knowing the rate at which an intruded body of molten rock cools by conduction of heat into surrounding rocks. An engineer wants to know the rate at which water flows into or out of a reservoir. An urban geographer is interested in the rate of change of population density in a city with the expansion of the city. A meteorologist is concerned with the rate of change of atmospheric pressure with respect to height.

In psychology, those interested in learning theory, study the so called learning curve, which graphs the performance of someone learning a skill as a function of the training time. Of particular interest is the rate at which performance improves as time passes.

When we enter a darkened room, our eyes adjust to the reduced level of light by increasing the size of our pupils, allowing more light to enter the eyes and making objects around us easier to see. By contrast, when we enter a brightly lit room, our pupils contract, reducing the amount of light entering the eyes, as too much light would overload our visual system. Researchers study such mechanisms based on limits.

Velocity, density, current, power and temperature gradient in physics; rate of reaction and compressibility in chemistry, rate of growth and blood velocity in biology; marginal cost and marginal profit in economics; rate of heat flow in geology; rate of improvement of performance in psychology - these are all cases of a single mathematical concept, the derivative.

This is an illustration of the fact that part of the power of mathematics lies in its abstractness. A single abstract mathematical concept (such as derivatives) can have different interpretations in each of the sciences. When we develop the properties of the mathematical concept, we can then apply these results to all of the sciences. This is much more efficient than developing properties of special concepts in each separate science.

One of the greatest creations of the ancient past was Euclidean geometry. This monumental work was not matched in importance until the discovery of calculus almost two thousand years later.

Calculus was created independently in England by Sir Isaac Newton (1642-1727) and in Germany by Gottfried Wilhelm Leibnitz (1646-1716) in the last quarter of the seventeenth century.

Newton's interest in mathematics began with his study of two of the great books on mathematics at that time: Euclid's Elements and Descartes' La Geometrie. He also became aware of the work of the great scientists who preceded him, including Galileo and Fermat.

By the end of 1664, Newton seemed to have mastered all the mathematical knowledge of the time and had begun adding substantially to it. In 1665, he began his study of the rates of change or flexions, of quantities, such as distances or temperatures that varied continuously. The result of this study was what we today call differential calculus. All who study mathematics today stand on Isaac Newton's shoulders.

Many of Leibnitz's mathematical papers appeared in the journal 'Acta Eruditorum' which he cofounded in 1682. This journal contained his work on calculus and led to the bitter controversy with Newton over who first discovered calculus. Leibnitz was the first to publish the important results on calculus and was the first to use the notation that has now become standard.

Augustin-Louis Cauchy (1789-1857), born in Paris in 1789 is considered to be the most outstanding mathematical analyst of the first half of the nineteenth century. Cauchy made many contributions to calculus. In his 1829 text book 'Lecons le calcul differential', he gave the first reasonably clear definition of a limit and was the first to define the derivative as the limit of the difference quotient,

\[
\frac{\Delta y}{\Delta x} = \frac{f(x + \Delta x) - f(x)}{\Delta x}.
\]

Karl Weierstrass (1815-1897), a German mathematician gave the precise definition \( \epsilon - \delta \) definition) of the concepts of limit, continuity and differentiability.

### What is Calculus?

Calculus is the mathematics of ratio of change of quantities. It is also the mathematics of tangent lines, slopes, areas, volumes, arc lengths, centroids, curvatures and a variety of other concepts that have enabled scientists, engineers and economists to model real-life situations.

Although pre calculus mathematics deals with velocities, accelerations, tangent lines, slopes and so on, there is a fundamental difference between pre calculus mathematics and calculus. Pre calculus mathematics is more static, whereas calculus is more dynamic. Here are some examples:

- An object travelling at a constant velocity can be analyzed with pre calculus mathematics. To analyse the velocity of an accelerating object, you need calculus.
- The slope of a line can be analysed with pre calculus mathematics. To analyse the slope of a curve, you need calculus.
- A tangent line to a circle can be analysed with pre calculus mathematics. To analyse a line tangential to a general graph, you need calculus.
- The area of a rectangle can be analysed with pre calculus mathematics. To analyse the area under a general curve, you need calculus.

Each of these situations involves the same general strategy, the reformulation of pre calculus mathematics through the use of a limit process. So, one way to answer the question 'What is calculus?' is to say that calculus is a 'limit machine' that involves three stages. The first stage is pre calculus mathematics such as the slope of a line or the area of a rectangle. The second stage is the limit process and the third stage is a new calculus formulation, such as a derivative or integral.

| Pre calculus Mathematics | → | Limit Process | → | Calculus |
|-------------------------|---|---------------|---|----------|

It is cautioned that those who try to learn calculus as if it were simply a collection of new formulae rather than as a process, will miss a great deal of understanding, self-confidence and satisfaction.

## Learning Objectives

On completion of this chapter, the students are expected to

- visualize the concept of limit / continuity through geometric process.
- relate the concept of limit / continuity with every day life activities.
- assimilate limit / continuity as the heart and spirit of calculus.
- understand limit / continuity as an operation (operator) to measure / quantify / mathematize changes in physical world.
- concretize the concept of limit / continuity via illustrations of real life related situations.

## 9.2 Limits

### 9.2.1 The calculation of limits

The notion of a limit, which we will discuss extensively in this chapter, plays a central role in calculus and in much of modern mathematics. However, although mathematics dates back over three thousand years, limits were not really understood until the monumental work of the great French mathematician Augustin-Louis Cauchy and Karl Weierstrass in the nineteenth century, the age of rigour in mathematics.

In this section we define limit and show how limits can be calculated.

#### Illustration 9.1

We begin by looking at the function \( y = f(x) = x^{2} + 3 \). Note that \( f \) is a function from \( \mathbb{R} \to \mathbb{R} \).

Let us investigate the behaviour of this function near \( x = 2 \). We can use two sets of \( x \) values: one set that approaches 2 from the left (values less than 2) and one set that approaches 2 from the right (values greater than 2) as shown in the table.

| x approaches 2 from the left | | | | | x approaches 2 from the right | | | | |
|----------------------------|---|---|---|---|-----------------------------|---|---|---|---|
| \( x \) | 1.7 | 1.9 | 1.95 | 1.99 | 1.999 | 2.0001 | 2.001 | 2.01 | 2.05 | 2.1 | 2.3 |
| \( f(x) \) | 5.89 | 6.61 | 6.8025 | 6.9601 | 6.996001 | 7.0040001 | 7.004001 | 7.0401 | 7.2025 | 7.41 | 8.29 |

It appears from the table that as \( x \) gets close to \( x = 2 \), \( f(x) = x^{2} + 3 \) gets close to 7. This is not surprising since if we now calculate \( f(x) \) at \( x = 2 \) we obtain \( f(2) = 2^{2} + 3 = 7 \).

In order to guess at this limit, we didn't have to evaluate \( x^{2} + 3 \) at \( x = 2 \).

That is, as \( x \) approaches 2 from either the left (values lower than 2) or right (values higher than 2) the functional values \( f(x) \) are approaching 7 from either side; that is, when \( x \) is near 2, \( f(x) \) is near 7. The above situation is described in a condensed form:

The value 7 is the left limit of \( f(x) \) as \( x \) approaches 2 from the left as well as 7 is the right limit of \( f(x) \) as \( x \) approaches 2 from the right and write: \( f(x) \to 7 \) as \( x \to 2^{-} \) and \( f(x) \to 7 \) as \( x \to 2^{+} \)

or

\[
\lim_{x \to 2^{-}} f(x) = 7 \quad \text{and} \quad \lim_{x \to 2^{+}} f(x) = 7.
\]

Note also that \( \lim_{x \to 2^{-}} f(x) = 7 = \lim_{x \to 2^{+}} f(x) \). The common value is written as \( \lim_{x \to 2} f(x) = 7 \).

We also observe that the limit is a definite real number. Here, definiteness means that \( \lim_{x \to 2^{-}} f(x) \) and \( \lim_{x \to 2^{+}} f(x) \) are the same and \( \lim_{x \to 2^{-}} f(x) = \lim_{x \to 2^{+}} f(x) \) is a unique real number.

#### Illustration 9.2

Next, let us look at the rational function \( f(x) = \frac{16 - x^{2}}{4 + x} \).

The domain of this function is \( \mathbb{R} \setminus \{-4\} \). Although \( f(-4) \) is not defined, nonetheless, \( f(x) \) can be calculated for any value of \( x \) near \( -4 \) because the symbol \( \lim_{x \to -4} \left( \frac{16 - x^{2}}{4 + x} \right) \) says that we consider values of \( x \) that are close to \( -4 \) but not equal to \( -4 \). The table below gives the values of \( f(x) \) for values of \( x \) that approach \( -4 \).

| \( x (< -4) \) (\( x \to -4^{-} \)) | \( f(x) \) | \( x (> -4) \) (\( x \to -4^{+} \)) | \( f(x) \) |
|----------------------------------|-----------|-----------------------------------|-----------|
| -4.1 | 8.1 | -3.9 | 7.9 |
| -4.01 | 8.01 | -3.99 | 7.99 |
| -4.001 | 8.001 | -3.999 | 7.999 |

For \( x \neq -4 \), \( f(x) \) can be simplified by cancellation:

\[
f(x) = \frac{16 - x^{2}}{4 + x} = \frac{(4 + x)(4 - x)}{(4 + x)} = 4 - x.
\]

As seen in Fig.9.2, the graph of \( f(x) \) is essentially the graph of \( y = 4 - x \) with the exception that the graph of \( f \) has a hole (puncture) at the point that corresponds to \( x = -4 \). As \( x \) gets closer and closer to \( -4 \), represented by the two arrow heads on the \( x \)-axis, the two arrow heads on the \( y \)-axis simultaneously get closer and closer to the number 8.

Here, note that

\[
\lim_{x \to -4^{-}} f(x) = 8 = \lim_{x \to -4^{+}} f(x) \quad \text{and hence} \quad \lim_{x \to -4} f(x) = \lim_{x \to -4} \frac{16 - x^{2}}{4 + x} = 8.
\]

In Illustration 9.2, note that the function is not defined at \( x = -4 \) and yet \( f(x) \) appears to be approaching a limit as \( x \) approaches \( -4 \). This often happens, and it is important to realise that the existence or non-existence of \( f(x) \) at \( x = -4 \) has no bearing on the existence of the limit of \( f(x) \) as \( x \) approaches \( -4 \).

#### Illustration 9.3

Now let us consider a function different from Illustrations 9.1 and 9.2.

Let \( f(x) = \frac{|x|}{x} \).

\( x = 0 \) does not belong to the domain of this function, \( \mathbb{R} \setminus \{0\} \). Look at the graph of this function. From the graph one can see that for positive values of \( x \),

\[
\frac{|x|}{x} = \frac{x}{x} = +1
\]

and for negative \( x \) values,

\[
\frac{|x|}{x} = \frac{-x}{x} = -1.
\]

This means that no matter how close \( x \) gets to 0 (in a small neighbourhood of 0), there will be both positive and negative \( x \) values that yield \( f(x) = 1 \) and \( f(x) = -1 \).

That is, \( \lim_{x \to 0^{-}} f(x) = -1 \) and \( \lim_{x \to 0^{+}} f(x) = +1 \).

This means that the limit does not exist. Of course, for any other value of \( x \), there is a limit.

### 9.2.2 One sided limits

**Definition 9.2**

We say that the left-hand limit of \( f(x) \) as \( x \) approaches \( x_{0} \) (or the limit of \( f(x) \) as \( x \) approaches \( x_{0} \) from the left) is equal to \( l_{1} \) if we can make the values of \( f(x) \) arbitrarily close to \( l_{1} \) by taking \( x \) to be sufficiently close to \( x_{0} \) and less than \( x_{0} \). It is symbolically written as \( f(x_{0}^{-}) = \lim_{x \to x_{0}^{-}} f(x) = l_{1} \).

Similarly, we define the right hand limit.

We say that the right-hand limit of \( f(x) \) as \( x \) approaches \( x_{0} \) (or the limit of \( f(x) \) as \( x \) approaches \( x_{0} \) from the right) is equal to \( l_{2} \) if we can make the values of \( f(x) \) arbitrarily close to \( l_{2} \) by taking \( x \) to be sufficiently close to \( x_{0} \) and greater than \( x_{0} \). It is symbolically written as \( f(x_{0}^{+}) = \lim_{x \to x_{0}^{+}} f(x) = l_{2} \).

Thus the symbols \( x \to x_{0}^{-} \) and \( x \to x_{0}^{+} \) mean that we consider only \( x < x_{0} \) and \( x > x_{0} \) respectively.

From the definitions of one sided limits and that of the limit of \( f(x) \) we have the following:

\[
\lim_{x \to x_{0}} f(x) = L \quad \text{iff} \quad \lim_{x \to x_{0}^{-}} f(x) = L = \lim_{x \to x_{0}^{+}} f(x).
\]

Thus, when we say \( \lim_{x \to x_{0}} f(x) \) exists, it is understood that \( L \) is a unique real number. If any one of the above conditions fails then we say, the limit of \( f(x) \) as \( x \) approaches \( x_{0} \) does not exist.

We remark that the existence of one sided limits is weaker than the existence of limits.

Sometimes it is very useful to use the following in computing left and right limits. For \( h > 0 \),

\[
f(x_{0}^{-}) = \lim_{h \to 0} f(x_{0} - h), \quad f(x_{0}^{+}) = \lim_{h \to 0} f(x_{0} + h).
\]

Note that \( f(x_{0}^{-}) \) and \( f(x_{0}^{+}) \) stand for the left and right limiting values. But \( f(x_{0}) \) is the value of the function at \( x = x_{0} \).

### Example 9.1

Calculate \( \lim_{x \to 0} |x| \).

**Solution**

Recall that \( |x| = \begin{cases} -x & \text{if } x < 0 \\ 0 & \text{if } x = 0 \\ x & \text{if } x > 0 \end{cases} \)

If \( x > 0 \), then \( |x| = x \), which tends to 0 as \( x \to 0 \) from the right of 0. That is, \( \lim_{x \to 0^{+}} |x| = 0 \).

If \( x < 0 \), then \( |x| = -x \) which again tends to 0 as \( x \to 0 \) from the left of 0. That is, \( \lim_{x \to 0^{-}} |x| = 0 \).

Thus, \( \lim_{x \to 0^{-}} |x| = 0 = \lim_{x \to 0^{+}} |x| \).

Hence \( \lim_{x \to 0} |x| = 0 \).

### Example 9.2

Consider the function \( f(x) = \sqrt{x}, x \geq 0 \). Does \( \lim_{x \to 0} f(x) \) exist?

**Solution**

No. \( f(x) = \sqrt{x} \) is not even defined for \( x < 0 \). Therefore as \( x \to 0^{-} \), \( \lim_{x \to 0^{-}} \sqrt{x} \) does not exist. However, \( \lim_{x \to 0^{+}} \sqrt{x} = 0 \). Therefore \( \lim_{x \to 0} \sqrt{x} \) does not exist.

Does \( \lim_{x \to 0^{-}} \log x \) exist? Look at the graph of \( \log x \) for the answer.

### Example 9.3

Evaluate \( \lim_{x \to 2^{-}} \lfloor x \rfloor \) and \( \lim_{x \to 2^{+}} \lfloor x \rfloor \).

**Solution**

The greatest integer function \( f(x) = \lfloor x \rfloor \) is defined as the greatest integer lesser than or equal to \( x \).

From the graph of this function it is clear that \( \lim_{x \to 2^{-}} \lfloor x \rfloor = 1 \) and \( \lim_{x \to 2^{+}} \lfloor x \rfloor = 2 \).

Moreover, for any integer \( n \), \( \lim_{x \to n^{-}} \lfloor x \rfloor = n - 1 \) and \( \lim_{x \to n^{+}} \lfloor x \rfloor = n \).

Does \( \lim_{x \to n} \lfloor x \rfloor \) exist? Look at the graph of \( \lfloor x \rfloor \) for the answer.

### Example 9.4

\[
f(x) = \begin{cases}
\frac{|x|}{x}, & x \neq 0 \\
0, & x = 0
\end{cases}
\]

Verify the existence of limit as \( x \to 0 \).

**Solution**

Clearly \( \lim_{x \to 0^{-}} f(x) = -1 \) and \( \lim_{x \to 0^{+}} f(x) = 1 \). Since these limits are different, \( \lim_{x \to 0} f(x) \) does not exist.

### Example 9.5

Check if \( \lim_{x \to -5} f(x) \) exists or not, where \( f(x) = \frac{|x + 5|}{x + 5}, x \neq -5 \).

**Solution**

(i) \( f(-5^{-}) \): For \( x < -5 \), \( |x + 5| = -(x + 5) \). Thus \( f(-5^{-}) = \lim_{x \to -5^{-}} \frac{-(x + 5)}{(x + 5)} = -1 \).

(ii) \( f(-5^{+}) \): For \( x > -5 \), \( |x + 5| = (x + 5) \). Thus \( f(-5^{+}) = \lim_{x \to -5^{+}} \frac{(x + 5)}{(x + 5)} = 1 \).

Note that \( f(-5^{-}) \neq f(-5^{+}) \). Hence the limit does not exist.

### Example 9.6

Test the existence of the limit, \( \lim_{x \to 1} \frac{4|x - 1| + x - 1}{|x - 1|}, x \neq 1 \).

**Solution**

For \( x > 1 \), \( |x - 1| = x - 1 \) and \( f(1^{+}) = \lim_{x \to 1^{+}} \frac{4(x - 1) + x - 1}{x - 1} = \lim_{x \to 1^{+}} \frac{5(x - 1)}{(x - 1)} = 5 \).

For \( x < 1 \), \( |x - 1| = -(x - 1) \), and \( f(1^{-}) = \lim_{x \to 1^{-}} \frac{-4(x - 1) + (x - 1)}{-(x - 1)} = \lim_{x \to 1^{-}} \frac{3(x - 1)}{(x - 1)} = 3 \).

Thus \( f(1^{-}) \neq f(1^{+}) \) and hence the limit does not exist.

## EXERCISE 9.1

In problems 1-6, using the table estimate the value of the limit.

(1) \( \lim_{x \to 2} \frac{x - 2}{x^{2} - x - 2} \)

| x | 1.9 | 1.99 | 1.999 | 2.001 | 2.01 | 2.1 |
|---|---|---|---|---|---|---|
| f(x) | 0.344820 | 0.334440 | 0.333440 | 0.333222 | 0.332220 | 0.322258 |

(2) \( \lim_{x \to 2} \frac{x - 2}{x^{2} - 4} \)

| x | 1.9 | 1.99 | 1.999 | 2.001 | 2.01 | 2.1 |
|---|---|---|---|---|---|---|
| f(x) | 0.25641 | 0.25062 | 0.250062 | 0.24993 | 0.24937 | 0.24390 |

(3) \( \lim_{x \to 0} \frac{\sqrt{x + 3} - \sqrt{3}}{x} \)

| x | -0.1 | -0.01 | -0.001 | 0.001 | 0.01 | 0.1 |
|---|---|---|---|---|---|---|
| f(x) | 0.2911 | 0.2891 | 0.2886 | 0.2886 | 0.2885 | 0.28631 |

(4) \( \lim_{x \to -3} \frac{\sqrt{1 - x} - 2}{x + 3} \)

| x | -3.1 | -3.01 | -3.00 | -2.999 | -2.99 | -2.9 |
|---|---|---|---|---|---|---|
| f(x) | -0.24845 | -0.24984 | -0.24998 | -0.25001 | -0.25015 | -0.25158 |

(5) \( \lim_{x \to 0} \frac{\sin x}{x} \)

| x | -0.1 | -0.01 | -0.001 | 0.001 | 0.01 | 0.1 |
|---|---|---|---|---|---|---|
| f(x) | 0.99833 | 0.99998 | 0.99999 | 0.99999 | 0.99998 | 0.99833 |

(6) \( \lim_{x \to 0} \frac{\cos x - 1}{x} \)

| x | -0.1 | -0.01 | -0.001 | 0.0001 | 0.01 | 0.1 |
|---|---|---|---|---|---|---|
| f(x) | 0.04995 | 0.0049999 | 0.0004999 | -0.0004999 | -0.004999 | -0.04995 |

In exercise problems 7 - 15, use the graph to find the limits (if it exists). If the limit does not exist, explain why?

(7) \( \lim_{x \to 3} (4 - x) \)

(8) \( \lim_{x \to 1} (x^{2} + 2) \)

(9) \( \lim_{x \to 1} f(x) \) where \( f(x) = \begin{cases} x + 2, & x \neq 1 \\ 4, & x = 1 \end{cases} \)

(10) \( \lim_{x \to 1} f(x) \) where \( f(x) = \begin{cases} x - 2, & x < 1 \\ 2x - 3, & x \geq 1 \end{cases} \)

(11) \( \lim_{x \to 3} \frac{1}{x - 3} \)

(12) \( \lim_{x \to 5} \frac{|x - 5|}{x - 5} \)

(13) \( \lim_{x \to 1} \sin \pi x \)

(14) \( \lim_{x \to 0} \sec x \)

(15) \( \lim_{x \to \frac{\pi}{2}} \tan x \)

(16) Sketch the graph of \( f \), then identify the values of \( x_{0} \) for which \( \lim_{x \to x_{0}} f(x) \) exists.

(i) \( f(x) = \begin{cases} x^{2}, & x \leq 2 \\ 8 - 2x, & 2 < x < 4 \\ 4, & x \geq 4 \end{cases} \)

(ii) \( f(x) = \begin{cases} \sin x, & x < 0 \\ 1 - \cos x, & 0 \leq x \leq \pi \\ \cos x, & x > \pi \end{cases} \)

(17) Sketch the graph of a function \( f \) that satisfies the given values:
(i) \( f(0) \) is undefined, \( \lim_{x \to 0} f(x) = 4 \), \( f(2) = 6 \), \( \lim_{x \to 2} f(x) = 3 \)
(ii) \( f(-2) = 0 \), \( f(2) = 0 \), \( \lim_{x \to -2} f(x) = 0 \), \( \lim_{x \to 2} f(x) \) does not exist.

(18) Write a brief description of the meaning of the notation \( \lim_{x \to 8} f(x) = 25 \).

(19) If \( f(2) = 4 \), can you conclude anything about the limit of \( f(x) \) as \( x \) approaches 2?

(20) If the limit of \( f(x) \) as \( x \) approaches 2 is 4, can you conclude anything about \( f(2) \)? Explain reasoning.

(21) Evaluate: \( \lim_{x \to 3} \frac{x^{2} - 9}{x - 3} \) if it exists by finding \( f(3^{-}) \) and \( f(3^{+}) \).

(22) Verify the existence of \( \lim_{x \to 1} f(x) \), where \( f(x) = \begin{cases} \frac{|x - 1|}{x - 1}, & \text{for } x \neq 1 \\ 0, & \text{for } x = 1 \end{cases} \)

### 9.2.3 Theorems on limits

The intention of the informal discussion in the earlier section was to have an intuitive grasp of existence or non existence of the limit. However, it is neither desirable nor practical in every instance, to reach a conclusion about the existence of a limit based on a graph or table of functional values. We must be able to evaluate a limit, or discern its non existence, in a somewhat mechanical fashion. The theorems that we shall consider in this section establish such a means. The proofs of these theorems are more of technical and are beyond the scope of this textbook.

In Illustration 9.1, we concluded that \( \lim_{x \to 2} (x^{2} + 3) = 2^{2} + 3 = 7 \). That is, the limit of \( f(x) = x^{2} + 3 \) as \( x \) tends to 2 is equal to \( f(x) \) evaluated at \( x = 2 \). [That is, \( f(2) \)]. However, this process of evaluation, as noted earlier, will not always work because \( f(x) \) may not even be defined at \( x_{0} \). Nevertheless, it is true that if \( f \) is a polynomial, then it is always possible to calculate the limit by evaluation.

**Theorem 9.1**

Let \( P(x) = a_{0} + a_{1}x + a_{2}x^{2} + \dots + a_{n}x^{n} \) be a polynomial, where \( a_{0}, a_{1}, \dots, a_{n} \) are real numbers and \( n \) is a fixed positive integer. Then

\[
\lim_{x \to x_{0}} P(x) = a_{0} + a_{1}x_{0} + a_{2}x_{0}^{2} + \dots + a_{n}x_{0}^{n} = P(x_{0}).
\]

### Example 9.7

\[
\lim_{x \to 3} (x^{3} - 2x + 6).
\]

**Solution**

\( P(x) = x^{3} - 2x + 6 \) is a polynomial.

Hence, \( \lim_{x \to 3} P(x) = P(3) = 3^{3} - 2 \times 3 + 6 = 27 \).

### Example 9.8

Calculate \( \lim_{x \to x_{0}} (5) \) for any real number \( x_{0} \).

**Solution**

\( f(x) = 5 \) is a polynomial (of degree 0).

Hence \( \lim_{x \to x_{0}} (5) = f(x_{0}) = 5 \).

The limit of a constant function is that constant.

**Theorem 9.2**

Let \( I \) be an open interval containing \( x_{0} \in \mathbb{R} \). Let \( f, g : I \to \mathbb{R} \). Suppose that \( c \) is a constant and the limits \( \lim_{x \to x_{0}} f(x) \) and \( \lim_{x \to x_{0}} g(x) \) exist. Then \( \lim_{x \to x_{0}} (c f(x)) \), \( \lim_{x \to x_{0}} [f(x) + g(x)] \), \( \lim_{x \to x_{0}} [f(x) - g(x)] \), \( \lim_{x \to x_{0}} [f(x) g(x)] \) and \( \lim_{x \to x_{0}} \frac{f(x)}{g(x)} \) (\( g(x) \neq 0 \)), all exist. Moreover,

(i) \( \lim_{x \to x_{0}} c f(x) = c \lim_{x \to x_{0}} f(x) \),

(ii) \( \lim_{x \to x_{0}} [f(x) \pm g(x)] = \lim_{x \to x_{0}} f(x) \pm \lim_{x \to x_{0}} g(x) \),

(iii) \( \lim_{x \to x_{0}} [f(x) g(x)] = \lim_{x \to x_{0}} f(x) \cdot \lim_{x \to x_{0}} g(x) \),

(iv) \( \lim_{x \to x_{0}} \frac{f(x)}{g(x)} = \frac{\lim_{x \to x_{0}} f(x)}{\lim_{x \to x_{0}} g(x)} \), provided \( \lim_{x \to x_{0}} g(x) \neq 0 \).

These results can be extended to any finite number of functions.

### Example 9.9

Compute (i) \( \lim_{x \to 8} (5x) \) (ii) \( \lim_{x \to -2} \left( \frac{3}{x} - 2 \right) \).

**Solution**

(i) \( \lim_{x \to 8} (5x) = 5 \lim_{x \to 8} x = 5 \times 8 = 40 \).

(ii) \( \lim_{x \to -2} \left( \frac{3}{x} - 2 \right) = 3 \lim_{x \to -2} \left( \frac{1}{x} \right) - 2 = 3 \times \left( -\frac{1}{2} \right) - 2 = -\frac{3}{2} - 2 = -\frac{7}{2} \).

### Example 9.10

Compute \( \lim_{x \to 0} \left[ \frac{x^{2} + x}{x} + (4x + 3) \right] \).

**Solution**

\[
\lim_{x \to 0} \left[ \frac{x^{2} + x}{x} + (4x + 3) \right] = \lim_{x \to 0} \left( \frac{x^{2} + x}{x} \right) + \lim_{x \to 0} (4x + 3)
\]
\[
= \lim_{x \to 0} (x + 1) + \lim_{x \to 0} (4x + 3) = (0 + 1) + (0 + 3) = 4.
\]

### Example 9.11

Calculate \( \lim_{x \to -1} (x^{2} - 3)^{10} \).

**Solution**

\[
\lim_{x \to -1} (x^{2} - 3) = 1 - 3 = -2.
\]

\[
\lim_{x \to -1} (x^{2} - 3)^{10} = \lim_{x \to -1} (x^{2} - 3)(x^{2} - 3) \dots (x^{2} - 3) \text{ (10 times)}
\]
\[
= \left[ \lim_{x \to -1} (x^{2} - 3) \right]^{10} = (-2)^{10} = 2^{10} = 1024.
\]

Note that \( \lim_{x \to -1} (x^{2} - 3)^{10} = \left[ \lim_{x \to -1} (x^{2} - 3) \right]^{10} \).

**Theorem 9.3**

If \( \lim_{x \to x_{0}} f(x) \) exists then \( \lim_{x \to x_{0}} [f(x)]^{n} \) exists and \( \lim_{x \to x_{0}} [f(x)]^{n} = \left[ \lim_{x \to x_{0}} f(x) \right]^{n} \).

### Example 9.12

Calculate \( \lim_{x \to -2} (x^{3} - 3x + 6)(-x^{2} + 15) \).

**Solution**

\[
\lim_{x \to -2} (x^{3} - 3x + 6) = (-2)^{3} - 3(-2) + 6 = -8 + 6 + 6 = 4
\]
\[
\lim_{x \to -2} (-x^{2} + 15) = -(-2)^{2} + 15 = -4 + 15 = 11
\]
\[
\lim_{x \to -2} (x^{3} - 3x + 6)(-x^{2} + 15) = \lim_{x \to -2} (x^{3} - 3x + 6) \cdot \lim_{x \to -2} (-x^{2} + 15) = 4 \times 11 = 44.
\]

### Example 9.13

Calculate \( \lim_{x \to 3} \frac{x^{2} - 6x + 5}{x^{3} - 8x + 7} \).

**Solution**

\[
\lim_{x \to 3} (x^{2} - 6x + 5) = 3^{2} - 6 \times 3 + 5 = -4
\]
\[
\lim_{x \to 3} (x^{3} - 8x + 7) = 3^{3} - 8 \times 3 + 7 = 10 \neq 0.
\]
\[
\lim_{x \to 3} \frac{x^{2} - 6x + 5}{x^{3} - 8x + 7} = \frac{\lim_{x \to 3} (x^{2} - 6x + 5)}{\lim_{x \to 3} (x^{3} - 8x + 7)} = \frac{-4}{10} = -\frac{2}{5}.
\]

**Caution:** Do not use the limit theorem for the quotient if \( \lim_{x \to x_{0}} g(x) = 0 \).

### Example 9.14

Compute \( \lim_{x \to 1} \frac{\sqrt{x} - 1}{x - 1} \).

**Solution**

Here \( \lim_{x \to 1} (x - 1) = 0 \). In such cases, rationalise the numerator.

\[
\lim_{x \to 1} \frac{\sqrt{x} - 1}{x - 1} = \lim_{x \to 1} \frac{(\sqrt{x} - 1)}{(\sqrt{x} - 1)(\sqrt{x} + 1)} = \lim_{x \to 1} \frac{1}{\sqrt{x} + 1} = \frac{1}{\sqrt{1} + 1} = \frac{1}{2}.
\]

### Example 9.15

\[
\lim_{t \to 0} \frac{\sqrt{t^{2} + 9} - 3}{t^{2}}.
\]

**Solution**

We can't apply the quotient theorem immediately. Use the algebra technique of rationalising the numerator.

\[
\frac{\sqrt{t^{2} + 9} - 3}{t^{2}} = \frac{(\sqrt{t^{2} + 9} - 3)(\sqrt{t^{2} + 9} + 3)}{t^{2}(\sqrt{t^{2} + 9} + 3)} = \frac{t^{2} + 9 - 9}{t^{2}(\sqrt{t^{2} + 9} + 3)} = \frac{1}{\sqrt{t^{2} + 9} + 3}
\]
\[
\lim_{t \to 0} \frac{\sqrt{t^{2} + 9} - 3}{t^{2}} = \lim_{t \to 0} \frac{1}{\sqrt{t^{2} + 9} + 3} = \frac{1}{\sqrt{9} + 3} = \frac{1}{6}.
\]

**Theorem 9.4**

\[
\lim_{x \to a} \frac{x^{n} - a^{n}}{x - a} = n a^{n-1}.
\]

**Proof**

We know that \( x^{n} - a^{n} = (x - a)(x^{n-1} + x^{n-2}a + x^{n-3}a^{2} + \dots + x a^{n-2} + a^{n-1}) \)

\[
\lim_{x \to a} \frac{x^{n} - a^{n}}{x - a} = \lim_{x \to a} \frac{(x - a)(x^{n-1} + x^{n-2}a + \dots + a^{n-1})}{(x - a)}
\]
\[
= \lim_{x \to a} (x^{n-1} + x^{n-2}a + x^{n-3}a^{2} + \dots + x a^{n-2} + a^{n-1})
\]
\[
= a^{n-1} + a^{n-1} + \dots + a^{n-1} \quad (n \text{ times})
\]
\[
= n a^{n-1}.
\]

It is also true for any rational number \( n \).

### Example 9.16

\[
\lim_{x \to 1} \frac{x^{3} - 1}{x - 1}.
\]

**Solution**

\[
\lim_{x \to 1} \frac{x^{3} - 1}{x - 1} = \lim_{x \to 1} \frac{x^{3} - 1^{3}}{x - 1} = 3(1)^{3-1} = 3.
\]

### Example 9.17

Calculate \( \lim_{t \to 1} \frac{\sqrt{t} - 1}{t - 1} \).

**Solution**

\[
\lim_{t \to 1} \frac{\sqrt{t} - 1}{t - 1} = \lim_{t \to 1} \frac{t^{\frac{1}{2}} - 1^{\frac{1}{2}}}{t - 1} = \frac{1}{2} (1)^{\frac{1}{2} - 1} = \frac{1}{2}.
\]

### Example 9.18

\[
\lim_{x \to 0} \frac{(2 + x)^{5} - 2^{5}}{x}.
\]

**Solution**

Put \( 2 + x = y \) so that as \( x \to 0 \), \( y \to 2 \).

\[
\lim_{x \to 0} \frac{(2 + x)^{5} - 2^{5}}{x} = \lim_{y \to 2} \frac{y^{5} - 2^{5}}{y - 2} = 5(2^{4}) = 80.
\]

### Example 9.19

Find the positive integer \( n \) so that \( \lim_{x \to 3} \frac{x^{n} - 3^{n}}{x - 3} = 27 \).

**Solution**

\[
\lim_{x \to 3} \frac{x^{n} - 3^{n}}{x - 3} = n \cdot 3^{n-1} = 27
\]

That is \( n \cdot 3^{n-1} = 3 \times 3^{2} = 3 \times 3^{3-1} \Rightarrow n = 3 \).

### Example 9.20

Find the relation between \( a \) and \( b \) if \( \lim_{x \to 3} f(x) \) exists where \( f(x) = \begin{cases} ax + b & \text{if } x > 3 \\ 3ax - 4b + 1 & \text{if } x < 3 \end{cases} \)

**Solution**

\[
\lim_{x \to 3^{-}} f(x) = 9a - 4b + 1, \quad \lim_{x \to 3^{+}} f(x) = 3a + b.
\]

Now the existence of limit forces us to have

\[
\lim_{x \to 3^{-}} f(x) = \lim_{x \to 3^{+}} f(x)
\]
\[
\Rightarrow 9a - 4b + 1 = 3a + b
\]
\[
\Rightarrow 6a - 5b + 1 = 0.
\]

## EXERCISE 9.2

Evaluate the following limits:

(1) \( \lim_{x \to 2} \frac{x^{4} - 16}{x - 2} \)

(2) \( \lim_{x \to 1} \frac{x^{m} - 1}{x^{n} - 1} \), \( m \) and \( n \) are integers.

(3) \( \lim_{x \to 3} \frac{x^{2} - 81}{\sqrt{x} - 3} \)

(4) \( \lim_{h \to 0} \frac{\sqrt{x + h} - \sqrt{x}}{h}, x > 0 \)

(5) \( \lim_{x \to 5} \frac{\sqrt{x + 4} - 3}{x - 5} \)

(6) \( \lim_{x \to 2} \frac{1}{x - 2} - \frac{2}{x^{2} - 2x} \)

(7) \( \lim_{x \to 1} \frac{x^{2} - x}{x - 1} \)

(8) \( \lim_{x \to 0} \frac{\sqrt{1 + x^{2}} - 1}{x} \)

(9) \( \lim_{x \to 0} \frac{\sqrt{1 + x} - 1}{x} \)

(10) \( \lim_{x \to 1} \frac{x^{3} + 7x^{2} - 3x - 3}{x - 1} \)

(11) \( \lim_{x \to 2} \left( \frac{2}{x} - \frac{3}{x^{2}} \right) \)

(12) \( \lim_{x \to 0} \frac{\sqrt{1 + x^{2}} - 1}{x} \)

(13) \( \lim_{x \to 0} \frac{\sqrt{1 + x} - 1}{x} \)

(14) \( \lim_{x \to 5} \frac{\sqrt{x - 2} - 3}{x - 5} \)

(15) \( \lim_{x \to a} \frac{x^{2} - b^{2}}{x - a}, (b > a) \)

### 9.2.4 Infinite limits and limits at infinity

#### Infinite Limits

Let \( f : \mathbb{R} \setminus \{0\} \to \mathbb{R} \) be defined by \( f(x) = \frac{1}{x^{2}} \).

Let us consider the problem of calculating \( \lim_{x \to 0} \frac{1}{x^{2}} \).

The following table gives the values of \( \frac{1}{x^{2}} \) near 0.

| \( x (< 0) \) \( x \to 0^{-} \) | \( x^{2} \) | \( \frac{1}{x^{2}} \) | \( x (> 0) \) \( x \to 0^{+} \) | \( x^{2} \) | \( \frac{1}{x^{2}} \) |
|-------------------------------|------------|---------------------|-------------------------------|------------|---------------------|
| -1 | 1 | 1 | 1 | 1 | 1 |
| -0.5 | 0.25 | 4 | 0.5 | 0.25 | 4 |
| -0.1 | 0.01 | 100 | 0.1 | 0.01 | 100 |
| -0.01 | 0.0001 | 10,000 | 0.01 | 0.0001 | 10,000 |
| -0.001 | 0.000001 | 1,000,000 | 0.001 | 0.000001 | 1,000,000 |
| -0.0001 | 0.00000001 | 100,000,000 | 0.0001 | 0.00000001 | 100,000,000 |

The table values tell us that as \( x \) gets closer and closer to 0, \( f(x) = \frac{1}{x^{2}} \) gets larger and larger. In fact, \( \frac{1}{x^{2}} \) grows without bound as \( x \) approaches 0 from either side. In this situation we say that \( f(x) \) tends to infinity as \( x \) approaches zero and write \( \frac{1}{x^{2}} \to \infty \) as \( x \to 0^{-} \), \( \frac{1}{x^{2}} \to \infty \) as \( x \to 0^{+} \) and hence \( \frac{1}{x^{2}} \to \infty \) as \( x \to 0 \).

Geometrically, \( x = 0 \) namely the \( y \)-axis is a vertical asymptote to the curve representing \( f(x) = \frac{1}{x^{2}} \).

The graph of the function \( f(x) = \frac{1}{x^{2}} \) is shown in Fig. 9.22.

Remember that the limit is infinite and so \( \lim_{x \to 0} \frac{1}{x^{2}} \) does not exist. Students are cautioned that \( \infty \) is a symbol for this behaviour of \( f(x) = \frac{1}{x^{2}} \) and is not a new number.

Similarly, if we look at \( f(x) = \frac{1}{x} \), it is easy to see that

\[
\frac{1}{x} \to -\infty \text{ as } x \to 0^{-} \quad \text{and} \quad \frac{1}{x} \to +\infty \text{ as } x \to 0^{+}
\]

which is geometrically clear from the graph of \( f(x) = \frac{1}{x} \) (Fig. 9.23).

In general we have the following intuitive definitions.

**Definition 9.4**

For a given \( M > 0 \), open intervals of the form \( (M, \infty) \) is called neighbourhood of \( \infty \).

Similarly, for given \( K < 0 \) open intervals of the form \( (-\infty, K) \) is called neighbourhood of \( -\infty \).

**Definition 9.5**

We say, \( f(x) \to \infty \) as \( x \) approaches \( x_{0} \) if for given positive number \( M \) there is a neighbourhood of \( x_{0} \), such that whenever \( x \) is in the neighbourhood of \( x_{0} \), \( f(x) > M \). i.e., \( f(x) \in (M, \infty) \).

Similarly, \( f(x) \to -\infty \) as \( x \) approaches \( x_{0} \) if for a given \( K < 0 \) there is a neighbourhood of \( x_{0} \) such that whenever \( x \) is in the neighbourhood of \( x_{0} \), \( f(x) < K \). i.e., \( f(x) \in (-\infty, K) \).

To describe this situation symbolically, we write

\[
f(x) \to \infty \text{ as } x \to x_{0}
\]
\[
f(x) \to -\infty \text{ as } x \to x_{0}
\]
\[
f(x) \to \infty \text{ as } x \to x_{0}^{-}
\]
\[
f(x) \to -\infty \text{ as } x \to x_{0}^{+}
\]
\[
\text{and } f(x) \to \infty \text{ as } x \to x_{0}^{+}
\]
\[
f(x) \to -\infty \text{ as } x \to x_{0}^{-}
\]

are called infinite limits. If any one of the foregoing conditions hold, then the line \( x = x_{0} \) is a vertical asymptote for the graph of \( f(x) \).

### Example 9.21

Calculate \( \lim_{x \to 0} \frac{1}{x^{2} + x^{3}} \).

**Solution**

One can tabulate values of \( x \) near 0 (from either side) and conclude \( f(x) = \frac{1}{x^{2} + x^{3}} \) grows without bound and hence \( f(x) \to \infty \) as \( x \to 0 \).

To calculate this limit without making a table, we first divide the numerator and denominator by \( x^{2} \). This division can be done, since in the calculation of the limit \( x \neq 0 \) and hence \( x^{2} \neq 0 \). We can have

\[
\lim_{x \to 0} \frac{1}{x^{2} + x^{3}} = \lim_{x \to 0} \frac{\frac{1}{x^{2}}}{\frac{x^{2} + x^{3}}{x^{2}}} = \frac{\lim_{x \to 0} \left( \frac{1}{x^{2}} \right)}{\lim_{x \to 0} (1 + x)}.
\]

Now \( \frac{1}{x^{2}} \to \infty \) as \( x \to 0 \) and \( \lim_{x \to 0} (1 + x) = 1 \). Thus the numerator grows without bound while the denominator approaches 1, implying that \( \frac{1}{(x^{2} + x^{3})} \) does tend to infinity.

This example illustrates how a difficult calculation can be greatly simplified by a few algebraic manipulations.

### Example 9.22

Evaluate \( \lim_{x \to 2} \frac{1}{(x - 2)^{3}} \).

**Solution**

From the graph of \( f(x) = \frac{1}{(x - 2)^{3}} \) clearly, \( \frac{1}{(x - 2)^{3}} \to -\infty \) as \( x \to 2^{-} \) and \( \frac{1}{(x - 2)^{3}} \to \infty \) as \( x \to 2^{+} \). Hence the limit does not exist.

In general

(i) If \( n \) is an even positive integer then

\[
\frac{1}{(x - a)^{n}} \to \infty \text{ as } x \to a
\]
\[
\frac{1}{(x - a)^{n}} \to \infty \text{ as } x \to a^{-}
\]
\[
\frac{1}{(x - a)^{n}} \to \infty \text{ as } x \to a^{+}
\]

(ii) If \( n \) is an odd positive integer, then

\[
\frac{1}{(x - a)^{n}} \to -\infty \text{ as } x \to a^{-}
\]
\[
\frac{1}{(x - a)^{n}} \to +\infty \text{ as } x \to a^{+}
\]

### 9.2.5 Limits at infinity

In the previous section we investigated infinite limits and vertical asymptotes. There, we let \( x \) approach a number and the result was that the values of \( y \) became arbitrarily large (very large positive or very large negative). In this section, we let \( x \) become arbitrarily large (positive or negative) and see what happens to \( y \).

Let's begin by investigating the behaviour of \( f : \mathbb{R} \to \mathbb{R} \) defined by

\[
f(x) = \frac{x^{2} - 1}{x^{2} + 1} \text{ as } x \text{ becomes large.}
\]

We tabulate the values of this function

| \( x \) | \( f(x) \) |
|--------|------------|
| 0 | -1 |
| ±1 | 0 |
| ±2 | 0.6000000 |
| ±3 | 0.800000 |
| ±4 | 0.882353 |
| ±5 | 0.923077 |
| ±10 | 0.980198 |
| ±50 | 0.999200 |
| ±100 | 0.999800 |
| ±1000 | 0.999998 |

As \( x \) grows larger and larger (large positive or large negative) you can see that the values of \( f(x) \) gets closer and closer to 1. In fact, it seems that we can make the values of \( f(x) \) as close as to 1 by taking \( x \) sufficiently large. This situation is expressed symbolically by writing

\[
\lim_{x \to \pm \infty} \frac{x^{2} - 1}{x^{2} + 1} = 1.
\]

If we look at the graph (see Fig. 9.25), this situation also leads us to have

**Definition 9.6**

The line \( y = l \) is called a horizontal asymptote of the curve \( y = f(x) \) if either

\[
\lim_{x \to \infty} f(x) = l \quad \text{or} \quad \lim_{x \to +\infty} f(x) = l.
\]

#### Illustration 9.4

If \( f : \mathbb{R} \to \left[ -\frac{\pi}{2}, \frac{\pi}{2} \right] \) is defined by \( f(x) = \tan^{-1} x \), find \( \lim_{x \to -\infty} f(x) \) and \( \lim_{x \to \infty} f(x) \).

**Solution**

If we look at the graph of \( y = \tan^{-1} x \),

\[
\lim_{x \to -\infty} \tan^{-1} x = -\frac{\pi}{2}, \quad \lim_{x \to +\infty} \tan^{-1} x = \frac{\pi}{2}.
\]

#### Illustration 9.5

Calculate \( \lim_{x \to \infty} \frac{2x^{2} - 2x + 3}{x^{2} + 4x + 4} \).

**Solution**

If we could try to use limit theorems to calculate this limit, we end up in the following situations.

\( (2x^{2} - 2x + 3) \to \infty \) as \( x \to \infty \)

\( (x^{2} + 4x + 4) \to \infty \) as \( x \to \infty \)

\( \lim_{x \to \infty} \left( \frac{2x^{2} - 2x + 3}{x^{2} + 4x + 4} \right) \) is an indeterminate form.

But actual calculation and tabulation gives the following:

| \( x \) | \( 2x^{2} - 2x + 3 \) | \( x^{2} + 4x + 4 \) | \( \frac{2x^{2} - 2x + 3}{x^{2} + 4x + 4} \) |
|--------|----------------------|---------------------|---------------------------------------------|
| 1 | 3 | 9 | 0.33333 |
| 10 | 183 | 144 | 1.27083 |
| 100 | 19803 | 10404 | 1.90340 |
| 1000 | 1998003 | 1004004 | 1.99003 |
| 10000 | 199980003 | 100040004 | 1.99900 |

Table values show that as \( x \) becomes sufficiently large, \( f(x) \) becomes closer and closer to 2. Then,

\[
\lim_{x \to \infty} \left( \frac{2x^{2} - 2x + 3}{x^{2} + 4x + 4} \right) = 2.
\]

Fortunately, we may simplify the problem by dividing the numerator and denominator by \( x^{2} \). We have

\[
\lim_{x \to \infty} \frac{2x^{2} - 2x + 3}{x^{2} + 4x + 4} = \lim_{x \to \infty} \left( \frac{2 - \frac{2}{x} + \frac{3}{x^{2}}}{1 + \frac{4}{x} + \frac{4}{x^{2}}} \right)
\]
\[
= \frac{2 - 0 + 0}{1 + 0 + 0} \left( \text{since } \frac{1}{x} \to 0 \text{ as } x \to \infty, \frac{1}{x^{2}} \to 0 \text{ as } x \to \infty \right) = 2.
\]

Note that the degree of both numerator and denominator expressions are the same.

In general, the limits as \( x \to \pm \infty \) of rational expressions can be found by first dividing the numerator and denominator by the highest power of \( x \) that appears in the denominator, and then calculating the limit as \( x \to \infty \) (or \( x \to -\infty \)) of both numerator and denominator.

### Example 9.23

\[
\lim_{x \to \infty} \frac{x^{3} + 2x + 3}{5x^{2} + 1}.
\]

**Solution**

Dividing by \( x^{2} \)

\[
\lim_{x \to \infty} \frac{x^{3} + 2x + 3}{5x^{2} + 1} = \lim_{x \to \infty} \frac{x + \frac{2}{x} + \frac{3}{x^{2}}}{5 + \frac{1}{x^{2}}} \to \infty
\]

That is, \( \frac{x^{3} + 2x + 3}{5x^{2} + 1} \to \infty \) as \( x \to \infty \). In other words, the limit does not exist.

Note that the degree of numerator is higher than that of the denominator.

### Example 9.24

Calculate \( \lim_{x \to \infty} \frac{1 - x^{3}}{3x + 2} \).

**Solution**

Dividing by \( x \), we get

\[
\frac{1 - x^{3}}{3x + 2} = \frac{\frac{1}{x} - x^{2}}{3 + \frac{2}{x}} \to -\infty \text{ as } x \to \infty.
\]

Therefore the limit does not exist.

### 9.2.6 Limits of rational functions

If \( R(x) = \frac{p(x)}{q(x)} \) and the degree of the polynomial \( p(x) \) is greater than the degree of \( q(x) \), then

\[
\frac{p(x)}{q(x)} \to +\infty \text{ or } -\infty \text{ as } x \to \infty.
\]

If the degree of \( q(x) \) is greater than the degree of \( p(x) \), then

\[
\lim_{x \to \infty} \frac{p(x)}{q(x)} = 0.
\]

Finally, if the degree of \( p(x) \) is equal to the degree of \( q(x) \), then

\[
\lim_{x \to \infty} \frac{p(x)}{q(x)} = \frac{\text{coefficient of highest power of } x \text{ in } p(x)}{\text{coefficient of highest power of } x \text{ in } q(x)}.
\]

**Remark**

We reemphasize that statements such as \( f(x) \to \infty \) as \( x \to a \), \( f(x) \to -\infty \) as \( x \to a \), and \( f(x) \to \infty \) as \( x \to \infty \), \( f(x) \to -\infty \) as \( x \to \infty \) mean that the limits do not exist. The symbol \( \infty \) does not represent a number and should not be treated as a number.

### 9.2.7 Applications of limits

### Example 9.25

Alcohol is removed from the body by the lungs, the kidneys, and by chemical processes in liver. At moderate concentration levels, the majority work of removing the alcohol is done by the liver; less than 5% of the alcohol is eliminated by the lungs and kidneys. The rate \( r \) at which the liver processes alcohol from the bloodstream is related to the blood alcohol concentration \( x \) by a rational function of the form \( r(x) = \frac{\alpha x}{\beta + x} \) for some positive constants \( \alpha \) and \( \beta \). Find the maximum possible rate of removal.

**Solution**

As the alcohol concentration \( x \) increases the rate of removal increases.

Therefore, the maximum possible rate of removal = \( \lim_{x \to \infty} r(x) \)

\[
= \lim_{x \to \infty} \frac{\alpha x}{\beta + x} = \lim_{x \to \infty} \frac{\alpha}{1 + \frac{\beta}{x}} = \alpha.
\]

### 9.2.8 Sandwich Theorem

Sandwich theorem is also known as squeeze theorem. As shown in the figure 9.27, if \( f(x) \) is 'squeezed' or 'sandwiched' between \( g(x) \) and \( h(x) \) for all \( x \) close to \( x_{0} \), and if we know that the functions \( g \) and \( h \) have a common limit \( l \) as \( x \to x_{0} \), it stands to reason that \( f \) also approaches \( l \) as \( x \to x_{0} \).

**Theorem 9.5 (Sandwich Theorem)**

If \( g, f, h : I \to \mathbb{R} \) such that \( g(x) \leq f(x) \leq h(x) \) for all \( x \) in a deleted neighbourhood of \( x_{0} \) contained in \( I \), and if

\[
\lim_{x \to x_{0}} g(x) = \lim_{x \to x_{0}} h(x) = l,
\]

then \( \lim_{x \to x_{0}} f(x) = l \).

### Example 9.26

According to Einstein's theory of relativity, the mass \( m \) of a body moving with velocity \( v \) is \( m = \frac{m_{0}}{\sqrt{1 - \frac{v^{2}}{c^{2}}}} \), where \( m_{0} \) is the initial mass and \( c \) is the speed of light. What happens to \( m \) as \( v \to c^{-} \)? Why is a left hand limit necessary?

**Solution**

\[
\lim_{v \to c^{-}} m = \lim_{v \to c^{-}} \frac{m_{0}}{\sqrt{1 - \frac{v^{2}}{c^{2}}}}
\]

For \( h > 0 \), \( c - h < v < c \). This implies \( (c - h)^{2} < v^{2} < c^{2} \). That is, \( 1 - \frac{(c - h)^{2}}{c^{2}} > 1 - \frac{v^{2}}{c^{2}} > 0 \). So \( 0 < 1 - \frac{v^{2}}{c^{2}} < 1 - \frac{(c - h)^{2}}{c^{2}} \).

As \( h \to 0 \), \( 1 - \frac{v^{2}}{c^{2}} \to 0 \). Thus

\[
\lim_{v \to c^{-}} \left( 1 - \frac{v^{2}}{c^{2}} \right) = 0.
\]

By Sandwich theorem, \( \lim_{v \to c^{-}} \frac{v^{2}}{c^{2}} = 1 \). Therefore, \( \lim_{v \to c^{-}} m \to \infty \). That is, the mass becomes very very large (infinite) as \( v \to c^{-} \). The left hand limit is necessary. Otherwise as \( v \to c^{+} \) makes \( 1 - \frac{v^{2}}{c^{2}} < 0 \) and consequently we cannot find the mass.

### Example 9.27

The velocity in ft/sec of a falling object is modeled by \( r(t) = -\sqrt{\frac{32}{k}} \frac{1 - e^{-2t\sqrt{32k}}}{1 + e^{-2t\sqrt{32k}}} \), where \( k \) is a constant that depends upon the size and shape of the object and the density of the air. Find the limiting velocity of the object, that is, find \( \lim_{t \to \infty} r(t) \).

**Solution**

\[
\lim_{t \to \infty} r(t) = \lim_{t \to \infty} \left( -\sqrt{\frac{32}{k}} \frac{1 - e^{-2t\sqrt{32k}}}{1 + e^{-2t\sqrt{32k}}} \right)
\]
\[
= -\sqrt{\frac{32}{k}} \cdot \frac{1 - 0}{1 + 0} = -\sqrt{\frac{32}{k}} \text{ ft/sec}.
\]

### Example 9.28

Suppose that the diameter of an animal's pupils is given by \( f(x) = \frac{160x^{-0.4} + 90}{4x^{-0.4} + 15} \), where \( x \) is the intensity of light and \( f(x) \) is in mm. Find the diameter of the pupils with (a) minimum light (b) maximum light.

**Solution**

(a) For minimum light it is enough to find the limit of the function when \( x \to 0^{+} \)

\[
\lim_{x \to 0^{+}} f(x) = \lim_{x \to 0^{+}} \frac{160x^{-0.4} + 90}{4x^{-0.4} + 15} = \lim_{x \to 0^{+}} \frac{160 + 90x^{0.4}}{4 + 15x^{0.4}} = \frac{160}{4} = 40 \text{ mm}.
\]

(b) For maximum light, it is enough to find the limit of the function when \( x \to \infty \)

\[
\lim_{x \to \infty} f(x) = \lim_{x \to \infty} \frac{160x^{-0.4} + 90}{4x^{-0.4} + 15} = 6 \text{ mm}.
\]

That is, the pupils have a limiting size of 6 mm, as the intensity of light is very large.

### Exercise 9.3

(1) (a) Find the left and right limits of \( f(x) = \frac{x^{2} - 4}{(x^{2} + 4x + 4)(x + 3)} \) at \( x = -2 \).

(b) \( f(x) = \tan x \) at \( x = \frac{\pi}{2} \).

(2) Evaluate the following limits:

\[
\text{(i)} \lim_{x \to 3} \frac{x^{2} - 9}{x^{2}(x^{2} - 6x + 9)} \quad
\text{(ii)} \lim_{x \to \infty} \left( \frac{3}{x - 2} - \frac{2x + 11}{x^{2} + x - 6} \right)
\]

\[
\text{(iii)} \lim_{x \to \infty} \frac{x^{3} + x}{x^{4} - 3x^{2} + 1} \quad
\text{(iv)} \lim_{x \to \infty} \frac{x^{4} - 5x}{x^{2} - 3x + 1}
\]

\[
\text{(v)} \lim_{x \to \infty} \frac{1 + x - 3x^{3}}{1 + x^{2} + 3x^{3}} \quad
\text{(vi)} \lim_{x \to \infty} \left( \frac{x^{3}}{2x^{2} - 1} - \frac{x^{2}}{2x + 1} \right)
\]

(3) Show that

\[
\text{(i)} \lim_{n \to \infty} \frac{1 + 2 + 3 + \ldots + n}{3n^{2} + 7n + 2} = \frac{1}{6}
\]
\[
\text{(ii)} \lim_{n \to \infty} \frac{1^{2} + 2^{2} + \ldots + (3n)^{2}}{(1 + 2 + \ldots + 5n)(2n + 3)} = \frac{9}{25}
\]
\[
\text{(iii)} \lim_{n \to \infty} \left( \frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \ldots + \frac{1}{n(n + 1)} \right) = 1
\]

(4) An important problem in fishery science is to estimate the number of fish presently spawning in streams and use this information to predict the number of mature fish or "recruits" that will return to the rivers during the reproductive period. If \( S \) is the number of spawners and \( R \) the number of recruits, "Beverton-Holt spawner recruit function" is \( R(S) = \frac{S}{(\alpha S + \beta)} \) where \( \alpha \) and \( \beta \) are positive constants. Show that this function predicts approximately constant recruitment when the number of spawners is sufficiently large.

(5) A tank contains 5000 litres of pure water. Brine (very salty water) that contains 30 grams of salt per litre of water is pumped into the tank at a rate of 25 litres per minute. The concentration of salt water after \( t \) minutes (in grams per litre) is \( C(t) = \frac{30t}{200 + t} \). What happens to the concentration as \( t \to \infty \)?

### Example 9.29

Evaluate \( \lim_{x \to 0} x^{2} \sin \left( \frac{1}{x} \right) \).

**Solution**

\[
\left| \sin \frac{1}{x} \right| \leq 1 \Rightarrow -x^{2} \leq x^{2} \sin \frac{1}{x} \leq x^{2}
\]

Take \( g(x) = -x^{2} \), \( f(x) = x^{2} \sin \frac{1}{x} \), \( h(x) = x^{2} \).

Then \( \lim_{x \to 0} g(x) = \lim_{x \to 0} (-x^{2}) = 0 \) and \( \lim_{x \to 0} h(x) = \lim_{x \to 0} (x^{2}) = 0 \).

By Sandwich theorem,

\[
\lim_{x \to 0} x^{2} \sin \left( \frac{1}{x} \right) = 0.
\]

We could have wrongly concluded had we resorted to applying the limit theorems, namely

\[
\lim_{x \to 0} x^{2} \sin \left( \frac{1}{x} \right) = \lim_{x \to 0} x^{2} \cdot \lim_{x \to 0} \sin \left( \frac{1}{x} \right).
\]

Now, \( \lim_{x \to 0} \sin \left( \frac{1}{x} \right) \) does not exist, \( \lim_{x \to 0} x^{2} = 0 \) leading us into trouble.

Note that, if \( |f(x)| \leq a \), then \( -a \leq f(x) \leq a \).

### Example 9.30

Prove that \( \lim_{x \to 0} \sin x = 0 \).

**Solution**

Since \( -x \leq \sin x \leq x \) for all \( x \).

\[
\lim_{x \to 0} (-x) = 0 \quad \text{and} \quad \lim_{x \to 0} x = 0.
\]

By Sandwich theorem

\[
\lim_{x \to 0} \sin x = 0.
\]

### Example 9.31

Show that

\[
\lim_{x \to 0} \left[ \frac{x}{x} + \frac{2x}{x} + \dots + \frac{15x}{x} \right] = 120.
\]

**Solution**

\[
1 \leq \frac{x}{x} + 1 \leq x + 1 \quad \text{(for appropriate bounds)}
\]

[Note: The original solution in the PDF appears to have formatting issues. The intended meaning is to use the fact that for sufficiently small \( x \), the floor function terms behave in a certain way leading to the sum 120.]

### 9.2.9 Two special Trigonometric limits

**Result 9.1** (a) \( \lim_{\theta \to 0} \frac{\sin \theta}{\theta} = 1 \) (b) \( \lim_{\theta \to 0} \frac{1 - \cos \theta}{\theta} = 0 \)

**Proof**

We use a circular sector to prove the result.

Consider the circle with centre (0, 0) and radius 1. By area property

\[
\frac{\tan \theta}{2} \geq \frac{\theta}{2} \geq \frac{\sin \theta}{2}.
\]

Multiplying each expression by \( \frac{2}{\sin \theta} \) produces \( \frac{1}{\cos \theta} \geq \frac{\theta}{\sin \theta} \geq 1 \) and taking reciprocals

\[
\cos \theta \leq \frac{\sin \theta}{\theta} \leq 1.
\]

Because \( \cos(-\theta) = \cos \theta \) and \( \frac{\sin(-\theta)}{-\theta} = \frac{\sin \theta}{\theta} \) one can conclude that this inequality is valid for all non-zero \( \theta \) in the open interval \( \left( -\frac{\pi}{2}, \frac{\pi}{2} \right) \).

We know that \( \lim_{\theta \to 0} \cos \theta = 1 \); \( \lim_{\theta \to 0} (1) = 1 \) and applying Sandwich theorem we get \( \lim_{\theta \to 0} \frac{\sin \theta}{\theta} = 1 \).

\[
\lim_{\theta \to 0} \frac{1 - \cos \theta}{\theta} = 0.
\]

Since \( 1 - \cos \theta = 2 \sin^{2} \frac{\theta}{2} \),

\[
\lim_{\theta \to 0} \frac{1 - \cos \theta}{\theta} = \lim_{\theta \to 0} \frac{2 \sin^{2} \frac{\theta}{2}}{\theta} = \lim_{\theta \to 0} \left( \sin \frac{\theta}{2} \cdot \frac{\sin \frac{\theta}{2}}{\frac{\theta}{2}} \right) = 0 \times 1 = 0.
\]

### 9.2.10 Some important other limits

**Result 9.2**

\[
\lim_{x \to 0} \frac{e^{x} - 1}{x} = 1.
\]

**Proof**

\( e^{x} = 1 + \frac{x}{1!} + \frac{x^{2}}{2!} + \frac{x^{3}}{3!} + \ldots \) (from sequences and series)

\[
\lim_{x \to 0} \frac{e^{x} - 1}{x} = \lim_{x \to 0} \left( 1 + \frac{x}{2!} + \frac{x^{2}}{3!} + \ldots \right) = 1.
\]

**Result 9.3**

\[
\lim_{x \to 0} \frac{a^{x} - 1}{x} = \log a, \quad a > 0
\]

**Proof**

We know that \( a^{x} = e^{x \log a} \).

\[
\frac{a^{x} - 1}{x} = \frac{e^{x \log a} - 1}{x} = \frac{e^{x \log a} - 1}{x \log a} \cdot \log a.
\]

Now as \( x \to 0 \), \( y = x \log a \to 0 \).

\[
\lim_{x \to 0} \frac{a^{x} - 1}{x} = \lim_{y \to 0} \frac{e^{y} - 1}{y} \cdot \log a = \log a \quad (\text{since } \lim_{x \to 0} \frac{e^{x} - 1}{x} = 1).
\]

**Result 9.4**

\[
\lim_{x \to 0} \frac{\log(1 + x)}{x} = 1.
\]

**Proof**

Take \( \log(1 + x) = y \). Then \( y \to 0 \) as \( x \to 0 \) and

\( 1 + x = e^{y} \), \( x = e^{y} - 1 \).

\[
\lim_{x \to 0} \frac{\log(1 + x)}{x} = \lim_{y \to 0} \frac{y}{e^{y} - 1} = \lim_{y \to 0} \frac{1}{\left( \frac{e^{y} - 1}{y} \right)} = \frac{1}{1} = 1.
\]

**Some important limits without proof**

Results 9.5 to 9.9

\[
\lim_{x \to 0} \frac{\sin^{-1} x}{x} = 1, \quad \lim_{x \to 0} \frac{\tan^{-1} x}{x} = 1
\]
\[
\lim_{x \to \infty} \left( 1 + \frac{1}{x} \right)^{x} \text{ exists and this limit is } e.
\]

**Note**

The number \( e \) is known as transcendental number in the sense that \( e \) never satisfies a polynomial (algebraic) equation of the form \( a_{0}x^{n} + a_{1}x^{n-1} + \dots + a_{n-1}x + a_{n} = 0 \) and \( 2 < e < 3 \).

### Example 9.32

Evaluate: \( \lim_{x \to 0} (1 + \sin x)^{2 \csc x} \).

**Solution**

Let \( \sin x = \frac{1}{y} \). As \( x \to 0 \), \( y \to \infty \) and

\[
\lim_{x \to 0} (1 + \sin x)^{2 \csc x} = \lim_{y \to \infty} \left( 1 + \frac{1}{y} \right)^{2y} = \left[ \lim_{y \to \infty} \left( 1 + \frac{1}{y} \right)^{y} \right]^{2} = e^{2}.
\]

### Example 9.33

Evaluate: \( \lim_{x \to \infty} \left( \frac{x + 2}{x - 2} \right)^{x} \).

**Solution**

\[
\lim_{x \to \infty} \left( \frac{x + 2}{x - 2} \right)^{x} = \lim_{x \to \infty} \left( \frac{x - 2 + 4}{x - 2} \right)^{x - 2 + 2}
\]
\[
= \lim_{x \to \infty} \left( 1 + \frac{4}{x - 2} \right)^{(x - 2) + 2}
\]

Let \( y = x - 2 \). As \( x \to \infty \), \( y \to \infty \).

\[
\lim_{x \to \infty} \left( \frac{x + 2}{x - 2} \right)^{x} = \lim_{y \to \infty} \left( 1 + \frac{4}{y} \right)^{y+2} = \lim_{y \to \infty} \left( 1 + \frac{4}{y} \right)^{y} \cdot \lim_{y \to \infty} \left( 1 + \frac{4}{y} \right)^{2}
\]
\[
= e^{4} \cdot (1)^{2} = e^{4}.
\]

### Example 9.34

Evaluate: \( \lim_{x \to \frac{\pi}{4}} \frac{4\sqrt{2} - (\cos x + \sin x)^{5}}{1 - \sin 2x} \).

**Solution**

\[
\frac{4\sqrt{2} - (\cos x + \sin x)^{5}}{1 - \sin 2x} = \frac{2^{\frac{5}{2}} - [(\cos x + \sin x)^{2}]^{\frac{5}{2}}}{1 - \sin 2x}
\]
\[
= \frac{2^{\frac{5}{2}} - (1 + \sin 2x)^{\frac{5}{2}}}{2 - (1 + \sin 2x)}
\]
\[
\lim_{x \to \frac{\pi}{4}} \frac{2^{\frac{5}{2}} - [(\cos x + \sin x)^{2}]^{5/2}}{2 - [1 + \sin 2x]} = \lim_{x \to \frac{\pi}{4}} \frac{2^{\frac{5}{2}} - (1 + \sin 2x)^{\frac{5}{2}}}{2 - (1 + \sin 2x)}.
\]

Take \( y = 1 + \sin 2x \). As \( x \to \frac{\pi}{4} \), \( y \to 2 \).

\[
= \lim_{y \to 2} \frac{2^{\frac{5}{2}} - y^{\frac{5}{2}}}{2 - y} = \frac{5}{2} \cdot 2^{\frac{5}{2} - 1} = \frac{5}{2} \times 2^{\frac{3}{2}} = 5\sqrt{2}.
\]

### Example 9.35

Do the limits of following functions exist as \( x \to 0 \)? State reasons for your answer.

(i) \( \frac{\sin |x|}{x} \) (ii) \( \frac{\sin x}{|x|} \) (iii) \( \frac{x|x|}{\sin |x|} \) (iv) \( \frac{\sin(x - |x|)}{x - |x|} \).

**Solution**

(i) \( f(x) = \frac{\sin |x|}{x} = \begin{cases} \frac{\sin(-x)}{x} = -\frac{\sin x}{x}, & x < 0 \\ \frac{\sin x}{x}, & x > 0 \end{cases} \)

\[
\lim_{x \to 0^{-}} f(x) = -1 \quad \text{and} \quad \lim_{x \to 0^{+}} f(x) = 1.
\]

Hence the limit does not exist.

(ii) \( f(x) = \frac{\sin x}{|x|} = \begin{cases} \frac{\sin x}{-x} = -\frac{\sin x}{x}, & x < 0 \\ \frac{\sin x}{x}, & x > 0 \end{cases} \)

\[
\lim_{x \to 0^{-}} f(x) = -1, \quad \lim_{x \to 0^{+}} f(x) = 1.
\]

Hence the limit does not exist.

(iii) \( f(x) = \frac{x|x|}{\sin |x|} = \begin{cases} \frac{x(-x)}{\sin(-x)} = \frac{-x^{2}}{-\sin x} = \frac{x^{2}}{\sin x}, & x < 0 \\ \frac{x \cdot x}{\sin x} = \frac{x^{2}}{\sin x}, & x > 0 \end{cases} \)

Thus \( \lim_{x \to 0} f(x) = \lim_{x \to 0} \frac{x^{2}}{\sin x} = \lim_{x \to 0} \frac{x}{\frac{\sin x}{x}} = 0 \). Hence the limit exists.

(iv) \( f(x) = \frac{\sin(x - |x|)}{x - |x|} \). For \( x > 0 \), \( x - |x| = 0 \). For \( x < 0 \), \( x - |x| = x - (-x) = 2x \).

Then \( \frac{\sin(x - |x|)}{x - |x|} = \begin{cases} \frac{\sin 0}{0} & \text{undefined for } x > 0 \\ \frac{\sin(2x)}{2x}, & x < 0 \end{cases} \)

Thus the function is not defined for \( x > 0 \). Hence the limit does not exist.

## EXERCISE 9.4

Evaluate the following limits:

(1) \( \lim_{x \to \infty} \left( 1 + \frac{1}{x} \right)^{x} \)

(2) \( \lim_{x \to \infty} \left( 1 + \frac{k}{x} \right)^{x} \)

(3) \( \lim_{x \to \infty} \left( 1 + \frac{3}{x} \right)^{x+2} \)

(4) \( \lim_{x \to 0} \frac{\sin^{3} \left( \frac{x}{2} \right)}{x^{3}} \)

(5) \( \lim_{x \to 0} \frac{\sin \alpha x}{\sin \beta x} \)

(6) \( \lim_{x \to 0} \frac{\tan 2x}{\sin 5x} \)

(7) \( \lim_{\alpha \to 0} \frac{\sin(\alpha^{n})}{(\sin \alpha)^{m}} \)

(8) \( \lim_{x \to 0} \frac{\sin(a + x) - \sin(a - x)}{x} \)

(9) \( \lim_{x \to 0} \frac{\sqrt{x^{2} + a^{2}} - a}{\sqrt{x^{2} + b^{2}} - b} \)

(10) \( \lim_{x \to 0} \frac{2 \arcsin x}{3x} \)

(11) \( \lim_{x \to 0} \frac{1 - \cos x}{x^{2}} \)

(12) \( \lim_{x \to 0} \frac{\tan 2x}{x} \)

(13) \( \lim_{x \to 0} \frac{2^{x} - 3^{x}}{x} \)

(14) \( \lim_{x \to 0} \frac{3^{x} - 1}{\sqrt{x + 1} - 1} \)

(15) \( \lim_{x \to 0} \frac{1 - \cos^{2} x}{x \sin 2x} \)

(16) \( \lim_{x \to \infty} \left[ \frac{1}{3^{x}} + 1 - \cos \left( \frac{1}{x} \right) - e^{\frac{1}{x}} \right] \)

(17) \( \lim_{x \to \infty} \{ x [\log(x + a) - \log(x)] \} \)

(18) \( \lim_{x \to \infty} \frac{\sin 3x}{\sin 2x} \)

(19) \( \lim_{x \to \pi} (1 + \sin x)^{2 \csc x} \)

(20) \( \lim_{x \to 0} \frac{\sqrt{2} - \sqrt{1 + \cos x}}{\sin^{2} x} \)

(21) \( \lim_{x \to 0} \frac{\sqrt{1 + \sin x} - \sqrt{1 - \sin x}}{\tan x} \)

(22) \( \lim_{x \to \infty} \left( \frac{x^{2} - 2x + 1}{x^{2} - 4x + 2} \right)^{x} \)

(23) \( \lim_{x \to 0} \frac{e^{x} - e^{-x}}{\sin x} \)

(24) \( \lim_{x \to 0} \frac{e^{ax} - e^{bx}}{x} \)

(25) \( \lim_{x \to 0} \frac{\sin x (1 - \cos x)}{x^{3}} \)

(26) \( \lim_{x \to 0} \frac{\tan x - \sin x}{x^{3}} \)

## 9.3 Continuity

One of the chief features in the behaviour of functions is the property known as continuity. It reflects mathematically the general trait of many phenomena observed by us in nature. For instance, we speak of the continuous expansion of a rod on heating, of the continuous growth of an organism, of a continuous flow, or a continuous variation of atmospheric temperature etc.

The idea of continuity of a function stems from the geometric notion of "no breaks in a graph". In fact, the name itself derives from the Latin continuere, "to hang together". Nevertheless, to identify continuity with "no breaks in a graph" or "a hanging together" has serious drawbacks, at least from the point of view of applying the concept to the analysis of functions. Accordingly, a premature use of the graph to gain insight into the meaning of continuity is advised against as gravely misleading. However, we will realise later that for functions with interval domains, continuity means essentially that the graph may be traced without lifting the point of the pencil.

The proper and effective way of attitude which allows us to put the concept to work is to correlate continuity with limit. Loosely speaking, to possess the property of continuity will mean "to have a favourable limit". In order to formulate the concept of continuity in terms of limit we must focus our attention at a point. Both continuity and limit are primarily concepts defined at a point, but continuity acquires a global character in a pointwise way.

For motivation, consider the following physical situation. A thermometer \( T \) measures temperatures along a given hot wire \( L \).

To each point \( x \) on the hot wire \( L \) is assigned a temperature readings \( t(x) \) on thermometer \( T \). Suppose, to fix ideas, the temperature recordings are observed to be the same, \( 250^{\circ}F \) as one moves along the wire \( L \) until a point \( x_{0} \) is reached on \( L \).

Then suppose that at \( x_{0} \) the temperature drops suddenly to near room temperature, say \( 75^{\circ}F \) as if an insulation were at \( x_{0} \). But, beyond \( x_{0} \) suppose readings of \( 250^{\circ}F \) are again observed. In function notation we are assuming that

\[
t(x) = \begin{cases}
250^{\circ}F, & x \neq x_{0} \\
75^{\circ}F, & x = x_{0}
\end{cases}
\]

Thus the point \( x_{0} \) stands out as singular point ("singular" means "special" or "unusual"). Analyzing the range of temperature readings, we should say that the approach of \( x \) to \( x_{0} \) had no bearing on the approach of the corresponding \( t(x) \) values to \( t(x_{0}) \). Briefly, a jump occurs at \( x_{0} \). Thus we would be led to say that the temperature function "lacks continuity at \( x_{0} \). For, we would have expected \( t(x_{0}) \) to be \( 250^{\circ}F \) since the \( x \) values neighbouring \( x_{0} \) showed \( t(x) = 250^{\circ}F \). We now abstract the notion of continuity, and demand that images be "close" when pre-images are "close". In our example the points on the hot wire were the pre-images, while the temperature readings there were the corresponding images.

The students should reflect on the intuitive idea of continuity by considering instead the contrasting idea of lack of continuity, or more simply "discontinuity" as manifested in every day experiences of abrupt changes which could be headed "then suddenly!". A few that come readily to mind are listed below along with functions which correspond as mathematical models:

(1) Switching on a light: light intensity as a function of time.
(2) Collision of a vehicle: Velocity as a function of time.
(3) Switching off a radio: Sound intensity as a function of time.
(4) Busting of a balloon: Radius as a function of air input.
(5) Breaking of a string: Tension as a function of length.
(6) Cost of postage: Postage as a function of weight.
(7) Income tax: Tax-rate as a function of taxable income.
(8) Age count in years: Age in whole years as a function of time.
(9) Cost of insurance premium: Premium as a function of age.

Actually, examples (1) - (5) are not quite accurate. For example, light intensity has a transparent but continuous passage from zero luminosity to positive luminosity. Indeed, nature appears to abhor discontinuity. On the other hand, (6) - (9) are in fact discontinuous and really show jumps at certain points.

Students are advised to relate the mathematical definition of continuity corresponds closely with the meaning of the word continuity in everyday language. A continuous process is one that takes place gradually, without interruption or abrupt change. That is, there are no holes, jumps or gaps. Following figure identifies three values of \( x \) at which the graph of a function \( f \) is not continuous. At all other points in the interval \( (a, b) \), the graph of \( f \) is uninterrupted and continuous.

It appears that continuity at \( x = x_{0} \) can be destroyed by any one of the following three conditions:

(1) The function is not defined at \( x = x_{0} \).

(2) The limit of \( f(x) \) does not exist at \( x = x_{0} \).

(3) The limit of \( f(x) \) exists at \( x = x_{0} \), but it is not equal to \( f(x_{0}) \).

Now let us look at the illustrative examples

#### Illustration 9.6

(i) \( f(x) = x^{2} + 3 \)
(ii) \( f(x) = \frac{16 - x^{2}}{4 + x} \)

(i) As \( x \to 2 \), the one sided limits are

\[
\lim_{x \to 2^{-}} f(x) = 7, \quad \lim_{x \to 2^{+}} f(x) = 7
\]

and hence \( \lim_{x \to 2} f(x) = 7 \) and moreover \( f(2) \) is defined and \( f(2) = 7 = \lim_{x \to 2} f(x) \). In this case \( f(x) \) is continuous at \( x = 2 \).

(ii) The one sided limits are:

\[
\lim_{x \to -4^{-}} f(x) = 8, \quad \lim_{x \to -4^{+}} f(x) = 8
\]

and therefore \( \lim_{x \to -4} f(x) = 8 \) but \( f(-4) \) does not exist.

Note that although \( \lim_{x \to -4} f(x) \) exists, the function value at \( -4 \), namely \( f(-4) \) is not defined. Thus the existence of \( \lim_{x \to -4} f(x) \) has no bearing on the existence of \( f(-4) \).

Now we formally define continuity as in

**Definition 9.7**

Let \( I \) be an open interval in \( \mathbb{R} \) containing \( x_{0} \). Let \( f : I \to \mathbb{R} \). Then \( f \) is said to be continuous at \( x_{0} \) if it is defined in a neighbourhood of this point and if the limit of this function, as the independent variable \( x \) tends to \( x_{0} \) exists and is equal to the value of the function at \( x = x_{0} \).

Thus three requirements have to be satisfied for the continuity of a function \( y = f(x) \) at \( x = x_{0} \):

(i) \( f(x) \) must be defined in a neighbourhood of \( x_{0} \) (i.e., \( f(x_{0}) \) exists);

(ii) \( \lim_{x \to x_{0}} f(x) \) exists;

(iii) \( f(x_{0}) = \lim_{x \to x_{0}} f(x) \).

The condition (iii) can be reformulated as \( \lim_{\Delta x \to 0} [f(x_{0} + \Delta x) - f(x_{0})] = 0 \) and the continuity of \( f \) at \( x_{0} \) can be restated as follows:

**Definition 9.8**

A function \( y = f(x) \) is said to be continuous at a point \( x_{0} \) (or at \( x = x_{0} \)) if it is defined in some neighbourhood of \( x_{0} \) and if \( \lim_{\Delta x \to 0} [f(x_{0} + \Delta x) - f(x_{0})] = 0 \).

The condition (iii) can also be put in the form \( \lim_{x \to x_{0}} f(x) = f\left( \lim_{x \to x_{0}} x \right) \). Thus, if the symbol of the limit and the symbol of the function can be interchanged, the function is continuous at the limiting value of the argument.

### 9.3.1 Examples of functions Continuous at a point

(1) Constant function is continuous at each point of \( \mathbb{R} \).

Let \( f(x) = k \), \( k \in \mathbb{R} \) is constant. If \( x_{0} \in \mathbb{R} \), then \( f(x_{0}) = k \).

\[
\lim_{x \to x_{0}} f(x) = \lim_{x \to x_{0}} (k) = k.
\]

(2) Power functions with positive integer exponents are continuous at every point of \( \mathbb{R} \)

If \( f(x) = x^{n} \), domain of \( f \) is \( \mathbb{R} = (-\infty, \infty) \) and \( \lim_{x \to x_{0}} x^{n} = x_{0}^{n} \), \( x_{0} \in \mathbb{R} \) by the limit theorem.

(3) Polynomial functions, \( p(x) = a_{0}x^{n} + a_{1}x^{n-1} + \dots + a_{n-1}x + a_{n} \), \( a_{0} \neq 0 \) are continuous at every point of \( \mathbb{R} \). By limit theorem,

\[
\lim_{x \to x_{0}} p(x) = a_{0}x_{0}^{n} + a_{1}x_{0}^{n-1} + \dots + a_{n-1}x_{0} + a_{n} = p(x_{0}).
\]

(4) Quotients of polynomials namely rational functions of the form \( R(x) = \frac{p(x)}{q(x)} \), are continuous at every point where \( q(x) \neq 0 \), and

\[
\lim_{x \to x_{0}} R(x) = \frac{\lim_{x \to x_{0}} p(x)}{\lim_{x \to x_{0}} q(x)} = \frac{p(x_{0})}{q(x_{0})} = R(x_{0}).
\]

(5) The circular functions \( \sin x \) and \( \cos x \) are continuous at every point of their domain \( \mathbb{R} = (-\infty, \infty) \) since \( \lim_{x \to x_{0}} \sin x = \sin x_{0} \), \( \lim_{x \to x_{0}} \cos x = \cos x_{0} \).

As a consequence, \( \tan x \), \( \cot x \), \( \csc x \), \( \sec x \) are continuous on their proper domains in view of the reciprocal and quotient rules in the algebra of limits.

(6) The \( n \)th root functions, \( f(x) = x^{\frac{1}{n}} \) are continuous in their proper domain since \( \lim_{x \to x_{0}} \left( x^{\frac{1}{n}} \right) = x_{0}^{\frac{1}{n}} \).

(7) The reciprocal function \( f(x) = \frac{1}{x} \) is not defined at 0 and hence it is not continuous at 0. It is continuous at each point of \( \mathbb{R} - \{0\} \).

(8) \( h(x) = \begin{cases} x + 1, & x \leq 0 \\ x^{2} + 1, & x > 0 \end{cases} \)

\[
\lim_{x \to 0^{-}} h(x) = \lim_{x \to 0} (x + 1) = 1 = h(0)
\]
\[
\lim_{x \to 0^{+}} h(x) = \lim_{x \to 0^{+}} (x^{2} + 1) = 1 = h(0).
\]

Thus \( h(x) \) is continuous at \( x = 0 \). Indeed, \( h(x) \) is continuous at each point of \( (-\infty, 0) \) and each point of \( (0, \infty) \) and hence \( h \) is continuous in the whole of \( (-\infty, \infty) \).

(9) The greatest integer function \( f(x) = \lfloor x \rfloor \) is not continuous at \( x = 0 \).

For, \( \lim_{x \to 0^{-}} \lfloor x \rfloor = -1 \) and \( \lim_{x \to 0^{+}} \lfloor x \rfloor = 0 \). It is discontinuous at each integer point. In fact,

\[
\lim_{x \to n^{-}} \lfloor x \rfloor = n - 1 \quad \text{and} \quad \lim_{x \to n^{+}} \lfloor x \rfloor = n.
\]

(10) The modulus function \( f(x) = |x| \) is continuous at all points of the real line \( \mathbb{R} \).

In particular,

\[
\lim_{x \to 0^{-}} |x| = \lim_{x \to 0^{-}} (-x) = 0, \quad \lim_{x \to 0^{+}} |x| = \lim_{x \to 0^{+}} (x) = 0,
\]
\[
\text{and } \lim_{x \to 0^{-}} f(x) = 0 = \lim_{x \to 0^{+}} f(x) = 0 = f(0).
\]

(11) The exponential function \( f(x) = e^{x} \) is continuous on \( \mathbb{R} \).

(12) The logarithmic function \( f(x) = \log x (x > 0) \) is continuous in \( (0, \infty) \).

### 9.3.2 Algebra of continuous functions

If \( f \) and \( g \) are continuous at \( x_{0} \) then

(1) \( f + g \) is continuous at \( x = x_{0} \)

(2) \( f - g \) is continuous at \( x = x_{0} \)

(3) \( f \cdot g \) is continuous at \( x = x_{0} \)

(4) \( \frac{f}{g} \) is continuous at \( x = x_{0} \) (\( g(x) \neq 0 \))

(5) Composite function theorem on continuity: If \( f \) is continuous at \( g(x_{0}) \) and \( g \) is continuous at \( x_{0} \) then \( f \circ g \) is continuous at \( x_{0} \).

### Continuity in a closed interval

**Definition 9.9**

A function \( f : [a, b] \to \mathbb{R} \) is said to be continuous on the closed interval \( [a, b] \) if it is continuous on the open interval \( (a, b) \) and

\[
\lim_{x \to a^{+}} f(x) = f(a) \quad \text{and} \quad \lim_{x \to b^{-}} f(x) = f(b).
\]

That is, the function \( f \) is continuous from the right at \( a \) and continuous from the left at \( b \) and is continuous at each point \( x_{0} \in (a, b) \).

#### Illustration 9.7

Discuss the continuity of \( f(x) = \sqrt{1 - x^{2}} \).

The domain of definition of \( f \) is the closed interval \( [-1, 1] \). \( f \) is defined if \( 1 - x^{2} \geq 0 \).

For any point \( c \in (-1, 1) \)

\[
\lim_{x \to c} f(x) = \lim_{x \to c} \sqrt{1 - x^{2}} = \left[ \lim_{x \to c} (1 - x^{2}) \right]^{\frac{1}{2}} = (1 - c^{2})^{\frac{1}{2}} = f(c).
\]
\[
\lim_{x \to -1^{+}} f(x) = \lim_{x \to -1^{+}} (1 - x^{2})^{\frac{1}{2}} = 0 = f(-1)
\]
\[
\lim_{x \to 1^{-}} f(x) = \lim_{x \to 1^{-}} (1 - x^{2})^{\frac{1}{2}} = 0 = f(1).
\]

Thus \( f \) is continuous on \( [-1, 1] \). One can also solve this problem using composite function theorem.

### Example 9.36

Describe the interval(s) on which each function is continuous.

(i) \( f(x) = \tan x \)
(ii) \( g(x) = \sin \frac{1}{x} \)
(iii) \( h(x) = \begin{cases} x \sin \frac{1}{x}, & x \neq 0 \\ 0, & x = 0 \end{cases} \)

**Solution**

(i) The tangent function \( f(x) = \tan x \) is undefined at \( x = (2n + 1)\frac{\pi}{2} \), \( n \in \mathbb{Z} \). At all other points it is continuous, so \( f(x) = \tan x \) is continuous on each of the open intervals

\[
\ldots, \left( -\frac{3\pi}{2}, -\frac{\pi}{2} \right), \left( -\frac{\pi}{2}, \frac{\pi}{2} \right), \left( \frac{\pi}{2}, \frac{3\pi}{2} \right), \ldots
\]

(ii) The function \( g(x) = \sin \frac{1}{x} \) is continuous at all points except \( x = 0 \), where \( \lim_{x \to 0} g(x) \) does not exist. So, \( g \) is continuous on the intervals \( (-\infty, 0) \) and \( (0, \infty) \).

(iii) The function \( h(x) \) is defined at all points of the real line \( \mathbb{R} = (-\infty, \infty) \); for any \( x_{0} \neq 0 \)

\[
\lim_{x \to x_{0}} h(x) = \lim_{x \to x_{0}} x \sin \frac{1}{x} = x_{0} \sin \frac{1}{x_{0}} = h(x_{0}).
\]

For \( x_{0} = 0 \),

\[
h(x) = x \sin \frac{1}{x}, \quad -x \leq x \sin \frac{1}{x} \leq x
\]
\[
\lim_{x \to 0} (-x) = 0, \quad \lim_{x \to 0} x = 0.
\]

By Sandwich theorem \( \lim_{x \to 0} \left( x \sin \frac{1}{x} \right) = 0 = h(0) \). Therefore \( h(x) \) is continuous in the entire real line.

### Example 9.37

A tomato wholesaler finds that the price of newly harvested tomatoes is \( \text{₹}0.16 \) per kg if he purchases fewer than 100 kg each day. However, if he purchases at least 100 kg daily, the price drops to \( \text{₹}0.14 \) per kg. Find the total cost function and discuss the cost when the purchase is 100 kg.

**Solution**

Let \( x \) denote the number of kilograms bought per day and \( C \) denote the cost. Then,

\[
C(x) = \begin{cases}
0.16x, & \text{if } 0 \leq x < 100 \\
0.14x, & \text{if } x \geq 100
\end{cases}
\]

The sketch of this function is shown in Fig. 9.37.

Note that \( C(100) = 14 \). Thus,

\[
\lim_{x \to 100^{-}} C(x) = 16 \neq 14 = \lim_{x \to 100^{+}} C(x) \neq C(100).
\]

Note also that the function jumps from one finite value 14 to another finite value 16.

### 9.3.3 Removable and Jump Discontinuities

Let us look at the following functions:

\[
f(x) = \frac{\sin x}{x}
\]
\[
g(x) = C(x), \text{ where } C(x) \text{ is as defined in Example 9.37}
\]

The function \( f(x) \) is defined at all points of the real line except \( x = 0 \). That is, \( f(0) \) is undefined, but \( \lim_{x \to 0} \frac{\sin x}{x} = 1 \) exists. If we redefine the function \( f(x) \) as

\[
h(x) = \begin{cases}
\frac{\sin x}{x}, & x \neq 0 \\
1, & x = 0
\end{cases}
\]

\( h \) is defined at all points of the real line including \( x = 0 \). Moreover, \( h \) is continuous at \( x = 0 \) since

\[
\lim_{x \to 0} h(x) = \lim_{x \to 0} \frac{\sin x}{x} = 1 = h(0).
\]

Note that \( h(x) = f(x) \) for all \( x \neq 0 \). Even though the original function \( f(x) \) fails to be continuous at \( x = 0 \), the redefined function became continuous at 0. That is, we could remove the discontinuity by redefining the function. Such discontinuous points are called removable discontinuities. This example leads us to have the following.

**Definition 9.10**

A function \( f \) defined on an interval \( I \subseteq \mathbb{R} \) is said to have removable discontinuity at \( x_{0} \in I \) if there is a function \( h : I \to \mathbb{R} \) such that

\[
h(x) = \begin{cases}
f(x), & \text{if } x \neq x_{0} \\
\lim_{x \to x_{0}} f(x), & \text{if } x = x_{0}
\end{cases}
\]

Note that for removable discontinuity, \( \lim_{x \to x_{0}} f(x) \) must exist.

Now if we examine the function \( g(x) = C(x) \) (see Example 9.37), even though it is defined at all points of \( [0, \infty) \), \( \lim_{x \to 100} g(x) \) does not exist and it has a jump of height \( \lim_{x \to 100^{+}} g(x) - \lim_{x \to 100^{-}} g(x) = 16 - 14 = 2 \), which is finite. Since \( \lim_{x \to 100} g(x) \) does not exist, it is not continuous at \( x = 100 \). Such discontinuities are called jump discontinuities. Thus we have the following:

**Definition 9.11**

Let \( f \) be a function defined on an interval \( I \subseteq \mathbb{R} \). Then \( f \) is said to have jump discontinuity at a point \( x_{0} \in I \) if \( f \) is defined at \( x_{0} \),

\[
\lim_{x \to x_{0}^{-}} f(x) \quad \text{and} \quad \lim_{x \to x_{0}^{+}} f(x) \text{ exist but}
\]
\[
\lim_{x \to x_{0}^{-}} f(x) \neq \lim_{x \to x_{0}^{+}} f(x).
\]

### Example 9.38

Determine if \( f \) defined by \( f(x) = \begin{cases} x^{2} \sin \frac{1}{x}, & \text{if } x \neq 0 \\ 0, & \text{if } x = 0 \end{cases} \) is continuous in \( \mathbb{R} \).

**Solution**

By Sandwich theorem \( \lim_{x \to 0} x^{2} \sin \frac{1}{x} = 0 \) and \( f(0) = 0 \) by the definition of \( f(x) \). Hence it is continuous at \( x = 0 \). For other values it is clearly continuous and hence continuous in \( \mathbb{R} \).

## EXERCISE 9.5

(1) Prove that \( f(x) = 2x^{2} + 3x - 5 \) is continuous at all points in \( \mathbb{R} \).

(2) Examine the continuity of the following:

(i) \( x^{2} \cos x \)
(ii) \( e^{x} \tan x \)
(iii) \( e^{2x} + x^{2} \)
(iv) \( x \ln x \)
(v) \( \frac{\sin x}{x^{2}} \)
(vi) \( \frac{x^{2} - 16}{x + 4} \)
(vii) \( |x + 2| + |x - 1| \)
(viii) \( \frac{|x - 2|}{|x + 1|} \)
(ix) \( \cot x + \tan x \)

(3) Find the points of discontinuity of the function \( f \), where

\[
f(x) = \begin{cases}
4x + 5, & x \leq -1 \\
3x - 2, & -1 < x < 2 \\
2x + 3, & x \geq 2
\end{cases}
\]

(4) At the given point \( x_{0} \) discover whether the given function is continuous or discontinuous citing the reasons for your answer:

\[
f(x) = \begin{cases}
\frac{x^{2} - 4}{x - 2}, & x \neq 2 \\
4, & x = 2
\end{cases} \quad \text{at } x_{0} = 2
\]

(5) Show that the function \( \begin{cases} \frac{x^{3} - 1}{x - 1}, & \text{if } x \neq 1 \\ 3, & \text{if } x = 1 \end{cases} \) is continuous on \( (-\infty, \infty) \).

(6) For what value of \( \alpha \) is this function \( f(x) = \begin{cases} \frac{x^{4} - 1}{x - 1}, & \text{if } x \neq 1 \\ \alpha, & \text{if } x = 1 \end{cases} \) continuous at \( x = 1 \)?

(7) Let \( f(x) = \begin{cases} 0, & \text{if } x < 0 \\ x^{2}, & \text{if } 0 \leq x < 2 \\ 4, & \text{if } x \geq 2 \end{cases} \). Graph the function. Show that \( f(x) \) is continuous on \( (-\infty, \infty) \).

(8) If \( f \) and \( g \) are continuous functions with \( f(3) = 5 \) and \( \lim_{x \to 3} [2f(x) - g(x)] = 4 \), find \( g(3) \).

(9) Find the points at which \( f \) is discontinuous. At which of these points \( f \) is continuous from the right, from the left, or neither?

(i) \( f(x) = \begin{cases} 2x + 1, & \text{if } x \leq -1 \\ 3x, & \text{if } -1 < x < 1 \\ 2x - 1, & \text{if } x \geq 1 \end{cases} \)

(ii) \( f(x) = \begin{cases} (x - 1)^{3}, & \text{if } x < 0 \\ (x + 1)^{3}, & \text{if } x \geq 0 \end{cases} \)

(10) A function \( f \) is defined as follows:
\[
f(x) = \begin{cases}
0, & \text{for } x < 0 \\
x, & \text{for } 0 \leq x < 1 \\
-x^{2} + 4x - 2, & \text{for } 1 \leq x < 3 \\
4 - x, & \text{for } x \geq 3
\end{cases}
\]
Is the function continuous?

(11) Which of the following functions \( f \) has a removable discontinuity at \( x = x_{0} \)? If the discontinuity is removable, find a function \( g \) that agrees with \( f \) for \( x \neq x_{0} \) and is continuous on \( \mathbb{R} \).

(i) \( f(x) = \frac{x^{2} - 2x - 8}{x + 2}, \quad x_{0} = -2 \)

(ii) \( f(x) = \frac{x^{3} + 64}{x + 4}, \quad x_{0} = -4 \)

(iii) \( f(x) = \frac{3 - \sqrt{x}}{9 - x}, \quad x_{0} = 9 \)

(12) Find the constant \( b \) that makes \( g \) continuous on \( (-\infty, \infty) \).
\[
g(x) = \begin{cases}
x^{2} - b^{2}, & \text{if } x < 4 \\
bx + 20, & \text{if } x \geq 4
\end{cases}
\]

(13) Consider the function \( f(x) = x \sin \frac{\pi}{x} \). What value must we give \( f(0) \) in order to make the function continuous everywhere?

(14) The function \( f(x) = \frac{x^{2} - 1}{x^{3} - 1} \) is not defined at \( x = 1 \). What value must we give \( f(1) \) in order to make \( f(x) \) continuous at \( x = 1 \)?

(15) State how continuity is destroyed at \( x = x_{0} \) for each of the following graphs.

## EXERCISE 9.6

Choose the correct or the most suitable answer from the given four alternatives.

(1) \( \lim_{x \to \infty} \frac{\sin x}{x} \)
(1) 1
(2) 0
(3) \( \infty \)
(4) \( -\infty \)

(2) \( \lim_{x \to \pi/2} \frac{\cos x}{x - \pi/2} \)
(1) 1
(2) -1
(3) 0
(4) does not exist

(3) \( \lim_{x \to 0} \frac{1 - \cos 2x}{x} \)
(1) 0
(2) 1
(3) 2
(4) does not exist

(4) \( \lim_{\theta \to 0} \frac{\sin \theta}{\sin \theta} \)
(1) 1
(2) -1
(3) 0
(4) 2

(5) \( \lim_{x \to \infty} \left( \frac{x^{2} + 5x + 3}{x^{2} + x + 3} \right)^{x} \)
(1) \( e^{4} \)
(2) \( e^{2} \)
(3) \( e^{3} \)
(4) 1

(6) \( \lim_{x \to \infty} \frac{\sqrt{x^{2} - 1}}{2x + 1} = \)
(1) 1
(2) 0
(3) -1
(4) \( \frac{1}{2} \)

(7) \( \lim_{x \to 0} \frac{a^{x} - b^{x}}{x} = \)
(1) \( \log ab \)
(2) \( \log \left( \frac{a}{b} \right) \)
(3) \( \log \left( \frac{b}{a} \right) \)
(4) \( \frac{a}{b} \)

(8) \( \lim_{x \to 0} \frac{8^{x} - 4^{x} - 2^{x} + 1^{x}}{x^{2}} = \)
(1) \( 2 \log 2 \)
(2) \( 2 (\log 2)^{2} \)
(3) \( \log 2 \)
(4) \( 3 \log 2 \)

(9) If \( f(x) = x(-1)^{\lfloor \frac{1}{x} \rfloor} \), \( x \leq 0 \), then the value of \( \lim_{x \to 0} f(x) \) is equal to
(1) -1
(2) 0
(3) 2
(4) 4

(10) \( \lim_{x \to 1} \lfloor x \rfloor = \)
(1) 2
(2) 3
(3) does not exist
(4) 0

(11) Let the function \( f \) be defined by \( f(x) = \begin{cases} 3x, & 0 \leq x \leq 1 \\ -3x + 5, & 1 < x \leq 2 \end{cases} \), then
(1) \( \lim_{x \to 1} f(x) = 1 \)
(2) \( \lim_{x \to 1} f(x) = 3 \)
(3) \( \lim_{x \to 1} f(x) = 2 \)
(4) \( \lim_{x \to 1} f(x) \) does not exist

(12) If \( f : \mathbb{R} \to \mathbb{R} \) is defined by \( f(x) = |x - 3| + |x - 4| \) for \( x \in \mathbb{R} \), then \( \lim_{x \to 3^{-}} f(x) \) is equal to
(1) -2
(2) -1
(3) 0
(4) 1

(13) \( \lim_{x \to 0} \frac{x e^{x} - \sin x}{x} \) is
(1) 1
(2) 2
(3) 3
(4) 0

(14) If \( \lim_{x \to 0} \frac{\sin px}{\tan 3x} = 4 \), then the value of \( p \) is
(1) 6
(2) 9
(3) 12
(4) 4

(15) \( \lim_{\alpha \to \pi/4} \frac{\sin \alpha - \cos \alpha}{\alpha - \frac{\pi}{4}} \) is
(1) \( \sqrt{2} \)
(2) \( \frac{1}{\sqrt{2}} \)
(3) 1
(4) 2

(16) \( \lim_{n \to \infty} \left( \frac{1}{n^{2}} + \frac{2}{n^{2}} + \frac{3}{n^{2}} + \ldots + \frac{n}{n^{2}} \right) \) is
(1) \( \frac{1}{2} \)
(2) 0
(3) 1
(4) \( \infty \)

(17) \( \lim_{x \to 0} \frac{e^{x} - 1}{\sin x} = \)
(1) 1
(2) e
(3) \( \frac{1}{e} \)
(4) 0

(18) \( \lim_{x \to 0} \frac{e^{\tan x} - e^{x}}{\tan x - x} = \)
(1) 1
(2) e
(3) \( \frac{1}{2} \)
(4) 0

(19) The value of \( \lim_{x \to 0} \frac{\sin x}{\sqrt{x^{2}}} \) is
(1) 1
(2) -1
(3) 0
(4) limit does not exist

(20) The value of \( \lim_{x \to k^{-}} \frac{x - \lfloor x \rfloor}{x - k} \), where \( k \) is an integer is
(1) -1
(2) 1
(3) 0
(4) 2

(21) At \( x = \frac{3}{2} \) the function \( f(x) = \frac{|2x - 3|}{2x - 3} \) is
(1) continuous
(2) discontinuous
(3) differentiable
(4) non-zero

(22) Let \( f : \mathbb{R} \to \mathbb{R} \) be defined by \( f(x) = \begin{cases} x, & \text{if } x \text{ is irrational} \\ 1 - x, & \text{if } x \text{ is rational} \end{cases} \) then \( f \) is
(1) discontinuous at \( x = \frac{1}{2} \)
(2) continuous at \( x = \frac{1}{2} \)
(3) continuous everywhere
(4) discontinuous everywhere

(23) If \( f(x) = \begin{cases} \frac{x^{3} - 1}{x + 1}, & x \neq -1 \\ p, & x = -1 \end{cases} \) is continuous at \( x = -1 \), then \( p \) is
(1) \( \frac{2}{3} \)
(2) \( -\frac{2}{3} \)
(3) 1
(4) 0

(24) Let \( f \) be a continuous function on \( [2, 5] \). If \( f \) takes only rational values for all \( x \) and \( f(3) = 12 \), then \( f(4.5) \) is equal to
(1) \( \frac{f(3)}{f(4.5)} 7.5 \)
(2) 12
(3) 17.5
(4) \( \frac{f(4.5)}{f(3)} 1.5 \)

(25) Let a function \( f \) be defined by \( f(x) = \frac{|x|}{x} \) for \( x \neq 0 \) and \( f(0) = 0 \). Then \( f \) is
(1) continuous nowhere
(2) continuous everywhere
(3) continuous for all \( x \) except \( x = 1 \)
(4) continuous for all \( x \) except \( x = 0 \)

## SUMMARY

In this chapter we have acquired the knowledge of

- Limit of a function \( y = f(x) \) as \( x \) approaches \( x_{0} \) from the lower values of \( x_{0} \).
- Limit of \( y = f(x) \) as \( x \) approaches \( x_{0} \) from the higher values of \( x_{0} \).
- Limit of a function as \( x \) approaches \( x_{0} \), in the deleted neighbourhood of \( x_{0} \) exists if and only if \( \lim_{x \to x_{0}^{-}} f(x) = L = \lim_{x \to x_{0}^{+}} f(x) \).
- \( \lim_{x \to x_{0}} f(x) = L \) also means that \( f(x) \) converges to \( L \) as \( x \) approaches \( x_{0} \) from either side of \( x_{0} \) except at \( x = x_{0} \).
- If \( \lim_{x \to x_{0}} f(x) \) and \( \lim_{x \to x_{0}} g(x) \) exist then
  \[
  \lim_{x \to x_{0}} [f(x) \pm g(x)] = \lim_{x \to x_{0}} f(x) \pm \lim_{x \to x_{0}} g(x)
  \]
  \[
  \lim_{x \to x_{0}} [f(x) g(x)] = \lim_{x \to x_{0}} f(x) \cdot \lim_{x \to x_{0}} g(x)
  \]
  \[
  \lim_{x \to x_{0}} \left[ \frac{f(x)}{g(x)} \right] = \frac{\lim_{x \to x_{0}} f(x)}{\lim_{x \to x_{0}} g(x)} \quad \text{if } g(x) \neq 0 \text{ and } \lim_{x \to x_{0}} g(x) \neq 0.
  \]
- Limit of \( f(x) \) as \( x \) approaches \( x_{0} \) does not exist if either \( f(x) \to \pm \infty \) as \( x \to x_{0}^{-} \) or \( f(x) \to \pm \infty \) as \( x \to x_{0}^{+} \) or \( \lim_{x \to x_{0}^{-}} f(x) = l_{1} \neq l_{2} = \lim_{x \to x_{0}^{+}} f(x) \).
- \( (M, \infty) \) is the neighbourhood of \( +\infty \), \( M > 0 \); \( (-\infty, K) \) is the neighbourhood of \( -\infty \), \( K < 0 \).
- If \( f(x) \to \pm \infty \) as \( x \to x_{0} \) then \( x = x_{0} \) is a vertical asymptote.
- The line \( y = l_{1} \) (or \( l_{2} \)) is a horizontal asymptote of the curve \( y = f(x) \) if either \( f(x) \to l_{1} \) as \( x \to \infty \) or \( f(x) \to l_{2} \) as \( x \to -\infty \).
- \( f(x) \) is continuous at \( x_{0} \) if and only if
  \[
  \lim_{x \to x_{0}} f(x) = f(x_{0})
  \]
  \[
  \lim_{\Delta x \to 0} [f(x_{0} + \Delta x) - f(x_{0})] = 0
  \]
  \[
  \lim_{x \to x_{0}} f(x) = f\left( \lim_{x \to x_{0}} x \right).
  \]
- Jump and removable discontinuities.
