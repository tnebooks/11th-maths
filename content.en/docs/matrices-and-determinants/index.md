---
title: 'matrices and determinants'
weight: 7
summary: "This chapter introduces matrices as rectangular arrays of numbers and determinants as scalar values associated with square matrices, providing powerful mathematical tools for solving systems of linear equations and representing linear transformations. It covers various types of matrices, operations such as addition, subtraction, multiplication, and transpose, along with properties of determinants including evaluation using cofactor expansion and row/column operations. The chapter also discusses the inverse of a matrix, the adjoint method, Cramer's rule for solving linear systems, and the consistency and inconsistency of equations, which have extensive applications in physics, engineering, and computer science."
---

# Chapter 7: Matrices and Determinants

## 7.1 Introduction

The beginnings of matrices and determinants go back to the second century BC although traces can be seen back to the fourth century BC. However, it was not until near the end of the seventeenth century that the ideas reappeared and development really got underway. It is not surprising that the beginnings of matrices and determinants should arise through the study of systems of linear equations. The Babylonians studied problems which lead to simultaneous linear equations and some of these are preserved in clay tablets which survive till now.

The evolution of the theory of "matrices" is the result of attempts to obtain compact and simple methods for solving systems of linear equations. It also began with the study of transformations of geometric objects. In 1850, it was James Joseph Sylvester an English Mathematician and lawyer, coined the word 'Matrix' (originally from Latin: Mater means Mother - Collin's Dictionary). Matrices are now one of the most powerful tools in mathematics.

Generally, a matrix is nothing but a rectangular array of objects. These matrices can be visualised in day-to-day applications where we use matrices to represent a military parade or a school assembly or vegetation.

The term 'determinant' was first coined by Carl F Gauss in Disquisitiones arithmeticae (1801) while studying quadratic forms. But the concept is not the same as that of modern day determinant. In the same work Gauss laid out the coefficients of his quadratic forms in rectangular arrays where he described matrix multiplication.

It was Cauchy (in 1812) who used determinant in its modern sense and studied it in detail. He reproved the earlier results and gave new results of his own on minors and adjoints. It was Arthur Cayley whose major contribution was in developing the algebra of matrices and also published the theory of determinants in 1841. In that paper he used two vertical lines on either side of the array to denote the determinant, a notation which has now become standard. In 1858, he published Memoir on the theory of matrices which was remarkable for containing the first abstract definition of a matrix. He showed that the coefficient arrays studied earlier for quadratic forms and for linear transformations were special cases of his general concept. They simplify our work to a great extent when compared with other straight forward methods which would involve tedious computation. The mathematicians James Joseph Sylvester (1814-1897), William Rowan Hamilton (1805-1865), and Arthur Cayley (1821-1895) played important roles in the development of matrix theory. English mathematician Cullis was the first to use modern bracket notation for matrices in 1913. The knowledge of matrices is absolutely necessary not only within the branches of mathematics but also in other areas of science, genetics, economics, sociology, modern psychology and industrial management.

Matrices are also useful for representing coefficients in systems of linear equations. Matrix notations and operations are used in electronic spreadsheet programs on computers, which in turn are used in different areas of business like budgeting, sales projection, cost estimation, and in science, for analyzing the results of an experiment etc.

Interestingly, many geometric operations such as magnification, rotation and reflection through a plane can also be represented mathematically by matrices. Economists use matrices for social accounting, input-output tables and in the study of inter-industry economics. Matrices are also used in communication theory and network analysis in electrical engineering. They are also used in Cryptography.

In this chapter, we now first discuss matrices and their various properties. Then we continue to study determinants, basic properties, minors and their cofactors. Here we now restrict the discussion up to determinants of order 3 only.

## Learning Objectives

On completion of this chapter, the students are expected to

- visualise difficult problems in a simple manner in terms of matrices.
- understand different types of matrices and algebra of matrices.
- compute determinant values through expansion and using properties of determinants.
- apply the concepts of matrices and determinants to find the area of a triangle and collinearity of three points.

## 7.2 Matrices

A matrix is a rectangular array or arrangement of entries or elements displayed in rows and columns put within a square bracket [ ].

In general, the entries of a matrix may be real or complex numbers or functions of one variable (such as polynomials, trigonometric functions or a combination of them) or more variables or any other object. Usually, matrices are denoted by capital letters \( A, B, C, \ldots \) etc. In this chapter the entries of matrices are restricted to either real numbers or real valued functions on real variables.

### General form of a matrix

If a matrix \( A \) has \( m \) rows and \( n \) columns, then it is written as

\[
A = [a_{ij}]_{m \times n}, \quad 1 \leq i \leq m, \ 1 \leq j \leq n.
\]

That is,

\[
A = \begin{bmatrix}
a_{11} & a_{12} & \ldots & a_{1n} \\
a_{21} & a_{22} & \ldots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
a_{m1} & a_{m2} & \ldots & a_{mn}
\end{bmatrix}
\]

Note that \( m \) and \( n \) are positive integers.

The following are some examples of matrices:

\[
A = \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}, \quad
B = \begin{bmatrix}
1 & 2 & 3 & 4 \\
5 & 6 & 7 & 8 \\
9 & 10 & 11 & 12
\end{bmatrix}, \quad
C = \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9 \\
10 & 11 & 12
\end{bmatrix}
\]

In a matrix, the horizontal lines of elements are known as rows and the vertical lines of elements are known as columns. Thus \( A \) has 3 rows and 3 columns, \( B \) has 3 rows and 4 columns, and \( C \) has 4 rows and 3 columns.

**Definition 7.1**

If a matrix \( A \) has \( m \) rows and \( n \) columns then the order or size of the matrix \( A \) is defined to be \( m \times n \) (read as \( m \) by \( n \)).

The objects \( a_{11}, a_{12}, \ldots, a_{mn} \) are called elements or entries of the matrix \( A = [a_{ij}]_{m \times n} \). The element \( a_{ij} \) is common to \( i^{\text{th}} \) row and \( j^{\text{th}} \) column and is called \( (i, j)^{\text{th}} \) element of \( A \). Observe that the \( i^{\text{th}} \) row and \( j^{\text{th}} \) column of \( A \) are \( 1 \times n \) and \( m \times 1 \) matrices respectively and are given by \( [a_{i1}, a_{i2}, \ldots, a_{in}] \) and \( [a_{1j}, a_{2j}, \ldots, a_{mj}]^T \).

We shall now visualize the representation and construction of matrices for simplifying day-to-day problems.

### Illustration 7.1

Consider the marks scored by a student in different subjects and in different terminal examinations. They are exhibited in a tabular form as given below:

| | Tamil | English | Mathematics | Science | Social Science |
|---|---|---|---|---|---|
| Exam 1 | 48 | 71 | 80 | 62 | 55 |
| Exam 2 | 70 | 68 | 91 | 73 | 60 |
| Exam 3 | 77 | 84 | 95 | 82 | 62 |

This tabulation represents the above information in the form of matrix. What does the entry in the third row and second column represent?

\[
\begin{bmatrix}
48 & 71 & 80 & 62 & 55 \\
70 & 68 & 91 & 73 & 60 \\
77 & 84 & 95 & 82 & 62
\end{bmatrix}
\]

The entry 84 common to the third row and the second column in the matrix represents the mark scored by the student in English Exam 3.

### Example 7.1

Suppose that a matrix has 12 elements. What are the possible orders it can have? What if it has 7 elements?

**Solution**

The number of elements is the product of number of rows and number of columns. Therefore, we will find all ordered pairs of natural numbers whose product is 12. Thus, all the possible orders of the matrix are \( 1 \times 12 \), \( 12 \times 1 \), \( 2 \times 6 \), \( 6 \times 2 \), \( 3 \times 4 \) and \( 4 \times 3 \).

Since 7 is prime, the only possible orders of the matrix are \( 1 \times 7 \) and \( 7 \times 1 \).

### Example 7.2

Construct a \( 2 \times 3 \) matrix whose \( (i, j)^{\text{th}} \) element is given by

\[
a_{ij} = \frac{\sqrt{3}}{2} |2i - 3j| \quad (1 \leq i \leq 2, \ 1 \leq j \leq 3).
\]

**Solution**

In general, a \( 2 \times 3 \) matrix is given by \( A = \begin{bmatrix} a_{11} & a_{12} & a_{13} \\ a_{21} & a_{22} & a_{23} \end{bmatrix} \).

By definition of \( a_{ij} \), we easily have \( a_{11} = \frac{\sqrt{3}}{2} |2 - 3| = \frac{\sqrt{3}}{2} \) and other entries of the matrix \( A \) may be computed similarly. Thus, the required matrix \( A \) is

\[
\begin{bmatrix}
\frac{\sqrt{3}}{2} & 2\sqrt{3} & \frac{7\sqrt{3}}{2} \\
\frac{\sqrt{3}}{2} & \sqrt{3} & \frac{5\sqrt{3}}{2}
\end{bmatrix}.
\]

### 7.2.1 Types of Matrices

#### Row, Column, Zero matrices

**Definition 7.2**

A matrix having only one row is called a row matrix.

For instance, \( A = [1 \ 0 \ -1.1 \ \sqrt{2}] \) is a row matrix. More generally, \( A = [a_{ij}]_{1 \times n} \) is a row matrix of order \( 1 \times n \).

**Definition 7.3**

A matrix having only one column is called a column matrix.

For instance, \( \begin{bmatrix} x + 1 \\ x^2 \\ 3x \\ 4 \end{bmatrix} \) is a column matrix whose entries are real valued functions of real variable \( x \). More generally, \( A = [a_{ij}]_{m \times 1} = [a_{i1}]_{m \times 1} \) is a column matrix of order \( m \times 1 \).

**Definition 7.4**

A matrix \( A = [a_{ij}]_{m \times n} \) is said to be a zero matrix or null matrix or void matrix denoted by \( O \) if \( a_{ij} = 0 \) for all values of \( 1 \leq i \leq m \) and \( 1 \leq j \leq n \).

For instance, \( [0] \), \( \begin{bmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 0 \end{bmatrix} \) and \( \begin{bmatrix} 0 & 0 & 0 & 0 \\ 0 & 0 & 0 & 0 \end{bmatrix} \) are zero matrices of order \( 1 \times 1 \), \( 3 \times 3 \) and \( 2 \times 4 \) respectively.

A matrix \( A \) is said to be a non-zero matrix if at least one of the entries of \( A \) is non-zero.

#### Square, Diagonal, Unit, Triangular matrices

**Definition 7.5**

A matrix in which number of rows is equal to the number of columns, is called a square matrix. That is, a matrix of order \( n \times n \) is often referred to as a square matrix of order \( n \).

For instance, \( A = \begin{bmatrix} a & b & c \\ d & e & f \\ g & h & i \end{bmatrix} \) is a square matrix of order 3.

**Definition 7.6**

In a square matrix \( A = [a_{ij}]_{n \times n} \) of order \( n \), the elements \( a_{11}, a_{22}, a_{33}, \ldots, a_{nn} \) are called the principal diagonal or simply the diagonal or main diagonal or leading diagonal elements.

**Definition 7.7**

A square matrix \( A = [a_{ij}]_{n \times n} \) is called a diagonal matrix if \( a_{ij} = 0 \) whenever \( i \neq j \).

Thus, in a diagonal matrix all the entries except the entries along the main diagonal are zero. For instance,

\[
\begin{bmatrix}
2 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 2
\end{bmatrix}, \quad
\begin{bmatrix}
5 & 0 \\
0 & 5
\end{bmatrix}, \quad
[3], \quad
\begin{bmatrix}
a_1 & 0 & \cdots & 0 \\
0 & a_2 & \cdots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \cdots & a_n
\end{bmatrix}
\]

are diagonal matrices of order 3, 2, 1, and \( n \) respectively.

Is a square zero matrix, a diagonal matrix?

**Definition 7.8**

A diagonal matrix whose entries along the principal diagonal are equal is called a Scalar matrix.

That is, a square matrix \( A = [a_{ij}]_{n \times n} \) is said to be a scalar matrix if

\[
a_{ij} = \begin{cases}
c & \text{if } i = j \\
0 & \text{if } i \neq j
\end{cases}
\]

where \( c \) is a fixed number. For instance,

\[
\begin{bmatrix}
3 & 0 & 0 \\
0 & 3 & 0 \\
0 & 0 & 3
\end{bmatrix}, \quad
\begin{bmatrix}
5 & 0 \\
0 & 5
\end{bmatrix}, \quad
[2], \quad
\begin{bmatrix}
c & 0 & \cdots & 0 \\
0 & c & \cdots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \cdots & c
\end{bmatrix}
\]

are scalar matrices of order 3, 2, 1, and \( n \) respectively.

Observe that any square zero matrix can be considered as a scalar matrix with scalar 0.

**Definition 7.9**

A square matrix in which all the diagonal entries are 1 and the rest are all zero is called a unit matrix. Thus, a square matrix \( A = [a_{ij}]_{n \times n} \) is said to be a unit matrix if

\[
a_{ij} = \begin{cases}
1 & \text{if } i = j \\
0 & \text{if } i \neq j
\end{cases}
\]

We represent the unit matrix of order \( n \) as \( I_n \). For instance,

\[
[1], \quad \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}, \quad \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix}, \quad \begin{bmatrix}
1 & 0 & \cdots & 0 \\
0 & 1 & \cdots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \cdots & 1
\end{bmatrix}
\]

are unit matrices of order 1, 2, 3 and \( n \) respectively.

**Note 7.1**

Unit matrix is an example of a scalar matrix.

There are two kinds of triangular matrices namely upper triangular and lower triangular matrices.

**Definition 7.10**

A square matrix is said to be an upper triangular matrix if all the elements below the main diagonal are zero.

Thus, the square matrix \( A = [a_{ij}]_{n \times n} \) is said to be an upper triangular matrix if \( a_{ij} = 0 \) for all \( i > j \). For instance,

