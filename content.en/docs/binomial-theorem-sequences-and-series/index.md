---
title: 'combinatorics and mathematical induction'
weight: 5
---

# Chapter 5: Binomial Theorem, Sequences and Series

## 5.1 Introduction

Binomial theorem facilitates the algebraic expansion of the binomial \( (a + b) \) for a positive integral exponent \( n \). Binomial theorem is used in all branches of Mathematics and also in other Sciences. For example using the Binomial theorem one can easily find the coefficient of \( x^{20} \) in the expansion of \( (2x - 7)^{23} \). If one wants to know the maturity amount after 10 years on a sum of money deposited in a nationalised bank at the rate of \( 8\% \) compound interest per year or to know the size of population of our country after 15 years if the annual growth rate and present population size are known, Binomial theorem helps us in finding the above quantities. The coefficients in the binomial expansion of \( (a + b)^n \), \( n \in \mathbb{N} \), are called binomial coefficients. Binomial theorem plays a vital role in determining the probabilities of events when the random experiment involves finite sample space and each outcome is either success or failure. In this chapter we learn binomial theorem and some of its applications.

Greek Mathematician Euclid mentioned the special case of binomial theorem for exponent 2. Binomial theorem for exponent 3 was known by \( 6^{th} \) century in India. In 1544, Michael Stifel (German Mathematician) introduced the term binomial coefficient and expressed \( (1 + x)^n \) in terms of \( (1 + x)^{n - 1} \).

The German Mathematician Johann Carl Friedrich Gauss is one of the most renowned Mathematicians in history. Many have referred to him as the "Prince of Mathematics". He has contributed in the areas of Number theory, Physics, Astronomy etc., Number Theory was Gauss's favourite field and he referred to Number theory as the "Queen of Mathematics". Anecdote involves, his school teacher who wanted to test the students asked them to sum the integers from 1 to 100. Within a few seconds Gauss showed the answer has 5050. Nobody is sure which method of summing an arithmetic sequence Gauss used as a child.

Over the period of thousand years, legends have developed mathematical problems involving sequences and series. One of the famous legends about series concerns the invention of chess, where the cells of chess board were related to 1, 2, 4, 8, ... (imagine the number related to \( 64^{th} \) cell). There are many applications of arithmetic and geometric progressions to real life situations.

In the earlier classes we have learnt about sequences, series. Roughly speaking a sequence is an arrangement of objects in some order and a series is the sum of the terms of a sequence of numbers. The concept of infinite series helps us to compute many values, like \( \sin \frac{9}{44}\pi \), \( \log 43 \) and \( e^{20} \) to a desired level of approximation. Sequences are important in differential equations and analysis. We learn more about sequences and series.

## Learning Objectives

On completion of this chapter, the students are expected to know

- the concept of Binomial Theorem, to compute binomial coefficients and their applications
- the concepts of sequences and series
- how to compute arithmetic, geometric and harmonic means
- how to find the sum of finite and infinite series of real numbers
- how to add series using telescopic summation
- how to apply binomial, exponential and logarithmic series

## 5.2 Binomial Theorem

The prefix bi in the words bicycle, binocular, binary and in many more words means two. The word binomial stands for expressions having two terms. For examples \( (1 + x) \), \( (x + y) \), \( (x^{2} + xy) \) and \( (2a + 3b) \) are some binomial expressions.

### 5.2.1 Binomial Coefficients

In Chapter 4 we have learnt and used the symbol \( ^{n}C_{r} \) which is defined as

\[
^{n}C_{r} = \frac{n(n - 1)(n - 2)\ldots(n - (r - 1))}{r(r - 1)(r - 2)\ldots1} = \frac{n!}{(n - r)!r!}.
\]

Since \( ^{n}C_{r} \) occurs as the coefficients of \( x^{r} \) in \( (1 + x)^{n} \), \( n\in \mathbb{N} \) and as the coefficients of \( a^{r}b^{n - r} \) in \( (a + b)^{n} \), they are called binomial coefficients. Though the values of \( ^{n}C_{r} \) can be computed by formula, there is an interesting simple way to find \( ^{n}C_{r} \) without doing cumbersome multiplications.

### Pascal Triangle

The Pascal triangle is an arrangement of the values of \( ^{n}C_{r} \) in a triangular form. The \( (k + 1)^{st} \) row consists values of

\[
^{k}C_{0}, ^{k}C_{1}, ^{k}C_{2}, ^{k}C_{3}, \ldots , ^{k}C_{k}.
\]

In fact, the Pascal triangle is

\[
(a + b)^{0} = 1
\]
\[
(a + b)^{1} = a + b
\]
\[
(a + b)^{2} = a^{2} + 2ab + b^{2}
\]
\[
(a + b)^{3} = a^{3} + 3a^{2}b + 3ab^{2} + b^{3}
\]

If we observe carefully the Pascal triangle, we may notice that each row starts and ends with 1 and other entries are the sum of the two numbers just above it. For example '3' is the sum of 1 and 2 above it; '10' is the sum of 4 and 6 above it. We will prove in a short while that

\[
(a + b)^{n} = {}^{n}\mathrm{C}_{0}a^{n}b^{0} + {}^{n}\mathrm{C}_{1}a^{n - 1}b^{1} + \dots +{}^{n}\mathrm{C}_{r}a^{n - r}b^{r} + \dots +{}^{n}\mathrm{C}_{n}a^{0}b^{n}
\]

which is the binomial expansion of \( (a + b)^{n} \). The binomial expansion of \( (a + b)^{n} \) for any \( n\in \mathbb{N} \) can be written using Pascal triangle. For example, from the fifth row we can write down the expansion of \( (a + b)^{4} \) and from the sixth row we can write down the expansion of \( (a + b)^{5} \) and so on. We know the terms (without coefficients) of \( (a + b)^{5} \) are

\[
a^{5}, a^{4}b, a^{3}b^{2}, a^{2}b^{3}, ab^{4}, b^{5}
\]

and the sixth row of the Pascal triangle is

\[
1 \quad 5 \quad 10 \quad 10 \quad 5 \quad 1.
\]

Using these two we can write

\[
(a + b)^{5} = a^{5} + 5a^{4}b + 10a^{3}b^{2} + 10a^{2}b^{3} + 5ab^{4} + b^{5}.
\]

The Pascal triangle can be constructed using addition alone, without using any multiplication or division. So without multiplication we can write down the binomial expansion for \( (a + b)^{n} \) for any \( n\in \mathbb{N} \).

The above pattern resembling a triangle, is credited in the name of the seventeenth century French Mathematician Blaise Pascal, who studied mathematical properties of this structure and used this concept effectively in Probability Theory.

### 5.2.2 Binomial theorem for positive integral index

Now we prove the most celebrated theorem called Binomial Theorem.

**Theorem 5.1 (Binomial theorem for positive integral index):** If \( n \) is any positive integer, then

\[
(a + b)^{n} = {}^{n}\mathrm{C}_{0}a^{n}b^{0} + {}^{n}\mathrm{C}_{1}a^{n - 1}b^{1} + \dots +{}^{n}\mathrm{C}_{r}a^{n - r}b^{r} + \dots +{}^{n}\mathrm{C}_{n}a^{0}b^{n}.
\]

**Proof.** We prove the theorem by using mathematical induction. For any positive integer \( n \), let \( P(n) \) be the statement

\[
(a + b)^{n} = {}^{n}\mathrm{C}_{0}a^{n}b^{0} + {}^{n}\mathrm{C}_{1}a^{n - 1}b^{1} + \dots +{}^{n}\mathrm{C}_{r}a^{n - r}b^{r} + \dots +{}^{n}\mathrm{C}_{n}a^{0}b^{n}.
\]

Since \( ^{1}\mathrm{C}_{0} = 1 \) and \( ^{1}\mathrm{C}_{1} = 1 \), we have

\[
(a + b)^{1} = a + b = {}^{1}\mathrm{C}_{0}a^{1}b^{0} + {}^{1}\mathrm{C}_{1}a^{0}b^{1}
\]

Thus, \( P(1) \) is true.

Assume that \( P(m) \) is true for some positive integer \( m \). That is,

\[
(a + b)^{m} = {}^{m}\mathrm{C}_{0}a^{m}b^{0} + {}^{m}\mathrm{C}_{1}a^{m - 1}b^{1} + \dots +{}^{m}\mathrm{C}_{m - 1}a^{1}b^{m - 1} + {}^{m}\mathrm{C}_{m}a^{0}b^{m}.
\]

Now consider \( (a + b)^{m + 1} = (a + b)(a + b)^{m} \)

\[
= (a + b)[{}^{m}\mathrm{C}_{0}a^{m} + {}^{m}\mathrm{C}_{1}a^{m - 1}b + {}^{m}\mathrm{C}_{2}a^{m - 2}b^{2} + \dots +{}^{m}\mathrm{C}_{m - 1}ab^{m - 1} + {}^{m}\mathrm{C}_{m}b^{m}]
\]

\[
= a[{}^{m}\mathrm{C}_{0}a^{m} + {}^{m}\mathrm{C}_{1}a^{m - 1}b + {}^{m}\mathrm{C}_{2}a^{m - 2}b^{2} + \dots +{}^{m}\mathrm{C}_{m - 1}ab^{m - 1} + {}^{m}\mathrm{C}_{m}b^{m}]
\]
\[
+ b[{}^{m}\mathrm{C}_{0}a^{m} + {}^{m}\mathrm{C}_{1}a^{m - 1}b + {}^{m}\mathrm{C}_{2}a^{m - 2}b^{2} + \dots +{}^{m}\mathrm{C}_{m - 1}ab^{m - 1} + {}^{m}\mathrm{C}_{m}b^{m}]
\]

\[
= {}^{m}\mathrm{C}_{0}a^{m + 1} + {}^{m}\mathrm{C}_{1}a^{m}b + {}^{m}\mathrm{C}_{2}a^{m - 1}b^{2} + \dots +{}^{m}\mathrm{C}_{m - 1}a^{2}b^{m - 1} + {}^{m}\mathrm{C}_{m}ab^{m}
\]
\[
+ {}^{m}\mathrm{C}_{0}a^{m}b + {}^{m}\mathrm{C}_{1}a^{m - 1}b^{2} + \dots +{}^{m}\mathrm{C}_{m - 2}a^{2}b^{m - 1} + {}^{m}\mathrm{C}_{m - 1}ab^{m} + {}^{m}\mathrm{C}_{m}b^{m + 1}
\]

Grouping the like terms, we get

\[
(a + b)^{m + 1} = {}^{m}\mathrm{C}_{0}a^{m + 1} + [{}^{m}\mathrm{C}_{1} + {}^{m}\mathrm{C}_{0}]a^{m}b + [{}^{m}\mathrm{C}_{2} + {}^{m}\mathrm{C}_{1}]a^{m - 1}b^{2} + \dots
\]
\[
+ [{}^{m}\mathrm{C}_{r} + {}^{m}\mathrm{C}_{r - 1}]a^{m + 1 - r}b^{r} + \dots + {}^{m}\mathrm{C}_{m}b^{m + 1}
\]

But \( {}^{m}\mathrm{C}_{0} = 1 = {}^{m + 1}\mathrm{C}_{0} \), \( {}^{m}\mathrm{C}_{m} = 1 = {}^{m + 1}\mathrm{C}_{m + 1} \), and \( {}^{m}\mathrm{C}_{r} + {}^{m}\mathrm{C}_{r - 1} = {}^{m + 1}\mathrm{C}_{r} \). Therefore

\[
(a + b)^{m + 1} = {}^{m + 1}\mathrm{C}_{0}a^{m + 1} + {}^{m + 1}\mathrm{C}_{1}a^{m}b + {}^{m + 1}\mathrm{C}_{2}a^{m - 1}b^{2} + \dots + {}^{m + 1}\mathrm{C}_{m}ab^{m} + {}^{m + 1}\mathrm{C}_{m + 1}b^{m + 1}
\]

Thus \( P(m + 1) \) is true. Hence, by mathematical induction, \( P(n) \) is true for all positive integers \( n \).

(i) The expansion consists of \( (n + 1) \) terms.

(ii) In each term, the sum of the powers of \( a \) and \( b \) is always \( n \).

