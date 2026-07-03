---
title: 'introduction to probability theory'
weight: 12
summary: "This chapter introduces the fundamental concepts of probability, which measures the likelihood of occurrence of events in random experiments, and covers basic terminology such as trial, outcome, sample space, and event. It discusses classical, empirical, and axiomatic approaches to probability, along with important rules such as the addition theorem for mutually exclusive and non-mutually exclusive events, and the multiplication theorem for independent and dependent events. The chapter also covers conditional probability, Bayes' theorem, and provides a foundation for understanding random variables and probability distributions, which are essential for statistical analysis and decision-making."
---

# Chapter 12: Introduction to Probability Theory

## 12.1 Introduction

The most important questions of life are, indeed, for the most part, really only problems of probability – Pierre-Simon Laplace

A gambler's dispute in 1654 led to the creation of a mathematical theory of probability by two famous French mathematicians, Blaise Pascal and Pierre de Fermat. The fundamental principles of probability theory were formulated by Pascal and Fermat for the first time. After an extensive research, Laplace published his monumental work in 1812, and laid the foundation to Probability theory. In statistics, the Bayesian interpretation of probability was developed mainly by Laplace.

The topic of probability is seen in many facets of the modern world. From its origin as a method of studying games, probability has involved in a powerful and widely applicable branch of mathematics. The uses of probability range from the determination of life insurance premium, to the prediction of election outcomes, the description of the behaviour of molecules in a gas. Its utility is one good reason why the study of probability has found in the way into a school textbook. The interpretation of the word 'probability' involves synonyms such as chance, possible, probably, likely, odds, uncertainty, prevalence, risk, expectancy etc.

Our entire world is filled with uncertainty. We make decisions affected by uncertainty virtually every day. In order to measure uncertainty, we turn to a branch of mathematics called theory of probability. Probability is a measure of the likeliness that an event will occur.

## Learning Objectives

On completion of this chapter, the students are expected to

- understand the classical theory of probability and axiomatic approach to probability.
- understand mutually exclusive, mutually inclusive and exhaustive events.
- understand the concepts of conditional probability and independent events.
- apply Bayes' theorem.
- apply probability theory in day-to-day life.

## 12.2 Basic definitions

Before we study the theory of probability, let us recollect the definition of certain terms already studied in earlier classes, which are frequently used.

**Definition 12.1**

An experiment is defined as a process for which its result is well defined.

**Definition 12.2**

Deterministic experiment is an experiment whose outcomes can be predicted with certain, under ideal conditions.

**Definition 12.3**

A random experiment (or non-deterministic) is an experiment

(i) whose all possible outcomes are known in advance,

(ii) whose each outcome is not possible to predict in advance, and

(iii) can be repeated under identical conditions.

A die is 'rolled', a fair coin is 'tossed' are examples for random experiments.

**Definition 12.4**

A simple event (or elementary event or sample point) is the most basic possible outcome of a random experiment and it cannot be decomposed further.

**Definition 12.5**

A sample space is the set of all possible outcomes of a random experiment. Each point in sample space is an elementary event.

### Illustration 12.1

(1) (i) If a die is rolled, then the sample space \( S = \{1, 2, 3, 4, 5, 6\} \).

(ii) A coin is tossed, then the sample space \( S = \{H, T\} \).

(2) (i) Suppose we toss a coin until a head is obtained. One cannot say in advance how many tosses will be required, and so the sample space
\[
S = \{H, TH, TTH, TTTH, \dots\}
\]
is an infinite set.

(ii) The sample space associated with the number of passengers waiting to buy train tickets in counters is \( S = \{0, 1, 2, \dots\} \).

(3) (i) If the experiment consists of choosing a number randomly between 0 and 1, then the sample space is \( S = \{x : 0 < x < 1\} \).

(ii) The sample space for the life length (t in hours) of a tube light is \( S = \{t : 0 < t < 1000\} \).

From (2) and (3), one need to distinguish between two types of infinite sets, where one type is significantly larger than the other. In particular, \( S \) in (2) is called countably infinite, while the \( S \) in (3) is called uncountably infinite. The fact that one can list the elements of a countably infinite set means that the set can be put in one-to-one correspondence with natural numbers \( \mathbb{N} \). On the other hand, you cannot list the elements in uncountable set.

From the above example, one can understand that the sample space may consist of countable or uncountable number of elementary events.

## 12.3 Finite sample space

In this section we restrict our sample spaces that have at most a finite number of points.

### Types of events

Let us now define some of the important types of events, which are used frequently in this chapter.

- Sure event or certain event
- Impossible event
- Complementary event
- Mutually exclusive events
- Mutually inclusive event
- Exhaustive events
- Equally likely events
- Independent events (defined after learning the concepts of probability)

**Definition 12.6**

When the sample space is finite, any subset of the sample space is an event. That is, all elements of the power set \( \mathcal{P}(S) \) of the sample space are defined as events. An event is a collection of sample points or elementary events.

The sample space \( S \) is called sure event or certain event. The null set \( \emptyset \) in \( S \) is called an impossible event.

**Definition 12.7**

For every event \( A \), there corresponds another event \( \overline{A} \) is called the complementary event to \( A \). It is also called the event 'not \( A \)'.

### Illustration 12.2

Suppose a sample space \( S \) is given by \( S = \{1, 2, 3, 4\} \).

Let the set of all possible subsets of \( S \) (the power set of \( S \)) be \( \mathcal{P}(S) \).

\[
\mathcal{P}(S) = \{\emptyset, \{1\}, \{2\}, \{3\}, \{4\}, \{1,2\}, \{1,3\}, \{1,4\}, \{2,3\}, \{2,4\}, \{3,4\},
\]
\[
\{1,2,3\}, \{1,2,4\}, \{1,3,4\}, \{2,3,4\}, \{1,2,3,4\}\}.
\]

1. All the elements of \( \mathcal{P}(S) \) are events.
2. \( \emptyset \) is an impossible event.
3. \( \{1\}, \{2\}, \{3\}, \{4\} \) are the simple events or elementary events.
4. \( \{1,2,3,4\} \) is a sure event or certain event.

**Definition 12.8**

Two events cannot occur simultaneously are mutually exclusive events. \( A_1, A_2, A_3, \ldots, A_k \) are mutually exclusive means that, \( A_i \cap A_j = \emptyset \), for \( i \neq j \).

**Definition 12.9**

Two events are mutually inclusive when they can both occur simultaneously.

\( A_1, A_2, A_3, \ldots, A_k \) are mutually inclusive means that, \( A_i \cap A_j \neq \emptyset \), for \( i \neq j \).

### Illustration 12.3

When we roll a die, the sample space \( S = \{1, 2, 3, 4, 5, 6\} \).

(i) Since \( \{1,3\} \cap \{2,4,5,6\} = \emptyset \), the events \( \{1,3\} \) and \( \{2,4,5,6\} \) are mutually exclusive events.

(ii) The events \( \{1,6\}, \{2,3,5\} \) are mutually exclusive.

(iii) The events \( \{2,3,5\}, \{5,6\} \) are mutually inclusive, since \( \{2,3,5\} \cap \{5,6\} = \{5\} \neq \emptyset \).

**Definition 12.10**

\( A_1, A_2, A_3, \ldots, A_k \) are called exhaustive events if, \( A_1 \cup A_2 \cup A_3 \cup \dots \cup A_k = S \).

**Definition 12.11**

\( A_1, A_2, A_3, \ldots, A_k \) are called mutually exclusive and exhaustive events if,

(i) \( A_i \cap A_j = \emptyset \), for \( i \neq j \)

(ii) \( A_1 \cup A_2 \cup A_3 \cup \dots \cup A_k = S \)

### Illustration 12.4

When a die is rolled, sample space \( S = \{1,2,3,4,5,6\} \).

Some of the events are \( \{2,3\}, \{1,3,5\}, \{4,6\}, \{6\} \) and \( \{1,5\} \).

(i) Since \( \{2,3\} \cup \{1,3,5\} \cup \{4,6\} = \{1,2,3,4,5,6\} = S \) (sample space), the events \( \{2,3\}, \{1,3,5\}, \{4,6\} \) are exhaustive events.

(ii) Similarly \( \{2,3\}, \{4,6\} \) and \( \{1,5\} \) are also exhaustive events.

(iii) \( \{1,3,5\}, \{4,6\}, \{6\} \) and \( \{1,5\} \) are not exhaustive events. (Since \( \{1,3,5\} \cup \{4,6\} \cup \{6\} \cup \{1,5\} \neq S \))

(iv) \( \{2,3\}, \{4,6\} \) and \( \{1,5\} \) are mutually exclusive and exhaustive events, since
\[
\{2,3\} \cap \{4,6\} = \emptyset, \{2,3\} \cap \{1,5\} = \emptyset, \{4,6\} \cap \{1,5\} = \emptyset
\]
and
\[
\{2,3\} \cup \{4,6\} \cup \{1,5\} = S.
\]

Types of events associated with sample space are easy to visualize in terms of Venn diagrams.

**Definition 12.12**

The events having the same chance of occurrences are called equally likely events.

Example for equally likely events: Suppose a fair die is rolled.

Example for not equally likely events: A colour die is shown in figure is rolled.

Similarly, suppose if we toss a coin, the events of getting a head or a tail are equally likely.

### Methods to find sample space

#### Illustration 12.5

Two coins are tossed, the sample space is

(i) \( S = \{H, T\} \times \{H, T\} = \{(H,H), (H,T), (T,H), (T,T)\} \) or \( \{HH, HT, TH, TT\} \)

(ii) If a coin is tossed and a die is rolled simultaneously, then the sample space is
\[
S = \{H, T\} \times \{1,2,3,4,5,6\}
\]
\[
= \{H1, H2, H3, H4, H5, H6, T1, T2, T3, T4, T5, T6\}
\]
or
\[
S = \{(H,1), (H,2), (H,3), (H,4), (H,5), (H,6), (T,1), (T,2), (T,3), (T,4), (T,5), (T,6)\}.
\]

Also one can interchange the order of outcomes of coin and die. The following table gives the sample spaces for some random experiments.