\[
\begin{bmatrix}
1 & 2 & 3 \\
0 & 4 & 5 \\
0 & 0 & 6
\end{bmatrix}, \quad
\begin{bmatrix}
1 & 2 \\
0 & 3
\end{bmatrix}, \quad
\begin{bmatrix}
2 & 3 & 4 & 5 \\
0 & 6 & 7 & 8 \\
0 & 0 & 9 & 10 \\
0 & 0 & 0 & 11
\end{bmatrix}
\]

**Definition 7.11**

A square matrix is said to be a lower triangular matrix if all the elements above the main diagonal are zero.

More precisely, a square matrix \( A = [a_{ij}]_{n \times n} \) is said to be a lower triangular matrix if \( a_{ij} = 0 \) for all \( i < j \). For instance,

\[
\begin{bmatrix}
2 & 0 & 0 \\
4 & 1 & 0 \\
9 & -3 & 8
\end{bmatrix}, \quad
\begin{bmatrix}
2 & 0 \\
4 & 1
\end{bmatrix}, \quad
\begin{bmatrix}
a_1 & 0 & \cdots & 0 \\
a_{21} & a_2 & \cdots & 0 \\
\vdots & \vdots & \ddots & \vdots \\
a_{n1} & a_{n2} & \cdots & a_n
\end{bmatrix}
\]

**Definition 7.12**

A square matrix which is either upper triangular or lower triangular is called a triangular matrix.

Observe that a square matrix that is both upper and lower triangular simultaneously will turn out to be a diagonal matrix.

### 7.2.2 Equality of Matrices

**Definition 7.13**

Two matrices \( A = [a_{ij}] \) and \( B = [b_{ij}] \) are equal (written as \( A = B \)) if and only if

(i) both \( A \) and \( B \) are of the same order

(ii) the corresponding entries of \( A \) and \( B \) are equal. That is, \( a_{ij} = b_{ij} \) for all \( i \) and \( j \).

For instance, if

\[
\begin{bmatrix}
x + y & x \\
y & x - y
\end{bmatrix} = \begin{bmatrix}
4 & 3 \\
1 & 2
\end{bmatrix}
\]

**Definition 7.14**

Two matrices \( A \) and \( B \) are called unequal if either of condition (i) or (ii) of Definition 7.13 does not hold.

For instance, \( \begin{bmatrix} 4 & -3 \\ 0 & 8 \end{bmatrix} \neq \begin{bmatrix} 8 & -5 \\ 0 & 4 \end{bmatrix} \) as the corresponding entries are not equal. Also \( \begin{bmatrix} 4 & -3 \\ 0 & 8 \end{bmatrix} \neq \begin{bmatrix} 5 & -8 \\ 3 & 4 \\ 6 & 7 \end{bmatrix} \) as the orders are not the same.

### Example 7.3

Find the values of \( x, y, a, b \) if

\[
\begin{bmatrix}
3x + 4y & a + b \\
x - 2y & 2a - b
\end{bmatrix} = \begin{bmatrix}
2 & 5 \\
4 & -5
\end{bmatrix}
\]

**Solution**

As the orders of the two matrices are same, they are equal if and only if the corresponding entries are equal. Thus, by comparing the corresponding elements, we get

\[
3x + 4y = 2, \quad x - 2y = 4, \quad a + b = 5, \quad \text{and} \quad 2a - b = -5.
\]

Solving these equations, we get \( x = 2, y = -1, a = 0, \) and \( b = 5 \).

### 7.2.3 Algebraic Operations on Matrices

Basic operations on matrices are (1) multiplication of a matrix by a scalar, (2) addition/subtraction of two matrices, and (3) multiplication of two matrices. There is no concept of dividing a matrix by another matrix and thus, the operation \( \frac{A}{B} \), where \( A \) and \( B \) are matrices, is not defined.

#### (1) Multiplication of a matrix by a scalar

For a given matrix \( A = [a_{ij}]_{m \times n} \) and a scalar \( k \), we define a new matrix \( kA = [b_{ij}]_{m \times n} \), where \( b_{ij} = k a_{ij} \) for all \( i \) and \( j \).

For example,

\[
3 \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{bmatrix} = \begin{bmatrix}
3 & 6 & 9 \\
12 & 15 & 18
\end{bmatrix}
\]

In particular if \( k = -1 \), we obtain \( -A = [-a_{ij}]_{m \times n} \). This \( -A \) is called negative of the matrix \( A \). Don't say \( -A \) as a negative matrix.

#### (2) Addition and Subtraction of two matrices

If \( A \) and \( B \) are two matrices of the same order, then their sum denoted by \( A + B \), is again a matrix of same order, obtained by adding the corresponding entries of \( A \) and \( B \).

More precisely, if \( A = [a_{ij}]_{m \times n} \) and \( B = [b_{ij}]_{m \times n} \) are two matrices, then the sum \( A + B \) of \( A \) and \( B \) is a matrix given by

\[
A + B = [c_{ij}]_{m \times n} \quad \text{where} \quad c_{ij} = a_{ij} + b_{ij} \quad \text{for all } i \text{ and } j.
\]

Similarly subtraction \( A - B \) is defined as \( A - B = A + (-1)B \).

That is, \( A - B = [d_{ij}]_{m \times n} \), where \( d_{ij} = a_{ij} - b_{ij} \) for all \( i \) and \( j \). (The symbol \( \forall \) denotes for every or for all).

**Note 7.2**

(i) If \( A \) and \( B \) are not of the same order, then \( A + B \) and \( A - B \) are not defined.

(ii) The addition and subtraction can be extended to any finite number of matrices.

### Example 7.4

Compute \( A + B \) and \( A - B \) if

\[
A = \begin{bmatrix}
1 & -2 & 3 \\
-4 & 2 & 5
\end{bmatrix}, \quad
B = \begin{bmatrix}
2 & 3 & 4 \\
5 & 6 & 7
\end{bmatrix}
\]

**Solution**

By the definitions of addition and subtraction of matrices, we have

\[
A + B = \begin{bmatrix}
1+2 & -2+3 & 3+4 \\
-4+5 & 2+6 & 5+7
\end{bmatrix} = \begin{bmatrix}
3 & 1 & 7 \\
1 & 8 & 12
\end{bmatrix}
\]

\[
A - B = \begin{bmatrix}
1-2 & -2-3 & 3-4 \\
-4-5 & 2-6 & 5-7
\end{bmatrix} = \begin{bmatrix}
-1 & -5 & -1 \\
-9 & -4 & -2
\end{bmatrix}
\]

### Example 7.5

Find the sum \( A + B + C \) if \( A, B, C \) are given by

\[
A = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}, \quad
B = \begin{bmatrix}
5 & 6 \\
7 & 8
\end{bmatrix}, \quad
C = \begin{bmatrix}
-1 & -2 \\
-3 & -4
\end{bmatrix}
\]

**Solution**

By the definition of sum of matrices, we have

\[
A + B + C = \begin{bmatrix}
1+5+(-1) & 2+6+(-2) \\
3+7+(-3) & 4+8+(-4)
\end{bmatrix} = \begin{bmatrix}
5 & 6 \\
7 & 8
\end{bmatrix}
\]

### Example 7.6

Determine \( 3B + 4C - D \) if \( B, C \) and \( D \) are given by

\[
B = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}, \quad
C = \begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}, \quad
D = \begin{bmatrix}
2 & 2 \\
2 & 2
\end{bmatrix}
\]

**Solution**

\[
3B = \begin{bmatrix}
3 & 6 \\
9 & 12
\end{bmatrix}, \quad
4C = \begin{bmatrix}
4 & 0 \\
0 & 4
\end{bmatrix}
\]

\[
3B + 4C - D = \begin{bmatrix}
3+4-2 & 6+0-2 \\
9+0-2 & 12+4-2
\end{bmatrix} = \begin{bmatrix}
5 & 4 \\
7 & 14
\end{bmatrix}
\]

### Example 7.7

Simplify:

\[
2\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix} - 3\begin{bmatrix}
2 & 0 \\
1 & 1
\end{bmatrix} + \begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
\]

**Solution**

If we denote the given expression by \( A \), then using the scalar multiplication rule, we get

\[
2\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix} = \begin{bmatrix}
2 & 4 \\
6 & 8
\end{bmatrix}, \quad
3\begin{bmatrix}
2 & 0 \\
1 & 1
\end{bmatrix} = \begin{bmatrix}
6 & 0 \\
3 & 3
\end{bmatrix}
\]

\[
A = \begin{bmatrix}
2 & 4 \\
6 & 8
\end{bmatrix} - \begin{bmatrix}
6 & 0 \\
3 & 3
\end{bmatrix} + \begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix} = \begin{bmatrix}
2-6+1 & 4-0+1 \\
6-3+1 & 8-3+1
\end{bmatrix} = \begin{bmatrix}
-3 & 5 \\
4 & 6
\end{bmatrix}
\]

#### (3) Multiplication of matrices

**Definition 7.15**

A matrix \( A \) is said to be conformable for multiplication with a matrix \( B \) if the number of columns of \( A \) is equal to the number of rows of \( B \).

That is, if \( A = [a_{ij}]_{m \times n} \) and \( B = [b_{ij}]_{n \times p} \) are given two matrices, then the product of matrices \( A \) and \( B \) is denoted by \( AB \) and its order is \( m \times p \).

The order of \( AB \) is \( m \times p = \) (number of rows of \( A \)) \( \times \) (number of columns of \( B \)).

The product \( AB \) is defined as follows:

\[
(AB)_{ik} = \sum_{j=1}^{n} a_{ij} b_{jk}, \quad 1 \leq i \leq m, \ 1 \leq k \leq p
\]

### Example 7.8

Find \( AB \) if \( A = \begin{bmatrix} a & b & c \\ b & c & a \\ c & a & b \end{bmatrix} \) and \( B = \begin{bmatrix} 0 & c & b \\ c & 0 & a \\ b & a & 0 \end{bmatrix} \).

**Solution**

The order of \( A \) is \( 3 \times 3 \) and the order of \( B \) is \( 3 \times 3 \). Therefore the product \( AB \) is defined and its order is \( 3 \times 3 \).

\[
AB = \begin{bmatrix}
a & b & c \\
b & c & a \\
c & a & b
\end{bmatrix}
\begin{bmatrix}
0 & c & b \\
c & 0 & a \\
b & a & 0
\end{bmatrix}
\]

Let \( C = AB = [c_{ij}]_{3 \times 3} \). Then

\[
c_{11} = a \cdot 0 + b \cdot c + c \cdot b = bc + bc = 2bc
\]
\[
c_{12} = a \cdot c + b \cdot 0 + c \cdot a = ac + ac = 2ac
\]
\[
c_{13} = a \cdot b + b \cdot a + c \cdot 0 = ab + ab = 2ab
\]
\[
c_{21} = b \cdot 0 + c \cdot c + a \cdot b = c^2 + ab
\]
\[
c_{22} = b \cdot c + c \cdot 0 + a \cdot a = bc + a^2
\]
\[
c_{23} = b \cdot b + c \cdot a + a \cdot 0 = b^2 + ac
\]
\[
c_{31} = c \cdot 0 + a \cdot c + b \cdot b = ac + b^2
\]
\[
c_{32} = c \cdot c + a \cdot 0 + b \cdot a = c^2 + ab
\]
\[
c_{33} = c \cdot b + a \cdot a + b \cdot 0 = bc + a^2
\]

Thus,

\[
AB = \begin{bmatrix}
2bc & 2ac & 2ab \\
c^2 + ab & a^2 + bc & b^2 + ac \\
b^2 + ac & c^2 + ab & a^2 + bc
\end{bmatrix}
\]

### Example 7.9

Solve for \( x \) if

\[
[x \ 2 \ -1] \begin{bmatrix}
1 & 1 & 2 \\
-1 & -4 & 1 \\
-1 & -1 & -2
\end{bmatrix} \begin{bmatrix}
x \\
2 \\
1
\end{bmatrix} = 0.
\]

**Solution**

Let \( A = \begin{bmatrix} 1 & 1 & 2 \\ -1 & -4 & 1 \\ -1 & -1 & -2 \end{bmatrix} \). First compute

\[
\begin{bmatrix}
x & 2 & -1
\end{bmatrix} A = \begin{bmatrix}
x \cdot 1 + 2 \cdot (-1) + (-1) \cdot (-1) & x \cdot 1 + 2 \cdot (-4) + (-1) \cdot (-1) & x \cdot 2 + 2 \cdot 1 + (-1) \cdot (-2)
\end{bmatrix}
\]
\[
= \begin{bmatrix}
x - 2 + 1 & x - 8 + 1 & 2x + 2 + 2
\end{bmatrix} = \begin{bmatrix}
x - 1 & x - 7 & 2x + 4
\end{bmatrix}
\]

Now,

\[
\begin{bmatrix}
x - 1 & x - 7 & 2x + 4
\end{bmatrix} \begin{bmatrix}
x \\
2 \\
1
\end{bmatrix} = (x - 1)x + (x - 7) \cdot 2 + (2x + 4) \cdot 1
\]
\[
= x^2 - x + 2x - 14 + 2x + 4 = x^2 + 3x - 10 = 0
\]

Thus, \( x^2 + 3x - 10 = 0 \) gives \( (x + 5)(x - 2) = 0 \). Hence, \( x = -5 \) or \( x = 2 \).

**Note 7.3**

We have the following important observations:

(1) If \( A = [a_{ij}]_{m \times n} \) and \( B = [b_{ij}]_{n \times p} \), and \( m \neq p \), then the product \( AB \) is defined but not \( BA \).

(2) The fundamental properties of real numbers namely,
\[
ab = ba \ \forall a, b \in \mathbb{R}
\]
\[
ab = ac \Rightarrow b = c \ \forall a, b, c \in \mathbb{R}, a \neq 0
\]
\[
ab = 0 \Rightarrow a = 0 \text{ or } b = 0 \ \forall a, b \in \mathbb{R}
\]

Can we discuss these in matrices also?

(i) Even if \( AB \) and \( BA \) are defined, then \( AB = BA \) is not necessarily true.

For instance, we consider