(iii) The binomial coefficients \( ^{n}\mathrm{C}_{0}, ^{n}\mathrm{C}_{1}, ^{n}\mathrm{C}_{2}, \ldots \) form a pattern.

(iv) In the expansion, the \( r^{th} \) term from the beginning is \( ^{n}\mathrm{C}_{r - 1}a^{n - r + 1}b^{r - 1} \). It is usually denoted by \( T_r \). That is,

\[
T_r = {}^{n}\mathrm{C}_{r - 1}a^{n - r + 1}b^{r - 1}.
\]

(v) The binomial coefficients in the expansion of \( (a + b)^{n} \) are \( ^{n}\mathrm{C}_{0}, ^{n}\mathrm{C}_{1}, ^{n}\mathrm{C}_{2}, \ldots, ^{n}\mathrm{C}_{n} \).

(vi) \( ^{n}\mathrm{C}_{r} = ^{n}\mathrm{C}_{n - r} \). So the coefficients equidistant from the beginning and the end are equal.

(vii) In the expansion of \( (a + b)^{n}, n\in \mathbb{N} \), the greatest coefficient is \( ^{n}\mathrm{C}_{\frac{n}{2}} \) if \( n \) is even and the greatest coefficients are \( ^{n}\mathrm{C}_{\frac{n - 1}{2}} \) or \( ^{n}\mathrm{C}_{\frac{n + 1}{2}} \), if \( n \) is odd.

(viii) In the expansion of \( (a + b)^{n}, n\in \mathbb{N} \) if \( n \) is even, the middle term is \( T_{\frac{n}{2} + 1} = {}^{n}\mathrm{C}_{\frac{n}{2}}a^{n - \frac{n}{2}}b^{\frac{n}{2}} \). If \( n \) is odd, then the two middle terms are \( T_{\frac{n - 1}{2} + 1} \) and \( T_{\frac{n + 1}{2} + 1} \).

## 5.3 Particular cases of Binomial Theorem

(i) Replacing \( b \) by \( (-b) \), in the binomial expansion of \( (a + b)^{n}, n\in \mathbb{N} \), we get

\[
(a - b)^{n} = {}^{n}\mathrm{C}_{0}a^{n}b^{0} - {}^{n}\mathrm{C}_{1}a^{n - 1}b^{1} + {}^{n}\mathrm{C}_{2}a^{n - 2}b^{2} - \dots + (-1)^{r}{}^{n}\mathrm{C}_{r}a^{n - r}b^{r} + \dots + (-1)^{n}{}^{n}\mathrm{C}_{n}a^{0}b^{n}.
\]

Observe that the sign \( '+' \) and \( '-' \) appear alternately in the binomial expansion of \( (a - b)^{n} \)

(ii) Replacing \( a \) by 1 and \( b \) by \( x \), in the binomial expansion of \( (a + b)^{n}, n\in \mathbb{N} \), we get

