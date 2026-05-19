---
title: 'vector algebra'
weight: 8
---

# Vector Algebra

> "On earth there is nothing great but man; In man there is nothing great but mind"
>
> — Hamilton

## 8.1 Introduction

A pilot constructing a flight plan has to be concerned about the plane's course, heading, air speed, and ground speed. In order for the plane to proceed directly toward its destination, it must head into the wind at an angle such that the wind is exactly counteracted. If available, a navigation computer will do the calculation quickly and accurately. If, however, a navigation computer is not accessible, the pilot may have to depend on pencil-and-paper work supplemented by a calculator with a knowledge of vectors. An understanding of vectors and their operations is therefore vitally important.

At a certain point during a jump, there are two principal forces acting on a skydiver. One force \( (\vec{g}) \) gravity exerting straight down and another air resistance \( (\vec{r}) \) exerting up as well as to some direction. What is the net force acting on the skydiver? The answer is \( \vec{g} + \vec{r} \). (how?)

Let \( \vec{v} \) be the velocity vector of an aircraft. Suppose that the wind velocity is given by the vector \( \vec{w} \), what is the effective velocity of aircraft? The answer is \( \vec{v} + \vec{w} \). In what direction should the aircraft head in order to fly due west?

A global positioning system (GPS) is a system designed to help to navigate on the earth, in the air and on water. Vectors are also used in GPS.

The development of the concept of vectors was influenced by the works of the German mathematician H.G. Grassmann (1809 - 1877) and the Irish mathematician W.R. Hamilton (1805 - 1865). While Hamilton occupied high positions, Grassman was a secondary school teacher.

The best features of Quaternion Calculus and Cartesian Geometry were united, largely through the efforts of the American Mathematician J.B. Gibbs (1839 - 1903) and Q. Heaviside (1850 - 1925) of England and new subject called Vector Algebra was created. The development of the algebra of vectors and of vector analysis as we know it today was first revealed in sets of remarkable notes made by Gibbs for his students at Yale University. Clifford (1845 - 1879), in his Elements of Dynamics (1878), broke down the product of two quaternions into two very different vector products, which he called the scalar product and the vector product. The term vectors was due to Hamilton and it was derived from the Latin word to carry.

The theory of vector was also based on Grassman's theory of extension.

It was soon realised that vectors would be the ideal tools for the fruitful study of many ideas in geometry and physics. Vectors are now the modern language of a great deal of physics and applied mathematics and they continue to hold their own intrinsic mathematical interest.

## Learning Objectives

On completion of this chapter, the students are expected to

- realise vectors as a tool to study the various geometric and physics problems.
- distinguish the scalars from vectors.
- understand different types of vectors and algebra of vectors.
- understand the geometrical interpretations and resolutions of 2D and 3D vectors.
- appreciate the usage of matrix theory in vector algebra.
- visualise scalar product and vector product yielding scalars and vectors respectively as a unique feature.

## 8.2 Scalars and Vectors

### Definition 8.1

A **scalar** is a quantity that is determined by its magnitude.

For instance, distance, length, speed, temperature, voltage, mass, pressure, and work are scalars.

### Definition 8.2

A **vector** is a quantity that is determined by both its magnitude and its direction and hence it is a directed line segment.

For instance, force, displacement, and velocity (which gives the speed and direction of the motion) are vectors.

We denote vectors by lower case letters with arrow. A two dimensional vector is a directed line segment in \( \mathbb{R}^2 \) and a three dimensional vector is a directed line segment in \( \mathbb{R}^3 \).

## 8.3 Representation of a vector and types of vectors

A vector has a tail and a tip. Consider the diagram as in Fig. 8.1.

**Fig 8.1**

### Definition 8.3

The tail point \( A \) is called the **initial point** and the tip point \( B \) is called the **terminal point** of the vector \( \vec{a} \). The initial point of a vector is also taken as origin of the vector.

The initial point \( A \) of the vector \( \vec{a} \) is the original position of a point and the terminal point \( B \) is its position after the translation.

The length or magnitude of the vector \( \vec{a} \) is the length of the line segment \( AB \) and is denoted by \( |\vec{a}| \).

The undirected line \( AB \) is called the support of the vector \( \vec{a} \). To distinguish between an ordinary line segment without a direction and a line segment representing a vector, we make an arrow mark for the vector as \( \overrightarrow{AB} \) and \( \vec{a} \). So \( AB \) denotes the line segment.

### Definition 8.4

If we have a liberty to choose the origin of the vector at any point then it is said to be **free vector**, whereas if it is restricted to a certain specified point then the vector is said to be **localized vector**.

Upto vector product we will be dealing with free vectors only. Localised vectors are involved in finding equations of straight lines.

### Definition 8.5

**Co-initial vectors** are having the same initial point. On the other hand, the **co-terminus vectors** are having the same terminal point.

### Definition 8.6

Two or more vectors are said to be **collinear** or **parallel** if they have same line of action or have the lines of action parallel to one another.

Two or more vectors are said to be **coplanar** if they lie on the same plane or parallel to the same plane.

### Definition 8.7

Two vectors are said to be **equal** if they have same direction and same magnitude.

Let us note that it is not necessary to have the same initial point and same terminal point for two equal vectors. For instance, in Fig. 8.2, the vectors \( \vec{b} \) and \( \vec{c} \) are equal since they have same direction and same length, whereas \( \vec{a} \) and \( \vec{b} \) are not equal because of opposite direction even though they are having same length. The vectors \( \vec{c} \) and \( \vec{d} \) are not equal even though they are having same direction but not having same length.

**Fig.8.2**

### Definition 8.8

**Zero vector** is a vector which has zero magnitude and an arbitrary direction and it is denoted by \( \vec{0} \).

That is, a vector whose initial and terminal points are coincident is called a zero vector.

We observe that the initial and terminal points of a zero vector are the same. The zero vector is also called null vector or void vector.

A vector of magnitude 1 is called a **unit vector**. The unit vector in the direction of \( \vec{a} \) is denoted by \( \hat{a} \) (read as '\( a \) cap' or '\( a \) hat'). Clearly \( |\hat{a}| = 1 \).

We observe that there are infinitely many directions and hence there are infinitely many unit vectors. In fact, for each direction there is one unit vector in that direction.

Any non-zero vector \( \vec{a} \) can be written as the scalar multiple of a unit vector in the direction of \( \vec{a} \). This scalar is nothing but the magnitude of the vector.

Thus for any vector \( \vec{a} = |\vec{a}| \hat{a} \), where \( \hat{a} \) is the unit vector along the direction of \( \vec{a} \).

Clearly \( \hat{a} = \frac{\vec{a}}{|\vec{a}|} \) for any non-zero vector.

### Definition 8.9

Two vectors are said to be **like vectors** if they have the same direction. Two vectors are said to be **unlike vectors** if they have opposite directions.

**Like Vectors**

**Unlike Vectors**

**Neither like Vectors nor unlike Vectors**

We observe that if two vectors are like vectors or unlike vectors, then the undirected lines (support) of the vectors are parallel to each other. There are pair of vectors which are neither like nor unlike vectors.

## 8.4 Algebra of Vectors

We have studied basic algebraic operations on real numbers and on matrices. Similarly we studied some operations on vectors. Now let us see how to add two vectors, subtract a vector from another vector and multiply a vector by a scalar.

### 8.4.1 Addition of Vectors

Let us define the sum of two vectors in two ways and see that they are the same. Let us assume that an object of unit mass is placed at the origin \( (0,0) \) in \( \mathbb{R}^2 \). We assume that the size of the object is just a point. Let us assume that two forces \( \vec{a} \) and \( \vec{b} \) of unit magnitude act on the object in the positive directions of \( x \)-axis and \( y \)-axis respectively (Fig.8.4). It is easy to guess that the object will move in the direction \( 45^\circ \) to the \( x \)-axis as indicated in Fig.8.5. The forces \( \vec{a} \) and \( \vec{b} \) are equal to the vectors \( \vec{a} \) and \( \vec{b} \) as indicated in Fig. 8.6. We may think that the forces push the object in Fig. 8.4 and pull the object in Fig.8.6.

**Fig.8.4**

**Fig.8.5**

**Fig.8.6**

**Fig.8.7**

The next question before us is How long will it go? Let us assume that the forces act one after the other. The force \( \vec{a} \) will move the object one unit along the \( x \)-axis. So the object will move from \( (0,0) \) to \( (1,0) \). Now the force \( \vec{b} \) will move the object vertically from \( (1,0) \) to \( (1,1) \). So finally the object will be at \( (1,1) \) (Fig. 8.7). Thus the sum of the two vectors may be defined as the line segment joining \( (0,0) \) and \( (1,1) \) in the direction \( (0,0) \) to \( (1,1) \).

Now, as in the same situation discussed above, let us assume that the force \( \vec{a} \) has magnitude 2 instead of 1 (Fig. 8.8). It will not be difficult to guess that the object will move in a direction much closure to the \( x \)-axis as indicated in Fig. 8.9. Also we may guess that the object will go to the point \( (2,1) \). Thus the sum of the two vectors may be defined as the line segment joining \( (0,0) \) and \( (2,1) \) in the direction \( (0,0) \) to \( (2,1) \).

**Fig.8.8**

**Fig.8.9**

In the two situations discussed above the directions of the forces are perpendicular to each other. This need not be the case in general. Even then we can add the forces by considering one after the other. For example let \( \vec{a} \) and \( \vec{b} \) be two forces in a plane as shown in Fig. 8.10.

**Fig.8.10**

**Fig.8.11**

**Fig.8.12**

Bringing the initial point of \( \vec{b} \) to the terminal point of \( \vec{a} \) (Fig. 8.11), we can get the resultant of these two forces (see Fig. 8.12). This motivates us to define the sum of two vectors.

### Triangle law of addition

Let \( \vec{a} \) and \( \vec{b} \) be two vectors. Let \( A_1 \) and \( B_1 \) be the initial points of \( \vec{a} \) and \( \vec{b} \), and \( A_2 \) and \( B_2 \) be the terminal points of \( \vec{a} \) and \( \vec{b} \) respectively.

**Fig.8.13**

Draw \( A_2 B_2 \) parallel to \( B_1 B_2 \) so that \( A_2 B_2 = B_1 B_2 \). Then the vector \( \overrightarrow{A_1 B_1} \) is defined as the sum of the vectors \( \vec{a} \) and \( \vec{b} \), and it is denoted as \( \vec{a} + \vec{b} \). This can be restated as,

### Definition 8.10 (Triangle law of addition)

If two vectors are represented in magnitude and direction by the two sides of a triangle taken in order, then their sum is represented by the third side taken in the reverse order.

### Result 8.1

If \( \vec{a}, \vec{b} \) and \( \vec{c} \) are the sides of a triangle taken in order then \( \vec{a} + \vec{b} + \vec{c} = \vec{0} \).

**Proof**

**Fig.8.14**

Let \( \overrightarrow{AB} = \vec{a}, \overrightarrow{BC} = \vec{b} \) and \( \overrightarrow{CA} = \vec{c} \). Now

\[
\vec{a} + \vec{b} + \vec{c} = \overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{CA} = \overrightarrow{AC} + \overrightarrow{CA} = \overrightarrow{AA} = \vec{0}.
\]

Thus the result is proved.

### Parallelogram law of vector addition

Let \( \vec{a} \) and \( \vec{b} \) be two vectors. Assuming that the initial points of the two vectors are the same, let us find the sum according to Definition 8.7. Let \( A \) and \( B \) be the terminal points of \( \vec{a} \) and \( \vec{b} \) respectively (Fig. 8.15). To find \( \vec{a} + \vec{b} \), we draw \( AC \) parallel to \( OB \) so that \( OB = AC \) and declare that \( \overrightarrow{OC} \) is the sum (Fig. 8.16). We observe that \( OA \) and \( BC \) are parallel (Fig. 8.17).

**Fig.8.15**

**Fig.8.16**

**Fig.8.17**

So to find the sum of two vectors with the same initial point, draw the parallelogram with the given vectors as adjacent sides and declare the diagonal as the sum. Even the vectors do not have the same initial point, we can move one of the vectors suitably and make them to have same initial point. This leads us to the following Definition 8.11.

Let \( \vec{a} \) and \( \vec{b} \) be two vectors with the same initial point \( O \). Let \( A \) and \( B \) be the terminal points of \( \vec{a} \) and \( \vec{b} \) respectively.

Complete the parallelogram \( OACB \). Then the vector \( \overrightarrow{OC} \) is defined as the sum of the vectors \( \vec{a} \) and \( \vec{b} \). Thus

### Definition 8.11 (Parallelogram law of addition)

In a parallelogram \( OABC \) if \( \overrightarrow{OA} \) and \( \overrightarrow{OB} \) represents two adjacent sides, then the diagonal \( \overrightarrow{OC} \) represents their sum (see Fig. 8.17).

Though we have two definitions for addition of vectors, they are one and the same. Definition 8.10 is defined using the triangle law for addition of vectors and Definition 8.11 is defined using the parallelogram law for addition of vectors:

In a triangle \( ABC \) if \( \overrightarrow{AB} \) and \( \overrightarrow{BC} \) represent two sides, then the third side \( \overrightarrow{AC} \) represents their sum.

### 8.4.2 Difference between two Vectors

Now let us see how to subtract one vector from another vector.

### Definition 8.12

Let \( \vec{a} \) be a vector. Then the **reverse** of \( \vec{a} \), denoted by \( -\vec{a} \), is defined as the vector having the magnitude of \( \vec{a} \) and the direction opposite to the direction of \( \vec{a} \).

Notice that if \( \overrightarrow{AB} = \vec{a} \), then \( \overrightarrow{BA} = -\vec{a} \).

### Geometrical interpretation of difference between two vectors

Let \( \vec{a} \) be a vector with initial point \( P \) and terminal point \( Q \). Let \( \vec{b} \) be the vector with initial point \( Q \) and terminal point \( P \). The magnitude of both of the vectors is the length of the line segment joining \( P \) and \( Q \). So they have the same magnitude. But clearly they have opposite directions. So \( \vec{b} \) is equal to \( -\vec{a} \).

If \( \vec{a} \) and \( \vec{b} \) are two vectors, then the vector \( \vec{a} - \vec{b} \) is defined as the sum of the vectors \( \vec{a} \) and \( -\vec{b} \). That is \( \vec{a} + (-\vec{b}) \).

We can view the vector \( \vec{a} - \vec{b} \) geometrically. Let \( \overrightarrow{OA} \) and \( \overrightarrow{OB} \) represent the vectors \( \vec{a} \) and \( \vec{b} \) respectively (Fig. 8.18). Draw \( AC \) parallel to \( OB \) with \( AC = OB \). Then \( \overrightarrow{AC} \) is equal to \( \vec{b} \). Extend the line \( CA \) to \( D \) so that \( CA = AD \). Then \( \overrightarrow{AD} \) is equal to \( -\vec{b} \). Thus \( \vec{a} + (-\vec{b}) = \overrightarrow{OD} \). Hence \( \vec{a} - \vec{b} = \overrightarrow{OD} \) (Fig. 8.19).

Let us complete the parallelogram \( OACB \). We observe that \( BA \) and \( OD \) are parallel and they have equal length. Thus the two vectors \( \overrightarrow{BA} \) and \( \overrightarrow{OD} \) are equal. So we may consider \( \overrightarrow{BA} \) as \( \vec{a} - \vec{b} \). This shows that if the sides \( \overrightarrow{OA} \) and \( \overrightarrow{OB} \) of the parallelogram \( OACB \) represent the vectors \( \vec{a} \) and \( \vec{b} \) respectively, then the diagonal \( \overrightarrow{BA} \) will represent the vector \( \vec{a} - \vec{b} \). (Fig. 8.20). We note that we have already seen that the diagonal \( \overrightarrow{OC} \) represents the vector \( \vec{a} + \vec{b} \).

