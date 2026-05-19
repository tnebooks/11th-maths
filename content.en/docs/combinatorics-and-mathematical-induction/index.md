---
title: 'combinatorics and mathematical induction'
weight: 4
---

# Combinatorics and Mathematical Induction

> No great discovery was ever made without a bold guess
>
> — Newton

## 4.1 Introduction

Combinatorics is the branch of mathematics which is related to counting. It deals with arrangements of objects as well as enumeration, that is, counting of objects with specific properties. The roots of the subject can be traced as far back as 2800 BC (BCE) when it was used to study magic squares and patterns within them.

English physicist and mathematician Sir Isaac Newton, most famous for his law of gravitation, was instrumental in the scientific revolution of the 17th century. Newton's belief in the "Persistence of patterns" led to his first significant mathematical discovery, the generalization of the expansion of binomial expressions.

Newton discovered Binomial Theorem which he claimed the easiest way to solve the quadratures of curves. This discovery is essential in understanding probability. The generalized version of the Binomial Theorem, the Multinomial Theorem, applies to multiple variables. It is widely used in Combinatorics and Statistics.

He was the first to use fractional indices and to employ coordinate geometry to derive solutions to Diophantine equations. He approximated partial sums of the harmonic series by logarithms (a precursor to Euler's summation formula) and was the first to use power series with confidence and to revert power series. Newton's work on infinite series was inspired by Simon Stevin's decimals.

**Newton (1643-1727)**

In 1705, he was knighted by Queen Anne of England, making him Sir Isaac Newton. Newton made discoveries in optics and theory of motions. Along with mathematician Leibnitz, Newton is credited for developing essential theories of calculus.

Combinatorics has many real life applications where counting of objects are involved. For example, we may be interested to know if there are enough mobile numbers to meet the demand or the number of allowable passwords in a computer system. It also deals with counting techniques and with optimisation methods, that is, methods related to finding the best possible solution among several possibilities in a real problem. In this chapter we shall study counting problems in terms of ordered or unordered arrangements of objects. These arrangements are referred to as permutations and combinations. Combinatorics are largely used in the counting problems of Network communications, Cryptography, Network Security and Probability theory. We shall explore their properties and apply them to counting problems.

Consider another situation: We all know that our electricity consumer card number is of the form A: B : C, where A denotes the electrical substation /larger capacity transformer number, B denotes the smaller capacity electricity transformer number and C denotes the consumer number. There may be conditions that to each substation certain maximal number of transformer can only be linked and with a particular transformer certain maximal number of consumer connection can only be linked. Now the question of deciding, whether a new Transformer/Substation needs to be erected, can be made by the count of the number of consumer connections linked with a substation transformer. How to get that count? This count can be easily arrived by the use of counting principles.

In this Chapter, the art of counting is discussed starting with the Fundamental principles of counting, travelling through Permutation and Combinations.

## Learning Objectives

On completion of this chapter, the students are expected to

- know the principles of counting and applying it to various situations.
- how to compute the number of ways in arranging a set of distinct objects.
- how to compute the number of arrangements from a set containing identical objects.
- how to compute and applying the strategies to find the number of combinations of a set of different objects.
- the applications of the principle of mathematical induction.

We shall start the chapter with the section on

## 4.2 Fundamental principles of counting

### 1. The Sum Rule

Let us consider two tasks which need to be completed. If the first task can be completed in \(M\) different ways and the second in \(N\) different ways, and if these cannot be performed simultaneously, then there are \(M + N\) ways of doing either task. This is the sum rule of counting.

### Example 4.1

Suppose one girl or one boy has to be selected for a competition from a class comprising 17 boys and 29 girls. In how many different ways can this selection be made?

**Solution:**

The first task of selecting a girl can be done in 29 ways. The second task of selecting a boy can be done in 17 ways. It follows from the sum rule, that there are \(17 + 29 = 46\) ways of making this selection.

The sum rule may be extended to more than two tasks. Thus if there are \(n\) non-simultaneous tasks \(T_1, T_2, T_3, \dots, T_n\) which can be performed in \(m_1, m_2, \dots, m_n\) ways respectively, then the number of ways of doing one of these tasks is \(m_1 + m_2 + \dots + m_n\).

### 2. The Product Rule

Let us suppose that a task comprises of two procedures. If the first procedure can be completed in \(M\) different ways and the second procedure can be done in \(N\) different ways after the first procedure is done, then the total number of ways of completing the task is \(M \times N\).

### Example 4.2

Consider the 3 cities Chennai, Trichy and Tirunelveli. In order to reach Tirunelveli from Chennai, one has to pass through Trichy. There are 2 roads connecting Chennai with Trichy and there are 3 roads connecting Trichy with Tirunelveli. What are the total number of ways of travelling from Chennai to Tirunelveli?

**Solution:**

Let the two roads from Chennai to Trichy be \(R_1\) and \(R_2\). There are 3 roads connecting Trichy to Tirunelveli. Let us name them as \(S_1, S_2\) and \(S_3\). Suppose a person chooses \(R_1\) to travel from Chennai to Trichy and may further choose any of the 3 roads \(S_1, S_2\) or \(S_3\) to travel from Trichy to Tirunelveli. Thus the possible road choices are \((R_1, S_1), (R_1, S_2), (R_1, S_3)\). Similarly, if the person chooses \(R_2\) to travel from Chennai to Trichy, the choices would be \((R_2, S_1), (R_2, S_2), (R_2, S_3)\).

**Figure 4.1**

Thus there are \(2 \times 3 = 6\) ways of travelling from Chennai to Tirunelveli.

An extension of the product rule may be stated as follows:

If a task comprises of \(n\) procedures \(P_1, P_2, P_3, \dots, P_n\) which can be performed in \(m_1, m_2, \dots, m_n\) ways respectively, and procedure \(P_i\) can be done after procedures \(P_1, P_2, P_3, \dots, P_{i-1}\) are done, then the number of ways of completing the task is \(m_1 \times m_2 \times \dots \times m_n\).

### 3. The Inclusion-Exclusion Principle

Suppose two tasks \(A\) and \(B\) can be performed simultaneously. Let \(n(A)\) and \(n(B)\) represent the number of ways of performing the tasks \(A\) and \(B\) independent of each other. Also let \(n(A \cap B)\) be the number of ways of performing the two tasks simultaneously. We cannot use the sum rule to count the number of ways of performing one of the tasks as that would lead to over counting. To obtain the correct number of ways we add the number of ways of performing each of the two tasks and then subtract the number of ways of doing both tasks simultaneously. This method is referred to as the principle of inclusion - exclusion. Using the notation of set theory we write it as

$$
n(A \cup B) = n(A) + n(B) - n(A \cap B).
$$

Suppose we have to find the number of positive integers divisible by 2 or 7 (but not both), upto 1000. Let \(n(A)\) denote the number of integers divisible by 2, \(n(B)\) denote the number of integers divisible by 7 and \(n(A \cap B)\) the number of integers divisible by both 2 and 7. Then the number of positive integers divisible by 2 or 7 is given by

$$
n(A \cup B) = n(A) + n(B) - n(A \cap B) = 500 + 142 - 71 = 571.
$$

(Note that \(n(A)\) will include all multiples of 2 upto 1000, \(n(B)\) will include all multiples of 7 upto 1000 and so on.)

**Tree Diagrams:** Tree diagrams are often helpful in representing the possibilities in a counting problem. Typically in a tree the branches represent the various possibilities. For example, suppose a person wants to buy a Car for the family. There are two different branded cars and five colours are available for each brand. Each colour will have three different variant on it namely GL, SS, SL. Then the various choices for choosing a car can be represented through a tree diagram as follows:

**Figure 4.2**

We shall now illustrate the different rules described above through examples.

### Example 4.3

A School library has 75 books on Mathematics, 35 books on Physics. A student can choose only one book. In how many ways a student can choose a book on Mathematics or Physics?

**Solution:**

(i) A student can choose a Mathematics book in "75" different ways.
(ii) A student can choose a Physics book in "35" different ways.

Hence applying the Rule of Sum, the number of ways a student can choose a book is \(75 + 35 = 110\).

Now we shall discuss the problem stated in our introduction.

### Example 4.4

If an electricity consumer has the consumer number say 238:110:29, then describe the linking and count the number of house connections upto the 29th consumer connection linked to the larger capacity transformer number 238 subject to the condition that each smaller capacity transformer can have a maximal consumer link of say 100.

**Solution:**

The following figure illustrates the electricity distribution network.

**Figure 4.3**

There are 110 smaller capacity transformers attached to a larger capacity transformer. As each smaller capacity transformer can be linked with only 100 consumers, we have for the 109 transformers, there will be \(109 \times 100 = 10900\) links. For the \(110^{th}\) transformer there are only 29 consumers linked. Hence, the total number of consumers linked to the \(238^{th}\) larger capacity transformer is \(10900 + 29 = 10929\).

### Example 4.5

A person wants to buy a car. There are two brands of car available in the market and each brand has 3 variant models and each model comes in five different colours. In how many ways she can choose a car to buy?

**Solution:**

A car can be bought by choosing a brand, then a variant model, and then a colour. A brand can be chosen in 2 ways; a model can be chosen in 3 ways and a colour can be chosen in 5 ways. By the rule of product the person can buy a car in \(2 \times 3 \times 5 = 30\) different ways.

### Example 4.6

A Woman wants to select one silk saree and one sungudi saree from a textile shop located at Kancheepuram. In that shop, there are 20 different varieties of silk sarees and 8 different varieties of sungudi sarees. In how many ways she can select her sarees?

**Solution:**

The work is done when she selects one silk saree and one sungudi saree. The Woman can select a silk saree in 20 ways and sungudi saree in 8 ways. By the rule of product, the total number of ways of selecting these 2 sarees is \(20 \times 8 = 160\).

### Example 4.7

In a village, out of the total number of people, 80 percentage of the people own Coconut groves and 65 percent of the people own Paddy fields. What is the minimum percentage of people own both?

**Solution:**

Let \(n(C)\) denote the percentage of people who own the Coconut groves and \(n(P)\) denote the percentage of people who own Paddy fields. We are given \(n(C) = 80\) and \(n(P) = 65\). By the rule of inclusion - exclusion

$$
n(C \cap P) = n(C) + n(P) - n(C \cup P).
$$

The maximum value of \(n(C \cup P)\) is 100. Therefore, the minimum value of \(n(C \cap P)\) is \(80 + 65 - 100 = 45\). That is, the minimum percentage of the people who own both is 45.

In the next problem, we use the notion of a 'string'. A string is formed by writing given letters one by one in a sequence. For instance, strings of length three formed out of the letters a, b, c & d are aaa, abb, bda, dca, cdd ...

### Example 4.8

(i) Find the number of strings of length 4, which can be formed using the letters of the word BIRD, without repetition of the letters.
(ii) How many strings of length 5 can be formed out of the letters of the word PRIME taking all the letters at a time without repetition.

**Solution:**

(i) There are as many strings as filling the 4 vacant places by the 4 letters, keeping in mind that repetition is not allowed. The first place can be filled in 4 different ways by any one of the letters B, I, R, D. Following which, the second place can be filled in by any one of the remaining 3 letters in 3 different ways, following which the third place can be filled in 2 different ways, following which fourth place can be filled in 1 way.

Thus the total number of strings \(= 4 \times 3 \times 2 \times 1 = 24\). Hence, the required number of strings is 24.

(ii) There are 5 different letters with which 5 places are to be filled. The first place can be filled in 5 ways as any one of the five letters P, R, I, M, E can be placed there. Having filled the first place with any of the 5 letters, 4 letters are left to be placed in the second place, three letters are left for the third place and 2 letters are left to be put in the fourth place. The remaining 1 letter has to be placed in the fifth place. Hence, the total number of ways filling up five places is

$$
5 \times 4 \times 3 \times 2 \times 1 = 120.
$$

Hence, the total number of ways filling up five places is \(5 \times 4 \times 3 \times 2 \times 1 = 120\).

Observe the similarity between the above two cases.

### Example 4.9

How many strings of length 6 can be formed using letters of the word FLOWER if

(i) either starts with F or ends with R?
(ii) neither starts with F nor ends with R?

**Solution:**

In any such string, each of the letters F, L, O, W, E, R is used exactly once.

(i) If such a string starts with F, then the other five positions are to be filled with the letters L, O, W, E, R.

As there cannot be any repetition of letters in the formation of the strings we can fill up the 2nd, 3rd, 4th, 5th and 6th places in 5, 4, 3, 2 and 1 ways.

Hence, by the rule of product, the number of strings of length 6 starting with F is equal to \(5 \times 4 \times 3 \times 2 \times 1 = 120\).

If such a string ends with R, then the other five positions are to be filled with the letters F, L, O, W, E.

As in the previous case, we conclude that the number of strings of length ending with R is 120.

If a string starts with F and also ends with R, then the other 4 positions are to be filled with letters L, O, W, E.

**Figure 4.4**

**Figure 4.5**

**Figure 4.6**

As in the previous cases, the number of strings of length of 6 starting with F and ending with R is \(4 \times 3 \times 2 \times 1 = 24\).

By the principle of inclusion - exclusion, the number of strings of length 6, either starting with F or ending with R is \(120 + 120 - 24 = 216\).

(ii) A string that neither starts with F nor ends with R is one which has not been counted in (i). Together, they account for all possible strings of length 6 formed out of the letters, F, L, O, W, E, R, where no letter is repeated.

Now, the number of all such strings is formed by filling the first position by any of the 6 letters, the second by any of the remaining 5 letters and so on. That is, there are in total \(6 \times 5 \times 4 \times 3 \times 2 \times 1 = 720\) such strings. The number of words neither starting with F nor ending with R is the same as the difference between total number of letter strings and the number of strings either starting with F or end with R which is \(720 - 216 = 504\).

### Example 4.10

How many licence plates may be made using either two distinct letters followed by four digits or two digits followed by 4 distinct letters where all digits or letters are distinct?

**Solution:**

Here we have two cases:

Case 1: The number of licence plates having two letters followed by four digits is

$$
26 \times 25 \times 10 \times 9 \times 8 \times 7 = 32,76,000.
$$

Case 2: The number of licence plates having two digits followed by four letters is

$$
10 \times 9 \times 26 \times 25 \times 24 \times 23 = 3,22,92,000.
$$

Since either case 1 or case 2 is possible, the total number of licence plates is

$$
(26 \times 25 \times 10 \times 9 \times 8 \times 7) + (10 \times 9 \times 26 \times 25 \times 24 \times 23) = 3,55,68,000.
$$

### Example 4.11

Count the number of positive integers greater than 7000 and less than 8000 which are divisible by 5, provided that no digits are repeated.

**Solution:**

It should be a 4-digit number greater than 7000 and less than 8000. Then the \(1000^{th}\) place will be the digit 7. Further, as the number must be divisible by 5 the unit place should be either 0 or 5.

**Figure 4.7**

As repetition is not permitted, the \(100^{th}\) place can be filled in 8 ways using remaining numbers and \(10^{th}\) place can be filled in 7 ways.

Hence, the required number of numbers is \(1 \times 8 \times 7 \times 2 = 112\).

### Example 4.12

How many 4-digit even numbers can be formed using the digits 0, 1, 2, 3 and 4, if repetition of digits are not permitted?

**Solution:**

There are two conditions as follows:

1. It is 4-digit number and hence its \(1000^{th}\) place cannot be 0.
2. It is an even number and hence its unit place can be either 0, 2 or 4.

Two cases arise in this situation. Either 0 in the unit place or not.

**Case 1.** When the unit place is filled by 0, then the \(1000^{th}\) place can be filled in 4 ways, \(100^{th}\) place can be filled in 3 ways and \(10^{th}\) place in 2 ways. Therefore, number of 4-digit numbers having 0 at unit place is \(4 \times 3 \times 2 \times 1 = 24\).

**Case 2.** When the unit place is filled with non-zero numbers, that is 2 or 4, the number of ways is 2, the number of ways of filling the \(1000^{th}\) place is in 3 ways (excluding '0'), \(100^{th}\) place in 3 ways and \(10^{th}\) place in 2 ways. Therefore, number of 4-digit numbers without 0 at unit place is \(3 \times 3 \times 2 \times 2 = 36\).

**Figure 4.8**

**Figure 4.9**

Hence, by the rule of sum, the required number of 4 digit even numbers is \(24 + 36 = 60\).

### Example 4.13

Find the total number of outcomes when 5 coins are tossed once.

**Solution:**

When a coin is tossed, the outcomes are in two ways which are \(\{Head, Tail\}\). By the rule of product, the number of outcomes when 5 coins are tossed is \(2 \times 2 \times 2 \times 2 \times 2 = 2^5 = 32\).

More generally, if \(n\) coins are tossed then the number of outcomes is \(2^n\).

### Example 4.14

In how many ways (i) 5 different balls be distributed among 3 boxes? (ii) 3 different balls be distributed among 5 boxes?

**Solution:**

(i) Each ball can be placed into any one of the three boxes in 3 different ways. Therefore, by rule of product, the number of ways of distributing 5 different balls among three boxes is \(3 \times 3 \times 3 \times 3 \times 3 = 3^5 = 243\).

(ii) Each ball can be placed into any one of the five boxes in 5 different ways. Therefore, by rule of product, the number of ways of distributing 3 different balls among five boxes is \(5 \times 5 \times 5 = 5^3 = 125\).

In order to avoid confusions, take the objects(balls) and distribute them in places(boxes). More generally, if \(n\) different objects are to be placed in \(m\) places, then the number of ways of placing is \(m^n\).

### Example 4.15

There are 10 bulbs in a room. Each one of them can be operated independently. Find the number of ways in which the room can be illuminated.

**Solution:**

Each of the 10 bulbs are operated independently means that each bulb can be operated in two ways. That is in off mode or on mode. The total number of doing this are \(2^{10}\) which includes the case in which 10 bulbs are off. Keeping all 10 bulbs in "off" mode, the room cannot be illuminated. Hence, the total number of ways the room can be illuminated are \(2^{10} - 1 = 1024 - 1 = 1023\).

Another concept which is an essential tool in a counting process which is stated as follows:

### The Pigeonhole Principle:

Suppose a flock of pigeons fly into a set of pigeonholes. If there are more pigeons than pigeonholes then there must be at least one pigeonhole with at least two pigeons in it. A generalised form of this may be applied to other objects and situations as well. If \(k + 1\) or more objects are placed in \(k\) boxes, then there is at least one box containing two or more of the objects.

Here are some examples.

1. In any group of 27 English words, there must be at least two words which begin with the same letter (since there are only 26 letters in the English alphabet).
2. If six meetings are held 5 working days of a week, then there must be at least two meetings held on the same day.

## 4.3 Factorials

Factorial of a natural number \(n\) is the product of the first \(n\) natural numbers. It is denoted by \(n!\) That is,

$$
n! = 1 \times 2 \times 3 \times \dots \times n.
$$

We read this symbol as "\(n\) factorial" or "factorial of \(n\)". The notation \(n!\) was introduced by the French mathematician Christian Kramp in the year 1808. Note that for a positive integer \(n\)

\[
\begin{aligned}
n! &= n \times (n-1) \times (n-2) \times \dots \times 3 \times 2 \times 1 \\
&= n(n-1)! \quad \text{for } n > 1 \\
&= n(n-1)(n-2)! \quad \text{for } n > 2 \\
&= n(n-1)(n-2)(n-3)! \quad \text{for } n > 3 \text{ and so on}.
\end{aligned}
\]

Observe that,

\[
\begin{aligned}
1! &= 1 \\
2! &= 2 \times 1 = 2 \\
3! &= 3 \times 2 \times 1 = 6 \\
4! &= 4 \times 3 \times 2 \times 1 = 24 \\
5! &= 5 \times 4 \times 3 \times 2 \times 1 = 120 \\
&\dots \\
22! &= 22 \times 21 \times 20 \times \dots \times 3 \times 2 \times 1 = 1124000727777607680000
\end{aligned}
\]

The number 22 (the Birth date of Srinivasa Ramanujan) has a special place with respect to factorial that, it is the least integer \(N\) greater than 1 whose factorial has exactly \(N\) digits.

It will be a good exercise for both students and teachers to find the next number \(N\) such that \(N!\) has exactly \(N\) digits.

Note that \(0! = 1\) is evident by substituting \(n = 0\) in the equation \((n+1)! = (n+1) \times n!\) as \(1! = (0+1) \times 0! \Rightarrow 0! = \frac{1!}{1} = 1\). This way, we talk of factorial for non-negative integers. Note that factorials can be extended to certain negative numbers and also to complex numbers, which are beyond the scope of this book.

We shall now discuss certain examples in order to familiarise the computation of factorials.

### Example 4.16

Find the value of

(i) \(5!\) (ii) \(6! - 5!\) (iii) \(\frac{8!}{5! \times 2!}\)

**Solution:**

\[
\begin{aligned}
\text{(i)} \quad 5! &= 5 \times 4 \times 3 \times 2 \times 1 = 120. \\
\text{(ii)} \quad 6! - 5! &= 6 \times 5! - 5! = (6 - 1) \times 5! = 5 \times 120 = 600. \\
\text{(iii)} \quad \frac{8!}{5! \times 2!} &= \frac{8 \times 7 \times 6 \times 5!}{5! \times 2!} = \frac{8 \times 7 \times 6}{2} = 168.
\end{aligned}
\]

### Example 4.17

Find the value of \(\frac{7!}{2!}\).

**Solution:**

\[
\frac{7!}{2!} = \frac{7 \times 6 \times 5 \times 4 \times 3 \times 2!}{2!} = 7 \times 6 \times 5 \times 4 \times 3 = 2520.
\]

### Example 4.18

Evaluate \(\frac{n!}{r!(n - r)!}\) when (i) \(n = 7, r = 5\) (ii) \(n = 50, r = 47\) (iii) For any \(n\) with \(r = 3\).

**Solution:**

(i) When \(n = 7, r = 5\)

\[
\frac{n!}{r!(n - r)!} = \frac{7!}{5!(7 - 5)!} = \frac{7 \times 6 \times 5!}{5! \times 2!} = \frac{7 \times 6}{1 \times 2} = 21.
\]

(ii) When \(n = 50, r = 47\)

\[
\frac{n!}{r!(n - r)!} = \frac{50!}{47!(50 - 47)!} = \frac{50 \times 49 \times 48 \times 47!}{47! \times 3!} = \frac{50 \times 49 \times 48}{1 \times 2 \times 3} = 19600.
\]

(iii) For any \(n\) and \(r = 3\)

\[
\frac{n!}{r!(n - r)!} = \frac{n!}{3!(n - 3)!} = \frac{n \times (n - 1) \times (n - 2) \times (n - 3)!}{1 \times 2 \times 3 \times (n - 3)!} = \frac{n(n - 1)(n - 2)}{6}.
\]

### Example 4.19

Let \(N\) denote the number of days. If the value of \(N!\) is equal to the total number of hours in \(N\) days then find the value of \(N\).

**Solution:**

We need to solve the equation \(N! = 24 \times N\).

For \(N = 1, 2, 3, 4\): \(N! < 24 \times N\).

For \(N = 5\): \(N! = 5! = 4! \times 5 = 24N\).

For \(N > 5\): \(N! \geq 5! N > 24 \times N\).

Hence \(N = 5\).

### Example 4.20

If \(\frac{6!}{n!} = 6\), then find the value of \(n\).

**Solution:**

\[
\frac{6!}{n!} = \frac{1 \cdot 2 \cdot 3 \cdot 4 \cdot 5 \cdot 6}{1 \cdot 2 \cdot 3 \ldots n} = 6.
\]

As \(n < 6\) we get \(n = 5\).

### Example 4.21

If \(n! + (n - 1)! = 30\), then find the value of \(n\).

**Solution:**

Now, \(30 = 6 \times 5\). As \(n! + (n - 1)! = (n + 1)(n - 1)!\), equating \((n - 1)! = 6 = 3!\), we get \(n = 4\).

### Example 4.22

What is the unit digit of the sum \(2! + 3! + 4! + \ldots + 22!\)?

**Solution:**

From 5! onwards for all \(n!\) the unit digit is zero and hence the contribution to the unit digit is through \(2! + 3! + 4!\) only, which is \(2 + 6 + 24 = 32\). Therefore the required unit digit is 2.

### Example 4.23

If \(\frac{1}{7!} + \frac{1}{8!} = \frac{A}{9!}\) then find the value of \(A\).

**Solution:**

We have,

\[
\frac{A}{9 \times 8 \times 7!} = \frac{1}{7!} + \frac{1}{8 \times 7!}.
\]

Therefore,

\[
\frac{1}{7!} \times \frac{A}{9 \times 8} = \frac{1}{7!} \times \left[1 + \frac{1}{8}\right],
\]

equivalently, \(\frac{A}{72} = \frac{9}{8}\), which implies \(A = 81\).

### Example 4.24

Prove that \(\frac{(2n)!}{n!} = 2^n (1 \cdot 3 \cdot 5 \cdots (2n - 1))\).

**Solution:**

\[
\begin{aligned}
\frac{(2n)!}{n!} &= \frac{1 \cdot 2 \cdot 3 \cdot 4 \cdots (2n - 2) \cdot (2n - 1) \cdot 2n}{n!} \\
&= \frac{(1 \cdot 3 \cdot 5 \cdots (2n - 1)) \cdot (2 \cdot 4 \cdot 6 \cdots (2n - 2) \cdot 2n)}{n!} \quad \text{(Grouping the odd and even numbers separately)} \\
&= \frac{(1 \cdot 3 \cdot 5 \cdots (2n - 1)) \cdot 2^n (1 \cdot 2 \cdot 3 \cdots (n - 1) \cdot n)}{n!} \quad \text{(taking out the 2's)} \\
&= \frac{(1 \cdot 3 \cdot 5 \cdots (2n - 1)) \cdot 2^n \cdot n!}{n!} \\
&= 2^n (1 \cdot 3 \cdot 5 \cdots (2n - 1)).
\end{aligned}
\]

## Exercise 4.1

1. (i) A person went to a restaurant for dinner. In the menu card, the person saw 10 Indian and 7 Chinese food items. In how many ways the person can select either an Indian or a Chinese food?

   (ii) There are 3 types of toy car and 2 types of toy train available in a shop. Find the number of ways a baby can select a toy car and a toy train?

   (iii) How many two-digit numbers can be formed using 1, 2, 3, 4, 5 without repetition of digits?

2. (i) A mobile phone has a passcode of 6 distinct digits. What is the maximum number of attempts one makes to retrieve the passcode?

   (ii) Given four flags of different colours, how many different signals can be generated if each signal requires the use of three flags, one below the other?

3. Four children are running a race.

   (i) In how many ways can the first two places be filled?

   (ii) In how many different ways could they finish the race?

4. Count the number of three-digit numbers which can be formed from the digits 2, 4, 6, 8 if

   (i) repetition of digits is allowed.

   (ii) repetition of digits is not allowed.

5. How many three-digit numbers are there with 3 in the unit place?

   (i) with repetition

   (ii) without repetition.

6. How many numbers are there between 100 and 500 with the digits 0, 1, 2, 3, 4, 5 ?

   (i) With repetition of digits

   (ii) Without repetition of digits

7. How many three-digit odd numbers can be formed by using the digits 0, 1, 2, 3, 4, 5 ?

   (i) With repetition of digits

   (ii) Without repetition of digits

8. Count the numbers between 999 and 10000 subject to the condition that there are

   (i) no restriction.

   (ii) no digit is repeated.

   (iii) at least one of the digits is repeated.

9. How many three-digit numbers, which are divisible by 5, can be formed using the digits 0, 1, 2, 3, 4, 5 if

   (i) repetition of digits are not allowed?

   (ii) repetition of digits are allowed?

10. To travel from a place A to place B, there are two different bus routes \(B_1, B_2\), two different train routes \(T_1, T_2\) and one air route \(A_1\). From place B to place C there is one bus route say \(B_1'\), two different train routes say \(T_1', T_2'\) and one air route \(A_1'\). Find the number of routes of commuting from place A to place C via place B without using similar mode of transportation.

11. How many numbers are there between 1 and 1000 (both inclusive) which are divisible neither by 2 nor by 5?

12. How many strings can be formed using the letters of the word LOTUS if the word

    (i) either starts with L or ends with S?

    (ii) neither starts with L nor ends with S?

13. (i) Count the total number of ways of answering 6 objective type questions, each question having 4 choices.

    (ii) In how many ways 10 pigeons can be placed in 3 different pigeon holes?

    (iii) Find the number of ways of distributing 12 distinct prizes to 10 students?

14. Find the value of

    (i) \(6!\)

    (ii) \(4! + 5!\)

    (iii) \(3! - 2!\)

    (iv) \(3! \times 4!\)

    (v) \(\frac{12!}{9! \times 3!}\)

    (vi) \(\frac{(n + 3)!}{(n + 1)!}\)

15. Evaluate \(\frac{n!}{r!(n - r)!}\) when

    (i) \(n = 6\), \(r = 2\)

    (ii) \(n = 10\), \(r = 3\)

    (iii) For any \(n\) with \(r = 2\)

16. Find the value of \(n\) if

    (i) \((n + 1)! = 20(n - 1)!\)

    (ii) \(\frac{1}{8!} + \frac{1}{9!} = \frac{n}{10!}\)

### Double Factorial of \(n\)

Factorial of an integer \(n\), denoted by \(n!\) can be viewed as a function \(f : \mathbb{N} \cup \{0\} \to \mathbb{N}\), where \(\mathbb{N}\) is the set of all Natural numbers, define as

$$
f(n) = n! = \begin{cases}
1 & \text{if } n = 0, 1 \\
n \times (n - 1)! & \text{if } n > 1
\end{cases}
$$

One can define \(n!!\) (double factorial of \(n\)) as

$$
n!! = \begin{cases}
n \times (n - 2) \times \cdots 5 \times 3 \times 1 & \text{if } n \text{ is odd} \\
n \times (n - 2) \times \cdots 6 \times 4 \times 2 & \text{if } n \text{ is even}
\end{cases}
$$

Accordingly, \(5!! = 5 \times 3 \times 1 = 15\) and \(8!! = 8 \times 6 \times 4 \times 2 = 384\). Note that \(n!! \neq (n!)!\) as \(4!! = 8\) whereas \((4!)! = (24)!\).

## 4.4 Permutations

What is a permutation? Permutations come in various disguises.

Suppose three friends A, B and C have to stand in line for a photograph. In how many order can they stand? Some of the possible arrangements (from left to right) are

ABC, ACB, BAC, BCA, CAB, CBA.

Thus there are six possible ways in which they can arrange themselves for the photograph.

Thus if 3 objects have to be arranged in a row there are \(3 \times 2 \times 1 = 3!\) possible permutations. The number of permutations of 4 objects taken all at a time is \(4 \times 3 \times 2 \times 1 = 4!\). Thus if \(n\) objects have to be arranged in a line there are \(n \times (n-1) \times (n-2) \times \dots \times 3 \times 2 \times 1 = n!\) possible arrangements or permutations.

Suppose you have 7 letters A, B, C, D, E, F and G. We want to make a 4 letter string. We have 7 choices for the 1st letter. Having chosen the first letter, we have 6 choices for the second letter. Proceeding this way, we have 4 choices for the 4th letter.

Hence, the number of permutations of 4 letter strings chosen from 7 letters is

$$
7 \times 6 \times 5 \times 4 = \frac{7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1}{3 \times 2 \times 1} = \frac{7!}{3!} = \frac{7!}{(7 - 4)!}.
$$

More generally, the number of distinct permutations of \(r\) objects which can be made from \(n\) distinct objects is \(\frac{n!}{(n - r)!}\). It is denoted by \(^{n}P_{r}\). The formal proof of this result will be proved in this section.

### 4.4.1 Permutations of distinct objects

In terms of function on any finite set say \(S = \{x_1, x_2, \ldots, x_n\}\), a permutation can be defined as a bijective mapping on the set \(S\) onto itself. The number of permutation on the set \(S\) is the same as the total number of bijective mappings on the set \(S\).

We denote the number of permutations by \(^{n}P_{r}\).

### Theorem 4.1

If \(n, r\) are positive integers and \(r \leq n\), then the number of permutations of \(n\) distinct objects taken \(r\) at a time is

$$
n(n - 1)(n - 2) \dots (n - r + 1).
$$

**Proof.** A permutation is an ordering. A permutation of \(n\) distinct objects taken \(r\) at a time is formed by filling of \(r\) positions, in a row with objects chosen from the given \(n\) distinct objects.

There are \(n\) objects that can be filled in the first position. For the second position there are remaining \(n - 1\) objects. There are \(n - 2\) objects for the third position. Continuing like this until finally we place one of the \((n - (r - 1))\) possible objects in the \(r^{th}\) position. By the rule of product we conclude

$$
^{n}P_{r} = n(n - 1)(n - 2) \dots (n - r + 1).
$$

### Theorem 4.2

If \(n \geq 1\), and \(0 \leq r \leq n\), then

$$
^{n}P_{r} = \frac{n!}{(n - r)!}.
$$

**Proof.** By Theorem 4.1, we have,

\[
\begin{aligned}
^{n}P_{r} &= n \times (n-1) \times (n-2) \times \dots \times (n - r + 1) \\
&= \frac{n \times (n-1) \times (n-2) \times \dots \times (n - r + 1) \times (n - r) \times (n - r - 1) \dots 2 \times 1}{(n - r) \times (n - r - 1) \times \dots \times 2 \times 1} \\
&= \frac{n!}{(n - r)!}.
\end{aligned}
\]

To be specific, if \(n\) is a positive integer, and \(r\) is any non-negative integer, we can represent,

$$
^{n}P_{0} = 1, \quad ^{n}P_{1} = n, \quad ^{n}P_{n} = n!.
$$

The \(n\) different objects arranged in a row is \(^{n}P_{n} = n!\) ways.

### Theorem 4.3

The number of permutations of \(n\) different objects taken \(r\) at a time where repetition is allowed, is \(n^{r}\).

**Proof.** As in Theorem 4.1. We can fill the first position with \(n\) objects. For the second position (still we can use the object used in first position), there are \(n\) objects, and so on the \(r^{th}\) position can be filled with \(n\) objects. By the rule of product, the number of permutations of \(n\) different objects taken \(r\) at a time when repetition allowed is \(n \times n \times n \times \cdots n\) (\(r\) times) = \(n^{r}\).

### 4.4.2 Properties of Permutations

**Property 1:** \(^{n}P_{n} = ^{n}P_{n-1}\).

**Proof.** We have,

$$
^{n}P_{n-1} = \frac{n!}{(n - (n - 1))!} = \frac{n!}{1!} = n! = \frac{n!}{(n - n)!} = ^{n}P_{n}.
$$

**Property 2:** \(^{n}P_{r} = n \times ^{n-1}P_{r-1}\).

**Proof.** We have,

$$
n \times ^{n-1}P_{r-1} = n \times \frac{(n - 1)!}{((n - 1) - (r - 1))!} = \frac{n!}{(n - r)!} = ^{n}P_{r}.
$$

Continuing this process, we arrive at

\[
\begin{aligned}
^{n}P_{r} &= n \times ^{n-1}P_{r-1} = n \times (n-1) \times ^{n-2}P_{r-2} \\
&= n \times (n-1) \times (n-2) \times ^{n-3}P_{r-3} \times \cdots \times (n - (r - 1)) \times ^{n-r}P_{0} \\
&= n \times (n-1) \times (n-2) \times \cdots \times (n - r + 1).
\end{aligned}
$$

Thus, \(^{n}P_{r} = n \times (n-1) \times (n-2) \times \cdots \times (n - r + 1)\).

**Property 3:** \(^{n}P_{r} = ^{n-1}P_{r} + r \times ^{n-1}P_{r-1}\).

**Proof.** We have,

\[
\begin{aligned}
^{n-1}P_{r} + r \times ^{n-1}P_{r-1} &= \frac{(n-1)!}{((n-1)-r)!} + r\frac{(n-1)!}{(n - r)!} \\
&= \frac{(n-1)!}{(n - 1 - r)!} + \frac{r(n-1)!}{(n - r)!} \\
&= \frac{(n-1)! \times (n - r)}{(n - 1 - r)! \times (n - r)} + \frac{r(n-1)!}{(n - r)!} \\
&= \frac{(n-1)! \times (n - r)}{(n - r)!} + \frac{r(n-1)!}{(n - r)!} \\
&= \frac{(n-1)!((n - r) + r)}{(n - r)!} \\
&= \frac{(n-1)! n}{(n - r)!} = \frac{n!}{(n - r)!} = ^{n}P_{r}.
\end{aligned}
\]

### Example 4.25

Evaluate:

(i) \(^{4}P_{4}\) (ii) \(^{5}P_{3}\) (iii) \(^{8}P_{4}\) (iv) \(^{6}P_{5}\).

**Solution:**

\[
\begin{aligned}
^{4}P_{4} &= 4 \times 3 \times 2 \times 1 = 4! = 24. \\
^{5}P_{3} &= 5 \times 4 \times 3 = 60. \\
^{8}P_{4} &= 8 \times 7 \times 6 \times 5 = 1680. \\
^{6}P_{5} &= 6 \times 5 \times 4 \times 3 \times 2 = 6! = 720.
\end{aligned}
\]

### Example 4.26

If \(^{n+2}P_{4} = 42 \times ^{n}P_{2}\) find \(n\).

**Solution:**

\[
\frac{^{n+2}P_{4}}{^{n}P_{2}} = 42
\]

\[
\Rightarrow \frac{(n+2)(n+1)(n)(n-1)}{n(n-1)} = 42
\]

\[
\Rightarrow (n+2)(n+1) = 42 = 7 \times 6
\]

\[
\Rightarrow n+2 = 7 \Rightarrow n = 5.
\]

### Example 4.27

If \(^{10}P_{r} = ^{7}P_{r+2}\) find \(r\).

**Solution:**

\[
^{10}P_{r} = ^{7}P_{r+2}
\]

\[
\frac{10!}{(10 - r)!} = \frac{7!}{(5 - r)!}
\]

i.e.,

\[
\frac{10 \times 9 \times 8 \times 7!}{(10 - r) \times (9 - r) \times (8 - r) \times (7 - r) \times (6 - r) \times (5 - r)!} = \frac{7!}{(5 - r)!}
\]

\[
(10 - r) \times (9 - r) \times (8 - r) \times (7 - r) \times (6 - r) = 10 \times 9 \times 8 = 6 \times 5 \times 4 \times 3 \times 2.
\]

Here, \(r\) is a positive integer.

Therefore, \(10 - r = 6 \Rightarrow r = 4\).

### Example 4.28

How many 'letter strings' together can be formed with the letters of the word "VOWELS" so that

(i) the strings begin with \(E\)

(ii) the strings begin with \(E\) and end with \(W\).

**Solution:**

The given strings contains 6 letters (V, O, W, E, L, S).

(i) Since all strings must begin with \(E\) we have the remaining 5 letters which can be arranged in \(^{5}P_{5} = 5!\) ways. Therefore the total number of strings with \(E\) as the starting letter is \(5! = 120\).

(ii) Since all strings must begin with \(E\) and end with \(W\) we need to fix \(E\) and \(W\). The remaining 4 letters can be arranged in \(^{4}P_{4} = 4!\) ways.

**Figure 4.10**

**Figure 4.11**

Therefore the total number of strings with \(E\) as the starting letter and \(W\) as the final letter is \(4! = 24\).

### Example 4.29

A four digit number with four different digits using 1, 2, 3, 4 and 5 is formed. Find the following

(i) How many such numbers can be formed?

(ii) How many of these are even?

(iii) How many of these are exactly divisible by 4?

**Solution:**

(i) The solution for this is the same as the number of permutations taking four digits out of 5 digits is \(^{5}P_{4} = 5 \times 4 \times 3 \times 2 = 120\).

(ii) For even number last digits must be 2 or 4 which is filled in \(^{2}P_{1}\) ways and remaining 3 places filled from remaining 4 digits in \(^{4}P_{3}\) ways. Therefore the required number of ways is \(^{2}P_{1} \times ^{4}P_{3} = 2 \times 24 = 48\).

(iii) Since the number divisible by 4, then last two digit must be divisible by 4. The Last two digits become 12, 24, 32, 52 (4 ways). The remaining first two places filled from remaining 3 digits in \(^{3}P_{2}\) ways. The required number of numbers which are divisible by 4 is \(^{4}P_{1} \times ^{3}P_{2} = 4 \times 6 = 24\).

**Figure 4.12**

**Figure 4.13**

**Figure 4.14**

### 4.4.3 Objects always together (String method)

The number of permutations of \(n\) different objects, taken all at a time, when \(m\) specified objects are always together:

Consider a string of \(m\) specified objects as a single unit. Then we have \((n - m + 1)\) objects. Permute these \((n - m + 1)\) objects in \((n - m + 1)!\) ways. Then permute the \(m\) specified objects between themselves in \(m!\) ways. Finally, the answer is \(m! \times (n - m + 1)!\).

### 4.4.4 No two things are together (Gap method)

To obtain the number of permutations of \(n\) different objects when no two of \(k\) given objects occur together and there are no restrictions on the remaining \(m = n - k\) objects, we follow the procedure as follows:

First of all, arrange the \(m\) objects on which there is no restriction in a row. These \(m\) objects can be permuted in \(^{m}P_{m} = m!\) ways. Then count the number of gaps between every two of \(m\) objects on which there is no restriction including the end positions. Number of such gaps will be one more than \(m\) that is \((m + 1)\). In these \(m + 1\) gaps, we can permute the \(k\) objects in \(^{m+1}P_{k}\) ways. Then the required number of ways are \(m! \times ^{m+1}P_{k}\).

### Example 4.30

How many different strings can be formed together using the letters of the word "EQUATION" so that

(i) the vowels always come together?

(ii) the vowels never come together?

**Solution:**

(i) There are 8 letters in the word "EQUATION" which includes 5 vowels (E, U, A, I, O) and 3 consonants (Q, T, N). Considering 5 vowels as one letter, we have 4 letters which can be arranged in \(^{4}P_{4} = 4!\) ways. But corresponding each of these arrangements, the vowels E, U, A, I, O can be put in \(^{5}P_{5} = 5!\) ways.

Hence, by the rule of product required number of words is \(4! \times 5! = 24 \times 120 = 2880\).

(ii) The total number of strings formed by using all the eight letters of the word "EQUATION" is \(^{8}P_{8} = 8! = 40320\).

So, the total number of strings in which vowels are never together is the same as the difference between the total number of strings and the number of strings in which vowels are together is \(40320 - 2880 = 37440\).

### Example 4.31

There are 15 candidates writing an examination. 7 candidates are appearing for mathematics examination while the remaining 8 are appearing for different subjects. In how many ways can they be seated in a row so that no two candidates writing mathematics are together?

**Solution:**

Let us arrange the 8 non-mathematics candidates in \(^{8}P_{8} = 8!\) ways. Each of these arrangements create 9 gaps. Therefore, the 7 candidates writing mathematics can be placed in these 9 gaps in \(^{9}P_{7}\) ways.

\[
- O_1 - O_2 - O_3 - O_4 - O_5 - O_6 - O_7 - O_8 -
\]

By the rule of product, the required number of arrangements is

$$
8! \times ^{9}P_{7} = 8! \times \frac{9!}{2!} = \frac{8! \times 9!}{2!}.
$$

### Example 4.32

In how many ways 5 boys and 4 girls can be seated in a row so that no two girls are together.

**Solution:**

\[
\_ B_1 \_ B_2 \_ B_3 \_ B_4 \_ B_5 \_
\]

The 5 boys can be seated in the row in \(^{5}P_{5} = 5!\) ways. In each of these arrangements 6 gaps are created. Since no two girls are to sit together, we may arrange 4 girls in these 6 gaps. This can be done in \(^{6}P_{4}\) ways. Hence, the total number of seating arrangements is

$$
5! \times ^{6}P_{4} = 120 \times 360 = 43200.
$$

### Example 4.33

4 boys and 4 girls form a line with the boys and girls alternating. Find the number of ways of making this line.

**Solution:**

4 boys can be arranged in a line in \(^{4}P_{4} = 4!\) ways. By keeping boys as first in each of these arrangements, 4 gaps are created. In these 4 gaps, 4 girls can be arranged in \(^{4}P_{4} = 4!\) ways.

\[
B_1 \_ B_2 \_ B_3 \_ B_4 \_ \quad \text{or} \quad \_ G_1 \_ G_2 \_ G_3 \_ G_4 \_
\]

Therefore, keeping boys as first, the total number of arrangements are \(4! \times 4!\). Similarly, keeping girls as first, by a similar argument, the total number of arrangements are \(4! \times 4!\). Hence, by the rule of sum, keeping either a boy or a girl first, the total number of arrangements are

$$
(4! \times 4!) + (4! \times 4!) = 2(4!)^2 = 1152.
$$

### Example 4.34

A van has 8 seats. It has two seats in the front with two rows of three seats behind. The van belongs to a family, consisting of seven members, \(F, M, S_1, S_2, S_3, D_1, D_2\). How many ways can the family sit in the van if

(i) There are no restriction?

(ii) Either \(F\) or \(M\) drives the van?

(iii) \(D_1, D_2\) sits next to a window and \(F\) is driving?

**Solution:**

(i) As there are 8 seats to be occupied out of which one seat is for the one who drives. Since there are no restrictions any one can drive the van. Hence the number of ways of occupying the driver seat is \(^{7}P_{1} = 7\) ways. The number of ways of occupying the remaining 7 seats by the remaining 6 people is \(^{7}P_{6} = 5040\). Hence the total number of ways the family can be seated in the car is \(7 \times 5040 = 35280\).

(ii) As the driver seat can be occupied by only F or M, there are only two ways it can be occupied. Hence the total number of ways the family can be seated in the car is \(2 \times 5040 = 10080\).

(iii) As there are only 5 window seats available for \(D_1 \& D_2\) to occupy the number of ways of seated near the windows by the two family members is \(^{5}P_{2} = 20\). As the driver seat is occupied by F, the remaining 4 people can be seated in the available 5 seats in \(^{5}P_{4} = 120\). Hence the total number of ways the family can be seated in the car is \(20 \times 1 \times 120 = 2400\).

To understand the next problem we now define, **The Rank of a word in the dictionary**. It is the place at which the given word comes when writing all the strings formed by the letters of the given word in the dictionary order or lexicographic order.

### Example 4.35

If the letters of the word TABLE are permuted in all possible ways and the words thus formed are arranged in the dictionary order (alphabetical order), find the ranks of the words (i) TABLE, (ii) BLEAT.

**Solution:**

The dictionary order of the letters of given word is A, B, E, L, T. In the dictionary order of the words which begin with A come first. If we fill the first place with A, remaining 4 letters (B, E, L, T) can be arranged in 4! ways. On proceeding like this we get

(i) The rank of the word TABLE

\[
\begin{aligned}
A - - - - &= 4! = 24 \text{ words} \\
B - - - - &= 4! = 24 \text{ words} \\
E - - - - &= 4! = 24 \text{ words} \\
L - - - - &= 4! = 24 \text{ words} \\
T A B E L &= 1 \text{ word} \\
T A B L E &= 1 \text{ word}
\end{aligned}
\]

The rank of the word TABLE is \(4 \times 4! + 1 + 1 = 98\).

(ii) The rank of the word BLEAT

\[
\begin{aligned}
A - - - - &= 4! = 24 \text{ words} \\
BA - - - &= 3! = 6 \text{ words} \\
BE - - - &= 3! = 6 \text{ words} \\
BLA - - &= 2! = 2 \text{ words} \\
BLEAT &= 1 \text{ word}
\end{aligned}
\]

The rank of the word BLEAT is \(24 + 6 + 6 + 2 + 1 = 39\).

### 4.4.5 Permutations of not all distinct objects

Consider permuting the letters of the word JEE. In this case the letters of the word are not different. There are 2 E's, which are of same kind. Let us treat, temporarily, the 2 E's as different, say \(E_1\) and \(E_2\). The number of permutations of 3 different letters taken all at a time is 3!.

| Permutations when \(E_1, E_2\) are different | Permutations when \(E_1, E_2\) are the same |
|---------------------------------------------|-------------------------------------------|
| \(J E_1 E_2, J E_2 E_1\) | \(J E E\) |
| \(E_1 J E_2, E_2 J E_1\) | \(E J E\) |
| \(E_1 E_2 J, E_2 E_1 J\) | \(E E J\) |

It is because of the two \(E_1, E_2\) permuted internally will give rise to the same permutations. Since they are same, the required number of permutations is \(\frac{3!}{2!} = 3\).

### Theorem 4.4

The number of permutations of \(n\) objects, where \(p\) objects are of the same kind and rest are all different is \(\frac{n!}{p!}\).

Generally, the number of permutations of \(n\) objects, where \(p_1\) objects are of one kind, \(p_2\) objects are of second kind, \(\dots p_k\) are of \(k^{th}\) kind and the rest of it are of different kind is

$$
\frac{n!}{p_1! \times p_2! \times \dots \times p_k!}.
$$

### Example 4.36

Find the number of ways of arranging the letters of the word BANANA.

**Solution:**

This word has 6 letters in which there are 3 A's, 2 N's and one B. The number of ways of arrangements is

$$
\frac{6!}{3! \times 2!} = 60.
$$

### Example 4.37

Find the number of ways of arranging the letters of the word RAMANUJAN so that the relative positions of vowels and consonants are not changed.

**Solution:**

In the word RAMANUJAN there are 4 vowels (A, A, U, A) in that 3 A's, 1 U and 5 consonants (R, M, N, J, N) in that two N's and rest are distinct. The 4 vowels (A, A, A, U) can be arranged themselves in \(\frac{4!}{3!} = 4\) ways. The 5 consonants (R, M, N, J, N) can be arranged themselves in \(\frac{5!}{2!} = 60\) ways. Therefore the number of required arrangements are

$$
\frac{4!}{3!} \times \frac{5!}{2!} = 4 \times 60 = 240.
$$

### Example 4.38

Three twins pose for a photograph standing in a line. How many arrangements are there

(i) when there are no restrictions.

(ii) when each person is standing next to his or her twin?

**Solution:**

(i) The six persons without any restriction may be arranged in \(^{6}P_{6} = 6! = 720\) ways.

(ii) Let us consider three twins as \(T_1, T_2, T_3\). Each twin is considered as a single unit and these three can be permuted in 3! ways. Again each twin can be permuted between themselves in 2! ways. Hence, the total number of arrangements is \(3! \times 2! \times 2! \times 2! = 48\) ways.

### Example 4.39

How many numbers can be formed using the digits 1, 2, 3, 4, 2, 1 such that even digits occupies even place?

**Solution:**

There are 6 places in that there are 3 even places we have 2, 4, 2 as even numbers. The number of ways of permuting 2, 4, 2 in the 3 even places in \(\frac{3!}{2!} = 3\) ways. The remaining numbers 1, 3, 1 can be permuted in the remaining 3 places in \(\frac{3!}{2!} = 3\) ways. Hence, the required number of numbers is \(3 \times 3 = 9\).

### Example 4.40

How many paths are there from start to end on a \(6 \times 4\) grid as shown in the picture?

**Figure 4.15**

**Solution:**

Note that any such path comprises 6 horizontal unit lengths and 4 vertical unit lengths. Thus each path consists of 10 unit lengths where 6 are of one kind (horizontal) and 4 are of another kind (vertical).

Thus the total number of paths is

$$
\frac{10!}{4! \times 6!} = 210.
$$

### Example 4.41

If the different permutations of all letters of the word BHASKARA are listed as in a dictionary, how many strings are there in this list before the first word starting with B?

**Solution:**

The required number of strings is the total number of strings starting with A and using the letters A, A, B, H, K, R, S is

$$
\frac{7!}{2!} = 2520.
$$

### Example 4.42

If the letters of the word IITJEE are permuted in all possible ways and the strings thus formed are arranged in the lexicographic order, find the rank of the word IITJEE.

**Solution:**

The lexicographic order of the letters of given word is E, E, I, I, J, T. In the lexicographic order, the strings which begin with E come first. If we fill the first place with E, remaining 5 letters (E, I, I, J, T) can be arranged in \(\frac{5!}{2!}\) ways. On proceeding like this we get

\[
\begin{aligned}
E - - - - &= \frac{5!}{2!} = 60 \text{ ways} \\
IE - - - - &= 4! = 24 \text{ ways} \\
IIE - - - &= 3! = 6 \text{ ways} \\
IIJ - - - &= \frac{3!}{2!} = 3 \text{ ways} \\
IITE - - &= 2! = 2 \text{ ways} \\
IITJEE &= 1 \text{ way}
\end{aligned}
\]

The rank of the word IITJEE is \(60 + 24 + 6 + 3 + 2 + 1 = 96\).

### Example 4.43

Find the sum of all 4-digit numbers that can be formed using the digits 1, 2, 4, 6, 8.

**Solution:**

The number of 4-digit numbers that can be formed using the given 5 digits is \(^{5}P_{4} = 120\). We first find the sum of the digits in the unit place of all these 120 numbers. By filling 1 in unit place, the remaining three places can be filled with remaining 4 digits in \(^{4}P_{3} = 24\) ways. This means, the number of 4-digit numbers having 1 in units place is \(^{4}P_{3} = 24\). Similarly, each of the digits 2, 4, 6, 8 appear 24 times in units place. An addition of all these digits gives the sum of all the unit digits of all 120 numbers. Therefore,

\[
\begin{aligned}
(^{4}P_{3} \times 1) + (^{4}P_{3} \times 2) + (^{4}P_{3} \times 4) + (^{4}P_{3} \times 6) + (^{4}P_{3} \times 8) \\
&= ^{4}P_{3} \times (1 + 2 + 4 + 6 + 8) \\
&= ^{4}P_{3} \times (\text{sum of the digits}) \\
&= ^{4}P_{3} \times 21.
\end{aligned}
\]

Similarly, we get the sum of the digits in \(10^{th}\) place as \(^{4}P_{3} \times 21\). Since it is in \(10^{th}\) place, its value is \(^{4}P_{3} \times 21 \times 10\). Similarly, the values of the sum of the digits in \(100^{th}\) place and \(1000^{th}\) place are \(^{4}P_{3} \times 21 \times 100\) and \(^{4}P_{3} \times 21 \times 1000\) respectively. Hence the sum of all the 4 digit numbers formed by using the digits 1, 2, 4, 6, 8 is

\[
\begin{aligned}
&(^{4}P_{3} \times 21) + (^{4}P_{3} \times 21 \times 10) + (^{4}P_{3} \times 21 \times 100) + (^{4}P_{3} \times 21 \times 1000) \\
&= ^{4}P_{3} \times 21 \times 1111 \\
&= 24 \times 21 \times 1111 \\
&= 559944.
\end{aligned}
\]

**Deduction 4.1:** The sum of all \(r\)-digit numbers that can be formed using the given \(n\) non zero digits is

$$
^{(n-1)}P_{(r-1)} \times (\text{sum of the digits}) \times \underbrace{111\ldots1}_{r \text{ times}}.
$$

**Deduction 4.2:** If 0 is one digit among the given \(n\) digits, then we get that the sum of the \(r\)-digits numbers that can be formed using the given \(n\) digits (including 0) is

$$
\{{}^{(n-1)}P_{(r-1)} \times (\text{sum of the digits}) \times \underbrace{111\ldots1}_{r \text{ times}}\} - \{{}^{(n-2)}P_{(r-2)} \times (\text{sum of the digits}) \times \underbrace{111\ldots1}_{(r-1) \text{ times}}\}.
$$

### Permutation as Function

Permutation on any finite set \(S_n = \{x_1, x_2, x_3, \dots, x_n\}\) is a bijective function from \(S_n \to S_n\). Therefore the set of all permutations on a finite set with \(n\) elements is the same as the total number of bijective functions on the set. This is precisely \(n!\). Hence the study of permutation is the same as the study of the bijective mappings on the set. Few representations for a permutation on \(S_3\) are given by

$$
f : \begin{pmatrix} 1 & 2 & 3 \\ 2 & 1 & 3 \end{pmatrix}, \quad g : \begin{pmatrix} 1 & 2 & 3 \\ 2 & 3 & 1 \end{pmatrix}.
$$

## Exercise 4.2

1. If \(^{n-1}P_{3} : ^{n}P_{4} = 1 : 10\) find \(n\).

2. If \(^{10}P_{r-1} = 2 \times ^{6}P_{r}\) find \(r\).

3. (i) Suppose 8 people enter an event in a swimming meet. In how many ways could the gold, silver and bronze prizes be awarded?

   (ii) Three men have 4 coats, 5 waist coats and 6 caps. In how many ways can they wear them?

4. Determine the number of permutations of the letters of the word SIMPLE if all are taken at a time.

5. A test consists of 10 multiple choice questions. In how many ways can the test be answered if

   (i) Each question has four choices?

   (ii) The first four questions have three choices and the remaining have five choices?

   (iii) Question number \(n\) has \(n + 1\) choices?

6. A student appears in an objective test which contain 5 multiple choice questions. Each question has four choices out of which one correct answer.

   (i) What is the maximum number of different answers can the students give?

   (ii) How will the answer change if each question may have more than one correct answers?

7. How many strings can be formed from the letters of the word ARTICLE, so that vowels occupy the even places?

8. 8 women and 6 men are standing in a line.

   (i) How many arrangements are possible if any individual can stand in any position?

   (ii) In how many arrangements will all 6 men be standing next to one another?

   (iii) In how many arrangements will no two men be standing next to one another?

9. Find the distinct permutations of the letters of the word MISSISSIPPI.

10. How many ways can the product \(a^2 b^3 c^4\) be expressed without exponents?

11. In how many ways 4 mathematics books, 3 physics books, 2 chemistry books and 1 biology book can be arranged on a shelf so that all books of the same subjects are together.

12. In how many ways can the letters of the word SUCCESS be arranged so that all S's are together?

13. A coin is tossed 8 times,

    (i) How many different sequences of heads and tails are possible?

    (ii) How many different sequences containing six heads and two tails are possible?

14. How many strings are there using the letters of the word INTERMEDIATE, if

    (i) The vowels and consonants are alternative

    (ii) All the vowels are together

    (iii) Vowels are never together

    (iv) No two vowels are together.

15. Each of the digits 1, 1, 2, 3, 3 and 4 is written on a separate card. The six cards are then laid out in a row to form a 6-digit number.

    (i) How many distinct 6-digit numbers are there?

    (ii) How many of these 6-digit numbers are even?

    (iii) How many of these 6-digit numbers are divisible by 4?

16. If the letters of the word GARDEN are permuted in all possible ways and the strings thus formed are arranged in the dictionary order, then find the ranks of the words (i) GARDEN (ii) DANGER.

17. Find the number of strings that can be made using all letters of the word THING. If these words are written as in a dictionary, what will be the \(15^{th}\) string?

18. If the letters of the word FUNNY are permuted in all possible ways and the strings thus formed are arranged in the dictionary order, find the rank of the word FUNNY.

19. Find the sum of all 4-digit numbers that can be formed using digits 1, 2, 3, 4, and 5 repetitions not allowed.

20. Find the sum of all 4-digit numbers that can be formed using digits 0, 2, 5, 7, 8 without repetition.

## 4.5 Combinations

Let us suppose there are four persons \(A, B, C\) and \(D\) (actual names may be used here) and we have to select three of them to be a part of a committee. In how many ways can we make this selection? For example, \(A, B, C\) is one possible choice. Here the order of selection is immaterial. Thus \(A, B, C\) is the same as \(B, A, C\) or \(C, A, B\) as long as the same three persons are selected. Thus the possible distinct choices or selections are \(A, B, C; A, B, D; A, C, D\) and \(B, C, D\). We may thus conclude that there are 4 ways of selecting 3 people out of 4. Each choice or selection is referred to as a combination of 4 different objects taken 3 at a time.

Suppose two persons are to be selected from four persons. The possible choices are: \(A, B; A, C; A, D; B, C; B, D; C, D\). Thus the number of combinations of 4 different objects taken 2 at a time is 6. The number of combinations of \(n\) different objects taken \(r\) at a time is represented by \(^{n}C_{r}\). From the above we may conclude that \(^{4}C_{3} = 4\) and \(^{4}C_{2} = 6\). Now, \(^{4}C_{3}\) is the number of combinations of 4 objects taken 3 at a time. Note that in each combination, the three objects may be arranged in 3! ways. Thus the total number of permutations of 4 objects taken 3 at a time is \(^{4}C_{3} \times 3!\). This is also equal to \(^{4}P_{3}\). Hence \(^{4}P_{3} = ^{4}C_{3} \times 3!\).

In general, this leads to an important relationship between permutations and combinations as,

$$
^{n}P_{r} = ^{n}C_{r} \times r!.
$$

Normally for any reader there may be a confusion between permutation and combination. The following table with an example may be helpful in clearing the confusion.

| S.No | Description | Permutation | Combination |
|------|-------------|-------------|-------------|
| 1 | What is | Number of Arrangement or Listing of objects | Number of Selections or Grouping of objects |
| 2 | Where to use | If the ordering of objects matters | If the ordering of objects does not matter |
| 3 | Representation | \(^{n}P_{r}\) | \(^{n}C_{r}\) |
| **Examples** | | | |
| 4 | In a game of cricket | The number of batting line up of 11 players out of the 15 players | The number of teams consisting of 11 players out of 15 players |
| 5 | In a process of prize distribution | The number of ways of distributing 3 distinct prizes | The number of ways of distributing 3 identical prizes |
| 6 | In a committee formation | The number of ways of choosing a President and a Vice-President for a committee of 13 members | The number of ways of forming a committee of 2 persons from 13 members |
| 7 | In a process of choosing objects | The number of ways of choosing 3 out of 15 distinct objects one after another | The number of ways of choosing 3 out of 15 distinct objects simultaneously |

### Theorem 4.5

The number of combinations of \(n\) distinct objects taken \(r\) at a time is given by

$$
^{n}C_{r} = \frac{n!}{r!(n - r)!}, \quad 0 \leq r \leq n.
$$

### 4.5.1 Properties of Combinations

**Property 1:** (i) \(^{n}C_{0} = 1\), (ii) \(^{n}C_{n} = 1\), (iii) \(^{n}C_{r} = \frac{n(n - 1)(n - 2)\cdots(n - r + 1)}{r!}\).

**Proof.**

\[
\begin{aligned}
\text{(i)} \quad ^{n}C_{0} &= \frac{n!}{0!(n - 0)!} = 1. \\
\text{(ii)} \quad ^{n}C_{n} &= \frac{n!}{n!(n - n)!} = \frac{n!}{n!0!} = 1. \\
\text{(iii)} \quad ^{n}C_{r} &= \frac{n(n - 1)(n - 2)\cdots(n - (r - 1))}{r!} = \frac{n(n - 1)(n - 2)\cdots(n - r + 1)}{r!}.
\end{aligned}
\]

**Property 2:** \(^{n}C_{r} = ^{n}C_{n - r}\).

**Proof.** In view of,

\[
^{n}C_{n - r} = \frac{n!}{(n - r)!(n - (n - r))!} = \frac{n!}{(n - r)!r!} = ^{n}C_{r}.
\]

**Property 3:** If \(^{n}C_{x} = ^{n}C_{y}\) then either \(x = y\) or \(x + y = n\).

**Proof.** By the property 2 we have, \(^{n}C_{y} = ^{n}C_{n - y}\).

Therefore, \(^{n}C_{x} = ^{n}C_{y} = ^{n}C_{n - y}\) gives us \(x = y\) or \(x = n - y\) equivalently, \(x = y\) or \(x + y = n\).

**Property 4:** \(^{n}C_{r} + ^{n}C_{r-1} = ^{n+1}C_{r}\).

**Proof.** Using the expressions for the "combination" we have,

\[
\begin{aligned}
^{n}C_{r} + ^{n}C_{r-1} &= \frac{n!}{r!(n - r)!} + \frac{n!}{(r - 1)!(n - (r - 1))!} \\
&= \frac{n!}{r!\times (n - r)!} + \frac{n!}{(r - 1)!\times (n - r + 1)!} \\
&= \frac{n!}{r \cdot (r - 1)! \times (n - r)!} + \frac{n!}{(r - 1)!(n - r)!(n - r + 1)} \\
&= \frac{n!}{(r - 1)! \times (n - r)!} \times \left(\frac{1}{r} + \frac{1}{(n - r + 1)}\right) \\
&= \frac{n!}{(r - 1)! \times (n - r)!} \times \frac{(n - r + 1 + r)}{r(n - r + 1)} \\
&= \frac{n!}{(r - 1)! \times (n - r)!} \times \frac{(n + 1)}{r(n - r + 1)} \\
&= \frac{(n + 1)!}{r! \times (n + 1 - r)!} = ^{n+1}C_{r}.
\end{aligned}
\]

**Property 5:** \(^{n}C_{r} = \frac{n}{r} \times ^{(n-1)}C_{(r-1)}\).

**Proof.**

\[
\frac{n}{r} \times ^{(n-1)}C_{(r-1)} = \frac{n}{r} \cdot \frac{(n - 1)!}{(r - 1)! \times ((n - 1) - (r - 1))!} = \frac{n(n - 1)!}{r(r - 1)!(n - r)!} = ^{n}C_{r}.
\]

### Example 4.44

Evaluate the following: (i) \(^{10}C_{3}\) (ii) \(^{15}C_{13}\) (iii) \(^{100}C_{99}\) (iv) \(^{50}C_{50}\).

**Solution:**

\[
\begin{aligned}
\text{(i)} \quad ^{10}C_{3} &= \frac{10 \times 9 \times 8}{3 \times 2 \times 1} = 120. \\
\text{(ii)} \quad ^{15}C_{13} &= ^{15}C_{2} = \frac{15 \times 14}{2 \times 1} = 105. \\
\text{(iii)} \quad ^{100}C_{99} &= \frac{100 \times 99!}{99!} = 100. \\
\text{(iv)} \quad ^{50}C_{50} &= \frac{50!}{50! \times 0!} = 1.
\end{aligned}
\]

### Example 4.45

Find the value of \(^{5}C_{2}\) and \(^{7}C_{3}\) using the property 5.

**Solution:**

\(^{n}C_{r} = \frac{n}{r} \times ^{n-1}C_{r-1}\).

Substituting \(n = 5\) and \(r = 2\), we get

\[
^{5}C_{2} = \frac{5}{2} \times ^{4}C_{1} = \frac{5}{2} \times \frac{4}{1} = \frac{5 \times 4}{2 \times 1} = 10.
\]

Substituting \(n = 7\) and \(r = 3\), we get

\[
^{7}C_{3} = \frac{7}{3} \times ^{6}C_{2} = \frac{7}{3} \times \frac{6 \times 5}{2 \times 1} = \frac{7}{3} \times 15 = 35.
\]

### Example 4.46

If \(^{n}C_{4} = 495\), then find \(n\).

**Solution:**

We know that,

\[
^{n}C_{4} = 495.
\]

Therefore,

\[
\frac{n \times (n-1) \times (n-2) \times (n-3)}{4 \times 3 \times 2 \times 1} = 495
\]

\[
\Rightarrow n \times (n-1) \times (n-2) \times (n-3) = 495 \times 4 \times 3 \times 2 \times 1
\]

Factoring \(495 = 3 \times 3 \times 5 \times 11\), and writing this product as a product of 4 consecutive numbers in the descending order we get,

\[
n \times (n-1) \times (n-2) \times (n-3) = 12 \times 11 \times 10 \times 9.
\]

Equating \(n\) with the maximum number, we obtain \(n = 12\).

### Example 4.47

If \(^{n}P_{r} = 11880\) and \(^{n}C_{r} = 495\), Find \(n\) and \(r\).

**Solution:**

We know that,

\[
\frac{^{n}P_{r}}{^{n}C_{r}} = r!.
\]

Therefore,

\[
r! = \frac{11880}{495} = 24 = 4!,
\]

gives \(r = 4\). Using this \(r = 4\), in \(^{n}C_{4} = 495\), and applying the result of the Example (4.46) we get, \(n = 12\).

### Example 4.48

Prove that \(^{24}C_{4} + \sum_{r=0}^{4} {}^{(28-r)}C_{3} = ^{29}C_{4}\).

**Solution:**

\[
\begin{aligned}
^{24}C_{4} + \sum_{r=0}^{4} {}^{(28-r)}C_{3} &= ^{24}C_{4} + [^{28}C_{3} + ^{27}C_{3} + ^{26}C_{3} + ^{25}C_{3} + ^{24}C_{3}] \\
&= ^{24}C_{4} + ^{24}C_{3} + ^{25}C_{3} + ^{26}C_{3} + ^{27}C_{3} + ^{28}C_{3} \\
&= ^{25}C_{4} + ^{25}C_{3} + ^{26}C_{3} + ^{27}C_{3} + ^{28}C_{3} \\
&= ^{26}C_{4} + ^{26}C_{3} + ^{27}C_{3} + ^{28}C_{3} \\
&= ^{27}C_{4} + ^{27}C_{3} + ^{28}C_{3} \\
&= ^{28}C_{4} + ^{28}C_{3} \\
&= ^{29}C_{4}.
\end{aligned}
\]

### Example 4.49

Prove that \(^{10}C_{2} + 2 \times ^{10}C_{3} + ^{10}C_{4} = ^{12}C_{4}\).

**Solution:**

\[
\begin{aligned}
^{10}C_{2} + 2 \times ^{10}C_{3} + ^{10}C_{4} &= ^{10}C_{2} + (^{10}C_{3} + ^{10}C_{3}) + ^{10}C_{4} \\
&= (^{10}C_{2} + ^{10}C_{3}) + (^{10}C_{3} + ^{10}C_{4}) \\
&= ^{11}C_{3} + ^{11}C_{4} \\
&= ^{12}C_{4}.
\end{aligned}
\]

### Example 4.50

If \(^{n+2}C_{7} : ^{n-1}P_{4} = 13 : 24\) find \(n\).

**Solution:**

\[
\frac{^{n+2}C_{7}}{^{n-1}P_{4}} = \frac{13}{24}
\]

\[
\frac{\frac{(n+2)!}{7!(n-5)!}}{(n-1)(n-2)(n-3)(n-4)} = \frac{13}{24}
\]

\[
\frac{(n+2)(n+1)n(n-1)!}{7! (n-5)!} \times \frac{1}{(n-1)(n-2)(n-3)(n-4)} = \frac{13}{24}
\]

\[
\frac{(n+2)(n+1)n}{7!} \times \frac{(n-1)!}{(n-5)! (n-1)(n-2)(n-3)(n-4)} = \frac{13}{24}
\]

\[
\frac{(n+2)(n+1)n}{7!} \times \frac{1}{1} = \frac{13}{24}
\]

\[
\frac{(n+2)(n+1)n}{5040} = \frac{13}{24}
\]

\[
(n+2)(n+1)n = \frac{13}{24} \times 5040 = 13 \times 210 = 2730
\]

\[
(n+2)(n+1)n = 15 \times 14 \times 13
\]

\[
n + 2 = 15 \Rightarrow n = 13.
\]

### Example 4.51

A salad at a certain restaurant consists of 4 of the following fruits: apple, banana, guava, pomegranate, grapes, papaya and pineapple. Find the total possible number of fruit salads.

**Solution:**

There are seven fruits and we have to select four fruits for the fruit salad. Hence, the total number of possible ways of making a fruit salad is \(^{7}C_{4} = ^{7}C_{3} = 35\).

### Example 4.52

A Mathematics club has 15 members. In that 8 are girls. 6 of the members are to be selected for a competition and half of them should be girls. How many ways of these selections are possible?

**Solution:**

There are 8 girls and 7 boys in the mathematics club. The number of ways of selecting 6 members in that half of them girls (3 girls and 3 others) is \(^{8}C_{3} \times ^{7}C_{3} = 56 \times 35 = 1960\).

### Example 4.53

In rating 20 brands of cars, a car magazine picks up five best brands as a first, second, third, fourth and fifth and then 7 more as acceptable. In how many ways can it be done?

**Solution:**

The picking of 5 brands for a first, second, third, fourth and fifth best brand from 20 brands in \(^{20}P_{5}\) ways. From the remaining 15 we need to select 7 acceptable in \(^{15}C_{7}\) ways. By the rule of product it can be done in \(^{20}P_{5} \times ^{15}C_{7}\) ways.

### Example 4.54

From a class of 25 students, 10 students are to be chosen for an excursion party. There are 4 students who decide that either all of them will join or none of them will join. In how many ways can the excursion party be chosen?

**Solution:**

There are two possibilities:

(i) All the 4 students will go to the excursion party then, we need to select 6 students out of 21 students. It can be done in \(^{21}C_{6} = \frac{21!}{6! \times 15!}\) ways.

(ii) All the 4 students will not go to the excursion party then, we need to select 10 students out of 21 students. It can be done in \(^{21}C_{10} = \frac{21!}{10! \times 11!}\).

Hence, the total number of ways is \(^{21}C_{6} + ^{21}C_{10}\).

### Example 4.55

A box of one dozen apple contains a rotten apple. If we are choosing 3 apples simultaneously, in how many ways, one can get only good apples.

**Solution:**

The total number of ways of selecting 3 apples from 12 apples is \(^{12}C_{3} = 220\).

The total number of ways of getting a rotten apple when selecting 3 apples from 12 apples is equal to selecting 1 rotten apple and remaining 2 apples can be selected from 11 apples is \(^{11}C_{2} = 55\).

Therefore, the total number of ways of getting only good apples is

\[
^{12}C_{3} - ^{11}C_{2} = 220 - 55 = 165.
\]

### Example 4.56

An exam paper contains 8 questions, 4 in Part A and 4 in Part B. Examiners are required to answer 5 questions. In how many ways can this be done if

(i) There are no restrictions of choosing a number of questions in either parts.

(ii) At least two questions from Part A must be answered.

**Solution:**

(i) There are no restrictions. Totally there are 8 questions in both Part A and Part B. The total number of ways of attempting 5 questions from 8 questions is \(^{8}C_{5} = ^{8}C_{3} = 56\).

(ii) At least two questions from Part A needs to be answered. Accordingly, various choices are tabulated as follows.

| Part A | Part B | Number of selections |
|--------|--------|---------------------|
| 2 | 3 | \(^{4}C_{2} \times ^{4}C_{3} = 6 \times 4 = 24\) |
| 3 | 2 | \(^{4}C_{3} \times ^{4}C_{2} = 4 \times 6 = 24\) |
| 4 | 1 | \(^{4}C_{4} \times ^{4}C_{1} = 1 \times 4 = 4\) |

Therefore, the required number of ways of answering is \(24 + 24 + 4 = 52\).

### Example 4.57

Out of 7 consonants and 4 vowels, how many strings of 3 consonants and 2 vowels can be formed?

**Solution:**

Number of ways of selecting (3 consonants out of 7) and (2 vowels out of 4) is

\[
^{7}C_{3} \times ^{4}C_{2}.
\]

Each string contains 5 letters. Number of ways of arranging 5 letters among themselves is \(5! = 120\).

Hence required number of ways is,

\[
^{7}C_{3} \times ^{4}C_{2} \times 5! = 35 \times 6 \times 120 = 25200.
\]

### Example 4.58

Find the number of strings of 5 letters that can be formed with the letters of the word PROPOSITION.

**Solution:**

There are 11 letters in the word, with respect to number of repetitions of letters there are 4 distinct letters (R, S, T, N), 2 sets of two alike letters (PP, II), 1 set of three alike letters (OOO). The following table will illustrate the combination of these sets and the number of words.

| S.No | Letter Options | Selections | Arrangements |
|------|---------------|------------|--------------|
| 1 | 5 distinct (R, S, T, N, P, I, O) | \(^{7}C_{5}\) | \(^{7}C_{5} \times 5! = 2520\) |
| 2 | 1 set of 3 alike (OOO), 1 set of 2 alike (PP, II) | \(^{1}C_{1} \times ^{2}C_{1}\) | \(^{1}C_{1} \times ^{2}C_{1} \times \frac{5!}{3! \times 2!} = 20\) |
| 3 | 1 set of 3 alike (OOO), 2 distinct (R, S, T, N, P, I) | \(^{1}C_{1} \times ^{6}C_{2}\) | \(^{1}C_{1} \times ^{6}C_{2} \times \frac{5!}{3!} = 300\) |
| 4 | 2 sets of 2 alike (PP, II, OO), 1 distinct (R, S, T, N and remaining one in 2 alike) | \(^{3}C_{2} \times ^{5}C_{1}\) | \(^{3}C_{2} \times ^{5}C_{1} \times \frac{5!}{2! \times 2!} = 450\) |
| 5 | 1 set of 2 alike (PP, II, OO), 3 distinct (R, S, T, N and remaining two in 2 alike) | \(^{3}C_{1} \times ^{6}C_{3}\) | \(^{3}C_{1} \times ^{6}C_{3} \times \frac{5!}{2!} = 3600\) |

Hence, the total number of strings are \(2520 + 20 + 300 + 450 + 3600 = 6890\).

### Example 4.59

If a set of \(m\) parallel lines intersect another set of \(n\) parallel lines (not parallel to the lines in the first set), then find the number of parallelograms formed in this lattice structure.

**Solution:**

Whenever we select 2 lines from the first set of \(m\) lines and 2 lines from the second set of \(n\) lines, one parallelogram is formed. Thus the number of parallelograms formed is

$$
^{m}C_{2} \times ^{n}C_{2}.
$$

### Example 4.60

How many diagonals are there in a polygon with \(n\) sides?

**Solution:**

A polygon of \(n\) sides has \(n\) vertices. By joining any two vertices of a polygon, we obtain either a side or a diagonal of the polygon. Number of line segments obtained by joining the vertices of a \(n\) sided polygon taken two at a time is

$$
^{n}C_{2} = \frac{n(n - 1)}{2}.
$$

Out of these lines, there are \(n\) sides of polygon. Therefore, number of diagonals of the polygon is

$$
\frac{n(n - 1)}{2} - n = \frac{n(n - 3)}{2}.
$$

In particular for a pentagon and heptagon (Septagon), number of diagonals respectively are

$$
\frac{5(5 - 3)}{2} = 5 \quad \text{and} \quad \frac{7(7 - 3)}{2} = 14.
$$

## Exercise 4.3

1. If \(^{n}C_{12} = ^{n}C_{9}\) find \(^{21}C_{n}\).

2. If \(^{15}C_{2r-1} = ^{15}C_{2r+4}\), find \(r\).

3. If \(^{n}P_{r} = 720\), and \(^{n}C_{r} = 120\), find \(n, r\).

4. Prove that \(^{15}C_{3} + 2 \times ^{15}C_{4} + ^{15}C_{5} = ^{17}C_{5}\).

5. Prove that \(^{35}C_{5} + \sum_{r=0}^{4} {}^{(39-r)}C_{4} = ^{40}C_{5}\).

6. If \(^{n+1}C_{8} : ^{n-3}P_{4} = 57 : 16\), find the value of \(n\).

7. Prove that \(^{2n}C_{n} = \frac{2^{n} \times 1 \times 3 \times \cdots (2n - 1)}{n!}\).

8. Prove that if \(1 \leq r \leq n\) then \(n \times ^{n-1}C_{r-1} = (n - r + 1) \times ^{n}C_{r-1}\).

9. (i) A Kabaddi coach has 14 players ready to play. How many different teams of 7 players could the coach put on the court?

   (ii) There are 15 persons in a party and if each 2 of them shakes hands with each other, how many handshakes happen in the party?

   (iii) How many chords can be drawn through 20 points on a circle?

   (iv) In a parking lot one hundred, one year old cars, are parked. Out of them five are to be chosen at random for to check its pollution devices. How many different set of five cars can be chosen?

   (v) How many ways can a team of 3 boys, 2 girls and 1 transgender be selected from 5 boys, 4 girls and 2 transgenders?

10. Find the total number of subsets of a set with

    [Hint: \(^{n}C_{0} + ^{n}C_{1} + ^{n}C_{2} + \dots + ^{n}C_{n} = 2^{n}\)]

    (i) 4 elements

    (ii) 5 elements

    (iii) \(n\) elements.

11. A trust has 25 members.

    (i) How many ways 3 officers can be selected?

    (ii) In how many ways can a President, Vice President and a Secretary be selected?

12. How many ways a committee of six persons from 10 persons can be chosen along with a chair person and a secretary?

13. How many different selections of 5 books can be made from 12 different books if,

    (i) Two particular books are always selected?

    (ii) Two particular books are never selected?

14. There are 5 teachers and 20 students. Out of them a committee of 2 teachers and 3 students is to be formed. Find the number of ways in which this can be done. Further find in how many of these committees

    (i) a particular teacher is included?

    (ii) a particular student is excluded?

15. In an examination a student has to answer 5 questions, out of 9 questions in which 2 are compulsory. In how many ways a student can answer the questions?

16. Find the number of ways of forming a committee of 5 members out of 7 Indians and 5 Americans, so that always Indians will be the majority in the committee.

17. A committee of 7 peoples has to be formed from 8 men and 4 women. In how many ways can this be done when the committee consists of

    (i) exactly 3 women?

    (ii) at least 3 women?

    (iii) at most 3 women?

18. 7 relatives of a man comprises 4 ladies and 3 gentlemen, his wife also has 7 relatives; 3 of them are ladies and 4 gentlemen. In how many ways can they invite a dinner party of 3 ladies and 3 gentlemen so that there are 3 of man's relative and 3 of the wife's relatives?

19. A box contains two white balls, three black balls and four red balls. In how many ways can three balls be drawn from the box, if at least one black ball is to be included in the draw?

20. Find the number of strings of 4 letters that can be formed with the letters of the word EXAMINATION.

21. How many triangles can be formed by joining 15 points on the plane, in which no line joining any three points?

22. How many triangles can be formed by 15 points, in which 7 of them lie on one line and the remaining 8 on another parallel line?

23. There are 11 points in a plane. No three of these lies in the same straight line except 4 points, which are collinear. Find,

    (i) the number of straight lines that can be obtained from the pairs of these points?

    (ii) the number of triangles that can be formed for which the points are their vertices?

24. A polygon has 90 diagonals. Find the number of its sides.

## 4.6 Mathematical induction

Let us consider the sum of the first \(n\) positive odd numbers. These are \(1, 3, 5, 7, \dots, 2n-1\). The first odd number 1 which is equal to 1. The first two odd numbers are 1 and 3 and their sum is 4. Writing these as follows helps us to see a pattern.

\[
\begin{aligned}
1 &= 1 \\
1 + 3 &= 4 \\
1 + 3 + 5 &= 9 \\
1 + 3 + 5 + 7 &= 16 \\
1 + 3 + 5 + 7 + 9 &= 25
\end{aligned}
\]

We may conjecture that

$$
1 + 3 + 5 + \cdots + (2n-1) = n^2.
$$

However we have only made a conjecture. In order to prove the conjecture we shall use the Principle of Mathematical Induction. Mathematical Induction is a method or technique of proving mathematical results or theorems of the above kind. This technique relies upon making conjectures by observing all possible cases of a specific result. It is well suited for proving results in algebra or in other disciplines of mathematics where results or theorems are stated in terms of \(n\), \(n\) being a positive integer. The process of Mathematical Induction may be compared to that of climbing an infinite staircase.

In order to ensure that we complete the climb, it is sufficient to ensure the following.

(a) We can climb the first step.
(b) Once we have reached a particular step of the staircase, we can climb to the next step.

Being sure of (a) and (b) will enable us to climb all the steps in the staircase. Similarly, when we apply this method to prove a mathematical statement \(P(n)\), the process of induction involves the following steps.

**Figure 4.16**

**Step 1:** Verify that the statement is true for \(n = 1\), that is, verify that \(P(1)\) is true. This is akin to climbing the first step of the staircase and is referred to as the **initial step**.

**Step 2:** Verify that the statement is true for \(n = k + 1\) whenever it is true for \(n = k\), where \(k\) is a positive integer. This means that we need to prove that \(P(k + 1)\) is true whenever \(P(k)\) is true. This is referred to as the **inductive step**.

**Step 3:** If steps 1 and 2 have been established then the statement \(P(n)\) is true for all positive integers \(n\).

One of the interesting method of proof in Mathematics is by the Mathematical induction. We shall illustrate the method through problems. As an illustration of the process let us revisit a well known result through an example below:

### Example 4.61

By the principle of mathematical induction, prove that, for all integers \(n \geq 1\),

$$
1 + 2 + 3 + \dots + n = \frac{n(n + 1)}{2}.
$$

**Solution:**

Let,

$$
P(n) \coloneqq 1 + 2 + 3 + \dots + n = \frac{n(n + 1)}{2}.
$$

Substituting the value of \(n = 1\), in the statement we get, \(P(1) = \frac{1(1 + 1)}{2} = 1\). Hence, \(P(1)\) is true.

Let us assume that the statement is true for \(n = k\). Then

$$
P(k) = 1 + 2 + 3 + \dots + k = \frac{k(k + 1)}{2}.
$$

We need to show that \(P(k + 1)\) is true. Consider,

\[
\begin{aligned}
P(k + 1) &= \underbrace{1 + 2 + 3 + \dots + k}_{P(k)} + (k + 1) \\
&= \frac{k(k + 1)}{2} + (k + 1) \\
&= \frac{k(k + 1) + 2(k + 1)}{2} \\
&= \frac{(k + 1)(k + 2)}{2}.
\end{aligned}
\]

This implies, \(P(k + 1)\) is true. The validity of \(P(k + 1)\) follows from that of \(P(k)\). Therefore by the principle of mathematical induction, for all integers \(n \geq 1\),

$$
1 + 2 + 3 + \dots + n = \frac{n(n + 1)}{2}.
$$

### Example 4.62

Prove that the sum of first \(n\) positive odd numbers is \(n^2\).

**Solution:**

Let \(P(n) = 1 + 3 + 5 + \dots + (2n - 1)\). Therefore \(P(1) = 1 = 1^2\) is true.

We assume that \(P(k) = 1 + 3 + 5 + \ldots + (2k - 1)\) is true for \(n = k\). That is \(P(k) = k^2\).

We need to prove \(P(k + 1) = (k + 1)^2\).

\[
\begin{aligned}
P(k+1) &= 1 + 3 + 5 + \ldots + (2(k+1) - 1) \\
&= 1 + 3 + 5 + 7 + \ldots + (2k - 1) + (2k + 1) \\
&= P(k) + 2k + 1 \\
&= k^2 + 2k + 1 = (k + 1)^2.
\end{aligned}
\]

This implies, \(P(k + 1)\) is true. Hence, by the principle of mathematical induction, \(P(n)\) is true for all natural numbers.

### Example 4.63

By the principle of mathematical induction, prove that, for all integers \(n \geq 1\),

$$
1^2 + 2^2 + 3^2 + \dots + n^2 = \frac{n(n + 1)(2n + 1)}{6}.
$$

**Solution:**

Let,

$$
P(n) \coloneqq 1^2 + 2^2 + 3^2 + \dots + n^2 = \frac{n(n + 1)(2n + 1)}{6}.
$$

Substituting \(n = 1\) in the statement we get, \(P(1) = \frac{1(1 + 1)(2(1) + 1)}{6} = 1\). Hence, \(P(1)\) is true.

Let us assume that the statement is true for \(n = k\). Then

$$
P(k) = 1^2 + 2^2 + 3^2 + \dots + k^2 = \frac{k(k + 1)(2k + 1)}{6}.
$$

We need to show that \(P(k + 1)\) is true. Consider

\[
\begin{aligned}
P(k+1) &= 1^2 + 2^2 + 3^2 + \cdots + k^2 + (k+1)^2 \\
&= P(k) + (k+1)^2 \\
&= \frac{k(k+1)(2k+1)}{6} + (k+1)^2 \\
&= \frac{k(k+1)(2k+1) + 6(k+1)^2}{6} \\
&= \frac{(k+1)[k(2k+1) + 6(k+1)]}{6} \\
&= \frac{(k+1)[2k^2 + k + 6k + 6]}{6} \\
&= \frac{(k+1)(2k^2 + 7k + 6)}{6} \\
&= \frac{(k+1)[(k+2)(2k+3)]}{6} \\
&= \frac{(k+1)[((k+1)+1)(2(k+1)+1)]}{6}.
\end{aligned}
\]

That is,

$$
P(k + 1) = \frac{(k + 1)((k + 1) + 1)(2(k + 1) + 1)}{6}.
$$

This implies, \(P(k + 1)\) is true. The validity of \(P(k + 1)\) follows from that of \(P(k)\). Therefore by the principle of mathematical induction,

$$
1^2 + 2^2 + 3^2 + \dots + n^2 = \frac{n(n + 1)(2n + 1)}{6}, \text{ for all } n \geq 1.
$$

### Example 4.64

Using the Mathematical induction, show that for any natural number \(n\),

$$
\frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{n(n + 1)} = \frac{n}{n + 1}.
$$

**Solution:**

Let

$$
P(n) = \frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{n(n + 1)} = \frac{n}{n + 1}.
$$

Step 1: \(P(1) = \frac{1}{1 \cdot 2} = \frac{1}{2} = \frac{1}{1 + 1}\). So \(P(1)\) is true.

Step 2: Assume that \(P(k)\) is true for \(n = k\).

That is, \(P(k) = \frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{k(k + 1)} = \frac{k}{k + 1}\).

We shall now prove \(P(k + 1)\).

\[
\begin{aligned}
P(k+1) &= \frac{1}{1 \cdot 2} + \frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{k(k+1)} + \frac{1}{(k+1)(k+2)} \\
&= P(k) + \frac{1}{(k+1)(k+2)} \\
&= \frac{k}{k+1} + \frac{1}{(k+1)(k+2)} \\
&= \frac{k(k+2) + 1}{(k+1)(k+2)} = \frac{k^2 + 2k + 1}{(k+1)(k+2)} \\
&= \frac{(k+1)^2}{(k+1)(k+2)} = \frac{k+1}{k+2}.
\end{aligned}
\]

Hence \(P(k+1)\) is true. Therefore by the principle of mathematical induction, the statement \(P(n)\) is true for all natural numbers \(n\).

### Example 4.65

Prove that \(a^n - b^n\) is divisible by \(a - b\) for all natural numbers \(n\), where \(a > b\).

**Solution:**

Let \(P(n) \coloneqq a^n - b^n\) is divisible by \(a - b\).

For \(n = 1\), \(P(1) = a - b\) is divisible by \(a - b\). Hence \(P(1)\) is true.

Assume that \(P(k)\) is true for \(n = k\). That is, \(a^k - b^k\) is divisible by \(a - b\).

We need to prove that \(a^{k+1} - b^{k+1}\) is divisible by \(a - b\).

Consider,

\[
\begin{aligned}
a^{k+1} - b^{k+1} &= a^{k+1} - a^k b + a^k b - b^{k+1} \\
&= a^k(a - b) + b(a^k - b^k).
\end{aligned}
\]

Here \(a^k(a - b)\) is divisible by \(a - b\). Also by the induction hypothesis \(a^k - b^k\) is divisible by \(a - b\), so \(b(a^k - b^k)\) is divisible by \(a - b\). Hence their sum \(a^{k+1} - b^{k+1}\) is divisible by \(a - b\).

Thus \(P(k+1)\) is true whenever \(P(k)\) is true. Hence by the principle of mathematical induction, \(a^n - b^n\) is divisible by \(a - b\) for all natural numbers \(n\).

### Example 4.66

Prove that \(3^{2n+2} - 8n - 9\) is divisible by 8 for all \(n \geq 1\).

**Solution:**

Let \(P(n) \coloneqq 3^{2n+2} - 8n - 9\) is divisible by 8.

For \(n = 1\),

$$
P(1) = 3^{2+2} - 8(1) - 9 = 81 - 8 - 9 = 64,
$$

which is divisible by 8. Hence \(P(1)\) is true.

Assume that \(P(k)\) is true for \(n = k\). Then \(P(k) = 3^{2k+2} - 8k - 9\) is divisible by 8. We can write

$$
3^{2k+2} = 8m + 8k + 9
$$

for some integer \(m\).

We need to show that \(P(k+1) = 3^{2(k+1)+2} - 8(k+1) - 9\) is divisible by 8. Consider,

\[
\begin{aligned}
P(k+1) &= 3^{2k+4} - 8k - 8 - 9 \\
&= 9 \cdot 3^{2k+2} - 8k - 17 \\
&= 9(8m + 8k + 9) - 8k - 17 \\
&= 72m + 72k + 81 - 8k - 17 \\
&= 72m + 64k + 64 \\
&= 8(9m + 8k + 8),
\end{aligned}
\]

which is divisible by 8. This implies that \(P(k + 1)\) is true.

Therefore by the principle of mathematical induction, \(3^{2n+2} - 8n - 9\) is divisible by 8 for all \(n \geq 1\).

### Example 4.67

Using the Mathematical induction, show that for any integer \(n \geq 2\),

$$
3n^2 > (n + 1)^2.
$$

**Solution:**

Let \(P(n)\) be the statement that \(3n^2 > (n + 1)^2\) with \(n \geq 2\). Therefore the first stage is \(n = 2\).

Now, \(P(2) = 3 \times 2^2 = 12\) and \(3^2 = 9\). As \(12 > 9\) we get \(P(2)\) is true.

We assume that \(P(n)\) is true for \(n = k\). That is, \(3k^2 > (k + 1)^2\).

We need to prove \(P(k+1)\) i.e., \(3(k+1)^2 > (k+2)^2\).

\[
\begin{aligned}
3(k+1)^2 &= 3k^2 + 6k + 3 \\
&> (k+1)^2 + 6k + 3 \quad \text{(by induction hypothesis)}\\
&= k^2 + 2k + 1 + 6k + 3 \\
&= k^2 + 8k + 4 \\
&= (k^2 + 4k + 4) + 4k \\
&= (k+2)^2 + 4k \\
&> (k+2)^2 \quad \text{since } k > 0.
\end{aligned}
\]

Thus \(P(k+1)\) is true. Therefore by the principle of mathematical induction, for all \(n \geq 2\), \(3n^2 > (n+1)^2\).

### Example 4.68

Using the Mathematical induction, show that for any integer \(n \geq 2\),

$$
3^n > n^2.
$$

**Solution:**

Let \(P(n)\) be the statement that \(3^n > n^2\) with \(n \geq 2\). Therefore the first stage is \(n = 2\).

Now, \(P(2) = 3^2 = 9\) and \(2^2 = 4\). As \(9 > 4\), we get \(P(2)\) is true.

We assume that \(P(n)\) is true for \(n = k\). That is \(3^k > k^2\).

Now,

\[
\begin{aligned}
P(k+1) &= 3^{k+1} = 3 \times 3^k > 3 \times k^2 \quad \text{(by induction hypothesis)} \\
&> (k+1)^2 \quad \text{by Example 4.67}.
\end{aligned}
\]

Hence, for any integer \(n \geq 2\), \(3^n > n^2\).

### Example 4.69

By the principle of mathematical induction, prove that, for \(n \in \mathbb{N}\),

$$
\cos \alpha + \cos (\alpha + \beta) + \cos (\alpha + 2\beta) + \dots + \cos (\alpha + (n-1)\beta) = \cos \left(\alpha + \frac{(n-1)\beta}{2}\right) \times \frac{\sin\left(\frac{n\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)}.
$$

**Solution:**

Let \(P(n) \coloneqq \cos \alpha + \cos (\alpha + \beta) + \cos (\alpha + 2\beta) + \dots + \cos (\alpha + (n-1)\beta)\).

Then,

$$
P(1) = \cos \alpha = \frac{\cos \alpha \cdot \sin\left(\frac{\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)},
$$

which shows \(P(1)\) is true.

We now assume that \(P(n)\) is true for \(n = k\). That is,

$$
\cos \alpha + \cos (\alpha + \beta) + \cos (\alpha + 2\beta) + \dots + \cos (\alpha + (k-1)\beta) = \cos \left(\alpha + \frac{(k-1)\beta}{2}\right) \times \frac{\sin\left(\frac{k\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)}.
$$

We need to prove \(P(k+1)\) is true. Now,

\[
P(k+1) = \underbrace{\cos \alpha + \cos (\alpha + \beta) + \dots + \cos (\alpha + (k-1)\beta)}_{P(k)} + \cos (\alpha + k\beta).
\]

Then,

\[
\begin{aligned}
P(k+1) &= \cos \left(\alpha + \frac{(k-1)\beta}{2}\right) \frac{\sin\left(\frac{k\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)} + \cos(\alpha + k\beta) \\
&= \frac{1}{\sin\left(\frac{\beta}{2}\right)} \left[ \cos \left(\alpha + \frac{(k-1)\beta}{2}\right) \sin\left(\frac{k\beta}{2}\right) + \cos(\alpha + k\beta) \sin\left(\frac{\beta}{2}\right) \right].
\end{aligned}
\]

After simplification using trigonometric identities, we get

$$
P(k+1) = \cos \left(\alpha + \frac{k\beta}{2}\right) \times \frac{\sin\left(\frac{(k+1)\beta}{2}\right)}{\sin\left(\frac{\beta}{2}\right)}.
$$

Thus \(P(k+1)\) is true. Hence by the principle of mathematical induction, the statement holds for all natural numbers \(n\).

### Example 4.70

Using the Mathematical induction, show that for any natural number \(n\), with the assumption \(i^2 = -1\),

$$
(r(\cos \theta + i \sin \theta))^n = r^n (\cos n\theta + i \sin n\theta).
$$

**Solution:**

Let

$$
P(n) = (r(\cos \theta + i \sin \theta))^n = r^n (\cos n\theta + i \sin n\theta).
$$

For \(n = 1\),

$$
P(1) = (r(\cos \theta + i \sin \theta))^1 = r(\cos \theta + i \sin \theta).
$$

Hence, \(P(1)\) is true.

Assume that \(P(k)\) is true for \(n = k\). Then

$$
(r(\cos \theta + i \sin \theta))^k = r^k (\cos k\theta + i \sin k\theta).
$$

We need to show that \(P(k+1)\) is true. Consider,

\[
\begin{aligned}
P(k+1) &= (r(\cos \theta + i \sin \theta))^{k+1} \\
&= (r(\cos \theta + i \sin \theta))^k \times r(\cos \theta + i \sin \theta) \\
&= r^k (\cos k\theta + i \sin k\theta) \times r(\cos \theta + i \sin \theta) \\
&= r^{k+1} \times \left[ (\cos k\theta \cos \theta + i^2 \sin k\theta \sin \theta) + i(\sin k\theta \cos \theta + \cos k\theta \sin \theta) \right] \\
&= r^{k+1} \times \left[ (\cos k\theta \cos \theta - \sin k\theta \sin \theta) + i(\sin k\theta \cos \theta + \cos k\theta \sin \theta) \right] \\
&= r^{k+1} \times (\cos (k+1)\theta + i \sin (k+1)\theta).
\end{aligned}
\]

This implies that \(P(k+1)\) is true. Therefore by the principle of mathematical induction, for any natural number \(n\),

$$
(r(\cos \theta + i \sin \theta))^n = r^n (\cos n\theta + i \sin n\theta).
$$

What we have proved in Example 4.70 is called the **Demoivre's theorem** for natural numbers, which will be studied in detail in the second year of Higher Secondary course.

## Exercise 4.4

1. By the principle of mathematical induction, prove that, for \(n \geq 1\)

   $$
   1^3 + 2^3 + 3^3 + \dots + n^3 = \left(\frac{n(n+1)}{2}\right)^2.
   $$

2. By the principle of mathematical induction, prove that, for \(n \geq 1\)

   $$
   1^2 + 3^2 + 5^2 + \dots + (2n-1)^2 = \frac{n(2n-1)(2n+1)}{3}.
   $$

3. Prove that the sum of the first \(n\) non-zero even numbers is \(n^2 + n\).

4. By the principle of Mathematical induction, prove that, for \(n \geq 1\)

   $$
   1 \cdot 2 + 2 \cdot 3 + 3 \cdot 4 + \dots + n \cdot (n+1) = \frac{n(n+1)(n+2)}{3}.
   $$

5. Using the Mathematical induction, show that for any natural number \(n \geq 2\)

   $$
   \left(1 - \frac{1}{2^2}\right)\left(1 - \frac{1}{3^2}\right)\left(1 - \frac{1}{4^2}\right) \dots \left(1 - \frac{1}{n^2}\right) = \frac{n+1}{2n}.
   $$

6. Using the Mathematical induction, show that for any natural number \(n \geq 2\)

   $$
   \frac{1}{1+2} + \frac{1}{1+2+3} + \frac{1}{1+2+3+4} + \dots + \frac{1}{1+2+3+\dots+n} = \frac{n-1}{n+1}.
   $$

7. Using the Mathematical induction, show that for any natural number \(n\)

   $$
   \frac{1}{1 \cdot 2 \cdot 3} + \frac{1}{2 \cdot 3 \cdot 4} + \frac{1}{3 \cdot 4 \cdot 5} + \dots + \frac{1}{n(n+1)(n+2)} = \frac{n(n+3)}{4(n+1)(n+2)}.
   $$

8. Using the Mathematical induction, show that for any natural number \(n\)

   $$
   \frac{1}{2 \cdot 5} + \frac{1}{5 \cdot 8} + \frac{1}{8 \cdot 11} + \dots + \frac{1}{(3n-1)(3n+2)} = \frac{n}{6n+4}.
   $$

9. Prove by Mathematical Induction that

   $$
   1! + (2 \times 2!) + (3 \times 3!) + \dots + (n \times n!) = (n+1)! - 1.
   $$

10. Using the Mathematical induction, show that for any natural number \(n\), \(x^{2n} - y^{2n}\) is divisible by \(x + y\).

11. By the principle of Mathematical induction, prove that, for \(n \geq 1\)

    $$
    1^2 + 2^2 + 3^2 + \dots + n^2 > \frac{n^3}{3}.
    $$

12. Use induction to prove that \(n^3 - 7n + 3\) is divisible by 3, for all natural numbers \(n\).

13. Use induction to prove that \(5^{n+1} + 4 \times 6^n\) when divided by 20 leaves a remainder 9, for all natural numbers \(n\).

14. Use induction to prove that \(10^n + 3 \times 4^{n+2} + 5\) is divisible by 9, for all natural numbers \(n\).

15. Prove that using the Mathematical induction

    $$
    \sin \alpha + \sin \left(\alpha + \frac{\pi}{6}\right) + \sin \left(\alpha + \frac{2\pi}{6}\right) + \dots + \sin \left(\alpha + \frac{(n-1)\pi}{6}\right) = \frac{\sin\left(\alpha + \frac{(n-1)\pi}{12}\right) \times \sin\left(\frac{n\pi}{12}\right)}{\sin\left(\frac{\pi}{12}\right)}.
    $$

## Exercise 4.5

### Choose the correct or the most suitable answer

1. The sum of the digits at the \(10^{th}\) place of all numbers formed with the help of 2, 4, 5, 7 taken all at a time is

   (1) 432

   (2) 108

   (3) 36

   (4) 18

2. In an examination there are three multiple choice questions and each question has 5 choices. Number of ways in which a student can fail to get all answer correct is

   (1) 125

   (2) 124

   (3) 64

   (4) 63

3. The number of ways in which the following prize be given to a class of 30 boys first and second in mathematics, first and second in physics, first in chemistry and first in English is

   (1) \(30^4 \times 29^2\)

   (2) \(30^3 \times 29^3\)

   (3) \(30^2 \times 29^4\)

   (4) \(30 \times 29^5\)

4. The number of 5 digit numbers all digits of which are odd is

   (1) 25

   (2) \(5^5\)

   (3) \(5^6\)

   (4) 625

5. In 3 fingers, the number of ways four rings can be worn is

   (1) \(4^3 - 1\)

   (2) \(3^4\)

   (3) 68

   (4) 64

6. If \(^{n+5}P_{(n+1)} = \left(\frac{11(n-1)}{2}\right) \times ^{n+3}P_{n}\), then the value of \(n\) are

   (1) 7 and 11

   (2) 6 and 7

   (3) 2 and 11

   (4) 2 and 6

7. The product of \(r\) consecutive positive integers is divisible by

   (1) \(r!\)

   (2) \((r-1)!\)

   (3) \((r+1)!\)

   (4) \(r^r\)

8. The number of five digit telephone numbers having at least one of their digits repeated is

   (1) 90000

   (2) 10000

   (3) 30240

   (4) 69760

9. If \(^{a^2-a}C_{2} = ^{a^2-a}C_{4}\) then the value of \(a\) is

   (1) 2

   (2) 3

   (3) 4

   (4) 5

10. There are 10 points in a plane and 4 of them are collinear. The number of straight lines joining any two points is

    (1) 45

    (2) 40

    (3) 39

    (4) 38

11. The number of ways in which a host lady invite 8 people for a party of 8 out of 12 people of whom two do not want to attend the party together is

    (1) \(2 \times ^{11}C_{7} + ^{10}C_{8}\)

    (2) \(^{11}C_{7} + ^{10}C_{8}\)

    (3) \(^{12}C_{8} - ^{10}C_{6}\)

    (4) \(^{10}C_{6} + 2!\)

12. The number of parallelograms that can be formed from a set of four parallel lines intersecting another set of three parallel lines.

    (1) 6

    (2) 9

    (3) 12

    (4) 18

13. Everybody in a room shakes hands with everybody else. The total number of shake hands is 66. The number of persons in the room is

    (1) 11

    (2) 12

    (3) 10

    (4) 6

14. Number of sides of a polygon having 44 diagonals is

    (1) 4

    (2) 4!

    (3) 11

    (4) 22

15. If 10 lines are drawn in a plane such that no two of them are parallel and no three are concurrent, then the total number of points of intersection are

    (1) 45

    (2) 40

    (3) 10!

    (4) 20

16. In a plane there are 10 points are there out of which 4 points are collinear, then the number of triangles formed is

    (1) 110

    (2) \(^{10}C_{3}\)

    (3) 120

    (4) 116

17. If \(^{2n}C_{3} : ^{n}C_{3} = 11 : 1\) then \(n\) is

    (1) 5

    (2) 6

    (3) 11

    (4) 7

18. \(^{n-1}C_{r} + ^{n-1}C_{r-1}\) is

    (1) \(^{n+1}C_{r}\)

    (2) \(^{n-1}C_{r}\)

    (3) \(^{n}C_{r}\)

    (4) \(^{n}C_{r-1}\)

19. The number of rectangles in a chessboard is

    (1) 81

    (2) 9

    (3) 1296

    (4) 6561

20. The number of 10 digit number that can be written by using the digits 2 and 3 is

    (1) \(^{10}C_{2} + ^{9}C_{2}\)

    (2) \(2^{10}\)

    (3) \(2^{10} - 2\)

    (4) 10!

21. If \(P_{r}\) stands for \(^{r}P_{r}\) then the sum of the series \(1 + P_{1} + 2P_{2} + 3P_{3} + \dots + nP_{n}\) is

    (1) \(P_{n+1}\)

    (2) \(P_{n+1} - 1\)

    (3) \(P_{n-1} + 1\)

    (4) \((n+1)P_{(n-1)}\)

22. The product of first \(n\) odd natural numbers equals

    (1) \(^{2n}C_{n} \times ^{n}P_{n}\)

    (2) \(\left(\frac{1}{2}\right)^n \times ^{2n}C_{n} \times ^{n}P_{n}\)

    (3) \(\left(\frac{1}{4}\right)^n \times ^{2n}C_{n} \times ^{2n}P_{n}\)

    (4) \(^{n}C_{n} \times ^{n}P_{n}\)

23. If \(^{n}C_{4}, ^{n}C_{5}, ^{n}C_{6}\) are in AP the value of \(n\) can be

    (1) 14

    (2) 11

    (3) 9

    (4) 5

24. \(1 + 3 + 5 + 7 + \dots + 17\) is equal to

    (1) 101

    (2) 81

    (3) 71

    (4) 61

## Summary

In this chapter, we acquired the knowledge of

- Factorial of a natural number \(n\) is the product of the first \(n\) natural numbers.

- \(n! = n(n - 1)!\), for any integer \(n \geq 1\).

- The number of ways of arranging \(n\) unlike objects is \(n!\).

- The number of distinct permutations of \(r\) objects which can be made from \(n\) distinct objects is

  $$
  ^{n}P_{r} = \frac{n!}{(n - r)!} = n(n - 1)(n - 2)\dots(n - r + 1).
  $$

- The number of permutations of \(n\) objects taken all at a time where \(p_1\) objects one of first kind, \(p_2\) objects one of second kind, \(\dots p_k\) objects one of the \(k^{th}\) kind and the rest, if any are all different and is given by

  $$
  \frac{n!}{p_1! p_2! \dots p_k!}.
  $$

- Order matters for a permutation whereas order does not matter for a combination.

- The number of combinations of \(n\) different objects taken \(r\) at a time denoted by \(^{n}C_{r}\) is given by

  $$
  ^{n}C_{r} = \frac{n!}{r!(n - r)!} = \frac{n(n - 1)(n - 2)\dots(n - r + 1)}{r!}.
  $$