\[
A = \begin{bmatrix}
1 & 1 \\
2 & 0
\end{bmatrix}, \quad
B = \begin{bmatrix}
2 & -1 \\
3 & 1
\end{bmatrix}
\]

Then
\[
AB = \begin{bmatrix}
5 & 0 \\
4 & -2
\end{bmatrix}, \quad
BA = \begin{bmatrix}
0 & 2 \\
5 & 3
\end{bmatrix}
\]

In this case we say that \( A \) and \( B \) do not commute (with respect to multiplication).

Observe that \( AB = BA \) is also possible. For instance,

\[
A = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}, \quad
B = \begin{bmatrix}
2 & 0 \\
0 & 2
\end{bmatrix}
\]
\[
AB = \begin{bmatrix}
2 & 4 \\
6 & 8
\end{bmatrix}, \quad
BA = \begin{bmatrix}
2 & 4 \\
6 & 8
\end{bmatrix}
\]

In this case we say that \( A \) and \( B \) commute with respect to multiplication.

(ii) Cancellation property does not hold for matrix multiplication. That is, if \( A \neq O \), \( B \), and \( C \) are three square matrices of same order \( n \times n \) with \( n > 1 \), then \( AB = AC \) does not imply \( B = C \) and \( BA = CA \) does not imply \( B = C \).

As a simple demonstration of these facts, we observe that for instance,

\[
A = \begin{bmatrix}
0 & 1 \\
0 & 0
\end{bmatrix}, \quad
B = \begin{bmatrix}
1 & 0 \\
0 & 0
\end{bmatrix}, \quad
C = \begin{bmatrix}
1 & 0 \\
1 & 0
\end{bmatrix}
\]
\[
AB = \begin{bmatrix}
0 & 0 \\
0 & 0
\end{bmatrix}, \quad
AC = \begin{bmatrix}
0 & 0 \\
0 & 0
\end{bmatrix}
\]

Here \( AB = AC \) but \( B \neq C \).

(iii) It is possible that \( AB = O \) with \( A \neq O \) and \( B \neq O \); Equivalently, \( AB = O \) is not necessarily imply either \( A = O \) or \( B = O \). The following relation demonstrates this fact:

\[
\begin{bmatrix}
1 & 1 \\
1 & 1
\end{bmatrix}
\begin{bmatrix}
1 & 1 \\
-1 & -1
\end{bmatrix} = \begin{bmatrix}
0 & 0 \\
0 & 0
\end{bmatrix}
\]

(3) In general, for any two matrices \( A \) and \( B \) which are conformable for addition and multiplication, for the below operations, we have
\[
(A + B)^2 \neq A^2 + 2AB + B^2
\]
unless \( AB = BA \).

### Example 7.10

If \( A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} \) and \( B = \begin{bmatrix} 1 & 0 \\ 0 & 1 \\ 1 & 0 \end{bmatrix} \), find \( AB \).

**Solution**

The order of \( A \) is \( 3 \times 3 \) and the order of \( B \) is \( 3 \times 2 \). Therefore the order of \( AB \) is \( 3 \times 2 \). \( A \) and \( B \) are conformable for the product \( AB \). Call \( C = AB \). Then,

\[
c_{11} = \text{(first row of } A\text{)} \cdot \text{(first column of } B\text{)} = 1 \cdot 1 + 2 \cdot 0 + 3 \cdot 1 = 1 + 0 + 3 = 4
\]
\[
c_{12} = \text{(first row of } A\text{)} \cdot \text{(second column of } B\text{)} = 1 \cdot 0 + 2 \cdot 1 + 3 \cdot 0 = 0 + 2 + 0 = 2
\]
\[
c_{21} = \text{(second row of } A\text{)} \cdot \text{(first column of } B\text{)} = 4 \cdot 1 + 5 \cdot 0 + 6 \cdot 1 = 4 + 0 + 6 = 10
\]
\[
c_{22} = \text{(second row of } A\text{)} \cdot \text{(second column of } B\text{)} = 4 \cdot 0 + 5 \cdot 1 + 6 \cdot 0 = 0 + 5 + 0 = 5
\]
\[
c_{31} = \text{(third row of } A\text{)} \cdot \text{(first column of } B\text{)} = 7 \cdot 1 + 8 \cdot 0 + 9 \cdot 1 = 7 + 0 + 9 = 16
\]
\[
c_{32} = \text{(third row of } A\text{)} \cdot \text{(second column of } B\text{)} = 7 \cdot 0 + 8 \cdot 1 + 9 \cdot 0 = 0 + 8 + 0 = 8
\]

Therefore,
\[
AB = C = \begin{bmatrix}
4 & 2 \\
10 & 5 \\
16 & 8
\end{bmatrix}
\]

The product \( BA \) does not exist, because the number of columns in \( B \) is not equal to the number of rows in \( A \).

### Example 7.11

A fruit shop keeper prepares 3 different varieties of gift packages. Pack-I contains 6 apples, 3 oranges and 3 pomegranates. Pack-II contains 5 apples, 4 oranges and 4 pomegranates and Pack-III contains 6 apples, 6 oranges and 6 pomegranates. The cost of an apple, an orange and a pomegranate respectively are ₹30, ₹15 and ₹45. What is the cost of preparing each package of fruits?

**Solution**

Cost matrix \( A = \begin{bmatrix} 30 & 15 & 45 \end{bmatrix} \)

Fruit matrix \( B = \begin{bmatrix}
6 & 5 & 6 \\
3 & 4 & 6 \\
3 & 4 & 6
\end{bmatrix} \) (Apples, Oranges, Pomegranates)

Cost of packages are obtained by computing \( AB \). That is, by multiplying cost of each item in \( A \) (cost matrix \( A \)) with number of items in \( B \) (Fruit matrix \( B \)).

\[
AB = \begin{bmatrix}
30 & 15 & 45
\end{bmatrix}
\begin{bmatrix}
6 & 5 & 6 \\
3 & 4 & 6 \\
3 & 4 & 6
\end{bmatrix}
\]
\[
= \begin{bmatrix}
30 \cdot 6 + 15 \cdot 3 + 45 \cdot 3 & 30 \cdot 5 + 15 \cdot 4 + 45 \cdot 4 & 30 \cdot 6 + 15 \cdot 6 + 45 \cdot 6
\end{bmatrix}
\]
\[
= \begin{bmatrix}
180 + 45 + 135 & 150 + 60 + 180 & 180 + 90 + 270
\end{bmatrix}
\]
\[
= \begin{bmatrix}
360 & 390 & 540
\end{bmatrix}
\]

Pack-I cost ₹360, Pack-II cost ₹390, Pack-III costs ₹540.

### 7.2.4 Properties of Matrix Addition, Scalar Multiplication and Product of Matrices

Let \( A, B, \) and \( C \) be three matrices of same order which are conformable for addition and \( a, b \) be two scalars. Then we have the following:

(1) \( A + B \) yields a matrix of the same order

(2) \( A + B = B + A \) (Matrix addition is commutative)

(3) \( (A + B) + C = A + (B + C) \) (Matrix addition is associative)

(4) \( A + O = O + A = A \) (O is additive identity)

(5) \( A + (-A) = O = (-A) + A \) (\(-A\) is the additive inverse of \(A\))

(6) \( (a + b)A = aA + bA \) and \( a(A + B) = aA + aB \)

(7) \( a(bA) = (ab)A \), \( 1A = A \) and \( 0A = O \)

#### Properties of matrix multiplication

Using the algebraic properties of matrices we have,

- If \( A, B, \) and \( C \) are three matrices of orders \( m \times n, n \times p \) and \( p \times q \) respectively, then \( A(BC) \) and \( (AB)C \) are matrices of same order \( m \times q \) and \( A(BC) = (AB)C \) (Matrix multiplication is associative).

- If \( A, B \) and \( C \) are three matrices of orders \( m \times n, n \times p \) and \( n \times p \) respectively, then \( A(B + C) \) and \( AB + AC \) are matrices of the same order \( m \times p \) and \( A(B + C) = AB + AC \) (Matrix multiplication is left distributive over addition).

- If \( A, B \) and \( C \) are three matrices of orders \( m \times n, m \times n \) and \( n \times p \) respectively, then \( (A + B)C \) and \( AC + BC \) are matrices of the same order \( m \times p \) and \( (A + B)C = AC + BC \) (Matrix multiplication is right distributive over addition).

- If \( A, B \) are two matrices of orders \( m \times n \) and \( n \times p \) respectively and \( \alpha \) is scalar, then \( \alpha(AB) = A(\alpha B) = (\alpha A)B \) is a matrix of order \( m \times p \).

- If \( I \) is the unit matrix, then \( AI = IA = A \) (\(I\) is called multiplicative identity).

### 7.2.5 Operation of Transpose of a Matrix and its Properties

**Definition 7.16**

The transpose of a matrix is obtained by interchanging rows and columns of \( A \) and is denoted by \( A^T \).

More precisely, if \( A = [a_{ij}]_{m \times n} \), then \( A^T = [b_{ij}]_{n \times m} \), where \( b_{ij} = a_{ji} \) so that the \( (i, j)^{\text{th}} \) entry of \( A^T \) is \( a_{ji} \).

For instance,
\[
A = \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{bmatrix} \Rightarrow A^T = \begin{bmatrix}
1 & 4 \\
2 & 5 \\
3 & 6
\end{bmatrix}
\]

We state a few basic results on transpose whose proofs are straight forward.

For any two matrices \( A \) and \( B \) of suitable orders, we have

(i) \( (A^T)^T = A \)

(ii) \( (kA)^T = kA^T \) (where \( k \) is any scalar)

(iii) \( (A + B)^T = A^T + B^T \)

(iv) \( (AB)^T = B^T A^T \) (reversal law on transpose)

### Example 7.12

If \( A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} \) and \( B = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} \), verify

(i) \( (AB)^T = B^T A^T \)

(ii) \( (A + B)^T = A^T + B^T \)

(iii) \( (A - B)^T = A^T - B^T \)

(iv) \( (3A)^T = 3A^T \)

**Solution**

\[
A = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad
B = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
\]
\[
A^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}, \quad
B^T = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix}
\]
\[
AB = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix}, \quad
(AB)^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}
\]
\[
B^T A^T = \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix} = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix}
\]

Thus, (i) is verified.

\[
A + B = \begin{bmatrix} 2 & 2 \\ 3 & 5 \end{bmatrix}, \quad
(A + B)^T = \begin{bmatrix} 2 & 3 \\ 2 & 5 \end{bmatrix}
\]
\[
A^T + B^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix} + \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 2 & 3 \\ 2 & 5 \end{bmatrix}
\]

Thus, (ii) is verified.

\[
A - B = \begin{bmatrix} 0 & 2 \\ 3 & 3 \end{bmatrix}, \quad
(A - B)^T = \begin{bmatrix} 0 & 3 \\ 2 & 3 \end{bmatrix}
\]
\[
A^T - B^T = \begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix} - \begin{bmatrix} 1 & 0 \\ 0 & 1 \end{bmatrix} = \begin{bmatrix} 0 & 3 \\ 2 & 3 \end{bmatrix}
\]

Thus, (iii) is verified.

\[
3A = \begin{bmatrix} 3 & 6 \\ 9 & 12 \end{bmatrix}, \quad
(3A)^T = \begin{bmatrix} 3 & 9 \\ 6 & 12 \end{bmatrix}
\]
\[
3A^T = 3\begin{bmatrix} 1 & 3 \\ 2 & 4 \end{bmatrix} = \begin{bmatrix} 3 & 9 \\ 6 & 12 \end{bmatrix}
\]

Thus, (iv) is verified.

### 7.2.6 Symmetric and Skew-symmetric Matrices

**Definition 7.17**

A square matrix \( A \) is said to be symmetric if \( A^T = A \).

That is, \( A = [a_{ij}]_{n \times n} \) is a symmetric matrix, then \( a_{ij} = a_{ji} \) for all \( i \) and \( j \).

For instance, \( A = \begin{bmatrix} 3 & -6 & 9 \\ -6 & 8 & 5 \\ 9 & 5 & 2 \end{bmatrix} \) is a symmetric matrix since \( A^T = A \).

Observe that transpose of \( A^T \) is the matrix \( A \) itself. That is \( (A^T)^T = A \).

**Definition 7.18**

A square matrix \( A \) is said to be skew-symmetric if \( A^T = -A \).

If \( A = [a_{ij}]_{n \times n} \) is a skew-symmetric matrix, then \( a_{ij} = -a_{ji} \) for all \( i \) and \( j \).

Now, if we put \( i = j \), then \( 2a_{ii} = 0 \) or \( a_{ii} = 0 \) for all \( i \). This means that all the diagonal elements of a skew-symmetric matrix are zero.

For instance, \( A = \begin{bmatrix} 0 & 2 & 3 \\ -2 & 0 & 4 \\ -3 & -4 & 0 \end{bmatrix} \) is a skew-symmetric matrix since \( A^T = -A \).

It is interesting to note that any square matrix can be written as the sum of symmetric and skew-symmetric matrices.

**Theorem 7.1**

For any square matrix \( A \) with real number entries, \( A + A^T \) is a symmetric matrix and \( A - A^T \) is a skew-symmetric matrix.

**Proof**

Let \( B = A + A^T \).

\[
B^T = (A + A^T)^T = A^T + (A^T)^T = A^T + A = A + A^T = B.
\]

This implies \( A + A^T \) is a symmetric matrix.

Next, we let \( C = A - A^T \). Then we see that

\[
C^T = (A + (-A^T))^T = A^T + (-A^T)^T = A^T - (A^T)^T = A^T - A = -(A - A^T) = -C
\]

This implies \( A - A^T \) is a skew-symmetric matrix.

**Theorem 7.2**

Any square matrix can be expressed as the sum of a symmetric matrix and a skew-symmetric matrix.

**Proof**

Let \( A \) be a square matrix. Then, we can write

\[
A = \frac{1}{2}(A + A^T) + \frac{1}{2}(A - A^T).
\]