**Fig.8.18**

**Fig.8.19**

**Fig.8.20**

Thus, if \( \vec{a} \) and \( \vec{b} \) represent two adjacent sides of a parallelogram then the diagonals represent \( \vec{a} + \vec{b} \) and \( \vec{a} - \vec{b} \).

### 8.4.3 Scalar multiplication of a vector

Now let us see how to multiply a vector by a scalar.

Let \( \vec{a} \) be a vector and \( m \) be a scalar. Then the vector \( m\vec{a} \) is called the **scalar multiple** of a vector \( \vec{a} \) by the scalar \( m \).

Let us note that when \( m \) is zero, the magnitude of \( m\vec{a} \) becomes 0 and hence \( m\vec{a} \) becomes the zero vector. If \( m \) is positive, then both \( \vec{a} \) and \( m\vec{a} \) have the same direction and when \( m \) is negative, then \( \vec{a} \) and \( m\vec{a} \) have opposite directions. Thus \( \vec{a} \) and \( m\vec{a} \) are like vectors if \( m \) is positive and unlike vectors if \( m \) is negative. The magnitude of \( m\vec{a} \) is \( |m\vec{a}| = |m||\vec{a}| \).

### Definition 8.13

Two vectors \( \vec{a} \) and \( \vec{b} \) are said to be **parallel** if \( \vec{a} = \lambda \vec{b} \), where \( \lambda \) is a scalar. If \( \lambda > 0 \), they are in the same direction. If \( \lambda < 0 \) then they are in the opposite direction to each other.

### 8.4.4 Some properties and results

For any two vectors \( \vec{a} \) and \( \vec{b} \) and scalars \( m \) and \( n \), we have

\[
\begin{array}{rl}
\text{(i)} & m(n\vec{a}) = mn(\vec{a}) = n(m\vec{a}) \\
\text{(ii)} & (m + n)\vec{a} = m\vec{a} + n\vec{a} \\
\text{(iii)} & m(\vec{a} + \vec{b}) = m\vec{a} + m\vec{b}
\end{array}
\]

### Result 8.2

Vector addition is associative.

For any three vectors \( \vec{a}, \vec{b} \) and \( \vec{c} \)

\[
(\vec{a} + \vec{b}) + \vec{c} = \vec{a} + (\vec{b} + \vec{c}).
\]

### Result 8.3

For any vector \( \vec{a} \), \( \vec{a} + \vec{0} = \vec{0} + \vec{a} = \vec{a} \).

### Result 8.4

For any vector \( \vec{a} \), \( \vec{a} + (-\vec{a}) = (-\vec{a}) + \vec{a} = \vec{0} \).

This result states that the additive inverse exists for every vector.

### Result 8.5

Vector addition is commutative.

**Proof**

Let \( \vec{a} \) and \( \vec{b} \) be two vectors. Let \( \vec{a} = \overrightarrow{OA} \), \( \vec{b} = \overrightarrow{OB} \).

Complete the parallelogram \( OACB \) with \( \vec{a} \) and \( \vec{b} \) as adjacent sides. The vectors \( \overrightarrow{OB} \) and \( \overrightarrow{AC} \) have same direction and equal magnitude; so \( \overrightarrow{OB} = \overrightarrow{AC} \). Thus

\[
\vec{a} + \vec{b} = \overrightarrow{OA} + \overrightarrow{AC} = \overrightarrow{OC}.
\]

As, \( \overrightarrow{OA} = \overrightarrow{BC} \),

\[
\vec{b} + \vec{a} = \overrightarrow{OB} + \overrightarrow{BC} = \overrightarrow{OC}.
\]

Thus

\[
\vec{a} + \vec{b} = \vec{b} + \vec{a}.
\]

**Fig.8.21**

### Polygon law of addition

Let \( \overrightarrow{OA}, \overrightarrow{AB}, \overrightarrow{BC}, \overrightarrow{CD} \), and \( \overrightarrow{DE} \) be any five vectors as shown in the Fig. 8.22.

We observe from the figure that each vector is drawn from the terminal point of its previous one. By the triangle law,

\[
\overrightarrow{OA} + \overrightarrow{AB} = \overrightarrow{OB} ;\quad \overrightarrow{OB} + \overrightarrow{BC} = \overrightarrow{OC}
\]
\[
\overrightarrow{OC} + \overrightarrow{CD} = \overrightarrow{OD} ;\quad \overrightarrow{OD} + \overrightarrow{DE} = \overrightarrow{OE}
\]

**Fig.8.22**

\[
\overrightarrow{OA} + \overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{CD} + \overrightarrow{DE} = \overrightarrow{OE}.
\]

Thus the line joining the initial point of first vector to the terminal point of the last vector is the sum of all the vectors. This is called the **polygon law** of addition of vectors.

### Example 8.1

Represent graphically the displacement of

(i) \( 30 \text{ km } 60^\circ \) west of north

(ii) \( 60 \text{ km } 50^\circ \) south of east.

**Fig.8.23**

**Fig.8.24**

### Example 8.2

If \( \vec{a} \) and \( \vec{b} \) are vectors represented by two adjacent sides of a regular hexagon, then find the vectors represented by other sides.

**Solution**

Let \( A, B, C, D, E, F \) be the vertices of a regular hexagon.

Let \( \vec{a} = \overrightarrow{AB} \) and \( \vec{b} = \overrightarrow{BC} \).

We use the following facts about regular hexagon.

(i) The lines \( AB, CF \) and \( ED \) are parallel and the lines \( BC, AD \) and \( EF \) are parallel.

(ii) The length of \( CF \) is twice the length of \( AB \) and the length of \( AD \) is twice the length of \( BC \).

Since the lines \( AB \) and \( DE \) are parallel, equal in length and opposite in direction we have

**Fig.8.25**

\[
\overrightarrow{DE} = -\vec{a}.
\]

Since the lines \( AB \) and \( CF \) are parallel and opposite in direction we have

\[
\overrightarrow{CF} = -2\vec{a}.
\]

Similarly \( \overrightarrow{EF} = -\vec{b} \) and \( \overrightarrow{AD} = 2\vec{b} \).

Since \( \overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC} \) we have

\[
\overrightarrow{AC} = \vec{a} + \vec{b}.
\]

Since \( \overrightarrow{AC} + \overrightarrow{CD} = \overrightarrow{AD} \) we have

\[
\vec{a} + \vec{b} + \overrightarrow{CD} = 2\vec{b}.
\]

Thus

\[
\overrightarrow{CD} = 2\vec{b} - (\vec{a} + \vec{b}) = \vec{b} - \vec{a}.
\]

As \( \overrightarrow{FA} = -\overrightarrow{CD} \), we have

\[
\overrightarrow{FA} = \vec{a} - \vec{b}.
\]

Hence, for given sides \( \overrightarrow{AB} = \vec{a} \) and \( \overrightarrow{BC} = \vec{b} \), we have obtained all other sides of the hexagon as \( \overrightarrow{CD} = \vec{b} - \vec{a} \), \( \overrightarrow{DE} = -\vec{a} \), \( \overrightarrow{EF} = -\vec{b} \), and \( \overrightarrow{FA} = \vec{a} - \vec{b} \).

## 8.5 Position vectors

### Definition 8.14

Let \( O \) be the origin and \( P \) be any point (in the plane or space). Then the vector \( \overrightarrow{OP} \) is called the **position vector** of the point \( P \) with respect to the origin \( O \) (point of reference).

The relation between the vectors and position vectors are given in the following result.

### Result 8.6

Let \( O \) be the origin, \( A \) and \( B \) be two points. Then \( \overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} \) where, \( \overrightarrow{OA} \) and \( \overrightarrow{OB} \) are position vectors of \( A \) and \( B \) respectively.

**Proof**

We know that, \( \overrightarrow{OA} + \overrightarrow{AB} = \overrightarrow{OB} \). Thus \( \overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} \).

### Theorem 8.1 (Section Formula - Internal Division)

Let \( O \) be the origin. Let \( A \) and \( B \) be two points. Let \( P \) be the point which divides the line segment \( AB \) internally in the ratio \( m : n \). If \( \vec{a} \) and \( \vec{b} \) are the position vectors of \( A \) and \( B \), then the position vector \( \overrightarrow{OP} \) of \( P \) is given by

\[
\overrightarrow{OP} = \frac{n\vec{a} + m\vec{b}}{m + n}.
\]

**Proof**

Since \( O \) is the origin, \( \vec{a} \) and \( \vec{b} \) are the position vectors of \( A \) and \( B \), we have

\[
\overrightarrow{OA} = \vec{a} \quad \text{and} \quad \overrightarrow{OB} = \vec{b}.
\]

Let \( \overrightarrow{OP} = \vec{r} \).

Since \( P \) divides the line segment \( AB \) internally in the ratio \( m : n \) we have,

\[
\frac{|\overrightarrow{AP}|}{|\overrightarrow{PB}|} = \frac{m}{n}
\]

**Fig.8.26**

and hence \( n|\overrightarrow{AP}| = m|\overrightarrow{PB}| \).

But the vectors \( \overrightarrow{AP} \) and \( \overrightarrow{PB} \) have the same direction. Thus

\[
n\overrightarrow{AP} = m\overrightarrow{PB}. \tag{8.1}
\]

\[
\overrightarrow{AP} = \overrightarrow{OP} - \overrightarrow{OA} = \vec{r} - \vec{a} \quad \text{and} \quad \overrightarrow{PB} = \overrightarrow{OB} - \overrightarrow{OP} = \vec{b} - \vec{r}
\]

Substituting this in (8.1), we get

\[
n(\vec{r} - \vec{a}) = m(\vec{b} - \vec{r})
\]

and hence

\[
(m + n)\vec{r} = n\vec{a} + m\vec{b}.
\]

\[
\overrightarrow{OP} = \frac{n\vec{a} + m\vec{b}}{m + n}.
\]

### Theorem 8.2 (Section Formula - External Division) (Without proof)

Let \( O \) be the origin. Let \( A \) and \( B \) be two points. Let \( P \) be the point which divides the line segment \( AB \) externally in the ratio \( m : n \). If \( \vec{a} \) and \( \vec{b} \) are the position vectors of \( A \) and \( B \), then the position vector \( \overrightarrow{OP} \) of \( P \) is given by

\[
\overrightarrow{OP} = \frac{n\vec{a} - m\vec{b}}{n - m}.
\]

### Note 8.1

By taking \( m = n = 1 \) in Theorem 8.1, we see that the position vector of the midpoint of the line joining the points \( A \) and \( B \) is \( \frac{\vec{a} + \vec{b}}{2} \), where \( \vec{a} \) and \( \vec{b} \) are the position vectors of the points \( A \) and \( B \) respectively.

From the above theorem we can get a condition for three points to be collinear.

### Result 8.7

Three distinct points \( A, B \) and \( C \) with position vectors \( \vec{a}, \vec{b} \) and \( \vec{c} \) are collinear if and only if there exist real numbers \( x, y, z \) none of them is zero, such that

\[
x + y + z = 0 \quad \text{and} \quad x\vec{a} + y\vec{b} + z\vec{c} = \vec{0}.
\]

### Example 8.3

Let \( A \) and \( B \) be two points with position vectors \( 2\vec{a} + 4\vec{b} \) and \( 2\vec{a} - 8\vec{b} \). Find the position vectors of the points which divide the line segment joining \( A \) and \( B \) in the ratio 1 : 3 internally and externally.

**Solution**

Let \( O \) be the origin. It is given that

\[
\overline{OA} = 2\vec{a} + 4\vec{b} \quad \text{and} \quad \overline{OB} = 2\vec{a} - 8\vec{b}.
\]

Let \( C \) and \( D \) be the points which divide the segment \( AB \) in the ratio 1 : 3 internally and externally respectively. Then

\[
\overline{OC} = \frac{3\overline{OA} + 1\overline{OB}}{3 + 1} = \frac{3(2\vec{a} + 4\vec{b}) + (2\vec{a} - 8\vec{b})}{4} = \frac{6\vec{a} + 12\vec{b} + 2\vec{a} - 8\vec{b}}{4} = \frac{8\vec{a} + 4\vec{b}}{4} = 2\vec{a} + \vec{b}.
\]

\[
\overline{OD} = \frac{3\overline{OA} - 1\overline{OB}}{3 - 1} = \frac{3(2\vec{a} + 4\vec{b}) - (2\vec{a} - 8\vec{b})}{2} = \frac{6\vec{a} + 12\vec{b} - 2\vec{a} + 8\vec{b}}{2} = \frac{4\vec{a} + 20\vec{b}}{2} = 2\vec{a} + 10\vec{b}.
\]

Let us recall the definition that the line joining a vertex of a triangle with the midpoint of its opposite side is called a median. The centroid divides the median from vertex to the midpoint of the opposite side internally in the ratio 2 : 1.

### Theorem 8.3

The medians of a triangle are concurrent.

**Proof**

Let \( ABC \) be a triangle and let \( D, E, F \) be the mid points of its sides \( BC, CA \) and \( AB \) respectively. We have to prove that the medians \( AD, BE, CF \) are concurrent.

Let \( O \) be the origin and \( \vec{a}, \vec{b}, \vec{c} \) be the position vectors of \( A, B \) and \( C \) respectively.

The position vectors of \( D, E \) and \( F \) are respectively

\[
\frac{\vec{b} + \vec{c}}{2}, \quad \frac{\vec{c} + \vec{a}}{2}, \quad \frac{\vec{a} + \vec{b}}{2}.
\]

Let \( G_1 \) be the point on \( AD \) dividing it internally in the ratio 2 : 1.

**Fig.8.27**

Therefore, position vector of \( G_1 = \frac{1 \cdot \overrightarrow{OA} + 2 \cdot \overrightarrow{OD}}{1 + 2} \)

\[
\overline{OG_1} = \frac{1\vec{a} + 2\left(\frac{\vec{b} + \vec{c}}{2}\right)}{3} = \frac{\vec{a} + \vec{b} + \vec{c}}{3} \tag{1}
\]

Let \( G_2 \) be the point on \( BE \) dividing it internally in the ratio 2 : 1.

\[
\overline{OG_2} = \frac{1 \cdot \overrightarrow{OB} + 2 \cdot \overrightarrow{OE}}{1 + 2} = \frac{\vec{b} + 2\left(\frac{\vec{c} + \vec{a}}{2}\right)}{3} = \frac{\vec{a} + \vec{b} + \vec{c}}{3} \tag{2}
\]

Similarly if \( G_3 \) divides \( CF \) in the ratio 2 : 1 then

\[
\overline{OG_3} = \frac{\vec{a} + \vec{b} + \vec{c}}{3} \tag{3}
\]

From (1), (2), and (3) we find that the position vectors of the three points \( G_1, G_2, G_3 \) are one and the same. Hence they are not different points. Let the common point be \( G \).

Therefore the three medians are concurrent and the point of concurrence is \( G \).

### Theorem 8.4

A quadrilateral is a parallelogram if and only if its diagonals bisect each other.

**Proof**

Let \( A, B, C, D \) be the vertices of a quadrilateral with diagonals \( AC \) and \( BD \). Let \( \vec{a}, \vec{b}, \vec{c} \) and \( \vec{d} \) be the position vectors of \( A, B, C \) and \( D \) respectively with respect to \( O \).

Let the quadrilateral \( ABCD \) be a parallelogram. Then

\[
\overline{AB} = \overline{DC} \Rightarrow \overline{OB} - \overline{OA} = \overline{OC} - \overline{OD} \Rightarrow \vec{b} - \vec{a} = \vec{c} - \vec{d} \Rightarrow \vec{b} + \vec{d} = \vec{a} + \vec{c}
\]

**Fig. 8.28**

and hence