| Random Experiment | Total Number of Outcomes | Sample space |
|-------------------|--------------------------|--------------|
| Tossing a fair coin | \( 2^1 = 2 \) | \( \{H, T\} \) |
| Tossing two coins | \( 2^2 = 4 \) | \( \{HH, HT, TH, TT\} \) |
| Tossing three coins | \( 2^3 = 8 \) | \( \{HHH, HHT, HTH, THH, HTT, THT, TTH, TTT\} \) |
| Rolling fair die | \( 6^1 = 6 \) | \( \{1, 2, 3, 4, 5, 6\} \) |
| Rolling Two dice or single die two times | \( 6^2 = 36 \) | \{(1,1), (1,2), (1,3), (1,4), (1,5), (1,6), (2,1), (2,2), (2,3), (2,4), (2,5), (2,6), (3,1), (3,2), (3,3), (3,4), (3,5), (3,6), (4,1), (4,2), (4,3), (4,4), (4,5), (4,6), (5,1), (5,2), (5,3), (5,4), (5,5), (5,6), (6,1), (6,2), (6,3), (6,4), (6,5), (6,6)\} |

### Notations

Let \( A \) and \( B \) be two events.

(i) \( A \cup B \) stands for the occurrence of \( A \) or \( B \) or both.

(ii) \( A \cap B \) stands for the simultaneous occurrence of \( A \) and \( B \). \( A \cap B \) can also be written as \( AB \).