From Theorem 7.1, it follows that \( (A + A^T) \) and \( (A - A^T) \) are symmetric and skew-symmetric matrices respectively. Since \( (kA)^T = kA^T \), it follows that \( \frac{1}{2}(A + A^T) \) and \( \frac{1}{2}(A - A^T) \) are symmetric and skew-symmetric matrices, respectively. Now, the desired result follows.

A matrix which is both symmetric and skew-symmetric is a zero matrix.

### Example 7.13

Express the matrix \( A = \begin{bmatrix} 1 & 3 & 5 \\ -6 & 8 & 3 \\ -4 & 6 & 5 \end{bmatrix} \) as the sum of a symmetric and a skew-symmetric matrices.

**Solution**

\[
A^T = \begin{bmatrix}
1 & -6 & -4 \\
3 & 8 & 6 \\
5 & 3 & 5
\end{bmatrix}
\]

\[
A + A^T = \begin{bmatrix}
2 & -3 & 1 \\
-3 & 16 & 9 \\
1 & 9 & 10
\end{bmatrix}, \quad
P = \frac{1}{2}(A + A^T) = \begin{bmatrix}
1 & -\frac{3}{2} & \frac{1}{2} \\
-\frac{3}{2} & 8 & \frac{9}{2} \\
\frac{1}{2} & \frac{9}{2} & 5
\end{bmatrix}
\]

Thus, \( P = \frac{1}{2}(A + A^T) \) is a symmetric matrix.

\[
A - A^T = \begin{bmatrix}
0 & 9 & 9 \\
-9 & 0 & -3 \\
-9 & 3 & 0
\end{bmatrix}, \quad
Q = \frac{1}{2}(A - A^T) = \begin{bmatrix}
0 & \frac{9}{2} & \frac{9}{2} \\
-\frac{9}{2} & 0 & -\frac{3}{2} \\
-\frac{9}{2} & \frac{3}{2} & 0
\end{bmatrix}
\]

Thus \( Q = \frac{1}{2}(A - A^T) \) is a skew-symmetric matrix.

\[
A = P + Q = \begin{bmatrix}
1 & -\frac{3}{2} & \frac{1}{2} \\
-\frac{3}{2} & 8 & \frac{9}{2} \\
\frac{1}{2} & \frac{9}{2} & 5
\end{bmatrix} + \begin{bmatrix}
0 & \frac{9}{2} & \frac{9}{2} \\
-\frac{9}{2} & 0 & -\frac{3}{2} \\
-\frac{9}{2} & \frac{3}{2} & 0
\end{bmatrix}
\]

Thus \( A \) is expressed as the sum of symmetric and skew-symmetric matrices.

## EXERCISE 7.1

(1) Construct an \( m \times n \) matrix \( A = [a_{ij}] \), where \( a_{ij} \) is given by
    (i) \( a_{ij} = \frac{(i - 2j)^2}{2} \) with \( m = 2, n = 3 \)
    (ii) \( a_{ij} = \frac{|3i - 4j|}{4} \) with \( m = 3, n = 4 \)

(2) Find the values of \( p, q, r, s \) if
    \[
    \begin{bmatrix}
    2 & 3 \\
    1 & 0
    \end{bmatrix} + \begin{bmatrix}
    p & q \\
    r & s
    \end{bmatrix} = \begin{bmatrix}
    3 & 1 \\
    7 & 2
    \end{bmatrix}
    \]

(3) Determine the value of \( x + y \) if
    \[
    \begin{bmatrix}
    2x & 4 \\
    7 & x
    \end{bmatrix} = \begin{bmatrix}
    7 & 7 \\
    13 & x+y
    \end{bmatrix}
    \]

(4) Determine the matrices \( A \) and \( B \) if they satisfy
    \[
    2A + B = \begin{bmatrix} 6 & -6 \\ 0 & 3 \end{bmatrix}, \quad 2B + A = \begin{bmatrix} 8 & 2 \\ -4 & -1 \end{bmatrix}
    \]

(5) If \( A = \begin{bmatrix} 1 & 0 \\ 1 & a \end{bmatrix} \), then compute \( A^4 \).

(6) Consider the matrix \( A_\alpha = \begin{bmatrix} \cos \alpha & -\sin \alpha \\ \sin \alpha & \cos \alpha \end{bmatrix} \)
    (i) Show that \( A_\alpha A_\beta = A_{\alpha + \beta} \).
    (ii) Find all possible real values of \( \alpha \) satisfying the condition \( A_\alpha + A_\alpha^T = I \).

(7) If \( A = \begin{bmatrix} 4 & 2 \\ 1 & x \end{bmatrix} \) and such that \( (A - 2I)(A - 3I) = O \), find the value of \( x \).

(8) If \( A = \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ a & b & -1 \end{bmatrix} \), show that \( A^2 \) is a unit matrix.

(9) If \( A = \begin{bmatrix} 3 & -2 \\ 1 & 0 \\ 2 & 0 \end{bmatrix} \) and \( A^2 + 2A + kI = O \), find the value of \( k \).

(10) Give your own examples of matrices satisfying the following conditions in each case:
    (i) \( A \) and \( B \) such that \( AB \neq BA \).
    (ii) \( A \) and \( B \) such that \( AB = O \) and \( BA \neq O \), \( A \neq O \), \( B \neq O \).
    (iii) \( A \) and \( B \) such that \( AB = O \) and \( BA = O \).

(11) Show that \( f(x)f(y) = f(x+y) \), where \( f(x) = \begin{bmatrix} \cos x & -\sin x & 0 \\ \sin x & \cos x & 0 \\ 0 & 0 & 1 \end{bmatrix} \).

(12) If \( A \) is a square matrix such that \( A^2 = A \), find the value of \( 7A - (I + A)^3 \).

(13) Verify the property \( A(B + C) = AB + AC \), when the matrices \( A, B, \) and \( C \) are given by
    \[
    A = \begin{bmatrix} 3 & -1 & 4 \\ -3 & 2 & 1 \\ 1 & -4 & 5 \end{bmatrix}, \quad
    B = \begin{bmatrix} 7 & -2 \\ 1 & 0 \\ 4 & -5 \end{bmatrix}, \quad
    C = \begin{bmatrix} 2 & 1 \\ -1 & 1 \\ 4 & 2 \end{bmatrix}
    \]

(14) Find the matrix \( A \) which satisfies the matrix relation
    \[
    A \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{bmatrix} = \begin{bmatrix} -7 & -8 & -9 \\ 2 & 4 & 6 \end{bmatrix}.
    \]

(15) If \( A^T = \begin{bmatrix} 4 & 5 \\ -1 & 0 \\ 2 & 3 \end{bmatrix} \) and \( B = \begin{bmatrix} 2 & -1 & 1 \\ 7 & 5 & -2 \end{bmatrix} \), verify the following
    (i) \( (A + B)^T = A^T + B^T = B^T + A^T \)
    (ii) \( (A - B)^T = A^T - B^T \)
    (iii) \( (B^T)^T = B \)

(16) If \( A \) is a \( 3 \times 4 \) matrix and \( B \) is a matrix such that both \( A^T B \) and \( BA^T \) are defined, what is the order of the matrix \( B \)?

(17) Express the following matrices as the sum of a symmetric matrix and a skew-symmetric matrix:
    (i) \( \begin{bmatrix} 4 & -2 \\ 3 & -5 \end{bmatrix} \) and (ii) \( \begin{bmatrix} 3 & 3 & -1 \\ -2 & -2 & 1 \\ -4 & -5 & 2 \end{bmatrix} \).

(18) Find the matrix \( A \) such that
    \[
    \begin{bmatrix} 2 & -1 \\ 1 & 0 \\ -3 & 4 \end{bmatrix} A^T = \begin{bmatrix} -1 & -8 & -10 \\ 1 & 2 & -5 \\ 9 & 22 & 15 \end{bmatrix}.
    \]

(19) If \( A = \begin{bmatrix} 1 & 2 & 2 \\ 2 & 1 & -2 \\ x & 2 & y \end{bmatrix} \) is a matrix such that \( AA^T = 9I \), find the values of \( x \) and \( y \).

(20) (i) For what value of \( x \), the matrix \( A = \begin{bmatrix} 0 & 1 & -2 \\ -1 & 0 & x^3 \\ 2 & -3 & 0 \end{bmatrix} \) is skew-symmetric.
    (ii) If \( \begin{bmatrix} 0 & p & 3 \\ 2 & q^2 & -1 \\ r & 1 & 0 \end{bmatrix} \) is skew-symmetric, find the values of \( p, q, \) and \( r \).

(21) Construct the matrix \( A = [a_{ij}]_{3 \times 3} \), where \( a_{ij} = i - j \). State whether \( A \) is symmetric or skew-symmetric.

(22) Let \( A \) and \( B \) be two symmetric matrices. Prove that \( AB = BA \) if and only if \( AB \) is a symmetric matrix.

(23) If \( A \) and \( B \) are symmetric matrices of same order, prove that
    (i) \( AB + BA \) is a symmetric matrix.
    (ii) \( AB - BA \) is a skew-symmetric matrix.

(24) A shopkeeper in a Nuts and Spices shop makes gift packs of cashew nuts, raisins and almonds. Pack I contains 100 gm of cashew nuts, 100 gm of raisins and 50 gm of almonds. Pack-II contains 200 gm of cashew nuts, 100 gm of raisins and 100 gm of almonds. Pack-III contains 250 gm of cashew nuts, 250 gm of raisins and 150 gm of almonds. The cost of 50 gm of cashew nuts is ₹50, 50 gm of raisins is ₹10, and 50 gm of almonds is ₹60. What is the cost of each gift pack?

## 7.3 Determinants

To every square matrix \( A = [a_{ij}] \) of order \( n \), we can associate a number called determinant of the matrix \( A \).

The determinant of a matrix \( A \) is denoted by \( |A| \) or det \( A \). For example, if \( A = \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix} \), then the determinant of \( A \) is defined as \( |A| = a_{11}a_{22} - a_{21}a_{12} \).

**Note 7.5**

(i) Determinants can be defined only for square matrices.

(ii) For a square matrix \( A \), \( |A| \) is read as determinant of \( A \).

(iii) Matrix is only a representation whereas determinant is a value of a matrix.

### 7.3.1 Determinants of Matrices of different order

#### Determinant of a matrix of order 1

Let \( A = [a] \) be the matrix of order 1, then the determinant of \( A \) is defined as \( a \).

#### Determinant of a matrix of order 2