\[
\frac{\vec{b} + \vec{d}}{2} = \frac{\vec{a} + \vec{c}}{2}.
\]

This shows that the position vectors of the midpoint of the line segments \( AC \) and \( BD \) are the same. In other words, the diagonals bisect each other.

Conversely let us assume that the diagonals bisect each other. Thus the position vectors of the midpoint of the line segments \( AC \) and \( BD \) are the same. Thus

\[
\frac{\vec{a} + \vec{c}}{2} = \frac{\vec{b} + \vec{d}}{2} \Rightarrow \vec{a} + \vec{c} = \vec{b} + \vec{d} \Rightarrow \vec{c} - \vec{d} = \vec{b} - \vec{a}.
\]

This implies that \( \overline{OC} - \overline{OD} = \overline{OB} - \overline{OA} \) and hence \( \overline{DC} = \overline{AB} \). This shows that the lines \( AB \) and \( DC \) are parallel. From \( \vec{a} + \vec{c} = \vec{b} + \vec{d} \) we see that \( \vec{a} - \vec{d} = \vec{b} - \vec{c} \) which shows that the lines \( AD \) and \( BC \) are parallel. Hence \( ABCD \) is a parallelogram.

## EXERCISE 8.1

1. Represent graphically the displacement of

   (i) \( 45 \text{ cm } 30^\circ \) north of east.

   (ii) \( 80 \text{ km } 60^\circ \) south of west.

2. Prove that the relation \( R \) defined on the set \( V \) of all vectors by \( \vec{a} R \vec{b} \) if \( \vec{a} = \vec{b} \) is an equivalence relation on \( V \).

3. Let \( \vec{a} \) and \( \vec{b} \) be the position vectors of the points \( A \) and \( B \). Prove that the position vectors of the points which trisects the line segment \( AB \) are \( \frac{\vec{a} + 2\vec{b}}{3} \) and \( \frac{\vec{b} + 2\vec{a}}{3} \).

4. If \( D \) and \( E \) are the midpoints of the sides \( AB \) and \( AC \) of a triangle \( ABC \) prove that \( \overline{BE} + \overline{DC} = \frac{3}{2}\overline{BC} \).

5. Prove that the line segment joining the midpoints of two sides of a triangle is parallel to the third side whose length is half of the length of the third side.

6. Prove that the line segments joining the midpoints of the adjacent sides of a quadrilateral form a parallelogram.

7. If \( \vec{a} \) and \( \vec{b} \) represent a side and a diagonal of a parallelogram, find the other sides and the other diagonal.

8. If \( \overrightarrow{PO} + \overrightarrow{OQ} = \overrightarrow{QO} + \overrightarrow{OR} \), prove that the points \( P, Q, R \) are collinear.

9. If \( D \) is the midpoint of the side \( BC \) of a triangle \( ABC \), prove that \( \overrightarrow{AB} + \overrightarrow{AC} = 2\overrightarrow{AD} \).

10. If \( G \) is the centroid of a triangle \( ABC \), prove that \( \overrightarrow{GA} + \overrightarrow{GB} + \overrightarrow{GC} = \vec{0} \).

11. Let \( A, B \) and \( C \) be the vertices of a triangle. Let \( D, E \) and \( F \) be the midpoints of the sides \( BC, CA \) and \( AB \) respectively. Show that \( \overrightarrow{AD} + \overrightarrow{BE} + \overrightarrow{CF} = \vec{0} \).

12. If \( ABCD \) is a quadrilateral and \( E \) and \( F \) are the midpoints of \( AC \) and \( BD \) respectively, then prove that \( \overrightarrow{AB} + \overrightarrow{AD} + \overrightarrow{CB} + \overrightarrow{CD} = 4\overrightarrow{EF} \).

## 8.6 Resolution of Vectors

Resolution of a vector can be done for any finite dimension. But we will discuss only in two and three dimensions. Let us start with two dimension.

### 8.6.1 Resolution of a vector in two dimension

### Theorem 8.5

Let \( \hat{i} \) and \( \hat{j} \) be the unit vectors along the positive \( x \)-axis and the \( y \)-axis having initial point at the origin \( O \). Now \( \overrightarrow{OP} \) is the position vector of any point \( P \) in the plane. Then \( \overrightarrow{OP} \) can be uniquely written as

\[
\overrightarrow{OP} = x\hat{i} + y\hat{j} \quad \text{for some real numbers } x \text{ and } y.
\]

Further \( |\overrightarrow{OP}| = \sqrt{x^2 + y^2} \).

**Proof**

Let \( (x, y) \) be the coordinates of the point \( P \). Let \( L \) and \( M \) be the foots of the perpendiculars drawn from \( P \) to the \( x \) and \( y \) axes. Then

\[
\overrightarrow{OP} = \overrightarrow{OL} + \overrightarrow{LP} = \overrightarrow{OL} + \overrightarrow{OM}.
\]

Since \( \hat{i} \) and \( \hat{j} \) are unit vectors, we have \( \overrightarrow{OL} = x\hat{i} \) and \( \overrightarrow{OM} = y\hat{j} \).

Thus \( \overrightarrow{OP} = x\hat{i} + y\hat{j} \).

**Fig.8.29**

To prove the uniqueness, let \( x_1\hat{i} + y_1\hat{j} \) and \( x_2\hat{i} + y_2\hat{j} \) be two representations of the same point \( P \). Then

\[
x_1\hat{i} + y_1\hat{j} = x_2\hat{i} + y_2\hat{j}.
\]

This implies that \( (x_1 - x_2)\hat{i} + (y_1 - y_2)\hat{j} = \vec{0} \Rightarrow x_1 - x_2 = 0, y_1 - y_2 = 0 \).

In other words \( x_1 = x_2 \) and \( y_1 = y_2 \) and hence the uniqueness follows.

\[
\text{In the triangle } OLP, \quad OP^2 = OL^2 + LP^2; \text{ hence } |\overline{OP}| = \sqrt{x^2 + y^2}.
\]

\[
\text{That is, } |\vec{r}| = r = \sqrt{x^2 + y^2}.
\]

Observe that if \( \hat{i} \) and \( \hat{j} \) are the unit vectors in the positive directions of \( x \) and \( y \) axes, then the position vector of the point \( (6,4) \) can be written as \( 6\hat{i} + 4\hat{j} \) and this is the only way of writing it.

### Result 8.8

If \( \vec{a} \) and \( \vec{b} \) are two non-collinear vectors in a plane, then any vector in the plane can be written as the linear combination of \( \vec{a} \) and \( \vec{b} \) in a unique way. That is, any vector in the plane is of the form \( l\vec{a} + m\vec{b} \) for some scalars \( l \) and \( m \).

**Proof**

Let \( \overline{OA} = \vec{a} \), \( \overline{OB} = \vec{b} \), and \( \vec{r} \) be any vector coplanar with \( \vec{a} \) and \( \vec{b} \).

Draw \( PL \) parallel to \( OB \). Clearly \( \overline{LP} = m\vec{b} \) and \( \overline{OL} = l\vec{a} \) for some \( l \) and \( m \).

Now \( \overline{OP} = \overline{OL} + \overline{LP} \).

That is, \( \vec{r} = l\vec{a} + m\vec{b} \).

**Fig.8.30**

Therefore if \( \vec{r}, \vec{a}, \vec{b} \) are coplanar then \( \vec{r} \) is a linear combination of \( \vec{a} \) and \( \vec{b} \).

### Note 8.2

Further if three non collinear vectors are coplanar then any one of the vector can be written as a linear combination of other two. Note that the converse is also true.

### Result 8.9

If \( \vec{a}, \vec{b} \) and \( \vec{c} \) are three non-coplanar vectors in the space, then any vector in the space can be written as \( l\vec{a} + m\vec{b} + n\vec{c} \) in a unique way for some scalars \( l, m \) and \( n \).

### Definition 8.15

Let \( \hat{i} \) and \( \hat{j} \) be the unit vectors in the positive directions of \( x \) and \( y \) axes respectively. Let \( \vec{r} \) be any vector in the plane. Then \( \vec{r} = x\hat{i} + y\hat{j} \) for some real numbers \( x \) and \( y \). Here \( x\hat{i} \) and \( y\hat{j} \) are called the **rectangular components** of \( \vec{r} \) along the \( x \) and \( y \) axes respectively in two dimension.

What we discussed so far can be discussed in the three dimensional space also.

### 8.6.2 Resolution of a vector in three dimension

### Theorem 8.6

Let \( \hat{i}, \hat{j} \) and \( \hat{k} \) be the unit vectors in the direction of positive \( x, y \) and \( z \) axes respectively having initial point at the origin \( O \). Let \( \overline{OP} \) be the position vector of any point \( P \) in the space. Then \( \overline{OP} \) can be uniquely written as

\[
\overline{OP} = x\hat{i} + y\hat{j} + z\hat{k}
\]

for some real numbers \( x, y \) and \( z \). Further \( |\overline{OP}| = \sqrt{x^2 + y^2 + z^2} \).

**Proof**

Let \( (x, y, z) \) be the coordinates of the point \( P \). Let \( Q \) be the foot of the perpendicular drawn from \( P \) to the \( xy \)-plane. Let \( R \) and \( S \) be the foots of the perpendiculars drawn from \( Q \) to the \( x \) and \( y \) axes respectively. Let \( \overline{OP} = \vec{r} \).

Then, \( OR = x \), \( OS = y \) and \( QP = z \).

\[
\overline{OR} = x\hat{i}, \quad \overline{RQ} = \overline{OS} = y\hat{j}, \quad \text{and} \quad \overline{QP} = z\hat{k}
\]

\[
\overline{OP} = \vec{r} = \overline{OP} + \overline{QP} = \overline{OR} + \overline{RQ} + \overline{QP} = x\hat{i} + y\hat{j} + z\hat{k}.
\]

That is \( \overline{OP} = \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \).

This \( \overline{OP} \) vector is called the position vector of \( P \) with respect to the origin \( O \) in three dimension.

In the triangle \( ORQ \)

\[
OQ^2 = OR^2 + RQ^2 \quad \text{(how?)}
\]

and in the triangle \( OQP \)

\[
OP^2 = OQ^2 + QP^2.
\]

Thus \( OP^2 = OQ^2 + QP^2 = OR^2 + RQ^2 + QP^2 = x^2 + y^2 + z^2 \) and hence \( |\overline{OP}| = \sqrt{x^2 + y^2 + z^2} \), that is \( |\vec{r}| = r = \sqrt{x^2 + y^2 + z^2} \).

**Fig.8.31**

### Components of vector joining two points

Let us find the components of the vector joining the point \( (x_1, y_1) \) to \( (x_2, y_2) \).

Let \( A \) and \( B \) be the points \( (x_1, y_1) \) and \( (x_2, y_2) \). Let \( P \) be the point \( (x_2 - x_1, y_2 - y_1) \). Then \( \overline{AB} = \overline{OP} \). The components of \( \overline{OP} \) are \( (x_2 - x_1)\hat{i} \) and \( (y_2 - y_1)\hat{j} \). Hence the components of \( \overline{AB} \) in the directions of \( x \) and \( y \) axes are \( (x_2 - x_1)\hat{i} \) and \( (y_2 - y_1)\hat{j} \).

Similarly if \( A \) and \( B \) are the points \( (x_1, y_1, z_1) \) and \( (x_2, y_2, z_2) \), then the components of \( \overline{AB} \) in the directions of \( x, y \) and \( z \) axes are \( (x_2 - x_1)\hat{i} \), \( (y_2 - y_1)\hat{j} \), and \( (z_2 - z_1)\hat{k} \).

### 8.6.3 Matrix representation of a vector

A vector with three components can be visualised as either a row or column matrix as

\[
\begin{bmatrix} x & y & z \end{bmatrix} \quad \text{or} \quad \begin{bmatrix} x \\ y \\ z \end{bmatrix}.
\]

Thus any vector \( \vec{A} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} \) can be obtained from

\[
\begin{bmatrix} a_1 & a_2 & a_3 \end{bmatrix} \begin{bmatrix} \hat{i} \\ \hat{j} \\ \hat{k} \end{bmatrix} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} = \vec{A}.
\]

Hence addition of vectors and multiplication of a vector by a scalar can be defined as follows.

If \( \vec{A} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} \) and \( \vec{B} = b_1\hat{i} + b_2\hat{j} + b_3\hat{k} \) then

\[
\vec{A} + \vec{B} = \begin{bmatrix} a_1 \\ a_2 \\ a_3 \end{bmatrix} + \begin{bmatrix} b_1 \\ b_2 \\ b_3 \end{bmatrix} = \begin{bmatrix} a_1 + b_1 \\ a_2 + b_2 \\ a_3 + b_3 \end{bmatrix}
\]

resulting in \( \vec{A} + \vec{B} = (a_1 + b_1)\hat{i} + (a_2 + b_2)\hat{j} + (a_3 + b_3)\hat{k} \). Also

\[
k\vec{A} = k \begin{bmatrix} a_1 \\ a_2 \\ a_3 \end{bmatrix} = \begin{bmatrix} k a_1 \\ k a_2 \\ k a_3 \end{bmatrix}
\]

yielding \( k\vec{A} = k a_1\hat{i} + k a_2\hat{j} + k a_3\hat{k} \). For \( k \in \mathbb{R}, k > 1 \) yields magnification, \( 0 < k < 1 \) yields contraction of a vector and \( k = 0 \) yields a zero vector \( \overrightarrow{OA} = 0\hat{i} + 0\hat{j} + 0\hat{k} = \vec{0} \).

### Result 8.10

Using the commutative, associative properties of vector addition and the distributive property of the scalar multiplication we can prove the following.

If \( \vec{a} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} \), \( \vec{b} = b_1\hat{i} + b_2\hat{j} + b_3\hat{k} \) and if \( m \) is a scalar, then

\[
\vec{a} + \vec{b} = (a_1 + b_1)\hat{i} + (a_2 + b_2)\hat{j} + (a_3 + b_3)\hat{k}
\]
\[
\vec{a} - \vec{b} = (a_1 - b_1)\hat{i} + (a_2 - b_2)\hat{j} + (a_3 - b_3)\hat{k}
\]
\[
m\vec{a} = m a_1\hat{i} + m a_2\hat{j} + m a_3\hat{k}
\]
and
\[
\vec{a} = \vec{b} \text{ if and only if } a_1 = b_1, a_2 = b_2, \text{ and } a_3 = b_3.
\]

### Example 8.4

Find a unit vector along the direction of the vector \( 5\hat{i} - 3\hat{j} + 4\hat{k} \).

**Solution**

We know that a unit vector along the direction of the vector \( \vec{a} \) is given by \( \frac{\vec{a}}{|\vec{a}|} \). So a unit vector along the direction of \( 5\hat{i} - 3\hat{j} + 4\hat{k} \) is given by

\[
\frac{5\hat{i} - 3\hat{j} + 4\hat{k}}{|5\hat{i} - 3\hat{j} + 4\hat{k}|} = \frac{5\hat{i} - 3\hat{j} + 4\hat{k}}{\sqrt{5^2 + (-3)^2 + 4^2}} = \frac{5\hat{i} - 3\hat{j} + 4\hat{k}}{\sqrt{50}}.
\]

### Note 8.3

Now we have another unit vector parallel to \( 5\hat{i} - 3\hat{j} + 4\hat{k} \) in the opposite direction. That is,

\[
-\frac{5\hat{i} - 3\hat{j} + 4\hat{k}}{\sqrt{50}}.
\]

## 8.7 Direction Cosines and Direction Ratios

Let \( P \) be a point in the space with coordinates \( (x, y, z) \) and of distance \( r \) from the origin. Let \( R, S \) and \( T \) be the foots of the perpendiculars drawn from \( P \) to the \( x, y \) and \( z \) axes respectively. Then