\[
(1 + x)^{n} = {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{1}x + {}^{n}\mathrm{C}_{2}x^{2} + \dots +{}^{n}\mathrm{C}_{r}x^{r} + \dots +{}^{n}\mathrm{C}_{n}x^{n}.
\]

In particular, when \( x = 1 \), \( {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{1} + {}^{n}\mathrm{C}_{2} + \dots +{}^{n}\mathrm{C}_{n} = 2^{n} \).

If \( X \) is a set containing \( n \) elements, then we know that \( ^{n}\mathrm{C}_{r} \) is the number of subsets of \( X \) having exactly \( r \) elements. So by adding \( ^{n}\mathrm{C}_{r} \) for \( r = 0, 1, 2, \ldots, n \) we get the number of subsets of \( X \). So by using the above identity we see that a set of \( n \) elements has \( 2^{n} \) subsets.

(iii) \( (1 - x)^{n} = {}^{n}\mathrm{C}_{0} - {}^{n}\mathrm{C}_{1}x + {}^{n}\mathrm{C}_{2}x^{2} - \dots + (-1)^{r}{}^{n}\mathrm{C}_{r}x^{r} + \dots + (-1)^{n}x^{n} \). In particular, when \( x = 1 \), we get,
\[
{}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{2} + {}^{n}\mathrm{C}_{4} + \dots = {}^{n}\mathrm{C}_{1} + {}^{n}\mathrm{C}_{3} + {}^{n}\mathrm{C}_{5} + \dots = 2^{n - 1}
\]

### Example 5.1

Find the expansion of \( (2x + 3)^{5} \).

**Solution:**

By taking \( a = 2x, b = 3 \) and \( n = 5 \) in the binomial expansion of \( (a + b)^{n} \) we get

\[
(2x + 3)^{5} = (2x)^{5} + 5(2x)^{4}3 + 10(2x)^{3}3^{2} + 10(2x)^{2}3^{3} + 5(2x)^{1}3^{4} + 3^{5}
\]
\[
= 32x^{5} + 240x^{4} + 720x^{3} + 1080x^{2} + 810x + 243.
\]

### Example 5.2

Evaluate \( 98^{4} \).

**Solution:**

By taking \( a = 100, b = 2 \) and \( n = 4 \) in the binomial expansion of \( (a - b)^{n} \) we get

\[
98^{4} = (100 - 2)^{4}
\]
\[
= {}^{4}\mathrm{C}_{0}100^{4} - {}^{4}\mathrm{C}_{1}100^{3}2 + {}^{4}\mathrm{C}_{2}100^{2}2^{2} - {}^{4}\mathrm{C}_{3}100^{1}2^{3} + {}^{4}\mathrm{C}_{4}100^{0}2^{4}
\]
\[
= 100000000 - 8000000 + 240000 - 3200 + 16
\]
\[
= 92236816.
\]

### Example 5.3

Find the middle term in the expansion of \( (x + y)^{6} \).

**Solution:**

Here \( n = 6 \); which is even. Thus the middle term in the expansion of \( (x + y)^{6} \) is the term containing \( x^{3}y^{3} \), that is the term \( ^{6}\mathrm{C}_{3}x^{3}y^{3} \) which is equal to \( 20x^{3}y^{3} \).

### Example 5.4

Find the middle terms in the expansion of \( (x + y)^{7} \).

**Solution:**

As \( n = 7 \) which is odd, the terms containing \( x^{4}y^{3} \) and \( x^{3}y^{4} \) are the two middle terms. They are \( ^{7}\mathrm{C}_{3}x^{4}y^{3} \) and \( ^{7}\mathrm{C}_{4}x^{3}y^{4} \) which are equal to \( 35x^{4}y^{3} \) and \( 35x^{3}y^{4} \).

### Example 5.5

Find the coefficient of \( x^{6} \) in the expansion of \( (3 + 2x)^{10} \).

**Solution:**

Let us take \( a = 3 \) and \( b = 2x \) in the binomial expansion of \( (a + b)^{10} \). Then, \( x^{6} \) will appear in the term containing \( (2x)^{6} \) and nowhere else. So the term containing \( x^{6} \) is

\[
^{10}\mathrm{C}_{6}a^{4}b^{6} = {}^{10}\mathrm{C}_{4}a^{4}b^{6} = \frac{10 \times 9 \times 8 \times 7}{4 \times 3 \times 2 \times 1}3^{4}(2x)^{6} = 210 \times 3^{4} \times 2^{6}x^{6}. \quad [\because {}^{10}\mathrm{C}_{6} = {}^{10}\mathrm{C}_{4}]
\]

So coefficient of \( x^{6} \) in the expansion of \( (3 + 2x)^{10} \) is \( 210 \times 3^{4} \times 2^{6} \).

### Example 5.6

Find the coefficient of \( x^{3} \) in the expansion of \( (2 - 3x)^{7} \).

**Solution:**

Let us take \( a = 2 \) and \( b = -3x \) in the binomial expansion of \( (a + b)^{7} \). Then, \( x^{3} \) will appear in the term containing \( (-3x)^{3} \) and nowhere else. So the term containing \( x^{3} \) is

\[
^{7}\mathrm{C}_{3}a^{4}b^{3} = \frac{7 \times 6 \times 5}{3 \times 2 \times 1}2^{4}(-3x)^{3} = 35 \times 2^{4} \times (-3)^{3}x^{3}.
\]

So coefficient of \( x^{3} \) in the expansion of \( (2 - 3x)^{7} \) is \( 35 \times 16 \times (-27) = -15120 \).

### Example 5.7

The \( 2^{nd} \), \( 3^{rd} \) and \( 4^{th} \) terms in the binomial expansion of \( (x + a)^{n} \) are 240, 720 and 1080 for a suitable value of \( x \). Find \( x \), \( a \) and \( n \).

**Solution:**

It is given that \( T_{2} = 240 \), \( T_{3} = 720 \) and \( T_{4} = 1080 \).

\[
T_{2} = {}^{n}\mathrm{C}_{1}x^{n - 1}a = 240 \tag{1}
\]
\[
T_{3} = {}^{n}\mathrm{C}_{2}x^{n - 2}a^{2} = 720 \tag{2}
\]
\[
T_{4} = {}^{n}\mathrm{C}_{3}x^{n - 3}a^{3} = 1080 \tag{3}
\]

Dividing (2) by (1) and (3) by (2) we get

\[
\frac{a}{x} = \frac{6}{n - 1} \tag{4}
\]
\[
\frac{a}{x} = \frac{9}{2(n - 2)} \tag{5}
\]

From (4) and (5)

\[
\frac{6}{n - 1} = \frac{9}{2(n - 2)}
\]

Thus \( n = 5 \). Substituting \( n = 5 \) in (1) and (4) also dividing (1) by (4), we get

\[
\frac{5x^{4}a}{\frac{a}{x}} = \frac{240}{\frac{6}{4}}
\]

Thus \( 5x^{5} = 160 \) and hence \( x = 2 \). Substituting in (4) we get \( a = 3 \).

### Example 5.8

Expand \( \left(2x - \frac{1}{2x}\right)^{4} \).

**Solution:**

We have

\[
\left(2x - \frac{1}{2x}\right)^{4} = {}^{4}\mathrm{C}_{0}(2x)^{4}\left(-\frac{1}{2x}\right)^{0} + {}^{4}\mathrm{C}_{1}(2x)^{3}\left(-\frac{1}{2x}\right)^{1} + {}^{4}\mathrm{C}_{2}(2x)^{2}\left(-\frac{1}{2x}\right)^{2}
\]
\[
+ {}^{4}\mathrm{C}_{3}(2x)^{1}\left(-\frac{1}{2x}\right)^{3} + {}^{4}\mathrm{C}_{4}(2x)^{0}\left(-\frac{1}{2x}\right)^{4}
\]
\[
= (2x)^{4} - 4(2x)^{3}\left(\frac{1}{2x}\right) + 6(2x)^{2}\left(\frac{1}{2x}\right)^{2} - 4(2x)\left(\frac{1}{2x}\right)^{3} + \left(\frac{1}{2x}\right)^{4}
\]
\[
= 16x^{4} - 16x^{2} + 6 - \frac{1}{x^{2}} + \frac{1}{16x^{4}}
\]

### Example 5.9

Expand \( \left(x^{2} + \sqrt{1 - x^{2}}\right)^{5} + \left(x^{2} - \sqrt{1 - x^{2}}\right)^{5} \).

**Solution:**

We have

\[
\left(x^{2} + \sqrt{1 - x^{2}}\right)^{5} = {}^{5}\mathrm{C}_{0}(x^{2})^{5}\left(\sqrt{1 - x^{2}}\right)^{0} + {}^{5}\mathrm{C}_{1}(x^{2})^{4}\left(\sqrt{1 - x^{2}}\right)^{1} + {}^{5}\mathrm{C}_{2}(x^{2})^{3}\left(\sqrt{1 - x^{2}}\right)^{2}
\]
\[
+ {}^{5}\mathrm{C}_{3}(x^{2})^{2}\left(\sqrt{1 - x^{2}}\right)^{3} + {}^{5}\mathrm{C}_{4}(x^{2})^{1}\left(\sqrt{1 - x^{2}}\right)^{4} + {}^{5}\mathrm{C}_{5}(x^{2})^{0}\left(\sqrt{1 - x^{2}}\right)^{5}
\]
\[
= x^{10} + 5x^{8}\sqrt{1 - x^{2}} + 10x^{6}(1 - x^{2}) + 10x^{4}(1 - x^{2})\sqrt{1 - x^{2}} + 5x^{2}(1 - x^{2})^{2} + (1 - x^{2})^{2}\sqrt{1 - x^{2}}
\]

Similarly,

\[
\left(x^{2} - \sqrt{1 - x^{2}}\right)^{5} = x^{10} - 5x^{8}\sqrt{1 - x^{2}} + 10x^{6}(1 - x^{2}) - 10x^{4}(1 - x^{2})\sqrt{1 - x^{2}} + 5x^{2}(1 - x^{2})^{2} - (1 - x^{2})^{2}\sqrt{1 - x^{2}}
\]

Thus

\[
\left(x^{2} + \sqrt{1 - x^{2}}\right)^{5} + \left(x^{2} - \sqrt{1 - x^{2}}\right)^{5} = 2[x^{10} + 10x^{6}(1 - x^{2}) + 5x^{2}(1 - x^{2})^{2}]
\]
\[
= 2[x^{10} + 10x^{6} - 10x^{8} + 5x^{2}(1 - 2x^{2} + x^{4})]
\]
\[
= 2[x^{10} - 10x^{8} + 15x^{6} - 10x^{4} + 5x^{2}]
\]

### Example 5.10

Using Binomial theorem, prove that \( 6^{n} - 5n \) always leaves remainder 1 when divided by 25 for all positive integer \( n \).

**Solution:**

To prove this it is enough to prove, \( 6^{n} - 5n = 25k + 1 \) for some integer \( k \). We first consider the expansion

\[
(1 + x)^{n} = {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{1}x + {}^{n}\mathrm{C}_{2}x^{2} + \dots + {}^{n}\mathrm{C}_{n-1}x^{n-1} + {}^{n}\mathrm{C}_{n}x^{n}, \quad n\in \mathbb{N}
\]

Taking \( x = 5 \) we get \( (1 + 5)^{n} = {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{1}5 + {}^{n}\mathrm{C}_{2}5^{2} + \dots + {}^{n}\mathrm{C}_{n-1}5^{n-1} + {}^{n}\mathrm{C}_{n}5^{n} \). The above equality reduces to \( 6^{n} = 1 + 5n + 25({}^{n}\mathrm{C}_{2} + 5^{n}\mathrm{C}_{3} + \dots + {}^{n}\mathrm{C}_{n}5^{n-2}) \). That is,

\[
6^{n} - 5n = 1 + 25({}^{n}\mathrm{C}_{2} + 5^{n}\mathrm{C}_{3} + \dots + {}^{n}\mathrm{C}_{n}5^{n-2}) = 1 + 25k, \quad k\in \mathbb{N}.
\]

Thus \( 6^{n} - 5n \) always leaves remainder 1 when divided by 25 for all positive integer \( n \).

### Example 5.11

Find the last two digits of the number \( 7^{400} \).

**Solution:**

We have

\[
7^{400} = (7^{2})^{200} = (50 - 1)^{200}
\]
\[
= {}^{200}\mathrm{C}_{0}50^{200} - {}^{200}\mathrm{C}_{1}50^{199} + \dots + {}^{200}\mathrm{C}_{198}50^{2}(-1)^{198} + {}^{200}\mathrm{C}_{199}50(-1)^{199} + {}^{200}\mathrm{C}_{200}(-1)^{200}
\]
\[
= 50^{2}({}^{200}\mathrm{C}_{0}50^{198} - {}^{200}\mathrm{C}_{1}50^{197} + \dots + {}^{200}\mathrm{C}_{198}(-1)^{198}) - 200 \times 50 + 1.
\]

As \( 50^{2} \) and 200 are divisible by 100, the last two digits of \( 7^{400} \) is 01.

## Exercise 5.1

1. Expand
   (i) \( \left(2x^{2} - \frac{3}{x}\right)^{3} \)
   (ii) \( \left(2x^{2} - 3\sqrt{1 - x^{2}}\right)^{4} + \left(2x^{2} + 3\sqrt{1 - x^{2}}\right)^{4} \).

2. Compute
   (i) \( 102^{4} \) (ii) \( 99^{4} \) (iii) \( 9^{7} \).

3. Using binomial theorem, indicate which of the following two number is larger: \( (1.01)^{1000000} \), 10000.

4. Find the coefficient of \( x^{15} \) in \( \left(x^{2} + \frac{1}{x^{3}}\right)^{10} \).

5. Find the coefficient of \( x^{2} \) and the coefficient of \( x^{6} \) in \( \left(x^{2} - \frac{1}{x^{3}}\right)^{6} \).

6. Find the coefficient of \( x^{4} \) in the expansion of \( (1 + x^{3})^{50}(x^{2} + \frac{1}{x})^{5} \).

7. Find the constant term of \( \left(2x^{3} - \frac{1}{3x^{2}}\right)^{5} \).

8. Find the last two digits of the number \( 3^{600} \).

9. If \( n \) is a positive integer, using Binomial theorem, show that, \( 9^{n+1} - 8n - 9 \) is always divisible by 64.

10. If \( n \) is an odd positive integer, prove that the coefficients of the middle terms in the expansion of \( (x + y)^{n} \) are equal.

11. If \( n \) is a positive integer and \( r \) is a nonnegative integer, prove that the coefficients of \( x^{r} \) and \( x^{n-r} \) in the expansion of \( (1 + x)^{n} \) are equal.

12. If \( a \) and \( b \) are distinct integers, prove that \( a - b \) is a factor of \( a^{n} - b^{n} \), whenever \( n \) is a positive integer. [Hint: write \( a^{n} = (a - b + b)^{n} \) and expand]

13. In the binomial expansion of \( (a + b)^{n} \), if the coefficients of the \( 4^{th} \) and \( 13^{th} \) terms are equal then, find \( n \).

14. If the binomial coefficients of three consecutive terms in the expansion of \( (a + x)^{n} \) are in the ratio \( 1:7:42 \), then find \( n \).

15. In the binomial expansion of \( (1 + x)^{n} \), the coefficients of the \( 5^{th} \), \( 6^{th} \) and \( 7^{th} \) terms are in AP. Find all values of \( n \).

16. Prove that \( C_{0}^{2} + C_{1}^{2} + C_{2}^{2} + \dots + C_{n}^{2} = \frac{(2n)!}{(n!)^{2}} \).

## 5.4 Finite Sequences

A sequence is a list of elements with a particular order. While the idea of a sequence of numbers, \( a_{1}, a_{2}, \dots \), is straight forward, it is useful to think of a sequence as a function whose domain is either the set of first \( n \) natural numbers or \( \mathbb{N} \). Throughout this chapter, we consider only sequences of real numbers and we will refer to them as sequences. The arithmetic sequences and geometric sequences are also known as arithmetic progressions (AP) and geometric progressions (GP). Let us recall, the basic definitions of sequences and series.

If \( X \) is any set and \( n\in \mathbb{N} \), then any function \( f: \{1, 2, 3, \ldots, n\} \to X \) is called a finite sequence on \( X \) and any function \( g: \mathbb{N} \to X \) is called an infinite sequence on \( X \). The value \( f(n) \) of the function \( f \) at \( n \) is denoted by \( a_{n} \) and the sequence itself is denoted by \( (a_{n}) \). If the set \( X \) happens to be a set of real numbers, the sequence is called a numerical sequence or a sequence of real numbers. Though every sequence is a function, a function is not necessarily a sequence. Unlike sets, where elements are not repeated, the terms in a sequence may be repeated. In particular, a sequence in which all terms are same is called a constant sequence. A useful way to visualise a sequence \( (a_{n}) \) is to plot the graph of \( \{(n, a_{n}) : n \in \mathbb{N}\} \) which gives some details about the sequence.

### 5.4.1 Arithmetic and Geometric Progressions

Progressions are some special cases of sequences where the terms of the sequences are either in increasing form or decreasing form.

We recall some definitions and results which has been discussed in earlier classes on arithmetic and geometric progressions.

#### Arithmetic Progression (AP)

A sequence of the form

\[
a, a + d, a + 2d, a + 3d, \ldots, a + (n - 1)d, a + nd, \ldots
\]

is called an arithmetic progression or an arithmetic sequence. In other words, each term (other than the first term) of the sequence is obtained by adding a constant to its previous term; the constant \( d \) is called common difference and the term \( a \) is called the initial term or first term.

The \( n^{th} \) term of an arithmetic progression is given by \( T_{n} = a + (n - 1)d \)

The sequences \( \sqrt{2}, \sqrt{2} + \sqrt{3}, \sqrt{2} + 2\sqrt{3}, \sqrt{2} + 3\sqrt{3}, \ldots \) and 12, 9, 6, 3, ... are arithmetic sequences with common differences \( \sqrt{3} \) and \( -3 \) respectively. It is interesting to observe that 3, 7, 11 are three prime numbers which form an AP. For \( n\in \mathbb{N}, T_{n} = an + b \) where \( a \) and \( b \) are relatively prime, form an AP which contains infinitely many prime numbers along with infinitely many composite numbers.

#### Geometric Progression (GP)

A sequence of the form

\[
a, ar, ar^{2}, ar^{3}, \ldots, ar^{n-1}, ar^{n}, \ldots
\]

with \( a\neq 0 \), and \( r\neq 0 \) is called a geometric progression or a geometric sequence. In other words, each term (other than the first term) of the sequence is obtained by multiplying its previous term by a constant; the constant \( r \) is called common ratio and the term \( a \) is called the initial term or first term.

The \( n^{th} \) term of a geometric progression is given by \( T_{n} = ar^{n-1} \)

The sequences 1, 2, 4, 8, 16, ... and \( \sqrt{2}, 2, 2\sqrt{2}, 4, 4\sqrt{2}, \ldots \) are geometric sequences with common ratios 2 and \( \sqrt{2} \) respectively. Taking logarithm of each term in a geometric progression with positive common ratio yields an arithmetic progression. i.e., If \( a, ar, ar^{2}, \ldots \) is a GP with \( r > 0 \), then \( \log a, \log(ar), \log(ar^{2}), \ldots \) is an AP with common difference \( \log r \).

It is interesting to note that the constant sequence \( c, c, c, \ldots \) is an arithmetic sequence and is also a geometric sequence if \( c\neq 0 \).

Let us consider the special constant sequence 0, 0, 0, 0, ... We have no problem in seeing this as an arithmetic sequence. But when we try to see this as a geometric sequence clearly the initial term must be 0. What can we say about the common ratio \( r \)? If we take \( r \) as 1, 2 or any other number we get the same sequence 0, 0, 0, 0, ... We are left with the situation where a geometric sequence has infinitely many common ratios. To overcome these confusions some mathematicians exclude this sequence from the class of geometric sequences by assuming \( a \neq 0 \) in the definition. (We made this assumption)

### 5.4.2 Arithmetico-Geometric Progression (AGP)

Combining arithmetic and geometric progressions, a new progression called arithmetico geometric progression is formed. As we use the abbreviations AP and GP for arithmetic progressions and geometric progressions, we use the abbreviation AGP for arithmetico geometric progression. AGP's arise in various applications, such as the computation of expected value in probability theory.

**Definition 5.1**

A sequence of the form

\[
a, (a + d)r, (a + 2d)r^{2}, (a + 3d)r^{3}, \ldots, (a + (n - 1)d)r^{n-1}, (a + nd)r^{n}, \ldots
\]

is called an arithmetico-geometric progression or an arithmetico-geometric sequence.

Consider an AP: \( a, a + d, a + 2d, \ldots \) and GP: \( 1, r, r^{2}, \ldots \)

Then the AGP is \( a, (a + d)r, (a + 2d)r^{2}, \ldots \)

Here, \( a \) is the initial term, \( d \) is the common difference and \( r \) is the common ratio of the AGP.

If we take \( r = 1 \), then the AGP will become an AP and if we take \( d = 0 \), then it will become a GP. So the arithmetic and Geometric progressions become particular cases of AGP. This is a nice situation to know the concept of generalization in mathematics.

We note that the \( n^{th} \) term of an AGP is given by \( T_n = (a + (n - 1)d)r^{n-1} \). All APs and all GPs are AGPs.

For example, the AP 0, 1, 2, 3, 4, ... and the GP 1, \( \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \ldots \) give the AGP \( \frac{0}{1}, \frac{1}{2}, \frac{2}{4}, \frac{3}{8}, \ldots \)

The sequence 4, 14, 40, 104, 256, 608, ... is also an example of an arithmetico-geometric progression. For this sequence \( a = 4 \), \( d = 3 \) and \( r = 2 \).

### 5.4.3 Harmonic Progression (HP)

Harmonic progression is one of many important sequences and is closely related to the arithmetic progression. Harmonic progression is widely used.

**Definition 5.2**

A sequence \( h_1, h_2, h_3, \ldots \) is said to be a harmonic sequence or a harmonic progression if \( \frac{1}{h_1}, \frac{1}{h_2}, \frac{1}{h_3}, \frac{1}{h_4}, \ldots \) is an arithmetic sequence.

Note that a sequence is in harmonic progression if reciprocal of its terms are in arithmetic progression. But we should not say that harmonic progressions are reciprocals of arithmetic progressions; in fact, if an arithmetic sequence contains a zero term, then its reciprocal is not meaningful. Of course, if an arithmetic progression contains no zero term, then its reciprocal is a harmonic progression. So a general harmonic progression will be of the form

\[
\frac{1}{a}, \frac{1}{a + d}, \frac{1}{a + 2d}, \frac{1}{a + 3d}, \ldots
\]

## 5.5 Means

The three Pythagorean means, the arithmetic mean (AM), the geometric mean (GM) and the harmonic mean (HM) are very important in mathematics and its applications. The arithmetic mean of a set of numbers is defined as the sum of the numbers divided by the number of numbers.

**Definition 5.3**

Let \( a_1, a_2, a_3, \ldots, a_n \) be \( n \) real numbers. Then the number

\[
\frac{a_1 + a_2 + a_3 + \ldots + a_n}{n}
\]

is called the arithmetic mean of the numbers \( a_1, a_2, a_3, \ldots, a_n \).

The numbers need not be distinct but they must be real numbers. For example, the arithmetic mean of the numbers 4, 8, 12, 18, 22 is 12.8. The arithmetic mean of the sequence 0, 1, 2, 3, 4, 5, 6, 7 is 3.5.

Taking the multiplication in place of addition and \( n^{th} \) root in place of division by \( n \) in the definition of arithmetic mean we get the definition of geometric mean.

**Definition 5.4**

Let \( n \) be any positive integer. Let \( a_1, a_2, a_3, \ldots, a_n \) be \( n \) non-negative numbers. Then the number

\[
\sqrt[n]{a_1 a_2 a_3 \ldots a_n}
\]

is called the geometric mean of the numbers \( a_1, a_2, a_3, \ldots, a_n \).

Here also the numbers \( a_1, a_2, a_3, \ldots, a_n \) need not be distinct but it is necessary that the numbers are non-negative. The geometric mean of the numbers 4, 6, 9 is \( \sqrt[3]{216} = 6 \). The arithmetic mean of these three numbers is \( \frac{19}{3} = 6\frac{1}{3} \). Observe that the arithmetic mean is greater than the geometric mean in this case. Is this true always?

It can be proved that "For any set of \( n \) non-negative numbers, the arithmetic mean is greater than or equal to the geometric mean". That is, if AM denotes the arithmetic mean and GM denotes the geometric mean, then \( AM \geq GM \).

Let us prove this inequality \( AM \geq GM \) for two non-negative numbers.

**Theorem 5.2:** If AM and GM denote the arithmetic mean and the geometric mean of two nonnegative numbers, then \( AM \geq GM \). The equality holds if and only if the two numbers are equal.

**Proof.** Let \( a \) and \( b \) be any two nonnegative numbers. Then

\[
AM = \frac{a + b}{2} \quad \text{and} \quad GM = \sqrt{ab}.
\]

We have, \( (a + b)^2 - 4ab = (a - b)^2 \geq 0 \). Thus, \( (a + b)^2 - 4ab \geq 0 \) which gives \( (a + b) \geq 2\sqrt{ab} \). Hence \( \frac{a + b}{2} \geq \sqrt{ab} \).

In other words, \( AM \geq GM \).

Moreover, the equality holds if and only if \( (a + b)^2 - 4ab = 0 \). This holds if and only if \( (a - b)^2 = 0 \) which holds if and only if \( a = b \). Thus \( AM = GM \) if and only if \( a = b \).

**Geometrical Proof for \( AM \geq GM \)**

Let \( a \) and \( b \) be any two nonnegative real numbers. If at least one of them is zero, then GM is 0 and hence we have nothing to prove. So let us assume that \( a > 0 \) and \( b > 0 \). We draw a straight line segment AB of length \( a + b \) and a semi-circle having AB as diameter. Let M be the midpoint of AB. Then M is the center of the semi-circle drawn. Since M is the midpoint of AB, we have \( AM = MB = \frac{a + b}{2} \). So the radius of the circle is \( \frac{a + b}{2} \). Let D be the point on AB so that \( AD = a \); then \( DB = b \).

Through D we draw the perpendicular to AB and let it to meet the semi-circle at C. We draw straight lines CA, CB and CM. Since M is the center \( CM = \) radius \( = \frac{a + b}{2} \). Clearly \( MD = \frac{a + b}{2} - a \). Using the similar triangles \( \triangle ACD \) and \( \triangle CBD \) we have \( \frac{CD}{AD} = \frac{BD}{CD} \) and hence \( CD^2 = AD \times BD = ab \). So \( CD = \sqrt{ab} \). (Using Pythagoras theorem also we can prove that \( CD = \sqrt{ab} \).) Since the length of any half chord is less than or equal to the radius, we have \( CD \leq CM \). In other words, \( \sqrt{ab} \leq \frac{a + b}{2} \). This means \( GM \leq AM \).

The length of the half chord \( DC \) is equal to the radius if and only if \( D = M \). Thus equality \( AM = GM \) holds if and only if \( a = b \).

**Result 5.1:** If \( a_1, a_2, a_3, \ldots, a_n \) is an arithmetic progression, every term \( a_k \) \( (k > 1) \) is the arithmetic mean of its immediate predecessor \( a_{k-1} \) and immediate successor \( a_{k+1} \).

**Proof.** Let \( a_1, a_2, a_3, \ldots, a_n \) be an arithmetic progression with initial term \( a \) and common difference \( d \). Then

\[
a_k = a + (k - 1)d, \quad a_{k-1} = a + (k - 2)d \quad \text{and} \quad a_{k+1} = a + kd.
\]

Thus

\[
\frac{a_{k-1} + a_{k+1}}{2} = \frac{a + (k - 2)d + a + kd}{2} = \frac{2a + (2k - 2)d}{2} = a + (k - 1)d = a_k.
\]

Therefore, \( a_k \) is the arithmetic mean of \( a_{k-1} \) and \( a_{k+1} \).

**Result 5.2:** If \( a_1, a_2, a_3, \ldots, a_n \) is a geometric progression, every term \( a_k \) \( (k > 1) \) is the geometric mean of its immediate predecessor \( a_{k-1} \) and immediate successor \( a_{k+1} \).

**Proof.** Let \( a_1, a_2, a_3, \ldots, a_n \) be a geometric progression with initial term \( a \) and common ratio \( r \). Then

\[
a_k = ar^{k-1}, \quad a_{k-1} = ar^{k-2} \quad \text{and} \quad a_{k+1} = ar^{k}.
\]

Thus

\[
\sqrt{a_{k-1}a_{k+1}} = \sqrt{ar^{k-2} \cdot ar^{k}} = \sqrt{a^2 r^{2k-2}} = ar^{k-1} = a_k.
\]

Therefore, \( a_k \) is the geometric mean of \( a_{k-1} \) and \( a_{k+1} \).

### Example 5.14

Find seven numbers \( A_1, A_2, \ldots, A_7 \) so that the sequence \( 4, A_1, A_2, \ldots, A_7, 7 \) is in arithmetic progression and also 4 numbers \( G_1, G_2, G_3, G_4 \) so that the sequence \( 12, G_1, G_2, G_3, G_4, \frac{3}{8} \) is in geometric progression.

**Solution:**

Since \( a = 4 \) and the 9th term is 7, we have \( 4 + 8d = 7 \) we get \( d = \frac{3}{8} \). So the required 7 numbers are \( 4\frac{3}{8}, 4\frac{6}{8}, 4\frac{9}{8}, 4\frac{12}{8}, 4\frac{15}{8}, 4\frac{18}{8}, 4\frac{21}{8} \) i.e., \( 4.375, 4.75, 5.125, 5.5, 5.875, 6.25, 6.625 \).

Since \( a = 12 \) and \( ar^5 = \frac{3}{8} \) we get \( r^5 = \frac{1}{32} \) and hence \( r = \frac{1}{2} \). Thus the required 4 numbers are \( 6, 3, \frac{3}{2}, \frac{3}{4} \).

### Example 5.15

If the product of the \( 4^{th}, 5^{th} \) and \( 6^{th} \) terms of a geometric progression is 4096 and if the product of the \( 5^{th}, 6^{th} \) and \( 7^{th} \) terms of it is 32768, find the sum of first 8 terms of the geometric progression.

**Solution:**

Let \( a, ar, ar^{2}, \ldots \) be the geometric series having the given properties. Since the \( 4^{th}, 5^{th} \) and \( 6^{th} \) terms are \( ar^{3}, ar^{4} \) and \( ar^{5} \), their product is \( a^{3} r^{12} \). Thus \( a^{3} r^{12} = 4096 \). Similarly \( a^{3} r^{15} = 32768 \).

Therefore \( \frac{a^{3}r^{15}}{a^{3}r^{12}} = \frac{32768}{4096} \). Hence \( r^{3} = 8 \). This implies that \( r = 2 \). \( a^{3}r^{12} = 4096 \) we have \( a^{3} = 1 \). Therefore \( a = 1 \). The sum of the first 8 terms is \( \frac{a(1 - r^{8})}{1 - r} = \frac{1 - 2^{8}}{1 - 2} = 255 \).

### Harmonic Mean

The harmonic mean of a set of positive numbers is the reciprocal of the arithmetic mean of the reciprocals of the set of numbers. That is, if \( h_1, h_2, \ldots, h_n \) are positive numbers, then their reciprocals are \( \frac{1}{h_1}, \frac{1}{h_2}, \ldots, \frac{1}{h_n} \); the arithmetic mean of the reciprocals is

\[
\frac{\frac{1}{h_1} + \frac{1}{h_2} + \dots + \frac{1}{h_n}}{n}
\]

and the reciprocal of this arithmetic mean, that is the harmonic mean of the numbers \( h_1, h_2, \ldots, h_n \) is

\[
\frac{n}{\frac{1}{h_1} + \frac{1}{h_2} + \dots + \frac{1}{h_n}}.
\]

**Definition 5.5**

The harmonic mean of a set \( \{h_1, h_2, \ldots, h_n\} \) of positive numbers is defined as

\[
\frac{n}{\frac{1}{h_1} + \frac{1}{h_2} + \dots + \frac{1}{h_n}}.
\]

In particular, the harmonic mean of two positive numbers \( a \) and \( b \) is \( \frac{2}{\frac{1}{a} + \frac{1}{b}} \) which is equal to \( \frac{2ab}{a + b} \).

It can be proved that "For any set of \( n \) positive numbers, the geometric mean is greater than or equal to the harmonic mean". That is, \( GM \geq HM \).

Let us prove this inequality \( GM \geq HM \) for two non-negative numbers.

**Theorem 5.3:** If \( GM \) and \( HM \) denote the geometric mean and the harmonic mean of two non-negative numbers, then \( GM \geq HM \). The equality holds if and only if the two numbers are equal.

**Proof.** Let \( a \) and \( b \) be any two positive numbers. Then

\[
GM = \sqrt{ab} \quad \text{and} \quad HM = \frac{2ab}{a + b}.
\]

\[
GM - HM = \sqrt{ab} - \frac{2ab}{a + b} = \frac{\sqrt{ab}(a + b) - 2ab}{a + b}
\]
\[
= \frac{\sqrt{ab}((a + b) - 2\sqrt{ab})}{a + b} = \frac{\sqrt{ab}(\sqrt{a} - \sqrt{b})^{2}}{a + b} \geq 0
\]

Thus \( GM - HM \geq 0 \) and hence \( GM \geq HM \).

(i) We have already proved that \( AM \geq GM \) in theorem 5.2 and now we have \( GM \geq HM \). Combining these two, we have an important inequality \( AM \geq GM \geq HM \).

**Result 5.3:** For any two positive numbers, the three means \( AM, GM \) and \( HM \) are in geometric progression.

**Proof.** Let \( a \) and \( b \) be any two positive real numbers. Then

\[
AM = \frac{a + b}{2}, \quad GM = \sqrt{ab}, \quad \text{and} \quad HM = \frac{2ab}{a + b}.
\]

Now

\[
AM \times HM = \left(\frac{a + b}{2}\right)\left(\frac{2ab}{a + b}\right) = ab = (\sqrt{ab})^2 = GM^2.
\]

That is, \( AM \times HM = GM^2 \) and hence \( AM, GM \) and \( HM \) are in geometric progression.

We note the following interesting results.

If \( b \) is the arithmetic mean of \( a \) and \( c \), then \( a, b, c \) is an arithmetic progression. If \( b \) is the geometric mean of \( a \) and \( c \), then \( a, b, c \) is a geometric progression. If \( b \) is the harmonic mean of \( a \) and \( c \), then \( a, b, c \) is a harmonic progression.

If a vehicle travels at a speed of \( x \) kmph covering certain distance and it returns the same distance with a speed of \( y \) kmph, then the average speed of the vehicle in the whole travel is the harmonic mean of the upward and downward speeds. Indeed, if \( d \) is the distance, then time taken for upward journey is \( \frac{d}{x} \) and the time taken for downward journey is \( \frac{d}{y} \).

Thus average speed is \( \frac{2d}{\frac{d}{x} + \frac{d}{y}} = \frac{2xy}{x + y} \).

For example if a vehicle travels at a speed of 60 kmph covering certain distance and it returns the same distance with a speed of 40 kmph, then the average speed of the vehicle in the whole travel is the harmonic mean of 60 and 40. That is \( \frac{2 \times 60 \times 40}{60 + 40} = 48 \) kmph speed.

## Exercise 5.2

1. Write the first 6 terms of the sequences whose \( n^{th} \) terms are given below and classify them as arithmetic progression, geometric progression, arithmetic-geometric progression, harmonic progression and none of them.
   \[
   (i) \frac{1}{2^{n+1}} \quad (ii) \frac{(n+1)(n+2)}{(n+3)(n+4)} \quad (iii) 4\left(\frac{1}{2}\right)^{n} \quad (iv) \frac{(-1)^{n}}{n} \quad (v) \frac{2n+3}{3n+4} \quad (vi) 2018 \quad (vii) \frac{3n-2}{3n-1}
   \]

2. Write the first 6 terms of the sequences whose \( n^{th} \) term \( a_n \) is given below.

3. Write the \( n^{th} \) term of the following sequences.
   \[
   (i) \frac{1}{2}, \frac{2}{3}, \frac{4}{5}, \frac{6}{7}, \frac{6}{9}, \frac{6}{10}, \ldots \quad (ii) \frac{1}{6}, \frac{2}{10}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \ldots
   \]

4. The product of three increasing numbers in GP is 5832. If we add 6 to the second number and 9 to the third number, then resulting numbers form an AP. Find the numbers in GP.

5. Write the \( n^{th} \) term of the sequence \( \frac{3}{1^{2}2^{2}}, \frac{5}{2^{2}3^{2}}, \frac{7}{3^{2}4^{2}}, \ldots \) as a difference of two terms.

6. If \( t_k \) is the \( k^{th} \) term of a GP, then show that \( t_{n-k}, t_n, t_{n+k} \) also form a GP for any positive integer \( k \).

7. If \( a, b, c \) are in geometric progression, and if \( a^{\frac{1}{x}} = b^{\frac{1}{y}} = c^{\frac{1}{z}} \), then prove that \( x, y, z \) are in arithmetic progression.

8. The AM of two numbers exceeds their GM by 10 and HM by 16. Find the numbers.

9. If the roots of the equation \( (q - r)x^{2} + (r - p)x + p - q = 0 \) are equal, then show that \( p, q \) and \( r \) are in AP.

10. If \( a, b, c \) are respectively the \( p^{th}, q^{th} \) and \( r^{th} \) terms of a GP, show that \( (q - r)\log a + (r - p)\log b + (p - q)\log c = 0 \).

## 5.5 Finite Series

Roughly speaking a series is the sum of terms of a sequence of numbers; a finite series is the sum of terms of a finite sequence of numbers. If \( (a_n) \) is a sequence of numbers, then the expression \( a_1 + a_2 + \dots + a_n \) is called a finite series. The expression \( a_1 + a_2 + \dots + a_n \) is denoted as \( \sum_{k=1}^{n} a_k \). Sometimes, depending upon the problem under consideration and for simplicity a series may be given as \( a_0 + a_1 + a_2 + \dots \) with first term as \( a_0 \).

### 5.5.1 Sum of Arithmetic, Geometric and Arithmetic-Geometric Progressions

In the earlier classes we studied about the sum of a few terms, like sum of first \( n \) terms, of arithmetic and geometric progressions. We now recall them.

#### Sum of Arithmetic and Geometric Progressions

A series is said to be an arithmetic series if the terms of the series form an arithmetic sequence. A series is said to be a geometric series if the terms of the series form a geometric sequence. The sum \( S_n \) of the first \( n \) terms of the arithmetic sequence \( (a + (n - 1)d) \) is given by \( S_n = na + \frac{(n - 1)n}{2}d = \frac{n}{2}[2a + (n - 1)d] \). The sum \( S_n \) of the first \( n \) terms of the geometric sequence \( (ar^{n-1}) \) is given by \( S_n = \frac{a(1 - r^{n})}{1 - r} \) provided \( r \neq 1 \). If \( r = 1 \), then the sequence is nothing but the constant sequence \( a, a, a, \ldots \) and the sum of the first \( n \) terms is clearly \( na \). Thus, if \( r \neq 1 \), then \( 1 + r + r^{2} + \dots + r^{n-1} = \frac{1 - r^{n}}{1 - r} \).

#### Sum of Arithmetic-Geometric Progressions

A series is said to be an arithmetic-Geometric series if the terms of the series form an arithmetic-Geometric sequence.

The sum \( S_n \) of the first \( n \) terms of the arithmetic-Geometric sequence \( ((a + (n - 1)d)r^{n-1}) \) is given by

\[
S_n = \frac{a - (a + (n - 1)d)r^{n}}{1 - r} + dr\left(\frac{1 - r^{n-1}}{(1 - r)^{2}}\right)
\]

for \( r \neq 1 \).

### 5.5.2 Telescopic Summation for Finite Series

### Example 5.17

Find the sum of the first \( n \) terms of the series \( \frac{1}{1 + \sqrt{2}} + \frac{1}{\sqrt{2} + \sqrt{3}} + \frac{1}{\sqrt{3} + \sqrt{4}} + \ldots \)

**Solution:**

Let \( t_k \) denote the \( k^{th} \) term of the given series. Then \( t_k = \frac{1}{\sqrt{k} + \sqrt{k+1}} \). If we are successful in writing the \( k^{th} \) term as a difference of two expressions, then we can solve using this technique. We have

\[
t_k = \frac{1}{\sqrt{k} + \sqrt{k+1}} = \frac{\sqrt{k} - \sqrt{k+1}}{(\sqrt{k} + \sqrt{k+1})(\sqrt{k} - \sqrt{k+1})} = \frac{\sqrt{k} - \sqrt{k+1}}{k - (k+1)} = \sqrt{k+1} - \sqrt{k}
\]

Thus

\[
t_1 + t_2 + \dots + t_n = (\sqrt{2} - \sqrt{1}) + (\sqrt{3} - \sqrt{2}) + \dots + (\sqrt{n+1} - \sqrt{n}) = \sqrt{n+1} - 1
\]

### Example 5.18

Find \( \sum_{k=1}^{n} \frac{1}{k(k+1)} \).

**Solution:**

Let \( t_k \) denote the \( k^{th} \) term of the given series. Then \( t_k = \frac{1}{k(k+1)} \). By using partial fraction we get

\[
\frac{1}{k(k+1)} = \frac{1}{k} - \frac{1}{k+1}.
\]

Thus

\[
t_1 + t_2 + \dots + t_n = \left(1 - \frac{1}{2}\right) + \left(\frac{1}{2} - \frac{1}{3}\right) + \left(\frac{1}{3} - \frac{1}{4}\right) + \dots + \left(\frac{1}{n} - \frac{1}{n+1}\right) = 1 - \frac{1}{n+1}.
\]

## Exercise 5.3

1. Find the sum of the first 20 terms of the arithmetic progression having the sum of first 10 terms as 52 and the sum of the first 15 terms as 77.

2. Find the sum up to the 17th term of the series \( \frac{1^{3}}{1} + \frac{1^{3} + 2^{3}}{1 + 3} + \frac{1^{3} + 2^{3} + 3^{3}}{1 + 3 + 5} + \cdots \)

3. Compute the sum of first \( n \) terms of the following series:
   (i) \( 8 + 88 + 888 + 8888 + \cdots \)
   (ii) \( 6 + 66 + 666 + 6666 + \cdots \)

4. Compute the sum of first \( n \) terms of \( 1 + (1 + 4) + (1 + 4 + 4^{2}) + (1 + 4 + 4^{2} + 4^{3}) + \cdots \)

5. Find the general term and sum to \( n \) terms of the sequence \( 1, \frac{4}{3}, \frac{7}{9}, \frac{10}{27}, \ldots \).

6. Find the value of \( n \), if the sum to \( n \) terms of the series \( \sqrt{3} + \sqrt{75} + \sqrt{243} + \cdots \) is \( 435\sqrt{3} \).

7. Show that the sum of \( (m + n)^{th} \) and \( (m - n)^{th} \) term of an AP is equal to twice the \( m^{th} \) term.

8. A man repays an amount of Rs.3250 by paying Rs.20 in the first month and then increases the payment by Rs.15 per month. How long will it take him to clear the amount?

9. In a race, 20 balls are placed in a line at intervals of 4 meters, with the first ball 24 meters away from the starting point. A contestant is required to bring the balls back to the starting place one at a time. How far would the contestant run to bring back all balls?

10. The number of bacteria in a certain culture doubles every hour. If there were 30 bacteria present in the culture originally, how many bacteria will be present at the end of 2nd hour, 4th hour and \( n^{th} \) hour?

11. What will Rs.500 amount to in 10 years after its deposit in a bank which pays annual interest rate of \( 10\% \) compounded annually?

12. In a certain town, a viral disease caused severe health hazards upon its people disturbing their normal life. It was found that on each day, the virus which caused the disease spread in Geometric Progression. The amount of infectious virus particle gets doubled each day, being 5 particles on the first day. Find the day when the infectious virus particles just grow over 1,50,000 units?

### 5.5.3 Some Special Finite Series

In this section we give some of the important formulas of summing up finitely many terms which follows either an AP, GP, or any specific series.

1. **Summation of first \( n \) natural numbers:**
   \[
   \sum_{k=1}^{n} k = 1 + 2 + 3 + \cdots + n = \frac{n(n+1)}{2}.
   \]
   [Treating this as an AP, one can find the sum.]

2. **Summation of the squares of first \( n \) natural numbers:**
   \[
   \sum_{k=1}^{n} k^{2} = 1^{2} + 2^{2} + 3^{2} + \cdots + n^{2} = \frac{n(n+1)(2n+1)}{6}.
   \]
   [Use the identity \( a^{3} - b^{3} = (a - b)(a^{2} + ab + b^{2}) \) and try to prove this result.]

3. **Summation of the cubes of first \( n \) natural numbers:**
   \[
   \sum_{k=1}^{n} k^{3} = 1^{3} + 2^{3} + 3^{3} + \cdots + n^{3} = \left(\frac{n(n+1)}{2}\right)^{2}.
   \]
   [Use the identity \( k^{4} - (k-1)^{4} = (4k^{3} - 6k^{2} + 4k - 1) \) and try to prove this result.]

Note that the above three results were proved in the earlier classes.

## 5.6 Infinite Sequences and Series

A finite sum of real numbers is well defined by the properties of real numbers, but in order to make sense of an infinite series, we need to consider the concept of convergence. Consider the infinite sum: \( \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots \) with each term positive. Can we assign a numerical value to the sum? While at first it may seem difficult or impossible, we can certainly do something similar where we have one quantity getting closer and closer to a fixed quantity.

Let us discuss an interesting problem. Let there be two plates \( A \) and \( B \). Let a full cake be placed on the plate \( A \) and let \( B \) be empty. Let us cut the cake in \( A \) into exactly two equal parts and place one part on \( B \) leaving the other part in \( A \). Let us cut the remaining part of the cake in \( A \) into exactly two equal parts and place one part on \( B \) leaving the other part in \( A \). Let us again cut the remaining part of the cake in \( A \) into exactly two equal parts and place one part on \( B \) leaving the other part in \( A \). If we go on doing this what will happen? What will be the amount of cake "finally" in \( A \) and in \( B \)? Let us list the stage by stage status:

Intuitively we feel that "finally" nothing will remain in plate \( A \) and the full cake will be in plate \( B \). In other words, the cake available in \( A \) is 0 and the cake available in \( B \) is 1. That is, intuitively we feel that

\[
1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \frac{1}{32}, \ldots
\]

"goes" to 0 and

\[
\frac{1}{2}, \frac{3}{4}, \frac{7}{8}, \frac{15}{16}, \ldots
\]

"goes" to 1 or equivalently

\[
\frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \frac{1}{16} + \dots = 1.
\]

In this section let us learn the sense in which the words "finally" and "goes" are used and also let us learn the addition of infinitely many numbers.

We intuitively feel that \( 1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \frac{1}{32}, \ldots \) "goes" to 0. Similarly we feel that the sequence \( 1, \frac{1}{10}, \frac{1}{100}, \frac{1}{1000}, \frac{1}{10000}, \frac{1}{100000}, \ldots \) also "goes" to 0.

If \( (a_n) \) is a sequence and \( a \) is a number so that for any given small positive number, there is a stage after which the distance between \( a_n \) and \( a \) is smaller than that positive number, then we may say that \( a_n \) goes to \( a \) as \( n \) goes to infinity. In technical terms we may say that \( a_n \) tends to \( a \) as \( n \) tends to infinity. In other words, in the limiting case \( a_n \) becomes \( a \) or the limit of \( a_n \) is \( a \) as \( n \) tends to \( \infty \). We also say that the sequence \( (a_n) \) converges to \( a \). If \( (a_n) \) converges to \( a \), then we write \( \lim_{n \to \infty} a_n = a \).

The sequence \( 1, 0, 1, 0, 1, 0, 1, 0, \ldots \) does not converge to any limit. So a sequence may not have a limit. But we can prove that a sequence cannot converge to more than one limit; that is, if a sequence converges to a limit, then it is unique.

### 5.6.1 Fibonacci Sequence

The Fibonacci sequence is a sequence of numbers where a number other than first two terms, is found by adding up the two numbers before it. Starting with 1, the sequence goes 1, 1, 2, 3, 5, 8, 13, 21, 34, and so forth. Written as a rule, the expression is \( x_n = x_{n-1} + x_{n-2}, n \geq 3 \) with \( x_1 = 1, x_2 = 1 \)

Named after Fibonacci, also known as Leonardo of Pisa or Leonardo Pisano, Fibonacci numbers were first introduced in the book Liber abaci in 1202. The son of a Pisan merchant, Fibonacci traveled widely and traded extensively. Mathematics was incredibly important to those in the trading industry, and his passion for numbers was cultivated in his youth.

Knowledge of numbers is said to have first originated in the Hindu-Arabic arithmetic system, which Fibonacci studied while growing up in North Africa. Prior to the publication of Liber abaci, the Latin-speaking world had yet to be introduced to the decimal number system. He wrote many books about geometry, commercial arithmetic and irrational numbers. He also helped in the development of the concept of zero.

\[
1, 1, 2, 3, 5, 8, 13, 21, 34, 55, \ldots
\]

For example, the \( 8^{th} \) term is sum of \( 6^{th} \) term and \( 7^{th} \) term. Thus, \( x_8 = 13 + 8 = 21 \)

There is an interesting pattern in the Fibonacci sequence.

Observe that

(i) every third number is a multiple of \( 3^{rd} \) term (\( t_3 = 2 \)).

(ii) every fourth number is a multiple of \( 4^{th} \) term (\( t_4 = 3 \)).

(iii) every fifth number is a multiple of \( 5^{th} \) term (\( t_5 = 5 \)).

(iv) So, every \( n^{th} \) number is a multiple of \( n^{th} \) term.

### 5.6.2 Infinite Geometric Series

The series \( \sum x^n \) is called a geometric series or geometric progression. Let us start with the series: \( \sum_{n=0}^{\infty} x^n, x \neq 1 \). If \( s_n = x_0 + x_1 + x_2 + \dots + x_n \), then \( s_n = \frac{1 - x^{n}}{1 - x} \). As \( x^n \) tends to 0 if \( |x| < 1 \), we say that \( s_n \) tends to \( \frac{1}{1 - x} \) if \( |x| < 1 \).

\( \sum_{n=0}^{\infty} x^n \) converges for all real number \( x \) with \( |x| < 1 \) and the sum is \( \frac{1}{1 - x} \). That is, for all real numbers \( x \) satisfying \( |x| < 1 \)

\[
\frac{1}{1 - x} = 1 + x + x^{2} + x^{3} + \dots
\]

\( \sum_{n=0}^{\infty} (-1)^n x^n \) converges for all real number \( x \) with \( |x| < 1 \) and the sum is \( \frac{1}{1 + x} \). That is, for all real numbers \( x \) satisfying \( |x| < 1 \)

\[
\frac{1}{1 + x} = 1 - x + x^{2} - x^{3} + \dots
\]

\( \sum_{n=0}^{\infty} (2x)^n \) converges for all real number \( x \) with \( |x| < \frac{1}{2} \) and the sum is \( \frac{1}{1 - 2x} \). That is, for real numbers \( x \) satisfying \( |x| < \frac{1}{2} \)

\[
\frac{1}{1 - 2x} = 1 + 2x + 4x^{2} + 8x^{3} + \dots
\]

\( \sum_{n=0}^{\infty} \frac{x^n}{n!} \) converges for all real number \( x \) and the sum is \( e^x \). That is,

\[
e^x = 1 + \frac{x}{1!} + \frac{x^{2}}{2!} + \frac{x^{3}}{3!} + \frac{x^{4}}{4!} + \dots
\]

for all real numbers \( x \).

\( \sum_{n=0}^{\infty} (-1)^n x^n \) converges only for \( x = 0 \).

Let us discuss some special series. By assuming the convergence of those series let us solve some problems.

### 5.6.3 Infinite Arithmetico-Geometric Series

The sum of the arithmetico-geometric series \( \sum ((a + (n - 1)d))r^{n-1} \) is given by

\[
S = \lim_{n \to \infty} S_n = \frac{a}{1 - r} + \frac{dr}{(1 - r)^2}
\]

for \( -1 < r < 1 \).

### 5.6.4 Telescopic Summation for Infinite Series

We discussed about summing terms of a finite sequence using telescopic summation technique in Section 5.5.2. The same applies for infinite series also.

### Example 5.20

Find \( \sum_{n=1}^{\infty} \frac{1}{n^{2} + 5n + 6} \).

**Solution:**

Let \( a_n \) denote the \( n^{th} \) term of the given series. Then \( a_n = \frac{1}{n^{2} + 5n + 6} \). By using partial fraction, we get

\[
a_n = \frac{1}{n + 2} - \frac{1}{n + 3}.
\]

Let \( s_n \) denote the sum of first \( n \) terms of the given series. Then

\[
s_n = a_1 + a_2 + \dots + a_n = \left(\frac{1}{3} - \frac{1}{4}\right) + \left(\frac{1}{4} - \frac{1}{5}\right) + \left(\frac{1}{5} - \frac{1}{6}\right) + \dots + \left(\frac{1}{n+2} - \frac{1}{n+3}\right) = \frac{1}{3} - \frac{1}{n+3}.
\]

But as \( n \) tends to infinity, \( \frac{1}{n+3} \) tends to zero and hence \( \frac{1}{3} - \frac{1}{n+3} \) tends to \( \frac{1}{3} \). In other words \( s_n \) tends to \( \frac{1}{3} \). Thus \( \sum_{n=1}^{\infty} \frac{1}{n^{2} + 5n + 6} = \frac{1}{3} \).

### 5.6.5 Binomial Series

In the discussion on geometric series we have seen that

\[
\frac{1}{1 - x} = 1 + x + x^{2} + \dots, \quad \frac{1}{1 + x} = 1 - x + x^{2} - \dots, \quad \frac{1}{1 - 2x} = 1 + 2x + 4x^{2} + \dots
\]

for some suitable values of \( x \). But the expressions \( \frac{1}{1 - x}, \frac{1}{1 + x} \) and \( \frac{1}{1 - 2x} \) can be written as \( (1 - x)^{-1}, (1 + x)^{-1} \) and \( (1 - 2x)^{-1} \). This suggests us a possibility of having negative exponents, that is negative powers, for \( (1 + x), (1 - x) \) and so on. Yes. This is possible. We can have any power, positive or negative, integer or rational. We can even have irrational exponent for \( (1 + x) \). We already proved Theorem 5.1 for positive integral exponent (integral exponent means integer power). Now let us state the Binomial theorem for rational power.

**Theorem 5.4 (Binomial Theorem for Rational Exponent):** For any rational number \( n \)

\[
(1 + x)^n = 1 + nx + \frac{n(n - 1)}{2!} x^{2} + \frac{n(n - 1)(n - 2)}{3!} x^{3} + \dots
\]

for all real numbers \( x \) satisfying \( |x| < 1 \).

As the proof involves higher mathematical concepts, let us assume the theorem without proof and see some particular cases and solve some problems. In the theorem

1. By taking \( -x \) in the place of \( x \), we get
   \[
   (1 - x)^n = 1 - nx + \frac{n(n - 1)}{2!} x^{2} - \frac{n(n - 1)(n - 2)}{3!} x^{3} + \dots \qquad (|x| < 1)
   \]

2. By taking \( -n \) in the place of \( n \), we get
   \[
   (1 + x)^{-n} = 1 + (-n)x + \frac{(-n)(-n - 1)}{2!} x^{2} + \frac{(-n)(-n - 1)(-n - 2)}{3!} x^{3} + \dots
   \]
   Hence
   \[
   (1 + x)^{-n} = 1 - nx + \frac{n(n + 1)}{2!} x^{2} - \frac{n(n + 1)(n + 2)}{3!} x^{3} + \dots \qquad (|x| < 1)
   \]

3. By taking \( -x \) and \( -n \) in the places of \( x \) and \( n \), we get
   \[
   (1 - x)^{-n} = 1 + nx + \frac{n(n + 1)}{2!} x^{2} + \frac{n(n + 1)(n + 2)}{3!} x^{3} + \dots \qquad (|x| < 1)
   \]

Even though we have explicitly mentioned that \( n \) is a rational number in the theorem, some of us may hesitate to use \( n \) in place of a general rational number. So we give the theorem using the representation \( \frac{p}{q} (q \neq 0) \) for a rational number.

\[
(1 + x)^{\frac{p}{q}} = 1 + \frac{p}{q}x + \frac{\frac{p}{q}\left(\frac{p}{q} - 1\right)}{2!}x^{2} + \frac{\frac{p}{q}\left(\frac{p}{q} - 1\right)\left(\frac{p}{q} - 2\right)}{3!}x^{3} + \dots
\]
\[
= 1 + \frac{p}{q}x + \frac{p(p - q)}{q^{2}2!}x^{2} + \frac{p(p - q)(p - 2q)}{q^{3}3!}x^{3} + \dots
\]
\[
(1 - x)^{\frac{p}{q}} = 1 - \frac{p}{q}x + \frac{p(p - q)}{q^{2}2!}x^{2} - \frac{p(p - q)(p - 2q)}{q^{3}3!}x^{3} + \dots
\]

Though the theorem gives a formula to compute \( (1 + x)^n \), to solve numerical problems quickly we must remember and be able to write certain expansions directly. Observation of the coefficient in each of such expansions will be very helpful in solving problems. Let us list some of them: (Try yourself!).

\[
(1 + x)^{-1} = 1 - x + x^{2} - x^{3} + \dots
\]
\[
(1 - x)^{-1} = 1 + x + x^{2} + x^{3} + \dots
\]
\[
(1 - x)^{-2} = 1 + 2x + 3x^{2} + 4x^{3} + 5x^{4} + 6x^{5} + \dots
\]
\[
(1 + x)^{-2} = 1 - 2x + 3x^{2} - 4x^{3} + 5x^{4} - 6x^{5} + \dots
\]

All the above expansions are valid only when \( |x| < 1 \).

### Example 5.21

Expand \( (1 + x)^{\frac{2}{3}} \) up to four terms for \( |x| < 1 \).

**Solution:**

Here \( n = \frac{2}{3} \).

\[
\frac{n(n-1)}{2!} = \frac{\frac{2}{3}\left(\frac{2}{3} - 1\right)}{2} = \frac{\frac{2}{3}\left(-\frac{1}{3}\right)}{2} = -\frac{1}{9}
\]
\[
\frac{n(n-1)(n-2)}{3!} = \frac{\frac{2}{3}\left(\frac{2}{3} - 1\right)\left(\frac{2}{3} - 2\right)}{6} = \frac{\frac{2}{3}\left(-\frac{1}{3}\right)\left(-\frac{4}{3}\right)}{6} = \frac{4}{81}
\]

Thus

\[
(1 + x)^{\frac{2}{3}} = 1 + \frac{2}{3}x - \frac{1}{9}x^{2} + \frac{4}{81}x^{3} + \dots
\]

### Example 5.22

Expand \( \frac{1}{(1 + 3x)^2} \) in powers of \( x \). Find a condition on \( x \) for which the expansion is valid.

**Solution:**

If we take \( 3x = y \), then

\[
\frac{1}{(1 + 3x)^2} = \frac{1}{(1 + y)^2}.
\]

Now \( \frac{1}{(1 + y)^2} \) can be expanded using binomial theorem in powers of \( y \). The expansion is valid only for values of \( y \) satisfying \( |y| < 1 \). Replacing \( y \) by \( 3x \) we can get an expansion of \( \frac{1}{(1 + 3x)^2} \). The expansion is valid only for values of \( x \) satisfying \( |3x| < 1 \); that is the expansion is valid only for values of \( x \) satisfying \( |x| < \frac{1}{3} \).

\[
\frac{1}{(1 + 3x)^2} = (1 + 3x)^{-2}
\]
\[
= 1 - 2(3x) + \frac{2(2 + 1)}{2!}(3x)^2 - \frac{2(2 + 1)(2 + 2)}{3!}(3x)^3 + \frac{2(2 + 1)(2 + 2)(2 + 3)}{4!}(3x)^4 - \dots
\]

Hence, \( \frac{1}{(1 + 3x)^2} = 1 - 6x + 27x^2 - 108x^3 + 405x^4 - \dots, \quad |x| < \frac{1}{3} \).

### Example 5.23

Expand \( \frac{1}{(3 + 2x)^2} \) in powers of \( x \). Find a condition on \( x \) for which the expansion is valid.

**Solution:**

(Clearly we have to use the expansion of \( (1 + x)^{-2} \). So, we have to write \( (3 + 2x) \) as \( 3\left(1 + \frac{2x}{3}\right) \) and proceed.)

\[
\frac{1}{(3 + 2x)^2} = \frac{1}{3^2\left(1 + \frac{2x}{3}\right)^2} = \frac{1}{9}\left(1 + \frac{2x}{3}\right)^{-2}
\]
\[
= \frac{1}{9}(1 + y)^{-2} \quad \left(\text{where } \frac{2x}{3} = y\right)
\]
\[
= \frac{1}{9}(1 - 2y + 3y^2 - 4y^3 + 5y^4 - \dots), \quad \text{if } |y| < 1
\]
\[
= \frac{1}{9}\left(1 - 2\left(\frac{2x}{3}\right) + 3\left(\frac{2x}{3}\right)^2 - 4\left(\frac{2x}{3}\right)^3 + 5\left(\frac{2x}{3}\right)^4 - \dots\right), \quad \left|\frac{2x}{3}\right| < 1
\]
\[
= \frac{1}{9}\left(1 - \frac{4}{3}x + \frac{4}{3}x^2 - \frac{32}{27}x^3 + \frac{80}{81}x^4 - \dots\right)
\]

Thus, \( \frac{1}{(3 + 2x)^2} = \frac{1}{9} - \frac{4}{27}x + \frac{4}{27}x^2 - \frac{32}{243}x^3 + \frac{80}{729}x^4 - \dots, \quad |x| < \frac{3}{2} \).

The expansion is valid if \( |y| < 1 \). So, the expansion is valid if \( |x| < \frac{3}{2} \).

We can find square root, cube root and other roots of any positive number by using binomial theorem. Let us see one such problem.

### Example 5.24

Find \( \sqrt[3]{65} \).

**Solution:**

We know that for \( |x| < 1 \)

\[
(1 + x)^n = 1 + nx + \frac{n(n - 1)}{2!}x^2 + \frac{n(n - 1)(n - 2)}{3!}x^3 + \ldots
\]

\[
\sqrt[3]{65} = 65^{\frac{1}{3}} = (64 + 1)^{\frac{1}{3}} = 64^{\frac{1}{3}}\left(1 + \frac{1}{64}\right)^{\frac{1}{3}} = 4\left(1 + \frac{1}{64}\right)^{\frac{1}{3}}
\]
\[
= 4\left[1 + \frac{1}{3} \times \frac{1}{64} + \frac{\frac{1}{3}\left(\frac{1}{3} - 1\right)}{2!} \times \left(\frac{1}{64}\right)^2 + \cdots\right]
\]
\[
= 4\left[1 + \frac{1}{192} - \frac{1}{9} \times \frac{1}{4096} + \cdots\right] = 4 + \frac{1}{48} - \frac{1}{9216} + \cdots
\]
\[
\approx 4 + 0.0208 \quad (\text{since } \frac{1}{9216} + \cdots \text{ is very small})
\]
\[
\sqrt[3]{65} \approx 4.02 \text{ (approximately)}.
\]

### Example 5.25

Prove that \( \sqrt[3]{x^3 + 7} - \sqrt[3]{x^3 + 4} \) is approximately equal to \( \frac{1}{x^2} \) when \( x \) is large.

**Solution:**

\[
\sqrt[3]{x^3 + 7} = (x^3 + 7)^{\frac{1}{3}} = \left[x^3\left(1 + \frac{7}{x^3}\right)\right]^{\frac{1}{3}} = x\left(1 + \frac{7}{x^3}\right)^{\frac{1}{3}}, \quad \left(\left|\frac{7}{x^3}\right| < 1 \text{ as } x \text{ is large}\right)
\]
\[
= x\left[1 + \frac{1}{3} \times \frac{7}{x^3} + \frac{\frac{1}{3}\left(\frac{1}{3} - 1\right)}{2!}\left(\frac{7}{x^3}\right)^2 + \cdots\right]
\]
\[
= x\left[1 + \frac{7}{3} \times \frac{1}{x^3} - \frac{49}{9} \times \frac{1}{x^6} + \cdots\right] = x + \frac{7}{3} \times \frac{1}{x^2} - \frac{49}{9} \times \frac{1}{x^5} + \cdots
\]

\[
\sqrt[3]{x^3 + 4} = (x^3 + 4)^{\frac{1}{3}} = \left[x^3\left(1 + \frac{4}{x^3}\right)\right]^{\frac{1}{3}} = x\left(1 + \frac{4}{x^3}\right)^{\frac{1}{3}} \quad \left(\left|\frac{4}{x^3}\right| < 1\right)
\]
\[
= x\left[1 + \frac{1}{3} \times \frac{4}{x^3} + \frac{\frac{1}{3}\left(\frac{1}{3} - 1\right)}{2!}\left(\frac{4}{x^3}\right)^2 + \cdots\right]
\]
\[
= x + \frac{4}{3} \times \frac{1}{x^2} - \frac{16}{9} \times \frac{1}{x^5} + \cdots
\]

Since \( x \) is large, \( \frac{1}{x} \) is very small and hence higher powers of \( \frac{1}{x} \) are negligible. Thus
\[
\sqrt[3]{x^3 + 7} \approx x + \frac{7}{3} \times \frac{1}{x^2} \quad \text{and} \quad \sqrt[3]{x^3 + 4} \approx x + \frac{4}{3} \times \frac{1}{x^2}.
\]

Therefore
\[
\sqrt[3]{x^3 + 7} - \sqrt[3]{x^3 + 4} \approx \left(x + \frac{7}{3x^2}\right) - \left(x + \frac{4}{3x^2}\right) = \frac{1}{x^2}.
\]

### 5.6.6 Exponential Series

The series \( \sum_{n=0}^{\infty} \frac{x^n}{n!} \) is called an exponential series. This series converges for all real numbers \( x \). The sum of the series is \( e^x \).

\[
e^x = 1 + \frac{x}{1!} + \frac{x^2}{2!} + \frac{x^3}{3!} + \frac{x^4}{4!} + \dots \quad \text{for all } x \in \mathbb{R}
\]

Similarly,
\[
e^{-x} = 1 - \frac{x}{1!} + \frac{x^2}{2!} - \frac{x^3}{3!} + \frac{x^4}{4!} - \dots
\]

Also,
\[
\frac{e^x + e^{-x}}{2} = 1 + \frac{x^2}{2!} + \frac{x^4}{4!} + \frac{x^6}{6!} + \dots
\]
\[
\frac{e^x - e^{-x}}{2} = \frac{x}{1!} + \frac{x^3}{3!} + \frac{x^5}{5!} + \dots
\]

### 5.6.7 Logarithmic Series

The series \( \sum_{n=1}^{\infty} (-1)^{n+1} \frac{x^n}{n} \) is called a logarithmic series. This series converges for all values of \( x \) satisfying \( |x| < 1 \). This series converges when \( x = 1 \) also.

For all values of \( x \) satisfying \( |x| < 1 \), the sum of the series is \( \log(1 + x) \). Thus

\[
\log(1 + x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \dots \quad \text{for all values of } x \text{ satisfying } |x| < 1.
\]

By taking \( -x \) in place of \( x \) we get

\[
\log(1 - x) = -x - \frac{x^2}{2} - \frac{x^3}{3} - \frac{x^4}{4} - \dots \quad \text{for all values of } x \text{ satisfying } |x| < 1.
\]

Now \( \log\left(\frac{1 + x}{1 - x}\right) = \log(1 + x) - \log(1 - x) \). Using this we get

\[
\log\left(\frac{1 + x}{1 - x}\right) = 2\left[x + \frac{x^3}{3} + \frac{x^5}{5} + \dots\right].
\]

Suppose we want to write \( \log(1 + 2x) \) in a series, then we can replace \( 2x \) by \( y \) and use the expansion

\[
\log(1 + y) = y - \frac{y^2}{2} + \frac{y^3}{3} - \frac{y^4}{4} + \dots
\]

for all values of \( y \) satisfying \( |y| < 1 \). But if \( |y| < 1 \), then \( |2x| < 1 \) and hence \( |x| < \frac{1}{2} \). So if \( |x| < \frac{1}{2} \) then

\[
\log(1 + 2x) = 2x - \frac{(2x)^2}{2} + \frac{(2x)^3}{3} - \frac{(2x)^4}{4} + \dots .
\]

Thus \( \log(1 + 2x) = 2x - \frac{4x^2}{2} + \frac{8x^3}{3} - \frac{16x^4}{4} + \dots \) for all values of \( x \) satisfying \( |x| < \frac{1}{2} \).

## Exercise 5.4

1. Expand the following in ascending powers of \( x \) and find the condition on \( x \) for which the binomial expansion is valid.
   \[
   (i) \frac{1}{5 + x} \quad (ii) \frac{2}{(3 + 4x)^2} \quad (iii) (5 + x^2)^{\frac{2}{3}} \quad (iv) (x + 2)^{-\frac{2}{3}}
   \]

2. Find \( \sqrt[3]{1001} \) approximately (two decimal places).

3. Prove that \( \sqrt[3]{x^3 + 6} - \sqrt[3]{x^3 + 3} \) is approximately equal to \( \frac{1}{x^2} \) when \( x \) is sufficiently large.

4. Prove that \( \sqrt{\frac{1 - x}{1 + x}} \) is approximately equal to \( 1 - x + \frac{x^2}{2} \) when \( x \) is very small.

5. Write the first 6 terms of the exponential series
   (i) \( e^{5x} \) (ii) \( e^{-2x} \) (iii) \( e^{\frac{1}{2}x} \)

6. Write the first 4 terms of the logarithmic series
   (i) \( \log(1 + 4x) \) (ii) \( \log(1 - 2x) \) (iii) \( \log\left(\frac{1 + 3x}{1 - 3x}\right) \) (iv) \( \log\left(\frac{1 - 2x}{1 + 2x}\right) \)
   Find the intervals on which the expansions are valid.

7. If \( y = x + \frac{x^2}{2} + \frac{x^3}{3} + \frac{x^4}{4} + \dots \), then show that \( x = y - \frac{y^2}{2!} + \frac{y^3}{3!} - \frac{y^4}{4!} + \dots \)

8. If \( p - q \) is small compared to either \( p \) or \( q \), then show that \( \sqrt[n]{p} \simeq \frac{(n+1)p + (n-1)q}{(n-1)p + (n+1)q} \). Hence find \( \sqrt[3]{\frac{15}{16}} \).

9. Find the coefficient of \( x^4 \) in the expansion of \( \frac{3 - 4x + x^2}{e^{2x}} \).

10. Find the value of \( \sum_{n=1}^{\infty} \frac{1}{2n - 1} \left(\frac{1}{9^{n-1}} + \frac{1}{9^{2n-1}}\right) \).

## Multiple Choice Questions

1. The value of \( 2 + 4 + 6 + \dots + 2n \) is
   (1) \( \frac{n(n - 1)}{2} \) (2) \( \frac{n(n + 1)}{2} \) (3) \( \frac{2n(2n + 1)}{2} \) (4) \( n(n + 1) \)

2. The coefficient of \( x^{6} \) in \( (2 + 2x)^{10} \) is
   (1) \( ^{10}\mathrm{C}_{6} \) (2) \( 2^{6} \) (3) \( ^{10}\mathrm{C}_{6}2^{6} \) (4) \( ^{10}\mathrm{C}_{6}2^{10} \)

3. The coefficient of \( x^{8}y^{12} \) in the expansion of \( (2x + 3y)^{20} \) is
   (1) 0 (2) \( 2^{8}3^{12} \) (3) \( 2^{8}3^{12} + 2^{12}3^{8} \) (4) \( ^{20}\mathrm{C}_{8}2^{8}3^{12} \)

4. If \( ^{n}\mathrm{C}_{10} > ^{n}\mathrm{C}_{r} \) for all possible \( r \), then a value of \( n \) is
   (1) 10 (2) 21 (3) 19 (4) 20

5. If \( a \) is the arithmetic mean and \( g \) is the geometric mean of two numbers, then
   (1) \( a \leq g \) (2) \( a \geq g \) (3) \( a = g \) (4) \( a > g \)

6. If \( (1 + x^{2})^{2}(1 + x)^{n} = a_{0} + a_{1}x + a_{2}x^{2} + \dots + x^{n+4} \) and if \( a_{0}, a_{1}, a_{2} \) are in AP, then \( n \) is
   (1) 1 (2) 5 (3) 2 (4) 4

7. If \( a, 8, b \) are in AP, \( a, 4, b \) are in GP, and if \( a, x, b \) are in HP then \( x \) is
   (1) 2 (2) 1 (3) 4 (4) 16

8. The sequence \( \frac{1}{\sqrt{3}}, \frac{1}{\sqrt{3} + \sqrt{2}}, \frac{1}{\sqrt{3} + 2\sqrt{2}}, \dots \) form a(n)
   (1) AP (2) GP (3) HP (4) AGP

9. The HM of two positive numbers whose AM and GM are 16, 8 respectively is
   (1) 10 (2) 6 (3) 5 (4) 4

10. If \( S_{n} \) denotes the sum of \( n \) terms of an AP whose common difference is \( d \), the value of \( S_{n} - 2S_{n-1} + S_{n-2} \) is
    (1) \( d \) (2) \( 2d \) (3) \( 4d \) (4) \( d^{2} \)

11. The remainder when \( 38^{15} \) is divided by 13 is
    (1) 12 (2) 1 (3) 11 (4) 5

12. The \( n^{th} \) term of the sequence \( 1, 2, 4, 7, 11, \dots \) is
    (1) \( n^{3} + 3n^{2} + 2n \) (2) \( n^{3} - 3n^{2} + 3n \) (3) \( \frac{n(n+1)(n+2)}{3} \) (4) \( \frac{n^{2} - n + 2}{2} \)

13. The sum up to \( n \) terms of the series \( \frac{1}{\sqrt{1} + \sqrt{3}} + \frac{1}{\sqrt{3} + \sqrt{5}} + \frac{1}{\sqrt{5} + \sqrt{7}} + \dots \) is
    (1) \( \sqrt{2n+1} \) (2) \( \frac{\sqrt{2n+1}}{2} \) (3) \( \sqrt{2n+1} - 1 \) (4) \( \frac{\sqrt{2n+1} - 1}{2} \)

14. The \( n^{th} \) term of the sequence \( \frac{1}{2}, \frac{3}{4}, \frac{7}{8}, \frac{15}{16}, \dots \) is
    (1) \( 2^{n} - n - 1 \) (2) \( 1 - 2^{-n} \) (3) \( 2^{-n} + n - 1 \) (4) \( 2^{n-1} \)

15. The sum up to \( n \) terms of the series \( \sqrt{2} + \sqrt{8} + \sqrt{18} + \sqrt{32} + \dots \) is
    (1) \( \frac{n(n+1)}{2} \) (2) \( 2n(n+1) \) (3) \( \frac{n(n+1)}{\sqrt{2}} \) (4) 1

16. The value of the series \( \frac{1}{2} + \frac{7}{4} + \frac{13}{8} + \frac{19}{16} + \dots \) is
    (1) 14 (2) 7 (3) 4 (4) 6

17. The sum of an infinite GP is 18. If the first term is 6, the common ratio is
    (1) \( \frac{1}{3} \) (2) \( \frac{2}{3} \) (3) \( \frac{1}{6} \) (4) \( \frac{3}{4} \)

18. The coefficient of \( x^{5} \) in the series \( e^{-2x} \) is
    (1) \( \frac{2}{3} \) (2) \( \frac{3}{2} \) (3) \( -\frac{4}{15} \) (4) \( \frac{4}{15} \)

19. The value of \( \frac{1}{2!} + \frac{1}{4!} + \frac{1}{6!} + \dots \) is
    (1) \( \frac{e^{2} + 1}{2e} \) (2) \( \frac{(e + 1)^{2}}{2e} \) (3) \( \frac{(e - 1)^{2}}{2e} \) (4) \( \frac{e^{2} - 1}{2e} \)

20. The value of \( 1 - \frac{1}{2}\left(\frac{2}{3}\right) + \frac{1}{3}\left(\frac{2}{3}\right)^{2} - \frac{1}{4}\left(\frac{2}{3}\right)^{3} + \dots \) is
    (1) \( \log\left(\frac{5}{3}\right) \) (2) \( \frac{3}{2}\log\left(\frac{5}{3}\right) \) (3) \( \frac{5}{3}\log\left(\frac{5}{3}\right) \) (4) \( \frac{2}{3}\log\left(\frac{2}{3}\right) \)

## Summary

In this chapter we have acquired the knowledge of

- Binomial theorem for any \( n\in \mathbb{N} \)
  \[
  (a + b)^{n} = {}^{n}\mathrm{C}_{0}a^{n}b^{0} + {}^{n}\mathrm{C}_{1}a^{n-1}b^{1} + \dots + {}^{n}\mathrm{C}_{n}a^{0}b^{n}.
  \]
- \( {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{1} + \dots + {}^{n}\mathrm{C}_{n} = 2^{n} \).
- \( {}^{n}\mathrm{C}_{1} + {}^{n}\mathrm{C}_{3} + {}^{n}\mathrm{C}_{5} + \dots = {}^{n}\mathrm{C}_{0} + {}^{n}\mathrm{C}_{2} + {}^{n}\mathrm{C}_{4} + \dots = 2^{n-1} \)
- \( AM \geq GM \geq HM \)
- The \( n^{th} \) term of an AP is given by \( T_n = a + (n-1)d \)
- The \( n^{th} \) term of a GP is given by \( T_n = ar^{n-1} \)
- The \( n^{th} \) term of an AGP is given by \( T_n = (a + (n-1)d)r^{n-1} \)
- For any positive numbers \( a \) and \( b \), we have
  \[
  \mathrm{AM} = \frac{a + b}{2}, \quad \mathrm{GM} = \sqrt{ab}, \quad \mathrm{HM} = \frac{2ab}{a + b}.
  \]
- The sum of first \( n \) terms of an AP is given by \( S_n = \frac{n}{2}(2a + (n-1)d) \)
- The sum of first \( n \) terms of a GP is given by \( S_n = \frac{a(1 - r^{n})}{1 - r} \) for \( r \neq 1 \)
- The sum of first \( n \) terms of an AGP is given by \( S_n = \frac{a - (a + (n-1)d)r^{n}}{1 - r} + dr\left(\frac{1 - r^{n-1}}{(1 - r)^{2}}\right) \) for \( r \neq 1 \)
- \( \sum_{k=1}^{n} k = 1 + 2 + 3 + \dots + n = \frac{n(n+1)}{2} \)
- \( \sum_{k=1}^{n} k^{2} = 1^{2} + 2^{2} + 3^{2} + \dots + n^{2} = \frac{n(n+1)(2n+1)}{6} \)
- \( \sum_{k=1}^{n} k^{3} = 1^{3} + 2^{3} + 3^{3} + \dots + n^{3} = \left(\frac{n(n+1)}{2}\right)^{2} \)
- Fibonacci sequence: 1, 1, 2, 3, 5, ...
- Binomial theorem for rational exponent
  \[
  (1 + x)^n = 1 + nx + \frac{n(n-1)}{2!}x^{2} + \frac{n(n-1)(n-2)}{3!}x^{3} + \dots \quad (|x| < 1)
  \]
- \( (1 + x)^{-1} = 1 - x + x^{2} - x^{3} + \dots \)
- \( (1 - x)^{-1} = 1 + x + x^{2} + x^{3} + \dots \)
- \( (1 - x)^{-2} = 1 + 2x + 3x^{2} + 4x^{3} + 5x^{4} + 6x^{5} + \dots \)
- \( (1 + x)^{-2} = 1 - 2x + 3x^{2} - 4x^{3} + 5x^{4} - 6x^{5} + \dots \)
- \( e^{x} = 1 + \frac{x}{1!} + \frac{x^{2}}{2!} + \frac{x^{3}}{3!} + \frac{x^{4}}{4!} + \dots \)
- \( e^{-x} = 1 - \frac{x}{1!} + \frac{x^{2}}{2!} - \frac{x^{3}}{3!} + \frac{x^{4}}{4!} - \dots \)
- \( \frac{e^{x} + e^{-x}}{2} = 1 + \frac{x^{2}}{2!} + \frac{x^{4}}{4!} + \frac{x^{6}}{6!} + \dots \) and \( \frac{e^{x} - e^{-x}}{2} = \frac{x}{1!} + \frac{x^{3}}{3!} + \frac{x^{5}}{5!} + \dots \)
- \( \log(1 + x) = x - \frac{x^{2}}{2} + \frac{x^{3}}{3} - \frac{x^{4}}{4} + \dots \) for all values of \( x \) satisfying \( |x| < 1 \)
- \( \log(1 - x) = -x - \frac{x^{2}}{2} - \frac{x^{3}}{3} - \frac{x^{4}}{4} - \dots \) for all values of \( x \) satisfying \( |x| < 1 \)
- \( \log\left(\frac{1 + x}{1 - x}\right) = 2\left[x + \frac{x^{3}}{3} + \frac{x^{5}}{5} + \dots\right] \) for all values of \( x \) satisfying \( |x| < 1 \)