(iii) \( \overline{A} \) or \( A' \) or \( A^c \) stands for non-occurrence of \( A \).

(iv) \( (A \cap \overline{B}) \) stands for the occurrence of only \( A \).

## 12.4 Probability

### 12.4.1 Classical definition (A priori) of probability (Bernoulli's principle of equally likely)

Earlier classes we have studied the frequency (A posteriori) definition of probability and the problems were solved. Now let us learn the fundamentals of the axiomatic approach to probability theory.

The basic assumption of underlying the classical theory is that the outcomes of a random experiment are equally likely. If there are \( n \) exhaustive, mutually exclusive and equally likely outcomes of an experiment and \( m \) of them are favorable to an event \( A \), then the mathematical probability of \( A \) is defined as the ratio \( \frac{m}{n} \). In other words, \( P(A) = \frac{m}{n} \).

**Definition 12.13**

Let \( S \) be the sample space associated with a random experiment and \( A \) be an event. Let \( n(S) \) and \( n(A) \) be the number of elements of \( S \) and \( A \) respectively. Then the probability of the event \( A \) is defined as

\[
P(A) = \frac{n(A)}{n(S)} = \frac{\text{Number of cases favourable to } A}{\text{Exhaustive number of cases in } S}.
\]

Every probabilistic model involves an underlying process.

The classical definition of probability is limited in its application only to situations where there are a finite number of possible outcomes. It mainly considered discrete events and its methods were mainly combinatorial. This renders it inapplicable to some important random experiments, such as tossing a coin until a head appears' which give rise to the possibility of infinite set of outcomes. Another limitation of the classical definition was the condition that each possible outcome is 'equally likely'.

These types of limitations in the classical definition of probability led to the evolution of the modern definition of probability which is based on the concept of sets. It is known an axiomatic approach.

The foundations of the Modern Probability theory were laid by Andrey Nikolayevich Kolmogorov, a Russian mathematician who combined the notion of sample space introduced by Richard von Mises, and measure theory and presented his axiomatic system for probability theory in 1933. We introduce the axiomatic approach proposed by A.N. Kolmogorov. Based on this, it is possible to construct a logically perfect structure of the modern theory of probability theory. The classical theory of probability is a particular case of axiomatic probability. The axioms are a set of rules, which can be used to prove theorems of probability.

### 12.4.2 Axiomatic approach to Probability

#### Axioms of probability

Let \( S \) be a finite sample space, let \( \mathcal{P}(S) \) be the class of events, and let \( P \) be a real valued function defined on \( \mathcal{P}(S) \). Then \( P(A) \) is called probability function of the event \( A \), when the following axioms are hold:

[P1] For any event \( A \), \( P(A) \geq 0 \) (Non-negativity axiom)

[P2] For any two mutually exclusive events, \( P(A \cup B) = P(A) + P(B) \) (Additivity axiom)

[P3] For the certain event, \( P(S) = 1 \) (Normalization axiom)

**Note 12.1**

(i) \( 0 \leq P(A) \leq 1 \)

(ii) If \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive events in a sample space \( S \), then
\[
P(A_1 \cup A_2 \cup A_3 \cup \dots \cup A_n) = P(A_1) + P(A_2) + P(A_3) + \dots + P(A_n).
\]

#### Theorems on finite probability spaces (without proof)

When the outcomes are equally likely Theorem 12.1 is applicable, else Theorem 12.2 is applicable.

**Theorem 12.1**

Let \( S \) be a sample space and for any subset \( A \) of \( S \), let \( P(A) = \frac{n(A)}{n(S)} \). Then \( P(A) \) satisfies axioms of probability [P1], [P2], and [P3].

**Theorem 12.2**

Let \( S \) be a finite sample space say \( S = \{a_1, a_2, a_3, \dots, a_n\} \). A finite probability space is obtained by assigning to each point \( a_i \) in \( S \) a real number \( p_i \), is called the probability of \( a_i \), satisfying the following properties:

(i) Each \( p_i \geq 0 \).

(ii) The sum of the \( p_i \) is 1, that is, \( \sum p_i = p_1 + p_2 + p_3 + \dots + p_n = 1 \).

If the probability \( P(A) \), of an event \( A \) is defined as the sum of the probabilities of the points in \( A \), then the function \( P(A) \) satisfies the axioms of probability [P1], [P2], and [P3].

Note: Sometimes the points in a finite sample space and their assigned probabilities are given in the form of a table as follows:

| Outcome | \( a_1 \) | \( a_2 \) | \( a_3 \) | ... | \( a_n \) |
|---------|----------|----------|----------|-----|-----------|
| Probability | \( p_1 \) | \( p_2 \) | \( p_3 \) | ... | \( p_n \) |

Here is an illustration of how to construct a probability law starting from some common sense assumptions about a model.

#### Illustration 12.6

(1) Let \( S = \{1,2,3\} \). Suppose \( \mathcal{P}(S) \) is the power set of \( S \), and \( P(A) = \frac{n(A)}{n(S)} \).

Then \( P(\{1\}) = \frac{1}{3} \), \( P(\{2\}) = \frac{1}{3} \), and \( P(\{3\}) = \frac{1}{3} \), satisfies axioms of probability [P1], [P2], and [P3]. Here all the outcomes are equally likely.

(2) Let \( S = \{1,2,3\} \). Suppose \( \mathcal{P}(S) \) is the power set of \( S \).

If the probability \( P(A) \), of an event \( A \) of \( S \) is defined as the sum of the probabilities of the points in \( A \),

then \( P(\{1\}) = \frac{1}{2} \), \( P(\{2\}) = \frac{1}{4} \), \( P(\{3\}) = \frac{1}{4} \), satisfy the axioms of probability [P1], [P2], and [P3].

(3) Let \( S = \{1,2,3\} \) and \( \mathcal{P}(S) \) is the power set of \( S \). If the probability \( P(A) \), of an event \( A \) of \( S \) is defined as the sum of the probabilities of the points in \( A \),

then \( P(\{1\}) = 0 \), \( P(\{2\}) = \frac{1}{\sqrt{2}} \), and \( P(\{3\}) = 1 - \frac{1}{\sqrt{2}} \), satisfy the above axioms [P1], [P2], and [P3].

In (2) and (3), the outcomes are not equally likely.

**Note 12.2**

Irrational numbers also can act as probabilities.

**Classroom Activity:** Each student to flip a coin 10 times,

Calculate: \( p = \frac{\text{Number of times heads occur}}{10} \)

Find the cumulative ratio of heads to tosses. As number of tosses increases \( p \rightarrow \frac{1}{2} \).

### Example 12.1

If an experiment has exactly the three possible mutually exclusive outcomes \( A, B \), and \( C \), check in each case whether the assignment of probability is permissible.

(i) \( P(A) = \frac{4}{7} \), \( P(B) = \frac{1}{7} \), \( P(C) = \frac{2}{7} \).

(ii) \( P(A) = \frac{2}{5} \), \( P(B) = \frac{1}{5} \), \( P(C) = \frac{3}{5} \).

(iii) \( P(A) = 0.3 \), \( P(B) = 0.9 \), \( P(C) = -0.2 \).

(iv) \( P(A) = \frac{1}{\sqrt{3}} \), \( P(B) = 1 - \frac{1}{\sqrt{3}} \), \( P(C) = 0 \).

(v) \( P(A) = 0.421 \), \( P(B) = 0.527 \), \( P(C) = 0.042 \).

**Solution**

Since the experiment has exactly the three possible mutually exclusive outcomes \( A \), \( B \) and \( C \), they must be exhaustive events.

\[
\Rightarrow S = A \cup B \cup C
\]

Therefore, by axioms of probability

\[
P(A) \geq 0, \quad P(B) \geq 0, \quad P(C) \geq 0
\]
and
\[
P(A \cup B \cup C) = P(A) + P(B) + P(C) = P(S) = 1.
\]

(i) Given that \( P(A) = \frac{4}{7} \geq 0 \), \( P(B) = \frac{1}{7} \geq 0 \) and \( P(C) = \frac{2}{7} \geq 0 \)

Also \( P(S) = P(A) + P(B) + P(C) = \frac{4}{7} + \frac{1}{7} + \frac{2}{7} = 1 \)

Therefore the assignment of probability is permissible.

(ii) Given that \( P(A) = \frac{2}{5} \geq 0 \), \( P(B) = \frac{1}{5} \geq 0 \) and \( P(C) = \frac{3}{5} \geq 0 \)

But \( P(S) = P(A) + P(B) + P(C) = \frac{2}{5} + \frac{1}{5} + \frac{3}{5} = \frac{6}{5} > 1 \)

Therefore the assignment is not permissible.

(iii) Since \( P(C) = -0.2 \) is negative, the assignment is not permissible.

(iv) The assignment is permissible because
\[
P(A) = \frac{1}{\sqrt{3}} \geq 0, \quad P(B) = 1 - \frac{1}{\sqrt{3}} \geq 0, \quad \text{and} \quad P(C) = 0 \geq 0
\]
\[
P(S) = P(A) + P(B) + P(C) = \frac{1}{\sqrt{3}} + 1 - \frac{1}{\sqrt{3}} + 0 = 1.
\]

(v) Even though \( P(A) = 0.421 \geq 0 \), \( P(B) = 0.527 \geq 0 \) and \( P(C) = 0.042 \geq 0 \), the sum of the probability
\[
P(S) = P(A) + P(B) + P(C) = 0.421 + 0.527 + 0.042 = 0.990 < 1.
\]

Therefore, the assignment is not permissible.

### Example 12.2

An integer is chosen at random from the first ten positive integers. Find the probability that it is (i) an even number (ii) multiple of three.

**Solution**

The sample space is
\[
S = \{1,2,3,4,5,6,7,8,9,10\}, \quad n(S) = 10.
\]

Let \( A \) be the event of choosing an even number and \( B \) be the event of choosing an integer multiple of three.

\[
A = \{2,4,6,8,10\}, \quad n(A) = 5,
\]
\[
B = \{3,6,9\}, \quad n(B) = 3.
\]

\[
P(\text{choosing an even integer}) = P(A) = \frac{n(A)}{n(S)} = \frac{5}{10} = \frac{1}{2}.
\]

\[
P(\text{choosing an integer multiple of three}) = P(B) = \frac{n(B)}{n(S)} = \frac{3}{10}.
\]

### Example 12.3

Three coins are tossed simultaneously, what is the probability of getting (i) exactly one head (ii) at least one head (iii) at most one head?

**Solution**

Notice that three coins are tossed simultaneously \( = \) one coin is tossed three times.

\[
S = \{HHH, HHT, HTH, THH, HTT, THT, TTH, TTT\}, \quad n(S) = 8.
\]

Let \( A \) be the event of getting exactly one head, \( B \) be the event of getting at least one head and \( C \) be the event of getting at most one head.

\[
A = \{HTT, THT, TTH\}; \quad n(A) = 3
\]
\[
B = \{HTT, THT, TTH, HHT, HTH, THH, HHH\}; \quad n(B) = 7
\]
\[
C = \{TTT, HTT, THT, TTH\}; \quad n(C) = 4.
\]

Therefore the required probabilities are
\[
P(A) = \frac{n(A)}{n(S)} = \frac{3}{8}, \quad
P(B) = \frac{n(B)}{n(S)} = \frac{7}{8}, \quad
P(C) = \frac{n(C)}{n(S)} = \frac{4}{8} = \frac{1}{2}.
\]

**Note 12.3**

When the number of elements in a sample space is considerably small we can solve by finger-counting the elements in the events. But when the number of elements is too large to count then combinatorics helps us to solve the problems.

For the following problem, combinatorics is used to find the number of elements in the sample space and the events.

### Example 12.4

Suppose ten coins are tossed. Find the probability to get (i) exactly two heads (ii) at most two heads (iii) at least two heads.

**Solution**

Ten coins are tossed simultaneously one time \( = \) one coin is tossed 10 times.

Let \( S \) the sample space. That is
\[
S = \{H,T\} \times \{H,T\} \times \{H,T\} \times \dots \times \{H,T\} \quad \text{(10 times)}.
\]

Let \( A \) be the event of getting exactly two heads, \( B \) be the event of getting at most two heads, and \( C \) be the event of getting at least two heads.

When ten coins are tossed, the number of elements in sample space is \( 2^n = 2^{10} = 1024 \).

\[
n(S) = 1024
\]
\[
n(A) = {}^{10}C_2 = 45
\]
\[
n(B) = {}^{10}C_0 + {}^{10}C_1 + {}^{10}C_2 = 1 + 10 + 45 = 56
\]
\[
n(C) = {}^{10}C_2 + {}^{10}C_3 + {}^{10}C_4 + \dots + {}^{10}C_{10} = n(S) - ({}^{10}C_0 + {}^{10}C_1) = 1024 - 11 = 1013
\]

The required probabilities are
(i) \( P(A) = \frac{n(A)}{n(S)} = \frac{45}{1024} \)
(ii) \( P(B) = \frac{n(B)}{n(S)} = \frac{56}{1024} = \frac{7}{128} \)
(iii) \( P(C) = \frac{n(C)}{n(S)} = \frac{1013}{1024} \).

### Example 12.5

Suppose a fair die is rolled. Find the probability of getting (i) an even number (ii) multiple of three.

**Solution**

Let \( S \) be the sample space, \( A \) be the event of getting an even number, \( B \) be the event of getting multiple of three.

Therefore,
\[
S = \{1,2,3,4,5,6\}, \quad n(S) = 6
\]
\[
A = \{2,4,6\}, \quad n(A) = 3
\]
\[
B = \{3,6\}, \quad n(B) = 2.
\]

The required probabilities are
\[
P(\text{getting an even number}) = P(A) = \frac{n(A)}{n(S)} = \frac{3}{6} = \frac{1}{2}
\]
\[
P(\text{getting multiple of three}) = P(B) = \frac{n(B)}{n(S)} = \frac{2}{6} = \frac{1}{3}.
\]

### Example 12.6

When a pair of fair dice is rolled, what are the probabilities of getting the sum (i) 7 (ii) 7 or 9 (iii) 7 or 12?

**Solution**

The sample space \( S = \{1,2,3,4,5,6\} \times \{1,2,3,4,5,6\} \)

Number of possible outcomes \( = 6^2 = 36 = n(S) \).

Let \( A \) be the event of getting sum 7, \( B \) be the event of getting sum 9 and \( C \) be the event of getting sum 12. Then
\[
A = \{(1,6), (2,5), (3,4), (4,3), (5,2), (6,1)\} \Rightarrow n(A) = 6
\]
\[
B = \{(3,6), (4,5), (5,4), (6,3)\} \Rightarrow n(B) = 4
\]
\[
C = \{(6,6)\} \Rightarrow n(C) = 1.
\]

\[
P(\text{getting sum } 7) = P(A) = \frac{n(A)}{n(S)} = \frac{6}{36} = \frac{1}{6}
\]

\[
P(\text{getting sum } 7 \text{ or } 9) = P(A \text{ or } B) = P(A \cup B) = P(A) + P(B) \quad (\text{Since } A \text{ and } B \text{ are mutually exclusive})
\]
\[
= \frac{n(A)}{n(S)} + \frac{n(B)}{n(S)} = \frac{6}{36} + \frac{4}{36} = \frac{5}{18}
\]

\[
P(\text{getting sum } 7 \text{ or } 12) = P(A \text{ or } C) = P(A \cup C) = P(A) + P(C) \quad (\text{since } A \text{ and } C \text{ are mutually exclusive})
\]
\[
= \frac{n(A)}{n(S)} + \frac{n(C)}{n(S)} = \frac{6}{36} + \frac{1}{36} = \frac{7}{36}.
\]

### Example 12.7

Three candidates \( X, Y, \) and \( Z \) are going to play in a chess competition to win FIDE (World Chess Federation) cup this year. \( X \) is thrice as likely to win as \( Y \) and \( Y \) is twice as likely as to win \( Z \). Find the respective probability of \( X, Y \) and \( Z \) to win the cup.

**Solution**

Let \( A, B, C \) be the event of winning FIDE cup respectively by \( X, Y, \) and \( Z \) this year.

Given that \( X \) is thrice as likely to win as \( Y \). \( A : B :: 3 : 1 \) ... (1)

\( Y \) is twice as likely as to win \( Z \). \( B : C :: 2 : 1 \) ... (2)

From (1) and (2) \( A : B : C :: 6 : 2 : 1 \)

\( A = 6k \), \( B = 2k \), \( C = k \), where \( k \) is proportional constant.

Probability to win the cup by \( X \) is
\[
P(A) = \frac{6k}{9k} = \frac{2}{3}
\]

Probability to win the cup by \( Y \) is
\[
P(B) = \frac{2k}{9k} = \frac{2}{9}
\]

Probability to win the cup by \( Z \) is
\[
P(C) = \frac{k}{9k} = \frac{1}{9}.
\]

### Example 12.8

Three letters are written to three different persons and addresses on three envelopes are also written. Without looking at the addresses, what is the probability that (i) exactly one letter goes to the right envelopes (ii) none of the letters go into the right envelopes?

**Solution**

Let \( A, B \) and \( C \) denote the envelopes and 1, 2, and 3 denote the corresponding letters.

The different combination of letters put into the envelopes are shown in the table.

Outcomes: \( c_1, c_2, c_3, c_4, c_5, c_6 \)

\[
S = \{c_1, c_2, c_3, c_4, c_5, c_6\}, \quad n(S) = 6
\]

Let \( X \) be the event of putting the letters into the exactly only one right envelopes.
Let \( Y \) be the event of putting none of the letters into the right envelope.

\[
X = \{c_2, c_3, c_6\}, \quad n(X) = 3
\]
\[
Y = \{c_4, c_5\}, \quad n(Y) = 2
\]

\[
P(X) = \frac{3}{6} = \frac{1}{2}, \quad P(Y) = \frac{2}{6} = \frac{1}{3}.
\]

### Example 12.9

Let the matrix \( M = \begin{bmatrix} x & y \\ z & 1 \end{bmatrix} \). If \( x, y \) and \( z \) are chosen at random from the set \( \{1,2,3\} \), and repetition is allowed (i.e., \( x = y = z \)), what is the probability that the given matrix \( M \) is a singular matrix?

**Solution**

If the given matrix \( M \) is singular, then
\[
\begin{vmatrix} x & y \\ z & 1 \end{vmatrix} = 0 \quad \Rightarrow \quad x - yz = 0.
\]

Hence the possible ways of selecting \( (x, y, z) \) are
\[
\{(1,1,1), (2,1,2), (2,2,1), (3,1,3), (3,3,1)\} = A \text{ (say)}.
\]

The number of favourable cases \( n(A) = 5 \).

The total number of cases are \( n(S) = 3^3 = 27 \).

The probability that the given matrix is a singular matrix is
\[
p = \frac{n(A)}{n(S)} = \frac{5}{27}.
\]

### Example 12.10

For a sports meet, a winners' stand comprising of three wooden blocks is in the form as shown in figure. There are six different colours available to choose from and three of the wooden blocks is to be painted such that no two of them has the same colour. Find the probability that the smallest block is to be painted in red, where red is one of the six colours.

**Solution**

Let \( S \) be the sample space and \( A \) be the event that the smallest block is to be painted in red.

\[
n(S) = {}^6P_3 = 6 \times 5 \times 4 = 120
\]
\[
n(A) = 5 \times 4 = 20
\]
\[
P(A) = \frac{n(A)}{n(S)} = \frac{20}{120} = \frac{1}{6}.
\]

### 12.4.3 ODDS

The word odds is frequently used in probability and statistics. Odds relate the chances in favour of an event \( A \) to the chances against it. Suppose '\( a \)' represents the number of ways that an event can occur and '\( b \)' represents the number of ways that the event can fail to occur.

The odds of an event \( A \) are \( a : b \) in favour of an event and
\[
P(A) = \frac{a}{a + b}.
\]

Further, it may be noted that the odds are \( a : b \) in favour of an event is the same as to say that the odds are \( b : a \) against the event.

If the probability of an event is \( p \), then the odds in favour of its occurrence are \( p \) to \( (1 - p) \) and the odds against its occurrence are \( (1 - p) \) to \( p \).

#### Illustration 12.7

(i) Suppose a die is rolled.

Let \( S \) be the sample space and \( A \) be the event of getting 5.
\[
n(S) = 6, \quad n(A) = 1 \text{ and } n(\overline{A}) = 5.
\]

It can also be interpreted as
Odds in favour of \( A \) is \( 1:5 \) or \( \frac{1}{5} \), odds against \( A \) is \( 5:1 \) or \( \frac{5}{1} \), and
\[
P(A) = \frac{n(A)}{n(A) + n(\overline{A})} = \frac{1}{1 + 5} = \frac{1}{6} = \frac{n(A)}{n(S)}.
\]

(ii) Suppose \( B \) is an event such that odds in favour of \( B \) is \( 3:5 \), then \( P(B) = \frac{3}{8} \).

(iii) Suppose \( C \) is an event such that odds against \( C \) is \( 4:11 \), then \( P(C) = \frac{11}{15} \).

### Example 12.11

A man keeps 2 ten rupee notes, 4 hundred rupee notes and 6 five hundred rupee notes in his box. If 2 notes are taken at random, what are the odds in favour of both notes being of hundred rupee denomination and also its probability?

**Solution**

Let \( S \) be the sample space and \( A \) be the event of taking 2 hundred rupee note.

Therefore,
\[
n(S) = {}^{12}C_2 = 66, \quad n(A) = {}^{4}C_2 = 6, \quad n(\overline{A}) = 66 - 6 = 60.
\]

Therefore, odds in favour of \( A \) is \( 6:60 \).

That is, odds in favour of \( A \) is \( 1:10 \), and \( P(A) = \frac{1}{11} \).

## EXERCISE 12.1

(1) An experiment has the four possible mutually exclusive and exhaustive outcomes \( A, B, C \), and \( D \). Check whether the following assignments of probability are permissible.
\[
\text{(i)} \quad P(A) = 0.15, P(B) = 0.30, P(C) = 0.43, P(D) = 0.12
\]
\[
\text{(ii)} \quad P(A) = 0.22, P(B) = 0.38, P(C) = 0.16, P(D) = 0.34
\]
\[
\text{(iii)} \quad P(A) = \frac{2}{5}, P(B) = \frac{3}{5}, P(C) = -\frac{1}{5}, P(D) = \frac{1}{5}
\]

(2) If two coins are tossed simultaneously, then find the probability of getting
(i) one head and one tail
(ii) at most two tails

(3) Five mangoes and 4 apples are in a box. If two fruits are chosen at random, find the probability that
(i) one is a mango and the other is an apple
(ii) both are of the same variety.

(4) What is the chance that (i) non-leap year (ii) leap year should have fifty three Sundays?

(5) Eight coins are tossed once, find the probability of getting
(i) exactly two tails
(ii) at least two tails
(iii) at most two tails

(6) An integer is chosen at random from the first 100 positive integers. What is the probability that the integer chosen is a prime or multiple of 8?

(7) A bag contains 7 red and 4 black balls, 3 balls are drawn at random. Find the probability that
(i) all are red
(ii) one red and 2 black.

(8) A cricket club has 16 members, of whom only 5 can bowl. What is the probability that in a team of 11 members at least 3 bowlers are selected?

(9) (i) The odds that the event \( A \) occurs is 5 to 7, find \( P(A) \).
(ii) Suppose \( P(B) = \frac{2}{5} \). Express the odds that the event \( B \) occurs.

## 12.5 Some basic Theorems on Probability

The problems solved in the last sections are related to mutually exclusive events. So we have used the formula \( P(A \text{ or } B) = P(A \cup B) = P(A) + P(B) \). But when the events are mutually inclusive, the additivity axioms counts \( (A \cap B) \) twice. We have a separate formula for the events when they are mutually inclusive.

In the development of probability theory, all the results are derived directly or indirectly using only the axioms of probability. Here we derive some of the basic important theorems on probability.

**Theorem 12.3**

The probability of the impossible event is zero. That is,
\[
\boxed{P(\emptyset) = 0}
\]

**Proof**

Impossible event contains no sample point.
\[
S \cup \emptyset = S
\]
\[
P(S \cup \emptyset) = P(S)
\]
\[
P(S) + P(\emptyset) = P(S)
\]
\[
P(\emptyset) = 0
\]

### Example 12.12

Find the probability of getting the number 7, when a usual die is rolled.

**Solution**

The event of getting 7 is an impossible event. Therefore, \( P(\text{getting } 7) = 0 \).

**Theorem 12.4**

If \( \overline{A} \) is the complementary event of \( A \), then
\[
\boxed{P(\overline{A}) = 1 - P(A)}
\]

**Proof**

Let \( S \) be a sample space, we have
\[
A \cup \overline{A} = S
\]
\[
P(A \cup \overline{A}) = P(S)
\]
\( P(A) + P(\overline{A}) = P(S) \) (since \( A \) and \( \overline{A} \) are mutually exclusive) \( = 1 \)
\[
P(\overline{A}) = 1 - P(A) \quad \text{or} \quad P(A) = 1 - P(\overline{A}).
\]

### Example 12.13

Nine coins are tossed once, find the probability to get at least two heads.

**Solution**

Let \( S \) be the sample space and \( A \) be the event of getting at least two heads.

Therefore, the event \( \overline{A} \) denotes, getting at most one head.

\[
n(S) = 2^9 = 512, \quad n(\overline{A}) = {}^9C_0 + {}^9C_1 = 1 + 9 = 10
\]
\[
P(\overline{A}) = \frac{10}{512} = \frac{5}{256}
\]
\[
P(A) = 1 - P(\overline{A}) = 1 - \frac{5}{256} = \frac{251}{256}.
\]

**Theorem 12.5**

If \( A \) and \( B \) are any two events and \( \overline{B} \) is the complementary events of \( B \), then
\[
\boxed{P(A \cap \overline{B}) = P(A) - P(A \cap B)}
\]

**Proof**

Clearly from the figure,
\[
(A \cap \overline{B}) \cup (A \cap B) = A
\]
\[
P\big[(A \cap \overline{B}) \cup (A \cap B)\big] = P(A)
\]
\[
P(A \cap \overline{B}) + P(A \cap B) = P(A)
\]
(since \( (A \cap \overline{B}) \) and \( (A \cap B) \) are mutually exclusive)
\[
P(A \cap \overline{B}) = P(A) - P(A \cap B).
\]

**Theorem 12.6**

If \( A \) and \( B \) are any two events, then
\[
\boxed{P(A \cup B) = P(A) + P(B) - P(A \cap B)}
\]

**Proof**

From the diagram,
\[
A \cup B = (A \cap \overline{B}) \cup B
\]
\[
P(A \cup B) = P\big[(A \cap \overline{B}) \cup B\big]
\]
(since \( (A \cap \overline{B}) \) and \( B \) are mutually exclusive)
\[
= [P(A) - P(A \cap B)] + P(B)
\]
Therefore,
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B).
\]