\[
\angle PRO = \angle PSO = \angle PTO = 90^\circ.
\]
\[
OR = x, \quad OS = y, \quad OT = z \quad \text{and} \quad OP = r.
\]

(It may be difficult to visualize that \( \angle PRO = \angle PSO = \angle PTO = 90^\circ \) in the figure; as they are foot of the perpendiculars to the axes from \( P \); in a three dimensional model we can easily visualize the fact.)

Let \( \alpha, \beta, \gamma \) be the angles made by the vector \( \overrightarrow{OP} \) with the positive \( x, y \) and \( z \) axes respectively. That is,

\[
\angle POR = \alpha, \quad \angle POS = \beta, \quad \text{and} \quad \angle POT = \gamma.
\]

**Fig.8.32**

**Fig.8.33**

In \( \triangle OPR \), \( \angle PRO = 90^\circ \), \( \angle POR = \alpha \), \( OR = x \), and \( OP = r \). Therefore

\[
\cos\alpha = \frac{OR}{OP} = \frac{x}{r}.
\]

In a similar way we can find that \( \cos\beta = \frac{y}{r} \) and \( \cos\gamma = \frac{z}{r} \).

Here the angles \( \alpha, \beta, \gamma \) are called **direction angles** of the vector \( \overrightarrow{OP} = \vec{r} \) and \( \cos\alpha, \cos\beta, \cos\gamma \) are called **direction cosines** of the vector \( \overrightarrow{OP} = x\hat{i} + y\hat{j} + z\hat{k} \). Thus \( \left( \frac{x}{r}, \frac{y}{r}, \frac{z}{r} \right) \), where \( r = \sqrt{x^2 + y^2 + z^2} \) are the direction cosines of the vector \( \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \).

Any three numbers which are proportional to the direction cosines of vector are called the **direction ratios** of the vector. Hence the direction ratios of a vector is not unique. For a given vector, we have infinitely many set of direction ratios.

### Observations

(i) For a given non-zero vector, one can find the direction ratios as well as the direction cosines.

(ii) For a given set of direction ratios, one cannot find the corresponding vector.

(iii) For a given set of direction cosines, one cannot find the corresponding vector.

(iv) For a given vector, the triplet of direction cosines is also a triplet of direction ratios.

(v) To find the vector, the magnitude as well as either the set of direction cosines or a set of direction ratios are essential.

### Note 8.4

Here we consider a vector \( \overrightarrow{OP} \) whose initial point is at the origin. If the vector whose initial point is not the origin, then, in order to find its direction cosines, we draw a vector with initial point at the origin and parallel to the given vector of same magnitude by translation. By the principle of two equal vectors having the same set of direction cosines, we can find direction cosines of any vector.

### Result 8.11

Let \( \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \) be the position vector of any point and let \( \alpha, \beta, \gamma \) be the direction angles of \( \vec{r} \). Then

(i) the sum of the squares of the direction cosines of \( \vec{r} \) is 1.

\[
\cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1
\]

(ii) \( \sin^2\alpha + \sin^2\beta + \sin^2\gamma = 2 \).

(iii) the direction cosines of \( \vec{r} \) are

\[
\left( \frac{x}{\sqrt{x^2 + y^2 + z^2}}, \frac{y}{\sqrt{x^2 + y^2 + z^2}}, \frac{z}{\sqrt{x^2 + y^2 + z^2}} \right).
\]

(iv) \( l, m, n \) are the direction cosines of a vector if and only if \( l^2 + m^2 + n^2 = 1 \).

(v) any unit vector can be written as \( \cos\alpha \hat{i} + \cos\beta \hat{j} + \cos\gamma \hat{k} \).

**Proof**

\[
\cos^2\alpha + \cos^2\beta + \cos^2\gamma = \frac{x^2}{r^2} + \frac{y^2}{r^2} + \frac{z^2}{r^2} = \frac{x^2 + y^2 + z^2}{r^2} = \frac{r^2}{r^2} = 1
\]

The proofs of (ii), (iii), (iv), and (v) are left as exercise.

### Example 8.5

Find a direction ratio and direction cosines of the following vectors.

(i) \( 3\hat{i} + 4\hat{j} - 6\hat{k} \)

**Solution**

(i) The direction ratios of \( 3\hat{i} + 4\hat{j} - 6\hat{k} \) are \( 3, 4, -6 \).

The direction cosines are \( \left( \frac{x}{r}, \frac{y}{r}, \frac{z}{r} \right) \), where \( r = \sqrt{x^2 + y^2 + z^2} \).

Therefore, the direction cosines are \( \left( \frac{3}{\sqrt{61}}, \frac{4}{\sqrt{61}}, \frac{-6}{\sqrt{61}} \right) \).

(ii) The direction ratios of \( 3\hat{i} - 4\hat{k} \) are \( 3, 0, -4 \).

The direction cosines are \( \left( \frac{3}{5}, 0, \frac{-4}{5} \right) \).

### Example 8.6

(i) Find the direction cosines of a vector whose direction ratios are \( 2, 3, -6 \).

(ii) Can a vector have direction angles \( 30^\circ, 45^\circ, 60^\circ \)?

(iii) Find the direction cosines of \( \overline{AB} \), where \( A \) is \( (2, 3, 1) \) and \( B \) is \( (3, -1, 2) \).

(iv) Find the direction cosines of the line joining \( (2, 3, 1) \) and \( (3, -1, 2) \).

(v) The direction ratios of a vector are \( 2, 3, 6 \) and its magnitude is \( 5 \). Find the vector.

**Solution**

(i) The direction cosines are \( \left( \frac{x}{\sqrt{x^2 + y^2 + z^2}}, \frac{y}{\sqrt{x^2 + y^2 + z^2}}, \frac{z}{\sqrt{x^2 + y^2 + z^2}} \right) \). That is,

\[
\left( \frac{2}{7}, \frac{3}{7}, \frac{-6}{7} \right).
\]

(ii) The condition is \( \cos^2\alpha + \cos^2\beta + \cos^2\gamma = 1 \).

Here \( \alpha = 30^\circ, \beta = 45^\circ, \gamma = 60^\circ \).

\[
\cos^2 30^\circ + \cos^2 45^\circ + \cos^2 60^\circ = \frac{3}{4} + \frac{1}{2} + \frac{1}{4} = 1.5 \neq 1.
\]

Therefore they are not direction angles of any vector.

(iii) \( \overline{AB} = \overrightarrow{OB} - \overrightarrow{OA} = \hat{i} - 4\hat{j} + \hat{k} \).

Direction cosines are \( \left( \frac{1}{\sqrt{18}}, \frac{-4}{\sqrt{18}}, \frac{1}{\sqrt{18}} \right) \).

(iv) Let \( A \) and \( B \) be the points \( (2, 3, 1) \) and \( (3, -1, 2) \). The direction cosines of \( AB \) are \( \left( \frac{1}{\sqrt{18}}, \frac{-4}{\sqrt{18}}, \frac{1}{\sqrt{18}} \right) \).

But any point can be taken as first point. Hence we have another set of direction cosines with opposite direction. Thus, we have another set of direction cosines \( \left( \frac{-1}{\sqrt{18}}, \frac{4}{\sqrt{18}}, \frac{-1}{\sqrt{18}} \right) \).

(v) The direction cosines are \( \frac{2}{7}, \frac{3}{7}, \frac{6}{7} \).

The unit vector is \( \frac{2}{7}\hat{i} + \frac{3}{7}\hat{j} + \frac{6}{7}\hat{k} \).

The required vector is \( 5\left( \frac{2}{7}\hat{i} + \frac{3}{7}\hat{j} + \frac{6}{7}\hat{k} \right) = \frac{10}{7}\hat{i} + \frac{15}{7}\hat{j} + \frac{30}{7}\hat{k} \).

### Example 8.7

Show that the points whose position vectors are \( 2\hat{i} + 3\hat{j} - 5\hat{k}, 3\hat{i} + \hat{j} - 2\hat{k} \) and \( 6\hat{i} - 5\hat{j} + 7\hat{k} \) are collinear.

**Solution**

Let \( O \) be the origin and let \( \overrightarrow{OA}, \overrightarrow{OB}, \overrightarrow{OC} \) be the vectors \( 2\hat{i} + 3\hat{j} - 5\hat{k}, 3\hat{i} + \hat{j} - 2\hat{k} \) and \( 6\hat{i} - 5\hat{j} + 7\hat{k} \) respectively. Then

\[
\overrightarrow{AB} = \hat{i} - 2\hat{j} + 3\hat{k} \quad \text{and} \quad \overrightarrow{AC} = 4\hat{i} - 8\hat{j} + 12\hat{k} = 4(\hat{i} - 2\hat{j} + 3\hat{k}).
\]

Thus \( \overrightarrow{AC} = 4\overrightarrow{AB} \) and hence \( \overrightarrow{AB} \) and \( \overrightarrow{AC} \) are parallel. They have a common point namely \( A \). Thus, the three points are collinear.

**Alternative method**

Let \( O \) be the point of reference.

Let \( \overrightarrow{OA} = 2\hat{i} + 3\hat{j} - 5\hat{k} \), \( \overrightarrow{OB} = 3\hat{i} + \hat{j} - 2\hat{k} \) and \( \overrightarrow{OC} = 6\hat{i} - 5\hat{j} + 7\hat{k} \).

\[
\overrightarrow{AB} = \hat{i} - 2\hat{j} + 3\hat{k}, \quad \overrightarrow{BC} = 3\hat{i} - 6\hat{j} + 9\hat{k}, \quad \overrightarrow{CA} = -4\hat{i} + 8\hat{j} - 12\hat{k}.
\]

\[
|\overrightarrow{AB}| = \sqrt{1 + 4 + 9} = \sqrt{14}, \quad |\overrightarrow{BC}| = \sqrt{9 + 36 + 81} = \sqrt{126} = 3\sqrt{14}, \quad |\overrightarrow{CA}| = \sqrt{16 + 64 + 144} = \sqrt{224} = 4\sqrt{14}.
\]

Thus, \( AC = AB + BC \). Hence \( A, B, C \) are lying on the same line. That is, they are collinear.

### Example 8.8

Find a point whose position vector has magnitude \( 5 \) and parallel to the vector \( 4\hat{i} - 3\hat{j} + 10\hat{k} \).

**Solution**

Let \( \vec{a} \) be the vector \( 4\hat{i} - 3\hat{j} + 10\hat{k} \). The unit vector along the direction of \( \vec{a} \) is

\[
\hat{a} = \frac{4\hat{i} - 3\hat{j} + 10\hat{k}}{5\sqrt{5}}.
\]

The vector whose magnitude is \( 5 \) and parallel to \( 4\hat{i} - 3\hat{j} + 10\hat{k} \) is

\[
5 \times \frac{4\hat{i} - 3\hat{j} + 10\hat{k}}{5\sqrt{5}} = \frac{4\hat{i} - 3\hat{j} + 10\hat{k}}{\sqrt{5}} = \frac{4}{\sqrt{5}}\hat{i} - \frac{3}{\sqrt{5}}\hat{j} + 2\sqrt{5}\hat{k}.
\]

So the required point is \( \left( \frac{4}{\sqrt{5}}, -\frac{3}{\sqrt{5}}, 2\sqrt{5} \right) \).

### Example 8.9

Prove that the points whose position vectors \( 2\hat{i} + 4\hat{j} + 3\hat{k}, 4\hat{i} + \hat{j} + 9\hat{k} \) and \( 10\hat{i} - \hat{j} + 6\hat{k} \) form a right angled triangle.

**Solution**

Let \( A, B, C \) be the given points and \( O \) be the point of reference or origin.

\[
\overrightarrow{OA} = 2\hat{i} + 4\hat{j} + 3\hat{k}, \quad \overrightarrow{OB} = 4\hat{i} + \hat{j} + 9\hat{k}, \quad \overrightarrow{OC} = 10\hat{i} - \hat{j} + 6\hat{k}
\]

\[
\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = (4\hat{i} + \hat{j} + 9\hat{k}) - (2\hat{i} + 4\hat{j} + 3\hat{k}) = 2\hat{i} - 3\hat{j} + 6\hat{k}
\]

\[
|\overrightarrow{AB}| = \sqrt{2^2 + (-3)^2 + 6^2} = \sqrt{4 + 9 + 36} = 7
\]

\[
\overrightarrow{BC} = \overrightarrow{OC} - \overrightarrow{OB} = (10\hat{i} - \hat{j} + 6\hat{k}) - (4\hat{i} + \hat{j} + 9\hat{k}) = 6\hat{i} - 2\hat{j} - 3\hat{k}
\]

\[
|\overrightarrow{BC}| = \sqrt{6^2 + (-2)^2 + (-3)^2} = \sqrt{36 + 4 + 9} = 7
\]

\[
\overrightarrow{CA} = \overrightarrow{OA} - \overrightarrow{OC} = (2\hat{i} + 4\hat{j} + 3\hat{k}) - (10\hat{i} - \hat{j} + 6\hat{k}) = -8\hat{i} + 5\hat{j} - 3\hat{k}
\]

\[
|\overrightarrow{CA}| = \sqrt{(-8)^2 + 5^2 + (-3)^2} = \sqrt{64 + 25 + 9} = \sqrt{98}
\]

\[
BC^2 = 49, \quad CA^2 = 98, \quad AB^2 = 49.
\]

Clearly \( CA^2 = BC^2 + AB^2 \).

Therefore, the given points form a right angled triangle.

### Example 8.10

Show that the vectors \( 5\hat{i} + 6\hat{j} + 7\hat{k}, 7\hat{i} - 8\hat{j} + 9\hat{k}, 3\hat{i} + 20\hat{j} + 5\hat{k} \) are coplanar.

**Solution**

Let

\[
5\hat{i} + 6\hat{j} + 7\hat{k} = s(7\hat{i} - 8\hat{j} + 9\hat{k}) + t(3\hat{i} + 20\hat{j} + 5\hat{k})
\]

Equating the components, we have

\[
5 = 7s + 3t, \quad 6 = -8s + 20t, \quad 7 = 9s + 5t
\]

Solving first two equations, we get \( s = t = \frac{1}{2} \), which satisfies the third equation.

Thus one vector is a linear combination of other two vectors. Hence the given vectors are coplanar.

## EXERCISE 8.2

1. Verify whether the following ratios are direction cosines of some vector or not.

   (i) \( \frac{1}{5}, \frac{3}{5}, \frac{4}{5} \)

   (ii) \( \frac{1}{\sqrt{2}}, \frac{1}{2}, \frac{1}{2} \)

   (iii) \( \frac{4}{3}, 0, \frac{3}{4} \)

2. Find the direction cosines of a vector whose direction ratios are

   (i) \( 1, 2, 3 \)

   (ii) \( 3, -1, 3 \)

   (iii) \( 0, 0, 7 \)

3. Find direction ratios and the direction cosines for the following vectors.

   (i) \( 3\hat{i} - 4\hat{j} + 8\hat{k} \)

   (ii) \( 3\hat{i} + \hat{j} + \hat{k} \)

   (iii) \( \hat{j} \)

   (iv) \( 5\hat{i} - 3\hat{j} - 48\hat{k} \)

   (v) \( 3\hat{i} - 3\hat{k} + 4\hat{j} \)

   (vi) \( \hat{i} - \hat{k} \)

4. A triangle is formed by joining the points \( (1, 0, 0) \), \( (0, 1, 0) \) and \( (0, 0, 1) \). Find the direction cosines of the medians.

5. If \( \frac{1}{2}, \frac{1}{\sqrt{2}}, a \) are the direction cosines of some vector, then find \( a \).

6. If \( (a, a + b, a + b + c) \) is one set of direction ratios of the line joining \( (1, 0, 0) \) and \( (0, 1, 0) \), then find a set of values of \( a, b, c \).