Let \( A = \begin{bmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{bmatrix} \) be a matrix of order 2. Then the determinant of \( A \) is defined as

\[
|A| = \begin{vmatrix} a_{11} & a_{12} \\ a_{21} & a_{22} \end{vmatrix} = a_{11}a_{22} - a_{21}a_{12}.
\]

### Example 7.14

Evaluate: (i) \( \begin{vmatrix} 2 & 4 \\ -1 & 2 \end{vmatrix} \) (ii) \( \begin{vmatrix} \cos \theta & \sin \theta \\ -\sin \theta & \cos \theta \end{vmatrix} \)

**Solution**

\[
\begin{vmatrix} 2 & 4 \\ -1 & 2 \end{vmatrix} = (2 \times 2) - (-1 \times 4) = 4 + 4 = 8.
\]

\[
\begin{vmatrix} \cos \theta & \sin \theta \\ -\sin \theta & \cos \theta \end{vmatrix} = (\cos \theta \cdot \cos \theta) - (-\sin \theta \cdot \sin \theta) = \cos^2 \theta + \sin^2 \theta = 1.
\]

#### Determinant of a Matrix of order 3

We consider the determinant of a \( 3 \times 3 \) matrix with entries as real numbers or real valued functions defined on \( \mathbb{R} \) and study its properties and discuss various methods of evaluation of certain determinants.

**Definition 7.19**

Let \( A = [a_{ij}]_{3 \times 3} \) be a given square matrix of order 3. The minor of an arbitrary element \( a_{ij} \) is the determinant obtained by deleting the \( i^{\text{th}} \) row and \( j^{\text{th}} \) column in which the element \( a_{ij} \) stands. The minor of \( a_{ij} \) is usually denoted by \( M_{ij} \).

The cofactor is a signed minor. The cofactor of \( a_{ij} \) is usually denoted by \( A_{ij} \) and is defined as \( A_{ij} = (-1)^{i + j} M_{ij} \).

For instance, consider the \( 3 \times 3 \) matrix defined by

\[
A = \begin{bmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{bmatrix}
\]

Then the minors and cofactors of the elements \( a_{11}, a_{12}, a_{13} \) are given as follows:

\[
\text{Minor of } a_{11} \text{ is } M_{11} = \begin{vmatrix} a_{22} & a_{23} \\ a_{32} & a_{33} \end{vmatrix} = a_{22}a_{33} - a_{32}a_{23}
\]
\[
\text{Cofactor of } a_{11} \text{ is } A_{11} = (-1)^{1+1} M_{11} = a_{22}a_{33} - a_{32}a_{23}
\]
\[
\text{Minor of } a_{12} \text{ is } M_{12} = \begin{vmatrix} a_{21} & a_{23} \\ a_{31} & a_{33} \end{vmatrix} = a_{21}a_{33} - a_{31}a_{23}
\]
\[
\text{Cofactor of } a_{12} \text{ is } A_{12} = (-1)^{1+2} M_{12} = -(a_{21}a_{33} - a_{31}a_{23})
\]
\[
\text{Minor of } a_{13} \text{ is } M_{13} = \begin{vmatrix} a_{21} & a_{22} \\ a_{31} & a_{32} \end{vmatrix} = a_{21}a_{32} - a_{31}a_{22}
\]
\[
\text{Cofactor of } a_{13} \text{ is } A_{13} = (-1)^{1+3} M_{13} = a_{21}a_{32} - a_{31}a_{22}
\]

**Result 7.1 (Laplace Expansion)**

For a given matrix \( A = [a_{ij}]_{3 \times 3} \), the sum of the product of elements of the first row with their corresponding cofactors is the determinant of \( A \).

\[
|A| = a_{11}A_{11} + a_{12}A_{12} + a_{13}A_{13}
\]

This can also be written using minors. That is, \( |A| = a_{11}M_{11} - a_{12}M_{12} + a_{13}M_{13} \).

The determinant can be computed by expanding along any row or column and it is important to note that the value in all cases remains the same. For example,

\[
\text{expansion along } R_1 \text{ is } |A| = a_{11}A_{11} + a_{12}A_{12} + a_{13}A_{13}.
\]
\[
\text{along } R_2 \text{ is } |A| = a_{21}A_{21} + a_{22}A_{22} + a_{23}A_{23}.
\]
\[
\text{along } C_1 \text{ is } |A| = a_{11}A_{11} + a_{21}A_{21} + a_{31}A_{31}.
\]

### Example 7.15

Compute all minors, cofactors of \( A \) and hence compute \( |A| \) if \( A = \begin{bmatrix} 1 & 3 & -2 \\ 4 & -5 & 6 \\ -3 & 5 & 2 \end{bmatrix} \). Also check that \( |A| \) remains unaltered by expanding along any row or any column.

**Solution**

The minors are:

\[
M_{11} = \begin{vmatrix} -5 & 6 \\ 5 & 2 \end{vmatrix} = -10 - 30 = -40
\]
\[
M_{12} = \begin{vmatrix} 4 & 6 \\ -3 & 2 \end{vmatrix} = 8 + 18 = 26
\]
\[
M_{13} = \begin{vmatrix} 4 & -5 \\ -3 & 5 \end{vmatrix} = 20 - 15 = 5
\]
\[
M_{21} = \begin{vmatrix} 3 & -2 \\ 5 & 2 \end{vmatrix} = 6 + 10 = 16
\]
\[
M_{22} = \begin{vmatrix} 1 & -2 \\ -3 & 2 \end{vmatrix} = 2 - 6 = -4
\]
\[
M_{23} = \begin{vmatrix} 1 & 3 \\ -3 & 5 \end{vmatrix} = 5 + 9 = 14
\]
\[
M_{31} = \begin{vmatrix} 3 & -2 \\ -5 & 6 \end{vmatrix} = 18 - 10 = 8
\]
\[
M_{32} = \begin{vmatrix} 1 & -2 \\ 4 & 6 \end{vmatrix} = 6 + 8 = 14
\]
\[
M_{33} = \begin{vmatrix} 1 & 3 \\ 4 & -5 \end{vmatrix} = -5 - 12 = -17
\]

The cofactors are:

\[
A_{11} = (-1)^{1+1} M_{11} = -40, \quad A_{12} = (-1)^{1+2} M_{12} = -26, \quad A_{13} = (-1)^{1+3} M_{13} = 5
\]
\[
A_{21} = (-1)^{2+1} M_{21} = -16, \quad A_{22} = (-1)^{2+2} M_{22} = -4, \quad A_{23} = (-1)^{2+3} M_{23} = -14
\]
\[
A_{31} = (-1)^{3+1} M_{31} = 8, \quad A_{32} = (-1)^{3+2} M_{32} = -14, \quad A_{33} = (-1)^{3+3} M_{33} = -17
\]

Now expanding along \( R_1 \):
\[
|A| = a_{11}A_{11} + a_{12}A_{12} + a_{13}A_{13} = 1 \cdot (-40) + 3 \cdot (-26) + (-2) \cdot 5 = -40 - 78 - 10 = -128
\]

Expanding along \( C_1 \):
\[
|A| = a_{11}A_{11} + a_{21}A_{21} + a_{31}A_{31} = 1 \cdot (-40) + 4 \cdot (-16) + (-3) \cdot 8 = -40 - 64 - 24 = -128
\]

Thus the value remains the same.

#### Evaluation of determinant of order 3 by using Sarrus Rule (named after the French Mathematician Pierre Frédéric Sarrus)

Write the entries of Matrix \( A \) as follows:
\[
\begin{vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{vmatrix}
\]

Then \( |A| \) is computed as follows:
\[
|A| = [a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32}] - [a_{33}a_{21}a_{12} + a_{32}a_{23}a_{11} + a_{31}a_{22}a_{13}]
\]

### Example 7.16

Compute the determinant of \( A = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} \) using Sarrus rule.

**Solution**

\[
|A| = [1 \cdot 5 \cdot 9 + 2 \cdot 6 \cdot 7 + 3 \cdot 4 \cdot 8] - [9 \cdot 4 \cdot 2 + 8 \cdot 6 \cdot 1 + 7 \cdot 5 \cdot 3]
\]
\[
= [45 + 84 + 96] - [72 + 48 + 105] = 225 - 225 = 0
\]

### Example 7.17

Compute \( |A| \) using Sarrus rule if \( A = \begin{bmatrix} 3 & 4 & 1 \\ 0 & -1 & 2 \\ 5 & -2 & 6 \end{bmatrix} \).

**Solution**

\[
|A| = [3 \cdot (-1) \cdot 6 + 4 \cdot 2 \cdot 5 + 1 \cdot 0 \cdot (-2)] - [6 \cdot 0 \cdot 4 + (-2) \cdot 2 \cdot 3 + 5 \cdot (-1) \cdot 1]
\]
\[
= [-18 + 40 + 0] - [0 - 12 - 5] = 22 + 17 = 39
\]

**Note 7.6**

For easier calculations, we expand the determinant along a row or column which contains maximum number of zeros.

### 7.3.2 Properties of Determinants

We can use one or more of the following properties of the determinants to simplify the evaluation of determinants.

**Property 1**

The determinant of a matrix remains unaltered if its rows are changed into columns and columns into rows. That is, \( |A| = |A^T| \).

Since the row-wise expansion is same as the column-wise expansion, the result holds good.

**Property 2**

If any two rows/columns of a determinant are interchanged, then the determinant changes in sign but its absolute value remains unaltered.

**Verification**

Let \( |A| = \begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} \). Interchanging second and third rows, we get

\[
|A_1| = \begin{vmatrix} a_1 & b_1 & c_1 \\ a_3 & b_3 & c_3 \\ a_2 & b_2 & c_2 \end{vmatrix} = -|A|
\]

Therefore, the property is verified.

**Property 3**

If there are \( n \) interchanges of rows (columns) of a matrix \( A \) then the determinant of the resulting matrix is \( (-1)^n |A| \).

**Property 4**

If two rows (columns) of a matrix are identical, then its determinant is zero.

**Verification**

Let \( |A| = \begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_2 & b_2 & c_2 \end{vmatrix} \), with 2nd and 3rd rows identical. Interchanging second and third rows, we get \( -|A| = |A| \Rightarrow 2|A| = 0 \Rightarrow |A| = 0 \).

**Property 5**

If a row (column) of a matrix \( A \) is a scalar multiple of another row (or column) of \( A \), then its determinant is zero.

**Note 7.8**

(i) If all entries of a row or a column are zero, then the determinant is zero.

(ii) The determinant of a triangular matrix is obtained by the product of the principal diagonal elements.

**Property 6**

If each element in a row (or column) of a matrix is multiplied by a scalar \( k \), then the determinant is multiplied by the same scalar \( k \).

**Verification**

Let \( |A| = \begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} \). Multiply the first row by \( k \):

\[
\begin{vmatrix} ka_1 & kb_1 & kc_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} = k \begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} = k|A|
\]

Therefore the property is verified.

**Note 7.9**

If \( A \) is a square matrix of order \( n \), then

\[
(i) |AB| = |A| |B|
\]
\[
(ii) \text{if } AB = O \text{ then either } |A| = 0 \text{ or } |B| = 0.
\]
\[
(iii) |A^n| = (|A|)^n
\]

**Property 7**

If each element of a row (or column) of a determinant is expressed as sum of two or more terms then the whole determinant is expressed as sum of two or more determinants.

\[
\begin{vmatrix}
a_1 + m_1 & b_1 & c_1 \\
a_2 + m_2 & b_2 & c_2 \\
a_3 + m_3 & b_3 & c_3
\end{vmatrix} = 
\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3
\end{vmatrix} +
\begin{vmatrix}
m_1 & b_1 & c_1 \\
m_2 & b_2 & c_2 \\
m_3 & b_3 & c_3
\end{vmatrix}
\]

**Verification**

By taking first column expansion it can be verified easily.

**Property 8**

If, to each element of any row (column) of a determinant the equi-multiples of the corresponding entries of one or more rows (columns) are added or subtracted, then the value of the determinant remains unchanged.

**Verification**

Let \( |A| = \begin{vmatrix} a_1 & b_1 & c_1 \\ a_2 & b_2 & c_2 \\ a_3 & b_3 & c_3 \end{vmatrix} \). Apply \( R_1 \to R_1 + kR_2 + lR_3 \). Then the new matrix is

\[
\begin{vmatrix}
a_1 + ka_2 + la_3 & b_1 + kb_2 + lb_3 & c_1 + kc_2 + lc_3 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3
\end{vmatrix}
\]

This determinant can be expressed as the sum of three determinants. By Property 4, each determinant with a multiple of one row added to another gives zero. Hence, the value remains unchanged.

### Example 7.18

If \( a, b, c \) and \( x \) are positive real numbers, then show that
\[
\begin{vmatrix}
(a^x + a^{-x})^2 & (a^x - a^{-x})^2 & 1 \\
(b^x + b^{-x})^2 & (b^x - b^{-x})^2 & 1 \\
(c^x + c^{-x})^2 & (c^x - c^{-x})^2 & 1
\end{vmatrix} = 0.
\]

**Solution**

Applying \( C_1 \to C_1 - C_2 \), we get
\[
\begin{vmatrix}
4 & (a^x - a^{-x})^2 & 1 \\
4 & (b^x - b^{-x})^2 & 1 \\
4 & (c^x - c^{-x})^2 & 1
\end{vmatrix}
\]
Here \( C_1 \) and \( C_3 \) are proportional (each element in \( C_1 \) is 4 and each element in \( C_3 \) is 1). Therefore the determinant is zero.

### Example 7.19

Without expanding the determinants, show that \( |B| = 2|A| \).

Where \( B = \begin{bmatrix} b+c & c+a & a+b \\ c+a & a+b & b+c \\ a+b & b+c & c+a \end{bmatrix} \) and \( A = \begin{bmatrix} a & b & c \\ b & c & a \\ c & a & b \end{bmatrix} \).

**Solution**

We have \( |B| = \begin{vmatrix} b+c & c+a & a+b \\ c+a & a+b & b+c \\ a+b & b+c & c+a \end{vmatrix} \)

Apply \( R_1 \to R_1 + R_2 + R_3 \):
\[
= \begin{vmatrix}
2(a+b+c) & 2(a+b+c) & 2(a+b+c) \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{vmatrix}
\]
\[
= 2(a+b+c) \begin{vmatrix}
1 & 1 & 1 \\
c+a & a+b & b+c \\
a+b & b+c & c+a
\end{vmatrix}
\]

Now apply \( C_2 \to C_2 - C_1 \) and \( C_3 \to C_3 - C_1 \):
\[
= 2(a+b+c) \begin{vmatrix}
1 & 0 & 0 \\
c+a & (a+b)-(c+a) & (b+c)-(c+a) \\
a+b & (b+c)-(a+b) & (c+a)-(a+b)
\end{vmatrix}
\]
\[
= 2(a+b+c) \begin{vmatrix}
1 & 0 & 0 \\
c+a & a+b-c-a & b+c-c-a \\
a+b & b+c-a-b & c+a-a-b
\end{vmatrix}
\]
\[
= 2(a+b+c) \begin{vmatrix}
1 & 0 & 0 \\
c+a & b-c & b-a \\
a+b & c-a & c-b
\end{vmatrix}
\]

Expanding along \( R_1 \):
\[
= 2(a+b+c) \begin{vmatrix} b-c & b-a \\ c-a & c-b \end{vmatrix}
\]
\[
= 2(a+b+c)[(b-c)(c-b) - (b-a)(c-a)]
\]
\[
= 2(a+b+c)[-(b-c)^2 - (b-a)(c-a)]
\]

Now consider \( |A| = \begin{vmatrix} a & b & c \\ b & c & a \\ c & a & b \end{vmatrix} \). It can be shown that
\[
|A| = (a+b+c)(ab+bc+ca - a^2 - b^2 - c^2)
\]
Thus, \( |B| = 2|A| \).

### Example 7.20

Evaluate \( \begin{vmatrix} 2014 & 2017 & 0 \\ 2020 & 2023 & 1 \\ 2023 & 2026 & 0 \end{vmatrix} \).

**Solution**

\[
\begin{vmatrix}
2014 & 2017 & 0 \\
2020 & 2023 & 1 \\
2023 & 2026 & 0
\end{vmatrix} = 1 \cdot \begin{vmatrix}
2014 & 2017 \\
2023 & 2026
\end{vmatrix} - 0 + 0 = 2014 \cdot 2026 - 2023 \cdot 2017
\]
\[
= (2014 \times 2026) - (2023 \times 2017)
\]

Let \( 2014 = a \). Then 2017 = a+3, 2020 = a+6, 2023 = a+9, 2026 = a+12.

Then the determinant becomes:
\[
a(a+12) - (a+9)(a+3) = a^2 + 12a - (a^2 + 12a + 27) = -27
\]

### Example 7.21

Find the value of \( x \) if \( \begin{vmatrix} x-1 & x & x-2 \\ 0 & x-2 & x-3 \\ 0 & 0 & x-3 \end{vmatrix} = 0 \).

**Solution**

Since all the entries below the principal diagonal are zero, the value of the determinant is \( (x-1)(x-2)(x-3) = 0 \) which gives \( x = 1, 2, 3 \).

### Example 7.22

Prove that \( \begin{vmatrix} 1 & 1 & 1 \\ x & y & z \\ x^2 & y^2 & z^2 \end{vmatrix} = (x-y)(y-z)(z-x) \).

**Solution**

Applying \( C_2 \to C_2 - C_1 \), \( C_3 \to C_3 - C_1 \), we get