**Note 12.4**

The above theorem can be extended to any 3 events.

(i) \( P(A \cup B \cup C) = \{P(A) + P(B) + P(C)\} - \{P(A \cap B) + P(B \cap C) + P(C \cap A)\} + P(A \cap B \cap C) \)

(ii) \( P(A \cup B \cup C) = 1 - P(\overline{A \cup B \cup C}) = 1 - P(\overline{A} \cap \overline{B} \cap \overline{C}) \)

### Example 12.14

Given that \( P(A) = 0.52 \), \( P(B) = 0.43 \), and \( P(A \cap B) = 0.24 \), find
(i) \( P(A \cap \overline{B}) \)
(ii) \( P(A \cup B) \)
(iii) \( P(\overline{A} \cap \overline{B}) \)
(iv) \( P(\overline{A} \cup \overline{B}) \)

**Solution**

\[
P(A \cap \overline{B}) = P(A) - P(A \cap B) = 0.52 - 0.24 = 0.28
\]
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B) = 0.52 + 0.43 - 0.24 = 0.71
\]
\[
P(\overline{A} \cap \overline{B}) = P(\overline{A \cup B}) \quad (\text{By de Morgan's law}) = 1 - P(A \cup B) = 1 - 0.71 = 0.29
\]
\[
P(\overline{A} \cup \overline{B}) = P(\overline{A \cap B}) \quad (\text{By de Morgan's law}) = 1 - P(A \cap B) = 1 - 0.24 = 0.76.
\]

### Example 12.15

The probability that a girl, preparing for competitive examination will get a State Government service is 0.12, the probability that she will get a Central Government job is 0.25, and the probability that she will get both is 0.07. Find the probability that (i) she will get at least one of the two jobs (ii) she will get only one of the two jobs.

**Solution**

Let \( I \) be the event of getting State Government service and \( C \) be the event of getting Central Government job.

Given that
\[
P(I) = 0.12, \quad P(C) = 0.25, \quad P(I \cap C) = 0.07
\]

\[
P(\text{at least one of the two jobs}) = P(I \text{ or } C) = P(I \cup C)
\]
\[
= P(I) + P(C) - P(I \cap C) = 0.12 + 0.25 - 0.07 = 0.30
\]

\[
P(\text{only one of the two jobs}) = P[\text{only } I \text{ or only } C]
\]
\[
= P(I \cap \overline{C}) + P(\overline{I} \cap C)
\]
\[
= [P(I) - P(I \cap C)] + [P(C) - P(I \cap C)]
\]
\[
= (0.12 - 0.07) + (0.25 - 0.07) = 0.05 + 0.18 = 0.23.
\]

## EXERCISE 12.2

(1) If \( A \) and \( B \) are mutually exclusive events \( P(A) = \frac{3}{8} \) and \( P(B) = \frac{1}{8} \), then find
(i) \( P(\overline{A}) \)
(ii) \( P(A \cup B) \)
(iii) \( P(\overline{A} \cap B) \)
(iv) \( P(\overline{A} \cup \overline{B}) \)

(2) If \( A \) and \( B \) are two events associated with a random experiment for which
\[
P(A) = 0.35, \quad P(A \text{ or } B) = 0.85, \quad \text{and} \quad P(A \text{ and } B) = 0.15.
\]
Find (i) \( P(\text{only } B) \)
(ii) \( P(\overline{B}) \)
(iii) \( P(\text{only } A) \)

(3) A die is thrown twice. Let \( A \) be the event, "First die shows \( 5 \)" and \( B \) be the event, "second die shows \( 5 \)". Find \( P(A \cup B) \).

(4) The probability of an event \( A \) occurring is 0.5 and \( B \) occurring is 0.3. If \( A \) and \( B \) are mutually exclusive events, then find the probability of
(i) \( P(A \cup B) \)
(ii) \( P(A \cap \overline{B}) \)
(iii) \( P(\overline{A} \cap B) \).

(5) A town has 2 fire engines operating independently. The probability that a fire engine is available when needed is 0.96.
(i) What is the probability that a fire engine is available when needed?
(ii) What is the probability that neither is available when needed?

(6) The probability that a new railway bridge will get an award for its design is 0.48, the probability that it will get an award for the efficient use of materials is 0.36, and that it will get both awards is 0.2. What is the probability, that
(i) it will get at least one of the two awards
(ii) it will get only one of the awards.

## 12.6 Conditional Probability

In some situations, we may have to find the probability of an event when we already know that some other event happened before that event. For instance, what is the probability that a student is admitted to a professional course given that she has passed the entrance examination? The probability of occurrence of an event \( B \) when it is known that some event \( A \) has already happened is called conditional probability and is denoted by \( P(B / A) \). The symbol \( P(B / A) \) is usually read as the probability that \( B \) occurs given that \( A \) occurs or simply the probability of \( B \) given \( A \).

**Definition 12.14**

If \( A \) and \( B \) are two events, then the conditional probability of \( B \) given \( A \) is denoted by \( P(B / A) \) and is defined, when \( P(A) > 0 \), as
\[
\boxed{P(B / A) = \frac{P(A \cap B)}{P(A)}}.
\]

Similarly,
\[
\boxed{P(A / B) = \frac{P(A \cap B)}{P(B)}}, \quad \text{provided } P(B) > 0.
\]

### Example 12.16

Given that \( P(A) = 0.6 \), \( P(B) = 0.5 \), and \( P(A \cap B) = 0.2 \), find \( P(A / B) \), \( P(\overline{A} / B) \), and \( P(A / \overline{B}) \).

**Solution**

Given that \( P(A) = 0.6 \), \( P(B) = 0.5 \), and \( P(A \cap B) = 0.2 \).

\[
P(A / B) = \frac{P(A \cap B)}{P(B)} = \frac{0.2}{0.5} = \frac{2}{5}
\]
\[
P(\overline{A} / B) = \frac{P(\overline{A} \cap B)}{P(B)} = \frac{P(B) - P(A \cap B)}{P(B)} = \frac{0.5 - 0.2}{0.5} = \frac{0.3}{0.5} = \frac{3}{5}
\]
\[
P(A / \overline{B}) = \frac{P(A \cap \overline{B})}{P(\overline{B})} = \frac{P(A) - P(A \cap B)}{1 - P(B)} = \frac{0.6 - 0.2}{1 - 0.5} = \frac{0.4}{0.5} = \frac{4}{5}.
\]

**Note 12.5**

\[
P(A / B) + P(\overline{A} / B) = 1.
\]

### Example 12.17

A die is rolled. If it shows an odd number, then find the probability of getting 5.

**Solution**

Sample space \( S = \{1,2,3,4,5,6\} \).

Let \( A \) be the event of die shows an odd number. Let \( B \) be the event of getting 5.

Then,
\[
A = \{1,3,5\}, \quad B = \{5\}, \quad \text{and} \quad A \cap B = \{5\}.
\]

Therefore,
\[
P(A) = \frac{3}{6} \quad \text{and} \quad P(A \cap B) = \frac{1}{6}.
\]

\( P(\text{getting } 5 / \text{die shows an odd number}) = P(B / A) \)
\[
= \frac{P(A \cap B)}{P(A)} = \frac{\frac{1}{6}}{\frac{3}{6}} = \frac{1}{3}.
\]

### Theorem 12.7 (Multiplication theorem on probability)

The probability of the simultaneous happening of two events \( A \) and \( B \) is given by
\[
\boxed{P(A \cap B) = P(A / B) P(B) \quad \text{or} \quad P(A \cap B) = P(B / A) P(A)}.
\]

### 12.6.1 Independent Events

Events are said to be independent if occurrence or non-occurrence of any one of the event does not affect the probability of occurrence or non-occurrence of the other events.

**Definition 12.15**

Two events \( A \) and \( B \) are said to be independent if and only if
\[
\boxed{P(A \cap B) = P(A) \cdot P(B)}.
\]

**Note 12.6**

(1) This definition is exactly equivalent to
\[
P(A / B) = P(A) \quad \text{if } P(B) > 0
\]
\[
P(B / A) = P(B) \quad \text{if } P(A) > 0.
\]

(2) The events \( A_1, A_2, A_3, \dots, A_n \) are mutually independent if
\[
P(A_1 \cap A_2 \cap A_3 \cap \dots \cap A_n) = P(A_1) \cdot P(A_2) \cdot \dots \cdot P(A_n).
\]

**Theorem 12.8**

If \( A \) and \( B \) are independent then

(i) \( \overline{A} \) and \( \overline{B} \) are independent.

(ii) \( A \) and \( \overline{B} \) are independent.

(iii) \( \overline{A} \) and \( B \) are also independent.

**Proof**

(i) To prove \( \overline{A} \) and \( \overline{B} \) are independent:

Since \( A \) and \( B \) are independent, \( P(A \cap B) = P(A) \cdot P(B) \).

To prove \( \overline{A} \) and \( \overline{B} \) are independent, we have to prove
\[
P(\overline{A} \cap \overline{B}) = P(\overline{A}) \cdot P(\overline{B}).
\]

By de Morgan's law
\[
P(\overline{A} \cap \overline{B}) = P(\overline{A \cup B}) = 1 - P(A \cup B)
\]
\[
= 1 - [P(A) + P(B) - P(A \cap B)]
\]
\[
= 1 - P(A) - P(B) + P(A) \cdot P(B)
\]
\[
= (1 - P(A))(1 - P(B)) = P(\overline{A}) \cdot P(\overline{B}).
\]

Thus \( \overline{A} \) and \( \overline{B} \) are independent.

Similarly one can prove (ii) and (iii).

### Example 12.18

Two cards are drawn from a pack of forty cards (shown below) in succession. Find the probability that they are 18 and 24 respectively

(i) the first drawn card is replaced
(ii) the first drawn card is not replaced.

**Solution**

Let \( A \) be the event of drawing a 18 in the first draw. Let \( B \) be the event of drawing a 24 in the second draw.

**Case (i) Card is replaced**

\( n(A) = 2 \), \( n(B) = 2 \) and \( n(S) = 40 \) (Total)

Clearly the event \( A \) will not affect the probability of the occurrence of event \( B \) and therefore \( A \) and \( B \) are independent.
\[
P(A \cap B) = P(A) \cdot P(B)
\]
\[
P(A) = \frac{2}{40}, \quad P(B) = \frac{2}{40}
\]
\[
P(A \cap B) = \frac{2}{40} \cdot \frac{2}{40} = \frac{1}{400}.
\]

**Case (ii) Card is not replaced**

In the first draw, there are two 18 and forty cards in total. Since a 18 drawn at the first draw is not replaced, in the second draw there are only thirty-nine cards in total. Therefore the first event \( A \) affects the probability of the occurrence of the second event \( B \). (Note that the event \( A \) need not affect the occurrence of event \( B \)). Thus \( A \) and \( B \) are not independent. That is, they are dependent events.
\[
P(A \cap B) = P(A) \cdot P(B / A)
\]
\[
P(A) = \frac{2}{40}, \quad P(B / A) = \frac{2}{39}
\]
\[
P(A \cap B) = \frac{2}{40} \cdot \frac{2}{39} = \frac{1}{390}.
\]

### Example 12.19

A coin is tossed twice. Events \( E \) and \( F \) are defined as follows: \( E = \text{Head on first toss} \), \( F = \text{Head on second toss} \). Find

(i) \( P(E \cup F) \)
(ii) \( P(E / F) \)
(iii) \( P(E / \overline{F}) \)
(iv) Are the events \( E \) and \( F \) independent?

**Solution**

The sample space is
\[
S = \{H, T\} \times \{H, T\} = \{(H, H), (H, T), (T, H), (T, T)\}.
\]
\[
E = \{(H, H), (H, T)\}, \quad F = \{(H, H), (T, H)\}
\]
\[
E \cup F = \{(H, H), (H, T), (T, H)\}, \quad E \cap F = \{(H, H)\}
\]

(i) \( P(E \cup F) = \frac{n(E \cup F)}{n(S)} = \frac{3}{4} \)
\[
\text{or} \quad P(E \cup F) = P(E) + P(F) - P(E \cap F) = \frac{2}{4} + \frac{2}{4} - \frac{1}{4} = \frac{3}{4}.
\]

(ii) \( P(E / F) = \frac{P(E \cap F)}{P(F)} = \frac{1/4}{2/4} = \frac{1}{2} \).

(iii) \( P(E / \overline{F}) = \frac{P(E \cap \overline{F})}{P(\overline{F})} = \frac{P(E) - P(E \cap F)}{1 - P(F)} = \frac{2/4 - 1/4}{1 - 2/4} = \frac{1/4}{2/4} = \frac{1}{2} \).

(iv) \( P(E) = \frac{2}{4} = \frac{1}{2} \), \( P(F) = \frac{2}{4} = \frac{1}{2} \), \( P(E \cap F) = \frac{1}{4} \).

Since \( P(E \cap F) = \frac{1}{4} = P(E) \cdot P(F) = \frac{1}{2} \cdot \frac{1}{2} \), \( E \) and \( F \) are independent events.

**Note 12.7**

Independent events is a property of probability but mutual exclusiveness is a set-theoretic property. Therefore independent events can be identified by their probabilities and mutually exclusive events can be identified by their events.

**Theorem 12.9**

Suppose \( A \) and \( B \) are two events, such that \( P(A) \neq 0 \), \( P(B) \neq 0 \).

(1) If \( A \) and \( B \) are mutually exclusive, they cannot be independent.

(2) If \( A \) and \( B \) are independent they cannot be mutually exclusive. (Without proof)

### Example 12.20

If \( A \) and \( B \) are two independent events such that \( P(A) = 0.4 \) and \( P(A \cup B) = 0.9 \). Find \( P(B) \).

**Solution**

\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]
\[
= P(A) + P(B) - P(A) \cdot P(B) \quad (\text{since } A \text{ and } B \text{ are independent})
\]
That is,
\[
0.9 = 0.4 + P(B) - (0.4) P(B)
\]
\[
0.9 - 0.4 = (1 - 0.4) P(B)
\]
\[
0.5 = 0.6 P(B)
\]
Therefore,
\[
P(B) = \frac{5}{6}.
\]

### Example 12.21

An anti-aircraft gun can take a maximum of four shots at an enemy plane moving away from it. The probability of hitting the plane in the first, second, third, and fourth shot are respectively 0.2, 0.4, 0.2 and 0.1. Find the probability that the gun hits the plane.

**Solution**

Let \( H_1, H_2, H_3 \) and \( H_4 \) be the events of hitting the plane by the anti-aircraft gun in the first, second, third and fourth shot respectively.

Let \( H \) be the event that anti-aircraft gun hits the plane. Therefore \( \overline{H} \) is the event that the plane is not shot down.

Given that
\[
P(H_1) = 0.2 \Rightarrow P(\overline{H}_1) = 1 - P(H_1) = 0.8
\]
\[
P(H_2) = 0.4 \Rightarrow P(\overline{H}_2) = 1 - P(H_2) = 0.6
\]
\[
P(H_3) = 0.2 \Rightarrow P(\overline{H}_3) = 1 - P(H_3) = 0.8
\]
\[
P(H_4) = 0.1 \Rightarrow P(\overline{H}_4) = 1 - P(H_4) = 0.9
\]

The probability that the gun hits the plane is
\[
P(H) = 1 - P(\overline{H}) = 1 - P(\overline{H}_1 \cup \overline{H}_2 \cup \overline{H}_3 \cup \overline{H}_4)
\]
\[
= 1 - P(\overline{H}_1 \cap \overline{H}_2 \cap \overline{H}_3 \cap \overline{H}_4) \quad (\text{since independent})
\]
\[
= 1 - P(\overline{H}_1) P(\overline{H}_2) P(\overline{H}_3) P(\overline{H}_4)
\]
\[
= 1 - (0.8)(0.6)(0.8)(0.9) = 1 - 0.3456 = 0.6544.
\]

### Example 12.22

\( X \) speaks truth in 70 percent of cases, and \( Y \) in 90 percent of cases. What is the probability that they likely to contradict each other in stating the same fact?

**Solution**

Let \( A \) be the event of \( X \) speaks the truth, \( B \) be the event of \( Y \) speaks the truth. \( \overline{A} \) is the event of \( X \) not speaking the truth and \( \overline{B} \) is the event of \( Y \) not speaking the truth.

Let \( C \) be the event that they will contradict each other.

Given that
\[
P(A) = 0.70 \Rightarrow P(\overline{A}) = 1 - P(A) = 0.30
\]
\[
P(B) = 0.90 \Rightarrow P(\overline{B}) = 1 - P(B) = 0.10
\]

\( C = (A \text{ speaks truth and } B \text{ does not speak truth}) \) or \( (B \text{ speaks truth and } A \text{ does not speak truth}) \)
\[
C = [(A \cap \overline{B}) \cup (\overline{A} \cap B)]
\]

Since \( (A \cap \overline{B}) \) and \( (\overline{A} \cap B) \) are mutually exclusive,
\[
P(C) = P(A \cap \overline{B}) + P(\overline{A} \cap B)
\]
\[
= P(A) P(\overline{B}) + P(\overline{A}) P(B) \quad (\text{Since } A, B \text{ are independent events, } A, \overline{B} \text{ are also independent events})
\]
\[
= (0.70)(0.10) + (0.30)(0.90) = 0.070 + 0.270 = 0.34.
\]

### Example 12.23

A main road in a City has 4 crossroads with traffic lights. Each traffic light opens or closes the traffic with the probability of 0.4 and 0.6 respectively. Determine the probability of

(i) a car crossing the first crossroad without stopping

(ii) a car crossing first two crossroads without stopping

(iii) a car crossing all the crossroads, stopping at third cross

(iv) a car crossing all the crossroads, stopping at exactly one cross.

**Solution**

Let \( A_i \) be the event that the traffic light opens at \( i \)th cross, for \( i = 1,2,3,4 \).

Let \( B_i \) be the event that the traffic light closes at \( i \)th cross, for \( i = 1,2,3,4 \).

The traffic lights are all independent. Therefore \( A_i \) and \( B_i \) are all independent events, for \( i = 1,2,3,4 \).

Given that
\[
P(A_i) = 0.4, \quad i = 1,2,3,4
\]
\[
P(B_i) = 0.6, \quad i = 1,2,3,4
\]

(i) Probability of car crossing the first crossroad without stopping,
\[
P(A_1) = 0.4.
\]

(ii) Probability of car crossing first two crossroads without stopping,
\[
P(A_1 \cap A_2) = P(A_1) P(A_2) = (0.4)(0.4) = 0.16.
\]

(iii) Probability of car crossing all the crossroads, stopping at third cross,
\[
P(A_1 \cap A_2 \cap B_3 \cap A_4) = P(A_1) P(A_2) P(B_3) P(A_4) = (0.4)(0.4)(0.6)(0.4) = 0.0384.
\]

(iv) Probability of car crossing all the crossroads, stopping at exactly one of the crossroads is
\[
P(B_1 A_2 A_3 A_4 \cup A_1 B_2 A_3 A_4 \cup A_1 A_2 B_3 A_4 \cup A_1 A_2 A_3 B_4)
\]
\[
= P(B_1 A_2 A_3 A_4) + P(A_1 B_2 A_3 A_4) + P(A_1 A_2 B_3 A_4) + P(A_1 A_2 A_3 B_4)
\]
\[
= 4 (0.4)(0.4)(0.6)(0.4) = 4(0.0384) = 0.1536.
\]

## EXERCISE 12.3

(1) Can two events be mutually exclusive and independent simultaneously?

(2) If \( A \) and \( B \) are two events such that \( P(A \cup B) = 0.7 \), \( P(A \cap B) = 0.2 \), and \( P(B) = 0.5 \), then show that \( A \) and \( B \) are independent.

(3) If \( A \) and \( B \) are two independent events such that \( P(A \cup B) = 0.6 \), \( P(A) = 0.2 \), find \( P(B) \).

(4) If \( P(A) = 0.5 \), \( P(B) = 0.8 \), and \( P(B / A) = 0.8 \), find \( P(A / B) \) and \( P(A \cup B) \).

(5) If for two events \( A \) and \( B \), \( P(A) = \frac{3}{4} \), \( P(B) = \frac{2}{5} \), and \( A \cup B = S \) (sample space), find the conditional probability \( P(A / B) \).

(6) A problem in Mathematics is given to three students whose chances of solving it are \( \frac{1}{3}, \frac{1}{4} \) and \( \frac{1}{5} \).
(i) What is the probability that the problem is solved?
(ii) What is the probability that exactly one of them will solve it?

(7) The probability that a car being filled with petrol will also need an oil change is 0.30, the probability that it needs a new oil filter is 0.40, and the probability that both the oil and filter need changing is 0.15.
(i) If the oil had to be changed, what is the probability that a new oil filter is needed?
(ii) If a new oil filter is needed, what is the probability that the oil has to be changed?

(8) One bag contains 5 white and 3 black balls. Another bag contains 4 white and 6 black balls. If one ball is drawn from each bag, find the probability that
(i) both are white
(ii) both are black
(iii) one white and one black

(9) Two thirds of students in a class are boys and rest girls. It is known that the probability of a girl getting a first grade is 0.85 and that of boys is 0.70. Find the probability that a student chosen at random will get first grade marks.

(10) Given \( P(A) = 0.4 \) and \( P(A \cup B) = 0.7 \). Find \( P(B) \) if
(i) \( A \) and \( B \) are mutually exclusive
(ii) \( A \) and \( B \) are independent events
(iii) \( P(A / B) = 0.4 \)
(iv) \( P(B / A) = 0.5 \)

(11) A year is selected at random. What is the probability that
(i) it contains 53 Sundays
(ii) it is a leap year which contains 53 Sundays

(12) Suppose the chances of hitting a target by a person \( X \) is 3 times in 4 shots, by \( Y \) is 4 times in 5 shots, and by \( Z \) is 2 times in 3 shots. They fire simultaneously exactly one time. What is the probability that the target is damaged by exactly 2 hits?

## 12.7 Total Probability of an event

**Theorem 12.10 (Total Probability of an event)**

If \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive and exhaustive events and \( B \) is any event in \( S \), then \( P(B) \) is called the total probability of event \( B \) and
\[
\boxed{P(B) = P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n) = \sum_{i=1}^{n} P(A_i) P(B / A_i)}.
\]

**Proof**

Since \( B \) is any event in \( S \), from the figure shown here
\[
B = (A_1 \cap B) \cup (A_2 \cap B) \cup (A_3 \cap B) \cup \dots \cup (A_n \cap B).
\]

Since \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive, \( (A_1 \cap B), (A_2 \cap B), (A_3 \cap B), \dots, (A_n \cap B) \) are also mutually exclusive.

Therefore,
\[
P(B) = P[(A_1 \cap B) \cup (A_2 \cap B) \cup (A_3 \cap B) \cup \dots \cup (A_n \cap B)]
\]
\[
P(B) = P(A_1 \cap B) + P(A_2 \cap B) + P(A_3 \cap B) + \dots + P(A_n \cap B)
\]
\[
P(B) = P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n) = \sum_{i=1}^{n} P(A_i) P(B / A_i).
\]

The following problems are solved using the law of total probability of an event.

### Example 12.24

Urn-I contains 8 red and 4 blue balls and urn-II contains 5 red and 10 blue balls. One urn is chosen at random and two balls are drawn from it. Find the probability that both balls are red.

**Solution**

Let \( A_1 \) be the event of selecting urn-I and \( A_2 \) be the event of selecting urn-II.

Let \( B \) be the event of selecting 2 red balls.

We have to find the total probability of event \( B \). That is, \( P(B) \).

Clearly \( A_1 \) and \( A_2 \) are mutually exclusive and exhaustive events.

We have
\[
P(A_1) = \frac{1}{2}, \quad P(B / A_1) = \frac{{}^8C_2}{{}^{12}C_2} = \frac{28}{66} = \frac{14}{33}
\]
\[
P(A_2) = \frac{1}{2}, \quad P(B / A_2) = \frac{{}^5C_2}{{}^{15}C_2} = \frac{10}{105} = \frac{2}{21}.
\]

We know
\[
P(B) = P(A_1) P(B / A_1) + P(A_2) P(B / A_2)
\]
\[
P(B) = \frac{1}{2} \cdot \frac{14}{33} + \frac{1}{2} \cdot \frac{2}{21} = \frac{7}{33} + \frac{1}{21} = \frac{49 + 11}{231} = \frac{60}{231} = \frac{20}{77}.
\]

### Example 12.25

A factory has two machines I and II. Machine-I produces \( 40\% \) of items of the output and Machine-II produces \( 60\% \) of the items. Further \( 4\% \) of items produced by Machine-I are defective and \( 5\% \) produced by Machine-II are defective. If an item is drawn at random, find the probability that it is a defective item.

**Solution**

Let \( A_1 \) be the event that the items are produced by Machine-I, \( A_2 \) be the event that items are produced by Machine-II. Let \( B \) be the event of drawing a defective item.

We have to find the total probability of event B. That is, \( P(B) \).

Clearly \( A_1 \) and \( A_2 \) are mutually exclusive and exhaustive events.

We have
\[
P(A_1) = 0.40, \quad P(B / A_1) = 0.04
\]
\[
P(A_2) = 0.60, \quad P(B / A_2) = 0.05
\]
\[
P(B) = P(A_1) \cdot P(B / A_1) + P(A_2) \cdot P(B / A_2)
\]
\[
= (0.40)(0.04) + (0.60)(0.05) = 0.016 + 0.03 = 0.046.
\]

## 12.8 Bayes' Theorem

Thomas Bayes was an English statistician, philosopher and Presbyterian minister who is known for formulating a specific case of a theorem. Bayesian methods stem from the principle of linking prior (before conducting experiment) probability and conditional probability (likelihood) to posterior (after conducting experiment) probability via Bayes' rule. Bayesian probability is the name given to several related interpretations of probability as an amount of epistemic confidence - the strength of beliefs, hypotheses etc., rather than a frequency.

**Theorem 12.11 (Bayes' Theorem)**

If \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive and exhaustive events such that \( P(A_i) > 0 \), \( i = 1,2,3,\dots,n \) and \( B \) is any event in which \( P(B) > 0 \), then
\[
\boxed{P(A_i / B) = \frac{P(A_i) P(B / A_i)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n)} = \frac{P(A_i) P(B / A_i)}{\sum_{i=1}^{n} P(A_i) P(B / A_i)}}.
\]

**Proof**

By the law of total probability of \( B \) we have
\[
P(B) = P(A_1) \cdot P(B / A_1) + P(A_2) \cdot P(B / A_2) + \dots + P(A_n) \cdot P(B / A_n)
\]
and by multiplication theorem \( P(A_i \cap B) = P(B / A_i) P(A_i) \).

By the definition of conditional probability,
\[
P(A_i / B) = \frac{P(A_i \cap B)}{P(B)} = \frac{P(B / A_i) P(A_i)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n)}.
\]