7. Show that the vectors \( 2\hat{i} - \hat{j} + \hat{k}, 3\hat{i} - 4\hat{j} - 4\hat{k}, \hat{i} - 3\hat{j} - 5\hat{k} \) form a right angled triangle.

8. Find the value of \( \lambda \) for which the vectors \( \vec{a} = 3\hat{i} + 2\hat{j} + 9\hat{k} \) and \( \vec{b} = \hat{i} + \lambda \hat{j} + 3\hat{k} \) are parallel.

9. Show that the following vectors are coplanar

   (i) \( \hat{i} - 2\hat{j} + 3\hat{k}, -2\hat{i} + 3\hat{j} - 4\hat{k}, -\hat{j} + 2\hat{k} \)

   (ii) \( 2\hat{i} + 3\hat{j} + \hat{k}, \hat{i} - \hat{j}, \hat{i} + 3\hat{j} + 2\hat{k} \)

10. Show that the points whose position vectors \( 4\hat{i} + 5\hat{j} + \hat{k}, -\hat{j} - \hat{k}, 3\hat{i} + 9\hat{j} + 4\hat{k} \) and \( -4\hat{i} + 4\hat{j} + 4\hat{k} \) are coplanar.

11. If \( \vec{a} = 2\hat{i} + 3\hat{j} - 4\hat{k}, \vec{b} = 3\hat{i} - 4\hat{j} - 5\hat{k} \), and \( \vec{c} = -3\hat{i} + 2\hat{j} + 3\hat{k} \), find the magnitude and direction cosines of

    (i) \( \vec{a} + \vec{b} + \vec{c} \)

    (ii) \( 3\vec{a} - 2\vec{b} + 5\vec{c} \)

12. The position vectors of the vertices of a triangle are \( \hat{i} + 2\hat{j} + 3\hat{k}, 3\hat{i} - 4\hat{j} + 5\hat{k} \) and \( -2\hat{i} + 3\hat{j} - 7\hat{k} \). Find the perimeter of the triangle.

13. Find the unit vector parallel to \( 3\vec{a} - 2\vec{b} + 4\vec{c} \) if \( \vec{a} = 3\hat{i} - \hat{j} - 4\hat{k}, \vec{b} = -2\hat{i} + 4\hat{j} - 3\hat{k}, \) and \( \vec{c} = \hat{i} + 2\hat{j} - \hat{k} \).

14. The position vectors \( \vec{a}, \vec{b}, \vec{c} \) of three points satisfy the relation \( 2\vec{a} - 7\vec{b} + 5\vec{c} = \vec{0} \). Are these points collinear?

15. The position vectors of the points \( P, Q, R, S \) are \( \hat{i} + \hat{j} + \hat{k}, 2\hat{i} + 5\hat{j}, 3\hat{i} + 2\hat{j} - 3\hat{k}, \) and \( \hat{i} - 6\hat{j} - \hat{k} \) respectively. Prove that the lines \( PQ \) and \( RS \) are parallel.

16. Find the value or values of \( m \) for which \( m(\hat{i} + \hat{j} + \hat{k}) \) is a unit vector.

17. Show that the points \( A(1, 1, 1) \), \( B(1, 2, 3) \) and \( C(2, -1, 1) \) are vertices of an isosceles triangle.

## 8.8 Product of Vectors

We have seen the notion of addition of two vectors, subtraction of one vector from another vector and the multiplication of a vector by a scalar. Now we study the notion of product of two vectors. There are two ways of multiplying two vectors.

(i) scalar product (dot product) and

(ii) vector product (cross product).

To define such products we need the angle between two vectors.

### 8.8.1 Angle between two vectors

Let \( \vec{a} \) and \( \vec{b} \) be any two vectors represented by \( \overline{OA} \) and \( \overline{OB} \) respectively. Angle between \( \vec{a} \) and \( \vec{b} \) is the angle between their directions when these directions are either both converge as in Fig. 8.36 or both diverge as in Fig. 8.34 from their point of intersection.

**Fig.8.34**

**Fig.8.35**

**Fig.8.36**

Note that, if \( \theta \) is the angle between two vectors then \( 0 \leq \theta \leq \pi \).

When \( \theta = 0 \) or \( \pi \), the vectors are parallel.

If two vectors neither converge nor diverge as in Fig. 8.35 then we can make them into either converge or diverge by extending the length of the vectors to find the angle between the two vectors.

### 8.8.2 Scalar product

### Definition 8.16

Let \( \vec{a} \) and \( \vec{b} \) be any two non-zero vectors and \( \theta \) be the included angle of the vectors as in Fig. 8.34.

Their **scalar product** or **dot product** is denoted by \( \vec{a} \cdot \vec{b} \) and is defined as a scalar \( |\vec{a}| |\vec{b}| \cos\theta \).

Thus

\[
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta.
\]

Since the resultant of \( \vec{a} \cdot \vec{b} \) is a scalar, it is called scalar product. Further we use the symbol dot \( (\cdot) \) and hence another name dot product.

### Geometrical meaning of scalar product (projection of one vector on another vector)

Let \( \overline{OA} = \vec{a} \), \( \overline{OB} = \vec{b} \) and \( \theta \) be the angle between \( \vec{a} \) and \( \vec{b} \).

Draw \( BL \) perpendicular to \( OA \). From the right triangle \( OLB \)

\[
\cos\theta = \frac{OL}{OB}
\]
\[
OL = OB \cos\theta = |\vec{b}| \cos\theta
\]

But \( OL \) is the projection of \( \vec{b} \) on \( \vec{a} \).

\[
\vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta = |\vec{a}| (OL)
\]

**Fig.8.37**

### 8.8.3 Properties of Scalar Product

(i) Scalar product of two vectors is commutative.

With usual definition, \( \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta = |\vec{b}| |\vec{a}| \cos\theta = \vec{b} \cdot \vec{a} \).

That is, for any two vectors \( \vec{a} \) and \( \vec{b} \), \( \vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{a} \).

(ii) Nature of scalar product

We know that \( 0 \leq \theta \leq \pi \).

If \( \theta = 0 \) then \( \vec{a} \cdot \vec{b} = ab \) [Two vectors are parallel in the same direction \( \Rightarrow \theta = 0 \)].

If \( \theta = \pi \) then \( \vec{a} \cdot \vec{b} = -ab \) [Two vectors are parallel in the opposite direction \( \Rightarrow \theta = \pi \)].

If \( \theta = \frac{\pi}{2} \) then \( \vec{a} \cdot \vec{b} = 0 \) [Two vectors are perpendicular \( \Rightarrow \theta = \frac{\pi}{2} \)].

If \( 0 < \theta < \frac{\pi}{2} \) then \( \cos\theta \) is positive and hence \( \vec{a} \cdot \vec{b} \) is positive.

If \( \frac{\pi}{2} < \theta < \pi \) then \( \cos\theta \) is negative and hence \( \vec{a} \cdot \vec{b} \) is negative.

That is,

\[
\vec{a} \cdot \vec{b} \text{ is } \begin{cases}
> 0 & \text{for } 0 \leq \theta < \pi/2 \\
= 0 & \text{for } \theta = \pi/2 \\
< 0 & \text{for } \pi/2 < \theta \leq \pi
\end{cases}
\]

(iii) \( \vec{a} \cdot \vec{b} = 0 \Rightarrow |\vec{a}| = 0 \) or \( |\vec{b}| = 0 \) or \( \theta = \frac{\pi}{2} \).

(iv) For any two non-zero vectors \( \vec{a} \) and \( \vec{b} \), \( \vec{a} \cdot \vec{b} = 0 \Leftrightarrow \vec{a} \) is perpendicular to \( \vec{b} \).

(v) Different ways of representations of \( \vec{a} \cdot \vec{a} \).

\[
\vec{a} \cdot \vec{a} = |\vec{a}|^2 = (\vec{a})^2 = \vec{a}^2 = a^2.
\]

These representations are essential while solving problems.

(vi) \( \hat{i} \cdot \hat{i} = \hat{j} \cdot \hat{j} = \hat{k} \cdot \hat{k} = 1 \) and \( \hat{i} \cdot \hat{j} = \hat{j} \cdot \hat{k} = \hat{k} \cdot \hat{i} = 0 \) (how?).

(vii) For any two scalars \( \lambda \) and \( \mu \)

\[
\lambda \vec{a} \cdot \mu \vec{b} = \lambda \mu (\vec{a} \cdot \vec{b}) = (\lambda \mu \vec{a}) \cdot \vec{b} = \vec{a} \cdot (\lambda \mu \vec{b}).
\]

(viii) Scalar product is distributive over vector addition.

That is, for any three vectors \( \vec{a}, \vec{b}, \vec{c} \)

\[
\vec{a} \cdot (\vec{b} + \vec{c}) = \vec{a} \cdot \vec{b} + \vec{a} \cdot \vec{c} \quad \text{(Left distributivity)}
\]
\[
(\vec{a} + \vec{b}) \cdot \vec{c} = \vec{a} \cdot \vec{c} + \vec{b} \cdot \vec{c} \quad \text{(Right distributivity)}
\]

Subsequently,

\[
\vec{a} \cdot (\vec{b} - \vec{c}) = \vec{a} \cdot \vec{b} - \vec{a} \cdot \vec{c} \quad \text{and} \quad (\vec{a} - \vec{b}) \cdot \vec{c} = \vec{a} \cdot \vec{c} - \vec{b} \cdot \vec{c}
\]

These can be extended to any number of vectors.

(ix) Vector identities

\[
(\vec{a} + \vec{b})^2 = |\vec{a}|^2 + |\vec{b}|^2 + 2\vec{a} \cdot \vec{b}
\]
\[
(\vec{a} - \vec{b})^2 = |\vec{a}|^2 + |\vec{b}|^2 - 2\vec{a} \cdot \vec{b}
\]
\[
(\vec{a} + \vec{b}) \cdot (\vec{a} - \vec{b}) = |\vec{a}|^2 - |\vec{b}|^2
\]

**Proof**

By property (viii)

\[
(\vec{a} + \vec{b})^2 = (\vec{a} + \vec{b}) \cdot (\vec{a} + \vec{b}) = |\vec{a}|^2 + |\vec{b}|^2 + \vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{a} = |\vec{a}|^2 + |\vec{b}|^2 + 2\vec{a} \cdot \vec{b}.
\]

Similarly one can prove other results.

(x) Working rule to find scalar product of two vectors

Let \( \vec{a} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} \) and \( \vec{b} = b_1\hat{i} + b_2\hat{j} + b_3\hat{k} \).

\[
\vec{a} \cdot \vec{b} = (a_1\hat{i} + a_2\hat{j} + a_3\hat{k}) \cdot (b_1\hat{i} + b_2\hat{j} + b_3\hat{k})
\]

\[
\begin{aligned}
= & a_1b_1(\hat{i} \cdot \hat{i}) + a_1b_2(\hat{i} \cdot \hat{j}) + a_1b_3(\hat{i} \cdot \hat{k}) \\
& + a_2b_1(\hat{j} \cdot \hat{i}) + a_2b_2(\hat{j} \cdot \hat{j}) + a_2b_3(\hat{j} \cdot \hat{k}) \\
& + a_3b_1(\hat{k} \cdot \hat{i}) + a_3b_2(\hat{k} \cdot \hat{j}) + a_3b_3(\hat{k} \cdot \hat{k})
\end{aligned}
\]

\[
= a_1b_1 + a_2b_2 + a_3b_3.
\]

Therefore, the scalar product of two vectors is equal to the sum of the products of their corresponding rectangular components.

(xi) If \( \theta \) is the angle between the vectors \( \vec{a} \) and \( \vec{b} \) then

\[
\theta = \cos^{-1} \left[ \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} \right].
\]

(xii) For any two vectors \( \vec{a} \) and \( \vec{b} \), \( |\vec{a} + \vec{b}| \leq |\vec{a}| + |\vec{b}| \).

We know that if \( \vec{a} \) and \( \vec{b} \) are the two sides of a triangle then the sum \( \vec{a} + \vec{b} \) represents the third side of the triangle. Therefore, by triangular property,

\[
|\vec{a} + \vec{b}| \leq |\vec{a}| + |\vec{b}|.
\]

(xiii) For any two vectors \( \vec{a} \) and \( \vec{b} \), \( |\vec{a} \cdot \vec{b}| \leq |\vec{a}| |\vec{b}| \).

If one of them is zero vector then the equality holds. So, let us assume that both are non-zero vectors. We have

\[
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|}.
\]

That is, \( \frac{|\vec{a} \cdot \vec{b}|}{|\vec{a}| |\vec{b}|} = |\cos\theta| \leq 1 \).

\[
\Rightarrow |\vec{a} \cdot \vec{b}| \leq |\vec{a}| |\vec{b}|.
\]

### Example 8.11

Find \( \vec{a} \cdot \vec{b} \) when

(i) \( \vec{a} = \hat{i} - \hat{j} + 5\hat{k} \) and \( \vec{b} = 3\hat{i} - 2\hat{k} \)

(ii) \( \vec{a} \) and \( \vec{b} \) represent the points \( (2, 3, -1) \) and \( (-1, 2, 3) \).

**Solution**

(i) \( \vec{a} \cdot \vec{b} = (1)(3) + (-1)(0) + (5)(-2) = 3 + 0 - 10 = -7 \).

(ii) \( \vec{a} = 2\hat{i} + 3\hat{j} - \hat{k} \), \( \vec{b} = -\hat{i} + 2\hat{j} + 3\hat{k} \).

\[
\vec{a} \cdot \vec{b} = (2)(-1) + (3)(2) + (-1)(3) = -2 + 6 - 3 = 1.
\]

### Example 8.12

Find \( (\vec{a} + 3\vec{b}) \cdot (2\vec{a} - \vec{b}) \) if \( \vec{a} = \hat{i} + \hat{j} + 2\hat{k} \) and \( \vec{b} = 3\hat{i} + 2\hat{j} - \hat{k} \).

**Solution**

\[
(\vec{a} + 3\vec{b}) \cdot (2\vec{a} - \vec{b}) = 2\vec{a} \cdot \vec{a} + 5\vec{a} \cdot \vec{b} - 3\vec{b} \cdot \vec{b}
\]
\[
= 2(1 + 1 + 4) + 5(3 + 2 - 2) - 3(9 + 4 + 1)
\]
\[
= 2(6) + 5(3) - 3(14) = 12 + 15 - 42 = -15.
\]

### Example 8.13

If \( \vec{a} = 2\hat{i} + 2\hat{j} + 3\hat{k} \), \( \vec{b} = -\hat{i} + 2\hat{j} + \hat{k} \) and \( \vec{c} = 3\hat{i} + \hat{j} \) be such that \( \vec{a} + \lambda \vec{b} \) is perpendicular to \( \vec{c} \), then find \( \lambda \).

**Solution**

\[
\vec{a} + \lambda \vec{b} = (2\hat{i} + 2\hat{j} + 3\hat{k}) + \lambda(-\hat{i} + 2\hat{j} + \hat{k}) = (2 - \lambda)\hat{i} + (2 + 2\lambda)\hat{j} + (3 + \lambda)\hat{k}
\]

Since \( \vec{a} + \lambda \vec{b} \) is perpendicular to \( \vec{c} \),

\[
(\vec{a} + \lambda \vec{b}) \cdot \vec{c} = 0
\]
\[
\Rightarrow [(2 - \lambda)\hat{i} + (2 + 2\lambda)\hat{j} + (3 + \lambda)\hat{k}] \cdot (3\hat{i} + \hat{j}) = 0
\]
\[
\Rightarrow 3(2 - \lambda) + 1(2 + 2\lambda) = 0
\]
\[
\Rightarrow 6 - 3\lambda + 2 + 2\lambda = 0 \Rightarrow 8 - \lambda = 0 \Rightarrow \lambda = 8.
\]