\[
\begin{vmatrix}
1 & 0 & 0 \\
x & y-x & z-x \\
x^2 & y^2 - x^2 & z^2 - x^2
\end{vmatrix}
\]
\[
= (y-x)(z-x) \begin{vmatrix}
1 & 0 & 0 \\
x & 1 & 1 \\
x^2 & y+x & z+x
\end{vmatrix}
\]
\[
= (y-x)(z-x)[1 \cdot (1 \cdot (z+x) - 1 \cdot (y+x)) - 0 + 0]
\]
\[
= (y-x)(z-x)(z-y) = (x-y)(y-z)(z-x)
\]

## EXERCISE 7.2

(1) Without expanding the determinant, prove that
    \[
    \begin{vmatrix}
    s & a^2 & b^2 + c^2 \\
    s & b^2 & c^2 + a^2 \\
    s & c^2 & a^2 + b^2
    \end{vmatrix} = 0.
    \]

(2) Show that
    \[
    \begin{vmatrix}
    b+c & bc & b^2c^2 \\
    c+a & ca & c^2a^2 \\
    a+b & ab & a^2b^2
    \end{vmatrix} = 0.
    \]

(3) Prove that
    \[
    \begin{vmatrix}
    a^2 & bc & ac + c^2 \\
    a^2 + ab & b^2 & ac \\
    ab & b^2 + bc & c^2
    \end{vmatrix} = 4a^2b^2c^2.
    \]

(4) Prove that
    \[
    \begin{vmatrix}
    \sec^2 \theta & \tan^2 \theta & 1 \\
    \tan^2 \theta & \sec^2 \theta & -1 \\
    38 & 36 & 2
    \end{vmatrix} = 0.
    \]

(5) Show that
    \[
    \begin{vmatrix}
    x+a & y+b & z+c \\
    x & y & z \\
    a & b & c
    \end{vmatrix} = 0.
    \]

(6) Write the general form of a \(3 \times 3\) skew-symmetric matrix and prove that its determinant is 0.

(7) If
    \[
    \begin{vmatrix}
    0 & a & b \\
    -a & 0 & c \\
    -b & -c & 0
    \end{vmatrix} = \alpha + \begin{vmatrix}
    a & b & c \\
    b & c & a \\
    c & a & b
    \end{vmatrix},
    \]
    prove that \( a, b, c \) are in G.P. or \( a \) is a root of \( ax^2 + 2bx + c = 0 \).

(8) Prove that
    \[
    \begin{vmatrix}
    1 & a & a^2 - bc \\
    1 & b & b^2 - ca \\
    1 & c & c^2 - ab
    \end{vmatrix} = 0.
    \]

(9) If \( a, b, c \) are \( p^{th} \), \( q^{th} \) and \( r^{th} \) terms of an A.P., find the value of
    \[
    \begin{vmatrix}
    a & b & c \\
    p & q & r \\
    1 & 1 & 1
    \end{vmatrix}.
    \]

(10) Show that
    \[
    \begin{vmatrix}
    a^2 + x^2 & ab & ac \\
    ab & b^2 + x^2 & bc \\
    ac & bc & c^2 + x^2
    \end{vmatrix}
    \]
    is divisible by \( x^4 \).

(11) If \( a, b, c \) are all positive, and are \( p^{th} \), \( q^{th} \) and \( r^{th} \) terms of a G.P., show that
    \[
    \begin{vmatrix}
    \log a & p & 1 \\
    \log b & q & 1 \\
    \log c & r & 1
    \end{vmatrix} = 0.
    \]

(12) Find the value of
    \[
    \begin{vmatrix}
    1 & \log_x y & \log_x z \\
    \log_y x & 1 & \log_y z \\
    \log_z x & \log_z y & 1
    \end{vmatrix}
    \]
    if \( x, y, z \neq 1 \).

(13) If \( A = \begin{bmatrix} 1 & \alpha \\ 2 & 1 \\ 0 & \frac{1}{2} \end{bmatrix} \), prove that \( \sum_{k=1}^n \det(A^k) = \frac{1}{3}\left(1 - \frac{1}{4^n}\right) \).

(14) Without expanding, evaluate the following determinants:
    \[
    \begin{vmatrix}
    1 & a & a^2 \\
    1 & b & b^2 \\
    1 & c & c^2
    \end{vmatrix}
    \]

(15) If \( A \) is a square matrix and \( |A| = 2 \), find the value of \( |AA^T| \).

(16) If \( A \) and \( B \) are square matrices of order 3 such that \( |A| = -1 \) and \( |B| = 3 \), find the value of \( |3AB| \).

(17) If \( \lambda = -2 \), determine the value of
    \[
    \begin{vmatrix}
    0 & 2\lambda & 1 \\
    \lambda^2 & 0 & 3\lambda^2 + 1 \\
    -1 & 6\lambda - 1 & 0
    \end{vmatrix}.
    \]

(18) Determine the roots of the equation
    \[
    \begin{vmatrix}
    1 & 4 & 20 \\
    1 & -2 & 5 \\
    1 & 2x & 5x^2
    \end{vmatrix} = 0.
    \]

(19) Verify that \( \det(AB) = (\det A)(\det B) \) for
    \[
    A = \begin{bmatrix} 4 & 3 & -2 \\ 1 & 0 & 7 \\ 2 & 3 & -5 \end{bmatrix}, \quad
    B = \begin{bmatrix} 1 & 3 & 3 \\ -2 & 4 & 0 \\ 9 & 7 & 5 \end{bmatrix}.
    \]

(20) Using cofactors of elements of second row, evaluate \( |A| \), where
    \[
    A = \begin{bmatrix} 5 & 3 & 8 \\ 2 & 0 & 1 \\ 1 & 2 & 3 \end{bmatrix}.
    \]

### 7.3.3 Application of Factor Theorem to Determinants

**Theorem 7.3 (Factor Theorem)**

If each element of a matrix \( A \) is a polynomial in \( x \) and if \( |A| \) vanishes for \( x = a \), then \( (x - a) \) is a factor of \( |A| \).

**Note 7.10**

(i) This theorem is very much useful when we have to obtain the value of the determinant in 'factors' form.

(ii) If we substitute \( b \) for \( a \) in the determinant \( |A| \), any two of its rows or columns become identical, then \( |A| = 0 \), and hence by factor theorem \( (a - b) \) is a factor of \( |A| \).

(iii) If \( r \) rows (columns) are identical in a determinant of order \( n \) (\( n \geq r \)), when we put \( x = a \), then \( (x - a)^{r-1} \) is a factor of \( |A| \).

(iv) A square matrix (or its determinant) is said to be in cyclic symmetric form if each row is obtained from the first row by changing the variables cyclically.

(v) If the determinant is in cyclic symmetric form and if \( m \) is the difference between the degree of the product of the factors (obtained by substitution) and the degree of the product of the leading diagonal elements, then
    - if \( m \) is zero, the required factor is a constant \( k \)
    - if \( m \) is 1, the required factor is \( k(a + b + c) \)
    - if \( m \) is 2, the required factor is \( k(a^2 + b^2 + c^2) + l(ab + bc + ca) \).

### Example 7.23

Using Factor Theorem, prove that
\[
\begin{vmatrix}
x+1 & 3 & 5 \\
2 & x+2 & 5 \\
2 & 3 & x+4
\end{vmatrix} = (x-1)^2(x+9).
\]

**Solution**

Let \( |A| = \begin{vmatrix} x+1 & 3 & 5 \\ 2 & x+2 & 5 \\ 2 & 3 & x+4 \end{vmatrix} \).

Put \( x = 1 \):
\[
|A| = \begin{vmatrix} 2 & 3 & 5 \\ 2 & 3 & 5 \\ 2 & 3 & 5 \end{vmatrix} = 0
\]
Since all the three rows are identical, \( (x-1)^2 \) is a factor of \( |A| \).

Now put \( x = -9 \):
\[
|A| = \begin{vmatrix} -8 & 3 & 5 \\ 2 & -7 & 5 \\ 2 & 3 & -5 \end{vmatrix}
\]
Apply \( C_1 \to C_1 + C_2 + C_3 \):
\[
= \begin{vmatrix} 0 & 3 & 5 \\ 0 & -7 & 5 \\ 0 & 3 & -5 \end{vmatrix} = 0
\]
Therefore \( (x+9) \) is a factor of \( |A| \).

The product \( (x-1)^2(x+9) \) is a factor of \( |A| \). Now the determinant is a cubic polynomial in \( x \). Therefore the remaining factor must be a constant \( k \).

\[
|A| = k(x-1)^2(x+9)
\]
Expanding \( |A| \) and comparing coefficients of \( x^3 \), we get \( k = 1 \). Thus \( |A| = (x-1)^2(x+9) \).

### Example 7.24

Prove that
\[
\begin{vmatrix}
1 & x^2 & x^3 \\
1 & y^2 & y^3 \\
1 & z^2 & z^3
\end{vmatrix} = (x-y)(y-z)(z-x)(xy + yz + zx).
\]

**Solution**

Put \( x = y \):
\[
\begin{vmatrix}
1 & y^2 & y^3 \\
1 & y^2 & y^3 \\
1 & z^2 & z^3
\end{vmatrix} = 0
\]
Therefore \( (x-y) \) is a factor.

The given determinant is in cyclic symmetric form in \( x, y \) and \( z \). Therefore \( (y-z) \) and \( (z-x) \) are also factors.

The degree of the product of the factors \( (x-y)(y-z)(z-x) \) is 3 and the degree of the product of the leading diagonal elements \( 1 \times y^2 \times z^3 \) is 5.

Therefore the other factor is \( k(x^2 + y^2 + z^2) + l(xy + yz + zx) \).

Thus,
\[
\begin{vmatrix}
1 & x^2 & x^3 \\
1 & y^2 & y^3 \\
1 & z^2 & z^3
\end{vmatrix} = [k(x^2+y^2+z^2) + l(xy+yz+zx)] \times (x-y)(y-z)(z-x)
\]

Taking suitable values for \( x, y, z \) and solving, we get \( k = 0, l = 1 \). Hence the result.

### Example 7.25

Prove that
\[
\begin{vmatrix}
(q+r)^2 & p^2 & p^2 \\
q^2 & (r+p)^2 & q^2 \\
r^2 & r^2 & (p+q)^2
\end{vmatrix} = 2pqr(p+q+r)^3.
\]

**Solution**

Taking \( p = 0 \), we get
\[
|A| = \begin{vmatrix}
(q+r)^2 & 0 & 0 \\
q^2 & r^2 & q^2 \\
r^2 & r^2 & q^2
\end{vmatrix} = 0
\]
Therefore \( p \) is a factor.

Since \( |A| \) is in cyclic symmetric form in \( p, q, r \), \( q \) and \( r \) are also factors.

Putting \( p+q+r = 0 \), we get \( q+r = -p, r+p = -q, p+q = -r \). Then
\[
|A| = \begin{vmatrix}
(-p)^2 & p^2 & p^2 \\
q^2 & (-q)^2 & q^2 \\
r^2 & r^2 & (-r)^2
\end{vmatrix} = \begin{vmatrix}
p^2 & p^2 & p^2 \\
q^2 & q^2 & q^2 \\
r^2 & r^2 & r^2
\end{vmatrix} = 0
\]
Therefore \( (p+q+r)^2 \) is a factor.

The degree of the obtained factor \( pqr(p+q+r)^2 \) is 5. The degree of \( |A| \) is 6. Therefore the required factor is \( k(p+q+r) \).

Thus,
\[
|A| = k \cdot pqr(p+q+r)^3
\]

Taking \( p = 1, q = 1, r = 1 \), we get
\[
\begin{vmatrix}
4 & 1 & 1 \\
1 & 4 & 1 \\
1 & 1 & 4
\end{vmatrix} = k \cdot 1 \cdot 1 \cdot 1 \cdot (3)^3
\]
\[
4(16-1) - 1(4-1) + 1(1-4) = 4(15) - 3 - 3 = 60 - 6 = 54
\]
\[
54 = 27k \Rightarrow k = 2
\]
Thus \( |A| = 2pqr(p+q+r)^3 \).

### Example 7.26

If
\[
\begin{vmatrix}
\sin A & \cos A & \sin A + \cos B \\
\sin B & \cos A & \sin B + \cos B \\
\sin C & \cos A & \sin C + \cos B
\end{vmatrix} = 0,
\]
prove that \( \triangle ABC \) is an isosceles triangle.

**Solution**

By putting \( \sin A = \sin B \), the first and second rows become identical. Hence the determinant becomes zero. Therefore \( \sin A = \sin B \) or \( A = B \) or \( A = \pi - B \) (not possible for angles of a triangle). So \( A = B \).

Similarly by putting \( \sin B = \sin C \) and \( \sin C = \sin A \), the given equation is satisfied.

Thus, we have \( A = B \) or \( B = C \) or \( C = A \).

In all cases at least two angles are equal. Thus the triangle is isosceles.

## EXERCISE 7.3

Solve the following problems by using Factor Theorem:

(1) Show that
    \[
    \begin{vmatrix}
    x & a & a \\
    a & x & a \\
    a & a & x
    \end{vmatrix} = (x-a)^2(x+2a).
    \]

(2) Show that
    \[
    \begin{vmatrix}
    b+c & a-c & a-b \\
    b-c & c+a & b-a \\
    c-b & c-a & a+b
    \end{vmatrix} = 8abc.
    \]

(3) Solve
    \[
    \begin{vmatrix}
    x+a & b & c \\
    a & x+b & c \\
    a & b & x+c
    \end{vmatrix} = 0.
    \]

(4) Show that
    \[
    \begin{vmatrix}
    b+c & a & a^2 \\
    c+a & b & b^2 \\
    a+b & c & c^2
    \end{vmatrix} = (a+b+c)(a-b)(b-c)(c-a).
    \]

(5) Solve
    \[
    \begin{vmatrix}
    4-x & 4+x & 4+x \\
    4+x & 4-x & 4+x \\
    4+x & 4+x & 4-x
    \end{vmatrix} = 0.
    \]

(6) Show that
    \[
    \begin{vmatrix}
    1 & 1 & 1 \\
    x & y & z \\
    x^2 & y^2 & z^2
    \end{vmatrix} = (x-y)(y-z)(z-x).
    \]