The above formula gives the relationship between \( P(A_i / B) \) and \( P(B / A_i) \).

### Example 12.26

A factory has two machines I and II. Machine I produces \( 40\% \) of items of the output and Machine II produces \( 60\% \) of the items. Further \( 4\% \) of items produced by Machine I are defective and \( 5\% \) produced by Machine II are defective. An item is drawn at random. If the drawn item is defective, find the probability that it was produced by Machine II. (See the previous example, compare the questions).

**Solution**

Let \( A_1 \) be the event that the items are produced by Machine-I, \( A_2 \) be the event that items are produced by Machine-II. Let \( B \) be the event of drawing a defective item. Now we are asked to find the conditional probability \( P(A_2 / B) \). Since \( A_1, A_2 \) are mutually exclusive and exhaustive events, by Bayes' theorem,
\[
P(A_2 / B) = \frac{P(A_2) P(B / A_2)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2)}.
\]

We have,
\[
P(A_1) = 0.40, \quad P(B / A_1) = 0.04
\]
\[
P(A_2) = 0.60, \quad P(B / A_2) = 0.05
\]
\[
P(A_2 / B) = \frac{(0.60)(0.05)}{(0.40)(0.04) + (0.60)(0.05)} = \frac{0.03}{0.016 + 0.03} = \frac{0.03}{0.046} = \frac{30}{46} = \frac{15}{23}.
\]