### Example 8.14

If \( |\vec{a} + \vec{b}| = |\vec{a} - \vec{b}| \), prove that \( \vec{a} \) and \( \vec{b} \) are perpendicular.

**Solution**

\[
|\vec{a} + \vec{b}| = |\vec{a} - \vec{b}|
\]
\[
|\vec{a} + \vec{b}|^2 = |\vec{a} - \vec{b}|^2
\]
\[
|\vec{a}|^2 + |\vec{b}|^2 + 2\vec{a} \cdot \vec{b} = |\vec{a}|^2 + |\vec{b}|^2 - 2\vec{a} \cdot \vec{b}
\]
\[
\Rightarrow 4\vec{a} \cdot \vec{b} = 0 \Rightarrow \vec{a} \cdot \vec{b} = 0
\]

Hence \( \vec{a} \) and \( \vec{b} \) are perpendicular.

### Example 8.15

For any vector \( \vec{r} \) prove that

\[
\vec{r} = (\vec{r} \cdot \hat{i})\hat{i} + (\vec{r} \cdot \hat{j})\hat{j} + (\vec{r} \cdot \hat{k})\hat{k}.
\]

**Solution**

Let \( \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \).

\[
\vec{r} \cdot \hat{i} = (x\hat{i} + y\hat{j} + z\hat{k}) \cdot \hat{i} = x
\]
\[
\vec{r} \cdot \hat{j} = (x\hat{i} + y\hat{j} + z\hat{k}) \cdot \hat{j} = y
\]
\[
\vec{r} \cdot \hat{k} = (x\hat{i} + y\hat{j} + z\hat{k}) \cdot \hat{k} = z
\]

\[
(\vec{r} \cdot \hat{i})\hat{i} + (\vec{r} \cdot \hat{j})\hat{j} + (\vec{r} \cdot \hat{k})\hat{k} = x\hat{i} + y\hat{j} + z\hat{k} = \vec{r}
\]

Thus \( \vec{r} = (\vec{r} \cdot \hat{i})\hat{i} + (\vec{r} \cdot \hat{j})\hat{j} + (\vec{r} \cdot \hat{k})\hat{k} \).

### Example 8.16

Find the angle between the vectors \( 5\hat{i} + 3\hat{j} + 4\hat{k} \) and \( 6\hat{i} - 8\hat{j} - \hat{k} \).

**Solution**

Let \( \vec{a} = 5\hat{i} + 3\hat{j} + 4\hat{k} \) and \( \vec{b} = 6\hat{i} - 8\hat{j} - \hat{k} \).

Let \( \theta \) be the angle between them.

\[
\vec{a} \cdot \vec{b} = (5)(6) + (3)(-8) + (4)(-1) = 30 - 24 - 4 = 2
\]
\[
|\vec{a}| = \sqrt{25 + 9 + 16} = \sqrt{50} = 5\sqrt{2}, \quad |\vec{b}| = \sqrt{36 + 64 + 1} = \sqrt{101}
\]

\[
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{2}{5\sqrt{2} \cdot \sqrt{101}} = \frac{2}{5\sqrt{202}}
\]

\[
\Rightarrow \theta = \cos^{-1} \left( \frac{2}{5\sqrt{202}} \right).
\]

### Example 8.17

Find the projection of \( \overrightarrow{AB} \) on \( \overrightarrow{CD} \) where \( A, B, C, D \) are the points \( (4, -3, 0) \), \( (7, -5, -1) \), \( (-2, 1, 3) \), \( (0, 2, 5) \).

**Solution**

Let \( O \) be the origin.

Therefore,
\[
\overrightarrow{OA} = 4\hat{i} - 3\hat{j}, \quad \overrightarrow{OB} = 7\hat{i} - 5\hat{j} - \hat{k}, \quad \overrightarrow{OC} = -2\hat{i} + \hat{j} + 3\hat{k}, \quad \overrightarrow{OD} = 2\hat{j} + 5\hat{k}
\]

\[
\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = 3\hat{i} - 2\hat{j} - \hat{k}, \quad \overrightarrow{CD} = \overrightarrow{OD} - \overrightarrow{OC} = 2\hat{i} + \hat{j} + 2\hat{k}
\]

Projection of \( \overrightarrow{AB} \) on \( \overrightarrow{CD} \) is

\[
\frac{\overrightarrow{AB} \cdot \overrightarrow{CD}}{|\overrightarrow{CD}|} = \frac{3(2) + (-2)(1) + (-1)(2)}{\sqrt{4 + 1 + 4}} = \frac{6 - 2 - 2}{3} = \frac{2}{3}.
\]

### Example 8.18

If \( \vec{a}, \vec{b}, \vec{c} \) are three unit vectors satisfying \( \vec{a} - \sqrt{3}\vec{b} + \vec{c} = \vec{0} \), then find the angle between \( \vec{a} \) and \( \vec{c} \).

**Solution**

Let \( \theta \) be the angle between \( \vec{a} \) and \( \vec{c} \).

\[
\vec{a} - \sqrt{3}\vec{b} + \vec{c} = \vec{0} \Rightarrow \vec{a} + \vec{c} = \sqrt{3}\vec{b}
\]

\[
\Rightarrow |\vec{a} + \vec{c}|^2 = |\sqrt{3}\vec{b}|^2 = 3|\vec{b}|^2 = 3(1)^2 = 3
\]

\[
\Rightarrow |\vec{a}|^2 + |\vec{c}|^2 + 2|\vec{a}||\vec{c}|\cos\theta = 3
\]

\[
\Rightarrow 1 + 1 + 2(1)(1)\cos\theta = 3
\]

\[
\Rightarrow 2 + 2\cos\theta = 3 \Rightarrow \cos\theta = \frac{1}{2}
\]

\[
\Rightarrow \theta = \frac{\pi}{3}.
\]

### Example 8.19

Show that the points \( (4, -3, 1) \), \( (2, -4, 5) \) and \( (1, -1, 0) \) form a right angled triangle.

**Solution**

Trivially they form a triangle. It is enough to prove one angle is \( \frac{\pi}{2} \). So find the sides of the triangle.

Let \( O \) be the point of reference and \( A, B, C \) be \( (4, -3, 1) \), \( (2, -4, 5) \) and \( (1, -1, 0) \) respectively.

\[
\overrightarrow{OA} = 4\hat{i} - 3\hat{j} + \hat{k}, \quad \overrightarrow{OB} = 2\hat{i} - 4\hat{j} + 5\hat{k}, \quad \overrightarrow{OC} = \hat{i} - \hat{j}
\]

Now,
\[
\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = -2\hat{i} - \hat{j} + 4\hat{k}
\]

Similarly,
\[
\overrightarrow{BC} = \overrightarrow{OC} - \overrightarrow{OB} = -\hat{i} + 3\hat{j} - 5\hat{k}, \quad \overrightarrow{CA} = \overrightarrow{OA} - \overrightarrow{OC} = 3\hat{i} - 2\hat{j} + \hat{k}
\]

Clearly,
\[
\overrightarrow{AB} \cdot \overrightarrow{CA} = (-2)(3) + (-1)(-2) + (4)(1) = -6 + 2 + 4 = 0
\]

Thus one angle is \( \frac{\pi}{2} \). Hence they form a right angled triangle.

### Note 8.5

Suppose three sides are given in vector form, prove

(i) either sum of the vectors is \( \vec{0} \) or sum of any two vectors is equal to the third vector, to form a triangle.

(ii) dot product between any two vectors is \( 0 \) to ensure one angle is \( \frac{\pi}{2} \).

## EXERCISE 8.3

1. Find \( \vec{a} \cdot \vec{b} \) when

   (i) \( \vec{a} = \hat{i} - 2\hat{j} + \hat{k} \) and \( \vec{b} = 3\hat{i} - 4\hat{j} - 2\hat{k} \)

   (ii) \( \vec{a} = 2\hat{i} + 2\hat{j} - \hat{k} \) and \( \vec{b} = 6\hat{i} - 3\hat{j} + 2\hat{k} \)

2. Find the value \( \lambda \) for which the vectors \( \vec{a} \) and \( \vec{b} \) are perpendicular, where

   (i) \( \vec{a} = 2\hat{i} + \lambda \hat{j} + \hat{k} \) and \( \vec{b} = \hat{i} - 2\hat{j} + 3\hat{k} \)

   (ii) \( \vec{a} = 2\hat{i} + 4\hat{j} - \hat{k} \) and \( \vec{b} = 3\hat{i} - 2\hat{j} + \lambda \hat{k} \)

3. If \( \vec{a} \) and \( \vec{b} \) are two vectors such that \( |\vec{a}| = 10, |\vec{b}| = 15 \) and \( \vec{a} \cdot \vec{b} = 75\sqrt{2} \), find the angle between \( \vec{a} \) and \( \vec{b} \).

4. Find the angle between the vectors

   (i) \( 2\hat{i} + 3\hat{j} - 6\hat{k} \) and \( 6\hat{i} - 3\hat{j} + 2\hat{k} \)

   (ii) \( \hat{i} - \hat{j} \) and \( \hat{j} - \hat{k} \)

5. If \( \vec{a}, \vec{b}, \vec{c} \) are three vectors such that \( \vec{a} + 2\vec{b} + \vec{c} = \vec{0} \) and \( |\vec{a}| = 3, |\vec{b}| = 4, |\vec{c}| = 7 \), find the angle between \( \vec{a} \) and \( \vec{b} \).

6. Show that the vectors \( \vec{a} = 2\hat{i} + 3\hat{j} + 6\hat{k} \), \( \vec{b} = 6\hat{i} + 2\hat{j} - 3\hat{k} \) and \( \vec{c} = 3\hat{i} - 6\hat{j} + 2\hat{k} \) are mutually orthogonal.

7. Show that the vectors \( -\hat{i} - 2\hat{j} - 6\hat{k}, 2\hat{i} - \hat{j} + \hat{k} \) and \( -\hat{i} + 3\hat{j} + 5\hat{k} \) form a right angled triangle.

8. If \( |\vec{a}| = 5, |\vec{b}| = 6, |\vec{c}| = 7 \) and \( \vec{a} + \vec{b} + \vec{c} = \vec{0} \), find \( \vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{c} + \vec{c} \cdot \vec{a} \).

9. Show that the points \( (2, -1, 3) \), \( (4, 3, 1) \) and \( (3, 1, 2) \) are collinear.

10. If \( \hat{a}, \hat{b} \) are unit vectors and \( \theta \) is the angle between them, show that

    (i) \( \sin\frac{\theta}{2} = \frac{1}{2}|\hat{a} - \hat{b}| \)

    (ii) \( \cos\frac{\theta}{2} = \frac{1}{2}|\hat{a} + \hat{b}| \)

    (iii) \( \tan\frac{\theta}{2} = \frac{|\hat{a} - \hat{b}|}{|\hat{a} + \hat{b}|} \)

11. Let \( \vec{a}, \vec{b}, \vec{c} \) be three vectors such that \( |\vec{a}| = 3, |\vec{b}| = 4, |\vec{c}| = 5 \) and each one of them being perpendicular to the sum of the other two, find \( |\vec{a} + \vec{b} + \vec{c}| \).

12. Find the projection of the vector \( \hat{i} + 3\hat{j} + 7\hat{k} \) on the vector \( 2\hat{i} + 6\hat{j} + 3\hat{k} \).

13. Find \( \lambda \), when the projection of \( \vec{a} = \lambda \hat{i} + \hat{j} + 4\hat{k} \) on \( \vec{b} = 2\hat{i} + 6\hat{j} + 3\hat{k} \) is 4 units.

14. Three vectors \( \vec{a}, \vec{b} \) and \( \vec{c} \) are such that \( |\vec{a}| = 2, |\vec{b}| = 3, |\vec{c}| = 4 \), and \( \vec{a} + \vec{b} + \vec{c} = \vec{0} \). Find \( 4\vec{a} \cdot \vec{b} + 3\vec{b} \cdot \vec{c} + 3\vec{c} \cdot \vec{a} \).

### 8.8.4 Vector Product

To define vector product between two vectors, we need the concept of right handed and left handed system.

If we align the fingers of our right hand along the vector \( \vec{a} \) and bend our fingers around in the direction of rotation from \( \vec{a} \) towards \( \vec{b} \) (through an angle less than \( 180^\circ \)), our thumb will point in the direction of \( \vec{a} \times \vec{b} \). Now, following the right-hand rule, \( \vec{b} \times \vec{a} \) will point in the direction opposite to \( \vec{a} \times \vec{b} \) (See Fig. 8.38).

We may also say that if \( \vec{a} \) is rotated into the direction of \( \vec{b} \) through the angle \( \theta ( < \pi) \), then \( \vec{a} \times \vec{b} \) advances in the same direction as a right-handed screw would if turned in the same way.

A Cartesian coordinate system is called right-handed if the corresponding unit vectors \( \vec{i}, \vec{j}, \vec{k} \) in the positive direction of the axes form a right-handed triple as in Fig. 8.39. The system is called left handed if the sense of \( \vec{k} \) is reversed as in Fig 8.40.

**Fig. 8.38**

**Right handed Fig.8.39**

**Left handed Fig.8.40**

**Right handed screw Fig.8.41**

**Left handed screw Fig.8.42**

### Definition 8.17

Vector product of any two non-zero vectors \( \vec{a} \) and \( \vec{b} \) is written as \( \vec{a} \times \vec{b} \) and is defined as

\[
\vec{a} \times \vec{b} = |\vec{a}| |\vec{b}| \sin\theta \, \hat{n},
\]

where \( \theta \) is the angle between \( \vec{a} \) and \( \vec{b} \), \( 0 \leq \theta \leq \pi \).

Here \( \vec{a}, \vec{b}, \hat{n} \) form a right handed system.

**Fig.8.43**

The resultant is a vector with magnitude \( |\vec{a}| |\vec{b}| \sin\theta \) and has the direction \( \hat{n} \).

Further \( \vec{a} \times \vec{b} \) is a vector perpendicular to both \( \vec{a} \) and \( \vec{b} \). That is, \( \vec{a} \times \vec{b} \) is normal to the plane containing \( \vec{a} \) and \( \vec{b} \).

### Note 8.6

(i) Note that the order of the vectors is very important to decide the direction of \( \hat{n} \).

(ii) Since the resultant is a vector, this product is named as vector product. Again, we use the symbol cross '\( \times \)' to define such a product and hence it has another name cross product.

### Geometrical interpretation of vector product

Construct a parallelogram \( OACB \) with \( \overline{OA} = \vec{a} \) and \( \overline{OB} = \vec{b} \) as adjacent sides.

Let \( \angle AOB = \theta \). From the diagram,

\[
\sin\theta = \frac{BL}{OB}
\]
\[
BL = (OB) \sin\theta = |\vec{b}| \sin\theta
\]

**Fig.8.44**

\[
|\vec{a} \times \vec{b}| = |\vec{a}| |\vec{b}| \sin\theta = |\vec{a}| (BL)
\]
\[
= (\text{base})(\text{height}) = \text{area of the parallelogram } OACB.
\]

Thus, \( \vec{a} \times \vec{b} \) is a vector whose magnitude is the area of the parallelogram, having \( \vec{a} \) and \( \vec{b} \) as its adjacent sides and whose direction \( \hat{n} \) is perpendicular to the plane containing \( \vec{a} \) and \( \vec{b} \) such that \( \vec{a}, \vec{b}, \hat{n} \) form a right handed system.

Thus, \( |\vec{a} \times \vec{b}| = \) area of the parallelogram whose adjacent sides are \( \vec{a} \) and \( \vec{b} \).

### Deduction

From the area of the parallelogram, we can deduce the area of the triangle \( OAB \) as half of the area of \( OACB \).