### 7.3.4 Product of Determinants

While multiplying two matrices "row-by-column" rule alone can be followed. The process of interchanging the rows and columns will not affect the value of the determinant (by Property 1). Therefore we can also adopt the following procedures for multiplication of two determinants.

(i) Row by column multiplication rule

(ii) Row by row multiplication rule

(iii) Column by column multiplication rule

(iv) Column by row multiplication rule

**Note 7.11**

(i) If \( A \) and \( B \) are square matrices of the same order \( n \), then \( |AB| = |A| |B| \) holds.

(ii) In matrices, although \( AB \neq BA \) in general, we do have \( |AB| = |BA| \) always.

### Example 7.27

Verify that \( |AB| = |A| |B| \) if
\[
A = \begin{bmatrix} \cos \theta & -\sin \theta \\ \sin \theta & \cos \theta \end{bmatrix}, \quad
B = \begin{bmatrix} \cos \theta & \sin \theta \\ -\sin \theta & \cos \theta \end{bmatrix}.
\]

**Solution**

\[
AB = \begin{bmatrix}
\cos \theta & -\sin \theta \\
\sin \theta & \cos \theta
\end{bmatrix}
\begin{bmatrix}
\cos \theta & \sin \theta \\
-\sin \theta & \cos \theta
\end{bmatrix}
= \begin{bmatrix}
\cos^2 \theta + \sin^2 \theta & \cos \theta \sin \theta - \sin \theta \cos \theta \\
\sin \theta \cos \theta - \cos \theta \sin \theta & \sin^2 \theta + \cos^2 \theta
\end{bmatrix}
= \begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
\]
\[
|AB| = 1
\]

\[
|A| = \cos^2 \theta + \sin^2 \theta = 1, \quad |B| = \cos^2 \theta + \sin^2 \theta = 1
\]
\[
|A||B| = 1
\]
Thus \( |AB| = |A||B| \).

### Example 7.28

Show that
\[
\begin{vmatrix}
c^2 + b^2 & ab & ac \\
ab & c^2 + a^2 & bc \\
ac & bc & a^2 + b^2
\end{vmatrix} = \begin{vmatrix}
0 & c & b \\
c & 0 & a \\
b & a & 0
\end{vmatrix}^2.
\]

**Solution**

LHS = \( \begin{vmatrix} c^2 + b^2 & ab & ac \\ ab & c^2 + a^2 & bc \\ ac & bc & a^2 + b^2 \end{vmatrix} \)

Consider \( \begin{vmatrix} 0 & c & b \\ c & 0 & a \\ b & a & 0 \end{vmatrix} \times \begin{vmatrix} 0 & c & b \\ c & 0 & a \\ b & a & 0 \end{vmatrix} = \begin{vmatrix} 0 \cdot 0 + c \cdot c + b \cdot b & 0 \cdot c + c \cdot 0 + b \cdot a & 0 \cdot b + c \cdot a + b \cdot 0 \\ c \cdot 0 + 0 \cdot c + a \cdot b & c \cdot c + 0 \cdot 0 + a \cdot a & c \cdot b + 0 \cdot a + a \cdot 0 \\ b \cdot 0 + a \cdot c + 0 \cdot b & b \cdot c + a \cdot 0 + 0 \cdot a & b \cdot b + a \cdot a + 0 \cdot 0 \end{vmatrix} \)

This product equals the given determinant. Hence the result.

### Example 7.29

Show that
\[
\begin{vmatrix}
bc & a^2 & a^2 \\
b^2 & ca & b^2 \\
c^2 & c^2 & ab
\end{vmatrix} = \begin{vmatrix}
a & b & c \\
b & c & a \\
c & a & b
\end{vmatrix}^2.
\]

**Solution**

RHS = \( \begin{vmatrix} a & b & c \\ b & c & a \\ c & a & b \end{vmatrix} \times \begin{vmatrix} a & b & c \\ b & c & a \\ c & a & b \end{vmatrix} \)

By multiplication, we obtain the given LHS. Hence proved.

### 7.3.5 Cofactor Determinant

**Definition 7.20**

Let \( A = [a_{ij}] \) be a square matrix of order \( n \). Then the matrix obtained by replacing every element \( a_{ij} \) by its cofactor is called the cofactor matrix of \( A \).

Let \( A_{ij} \) be the cofactor of \( a_{ij} \). Then the cofactor matrix is \( \begin{bmatrix} A_{11} & A_{12} & \cdots & A_{1n} \\ A_{21} & A_{22} & \cdots & A_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ A_{n1} & A_{n2} & \cdots & A_{nn} \end{bmatrix} \).

### Example 7.31

If \( A_i, B_i, C_i \) are the cofactors of \( a_i, b_i, c_i \), respectively, \( i = 1 \) to 3 in
\[
\Delta = \begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3
\end{vmatrix},
\]
then find the value of \( \begin{vmatrix} A_1 & B_1 & C_1 \\ A_2 & B_2 & C_2 \\ A_3 & B_3 & C_3 \end{vmatrix} \).

**Solution**

Consider the product
\[
\begin{vmatrix}
a_1 & b_1 & c_1 \\
a_2 & b_2 & c_2 \\
a_3 & b_3 & c_3
\end{vmatrix}
\begin{vmatrix}
A_1 & B_1 & C_1 \\
A_2 & B_2 & C_2 \\
A_3 & B_3 & C_3
\end{vmatrix}
=
\begin{vmatrix}
a_1A_1 + b_1A_2 + c_1A_3 & a_1B_1 + b_1B_2 + c_1B_3 & a_1C_1 + b_1C_2 + c_1C_3 \\
a_2A_1 + b_2A_2 + c_2A_3 & a_2B_1 + b_2B_2 + c_2B_3 & a_2C_1 + b_2C_2 + c_2C_3 \\
a_3A_1 + b_3A_2 + c_3A_3 & a_3B_1 + b_3B_2 + c_3B_3 & a_3C_1 + b_3C_2 + c_3C_3
\end{vmatrix}
\]

Since \( \sum a_i A_j = \Delta \) if \( i = j \) and 0 if \( i \neq j \), the product matrix becomes
\[
\begin{bmatrix}
\Delta & 0 & 0 \\
0 & \Delta & 0 \\
0 & 0 & \Delta
\end{bmatrix}
\]
Thus, \( \Delta \cdot \begin{vmatrix} A_1 & B_1 & C_1 \\ A_2 & B_2 & C_2 \\ A_3 & B_3 & C_3 \end{vmatrix} = \Delta^3 \). Therefore,
\[
\begin{vmatrix} A_1 & B_1 & C_1 \\ A_2 & B_2 & C_2 \\ A_3 & B_3 & C_3 \end{vmatrix} = \Delta^2.
\]

### 7.3.6 Area of a Triangle

We know that the area of a triangle whose vertices are \( (x_1, y_1), (x_2, y_2) \) and \( (x_3, y_3) \) is equal to the absolute value of
\[
\frac{1}{2} (x_1 y_2 - x_2 y_1 + x_2 y_3 - x_3 y_2 + x_3 y_1 - x_1 y_3).
\]

This expression can be written in the form of a determinant as the absolute value of
\[
\frac{1}{2} \begin{vmatrix} x_1 & y_1 & 1 \\ x_2 & y_2 & 1 \\ x_3 & y_3 & 1 \end{vmatrix}.
\]

### Example 7.32

If the area of the triangle with vertices \( (-3, 0), (3, 0) \) and \( (0, k) \) is 9 square units, find the values of \( k \).

**Solution**

Area = \( \frac{1}{2} \begin{vmatrix} -3 & 0 & 1 \\ 3 & 0 & 1 \\ 0 & k & 1 \end{vmatrix} = \frac{1}{2} \left| -3(0 \cdot 1 - 1 \cdot k) - 0 + 1(3k - 0) \right| \)
\[
= \frac{1}{2} | -3(-k) + 3k | = \frac{1}{2} | 3k + 3k | = \frac{1}{2} | 6k | = 3|k|
\]

Given area = 9, so \( 3|k| = 9 \Rightarrow |k| = 3 \Rightarrow k = \pm 3 \).

**Note 7.13**

The area of the triangle formed by three points is zero if and only if the three points are collinear. Also, we remind the reader that the determinant could be negative whereas area is always nonnegative.

### Example 7.33

Find the area of the triangle whose vertices are \( (-2, -3), (3, 2) \), and \( (-1, -8) \).

**Solution**

Area = \( \frac{1}{2} \begin{vmatrix} -2 & -3 & 1 \\ 3 & 2 & 1 \\ -1 & -8 & 1 \end{vmatrix} \)
\[
= \frac{1}{2} \left| -2(2 \cdot 1 - 1 \cdot (-8)) - (-3)(3 \cdot 1 - 1 \cdot (-1)) + 1(3 \cdot (-8) - 2 \cdot (-1)) \right|
\]
\[
= \frac{1}{2} \left| -2(2 + 8) + 3(3 + 1) + 1(-24 + 2) \right|
\]
\[
= \frac{1}{2} \left| -2(10) + 3(4) + (-22) \right| = \frac{1}{2} | -20 + 12 - 22 | = \frac{1}{2} | -30 | = 15
\]

Therefore required area is 15 sq.units.

### Example 7.34

Show that the points \( (a, b+c), (b, c+a) \), and \( (c, a+b) \) are collinear.

**Solution**

The area of the triangle formed by these points is
\[
\frac{1}{2} \begin{vmatrix} a & b+c & 1 \\ b & c+a & 1 \\ c & a+b & 1 \end{vmatrix}
\]

Apply \( C_1 \to C_1 + C_2 \):
\[
= \frac{1}{2} \begin{vmatrix} a+b+c & b+c & 1 \\ a+b+c & c+a & 1 \\ a+b+c & a+b & 1 \end{vmatrix} = \frac{a+b+c}{2} \begin{vmatrix} 1 & b+c & 1 \\ 1 & c+a & 1 \\ 1 & a+b & 1 \end{vmatrix}
\]

Since \( C_1 \) and \( C_3 \) are identical, the determinant is zero. Hence the points are collinear.

### 7.3.7 Singular and Non-singular Matrices

**Definition 7.21**

A square matrix \( A \) is said to be singular if \( |A| = 0 \).

A square matrix \( A \) is said to be non-singular if \( |A| \neq 0 \).

For instance, the matrix \( A = \begin{bmatrix} 3 & 8 & 1 \\ -4 & 1 & 1 \\ -4 & 1 & 1 \end{bmatrix} \) is a singular matrix, since
\[
|A| = 3(1-1) - 8(-4+4) + 1(-4+4) = 0.
\]

The matrix \( B = \begin{bmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \\ 7 & 8 & 9 \end{bmatrix} \) is singular because its determinant is zero. The matrix \( C = \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} \) is non-singular because \( |C| = 4 - 6 = -2 \neq 0 \).

**Note 7.14**

If \( A \) and \( B \) are non-singular matrices of the same order then \( AB \) and \( BA \) are also non-singular matrices because \( |AB| = |A| |B| \neq 0 \) and \( |BA| = |B| |A| \neq 0 \).

## EXERCISE 7.4

(1) Find the area of the triangle whose vertices are \( (0,0), (1,2) \) and \( (4,3) \).

(2) If \( (k,2), (2,4) \) and \( (3,2) \) are vertices of the triangle of area 4 square units then determine the value of \( k \).

(3) Identify the singular and non-singular matrices:
    (i) \( \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} \)
    (ii) \( \begin{bmatrix} 2 & 4 \\ 1 & 2 \end{bmatrix} \)
    (iii) \( \begin{bmatrix} 1 & 0 & 0 \\ 0 & 1 & 0 \\ 0 & 0 & 1 \end{bmatrix} \)
    (iv) \( \begin{bmatrix} 1 & 2 & 3 \\ 2 & 4 & 6 \\ 3 & 6 & 9 \end{bmatrix} \)

(4) Determine the values of \( a \) and \( b \) so that the following matrices are singular:
    (i) \( \begin{bmatrix} a & b \\ 3 & 2 \end{bmatrix} \)
    (ii) \( \begin{bmatrix} 1 & 2 & 1 \\ 3 & 4 & 2 \\ 2 & 4 & a \end{bmatrix} \)
    (iii) \( \begin{bmatrix} a & b & 3 \\ 2 & 1 & 4 \\ 1 & 2 & 5 \end{bmatrix} \)

(5) Find the value of the product:
    \[
    \begin{vmatrix} \log_3 64 & \log_4 3 \\ \log_3 8 & \log_4 9 \end{vmatrix} \times \begin{vmatrix} \log_2 3 & \log_3 3 \\ \log_3 4 & \log_3 4 \end{vmatrix}
    \]

## EXERCISE 7.5

Choose the correct or the most suitable answer from the given four alternatives.

(1) If \( a_{ij} = \frac{1}{2}(3i - 2j) \) and \( A = [a_{ij}]_{2 \times 2} \) is
    (1) \( \begin{bmatrix} \frac{1}{2} & -\frac{1}{2} \\ 2 & 1 \end{bmatrix} \)
    (2) \( \begin{bmatrix} \frac{1}{2} & -\frac{1}{2} \\ 2 & 1 \end{bmatrix} \)
    (3) \( \begin{bmatrix} 2 & 1 \\ -\frac{1}{2} & \frac{1}{2} \end{bmatrix} \)
    (4) \( \begin{bmatrix} 2 & -1 \\ 1 & \frac{1}{2} \end{bmatrix} \)

(2) If \( 2X + \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} = \begin{bmatrix} 3 & 8 \\ 7 & 2 \end{bmatrix} \) then matrix \( X \) is
    (1) \( \begin{bmatrix} 1 & 3 \\ 2 & -1 \end{bmatrix} \)
    (2) \( \begin{bmatrix} 4 & 10 \\ 10 & 6 \end{bmatrix} \)
    (3) \( \begin{bmatrix} 2 & 5 \\ 5 & -1 \end{bmatrix} \)
    (4) \( \begin{bmatrix} 1 & 6 \\ 2 & 1 \end{bmatrix} \)