### Example 12.27

A construction company employs 2 executive engineers. Engineer-1 does the work for \( 60\% \) of jobs of the company. Engineer-2 does the work for \( 40\% \) of jobs of the company. It is known from the past experience that the probability of an error when engineer-1 does the work is 0.03, whereas the probability of an error in the work of engineer-2 is 0.04. Suppose a serious error occurs in the work, which engineer would you guess did the work?

**Solution**

Let \( A_1 \) and \( A_2 \) be the events of job done by engineer-1 and engineer-2 of the company respectively. Let \( B \) be the event that the error occurs in the work.

We have to find the conditional probability \( P(A_1 / B) \) and \( P(A_2 / B) \) to compare their errors in their work.

From the given information, we have
\[
P(A_1) = 0.60, \quad P(B / A_1) = 0.03
\]
\[
P(A_2) = 0.40, \quad P(B / A_2) = 0.04
\]

\( A_1 \) and \( A_2 \) are mutually exclusive and exhaustive events.

Applying Bayes' theorem,
\[
P(A_1 / B) = \frac{P(A_1) P(B / A_1)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2)} = \frac{(0.60)(0.03)}{(0.60)(0.03) + (0.40)(0.04)} = \frac{0.018}{0.018 + 0.016} = \frac{0.018}{0.034} = \frac{9}{17}
\]
\[
P(A_2 / B) = \frac{P(A_2) P(B / A_2)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2)} = \frac{(0.40)(0.04)}{(0.60)(0.03) + (0.40)(0.04)} = \frac{0.016}{0.018 + 0.016} = \frac{0.016}{0.034} = \frac{8}{17}.
\]