\[
\text{Area of triangle } OAB = \frac{1}{2} |\vec{a} \times \vec{b}|
\]

The area of any triangle whose two sides are \( \vec{a} \) and \( \vec{b} = \frac{1}{2} |\vec{a} \times \vec{b}| \).

### 8.8.5 Properties

(i) **Vector product is non-commutative**

By definition

\[
\vec{b} \times \vec{a} = |\vec{b}| |\vec{a}| \sin\theta (-\hat{n}) \quad [\text{since } \vec{b}, \vec{a}, -\hat{n} \text{ for a right handed system}]
\]
\[
= -|\vec{a}| |\vec{b}| \sin\theta \, \hat{n} = -(\vec{a} \times \vec{b})
\]

Thus vector product is non-commutative.

**Fig.8.45**

(ii) If two vectors are collinear or parallel then \( \vec{a} \times \vec{b} = \vec{0} \) (how?)

But \( \vec{a} \times \vec{b} = \vec{0} \Rightarrow \vec{a} = \vec{0} \) or \( \vec{b} = \vec{0} \) or \( \vec{a} \) and \( \vec{b} \) are parallel.

(iii) For any two non-zero vectors \( \vec{a} \) and \( \vec{b} \), \( \vec{a} \times \vec{b} = \vec{0} \Leftrightarrow \vec{a} \) and \( \vec{b} \) are parallel.

**Deduction**

\[
\vec{a} \times \vec{a} = \vec{0}
\]

(iv) With usual meaning of \( \hat{i}, \hat{j} \) and \( \hat{k} \) (they form a right handed system), the following results are obtained.

It is clear that,

\[
\hat{i} \times \hat{i} = \hat{j} \times \hat{j} = \hat{k} \times \hat{k} = \vec{0}
\]
\[
\hat{i} \times \hat{j} = \hat{k}, \quad \hat{j} \times \hat{k} = \hat{i}, \quad \hat{k} \times \hat{i} = \hat{j}
\]
\[
\hat{j} \times \hat{i} = -\hat{k}, \quad \hat{k} \times \hat{j} = -\hat{i}, \quad \hat{i} \times \hat{k} = -\hat{j} \quad \text{(how?)}
\]

**Fig.8.46**

(v) If \( \theta = \frac{\pi}{2} \) then \( \vec{a} \times \vec{b} = |\vec{a}| |\vec{b}| \hat{n} \).

(vi) For any scalars \( m \) and \( n \)

\[
m\vec{a} \times n\vec{b} = mn(\vec{a} \times \vec{b}) = (mn\vec{a}) \times \vec{b} = \vec{a} \times (mn\vec{b}) = n\vec{a} \times m\vec{b}.
\]

(vii) **Vector product is distributive over addition.**

\[
\vec{a} \times (\vec{b} + \vec{c}) = (\vec{a} \times \vec{b}) + (\vec{a} \times \vec{c})
\]
\[
(\vec{a} + \vec{b}) \times \vec{c} = (\vec{a} \times \vec{c}) + (\vec{b} \times \vec{c})
\]

This property can be extended to subtraction and to any number of vectors.

\[
\vec{a} \times (\vec{b} - \vec{c}) = (\vec{a} \times \vec{b}) - (\vec{a} \times \vec{c})
\]
\[
\vec{a} \times (\vec{b} + \vec{c} + \vec{d}) = (\vec{a} \times \vec{b}) + (\vec{a} \times \vec{c}) + (\vec{a} \times \vec{d})
\]

(viii) **Working rule to find the cross product**

Let \( \vec{a} = a_1\hat{i} + a_2\hat{j} + a_3\hat{k} \), \( \vec{b} = b_1\hat{i} + b_2\hat{j} + b_3\hat{k} \).

\[
\vec{a} \times \vec{b} = (a_1\hat{i} + a_2\hat{j} + a_3\hat{k}) \times (b_1\hat{i} + b_2\hat{j} + b_3\hat{k})
\]

\[
\begin{aligned}
= & a_1b_1(\hat{i} \times \hat{i}) + a_1b_2(\hat{i} \times \hat{j}) + a_1b_3(\hat{i} \times \hat{k}) \\
& + a_2b_1(\hat{j} \times \hat{i}) + a_2b_2(\hat{j} \times \hat{j}) + a_2b_3(\hat{j} \times \hat{k}) \\
& + a_3b_1(\hat{k} \times \hat{i}) + a_3b_2(\hat{k} \times \hat{j}) + a_3b_3(\hat{k} \times \hat{k})
\end{aligned}
\]

\[
= (a_2b_3 - a_3b_2)\hat{i} - (a_1b_3 - a_3b_1)\hat{j} + (a_1b_2 - a_2b_1)\hat{k}
\]

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3
\end{vmatrix}
\]

(ix) If \( \theta \) is the angle between \( \vec{a} \) and \( \vec{b} \) then

\[
\theta = \sin^{-1} \left[ \frac{|\vec{a} \times \vec{b}|}{|\vec{a}| |\vec{b}|} \right].
\]

(The proof of this result is left as an exercise)

### Note 8.7

In this case \( \theta \) is always acute. Thus, if we try to find the angle using vector product, we get only the acute angle. Hence in problems of finding the angle, the use of dot product is preferable since it specifies the position of the angle \( \theta \).

(x) The unit vectors perpendicular to both \( \vec{a} \) and \( \vec{b} \) are

\[
\pm \hat{n} = \pm \frac{\vec{a} \times \vec{b}}{|\vec{a} \times \vec{b}|} \quad \text{(how?)}
\]

Vectors of magnitude \( \lambda \), perpendicular to both \( \vec{a} \) and \( \vec{b} \) are

\[
\pm \lambda \hat{n} = \pm \lambda \frac{\vec{a} \times \vec{b}}{|\vec{a} \times \vec{b}|}.
\]

### Example 8.20

Find \( |\vec{a} \times \vec{b}| \), where \( \vec{a} = 3\hat{i} + 4\hat{j} \) and \( \vec{b} = \hat{i} + \hat{j} + \hat{k} \).

**Solution**

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
3 & 4 & 0 \\
1 & 1 & 1
\end{vmatrix} = \hat{i}(4 \cdot 1 - 0 \cdot 1) - \hat{j}(3 \cdot 1 - 0 \cdot 1) + \hat{k}(3 \cdot 1 - 4 \cdot 1)
\]
\[
= \hat{i}(4) - \hat{j}(3) + \hat{k}(-1) = 4\hat{i} - 3\hat{j} - \hat{k}
\]
\[
|\vec{a} \times \vec{b}| = \sqrt{16 + 9 + 1} = \sqrt{26}.
\]

### Example 8.21

If \( \vec{a} = -3\hat{i} + 4\hat{j} - 7\hat{k} \) and \( \vec{b} = 6\hat{i} + 2\hat{j} - 3\hat{k} \), verify

(i) \( \vec{a} \) and \( \vec{a} \times \vec{b} \) are perpendicular to each other.

(ii) \( \vec{b} \) and \( \vec{a} \times \vec{b} \) are perpendicular to each other.

**Solution**

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
-3 & 4 & -7 \\
6 & 2 & -3
\end{vmatrix}
\]
\[
= \hat{i}[4(-3) - (-7)(2)] - \hat{j}[(-3)(-3) - (-7)(6)] + \hat{k}[(-3)(2) - 4(6)]
\]
\[
= \hat{i}[-12 + 14] - \hat{j}[9 + 42] + \hat{k}[-6 - 24] = 2\hat{i} - 51\hat{j} - 30\hat{k}
\]

\[
\vec{a} \cdot (\vec{a} \times \vec{b}) = (-3\hat{i} + 4\hat{j} - 7\hat{k}) \cdot (2\hat{i} - 51\hat{j} - 30\hat{k}) = -6 - 204 + 210 = 0.
\]

Therefore, \( \vec{a} \) and \( \vec{a} \times \vec{b} \) are perpendicular.

\[
\vec{b} \cdot (\vec{a} \times \vec{b}) = (6\hat{i} + 2\hat{j} - 3\hat{k}) \cdot (2\hat{i} - 51\hat{j} - 30\hat{k}) = 12 - 102 + 90 = 0.
\]

Therefore \( \vec{b} \) and \( \vec{a} \times \vec{b} \) are perpendicular.

### Example 8.22

Find the vectors of magnitude \( 6 \) which are perpendicular to both vectors

\[
\vec{a} = 4\hat{i} - \hat{j} + 3\hat{k} \quad \text{and} \quad \vec{b} = -2\hat{i} + \hat{j} - 2\hat{k}.
\]

**Solution**

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
4 & -1 & 3 \\
-2 & 1 & -2
\end{vmatrix} = \hat{i}[(-1)(-2) - (3)(1)] - \hat{j}[(4)(-2) - (3)(-2)] + \hat{k}[(4)(1) - (-1)(-2)]
\]
\[
= \hat{i}[2 - 3] - \hat{j}[-8 + 6] + \hat{k}[4 - 2] = -\hat{i} + 2\hat{j} + 2\hat{k}
\]

\[
|\vec{a} \times \vec{b}| = \sqrt{1 + 4 + 4} = 3
\]

Unit vectors perpendicular to both \( \vec{a} \) and \( \vec{b} \) are

\[
\pm \frac{\vec{a} \times \vec{b}}{|\vec{a} \times \vec{b}|} = \pm \left[ \frac{-\hat{i} + 2\hat{j} + 2\hat{k}}{3} \right]
\]

Vectors of magnitude \( 6 \) perpendicular to both \( \vec{a} \) and \( \vec{b} \) are

\[
6 \times \pm \frac{-\hat{i} + 2\hat{j} + 2\hat{k}}{3} = \pm 2(-\hat{i} + 2\hat{j} + 2\hat{k})
\]

### Example 8.23

Find the cosine and sine angle between the vectors \( \vec{a} = 2\hat{i} + \hat{j} + 3\hat{k} \) and \( \vec{b} = 4\hat{i} - 2\hat{j} + 2\hat{k} \).

**Solution**

Let \( \theta \) be the angle between \( \vec{a} \) and \( \vec{b} \).

\[
\vec{a} \cdot \vec{b} = (2\hat{i} + \hat{j} + 3\hat{k}) \cdot (4\hat{i} - 2\hat{j} + 2\hat{k}) = 8 - 2 + 6 = 12
\]
\[
|\vec{a}| = |2\hat{i} + \hat{j} + 3\hat{k}| = \sqrt{4 + 1 + 9} = \sqrt{14}
\]
\[
|\vec{b}| = |4\hat{i} - 2\hat{j} + 2\hat{k}| = \sqrt{16 + 4 + 4} = \sqrt{24}
\]

\[
\cos\theta = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| |\vec{b}|} = \frac{12}{\sqrt{14} \sqrt{24}} = \frac{12}{\sqrt{336}} = \frac{12}{4\sqrt{21}} = \frac{3}{\sqrt{21}} = \sqrt{\frac{3}{7}}
\]

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & 1 & 3 \\
4 & -2 & 2
\end{vmatrix} = \hat{i}[(1)(2) - (3)(-2)] - \hat{j}[(2)(2) - (3)(4)] + \hat{k}[(2)(-2) - (1)(4)]
\]
\[
= \hat{i}[2 + 6] - \hat{j}[4 - 12] + \hat{k}[-4 - 4] = 8\hat{i} + 8\hat{j} - 8\hat{k}
\]
\[
|\vec{a} \times \vec{b}| = \sqrt{64 + 64 + 64} = \sqrt{192} = 8\sqrt{3}
\]

\[
\sin\theta = \frac{|\vec{a} \times \vec{b}|}{|\vec{a}| |\vec{b}|} = \frac{8\sqrt{3}}{\sqrt{14} \sqrt{24}} = \frac{8\sqrt{3}}{\sqrt{336}} = \frac{8\sqrt{3}}{4\sqrt{21}} = \frac{2}{\sqrt{7}}.
\]

### Example 8.24

Find the area of the parallelogram whose adjacent sides are \( \vec{a} = 3\hat{i} + \hat{j} + 4\hat{k} \) and \( \vec{b} = \hat{i} - \hat{j} + \hat{k} \).

**Solution**

\[
\vec{a} \times \vec{b} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
3 & 1 & 4 \\
1 & -1 & 1
\end{vmatrix} = \hat{i}[(1)(1) - (4)(-1)] - \hat{j}[(3)(1) - (4)(1)] + \hat{k}[(3)(-1) - (1)(1)]
\]
\[
= \hat{i}[1 + 4] - \hat{j}[3 - 4] + \hat{k}[-3 - 1] = 5\hat{i} + \hat{j} - 4\hat{k}
\]
\[
|\vec{a} \times \vec{b}| = \sqrt{25 + 1 + 16} = \sqrt{42}
\]

Area of the parallelogram is \( \sqrt{42} \) sq.units.

### Example 8.25

For any two vectors \( \vec{a} \) and \( \vec{b} \), prove that \( |\vec{a} \times \vec{b}|^2 + (\vec{a} \cdot \vec{b})^2 = |\vec{a}|^2 |\vec{b}|^2 \).

**Solution**

\[
|\vec{a} \times \vec{b}| = |\vec{a}| |\vec{b}| \sin\theta, \quad \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta
\]
\[
|\vec{a} \times \vec{b}|^2 + (\vec{a} \cdot \vec{b})^2 = |\vec{a}|^2 |\vec{b}|^2 \sin^2\theta + |\vec{a}|^2 |\vec{b}|^2 \cos^2\theta
\]
\[
= |\vec{a}|^2 |\vec{b}|^2 (\sin^2\theta + \cos^2\theta) = |\vec{a}|^2 |\vec{b}|^2.
\]

### Example 8.26

Find the area of a triangle having the points \( A(1, 0, 0) \), \( B(0, 1, 0) \), and \( C(0, 0, 1) \) as its vertices.

**Solution**

Let us find two sides of the triangle.

\[
\overline{AB} = -\hat{i} + \hat{j}, \quad \overline{AC} = -\hat{i} + \hat{k}
\]
\[
\overline{AB} \times \overline{AC} = \begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
-1 & 1 & 0 \\
-1 & 0 & 1
\end{vmatrix} = \hat{i}[(1)(1) - (0)(0)] - \hat{j}[(-1)(1) - (0)(-1)] + \hat{k}[(-1)(0) - (1)(-1)]
\]
\[
= \hat{i}[1] - \hat{j}[-1] + \hat{k}[1] = \hat{i} + \hat{j} + \hat{k}
\]
\[
|\overline{AB} \times \overline{AC}| = \sqrt{1 + 1 + 1} = \sqrt{3}
\]

The area of the triangle \( ABC \) is \( \frac{1}{2} |\overline{AB} \times \overline{AC}| = \frac{\sqrt{3}}{2} \).

### Note 8.8

Instead of \( \overline{AB} \) and \( \overline{AC} \), one can take any two sides.

## EXERCISE 8.4

1. Find the magnitude of \( \vec{a} \times \vec{b} \) if \( \vec{a} = 2\hat{i} + \hat{j} + 3\hat{k} \) and \( \vec{b} = 3\hat{i} + 5\hat{j} - 2\hat{k} \).

2. Show that \( \vec{a} \times (\vec{b} + \vec{c}) + \vec{b} \times (\vec{c} + \vec{a}) + \vec{c} \times (\vec{a} + \vec{b}) = \vec{0} \).

3. Find the vectors of magnitude \( 10\sqrt{3} \) that are perpendicular to the plane which contains
   \( \hat{i} + 2\hat{j} + \hat{k} \) and \( \hat{i} + 3\hat{j} + 4\hat{k} \).

4. Find the unit vectors perpendicular to each of the vectors
   \( \vec{a} + \vec{b} \) and \( \vec{a} - \vec{b} \), where \( \vec{a} = \hat{i} + \hat{j} + \hat{k} \) and \( \vec{b} = \hat{i} + 2\hat{j} + 3\hat{k} \).