(3) Which one of the following is not true about the matrix \( \begin{bmatrix} 1 & 0 & 0 \\ 0 & 0 & 0 \\ 0 & 0 & 5 \end{bmatrix} \)?
    (1) a scalar matrix
    (2) a diagonal matrix
    (3) an upper triangular matrix
    (4) a lower triangular matrix

(4) If \( A \) and \( B \) are two matrices such that \( A + B \) and \( AB \) are both defined, then
    (1) \( A \) and \( B \) are two matrices not necessarily of same order
    (2) \( A \) and \( B \) are square matrices of same order
    (3) Number of columns of \( A \) is equal to the number of rows of \( B \)
    (4) \( A = B \)

(5) If \( A = \begin{bmatrix} \lambda & 1 \\ -1 & -\lambda \end{bmatrix} \), then for what value of \( \lambda \), \( A^2 = O \)?
    (1) 0
    (2) \( \pm 1 \)
    (3) -1
    (4) 1

(6) If \( A = \begin{bmatrix} 1 & -1 \\ 2 & -1 \end{bmatrix} \), \( B = \begin{bmatrix} a & 1 \\ b & -1 \end{bmatrix} \) and \( (A + B)^2 = A^2 + B^2 \), then the values of \( a \) and \( b \) are
    (1) \( a = 4, b = 1 \)
    (2) \( a = 1, b = 4 \)
    (3) \( a = 0, b = 4 \)
    (4) \( a = 2, b = 4 \)

(7) If \( \begin{bmatrix} 2 & -1 \\ 1 & 0 \\ -3 & 4 \end{bmatrix} A = \begin{bmatrix} -1 & -8 & -10 \\ 1 & 2 & -5 \\ 9 & 22 & 15 \end{bmatrix} \), then the ordered pair \( (a,b) \) is equal to
    (1) \( (2,-1) \)
    (2) \( (-2,1) \)
    (3) \( (2,1) \)
    (4) \( (-2,-1) \)

(8) If \( A \) is a square matrix, then which of the following is not symmetric?
    (1) \( A + A^T \)
    (2) \( AA^T \)
    (3) \( A^T A \)
    (4) \( A - A^T \)

(9) If \( A \) and \( B \) are symmetric matrices of order \( n \), where \( (A \neq B) \), then
    (1) \( A + B \) is skew-symmetric
    (2) \( A + B \) is symmetric
    (3) \( A + B \) is a diagonal matrix
    (4) \( A + B \) is a zero matrix

(10) If \( A = \begin{bmatrix} a & x \\ y & a \end{bmatrix} \) and if \( xy = 1 \), then det \( (AA^T) \) is equal to
    (1) \( (a-1)^2 \)
    (2) \( (a^2+1)^2 \)
    (3) \( a^2-1 \)
    (4) \( (a^2-1)^2 \)

(11) The value of \( x \), for which the matrix \( A = \begin{bmatrix} e^{x-2} & e^{7+x} \\ e^{2+x} & e^{2x+3} \end{bmatrix} \) is singular
    (1) 9
    (2) 8
    (3) 7
    (4) 6

(12) If the points \( (x,-2), (5,2), (8,8) \) are collinear, then \( x \) is equal to
    (1) -3
    (2) \( \frac{1}{3} \)
    (3) 1
    (4) 3

(13) If \( \begin{vmatrix} 2a & x_1 & y_1 \\ 2b & x_2 & y_2 \\ 2c & x_3 & y_3 \end{vmatrix} = \frac{abc}{2} \neq 0 \), then the area of the triangle whose vertices are
    \( \left( \frac{x_1}{a}, \frac{y_1}{a} \right), \left( \frac{x_2}{b}, \frac{y_2}{b} \right), \left( \frac{x_3}{c}, \frac{y_3}{c} \right) \) is
    (1) \( \frac{1}{4} \)
    (2) \( \frac{1}{4} abc \)
    (3) \( \frac{1}{8} \)
    (4) \( \frac{1}{8} abc \)

(14) If the square of the matrix \( \begin{bmatrix} \alpha & \beta \\ \gamma & -\alpha \end{bmatrix} \) is the unit matrix of order 2, then \( \alpha, \beta \) and \( \gamma \) should satisfy the relation
    (1) \( 1 + \alpha^2 + \beta \gamma = 0 \)
    (2) \( 1 - \alpha^2 - \beta \gamma = 0 \)
    (3) \( 1 - \alpha^2 + \beta \gamma = 0 \)
    (4) \( 1 + \alpha^2 - \beta \gamma = 0 \)

(15) If \( \Delta = \begin{vmatrix} a & b & c \\ x & y & z \\ p & q & r \end{vmatrix} \), then \( \begin{vmatrix} ka & kb & kc \\ kx & ky & kz \\ kp & kq & kr \end{vmatrix} \) is
    (1) \( \Delta \)
    (2) \( k\Delta \)
    (3) \( 3k\Delta \)
    (4) \( k^3 \Delta \)

(16) A root of the equation \( \begin{vmatrix} 3-x & -6 & 3 \\ -6 & 3-x & 3 \\ 3 & 3 & -6-x \end{vmatrix} = 0 \) is
    (1) 6
    (2) 3
    (3) 0
    (4) -6

(17) The value of the determinant of \( A = \begin{bmatrix} 0 & a & b \\ -a & 0 & c \\ -b & -c & 0 \end{bmatrix} \) is
    (1) -2abc
    (2) abc
    (3) 0
    (4) \( a^2 + b^2 + c^2 \)

(18) If \( x_1, x_2, x_3 \) as well as \( y_1, y_2, y_3 \) are in geometric progression with the same common ratio, then the points \( (x_1, y_1), (x_2, y_2), (x_3, y_3) \) are
    (1) vertices of an equilateral triangle
    (2) vertices of a right angled triangle
    (3) vertices of a right angled isosceles triangle
    (4) collinear

(19) If [.] denotes the greatest integer less than or equal to the real number under consideration and \( 0 \leq x < 1, 0 \leq y < 1, 0 \leq z < 1 \), then the value of the determinant
    \[
    \begin{vmatrix}
    1 + [x] & [y] & [z] \\
    [x] & 1 + [y] & [z] \\
    [x] & [y] & 1 + [z]
    \end{vmatrix}
    \]
    is
    (1) [z]
    (2) [y]
    (3) [x]
    (4) 1 + [x]

(20) If \( a, b, c \) satisfy \( 3a + 4b + 5c = 0 \), then \( \begin{vmatrix} a & b & c \\ b & c & a \\ c & a & b \end{vmatrix} = \)
    (1) \( a+b+c \)
    (2) 0
    (3) \( 3b \)
    (4) \( ab+bc \)

(21) If \( A = \begin{bmatrix} 1 & 2 & 4 \\ 2 & 4 & 2 \\ 3 & 1 & 0 \end{bmatrix} \) and \( B = \begin{bmatrix} 1 & 2 & 4 \\ 2 & 4 & 2 \\ 3 & 2 & 1 \end{bmatrix} \), then B is given by
    (1) \( B = 4A \)
    (2) \( B = -4A \)
    (3) \( B = -A \)
    (4) \( B = 6A \)

(22) If \( A \) is skew-symmetric of order \( n \) and \( C \) is a column matrix of order \( n \times 1 \), then \( C^T AC \) is
    (1) an identity matrix of order \( n \)
    (2) an identity matrix of order 1
    (3) a zero matrix of order 1
    (4) an identity matrix of order 2

(23) The matrix \( A \) satisfying the equation \( \begin{bmatrix} 1 & 3 \\ 0 & 1 \end{bmatrix} A = \begin{bmatrix} 1 & 1 \\ 0 & -1 \end{bmatrix} \) is
    (1) \( \begin{bmatrix} 1 & 1 \\ 0 & -1 \end{bmatrix} \)
    (2) \( \begin{bmatrix} 1 & 1 \\ 0 & 1 \end{bmatrix} \)
    (3) \( \begin{bmatrix} 1 & -2 \\ 0 & -1 \end{bmatrix} \)
    (4) \( \begin{bmatrix} 1 & 2 \\ 0 & -1 \end{bmatrix} \)

(24) If \( A + I = \begin{bmatrix} 3 & -2 \\ 4 & 1 \end{bmatrix} \), then \( (A + I)(A - I) \) is equal to
    (1) \( \begin{bmatrix} 5 & -4 \\ 8 & 5 \end{bmatrix} \)
    (2) \( \begin{bmatrix} 5 & -4 \\ 4 & 5 \end{bmatrix} \)
    (3) \( \begin{bmatrix} 5 & 4 \\ 8 & 5 \end{bmatrix} \)
    (4) \( \begin{bmatrix} 5 & -4 \\ 8 & -5 \end{bmatrix} \)

(25) Let \( A \) and \( B \) be two symmetric matrices of same order. Then which one of the following statement is not true?
    (1) \( A + B \) is a symmetric matrix
    (2) \( AB \) is a symmetric matrix
    (3) \( AB = (BA)^T \)
    (4) \( A^T B = AB^T \)

## SUMMARY

In this chapter we have acquired the knowledge of

- A matrix is a rectangular array of real numbers or real functions on or complex numbers.
- A matrix having \( m \) rows and \( n \) columns, then the order of the matrix is \( m \times n \).
- A matrix \( A = [a_{ij}]_{m \times n} \) is said to be
    - square matrix if \( m = n \)
    - row matrix if \( m = 1 \)
    - column matrix if \( n = 1 \)
    - zero matrix if \( a_{ij} = 0 \) for all \( i \) and \( j \)
    - diagonal matrix if \( m = n \) and \( a_{ij} = 0 \) for all \( i \neq j \)
    - scalar matrix if \( m = n \) and \( a_{ij} = 0 \) for all \( i \neq j \) and \( a_{ii} = \lambda \) for all \( i \)
    - unit matrix or identity matrix if \( m = n \) and \( a_{ij} = 0 \) for all \( i \neq j \) and \( a_{ii} = 1 \) for all \( i \)
    - upper triangular matrix if \( m = n \) and \( a_{ij} = 0 \) for all \( i > j \)
    - lower triangular matrix if \( m = n \) and \( a_{ij} = 0 \) for all \( i < j \)
- Matrices \( A = [a_{ij}]_{m \times n} \) and \( B = [b_{ij}]_{m \times n} \), are said to be equal if \( a_{ij} = b_{ij} \) for all \( i \) and \( j \).
- If \( A = [a_{ij}]_{m \times n} \) and \( B = [b_{ij}]_{m \times n} \), then \( A + B = [c_{ij}]_{m \times n} \), where \( c_{ij} = a_{ij} + b_{ij} \).
- If \( A = [a_{ij}]_{m \times n} \) and \( \lambda \) is a scalar, then \( \lambda A = [\lambda a_{ij}]_{m \times n} \).
- \( -A = (-1)A \)
- \( A + B = B + A \)
- \( A - B = A + (-1)B \)
- \( (A + B) + C = A + (B + C) \) where \( A, B \) and \( C \) have the same order.
- \( A(BC) = (AB)C \), \( A(B+C) = AB + AC \), \( (A+B)C = AC + BC \).
- The transpose of \( A \), denoted by \( A^T \) is obtained by interchanging rows and columns of \( A \).
    - \( (A^T)^T = A \)
    - \( (kA)^T = kA^T \)
    - \( (A+B)^T = A^T + B^T \)
    - \( (AB)^T = B^T A^T \)
- A square matrix \( A \) is called symmetric if \( A^T = A \) and skew-symmetric if \( A^T = -A \).
- Any square matrix can be expressed as sum of a symmetric and skew-symmetric matrices.
- The diagonal entries of a skew-symmetric matrix must be zero.
- For any square matrix \( A \) with real entries, \( A + A^T \) is symmetric and \( A - A^T \) is skew-symmetric and further \( A = \frac{1}{2}(A + A^T) + \frac{1}{2}(A - A^T) \).
- Determinant is defined only for square matrices.
- \( |A^T| = |A| \).
- \( |AB| = |A| |B| \) where \( A \) and \( B \) are square matrices of same order.
- If \( A = [a_{ij}]_{m \times n} \), then \( |kA| = k^n |A| \), where \( k \) is a scalar.
- A determinant of a square matrix \( A \) is the sum of products of elements of any row (or column) with its corresponding cofactors; for instance, \( |A| = a_{11}A_{11} + a_{12}A_{12} + a_{13}A_{13} \).
- If the elements of a row or column is multiplied by the cofactors of another row or column, then their sum is zero; for example, \( a_{11}A_{13} + a_{12}A_{23} + a_{13}A_{33} = 0 \).
- The determinant value remains unchanged if all its rows are interchanged by its columns.
- If all the elements of a row or a column are zero, then the determinant is zero.
- If any two rows or columns are interchanged, then the determinant changes its sign.
- If any two rows or columns are identical or proportional, then the determinant is zero.
- If each element of a row or a column is multiplied by constant \( k \), then determinant gets multiplied by \( k \).
- If each element in any row (column) is the sum of \( r \) terms, then the determinant can be expressed as the sum of \( r \) determinants.
- A determinant remains unaltered under a row \( (R_i) \) operation of the form \( R_i \to R_i + \alpha R_j + \beta R_k \) or a Column \( (C_i) \) operation of the form \( C_i \to C_i + \alpha C_j + \beta C_k \) where \( \alpha, \beta \) are scalars.
- Factor theorem: If each element of \( |A| \) is a polynomial in \( x \) and if \( |A| \) vanishes for \( x = a \), then \( x - a \) is a factor of \( |A| \).
- Area of the triangle with vertices \( (x_1, y_1), (x_2, y_2) \) and \( (x_3, y_3) \) is given by the absolute value of
    \[
    \frac{1}{2} \begin{vmatrix} x_1 & y_1 & 1 \\ x_2 & y_2 & 1 \\ x_3 & y_3 & 1 \end{vmatrix}.
    \]
    If the area is zero, then the three points are collinear.
- A square matrix \( A \) is said to be singular if \( |A| = 0 \) and non-singular if \( |A| \neq 0 \).