Since \( P(A_1 / B) > P(A_2 / B) \), the chance of error done by engineer-1 is greater than the chance of error done by engineer-2. Therefore one may guess that the serious error would have been be done by engineer-1.

### Example 12.28

The chances of \( X, Y \) and \( Z \) becoming managers of a certain company are \( 4:2:3 \). The probabilities that bonus scheme will be introduced if \( X, Y \) and \( Z \) become managers are 0.3, 0.5 and 0.4 respectively. If the bonus scheme has been introduced, what is the probability that \( Z \) was appointed as the manager?

**Solution**

Let \( A_1, A_2 \) and \( A_3 \) be the events of \( X, Y \) and \( Z \) becoming managers of the company respectively. Let \( B \) be the event that the bonus scheme will be introduced.

We have to find the conditional probability \( P(A_3 / B) \).

Since \( A_1, A_2 \) and \( A_3 \) are mutually exclusive and exhaustive events, applying Bayes' theorem
\[
P(A_3 / B) = \frac{P(A_3) P(B / A_3)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + P(A_3) P(B / A_3)}.
\]

\[
P(A_1) = \frac{4}{9}, \quad P(B / A_1) = 0.3
\]
\[
P(A_2) = \frac{2}{9}, \quad P(B / A_2) = 0.5
\]
\[
P(A_3) = \frac{3}{9}, \quad P(B / A_3) = 0.4
\]
\[
P(A_3 / B) = \frac{\left(\frac{3}{9}\right)(0.4)}{\left(\frac{4}{9}\right)(0.3) + \left(\frac{2}{9}\right)(0.5) + \left(\frac{3}{9}\right)(0.4)} = \frac{1.2}{1.2 + 1.0 + 1.2} = \frac{1.2}{3.4} = \frac{12}{34} = \frac{6}{17}.
\]

### Example 12.29

A consulting firm rents car from three agencies such that \( 50\% \) from agency \( L \), \( 30\% \) from agency \( M \) and \( 20\% \) from agency \( N \). If \( 90\% \) of the cars from \( L \), \( 70\% \) of cars from \( M \) and \( 60\% \) of the cars from \( N \) are in good conditions (i) what is the probability that the firm will get a car in good condition? (ii) if a car is in good condition, what is probability that it has come from agency \( N \)?

**Solution**

Let \( A_1, A_2 \) and \( A_3 \) be the events that the cars are rented from the agencies \( L, M \) and \( N \) respectively.

Let \( G \) be the event of getting a car in good condition.

We have to find (i) the total probability of event \( G \) that is, \( P(G) \), (ii) the conditional probability \( A_3 \) given \( G \) that is, \( P(A_3 / G) \).

We have
\[
P(A_1) = 0.50, \quad P(G / A_1) = 0.90
\]
\[
P(A_2) = 0.30, \quad P(G / A_2) = 0.70
\]
\[
P(A_3) = 0.20, \quad P(G / A_3) = 0.60.
\]

(i) Since \( A_1, A_2 \) and \( A_3 \) are mutually exclusive and exhaustive events and \( G \) is an event in S, then the total probability of event \( G \) is \( P(G) \)
\[
P(G) = P(A_1) P(G / A_1) + P(A_2) P(G / A_2) + P(A_3) P(G / A_3)
\]
\[
P(G) = (0.50)(0.90) + (0.30)(0.70) + (0.20)(0.60) = 0.45 + 0.21 + 0.12 = 0.78.
\]

(ii) The conditional probability \( A_3 \) given \( G \) is \( P(A_3 / G) \).

By Bayes' theorem,
\[
P(A_3 / G) = \frac{P(A_3) P(G / A_3)}{P(A_1) P(G / A_1) + P(A_2) P(G / A_2) + P(A_3) P(G / A_3)}
\]
\[
= \frac{(0.20)(0.60)}{(0.50)(0.90) + (0.30)(0.70) + (0.20)(0.60)} = \frac{0.12}{0.45 + 0.21 + 0.12} = \frac{0.12}{0.78} = \frac{2}{13}.
\]