5. Find the area of the parallelogram whose two adjacent sides are determined by the vectors \( \hat{i} + 2\hat{j} + 3\hat{k} \) and \( 3\hat{i} - 2\hat{j} + \hat{k} \).

6. Find the area of the triangle whose vertices are \( A(3, -1, 2) \), \( B(1, -1, -3) \) and \( C(4, -3, 1) \).

7. If \( \vec{a}, \vec{b}, \vec{c} \) are position vectors of the vertices \( A, B, C \) of a triangle \( ABC \), show that the area of the triangle \( ABC \) is \( \frac{1}{2} |\vec{a} \times \vec{b} + \vec{b} \times \vec{c} + \vec{c} \times \vec{a}| \). Also deduce the condition for collinearity of the points \( A, B \) and \( C \).

8. For any vector \( \vec{a} \) prove that \( |\vec{a} \times \hat{i}|^2 + |\vec{a} \times \hat{j}|^2 + |\vec{a} \times \hat{k}|^2 = 2|\vec{a}|^2 \).

9. Let \( \vec{a}, \vec{b}, \vec{c} \) be unit vectors such that \( \vec{a} \cdot \vec{b} = \vec{a} \cdot \vec{c} = 0 \) and the angle between \( \vec{b} \) and \( \vec{c} \) is \( \frac{\pi}{3} \). Prove that \( \vec{a} = \pm \frac{2}{\sqrt{3}} (\vec{b} \times \vec{c}) \).

10. Find the angle between the vectors \( 2\hat{i} + \hat{j} - \hat{k} \) and \( \hat{i} + 2\hat{j} + \hat{k} \) using vector product.

## EXERCISE 8.5

### Choose the correct or the most suitable answer from the given four alternatives

1. The value of \( \overrightarrow{AB} + \overrightarrow{BC} + \overrightarrow{DA} + \overrightarrow{CD} \) is

   (1) \( \overrightarrow{AD} \)

   (2) \( \overrightarrow{CA} \)

   (3) \( \vec{0} \)

   (4) \( -\overrightarrow{AD} \)

2. If \( \vec{a} + 2\vec{b} \) and \( 3\vec{a} + m\vec{b} \) are parallel, then the value of \( m \) is

   (1) \( 3 \)

   (2) \( \frac{1}{3} \)

   (3) \( 6 \)

   (4) \( \frac{1}{6} \)

3. The unit vector parallel to the resultant of the vectors \( \hat{i} + \hat{j} - \hat{k} \) and \( \hat{i} - 2\hat{j} + \hat{k} \) is

   (1) \( \frac{\hat{i} - \hat{j} + \hat{k}}{\sqrt{5}} \)

   (2) \( \frac{2\hat{i} + \hat{j}}{\sqrt{5}} \)

   (3) \( \frac{2\hat{i} - \hat{j} + \hat{k}}{\sqrt{5}} \)

   (4) \( \frac{2\hat{i} - \hat{j}}{\sqrt{5}} \)

4. A vector \( \overrightarrow{OP} \) makes \( 60^\circ \) and \( 45^\circ \) with the positive direction of the \( x \) and \( y \) axes respectively. Then the angle between \( \overrightarrow{OP} \) and the \( z \)-axis is

   (1) \( 45^\circ \)

   (2) \( 60^\circ \)

   (3) \( 90^\circ \)

   (4) \( 30^\circ \)

5. If \( \overrightarrow{BA} = 3\hat{i} + 2\hat{j} + \hat{k} \) and the position vector of \( B \) is \( \hat{i} + 3\hat{j} - \hat{k} \), then the position vector \( A \) is

   (1) \( 4\hat{i} + 2\hat{j} + \hat{k} \)

   (2) \( 4\hat{i} + 5\hat{j} \)

   (3) \( 4\hat{i} \)

   (4) \( -4\hat{i} \)

6. A vector makes equal angle with the positive direction of the coordinate axes. Then each angle is equal to

   (1) \( \cos^{-1}\left(\frac{1}{3}\right) \)

   (2) \( \cos^{-1}\left(\frac{2}{3}\right) \)

   (3) \( \cos^{-1}\left(\frac{1}{\sqrt{3}}\right) \)

   (4) \( \cos^{-1}\left(\frac{2}{\sqrt{3}}\right) \)

7. The vectors \( \vec{a} - \vec{b}, \vec{b} - \vec{c}, \vec{c} - \vec{a} \) are

   (1) parallel to each other

   (2) unit vectors

   (3) mutually perpendicular vectors

   (4) coplanar vectors

8. If \( ABCD \) is a parallelogram, then \( \overrightarrow{AB} + \overrightarrow{AD} + \overrightarrow{CB} + \overrightarrow{CD} \) is equal to

   (1) \( 2(\overrightarrow{AB} + \overrightarrow{AD}) \)

   (2) \( 4\overrightarrow{AC} \)

   (3) \( 4\overrightarrow{BD} \)

   (4) \( \vec{0} \)

9. One of the diagonals of parallelogram \( ABCD \) with \( \vec{a} \) and \( \vec{b} \) as adjacent sides is \( \vec{a} + \vec{b} \). The other diagonal \( \overrightarrow{BD} \) is

   (1) \( \vec{a} - \vec{b} \)

   (2) \( \vec{b} - \vec{a} \)

   (3) \( \vec{a} + \vec{b} \)

   (4) \( \frac{\vec{a} + \vec{b}}{2} \)

10. If \( \vec{a}, \vec{b} \) are the position vectors of \( A \) and \( B \), then which one of the following points whose position vector lies on \( AB \), is

    (1) \( \vec{a} + \vec{b} \)

    (2) \( \frac{2\vec{a} - \vec{b}}{2} \)

    (3) \( \frac{2\vec{a} + \vec{b}}{3} \)

    (4) \( \frac{\vec{a} - \vec{b}}{3} \)

11. If \( \vec{a}, \vec{b}, \vec{c} \) are the position vectors of three collinear points, then which of the following is true?

    (1) \( \vec{a} = \vec{b} + \vec{c} \)

    (2) \( 2\vec{a} = \vec{b} + \vec{c} \)

    (3) \( \vec{b} = \vec{c} + \vec{a} \)

    (4) \( 4\vec{a} + \vec{b} + \vec{c} = \vec{0} \)

12. If \( \vec{r} = \frac{9\vec{a} + 7\vec{b}}{16} \), then the point \( P \) whose position vector \( \vec{r} \) divides the line joining the points with position vectors \( \vec{a} \) and \( \vec{b} \) in the ratio

    (1) \( 7 : 9 \) internally

    (2) \( 9 : 7 \) internally

    (3) \( 9 : 7 \) externally

    (4) \( 7 : 9 \) externally

13. If \( \lambda \hat{i} + 2\lambda \hat{j} + 2\lambda \hat{k} \) is a unit vector, then the value of \( \lambda \) is

    (1) \( \frac{1}{3} \)

    (2) \( \frac{1}{4} \)

    (3) \( \frac{1}{9} \)

    (4) \( \frac{1}{2} \)

14. Two vertices of a triangle have position vectors \( 3\hat{i} + 4\hat{j} - 4\hat{k} \) and \( 2\hat{i} + 3\hat{j} + 4\hat{k} \). If the position vector of the centroid is \( \hat{i} + 2\hat{j} + 3\hat{k} \), then the position vector of the third vertex is

    (1) \( -2\hat{i} - \hat{j} + 9\hat{k} \)

    (2) \( -2\hat{i} - \hat{j} - 6\hat{k} \)

    (3) \( 2\hat{i} - \hat{j} + 6\hat{k} \)

    (4) \( -2\hat{i} + \hat{j} + 6\hat{k} \)

15. If \( |\vec{a} + \vec{b}| = 60, |\vec{a} - \vec{b}| = 40 \) and \( |\vec{b}| = 46 \), then \( |\vec{a}| \) is

    (1) 42

    (2) 12

    (3) 22

    (4) 32

16. If \( \vec{a} \) and \( \vec{b} \) having same magnitude and angle between them is \( 60^\circ \) and their scalar product is \( \frac{1}{2} \), then \( |\vec{a}| \) is

    (1) 2

    (2) 3

    (3) 7

    (4) 1

17. The value of \( \theta \in \left(0, \frac{\pi}{2}\right) \) for which the vectors \( \vec{a} = (\sin\theta)\hat{i} + (\cos\theta)\hat{j} \) and \( \vec{b} = \hat{i} - \sqrt{3}\hat{j} + 2\hat{k} \) are perpendicular, is equal to

    (1) \( \frac{\pi}{3} \)

    (2) \( \frac{\pi}{6} \)

    (3) \( \frac{\pi}{4} \)

    (4) \( \frac{\pi}{2} \)

18. If \( |\vec{a}| = 13, |\vec{b}| = 5 \) and \( \vec{a} \cdot \vec{b} = 60 \), then \( |\vec{a} \times \vec{b}| \) is

    (1) 15

    (2) 35

    (3) 45

    (4) 25

19. Vectors \( \vec{a} \) and \( \vec{b} \) are inclined at an angle \( \theta = 120^\circ \). If \( |\vec{a}| = 1, |\vec{b}| = 2 \), then \( [(\vec{a} + 3\vec{b}) \times (3\vec{a} - \vec{b})]^2 \) is equal to

    (1) 225

    (2) 275

    (3) 325

    (4) 300

20. If \( \vec{a} \) and \( \vec{b} \) are two vectors of magnitude 2 and inclined at an angle \( 60^\circ \), then the angle between \( \vec{a} \) and \( \vec{a} + \vec{b} \) is

    (1) \( 30^\circ \)

    (2) \( 60^\circ \)

    (3) \( 45^\circ \)

    (4) \( 90^\circ \)

21. If the projection of \( 5\hat{i} - \hat{j} - 3\hat{k} \) on the vector \( \hat{i} + 3\hat{j} + \lambda \hat{k} \) is same as the projection of \( \hat{i} + 3\hat{j} + \lambda \hat{k} \) on \( 5\hat{i} - \hat{j} - 3\hat{k} \), then \( \lambda \) is equal to

    (1) \( \pm 4 \)

    (2) \( \pm 3 \)

    (3) \( \pm 5 \)

    (4) \( \pm 1 \)

22. If \( (1, 2, 4) \) and \( (2, -3\lambda, -3) \) are the initial and terminal points of the vector \( \hat{i} + 5\hat{j} - 7\hat{k} \), then the value of \( \lambda \) is equal to

    (1) \( \frac{7}{3} \)

    (2) \( -\frac{7}{3} \)

    (3) \( -\frac{5}{3} \)

    (4) \( \frac{5}{3} \)

23. If the points whose position vectors \( 10\hat{i} + 3\hat{j} \), \( 12\hat{i} - 5\hat{j} \) and \( a\hat{i} + 11\hat{j} \) are collinear then \( a \) is equal to

    (1) 6

    (2) 3

    (3) 5

    (4) 8

24. If \( \vec{a} = \hat{i} + \hat{j} + \hat{k} \), \( \vec{b} = 2\hat{i} + x\hat{j} + \hat{k} \), \( \vec{c} = \hat{i} - \hat{j} + 4\hat{k} \) and \( \vec{a} \cdot (\vec{b} \times \vec{c}) = 70 \), then \( x \) is equal to

    (1) 5

    (2) 7

    (3) 26

    (4) 10

25. If \( \vec{a} = \hat{i} + 2\hat{j} + 2\hat{k}, |\vec{b}| = 5 \) and the angle between \( \vec{a} \) and \( \vec{b} \) is \( \frac{\pi}{6} \), then the area of the triangle formed by these two vectors as two sides, is

    (1) \( \frac{7}{4} \)

    (2) \( \frac{15}{4} \)

    (3) \( \frac{3}{4} \)

    (4) \( \frac{17}{4} \)

## SUMMARY

In this chapter we have acquired the knowledge of the following:

- A scalar is a quantity that is determined by its magnitude.
- A vector is a quantity that is determined by both its magnitude and its direction.
- If we have a liberty to choose the origins of the vector at any point then it is said to be a free vector, whereas if it is restricted to a certain specified point then the vector is said to be a localized vector.
- Two or more vectors are said to be coplanar if they lie on the same plane or parallel to the same plane.
- Two vectors are said to be equal if they have equal length and the same direction.
- A vector of magnitude 0 is called the zero vector. A vector of magnitude 1 is called a unit vector.
- Let \( \vec{a} \) be a vector and \( m \) be a scalar. Then the vector \( m\vec{a} \) is called the scalar multiple of a vector \( \vec{a} \) by the scalar \( m \).
- Two vectors \( \vec{a} \) and \( \vec{b} \) are said to be parallel if \( \vec{a} = \lambda \vec{b} \), where \( \lambda \) is a scalar.
- If \( \vec{a}, \vec{b} \) and \( \vec{c} \) are the sides of a triangle taken in order then \( \vec{a} + \vec{b} + \vec{c} = \vec{0} \).
- Vector addition is associative.
- For any vector \( \vec{a} \), \( \vec{a} + \vec{0} = \vec{0} + \vec{a} = \vec{a} \).
- For any vector \( \vec{a} \), \( \vec{a} + (-\vec{a}) = (-\vec{a}) + \vec{a} = \vec{0} \).
- Vector addition is commutative.
- "If two vectors are represented in magnitude and direction by the two sides of a triangle taken in the same order, then their sum is represented by the third side taken in the reverse order". This is known as the triangle law of addition.
- In a parallelogram \( OABC \), if \( \overline{OA} \) and \( \overline{OB} \) represents two adjacent sides, then the diagonal \( \overline{OC} \) represents their sum. This is parallelogram law of addition.
- If \( \alpha, \beta, \gamma \) are the direction angles then \( \cos\alpha, \cos\beta, \cos\gamma \) are the direction cosines.
- The direction ratios of the vector \( \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \) are \( x, y, z \).
- If \( \vec{a}, \vec{b} \) and \( \vec{c} \) are three non-coplanar vectors in the space, then any vector in the space can be written as \( l\vec{a} + m\vec{b} + n\vec{c} \) in a unique way.
- Let \( \vec{r} = x\hat{i} + y\hat{j} + z\hat{k} \) be the position vector of any point and let \( \alpha, \beta, \gamma \) be the direction angles of \( \vec{r} \). Then

  (i) the sum of the squares of the direction cosines of \( \vec{r} \) is 1.

  (ii) \( \sin^2\alpha + \sin^2\beta + \sin^2\gamma = 2 \).

  (iii) the direction cosines of \( \vec{r} \) are \( \frac{x}{\sqrt{x^2 + y^2 + z^2}}, \frac{y}{\sqrt{x^2 + y^2 + z^2}}, \frac{z}{\sqrt{x^2 + y^2 + z^2}} \).

  (iv) \( l, m, n \) are the direction cosines of a vector if and only if \( l^2 + m^2 + n^2 = 1 \).

  (v) any unit vector can be written as \( \cos\alpha \hat{i} + \cos\beta \hat{j} + \cos\gamma \hat{k} \).

- The scalar product of the vectors \( \vec{a} \) and \( \vec{b} \) is \( \vec{a} \cdot \vec{b} = |\vec{a}| |\vec{b}| \cos\theta \).

- Vector product of any two non-zero vectors \( \vec{a} \) and \( \vec{b} \) is written as \( \vec{a} \times \vec{b} \) and is defined as \( \vec{a} \times \vec{b} = |\vec{a}| |\vec{b}| \sin\theta \, \hat{n} \), where \( \theta \) is the angle between \( \vec{a} \) and \( \vec{b} \), \( 0 \leq \theta \leq \pi \). Here \( \vec{a}, \vec{b}, \hat{n} \) form a right handed system.