## EXERCISE 12.4

(1) A factory has two Machines-I and II. Machine-I produces \( 60\% \) of items and Machine-II produces \( 40\% \) of the items of the total output. Further \( 2\% \) of the items produced by Machine-I are defective whereas \( 4\% \) produced by Machine-II are defective. If an item is drawn at random what is the probability that it is defective?

(2) There are two identical urns containing respectively 6 black and 4 red balls, 2 black and 2 red balls. An urn is chosen at random and a ball is drawn from it.
(i) find the probability that the ball is black
(ii) if the ball is black, what is the probability that it is from the first urn?

(3) A firm manufactures PVC pipes in three plants viz, \( X \), \( Y \) and \( Z \). The daily production volumes from the three firms \( X \), \( Y \) and \( Z \) are respectively 2000 units, 3000 units and 5000 units. It is known from the past experience that \( 3\% \) of the output from plant \( X \), \( 4\% \) from plant \( Y \) and \( 2\% \) from plant \( Z \) are defective. A pipe is selected at random from a day's total production,
(i) find the probability that the selected pipe is a defective one.
(ii) if the selected pipe is a defective, then what is the probability that it was produced by plant \( Y \)?

(4) The chances of \( A \), \( B \) and \( C \) becoming manager of a certain company are \( 5:3:2 \). The probabilities that the office canteen will be improved if \( A \), \( B \), and \( C \) become managers are 0.4, 0.5 and 0.3 respectively. If the office canteen has been improved, what is the probability that \( B \) was appointed as the manager?

(5) An advertising executive is studying television viewing habits of married men and women during prime time hours. Based on the past viewing records he has determined that during prime time wives are watching television \( 60\% \) of the time. It has also been determined that when the wife is watching television, \( 40\% \) of the time the husband is also watching. When the wife is not watching the television, \( 30\% \) of the time the husband is watching the television. Find the probability that
(i) the husband is watching the television during the prime time of television
(ii) if the husband is watching the television, the wife is also watching the television.

## EXERCISE 12.5

Choose the correct or most suitable answer from the given four alternatives.

(1) Four persons are selected at random from a group of 3 men, 2 women and 4 children. The probability that exactly two of them are children is
(1) \( \frac{3}{4} \)
(2) \( \frac{10}{23} \)
(3) \( \frac{1}{2} \)
(4) \( \frac{10}{21} \)

(2) A number is selected from the set \( \{1,2,3,\dots,20\} \). The probability that the selected number is divisible by 3 or 4 is
(1) \( \frac{2}{5} \)
(2) \( \frac{1}{8} \)
(3) \( \frac{1}{2} \)
(4) \( \frac{2}{3} \)

(3) \( A, B \), and \( C \) try to hit a target simultaneously but independently. Their respective probabilities of hitting the target are \( \frac{3}{4}, \frac{1}{2}, \frac{5}{8} \). The probability that the target is hit by \( A \) or \( B \) but not by \( C \) is
(1) \( \frac{21}{64} \)
(2) \( \frac{7}{32} \)
(3) \( \frac{9}{64} \)
(4) \( \frac{7}{8} \)

(4) If \( A \) and \( B \) are any two events, then the probability that exactly one of them occur is
(1) \( P(A \cup \overline{B}) + P(\overline{A} \cup B) \)
(2) \( P(A \cap \overline{B}) + P(\overline{A} \cap B) \)
(3) \( P(A) + P(B) - P(A \cap B) \)
(4) \( P(A) + P(B) + 2P(A \cap B) \)

(5) Let \( A \) and \( B \) be two events such that \( P\left(\overline{A \cup B}\right) = \frac{1}{6} \), \( P\left(A \cap B\right) = \frac{1}{4} \) and \( P\left(\overline{A}\right) = \frac{1}{4} \). Then the events \( A \) and \( B \) are
(1) Equally likely but not independent
(2) Independent but not equally likely
(3) Independent and equally likely
(4) Mutually inclusive and dependent

(6) Two items are chosen from a lot containing twelve items of which four are defective, then the probability that at least one of the item is defective
(1) \( \frac{19}{33} \)
(2) \( \frac{17}{33} \)
(3) \( \frac{23}{33} \)
(4) \( \frac{13}{33} \)

(7) A man has 3 fifty rupee notes, 4 hundred rupees notes and 6 five hundred rupees notes in his pocket. If 2 notes are taken at random, what are the odds in favour of both notes being of hundred rupee denomination?
(1) 1:12
(2) 12:1
(3) 13:1
(4) 1:13

(8) A letter is taken at random from the letters of the word 'ASSISTANT' and another letter is taken at random from the letters of the word 'STATISTICS'. The probability that the selected letters are the same is
(1) \( \frac{7}{45} \)
(2) \( \frac{17}{90} \)
(3) \( \frac{29}{90} \)
(4) \( \frac{19}{90} \)

(9) A matrix is chosen at random from a set of all matrices of order 2, with elements 0 or 1 only. The probability that the determinant of the matrix chosen is non zero will be
(1) \( \frac{3}{16} \)
(2) \( \frac{3}{8} \)
(3) \( \frac{1}{4} \)
(4) \( \frac{5}{8} \)

(10) A bag contains 5 white and 3 black balls. Five balls are drawn successively without replacement. The probability that they are alternately of different colours is
(1) \( \frac{3}{14} \)
(2) \( \frac{5}{14} \)
(3) \( \frac{1}{14} \)
(4) \( \frac{9}{14} \)

(11) If \( A \) and \( B \) are two events such that \( A \subset B \) and \( P(B) \neq 0 \), then which of the following is correct?
(1) \( P(A / B) = \frac{P(A)}{P(B)} \)
(2) \( P(A / B) < P(A) \)
(3) \( P(A / B) \geq P(A) \)
(4) \( P(A / B) > P(B) \)

(12) A bag contains 6 green, 2 white, and 7 black balls. If two balls are drawn simultaneously, then the probability that both are different colours is
(1) \( \frac{68}{105} \)
(2) \( \frac{71}{105} \)
(3) \( \frac{64}{105} \)
(4) \( \frac{73}{105} \)

(13) If \( X \) and \( Y \) be two events such that \( P(X / Y) = \frac{1}{2} \), \( P(Y / X) = \frac{1}{3} \) and \( P(X \cap Y) = \frac{1}{6} \), then \( P(X \cup Y) \) is
(1) \( \frac{1}{3} \)
(2) \( \frac{2}{5} \)
(3) \( \frac{1}{6} \)
(4) \( \frac{2}{3} \)

(14) An urn contains 5 red and 5 black balls. A ball is drawn at random, its colour is noted and is returned to the urn. Moreover, 2 additional balls of the colour drawn are put in the urn and then a ball is drawn at random. The probability that the second ball drawn is red will be
(1) \( \frac{5}{12} \)
(2) \( \frac{1}{2} \)
(3) \( \frac{7}{12} \)
(4) \( \frac{1}{4} \)

(15) A number \( x \) is chosen at random from the first 100 natural numbers. Let \( A \) be the event of numbers which satisfies \( \frac{(x - 10)(x - 50)}{x - 30} \geq 0 \), then \( P(A) \) is
(1) 0.20
(2) 0.51
(3) 0.71
(4) 0.70

(16) If two events \( A \) and \( B \) are independent such that \( P(A) = 0.35 \) and \( P(A \cup B) = 0.6 \), then \( P(B) \) is
(1) \( \frac{5}{13} \)
(2) \( \frac{1}{13} \)
(3) \( \frac{4}{13} \)
(4) \( \frac{7}{13} \)

## SUMMARY

Let \( S \) be the sample space associated with a random experiment and \( A \) be an event.

\[
P(A) = \frac{n(A)}{n(S)} = \frac{\text{Number of cases favourable to } A}{\text{Exhaustive Number of cases in } S}.
\]

### Axioms of probability

Given a finite sample space \( S \) and an event \( A \) in \( S \), we define \( P(A) \), the probability of \( A \) satisfies the following three axioms.

[P1] \( P(A) \geq 0 \)

[P2] For two mutually exclusive events \( A \) and \( B \), \( P(A \cup B) = P(A) + P(B) \)

[P3] \( P(S) = 1 \)

The probability of the impossible event is zero. That is \( \boxed{P(\emptyset) = 0} \)

If \( \overline{A} \) is the complementary event of \( A \), then \( \boxed{P(\overline{A}) = 1 - P(A)} \)

If \( A \) and \( B \) are any two events and \( \overline{B} \) is the complementary events of \( B \), then
\[
\boxed{P(A \cap \overline{B}) = P(A) - P(A \cap B)}.
\]

If \( A \) and \( B \) are any two events, then
\[
\boxed{P(A \cup B) = P(A) + P(B) - P(A \cap B)}.
\]

The conditional probability of an event \( B \) assuming that the event \( A \) has already happened is denoted by \( P(B / A) \) and is defined as
\[
\boxed{P(B / A) = \frac{P(A \cap B)}{P(A)}} \quad \text{provided } P(A) \neq 0
\]
\[
\boxed{P(A / B) = \frac{P(A \cap B)}{P(B)}} \quad \text{provided } P(B) \neq 0.
\]

The probability of the simultaneous happening of two events \( A \) and \( B \) is given by
\[
\boxed{P(A \cap B) = P(A / B) P(B) \quad \text{or} \quad P(A \cap B) = P(B / A) P(A)}.
\]

Two events \( A \) and \( B \) are said to be independent if and only if
\[
\boxed{P(A \cap B) = P(A) \cdot P(B)}.
\]

### Total Probability

If \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive and exhaustive events and \( B \) is any event in \( S \), then \( P(B) \) is called the total probability of event \( B \) and
\[
\boxed{P(B) = P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n) = \sum_{i=1}^{n} P(A_i) P(B / A_i)}.
\]

### Bayes' Theorem

If \( A_1, A_2, A_3, \dots, A_n \) are mutually exclusive and exhaustive events such that \( P(A_i) > 0 \), \( i = 1,2,3,\dots,n \) and \( B \) is any event with \( P(B) > 0 \), then
\[
\boxed{P(A_i / B) = \frac{P(A_i) P(B / A_i)}{P(A_1) P(B / A_1) + P(A_2) P(B / A_2) + \dots + P(A_n) P(B / A_n)}}.
\]
