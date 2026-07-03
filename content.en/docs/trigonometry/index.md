---
title: 'trigonometry'
weight: 3
summary: "This chapter introduces the fundamental concepts of trigonometry, including the measurement of angles in degrees and radians, and the definitions of trigonometric ratios such as sine, cosine, and tangent in the context of right-angled triangles and the unit circle. It covers essential identities like Pythagorean identities, sum and difference formulas, multiple and sub-multiple angle formulas, and transformations of sums into products and vice versa. The chapter also discusses the signs of trigonometric functions in different quadrants, general solutions of trigonometric equations, and applications of trigonometry in solving real-world problems involving heights and distances."
---

# Chapter 3: Trigonometry

## 3.1 Introduction

Trigonometry is primarily a branch of Mathematics that studies relationship involving sides and angles of triangles. The word trigonometry stems from the Greek word trigonon which means triangle and metron which means to measure. So, literally trigonometry is the study of measuring triangles. Greek mathematicians used trigonometric ratios to determine unknown distances. The Egyptians on the other hand used a primitive form of trigonometry for building Pyramids in second millinium BC(BCE). Aristarchus (310-250 BC(BCE)) used trigonometry to determine the distances of Moon and Sun.

Eratosthenes (276-195 BC(BCE)) was the first person to calculate the earth's circumference, which he did by applying a measuring system using stadia, a standard unit of measurement during that period. The general principles of Trigonometry were formulated by the Greek astronomer Hipparchus (190-120 BC(BCE)) and he is credited as the founder of trigonometry. His ideas were used by Ptolemy of Alexandria (AD 90-168) leading to the development of Ptolemy theory of Astronomy. The most significant development of Trigonometry in ancient times was in India. Indian Mathematician and Astronomer Aryabhata (AD(CE) 476-550) defined sine, cosine, inverse cosine, inverse sine and he gave mathematical results in the form of 108 verses which included a formula for the area of a triangle. Mathematicians Brahmagupta (598 AD(CE)), Bhaskara I (600 AD(CE)) and Bhaskara II (1114 AD(CE)) are other Ancient Indians who contributed significantly to develop Trigonometry. Trigonometry was developed as a separate branch of Mathematics through the works of Johann Bernoulli (1667-1748) and Leonhard Euler (1707-1783). Euler established the fundamental results connecting trigonometric functions and complex exponential. Joseph Fourier (1768-1830) made important contribution to the study of trigonometric series. His invention of Fourier series has a wide range of applications especially in vibration analysis, electrical engineering, acoustics, optics, signal processing, image processing and quantum mechanics. In modern times, trigonometric functions are developed as mathematical functions of angular magnitudes, through the medium of which many kinds of geometrical and algebraic investigations are carried out in every branch of Mathematics and applications. Our GPS system in cars and mobile phones is based on trigonometric calculations. Advanced medical scanning procedures such as CT and MRI, used in detecting tumors, involve sine and cosine functions.

## Learning Objectives

At the end of this chapter, students are expected to know:

- the limitations of right triangle trigonometric ratios as they involve acute angles.
- the necessity for the study of radian measure of an angle and its advantage over degree measure.
- how unit circle is used to define trigonometric functions of real numbers.
- various trigonometric identities, their relationships and applications.
- the principal solution and general solution of a trigonometric equation.
- how to solve trigonometric equations.
- law of sines, law of cosines in triangles and their applications in real life situations.
- how to solve an oblique triangle using law of sines and law of cosines.
- application of Heron's formula and how to compute area of a triangle without finding its altitude.
- the existence of inverse trigonometric functions and their domains and ranges.

Let us recall the basics of trigonometric ratios using acute angles and their properties, which were discussed in earlier classes.

## 3.2 A recall of basic results

In earlier classes, we have learnt trigonometric ratios using a right triangle and proved trigonometric identities for an acute angle. One wonders, how the distance between planets, heights of Mountains, distance between far off objects like Earth and Sun, heights of tall buildings, the speed of supersonic jets are measured or calculated. Interestingly, such distances or heights are calculated applying the trigonometric ratios which were derived for acute angles. Our aim is to develop trigonometric functions defined for any real number and use them in all branches of mathematics, in particular, in calculus. First, let us recall the definition of angle and degree measure of an angle.

### 3.2.1 Angles

The angle \( AOB \) is a measure formed by two rays \( OA \) and \( OB \) sharing the common point \( O \) as shown in the Figure 3.1. The common point \( O \) is called the vertex of the angle. If we rotate the ray \( OA \) about its vertex \( O \) and takes the position \( OB \), then \( OA \) and \( OB \) respectively are called the initial side and the terminal side of the angle produced. An anticlockwise rotation generates a positive angle (angle with positive sign), while a clockwise rotation generates a negative angle (angle with negative sign).

**Figure 3.1**

One full anticlockwise (or clockwise) rotation of \( OA \) back to itself is called one complete rotation or revolution.

### 3.2.2 Different Systems of measurement of angle

There are three different systems for measuring angles.

#### (i) Sexagesimal system

The Sexagesimal system is the most prevalent system of measurement where a right angle is divided into 90 equal parts called Degrees. Each degree is divided into 60 equal parts called Minutes, and each minute into 60 equal parts called Seconds.

The symbols \( 1^\circ \), \( 1' \) and \( 1'' \) are used to denote a degree, a minute and a second respectively.

#### (ii) Centesimal system

In the Centesimal system, the right angle is divided into 100 equal parts, called Grades; each grade is subdivided into 100 Minutes, and each minute is subdivided into 100 Seconds. The symbol \( 1^g \) is used to denote a grade.

#### (iii) Circular system

In the circular system, the radian measure of an angle is introduced using arc lengths in a circle of radius \( r \). Circular system is used in all branches of Mathematics and in other applications in Science. The symbol \( 1^c \) is used to denote 1 radian measure.

### 3.2.3 Degree Measure

The degree is a unit of measurement of angles and is represented by the symbol \( ^\circ \). In degrees, we split up one complete rotation into 360 equal parts and each part is one degree, denoted by \( 1^\circ \). Thus, \( 1^\circ \) is \( \frac{1}{360} \) of one complete rotation. To measure a fraction of an angle and also for accuracy of measurement of angles, minutes and seconds are introduced. One minute \( (1') \) corresponds to \( \frac{1}{60} \) of a degree and in turn a second \( (1'') \) corresponds to \( \frac{1}{60} \) of a minute (or) \( \frac{1}{3600} \) of a degree.

We shall classify a pair of angles in the following way for better understanding and usages.

(i) Two angles that have the exact same measure are called congruent angles.

(ii) Two angles that have their measures adding to \( 90^\circ \) are called complementary angles.

(iii) Two angles that have their measures adding to \( 180^\circ \) are called supplementary angles.

(iv) Two angles between \( 0^\circ \) and \( 360^\circ \) are conjugate if their sum equals \( 360^\circ \).

(i) The concept of degrees, minutes and seconds, is analogous to the system of time measurement where we think of a degree representing one hour.

(ii) Observe that
\[
59.0854^\circ = 59^\circ + 0.0854^\circ
\]
\[
0.0854^\circ = 0.0854^\circ \times \frac{60'}{1^\circ} = 5.124'
\]
\[
5.124' = 5' + 0.124'
\]
\[
0.124' = 0.124' \times \frac{60''}{1'} = 7.44''
\]
Thus, \( 59.0854^\circ = 59^\circ 5' 7.44'' \)

(iii) Also notice that \( 34^\circ 51' 35'' = 34.8597^\circ \) and \( 90^\circ - 36^\circ 18' 47'' = 53^\circ 41' 13'' \)

### 3.2.4 Angles in Standard Position

**Figure 3.2**

An angle is said to be in standard position if its vertex is at the origin and its initial side is along the positive x-axis. An angle is said to be in the first quadrant, if in the standard position, its terminal side falls in the first quadrant. Similarly, we can define for the other three quadrants. Angles in standard position having their terminal sides along the x-axis or y-axis are called quadrantal angles. Thus, \( 0^\circ \), \( 90^\circ \), \( 180^\circ \), \( 270^\circ \) and \( 360^\circ \) are quadrantal angles.

The degree measurement of a quadrantal angle is a multiple of \( 90^\circ \).

### 3.2.5 Coterminal angles

One complete rotation of a ray in the anticlockwise direction results in an angle measuring of \( 360^\circ \). By continuing the anticlockwise rotation, angles larger than \( 360^\circ \) can be produced. If we rotate in clockwise direction, negative angles are produced. Angles \( 57^\circ \), \( 417^\circ \) and \( -303^\circ \) have the same initial side and terminal side but with different amount of rotations, such angles are called coterminal angles. Thus, angles in standard position that have the same terminal sides are coterminal angles. Hence, if \( \alpha \) and \( \beta \) are coterminal angles, then \( \beta = \alpha + k(360^\circ) \) where \( k \) is an integer. The measurements of coterminal angles differ by an integral multiple of \( 360^\circ \).

For example, \( 417^\circ \) and \( -303^\circ \) are coterminal because \( 417^\circ - (-303^\circ) = 720^\circ = 2(360^\circ) \)

**Figure 3.3**

(i) Observe that \( 45^\circ \), \( -315^\circ \) and \( 405^\circ \) lie in the first quadrant.

(ii) The following pairs of angles are coterminal angles: \( (30^\circ, 390^\circ) \); \( (280^\circ, 1000^\circ) \) and \( (-85^\circ, 275^\circ) \)

### 3.2.6 Basic Trigonometric ratios using a right triangle

We know that six ratios can be formed using the three lengths \( a, b, c \) of sides of a right triangle \( ABC \). Interestingly, these ratios lead to the definitions of six basic trigonometric functions.

First, let us recall the trigonometric ratios which are defined with reference to a right triangle.

\[
\sin \theta = \frac{\text{opposite side}}{\text{hypotenuse}}; \quad \cos \theta = \frac{\text{adjacent side}}{\text{hypotenuse}}
\]

**Figure 3.4**

With the help of \( \sin \theta \) and \( \cos \theta \) the remaining trigonometric ratios \( \tan \theta \), \( \cot \theta \), \( \csc \theta \) and \( \sec \theta \) are determined by using the relations

\[
\tan \theta = \frac{\sin \theta}{\cos \theta}, \quad \csc \theta = \frac{1}{\sin \theta}, \quad \sec \theta = \frac{1}{\cos \theta}, \quad \cot \theta = \frac{\cos \theta}{\sin \theta}.
\]

### 3.2.7 Exact values of trigonometric functions of widely used angles

Let us list out the values of trigonometric functions at known angles.

| \( \theta \) | \( 0^\circ \) | \( 30^\circ \) | \( 45^\circ \) | \( 60^\circ \) | \( 90^\circ \) |
|-------------|--------------|--------------|--------------|--------------|--------------|
| \( \sin \theta \) | \( 0 \) | \( \frac{1}{2} \) | \( \frac{1}{\sqrt{2}} \) | \( \frac{\sqrt{3}}{2} \) | \( 1 \) |
| \( \cos \theta \) | \( 1 \) | \( \frac{\sqrt{3}}{2} \) | \( \frac{1}{\sqrt{2}} \) | \( \frac{1}{2} \) | \( 0 \) |
| \( \tan \theta \) | \( 0 \) | \( \frac{1}{\sqrt{3}} \) | \( 1 \) | \( \sqrt{3} \) | undefined |

(i) The values given above are all exact.

(ii) We observe that \( \sin 30^\circ \) and \( \cos 60^\circ \) are equal. Also \( \sin 60^\circ \) and \( \cos 30^\circ \) are equal.

### 3.2.8 Basic Trigonometric Identities

A trigonometric identity represents a relationship that is always true for all admissible values in the domain. For example \( \sec \theta = \frac{1}{\cos \theta} \) is true for all admissible values of \( \theta \). Hence, this is an identity. However, \( \sin \theta = \frac{1}{2} \) is not an identity, since the relation fails when \( \theta = 60^\circ \). Identities enable us to simplify complicated expressions. They are the basic tools of trigonometry which are being used in solving trigonometric equations. The most important part of working with identities, is to manipulate them with the help of a variety of techniques from algebra.

Let us recall the fundamental identities (Pythagorean identities) of trigonometry, namely,

\[
\cos^2 \theta + \sin^2 \theta = 1
\]
\[
\sec^2 \theta - \tan^2 \theta = 1
\]
\[
\csc^2 \theta - \cot^2 \theta = 1
\]

(i) \( \sin^2 \theta \) is the commonly used notation for \( (\sin \theta)^2 \), likewise for other trigonometric ratios.

(ii) \( \sec^2 \theta - \tan^2 \theta = 1 \) is meaningless when \( \theta = 90^\circ \). But still it is an identity and true for all values of \( \theta \) for which \( \sec \theta \) and \( \tan \theta \) are defined. Thus, an identity is an equation that is true for all values of its domain values.

(iii) When we write \( \frac{\sin \theta}{1 + \cos \theta} \), we understand that the expression is valid for all values of \( \theta \) for which \( 1 + \cos \theta \neq 0 \).

### Example 3.1

Prove that \( \frac{\tan \theta + \sec \theta - 1}{\tan \theta - \sec \theta + 1} = \frac{1 + \sin \theta}{\cos \theta} \).

**Solution:**

\[
\frac{\tan \theta + \sec \theta - 1}{\tan \theta - \sec \theta + 1} = \frac{\tan \theta + \sec \theta - (\sec^2 \theta - \tan^2 \theta)}{\tan \theta - \sec \theta + 1}
\]
\[
= \frac{(\tan \theta + \sec \theta)[1 - (\sec \theta - \tan \theta)]}{\tan \theta - \sec \theta + 1}
\]
\[
= \tan \theta + \sec \theta = \frac{1 + \sin \theta}{\cos \theta}.
\]

### Example 3.2

Prove that \( (\csc A - \sin A)(1 + \tan A + \cot A) = \tan A \sec A - \cot A \csc A \).

**Solution:**

\[
\text{L.H.S.} = \left( \frac{1}{\sin A} - \sin A \right) \left[ 1 + \frac{\sin A}{\cos A} + \frac{\cos A}{\sin A} \right]
\]
\[
= \frac{\sin^3 A - \cos^3 A}{\sin^2 A \cos^2 A}
\]
\[
\text{R.H.S.} = \frac{\sin A}{\cos^2 A} - \frac{\cos A}{\sin^2 A} = \frac{\sin^3 A - \cos^3 A}{\sin^2 A \cos^2 A}
\]

From (i) and (ii), we get the required result.

## Exercise 3.1

1. Identify the quadrant in which an angle of each given measure lies
   (i) \( 25^\circ \) (ii) \( 825^\circ \) (iii) \( -55^\circ \) (iv) \( 328^\circ \) (v) \( -230^\circ \)

2. For each given angle, find a coterminal angle with measure of \( \theta \) such that \( 0^\circ \leq \theta < 360^\circ \)
   (i) \( 395^\circ \) (ii) \( 525^\circ \) (iii) \( 1150^\circ \) (iv) \( -270^\circ \) (v) \( -450^\circ \)

3. If \( a \cos \theta - b \sin \theta = c \), show that \( a \sin \theta + b \cos \theta = \pm \sqrt{a^2 + b^2 - c^2} \).

4. If \( \sin \theta + \cos \theta = m \), show that \( \cos^6 \theta + \sin^6 \theta = \frac{4 - 3(m^2 - 1)^2}{4} \), where \( m^2 \leq 2 \).

5. If \( \frac{\cos^4 \alpha}{\cos^2 \beta} + \frac{\sin^4 \alpha}{\sin^2 \beta} = 1 \), prove that
   (i) \( \sin^4 \alpha + \sin^4 \beta = 2 \sin^2 \alpha \sin^2 \beta \)
   (ii) \( \frac{\cos^4 \beta}{\cos^2 \alpha} + \frac{\sin^4 \beta}{\sin^2 \alpha} = 1 \).

6. If \( y = \frac{2 \sin \alpha}{1 + \cos \alpha + \sin \alpha} \), then prove that \( \frac{1 - \cos \alpha + \sin \alpha}{1 + \sin \alpha} = y \).

7. If \( x = \sum_{n=0}^{\infty} \cos^{2n} \theta \), \( y = \sum_{n=0}^{\infty} \sin^{2n} \theta \) and \( z = \sum_{n=0}^{\infty} \cos^{2n} \theta \sin^{2n} \theta \), \( 0 < \theta < \frac{\pi}{2} \), then show that \( xyz = x + y + z \).

   [Hint: Use the formula \( 1 + x + x^2 + x^3 + \ldots = \frac{1}{1 - x} \), where \( |x| < 1 \).]

8. If \( \tan^2 \theta = 1 - k^2 \), show that \( \sec \theta + \tan^3 \theta \sec \theta = (2 - k^2)^{3/2} \). Also, find the values of \( k \) for which this result holds.

9. If \( \sec \theta + \tan \theta = p \), obtain the values of \( \sec \theta \), \( \tan \theta \) and \( \sin \theta \) in terms of \( p \).

10. If \( \cot \theta (1 + \sin \theta) = 4m \) and \( \cot \theta (1 - \sin \theta) = 4n \), then prove that \( (m^2 - n^2)^2 = mn \).

11. If \( \cos \theta - \sin \theta = a^3 \) and \( \sec \theta - \cos \theta = b^3 \), then prove that \( a^2 b^2 (a^2 + b^2) = 1 \).

12. Eliminate \( \theta \) from the equations \( a \sec \theta - c \tan \theta = b \) and \( b \sec \theta + d \tan \theta = c \).

## 3.3 Radian Measure

Initially right triangles were used to define trigonometric ratios and angles were measured in degrees. But right triangles have limitations as they involve only acute angles. In degrees a full rotation corresponds to \( 360^\circ \) where the choice of 360 was made thousands of years prior to the Babylonians. They might have chosen 360 based on the number of days in a year. But it does have the nice property of breaking into smaller angles like \( 30^\circ \), \( 45^\circ \), \( 60^\circ \), \( 90^\circ \) and \( 180^\circ \). In 17th century, trigonometry was extended to Physics and Chemistry where it required trigonometric functions whose domains were sets of real numbers rather than angles. This was accomplished by using correspondence between an angle and length of the arc on a unit circle. Such a measure of angle is termed as radian measure. For theoretical applications, the radian is the most common system of angle measurement. Radians are common unit of measurement in many technical fields, including calculus. The most important irrational number \( \pi \) plays a vital role in radian measures of angles. Let us introduce the radian measure of an angle.

The radian measure of an angle is the ratio of the arc length it subtends, to the radius of the circle in which it is the central angle.

Consider a circle of radius \( r \). Let \( s \) be the arc length subtending an angle \( \theta \) at the centre.

Then, \( \theta = \frac{\text{arc length}}{\text{radius}} = \frac{s}{r} \) radians. Hence, \( s = r\theta \).

**Figure 3.5**

(i) All circles are similar. Thus, for a given central angle in any circle, the ratio of the intercepted arc length to the radius is always constant.

(ii) When \( s = r \), we have an angle of 1 radian. Thus, one radian is the angle made at the centre of a circle by an arc with length equal to the radius of the circle.

(iii) Since the lengths \( s \) and \( r \) have same unit, \( \theta \) is unitless and thus, we do not use any notation to denote radians.

(iv) \( \theta = 1 \) radian measure, if \( s = r \); \( \theta = 2 \) radian measure, if \( s = 2r \). Thus, in general \( \theta = k \) radian measure, if \( s = kr \). Hence, radian measure of an angle tells us how many radius lengths, we need to sweep out along the circle to subtend the angle \( \theta \).

(v) Radian angle measurement can be related to the edge of the unit circle. In radian system, we measure an angle by measuring the distance travelled along the edge of the unit circle to where the terminal side of the angle intersect the unit circle.

### 3.3.1 Relationship between Degree and Radian Measures

We have degree and radian units to measure angles. One measuring unit is better than another if it can be defined in a simpler and more intuitive way. For example, in measuring temperature, Celsius unit is better than Fahrenheit as Celsius was defined using \( 0^\circ \) and \( 100^\circ \) for freezing and boiling points of water. Radian measure is better for conversion and calculations. Radian measure is more convenient for analysis whereas degree measure of an angle is more convenient to communicate the concept between people. Greek Mathematicians observed the relation of \( \pi \) which arises from circumference of a circle and thus, \( \pi \) plays a crucial role in radian measure.

In unit circle, a full rotation corresponds to \( 360^\circ \) whereas, a full rotation is related to \( 2\pi \) radians, the circumference of the unit circle. Thus, we have the following relations:

\[
2\pi \text{ radians} = 360^\circ, \text{ which reduces to } \pi \text{ radians} = 180^\circ.
\]
\[
\text{Thus, } 1 \text{ radian} = \left( \frac{180}{\pi} \right)^\circ \text{ or } 1^\circ = \frac{\pi}{180} \text{ radians}.
\]
\[
x \text{ radian} = \left( \frac{180x}{\pi} \right)^\circ \text{ or } x^\circ = \frac{\pi x}{180} \text{ radians}.
\]

Observe that the scale used in radians is much smaller than the scale in degrees. The smaller scale makes the graphs of trigonometric functions more visible and usable. The above relation gives a way to convert radians into degrees or degrees into radians.

(i) The ratio of the circumference of any circle to its diameter is always a constant. This constant is denoted by the irrational number \( \pi \).

(ii) Mark a point \( P \) on a unit circle and put the unit circle on the number line so that \( P \) touches the number 0. Allow the circle to roll along the number line. The point \( P \) will touch the number \( 2\pi \) on the number line when the circle rolls to one complete revolution to the right.

(iii) If the unit of angle measure is not specified, then the angle is understood to be in radians.

(iv) Consider a sector of a circle with radius \( r \). If \( \theta \) is the central angle of the sector, then
\[
\text{Area of the sector} = \frac{1}{2} r^2 \theta
\]
Clearly, the calculation in radian measure is much easier to work with.

(v) The values of \( \pi \) and \( \frac{22}{7} \) correct to four decimal places are 3.1416 and 3.1429 respectively. Thus, \( \pi \) and \( \frac{22}{7} \) are approximately equal correct upto two decimal places. Hence, \( \pi \approx \frac{22}{7} \).

(vi)
\[
1 \text{ radian} \approx 57^\circ 17' 45'' \text{ and } 1^\circ \approx 0.017453 \text{ radian}
\]
\[
1' = \left( \frac{\pi}{180 \times 60} \right) \text{ radian} \approx 0.000291 \text{ radian}
\]
\[
1'' = \left( \frac{\pi}{180 \times 60 \times 60} \right) \text{ radian} \approx 0.000005 \text{ radian}
\]

(vii) The radian measures and the corresponding degree measures for some known angles are given in the following table

| Radians | 0 | 0.017453 | \( \pi/6 \) | \( \pi/4 \) | \( \pi/3 \) | \( \pi/2 \) | \( \pi \) | \( 3\pi/2 \) | \( 2\pi \) |
|---------|---|----------|-----------|-----------|-----------|-----------|---------|------------|-----------|
| Degrees | 0° | 57°17′45″ | 30° | 45° | 60° | 90° | 180° | 270° | 360° |

(viii) \( \sin 90^\circ = 1 \) but \( \sin 90 \neq 1 \) (in radian measure).

### Example 3.4

Convert (i) \( 18^\circ \) to radians (ii) \( -108^\circ \) to radians.

**Solution:**

Now, \( 180^\circ = \pi \) radians gives \( 1^\circ = \frac{\pi}{180} \) radians

(i) \( 18^\circ = \frac{\pi}{180} \times 18 \) radians \( = \frac{\pi}{10} \) radians

(ii) \( -108^\circ = \frac{\pi}{180} \times (-108) \) radians \( = -\frac{3\pi}{5} \) radians.

### Example 3.5

Convert (i) \( \frac{\pi}{5} \) radians to degrees (ii) 6 radians to degrees.

**Solution:**

We know that \( \pi \) radians \( = 180^\circ \) and thus,

(i) \( \frac{\pi}{5} \) radians \( = \frac{180^\circ}{5} = 36^\circ \)

(ii) \( 6 \) radians \( = \left( \frac{180}{\pi} \times 6 \right)^\circ \approx \left( \frac{7 \times 180}{22} \times 6 \right)^\circ = \left( 343\frac{7}{11} \right)^\circ \).

### Example 3.6

Find the length of an arc of a circle of radius \( 5 \) cm subtending a central angle measuring \( 15^\circ \).

**Solution:**

Let \( s \) be the length of the arc of a circle of radius \( r \) subtending a central angle \( \theta \). Then \( s = r\theta \).

We have, \( \theta = 15^\circ = 15 \times \frac{\pi}{180} = \frac{\pi}{12} \) radians

So that, \( s = r\theta \) gives \( s = 5 \times \frac{\pi}{12} = \frac{5\pi}{12} \) cm

In the product \( r\theta \), \( \theta \) must always be in radians.

### Example 3.7

If the arcs of same lengths in two circles subtend central angles \( 30^\circ \) and \( 80^\circ \), find the ratio of their radii.

**Solution:**

Let \( r_1 \) and \( r_2 \) be the radii of the two given circles and \( l \) be the length of the arc.

\[
\theta_1 = 30^\circ = \frac{\pi}{6} \text{ radians}, \quad \theta_2 = 80^\circ = \frac{4\pi}{9} \text{ radians}
\]

Given that \( l = r_1 \theta_1 = r_2 \theta_2 \)

Thus, \( \frac{\pi}{6} r_1 = \frac{4\pi}{9} r_2 \)

\[
\frac{r_1}{r_2} = \frac{8}{3} \text{ which implies } r_1 : r_2 = 8 : 3.
\]

## Exercise 3.2

1. Express each of the following angles in radian measure:
   (i) \( 135^\circ \) (ii) \( -205^\circ \) (iii) \( 150^\circ \) (iv) \( 330^\circ \).

2. Find the degree measure corresponding to the following radian measures
   (i) \( \frac{\pi}{3} \) (ii) \( \frac{\pi}{9} \) (iii) \( \frac{2\pi}{5} \) (iv) \( \frac{7\pi}{3} \) (v) \( \frac{10\pi}{9} \).

3. What must be the radius of a circular running path, around which an athlete must run 5 times in order to describe \( 1 \) km?

4. In a circle of diameter \( 40 \) cm, a chord is of length \( 20 \) cm. Find the length of the minor arc of the chord.

5. Find the degree measure of the angle subtended at the centre of circle of radius \( 100 \) cm by an arc of length \( 22 \) cm.

6. What is the length of the arc intercepted by a central angle of measure \( 41^\circ \) in a circle of radius \( 10 \) ft?

7. If in two circles, arcs of the same length subtend angles \( 60^\circ \) and \( 75^\circ \) at the centre, find the ratio of their radii.

8. The perimeter of a certain sector of a circle is equal to the length of the arc of a semi-circle having the same radius. Express the angle of the sector in degrees, minutes and seconds.

9. An airplane propeller rotates 1000 times per minute. Find the number of degrees that a point on the edge of the propeller will rotate in 1 second.

10. A train is moving on a circular track of 1500 m radius at the rate of 66 km/hr. What angle will it turn in 20 seconds?

11. A circular metallic plate of radius 8 cm and thickness 6 mm is melted and molded into a pie (a sector of the circle with thickness) of radius 16 cm and thickness 4 mm. Find the angle of the sector.

## 3.4 Trigonometric functions and their properties

### 3.4.1 Trigonometric Functions of any angle in terms of Cartesian coordinates

We have studied the principles of trigonometric ratios in the lower classes using acute angles. But we come across many angles which are not acute. We shall extend the acute angle idea and define trigonometric functions for any angle. The trigonometric ratios to any angle in terms of radian measure are called trigonometric functions.

Let \( P(x, y) \) be a point other than the origin on the terminal side of an angle \( \theta \) in standard position. Let \( OP = r \). Thus, \( r = \sqrt{x^2 + y^2} \)

The six trigonometric functions of \( \theta \) are defined as follows:

\[
\sin \theta = \frac{y}{r} \text{ and } \cos \theta = \frac{x}{r}.
\]

**Figure 3.6**

Using this, we have
\[
\tan \theta = \frac{y}{x}, \, x \neq 0; \quad \cot \theta = \frac{x}{y}, \, y \neq 0; \quad \csc \theta = \frac{r}{y}, \, y \neq 0; \quad \sec \theta = \frac{r}{x}, \, x \neq 0.
\]

(i) Since \( |x| \leq r, |y| \leq r \), we have \( |\sin \theta| \leq 1 \) and \( |\cos \theta| \leq 1 \)

(ii) In the case of acute angle, the above definitions are equivalent to our earlier definitions using right triangle.

(iii) The trigonometric functions have positive or negative values depending on the quadrant in which the point \( P(x, y) \) on the terminal side of \( \theta \) lies.

(iv) The above definitions of trigonometric functions is independent of the points on the terminal side of the angle. (verify!)

### Trigonometric ratios of Quadrantal angles

Let us recall that, an angle in its standard position for which the terminal side coincides with one of the axes, is a Quadrantal angle. We shall find the trigonometric ratios for the quadrantal angles.

Consider the unit circle \( x^2 + y^2 = 1 \). Let \( P(x, y) \) be a point on the unit circle where the terminal side of the angle \( \theta \) intersects the unit circle.

Then \( \cos \theta = \frac{x}{1} = x \) (x-coordinate of \( P \)) and
\[
\sin \theta = \frac{y}{1} = y \text{ (y-coordinate of } P)
\]

**Figure 3.7**

Thus, the coordinates of any point \( P(x, y) \) on the unit circle is \( P(\cos \theta, \sin \theta) \). In this way, the angle measure \( \theta \) is associated with a point on the unit circle.

The following table illustrates how trigonometric function values are determined for Quadrantal angles using the above explanation.

| Quadrantal angle | Corresponding point on the Unit circle \( P(x, y) = P(\cos \theta, \sin \theta) \) | \( \cos \theta \) | \( \sin \theta \) |
|-----------------|------------------------------------------------------------------------------------|-----------------|-----------------|
| \( \theta = 0^\circ \) | \( (1, 0) = (\cos 0^\circ, \sin 0^\circ) \) | \( \cos 0^\circ = 1 \) | \( \sin 0^\circ = 0 \) |
| \( \theta = 90^\circ \) | \( (0, 1) = (\cos 90^\circ, \sin 90^\circ) \) | \( \cos 90^\circ = 0 \) | \( \sin 90^\circ = 1 \) |
| \( \theta = 180^\circ \) | \( (-1, 0) = (\cos 180^\circ, \sin 180^\circ) \) | \( \cos 180^\circ = -1 \) | \( \sin 180^\circ = 0 \) |
| \( \theta = 270^\circ \) | \( (0, -1) = (\cos 270^\circ, \sin 270^\circ) \) | \( \cos 270^\circ = 0 \) | \( \sin 270^\circ = -1 \) |
| \( \theta = 360^\circ \) | \( (1, 0) = (\cos 360^\circ, \sin 360^\circ) \) | \( \cos 360^\circ = 1 \) | \( \sin 360^\circ = 0 \) |

(i) Observe that \( x \) and \( y \) coordinates of all points on the unit circle lie between \( -1 \) and 1. Hence, \( -1 \leq \cos \theta \leq 1, -1 \leq \sin \theta \leq 1 \), no matter whatever be the value of \( \theta \).

(ii) When \( \theta = 360^\circ \), we have completed one full rotation. Thus, the terminal side coincides with positive x-axis. Hence, sine has equal values at \( 0^\circ \) and at \( 360^\circ \). Cosine and other trigonometric functions also follow it.

(iii) If two angles differ by an integral multiple of \( 360^\circ \) or \( 2\pi \), then each trigonometric function will have equal values at both angles.

(iv) Using the values of sine and cosine at quadrantal angles, we have the following generalization geometrically.

| At Quadrantal angle | Justification | Generalization |
|---------------------|---------------|----------------|
| \( \sin 0 = 0 \) | | \( \sin (0 + 2n\pi) = 0; n \in \mathbb{Z} \) |
| | | \( \sin \theta = 0 \Rightarrow \theta = n\pi; n \in \mathbb{Z} \) |
| \( \sin \pi = 0 \) | | \( \sin (\pi + 2n\pi) = 0; n \in \mathbb{Z} \) |
| \( \cos \pi/2 = 0 \) | | \( \cos (\pi/2 + 2n\pi) = 0; n \in \mathbb{Z} \) |
| | | \( \cos \theta = 0 \Rightarrow \theta = (2n + 1)\pi/2; n \in \mathbb{Z} \) |
| \( \cos 3\pi/2 = 0 \) | | \( \cos (3\pi/2 + 2n\pi) = 0; n \in \mathbb{Z} \) |
| \( \tan 0 = 0 \) | | \( \tan (0 + 2n\pi) = 0; n \in \mathbb{Z} \) |
| | | \( \tan \theta = 0 \Rightarrow \theta = n\pi; n \in \mathbb{Z} \) |
| \( \tan \pi = 0 \) | | \( \tan (\pi + 2n\pi) = 0; n \in \mathbb{Z} \) |

(v) \( \tan \theta \) is not defined when \( \cos \theta = 0 \) and so, \( \tan \theta \) is not defined when \( \theta = (2n + 1)\frac{\pi}{2} \), \( n \in \mathbb{Z} \).

### 3.4.2 Trigonometric Functions of real numbers

**Figure 3.8**

For applications of trigonometry to the problems in higher mathematics including calculus and to problems in physics and chemistry, scientists required trigonometric functions of real numbers. This was skillfully done by exhibiting a correspondence between an angle and an arc length denoting a real number on a unit circle.

Consider a unit circle with the centre at the origin. Let the angle zero (in radian measure) be associated with the point \( A(1, 0) \) on the unit circle. Draw a tangent to the unit circle at the point \( A(1, 0) \). Let \( t \) be a real number such that \( t \) is y-coordinate of a point on the tangent line.

For each real number \( t \), identify a point \( B(x, y) \) on the unit circle such that the arc length \( AB \) is equal to \( t \). If \( t \) is positive, choose the point \( B(x, y) \) in the anticlockwise direction, otherwise choose it in the clockwise direction. Let \( \theta \) be the angle subtended by the arc \( AB \) at the centre. In this way, we have a function \( w(t) \) associating a real number \( t \) to a point on the unit circle. Such a function is called a wrapping function. Then \( s = r\theta \) gives arc length \( t = \theta \).

Now, define \( \sin t = \sin \theta \) and \( \cos t = \cos \theta \).

Clearly, \( \sin t = \sin \theta = y \) and \( \cos t = \cos \theta = x \).

Using \( \sin t \) and \( \cos t \), other trigonometric functions can be defined as functions of real numbers.

(i) \( B(x, y) = B(\cos t, \sin t) \) is a point on the unit circle.

Thus, \( -1 \leq \cos t \leq 1 \) and \( -1 \leq \sin t \leq 1 \) for any real number \( t \).

(ii) Wrapping function \( w(t) \) is analogous to wrapping a line around a circle.

(iii) The value of a trigonometric function of a real number \( t \) is its value at the angle \( t \) radians.

(iv) Trigonometric functions of real numbers are used to model phenomena like waves, oscillations, that occur in regular intervals.

### Example 3.8

The terminal side of an angle \( \theta \) in standard position passes through the point \( (3, -4) \). Find the six trigonometric function values at an angle \( \theta \).

**Solution:**

Let \( B(x, y) = B(3, -4) \), \( OA \) be the initial side and \( OB \) be the terminal side of the angle \( \theta \) in the standard position.

Then \( \angle AOB \) is the angle \( \theta \) and \( \theta \) lies in the IV quadrant. Also,
\[
OB = r, \quad r = \sqrt{x^2 + y^2} = \sqrt{3^2 + (-4)^2} = 5
\]
\[
x = 3, y = -4 \text{ and } r = 5, \text{ we have}
\]
\[
\sin \theta = \frac{y}{r} = -\frac{4}{5}; \quad \cos \theta = \frac{x}{r} = \frac{3}{5}; \quad \tan \theta = \frac{y}{x} = -\frac{4}{3};
\]
\[
\csc \theta = \frac{r}{y} = -\frac{5}{4}; \quad \sec \theta = \frac{r}{x} = \frac{5}{3}; \quad \cot \theta = \frac{x}{y} = -\frac{3}{4}.
\]

**Figure 3.9**

### Signs of Trigonometric functions

Consider a unit circle with centre at the origin. Let \( \theta \) be in standard position. Let \( P(x, y) \) be the point on the unit circle corresponding to the angle \( \theta \). Then, \( \cos \theta = x \), \( \sin \theta = y \) and \( \tan \theta = \frac{y}{x} \). The values of \( x \) and \( y \) are positive or negative depending on the quadrant in which \( P \) lies.

**Figure 3.10**

#### In the first quadrant:
\( \cos \theta = x > 0 \) (positive); \( \sin \theta = y > 0 \) (positive)

Thus, \( \cos \theta \) and \( \sin \theta \) and hence all trigonometric functions are positive in the first quadrant.

#### In the second quadrant:
\( \cos \theta = x < 0 \) (negative); \( \sin \theta = y > 0 \) (positive)

Thus, \( \sin \theta \) and \( \csc \theta \) are positive and others are negative. Similarly, we can find the sign of trigonometric functions in other two quadrants. Let us illustrate the above discussions in Figure 3.10.

Signs of trigonometric functions in various quadrants can be remembered with the slogan

"All Students Take Chocolate" (ASTC rule)

### Example 3.9

If \( \sin \theta = \frac{3}{5} \) and the angle \( \theta \) is in the second quadrant, then find the values of other five trigonometric functions.

**Solution:**

We know that \( \sin^2 \theta + \cos^2 \theta = 1 \Rightarrow \cos \theta = \pm \sqrt{1 - \sin^2 \theta} = \pm \sqrt{1 - \frac{9}{25}} = \pm \frac{4}{5} \)

Thus, \( \cos \theta = -\frac{4}{5} \) as \( \cos \theta \) is negative in the second quadrant.

\[
\sin \theta = \frac{3}{5} \Rightarrow \csc \theta = \frac{5}{3}; \quad \cos \theta = -\frac{4}{5} \Rightarrow \sec \theta = -\frac{5}{4}
\]
\[
\tan \theta = \frac{\sin \theta}{\cos \theta} = -\frac{3}{4}; \quad \cot \theta = -\frac{4}{3}
\]

If \( \sin \theta \) and \( \cos \theta \) are known, then the reciprocal identities and quotient identities can be used to find the other four trigonometric values. The Pythagorean identities can be used to find trigonometric values when one trigonometric value and the quadrant are known.

### 3.4.3 Allied Angles

Two angles are said to be allied if their sum or difference is a multiple of \( \frac{\pi}{2} \) radians.

Thus, any two angles of \( \theta \) such as, \( \pm \theta, \frac{\pi}{2} \pm \theta, \pi \pm \theta, \frac{3\pi}{2} \pm \theta, \dots \) are all allied angles.

Now we shall find the trigonometric ratios involving allied angles \( \theta \) and \( -\theta \).

#### Trigonometric ratios of \( -\theta \) in terms of \( \theta \)

**Figure 3.11**

Let \( \angle AOL = \theta \) and \( \angle AOM = -\theta \). Let \( P(a, b) \) be a point on \( OL \). Choose a point \( P' \) on \( OM \) such that \( OP = OP' \).

Draw \( PN \) perpendicular to \( OA \) intersecting \( OM \) at \( P' \). Since \( \angle AOP = \angle AOP' \) and \( \angle PON = \angle P'ON \), \( \triangle PON \) and \( \triangle P'ON \) are congruent.

Thus, \( PN = P'N \) and hence the point \( P' \) is given by \( P'(a, -b) \)

Now, by the definition of trigonometric functions

\[
\sin \theta = \frac{b}{OP}, \quad \cos \theta = \frac{a}{OP}, \quad \tan \theta = \frac{b}{a}
\]
\[
\sin(-\theta) = \frac{-b}{OP'} = \frac{-b}{OP} = -\sin \theta
\]
\[
\cos(-\theta) = \frac{a}{OP'} = \frac{a}{OP} = \cos \theta
\]

Then, it is easy to get

\[
\tan(-\theta) = -\tan \theta, \quad \csc(-\theta) = -\csc \theta, \quad \sec(-\theta) = \sec \theta, \quad \cot(-\theta) = -\cot \theta.
\]

(i) \( \sin(-\theta) = -\sin \theta \), and \( \cos(-\theta) = \cos \theta \). These facts follow from the symmetry of the unit circle about the x-axis. The angle \( -\theta \) is the same as angle \( \theta \) except it is on the other side of the x-axis. Flipping a point \( (x, y) \) to the other side of the x-axis makes the point into \( (x, -y) \), so the y-coordinate is negated and hence the sine is negated, but the x-coordinate remains the same and therefore the cosine is unchanged.

(ii) The negative-angle identities can be used to determine if a trigonometric function is an odd function or an even function.

### Example 3.10

Find the values of (i) \( \sin(-45^\circ) \) (ii) \( \cos(-45^\circ) \) (iii) \( \cot(-45^\circ) \)

**Solution:**

(i) \( \sin(-45^\circ) = -\sin(45^\circ) = -\frac{1}{\sqrt{2}} \).

(ii) \( \cos(-45^\circ) = \frac{1}{\sqrt{2}} \) and (iii) \( \cot(-45^\circ) = -1 \)

We have already learnt the trigonometric ratios of the angle \( (90^\circ - \theta) \), \( \left(0 < \theta < \frac{\pi}{2}\right) \) in the lower class. Let us recall the trigonometric ratios of angle \( (90^\circ - \theta) \):

\[
\sin(90^\circ - \theta) = \cos \theta, \quad \cos(90^\circ - \theta) = \sin \theta, \quad \tan(90^\circ - \theta) = \cot \theta
\]
\[
\csc(90^\circ - \theta) = \sec \theta, \quad \sec(90^\circ - \theta) = \csc \theta, \quad \cot(90^\circ - \theta) = \tan \theta.
\]

Now, we will establish the corresponding trigonometric ratios for an angle of the form \( (90^\circ + \theta) \).

#### Trigonometric ratios of an angle of the form \( (90^\circ + \theta) \), \( 0 < \theta < \frac{\pi}{2} \) in terms of \( \theta \).

**Figure 3.12**

Let \( \angle AOL = \theta \) and \( \angle AOR = (90^\circ + \theta) \). Let \( P(a, b) \) be a point on \( OL \) and choose a point \( P' \) on \( OR \) such that \( OP = OP' \).

Draw perpendiculars \( PM \) and \( P'N \) from \( P \) and \( P' \) on \( Ox \) and \( Ox' \) respectively.

Now, \( \angle AOP' = 90^\circ + \theta \).

Clearly, \( \triangle OPM \) and \( \triangle P'ON \) are congruent.

\[
ON = MP \text{ and } NP' = OM
\]

Hence, the coordinates of \( P \) and \( P' \) are \( P(a, b) \) and \( P'(-b, a) \), respectively. Now

\[
\sin(90^\circ + \theta) = \frac{y\text{-coordinate of } P'}{OP'} = \frac{a}{OP} = \cos \theta,
\]
\[
\cos(90^\circ + \theta) = \frac{x\text{-coordinate of } P'}{OP'} = \frac{-b}{OP} = -\sin \theta,
\]

Thus, \( \tan(90^\circ + \theta) = -\cot \theta \), \( \csc(90^\circ + \theta) = \sec \theta \), \( \sec(90^\circ + \theta) = -\csc \theta \), \( \cot(90^\circ + \theta) = -\tan \theta \).

The trigonometric function of other allied angles \( \pi \pm \theta \), \( \frac{3\pi}{2} \pm \theta \), \( 2\pi \pm \theta \) can be obtained in a similar way.

The above results can be summarized in the following table: \( \left(\text{Here } 0 < \theta < \frac{\pi}{2}\right) \)

| Function | \(-\theta\) | \(\frac{\pi}{2} - \theta\) | \(\frac{\pi}{2} + \theta\) | \(\pi - \theta\) | \(\pi + \theta\) | \(\frac{3\pi}{2} - \theta\) | \(\frac{3\pi}{2} + \theta\) | \(2\pi - \theta\) | \(2\pi + \theta\) |
|----------|-----------|-------------------------|-------------------------|----------------|-----------------|---------------------------|---------------------------|------------------|-------------------|
| sine | \(-\sin \theta\) | \(\cos \theta\) | \(\cos \theta\) | \(\sin \theta\) | \(-\sin \theta\) | \(-\cos \theta\) | \(-\cos \theta\) | \(-\sin \theta\) | \(\sin \theta\) |
| cosine | \(\cos \theta\) | \(\sin \theta\) | \(-\sin \theta\) | \(-\cos \theta\) | \(-\cos \theta\) | \(-\sin \theta\) | \(\sin \theta\) | \(\cos \theta\) | \(\cos \theta\) |
| tangent | \(-\tan \theta\) | \(\cot \theta\) | \(-\cot \theta\) | \(-\tan \theta\) | \(\tan \theta\) | \(\cot \theta\) | \(-\cot \theta\) | \(-\tan \theta\) | \(\tan \theta\) |

(i) The corresponding reciprocal ratios can be written using the above table.

(ii) If the allied angles are \( \pm \theta, \pi \pm \theta, 2\pi \pm \theta \), that is, angles of the form \( \frac{2n\pi}{2} \pm \theta, n \in \mathbb{Z} \), then, the form of trigonometric ratio is unaltered (i.e., sine remains sine, cosine remains cosine etc.)

(iii) If the allied angles are \( \frac{\pi}{2} \pm \theta, \frac{3\pi}{2} \pm \theta \), that is, angles of the form \( \frac{(2n + 1)\pi}{2} \pm \theta, n \in \mathbb{Z} \), then, the form of trigonometric ratio is altered to its complementary ratio. i.e., it is to add the prefix "co" if it is absent and remove the prefix "co" if it is already present (i.e., sine becomes cosine, cosine becomes sine etc.)

(iv) For determining the sign, first find out the quadrant and then attach the appropriate sign (+ or -) according to the quadrant rule "ASTC".

### Example 3.11

Find the value of (i) \( \sin 150^\circ \) (ii) \( \cos 135^\circ \) (iii) \( \tan 120^\circ \).

**Solution:**

(i) \( \sin 150^\circ = \sin(90^\circ + 60^\circ) = \cos(60^\circ) = \frac{1}{2} \)

(or) \( \sin 150^\circ = \sin(180^\circ - 30^\circ) = \sin(30^\circ) = \frac{1}{2} \)

(ii) \( \cos 135^\circ = \cos(90^\circ + 45^\circ) = -\sin(45^\circ) = -\frac{1}{\sqrt{2}} \)

(or) \( \cos 135^\circ = \cos(180^\circ - 45^\circ) = -\cos(45^\circ) = -\frac{1}{\sqrt{2}} \)

(iii) \( \tan 120^\circ = \tan(180^\circ - 60^\circ) = -\tan(60^\circ) = -\sqrt{3} \)

(or) write \( \tan 120^\circ \) as \( \tan(90^\circ + 30^\circ) \) and find the value.

### Example 3.12

Find the value of:
(i) \( \sin(765^\circ) \) (ii) \( \csc(-1410^\circ) \) (iii) \( \cot\left(-\frac{15\pi}{4}\right) \).

**Solution:**

(i) \( \sin 765^\circ = \sin(2 \times 360^\circ + 45^\circ) = \sin 45^\circ = \frac{1}{\sqrt{2}} \)

(ii) \( \csc(-1410^\circ) = -\csc(1410^\circ) = -\csc(4 \times 360^\circ - 30^\circ) = \csc 30^\circ = 2 \)

(iii) \( \cot\left(-\frac{15\pi}{4}\right) = -\cot\left(\frac{15\pi}{4}\right) = -\cot\left(4\pi - \frac{\pi}{4}\right) = \cot \frac{\pi}{4} = 1 \).

### Example 3.13

Prove that \( \tan(315^\circ) \cot(-405^\circ) + \cot(495^\circ) \tan(-585^\circ) = 2 \)

**Solution:**

\[
\text{L.H.S} = \tan(360^\circ - 45^\circ) [-\cot(360^\circ + 45^\circ)] + \cot(360^\circ + 135^\circ) [-\tan(360^\circ + 225^\circ)]
\]
\[
= [-\tan 45^\circ] [-\cot 45^\circ] + [-\tan 45^\circ] [-\tan 45^\circ] = (-1)(-1) + (-1)(-1) = 2 = \text{R.H.S}
\]

### 3.4.4 Some Characteristics of Trigonometric Functions

Trigonometric functions have some nice properties. For example,

(i) Sine and cosine functions are complementary to each other in the sense that \( \sin(90^\circ - \theta) = \cos \theta \) and \( \cos(90^\circ - \theta) = \sin \theta \).

(ii) As \( \cos \theta \) and \( \sin \theta \) are obtained as coordinates of a point on the unit circle, they satisfy the inequalities \( -1 \leq \cos \theta \leq 1 \) and \( -1 \leq \sin \theta \leq 1 \). Hence, \( \cos \theta, \sin \theta \in [-1, 1] \).

(iii) Trigonometric function repeats its values in regular intervals.

(iv) Sine and cosine functions have an interesting property that \( \cos(-\theta) = \cos \theta \) and \( \sin(-\theta) = -\sin \theta \).

Let us discuss the last two properties.

### Periodicity of Trigonometric Functions

We know that a function \( f \) is said to be a periodic function with period \( p \), if there exists a smallest positive number \( p \) such that \( f(x + p) = f(x) \) for all \( x \) in the domain.

For example, \( \sin(x + 2n\pi) = \sin x, n \in \mathbb{Z} \).

i.e., \( \sin(x + 2\pi) = \sin(x + 4\pi) = \sin(x + 6\pi) = \ldots = \sin x \)

Thus, \( \sin x \) is a periodic function with period \( 2\pi \).

Similarly, \( \cos x \), \( \csc x \) and \( \sec x \) are periodic functions with period \( 2\pi \).

But \( \tan x \) and \( \cot x \) are periodic functions with period \( \pi \).

The periodicity of \( \sin x \) and \( \cos x \) can be viewed best using their graphs.

(i) The graph of the sine function

**Figure 3.13: \( y = \sin x \)**

Here \( x \) represents a variable angle. Take the horizontal axis to be the x-axis and vertical axis to be the y-axis. Graph of the function \( y = \sin x \) is shown in the Figure 3.13. First, note that it is periodic of period \( 2\pi \). Geometrically it means that if you take the curve and slide it \( 2\pi \) either left or right, then the curve falls back on itself. Second, note that the graph is within one unit of the y-axis. The graph increases and decreases periodically. For instance, increases from \( -\frac{\pi}{2} \) to \( \frac{\pi}{2} \) and decreases from \( \frac{\pi}{2} \) to \( \frac{3\pi}{2} \).

(ii) The graph of the cosine function

**Figure 3.14: \( y = \cos x \)**

Observe that the graph of \( y = \cos x \) looks just like the graph of \( y = \sin x \) except it is being translated to the left by \( \frac{\pi}{2} \). This is because of the identity \( \cos x = \sin\left(\frac{\pi}{2} + x\right) \). It easily follows from the graph that \( \cos x = \cos(-x) = \sin\left(\frac{\pi}{2} + x\right) \)

(i) The sine and cosine functions are useful for one very important reason, since they repeat in a regular pattern (i.e., they are periodic). There are a vast array of things in and around us that repeat periodically. For example, the rising and setting of the sun, the motion of a spring up and down, the tides of the ocean and so on, are repeating at regular intervals of time. All periodic behaviour can be studied through combinations of the sine and cosine functions.

(ii) Periodic functions are used throughout science to describe oscillations, waves and other phenomena that occur periodically.

### Odd and Even trigonometric functions

Even and odd functions are functions satisfying certain symmetries. A real valued function \( f(x) \) is an even function if it satisfies \( f(-x) = f(x) \) for all real number \( x \) and an odd function if it satisfies \( f(-x) = -f(x) \) for all real number \( x \).

Basic trigonometric functions are examples of non-polynomial even and odd functions

Because \( \cos(-x) = \cos x \) and \( \sin(-x) = -\sin x \) for all \( x \), it follows that \( \cos x \) is an even function and \( \sin x \) is an odd function.

Also note that \( \sec x \) is an even function while \( \tan x \), \( \csc x \) and \( \cot x \) are all odd functions.

However, \( f(t) = t - \cos t \) is neither even function nor odd function (why?)

### Example 3.14

Determine whether the following functions are even, odd or neither.

(i) \( \sin^2 x - 2\cos^2 x - \cos x \) (ii) \( \sin(\cos(x)) \) (iii) \( \cos(\sin(x)) \) (iv) \( \sin x + \cos x \)

**Solution:**

(i) Let \( f(x) = \sin^2 x - 2\cos^2 x - \cos x \)

\( f(-x) = f(x) \) [since \( \sin(-x) = -\sin x \) and \( \cos(-x) = \cos x \)]

Thus, \( f(x) \) is even.

(ii) Let \( f(x) = \sin(\cos(x)) \)

\( f(-x) = f(x) \)

Thus, \( f(x) \) is an even function.

(iii) \( f(x) = \cos(\sin(x)), f(-x) = f(x) \)

Thus, \( f(x) \) is an even function.

(iv) Let \( f(x) = \sin x + \cos x \)

\[
f(-x) \neq f(x) \text{ and } f(-x) \neq -f(x)
\]

Thus, \( f(x) = \sin x + \cos x \) is neither even nor odd.

(i) In general, a function is an even function if its graph is unchanged under reflection about the y-axis. A function is odd if its graph is symmetric about the origin.

(ii) The properties of even and odd functions are useful in analyzing trigonometric functions particularly in the sum and difference formula.

(iii) The properties of even and odd functions are useful in evaluating some definite integrals, which we will see in calculus.

## Exercise 3.3

1. Find the values of
   (i) \( \sin(480^\circ) \) (ii) \( \sin(-1110^\circ) \) (iii) \( \cos(300^\circ) \)
   (iv) \( \tan(1050^\circ) \) (v) \( \cot(660^\circ) \) (vi) \( \tan\left(\frac{19\pi}{3}\right) \) (vii) \( \sin\left(-\frac{11\pi}{3}\right) \).

2. \( \left(\frac{5}{7}, \frac{2\sqrt{6}}{7}\right) \) is a point on the terminal side of an angle \( \theta \) in standard position. Determine the six trigonometric function values of angle \( \theta \).

3. Find the values of other five trigonometric functions for the following:
   (i) \( \cos \theta = -\frac{1}{2} \), \( \theta \) lies in the III quadrant.
   (ii) \( \cos \theta = \frac{2}{3} \), \( \theta \) lies in the I quadrant.
   (iii) \( \sin \theta = -\frac{2}{3} \), \( \theta \) lies in the IV quadrant.
   (iv) \( \tan \theta = -2 \), \( \theta \) lies in the II quadrant.
   (v) \( \sec \theta = \frac{13}{5} \), \( \theta \) lies in the IV quadrant.

4. Prove that \( \frac{\cot(180^\circ + \theta) \sin(90^\circ - \theta) \cos(-\theta)}{\sin(270^\circ + \theta) \tan(-\theta) \csc(360^\circ + \theta)} = \cos^2 \theta \cot \theta \).

5. Find all the angles between \( 0^\circ \) and \( 360^\circ \) which satisfy the equation \( \sin^2 \theta = \frac{3}{4} \).

6. Show that \( \sin^2 \frac{\pi}{18} + \sin^2 \frac{\pi}{9} + \sin^2 \frac{7\pi}{18} + \sin^2 \frac{4\pi}{9} = 2 \).

## 3.5 Trigonometric Identities

### 3.5.1 Sum and difference identities or compound angles formulas

Now, compound angles are algebraic sum of two or more angles. Trigonometric functions do not satisfy the functional relations like \( f(x + y) = f(x) + f(y) \) and \( f(kx) = kf(x) \), \( k \) is a real number. For example, \( \cos(\alpha + \beta) \neq \cos \alpha + \cos \beta \), \( \sin(2\alpha) \neq 2\sin \alpha \), \( \tan 3\alpha \neq 3\tan \alpha \), ... Thus, we need to derive formulas for \( \sin(\alpha + \beta) \), \( \cos(\alpha + \beta) \), ... and use them in calculations of application problems.

Music is made up of vibrations that create pressure on ear-drums. Musical tones can be modeled with sinusoidal graphs (graphs looks like that of \( y = \sin x \) or \( y = \cos x \)). When more than one tone is played, the resulting pressure is equal to the sum of the individual pressures. In this context sum and difference trigonometric identities are used as an important application. Also, sum and difference trigonometric identities are helpful in the analysis of waves.

First we shall prove the identity for the cosine of the sum of two angles and extend it to prove all other sum or difference identities.

**Identity 3.1:** \( \cos(\alpha + \beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta \)

**Proof.** Consider the unit circle with centre at \( O \). Let \( P = P(1, 0) \).

**Figure 3.15**

Let \( Q, R \) and \( S \) be points on the unit circle such that \( \angle POQ = \alpha \), \( \angle POR = \alpha + \beta \) and \( \angle POS = -\beta \) as shown in the Figure 3.15. Clearly, angles \( \alpha, \alpha + \beta \) and \( -\beta \) are in standard positions. Now, the points \( Q, R \) and \( S \) are given by \( Q(\cos \alpha, \sin \alpha) \), \( R(\cos(\alpha + \beta), \sin(\alpha + \beta)) \) and \( S(\cos(-\beta), \sin(-\beta)) \).

Since \( \triangle POR \) and \( \triangle SOQ \) are congruent. So, \( PR = SQ \) which gives \( PR^2 = SQ^2 \)

Thus,
\[
[\cos(\alpha + \beta) - 1]^2 + \sin^2(\alpha + \beta) = [\cos \alpha - \cos(-\beta)]^2 + [\sin \alpha - \sin(-\beta)]^2
\]
\[
-2\cos(\alpha + \beta) + 2 = 2 - 2\cos \alpha \cos \beta + 2\sin \alpha \sin \beta
\]
Hence,
\[
\cos(\alpha + \beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta
\]

(i) In the above proof, \( PR = SQ \) says that the distance between two points on a circle is determined by the radius and the central angle.

(ii) Arc lengths PR and SQ, subtends angles \( \alpha + \beta \) and \( \alpha + (-\beta) \) respectively at the center. Thus, \( PR = SQ \). Thus, distance between the points \( (\cos \alpha, \sin \alpha) \) and \( (\cos(-\beta), \sin(-\beta)) \) is same as the distance between the points \( (\cos(\alpha + \beta), \sin(\alpha + \beta)) \) and \( (1, 0) \)

(iii) In the above derivations, \( 0 \leq \alpha < 2\pi \), \( 0 \leq \beta < 2\pi \). Because of periodicity of sine and cosine, the result follows for any \( \alpha \) and \( \beta \)

**Identity 3.2:** \( \cos(\alpha - \beta) = \cos \alpha \cos \beta + \sin \alpha \sin \beta \)

**Proof.**

We know that \( \cos(\alpha + \beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta \)

\[
\cos(\alpha - \beta) = \cos[\alpha + (-\beta)]
\]
\[
= \cos \alpha \cos(-\beta) - \sin \alpha \sin(-\beta)
\]

Hence, \( \cos(\alpha - \beta) = \cos \alpha \cos \beta + \sin \alpha \sin \beta \)

(i) If \( \alpha = \beta \), the above identity is reduced to \( \cos^2 \alpha + \sin^2 \alpha = 1 \)

(ii) If \( \alpha = 0 \) and \( \beta = x \), then \( \cos(-x) = \cos x \), which shows that \( \cos x \) is an even function.

**Identity 3.3:** \( \sin(\alpha + \beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta \)

**Proof.** This formula may be proved by writing \( \sin(\alpha + \beta) = \cos\left[\frac{\pi}{2} - (\alpha + \beta)\right] = \cos\left[\left(\frac{\pi}{2} - \alpha\right) - \beta\right] \) and by using Identity 3.2.

If \( \alpha + \beta = \frac{\pi}{2} \), the above identity is reduced to \( \cos^2 \alpha + \sin^2 \alpha = 1 \)

**Identity 3.4:** \( \sin(\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta \)

**Proof.** This formula may be proved by writing \( \sin(\alpha - \beta) = \sin[\alpha + (-\beta)] \) and by using Identity 3.3.

The sum and difference formulas for sine and cosine can be written in the matrix form

**Identity 3.5:** \( \tan(\alpha + \beta) = \frac{\tan \alpha + \tan \beta}{1 - \tan \alpha \tan \beta} \)

**Proof.**

\[
\tan(\alpha + \beta) = \frac{\sin(\alpha + \beta)}{\cos(\alpha + \beta)} = \frac{\sin \alpha \cos \beta + \cos \alpha \sin \beta}{\cos \alpha \cos \beta - \sin \alpha \sin \beta}
\]
\[
= \frac{\frac{\sin \alpha \cos \beta + \cos \alpha \sin \beta}{\cos \alpha \cos \beta}}{\frac{\cos \alpha \cos \beta - \sin \alpha \sin \beta}{\cos \alpha \cos \beta}} = \frac{\tan \alpha + \tan \beta}{1 - \tan \alpha \tan \beta}
\]

**Identity 3.6:** \( \tan(\alpha - \beta) = \frac{\tan \alpha - \tan \beta}{1 + \tan \alpha \tan \beta} \)

**Proof.** This result may be proved by writing \( \tan(\alpha - \beta) = \tan[\alpha + (-\beta)] \) and using the Identity 3.5.

(i) Ptolemy (CE 100-170) treated the chord of an angle as his basic trigonometric function and proved the theorem: In a cyclic quadrilateral, the product of diagonals equals the sum of the products of opposite sides. That is, in a cyclic quadrilateral \( ABCD \)

\[
(AC)(BD) = (AB)(CD) + (AD)(BC).
\]

Using this theorem, one can prove Sum and Difference identities. Hence, these identities are known as Ptolemy's sum and difference formulas.

**Figure 3.16**

(ii) Observe that \( \cos(\alpha \pm \beta) \neq \cos \alpha \pm \cos \beta \). Similarly we can observe for other trigonometric functions also.

(iii) When \( \alpha = \beta \), \( \sin(\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta \) implies \( \sin 0 = 0 \), which we have already established.

(iv) When \( \alpha = \frac{\pi}{2} \) and \( \beta = \theta \), \( \sin(\alpha - \beta) = \sin \alpha \cos \beta - \cos \alpha \sin \beta \) gives \( \sin\left(\frac{\pi}{2} - \theta\right) = \cos \theta \), which we have already proved.

(v) We can find the trigonometric function values of a given angle, if we can break it up into sum or difference of two of the special angles. For example, we can evaluate \( \tan 75^\circ \) as \( \tan(45^\circ + 30^\circ) \) and \( \cos 135^\circ \) as \( \cos(180^\circ - 45^\circ) \).

### Example 3.15

Find the values of (i) \( \cos 15^\circ \) and (ii) \( \tan 165^\circ \).

**Solution:**

\[
\cos 15^\circ = \cos(45^\circ - 30^\circ) = \cos 45^\circ \cos 30^\circ + \sin 45^\circ \sin 30^\circ
\]
\[
= \frac{1}{\sqrt{2}} \cdot \frac{\sqrt{3}}{2} + \frac{1}{\sqrt{2}} \cdot \frac{1}{2} = \frac{\sqrt{3} + 1}{2\sqrt{2}}
\]
Also, note that \( \sin 75^\circ = \frac{\sqrt{3} + 1}{2\sqrt{2}} \)

\[
\tan 165^\circ = \tan(120^\circ + 45^\circ) = \frac{\tan 120^\circ + \tan 45^\circ}{1 - \tan 120^\circ \tan 45^\circ}
\]
But, \( \tan 120^\circ = \tan(90^\circ + 30^\circ) = -\cot 30^\circ = -\sqrt{3} \) and \( \tan 45^\circ = 1 \)

Thus, \( \tan 165^\circ = \frac{1 - \sqrt{3}}{1 + \sqrt{3}} \).

### Example 3.16

If \( \sin x = \frac{4}{5} \) (in I quadrant) and \( \cos y = -\frac{12}{13} \) (in II quadrant), then find (i) \( \sin(x - y) \), (ii) \( \cos(x - y) \).

**Solution:**

Given that \( \sin x = \frac{4}{5} \).

\( \cos^2 x + \sin^2 x = 1 \) gives \( \cos x = \pm \sqrt{1 - \sin^2 x} = \pm \sqrt{1 - \frac{16}{25}} = \pm \frac{3}{5} \)

In the first quadrant, \( \cos x \) is always positive. Thus, \( \cos x = \frac{3}{5} \).

Also, given that \( \cos y = -\frac{12}{13} \) in the II quadrant. We have

\( \sin y = \pm \sqrt{1 - \cos^2 y} = \pm \sqrt{1 - \frac{144}{169}} = \pm \frac{5}{13} \).

In the second quadrant, \( \sin y \) is always positive. Thus, \( \sin y = \frac{5}{13} \).

(i) \( \sin(x - y) = \sin x \cos y - \cos x \sin y = \frac{4}{5} \left(-\frac{12}{13}\right) - \frac{3}{5} \left(\frac{5}{13}\right) = -\frac{63}{65} \).

(ii) \( \cos(x - y) = \cos x \cos y + \sin x \sin y = \frac{3}{5} \left(-\frac{12}{13}\right) + \frac{4}{5} \left(\frac{5}{13}\right) = -\frac{16}{65} \).

### Example 3.17

Prove that \( \cos\left(\frac{3\pi}{4} + x\right) - \cos\left(\frac{3\pi}{4} - x\right) = -\sqrt{2} \sin x \)

**Solution:**

\[
\text{L.H.S} = \cos \frac{3\pi}{4} \cos x - \sin \frac{3\pi}{4} \sin x - \cos \frac{3\pi}{4} \cos x - \sin \frac{3\pi}{4} \sin x
\]
\[
= -2 \sin \left(\pi - \frac{\pi}{4}\right) \sin x = -2 \left(\frac{1}{\sqrt{2}}\right) \sin x = -\sqrt{2} \sin x
\]

Observe that \( \cos(A + x) - \cos(A - x) = -2 \sin A \sin x \)

### Example 3.18

Point \( A(9, 12) \) rotates around the origin \( O \) in a plane through \( 60^\circ \) in the anticlockwise direction to a new position \( B \). Find the coordinates of the point \( B \).

**Solution:**

Let \( A(9, 12) = A(r \cos \theta, r \sin \theta) \), where \( r = OA \). Then \( r \cos \theta = 9 \) and \( r \sin \theta = 12 \).

Thus, \( r^2 = 81 + 144 = 225 \Rightarrow r = 15 \).

Hence, the point \( A \) is given by \( A(15 \cos \theta, 15 \sin \theta) \).

Now, the point \( B \) is given by \( B(15 \cos(\theta + 60^\circ), 15 \sin(\theta + 60^\circ)) \).

\[
15 \cos(\theta + 60^\circ) = 15 (\cos \theta \cos 60^\circ - \sin \theta \sin 60^\circ)
\]
\[
= (15 \cos \theta) \cos 60^\circ - (15 \sin \theta) \sin 60^\circ = 9 \times \frac{1}{2} - 12 \times \frac{\sqrt{3}}{2} = \frac{3}{2}(3 - 4\sqrt{3})
\]

Similarly, \( 15 \sin(\theta + 60^\circ) = \frac{3}{2}(4 + 3\sqrt{3}) \). Hence, the point \( B \) is given by
\[
B\left( \frac{3}{2}(3 - 4\sqrt{3}), \frac{3}{2}(4 + 3\sqrt{3}) \right).
\]

### Example 3.19

A ripple tank demonstrates the effect of two water waves being added together. The two waves are described by \( h = 8 \cos t \) and \( h = 6 \sin t \), where \( t \in [0, 2\pi) \) is in seconds and \( h \) is the height in millimeters above still water. Find the maximum height of the resultant wave and the value of \( t \) at which it occurs.

**Solution:**

Let \( H \) be the height of the resultant wave at time \( t \). Then \( H \) is given by
\[
H = 8 \cos t + 6 \sin t
\]
Let \( 8 \cos t + 6 \sin t = k \cos(t - \alpha) = k(\cos t \cos \alpha + \sin t \sin \alpha) \)

Hence, \( k = 10 \) and \( \tan \alpha = \frac{3}{4} \), so that
\[
H = 10 \cos(t - \alpha)
\]

Thus, the maximum of \( H = 10 \) mm. The maximum occurs when \( t = \alpha \), where \( \tan \alpha = \frac{3}{4} \).

### Example 3.20

Expand (i) \( \sin(A + B + C) \) (ii) \( \tan(A + B + C) \)

**Solution:**

(i) \( \sin(A + B + C) = \sin[A + (B + C)] \)
\[
= \sin A \cos(B + C) + \cos A \sin(B + C)
\]
\[
= \sin A \cos B \cos C + \cos A \sin B \cos C
\]
\[
+ \cos A \cos B \sin C - \sin A \sin B \sin C
\]

(ii) \( \tan(A + B + C) = \tan[A + (B + C)] \)
\[
= \frac{\tan A + \tan(B + C)}{1 - \tan A \tan(B + C)}
\]
\[
= \frac{\tan A + \frac{\tan B + \tan C}{1 - \tan B \tan C}}{1 - \tan A \cdot \frac{\tan B + \tan C}{1 - \tan B \tan C}}
\]
\[
= \frac{\tan A + \tan B + \tan C - \tan A \tan B \tan C}{1 - \tan A \tan B - \tan B \tan C - \tan C \tan A}
\]

(i) If \( A + B + C = 0 \) or \( \pi \), we have \( \tan(A + B + C) = 0 \) so that
\[
\tan A + \tan B + \tan C = \tan A \tan B \tan C.
\]
This result is also true in the case of oblique triangles.

(ii) \( \tan(x - y) + \tan(y - z) + \tan(z - x) = \tan(x - y) \tan(y - z) \tan(z - x) \)

## Exercise 3.4

1. If \( \sin x = \frac{15}{17} \) and \( \cos y = \frac{12}{13} \), \( 0 < x < \frac{\pi}{2} \), \( 0 < y < \frac{\pi}{2} \), find the value of
   (i) \( \sin(x + y) \) (ii) \( \cos(x - y) \) (iii) \( \tan(x + y) \).

2. If \( \sin A = \frac{3}{5} \) and \( \cos B = \frac{9}{41} \), \( 0 < A < \frac{\pi}{2} \), \( 0 < B < \frac{\pi}{2} \), find the value of
   (i) \( \sin(A + B) \) (ii) \( \cos(A - B) \).

3. Find \( \cos(x - y) \), given that \( \cos x = -\frac{4}{5} \) with \( \pi < x < \frac{3\pi}{2} \) and \( \sin y = -\frac{24}{25} \) with \( \pi < y < \frac{3\pi}{2} \).

4. Find \( \sin(x - y) \), given that \( \sin x = \frac{8}{17} \) with \( 0 < x < \frac{\pi}{2} \) and \( \cos y = -\frac{24}{25} \) with \( \pi < y < \frac{3\pi}{2} \).

5. Find the value of
   (i) \( \cos 105^\circ \) (ii) \( \sin 105^\circ \) (iii) \( \tan \frac{7\pi}{12} \).

6. Prove that
   (i) \( \cos(30^\circ + x) = \frac{\sqrt{3}\cos x - \sin x}{2} \)
   (ii) \( \cos(\pi + \theta) = -\cos \theta \)
   (iii) \( \sin(\pi + \theta) = -\sin \theta \).

7. Find a quadratic equation whose roots are \( \sin 15^\circ \) and \( \cos 15^\circ \).

8. Expand \( \cos(A + B + C) \). Hence prove that
   \( \cos A \cos B \cos C = \sin A \sin B \cos C + \sin B \sin C \cos A + \sin C \sin A \cos B \), if \( A + B + C = \frac{\pi}{2} \).

9. Prove that
   (i) \( \sin(45^\circ + \theta) - \sin(45^\circ - \theta) = \sqrt{2} \sin \theta \).
   (ii) \( \sin(30^\circ + \theta) + \cos(60^\circ + \theta) = \cos \theta \).

10. If \( a \cos(x + y) = b \cos(x - y) \), show that \( (a + b) \tan x = (a - b) \cot y \).

11. Prove that \( \sin 105^\circ + \cos 105^\circ = \cos 45^\circ \).

12. Prove that \( \sin 75^\circ - \sin 15^\circ = \cos 105^\circ + \cos 15^\circ \).

13. Show that \( \tan 75^\circ + \cot 75^\circ = 4 \).

14. Prove that \( \cos(A + B) \cos C - \cos(B + C) \cos A = \sin B \sin(C - A) \).

15. Prove that \( \sin(n + 1)\theta \sin(n - 1)\theta + \cos(n + 1)\theta \cos(n - 1)\theta = \cos 2\theta \), \( n \in \mathbb{Z} \).

16. If \( x \cos \theta = y \cos\left(\theta + \frac{2\pi}{3}\right) = z \cos\left(\theta + \frac{4\pi}{3}\right) \), find the value of \( xy + yz + zx \).

17. Prove that
    (i) \( \sin(A + B) \sin(A - B) = \sin^2 A - \sin^2 B \)
    (ii) \( \cos(A + B) \cos(A - B) = \cos^2 A - \sin^2 B = \cos^2 B - \sin^2 A \)
    (iii) \( \sin^2(A + B) - \sin^2(A - B) = \sin 2A \sin 2B \)
    (iv) \( \cos 8\theta \cos 2\theta = \cos^2 5\theta - \sin^2 3\theta \)

18. Show that \( \cos^2 A + \cos^2 B - 2\cos A \cos B \cos(A + B) = \sin^2(A + B) \).

19. If \( \cos(\alpha - \beta) + \cos(\beta - \gamma) + \cos(\gamma - \alpha) = -\frac{3}{2} \), then prove that \( \cos \alpha + \cos \beta + \cos \gamma = \sin \alpha + \sin \beta + \sin \gamma = 0 \).

20. Show that
    (i) \( \tan(45^\circ + A) = \frac{1 + \tan A}{1 - \tan A} \)
    (ii) \( \tan(45^\circ - A) = \frac{1 - \tan A}{1 + \tan A} \).

21. Prove that \( \cot(A + B) = \frac{\cot A \cot B - 1}{\cot A + \cot B} \).

22. If \( \tan x = \frac{n}{n + 1} \) and \( \tan y = \frac{1}{2n + 1} \), find \( \tan(x + y) \).

23. Prove that \( \tan\left(\frac{\pi}{4} + \theta\right) \tan\left(\frac{3\pi}{4} + \theta\right) = -1 \).

24. Find the values of \( \tan(\alpha + \beta) \), given that \( \cot \alpha = \frac{1}{2} \), \( \alpha \in \left(\pi, \frac{3\pi}{2}\right) \) and \( \sec \beta = -\frac{5}{3} \), \( \beta \in \left(\frac{\pi}{2}, \pi\right) \).

25. If \( \theta + \phi = \alpha \) and \( \tan \theta = k \tan \phi \), then prove that \( \sin(\theta - \phi) = \frac{k - 1}{k + 1} \sin \alpha \).

### 3.5.2 Multiple angle identities and submultiple angle identities

In 1831, Michael Faraday discovered that when a wire is passed near a magnet, a small electric current is produced in the wire. This property is used to generate electric current for houses, institutions and business establishments throughout the world. By rotating thousands of wires near large electromagnets, massive amount of electricity can be produced.

Voltage is a quantity that can be modeled by sinusoidal graphs and functions. To model electricity and other phenomena, trigonometric functions and identities involving multiple angles or sub multiple angles are used.

If \( A \) is an angle, then \( 2A, 3A, \ldots \) are called multiple angles of \( A \) and the angle \( \frac{A}{2}, \frac{A}{3}, \ldots \) are called sub-multiple angles of \( A \). Now we shall discuss the trigonometric ratio of multiple angles and sub-multiple angles and derive some identities.

### Double Angle Identities

Let us take up the sum and difference identities and examine some of the consequences that come from them. Double angle identities are a special case of the sum identities. That is, when the two angles are equal, the sum identities are reduced to double angle identities. They are useful in solving trigonometric equations and also in the verification of trigonometric identities. Further double angle identities can be used to derive the reduction identities (power reducing identities). Also double angle identities are used to find maximum or minimum values of trigonometric expressions.

**Identity 3.7:** \( \sin 2A = 2\sin A \cos A \)

**Proof.**

We know that \( \sin(\alpha + \beta) = \sin \alpha \cos \beta + \cos \alpha \sin \beta \)

Taking \( \alpha = \beta = A \), we have \( \sin(A + A) = \sin A \cos A + \sin A \cos A \)

Thus, \( \sin 2A = 2\sin A \cos A \)

(i) \( y = \sin 2x \) and \( y = 2\sin x \) are different. Draw their graphs and identify the difference.

(ii) Application of \( \sin 2A = 2\sin A \cos A \): When an object is projected with speed \( u \) at an angle \( \alpha \) to the horizontal over level ground, the horizontal distance (Range) it travels before striking the ground is given by the formula \( R = \frac{u^2 \sin 2\alpha}{g} \)

Clearly maximum of \( R \) is \( \frac{u^2}{g} \), when \( \alpha = \frac{\pi}{4} \).

Thus, \( \sin A \cos A = \frac{1}{2} \sin 2A \)

From this, we infer that the maximum value of \( \sin A \cos A \) is \( \frac{1}{2} \) when \( A = \frac{\pi}{4} \)

### Example 3.21

A football player can kick a football from ground level with an initial velocity of 80 ft/second. Find the maximum horizontal distance the football travels and at what angle? (Take \( g = 32 \)).

**Solution:**

The formula for horizontal distance \( R \) is given by
\[
R = \frac{u^2 \sin 2\alpha}{g} = \frac{(80 \times 80) \sin 2\alpha}{32} = 10 \times 20 \sin 2\alpha.
\]

Thus, the maximum distance is 200 ft.

Hence, he has to kick the football at an angle of \( \alpha = 45^\circ \) to reach the maximum distance.

**Identity 3.8:** \( \cos 2A = \cos^2 A - \sin^2 A \)

**Proof.**

\[
\cos(\alpha + \beta) = \cos \alpha \cos \beta - \sin \alpha \sin \beta
\]
Taking \( \alpha = \beta = A \),
\[
\cos(A + A) = \cos A \cos A - \sin A \sin A
\]
\[
\cos 2A = \cos^2 A - \sin^2 A.
\]

From the identity \( \cos 2A = \cos^2 A - \sin^2 A \), we also have
\[
\cos 2A = \cos^2 A - (1 - \cos^2 A) = 2\cos^2 A - 1 \text{ and }
\]
\[
\cos 2A = (1 - \sin^2 A) - \sin^2 A = 1 - 2\sin^2 A.
\]

**Identity 3.9:** \( \tan 2A = \frac{2\tan A}{1 - \tan^2 A} \)

**Proof.**

\[
\tan(\alpha + \beta) = \frac{\tan \alpha + \tan \beta}{1 - \tan \alpha \tan \beta}
\]
Taking \( \alpha = \beta = A \),
\[
\tan(A + A) = \frac{\tan A + \tan A}{1 - \tan A \tan A}
\]
\[
\tan 2A = \frac{2\tan A}{1 - \tan^2 A}.
\]

**Identity 3.10:** \( \sin 2A = \frac{2\tan A}{1 + \tan^2 A} \)

**Proof.**

We know that \( \sin 2A = 2\sin A \cos A = \frac{2\sin A \cos A}{\sin^2 A + \cos^2 A} \)
\[
= \frac{2\sin A \cos A}{\sin^2 A + \cos^2 A} = \frac{2\tan A}{1 + \tan^2 A}.
\]

**Identity 3.11:** \( \cos 2A = \frac{1 - \tan^2 A}{1 + \tan^2 A} \)

**Proof.**

We know that \( \cos 2A = \cos^2 A - \sin^2 A = \frac{\cos^2 A - \sin^2 A}{\cos^2 A + \sin^2 A} \)
\[
= \frac{1 - \tan^2 A}{1 + \tan^2 A}
\]

Thus, \( \cos 2A = \frac{1 - \tan^2 A}{1 + \tan^2 A} \).

### Power reducing identities or Reduction identities

Power reducing identities for sine, cosine and tangent can be derived using the double-angle identities. For example,
\[
\cos 2A = 2\cos^2 A - 1 \Rightarrow \cos^2 A = \frac{1 + \cos 2A}{2}
\]

The following table is the list of power reducing identities.

| Power Reducing Identities |
|--------------------------|
| \( \sin^2 A = \frac{1 - \cos 2A}{2} \) |
| \( \cos^2 A = \frac{1 + \cos 2A}{2} \) |
| \( \tan^2 A = \frac{1 - \cos 2A}{1 + \cos 2A} \) |

(i) In the power reducing identities, we have reduced the square power on one side to power 1 on the other side.

(ii) Power reducing identities allow us to rewrite the even powers of sine or cosine in terms of the first power of cosine. For example, using power reducing identities one can easily prove that \( \cos^4 x = \frac{1}{8}\cos 4x + \frac{1}{2}\cos 2x + \frac{3}{8} \) and \( \sin^4 x = \frac{1}{8}\cos 4x - \frac{1}{2}\cos 2x + \frac{3}{8} \) (Try it!).

(iii) Power reducing formulas are important in higher level mathematics.

### Triple-Angle Identities

Using double angle identities, we can derive triple angle identities.

**Identity 3.12:** \( \sin 3A = 3\sin A - 4\sin^3 A \)

**Proof.**

We have, \( \sin 3A = \sin(2A + A) = \sin 2A \cos A + \cos 2A \sin A \)
\[
= 2\sin A \cos^2 A + (1 - 2\sin^2 A) \sin A
\]
\[
= 2\sin A(1 - \sin^2 A) + (1 - 2\sin^2 A) \sin A
\]
\[
= 3\sin A - 4\sin^3 A
\]

**Identity 3.13:** \( \cos 3A = 4\cos^3 A - 3\cos A \)

**Proof.**

\[
\cos 3A = \cos(2A + A) = \cos 2A \cos A - \sin 2A \sin A
\]
\[
= (2\cos^2 A - 1)\cos A - 2\sin A \cos A \sin A
\]
\[
= (2\cos^2 A - 1)\cos A + 2\cos A(1 - \cos^2 A)
\]
\[
= 4\cos^3 A - 3\cos A.
\]

**Identity 3.14:** \( \tan 3A = \frac{3\tan A - \tan^3 A}{1 - 3\tan^2 A} \)

**Proof.**

\[
\tan 3A = \tan(2A + A)
\]
\[
= \frac{\tan 2A + \tan A}{1 - \tan 2A \tan A}
\]
\[
= \frac{\frac{2\tan A}{1 - \tan^2 A} + \tan A}{1 - \frac{2\tan A}{1 - \tan^2 A} \cdot \tan A}
\]
\[
= \frac{3\tan A - \tan^3 A}{1 - 3\tan^2 A}.
\]

Double and Triple angle identities are given below:

| Function | sine | cosine | tangent |
|----------|------|--------|---------|
| Double | \( \sin 2A = 2\sin A \cos A = \frac{2\tan A}{1 + \tan^2 A} \) | \( \cos 2A = \cos^2 A - \sin^2 A = 2\cos^2 A - 1 = 1 - 2\sin^2 A = \frac{1 - \tan^2 A}{1 + \tan^2 A} \) | \( \tan 2A = \frac{2\tan A}{1 - \tan^2 A} \) |
| Triple | \( \sin 3A = 3\sin A - 4\sin^3 A \) | \( \cos 3A = 4\cos^3 A - 3\cos A \) | \( \tan 3A = \frac{3\tan A - \tan^3 A}{1 - 3\tan^2 A} \) |

### Half-Angle Identities

Half angle identities are closely related to the double angle identities. We can use half angle identities when we have an angle that is half the size of a special angle. For example, \( \sin 15^\circ \) can be computed by writing \( \sin 15^\circ = \sin \frac{30^\circ}{2} \). Also one can find exact values for some angles using half-angle identities. If we put \( 2A = \theta \) or \( A = \frac{\theta}{2} \) in the double angle identities, we get new identities in terms of angle \( \frac{\theta}{2} \).

| Double angle identity | Half-angle identity |
|----------------------|---------------------|
| \( \sin 2A = 2\sin A \cos A \) | \( \sin \theta = 2\sin \frac{\theta}{2} \cos \frac{\theta}{2} \) |
| \( \cos 2A = \cos^2 A - \sin^2 A \) | \( \cos \theta = \cos^2 \frac{\theta}{2} - \sin^2 \frac{\theta}{2} \) |
| \( \cos 2A = 2\cos^2 A - 1 \) | \( \cos \theta = 2\cos^2 \frac{\theta}{2} - 1 \) |
| \( \cos 2A = 1 - 2\sin^2 A \) | \( \cos \theta = 1 - 2\sin^2 \frac{\theta}{2} \) |
| \( \tan 2A = \frac{2\tan A}{1 - \tan^2 A} \) | \( \tan \theta = \frac{2\tan \frac{\theta}{2}}{1 - \tan^2 \frac{\theta}{2}} \) |
| \( \sin 2A = \frac{2\tan A}{1 + \tan^2 A} \) | \( \sin \theta = \frac{2\tan \frac{\theta}{2}}{1 + \tan^2 \frac{\theta}{2}} \) |
| \( \cos 2A = \frac{1 - \tan^2 A}{1 + \tan^2 A} \) | \( \cos \theta = \frac{1 - \tan^2 \frac{\theta}{2}}{1 + \tan^2 \frac{\theta}{2}} \) |

(i) The half angle identities are often used to replace a squared trigonometric function by a non squared trigonometric function.

(ii) Half angle identities allow us to find the value of the sine and cosine of half the angle if we know the value of the cosine of the original angle.

### Example 3.22

Find the value of \( \sin\left(22\frac{1}{2}^\circ\right) \)

**Solution:**

We know that \( \cos \theta = 1 - 2\sin^2 \frac{\theta}{2} \Rightarrow \sin \frac{\theta}{2} = \pm \sqrt{\frac{1 - \cos \theta}{2}} \).

Take \( \theta = 45^\circ \) we get \( \sin \frac{45^\circ}{2} = \pm \sqrt{\frac{1 - \cos 45^\circ}{2}} \) (taking positive sign only, since \( 22\frac{1}{2}^\circ \) lies in the first quadrant)

Thus, \( \sin 22\frac{1}{2}^\circ = \sqrt{\frac{1 - \frac{1}{\sqrt{2}}}{2}} = \frac{\sqrt{2 - \sqrt{2}}}{2} \).

### Example 3.23

Find the value of \( \sin 2\theta \), when \( \sin \theta = \frac{12}{13} \), \( \theta \) lies in the first quadrant.

**Solution:**

Using a right triangle, we can easily find that \( \cos \theta = \frac{5}{13} \)

\[
\sin 2\theta = 2\sin \theta \cos \theta = 2\left(\frac{12}{13}\right)\left(\frac{5}{13}\right) = \frac{120}{169}.
\]

Instead of constructing the triangle, we can also find the value of \( \cos \theta \) using \( \cos \theta = \pm \sqrt{1 - \sin^2 \theta} \) formula.

### Example 3.24

Prove that \( \sin 4A = 4\sin A \cos^3 A - 4\cos A \sin^3 A \)

**Solution:**

\[
4\sin A \cos^3 A - 4\cos A \sin^3 A = 4\sin A \cos A(\cos^2 A - \sin^2 A)
\]
\[
= 4\sin A \cos A \cos 2A = 2(2\sin A \cos A) \cos 2A
\]
\[
= 2(\sin 2A) \cos 2A = \sin 4A.
\]

### Example 3.25

Prove that \( \sin x = 2^{10} \sin\left(\frac{x}{2^{10}}\right) \cos\left(\frac{x}{2}\right) \cos\left(\frac{x}{2^2}\right) \dots \cos\left(\frac{x}{2^{10}}\right) \)

**Solution:**

\[
\sin x = 2 \sin \frac{x}{2} \cos \frac{x}{2}
\]
\[
= 2^2 \sin \frac{x}{4} \cos \frac{x}{4} \cos \frac{x}{2}
\]

Applying repeatedly the half angle sine formula, we get
\[
\sin x = 2^{10} \sin\left(\frac{x}{2^{10}}\right) \cos\left(\frac{x}{2}\right) \cos\left(\frac{x}{2^2}\right) \dots \cos\left(\frac{x}{2^{10}}\right).
\]

The above result can be extended to any finite number of times.

### Example 3.26

Prove that \( \frac{\sin \theta + \sin 2\theta}{1 + \cos \theta + \cos 2\theta} = \tan \theta \)

**Solution:**

\[
\frac{\sin \theta + \sin 2\theta}{1 + \cos \theta + \cos 2\theta} = \frac{\sin \theta + 2\sin \theta \cos \theta}{\cos \theta + (1 + \cos 2\theta)}
\]
\[
= \frac{\sin \theta(1 + 2\cos \theta)}{\cos \theta(1 + 2\cos \theta)} = \tan \theta.
\]

### Example 3.27

Prove that \( 1 - \frac{1}{2} \sin 2x = \frac{\sin^3 x + \cos^3 x}{\sin x + \cos x} \)

**Solution:**

\[
\frac{\sin^3 x + \cos^3 x}{\sin x + \cos x} = \frac{(\sin x + \cos x)(\sin^2 x - \sin x \cos x + \cos^2 x)}{\sin x + \cos x}
\]
\[
= 1 - \sin x \cos x = 1 - \frac{1}{2} \sin 2x.
\]

### Example 3.28

Find \( x \) such that \( -\pi \leq x \leq \pi \) and \( \cos 2x = \sin x \)

**Solution:**

We have \( \cos 2x = \sin x \) which gives
\[
1 - 2\sin^2 x = \sin x \Rightarrow 2\sin^2 x + \sin x - 1 = 0.
\]

The roots of the equation are
\[
\sin x = \frac{-1 \pm 3}{4} = -1 \text{ or } \frac{1}{2}
\]

Now, \( \sin x = \frac{1}{2} \Rightarrow x = \frac{\pi}{6}, \frac{5\pi}{6} \)

Also \( \sin x = -1 \Rightarrow x = -\frac{\pi}{2} \)

Thus, \( x = -\frac{\pi}{2}, \frac{\pi}{6}, \frac{5\pi}{6} \)

### Example 3.29

Find the values of (i) \( \sin 18^\circ \) (ii) \( \cos 18^\circ \) (iii) \( \sin 72^\circ \) (iv) \( \cos 36^\circ \) (v) \( \sin 54^\circ \)

**Solution:**

(i) Let \( \theta = 18^\circ \). Then \( 5\theta = 90^\circ \)

\[
3\theta + 2\theta = 90^\circ \Rightarrow 2\theta = 90^\circ - 3\theta
\]
\[
\sin 2\theta = \sin(90^\circ - 3\theta) = \cos 3\theta
\]
\[
2\sin \theta \cos \theta = 4\cos^3 \theta - 3\cos \theta
\]

Since \( \cos \theta = \cos 18^\circ \neq 0 \), we have
\[
2\sin \theta = 4\cos^2 \theta - 3 = 4(1 - \sin^2 \theta) - 3
\]
\[
4\sin^2 \theta + 2\sin \theta - 1 = 0
\]
\[
\sin \theta = \frac{-2 \pm \sqrt{4 - 4(4)(-1)}}{2(4)} = \frac{-1 \pm \sqrt{5}}{4}
\]

Thus, \( \sin 18^\circ = \frac{\sqrt{5} - 1}{4} \) (positive sign is taken. Why?)

\[
\cos 18^\circ = \sqrt{1 - \sin^2 18^\circ}
\]
\[
= \sqrt{1 - \left[\frac{\sqrt{5} - 1}{4}\right]^2} = \frac{1}{4}\sqrt{16 - (5 + 1 - 2\sqrt{5})} = \frac{1}{4}\sqrt{10 + 2\sqrt{5}}
\]
\[
\sin 72^\circ = \sin(90^\circ - 18^\circ) = \cos 18^\circ = \frac{1}{4}\sqrt{10 + 2\sqrt{5}}
\]
\[
\cos 36^\circ = 1 - 2\sin^2 18^\circ = 1 - 2\left[\frac{\sqrt{5} - 1}{4}\right]^2 = \frac{\sqrt{5} + 1}{4}
\]
\[
\sin 54^\circ = \sin(90^\circ - 36^\circ) = \cos 36^\circ = \frac{\sqrt{5} + 1}{4}.
\]

Observe that \( \sin 18^\circ = \cos 72^\circ \), \( \cos 18^\circ = \sin 72^\circ \) and \( \cos 36^\circ = \sin 54^\circ \)

### Example 3.30

If \( \tan \frac{\theta}{2} = \sqrt{\frac{1 - a}{1 + a}} \tan \frac{\phi}{2} \), then prove that \( \cos \phi = \frac{\cos \theta - a}{1 - a \cos \theta} \)

### Example 3.31

Find the value of \( \sqrt{3} \csc 20^\circ - \sec 20^\circ \)

**Solution:**

We have
\[
\sqrt{3} \csc 20^\circ - \sec 20^\circ = \frac{\sqrt{3}}{\sin 20^\circ} - \frac{1}{\cos 20^\circ} = 4\left[\frac{\frac{\sqrt{3}}{2} \cos 20^\circ - \frac{1}{2} \sin 20^\circ}{\sin 40^\circ}\right]
\]
\[
= 4\left[\frac{\sin 60^\circ \cos 20^\circ - \cos 60^\circ \sin 20^\circ}{\sin 40^\circ}\right] = 4.
\]

### Example 3.32

Prove that \( \cos A \cos 2A \cos 2^2 A \cos 2^3 A \ldots \cos 2^{n-1} A = \frac{\sin 2^n A}{2^n \sin A} \)

**Solution:**

\[
\text{L.H.S.} = \cos A \cos 2A \cos 2^2 A \cos 2^3 A \ldots \cos 2^{n-1} A
\]
\[
= \frac{1}{2\sin A} \cdot 2\sin A \cos A \cos 2A \cos 2^2 A \cos 2^3 A \ldots \cos 2^{n-1} A
\]
\[
= \frac{1}{2\sin A} \sin 2A \cos 2A \cos 2^2 A \cos 2^3 A \ldots \cos 2^{n-1} A
\]
\[
= \frac{1}{2^2 \sin A} \sin 4A \cos 2^2 A \cos 2^3 A \ldots \cos 2^{n-1} A
\]

Continuing the process, we get
\[
= \frac{\sin 2^n A}{2^n \sin A} = \text{R.H.S.}
\]

## Exercise 3.5

1. Find the value of \( \cos 2A \), \( A \) lies in the first quadrant, when
   (i) \( \cos A = \frac{15}{17} \) (ii) \( \sin A = \frac{4}{5} \) (iii) \( \tan A = \frac{16}{63} \).

2. If \( \theta \) is an acute angle, then find
   (i) \( \sin\left(\frac{\pi}{4} - \frac{\theta}{2}\right) \), when \( \sin \theta = \frac{1}{25} \).
   (ii) \( \cos\left(\frac{\pi}{4} + \frac{\theta}{2}\right) \), when \( \sin \theta = \frac{8}{9} \).

3. If \( \cos \theta = \frac{1}{2}\left(a + \frac{1}{a}\right) \), show that \( \cos 3\theta = \frac{1}{2}\left(a^3 + \frac{1}{a^3}\right) \).

4. Prove that \( \cos 5\theta = 16\cos^5 \theta - 20\cos^3 \theta + 5\cos \theta \).

5. Prove that \( \sin 4\alpha = 4\tan \alpha \frac{1 - \tan^2 \alpha}{(1 + \tan^2 \alpha)^2} \).

6. If \( A + B = 45^\circ \), show that \( (1 + \tan A)(1 + \tan B) = 2 \).

7. Prove that \( (1 + \tan 1^\circ)(1 + \tan 2^\circ)(1 + \tan 3^\circ)\ldots(1 + \tan 44^\circ) \) is a multiple of 4.

8. Prove that \( \tan\left(\frac{\pi}{4} + \theta\right) - \tan\left(\frac{\pi}{4} - \theta\right) = 2\tan 2\theta \).

9. Show that \( \cot\left(\frac{1}{2}^\circ\right) = \sqrt{2} + \sqrt{3} + \sqrt{4} + \sqrt{6} \).

10. Prove that \( (1 + \sec 2\theta)(1 + \sec 4\theta)\ldots(1 + \sec 2^n\theta) = \tan 2^n\theta \cot \theta \).

11. Prove that \( 32(\sqrt{3}) \sin \frac{\pi}{48} \cos \frac{\pi}{48} \cos \frac{\pi}{24} \cos \frac{\pi}{12} \cos \frac{\pi}{6} = 3 \).

### 3.5.3 Product to Sum and Sum to Product Identities

Some applications of trigonometric functions demand that a product of trigonometric functions be written as sum or difference of trigonometric functions. The sum and difference identities for the cosine and sine functions look amazingly like each other except for the sign in the middle. So, we tend to combine them to get nice identities. Thus, we use them to derive several identities that make it possible to rewrite a product as a sum or a sum as a product.

We know that

\[
\sin(A + B) = \sin A \cos B + \cos A \sin B \tag{3.1}
\]
\[
\sin(A - B) = \sin A \cos B - \cos A \sin B \tag{3.2}
\]
\[
\cos(A + B) = \cos A \cos B - \sin A \sin B \tag{3.3}
\]
\[
\cos(A - B) = \cos A \cos B + \sin A \sin B \tag{3.4}
\]

From the above identities, we can easily derive the following Product to Sum identities.

\[
\sin A \cos B = \frac{1}{2}[\sin(A + B) + \sin(A - B)] \tag{3.5}
\]
\[
\cos A \sin B = \frac{1}{2}[\sin(A + B) - \sin(A - B)] \tag{3.6}
\]
\[
\cos A \cos B = \frac{1}{2}[\cos(A + B) + \cos(A - B)] \tag{3.7}
\]
\[
\sin A \sin B = \frac{1}{2}[\cos(A - B) - \cos(A + B)] \tag{3.8}
\]

The above identities are very important whenever need arises to transform the product of sine and cosine into sum. This idea is very much useful in evaluation of some integrals.

To get Sum to Product identities, let us introduce the substitutions \( A + B = C \) and \( A - B = D \) or equivalently \( A = \frac{C + D}{2}, B = \frac{C - D}{2} \) in the product to sum identities (3.5) to (3.8). Then, we have the following Sum to Product identities

\[
\sin C + \sin D = 2\sin \frac{C + D}{2} \cos \frac{C - D}{2} \tag{3.9}
\]
\[
\sin C - \sin D = 2\cos \frac{C + D}{2} \sin \frac{C - D}{2} \tag{3.10}
\]
\[
\cos C + \cos D = 2\cos \frac{C + D}{2} \cos \frac{C - D}{2} \tag{3.11}
\]
\[
\cos C - \cos D = -2\sin \frac{C + D}{2} \sin \frac{C - D}{2} = 2\sin \frac{C + D}{2} \sin \frac{D - C}{2} \tag{3.12}
\]

**Identity 3.15:** Prove that \( \sin(60^\circ - A) \sin A \sin(60^\circ + A) = \frac{1}{4} \sin 3A \)

**Proof.**

\[
\sin(60^\circ - A) \sin A \sin(60^\circ + A) = \sin(60^\circ - A) \sin(60^\circ + A) \sin A
\]
\[
= \frac{1}{2}[\cos 2A - \cos 120^\circ] \sin A
\]
\[
= \frac{1}{2}\left[\cos 2A \sin A + \frac{1}{2} \sin A\right]
\]
\[
= \frac{1}{2}\left[\frac{1}{2} \sin 3A\right] = \frac{1}{4} \sin 3A
\]

Similarly we can prove the following two important identities

\[
\sin(60^\circ - A) \cos A \cos(60^\circ + A) = \frac{1}{4} \cos 3A
\]
\[
\sin(60^\circ - A) \tan A \tan(60^\circ + A) = \tan 3A
\]

### Example 3.33

Express each of the following product as a sum or difference

(i) \( \sin 40^\circ \cos 30^\circ \) (ii) \( \cos 110^\circ \sin 55^\circ \) (iii) \( \sin \frac{x}{2} \cos \frac{3x}{2} \)

**Solution:**

(i) We know that \( 2\sin A \cos B = \sin(A + B) + \sin(A - B) \)

Take \( A = 40^\circ \) and \( B = 30^\circ \). We get,
\[
2\sin 40^\circ \cos 30^\circ = \sin(40^\circ + 30^\circ) + \sin(40^\circ - 30^\circ) = \sin 70^\circ + \sin 10^\circ.
\]

Thus, \( \sin 40^\circ \cos 30^\circ = \frac{1}{2}[\sin 70^\circ + \sin 10^\circ]. \)

(ii) We know that \( 2\cos A \sin B = \sin(A + B) - \sin(A - B) \)

Take \( A = 110^\circ \) and \( B = 55^\circ \). We get,
\[
2\cos 110^\circ \sin 55^\circ = \sin(110^\circ + 55^\circ) - \sin(110^\circ - 55^\circ).
\]

Thus, \( \cos 110^\circ \sin 55^\circ = \frac{1}{2}[\sin 165^\circ - \sin 55^\circ] \)

(iii) We know that \( 2\sin A \cos B = \sin(A + B) + \sin(A - B) \)

Take \( A = \frac{x}{2} \) and \( B = \frac{3x}{2} \)

We get, \( 2\sin \frac{x}{2} \cos \frac{3x}{2} = \sin\left(\frac{x}{2} + \frac{3x}{2}\right) + \sin\left(\frac{x}{2} - \frac{3x}{2}\right) \)

Thus, \( \sin \frac{x}{2} \cos \frac{3x}{2} = \frac{1}{2}[\sin 2x - \sin x] \)

### Example 3.34

Express each of the following sum or difference as a product

(i) \( \sin 50^\circ + \sin 20^\circ \) (ii) \( \cos 60^\circ + \cos 20^\circ \) (iii) \( \cos \frac{3x}{2} - \cos \frac{9x}{2} \)

**Solution:**

(i) We know that \( \sin C + \sin D = 2\sin \frac{C + D}{2} \cos \frac{C - D}{2} \)

Take \( C = 50^\circ \) and \( D = 20^\circ \). We have
\[
\sin 50^\circ + \sin 20^\circ = 2\sin \frac{50^\circ + 20^\circ}{2} \cos \frac{50^\circ - 20^\circ}{2} = 2\sin 35^\circ \cos 15^\circ
\]

(ii) We know that \( \cos C + \cos D = 2\cos \frac{C + D}{2} \cos \frac{C - D}{2} \)

Take \( C = 60^\circ \) and \( D = 20^\circ \). We have
\[
\cos 60^\circ + \cos 20^\circ = 2\cos \frac{60^\circ + 20^\circ}{2} \cos \frac{60^\circ - 20^\circ}{2} = 2\cos 40^\circ \cos 20^\circ
\]

(iii) We know that \( \cos C - \cos D = 2\sin \frac{C + D}{2} \sin \frac{D - C}{2} \)

Take \( C = \frac{3x}{2} \) and \( D = \frac{9x}{2} \). We have
\[
\cos \frac{3x}{2} - \cos \frac{9x}{2} = 2\sin \frac{\frac{3x}{2} + \frac{9x}{2}}{2} \sin \frac{\frac{9x}{2} - \frac{3x}{2}}{2} = 2\sin 3x \sin \frac{3x}{2}.
\]

### Example 3.35

Find the value of \( \sin 34^\circ + \cos 64^\circ - \cos 4^\circ \).

**Solution:**

We have
\[
\sin 34^\circ + \cos 64^\circ - \cos 4^\circ = \sin 34^\circ - 2\sin\left(\frac{64^\circ + 4^\circ}{2}\right) \sin\left(\frac{64^\circ - 4^\circ}{2}\right)
\]
\[
= \sin 34^\circ - 2\sin 34^\circ \sin 30^\circ = 0.
\]

### Example 3.36

Show that \( \cos 36^\circ \cos 72^\circ \cos 108^\circ \cos 144^\circ = \frac{1}{16} \).

**Solution:**

\[
\text{L.H.S.} = \cos 36^\circ \cos(90^\circ - 18^\circ) \cos(90^\circ + 18^\circ) \cos(180^\circ - 36^\circ)
\]
\[
= \sin^2 18^\circ \cos^2 36^\circ
\]
\[
= \left(\frac{\sqrt{5} - 1}{4}\right)^2 \left(\frac{\sqrt{5} + 1}{4}\right)^2 = \frac{1}{16}.
\]

### Example 3.37

Simplify \( \frac{\sin 75^\circ - \sin 15^\circ}{\cos 75^\circ + \cos 15^\circ} \)

**Solution:**

We have
\[
\frac{\sin 75^\circ - \sin 15^\circ}{\cos 75^\circ + \cos 15^\circ} = \frac{2\cos\left(\frac{75^\circ + 15^\circ}{2}\right) \sin\left(\frac{75^\circ - 15^\circ}{2}\right)}{2\cos\left(\frac{75^\circ + 15^\circ}{2}\right) \cos\left(\frac{75^\circ - 15^\circ}{2}\right)}
\]
\[
= \frac{2\cos 45^\circ \sin 30^\circ}{2\cos 45^\circ \cos 30^\circ} = \tan 30^\circ = \frac{1}{\sqrt{3}}.
\]

Try to solve using \( \sin 75^\circ = \cos 15^\circ \) and \( \cos 75^\circ = \sin 15^\circ \)

### Example 3.38

Show that \( \cos 10^\circ \cos 30^\circ \cos 50^\circ \cos 70^\circ = \frac{3}{16} \).

**Solution:**

We know that \( \cos(60^\circ - A) \cos A \cos(60^\circ + A) = \frac{1}{4} \cos 3A \)

\[
\cos 10^\circ \cos 30^\circ \cos 50^\circ \cos 70^\circ = \cos 30^\circ [\cos 10^\circ \cos 50^\circ \cos 70^\circ]
\]
\[
= \cos 30^\circ [\cos(60^\circ - 10^\circ) \cos 10^\circ \cos(60^\circ + 10^\circ)]
\]
\[
= \frac{\sqrt{3}}{2} \left[\frac{1}{4} \cos 30^\circ\right] = \frac{\sqrt{3}}{2} \cdot \frac{1}{4} \cdot \frac{\sqrt{3}}{2} = \frac{3}{16}
\]

## Exercise 3.6

1. Express each of the following as a sum or difference
   (i) \( \sin 35^\circ \cos 28^\circ \) (ii) \( \sin 4x \cos 2x \) (iii) \( 2\sin 10\theta \cos 2\theta \) (iv) \( \cos 5\theta \cos 2\theta \) (v) \( \sin 5\theta \sin 4\theta \)

2. Express each of the following as a product
   (i) \( \sin 75^\circ - \sin 35^\circ \) (ii) \( \cos 65^\circ + \cos 15^\circ \) (iii) \( \sin 50^\circ + \sin 40^\circ \) (iv) \( \cos 35^\circ - \cos 75^\circ \)

3. Show that \( \sin 12^\circ \sin 48^\circ \sin 54^\circ = \frac{1}{8} \)

4. Show that \( \cos \frac{\pi}{15} \cos \frac{2\pi}{15} \cos \frac{3\pi}{15} \cos \frac{4\pi}{15} \cos \frac{5\pi}{15} \cos \frac{6\pi}{15} \cos \frac{7\pi}{15} = \frac{1}{128} \).

5. Show that \( \frac{\sin 8x \cos x - \sin 6x \cos 3x}{\cos 2x \cos x - \sin 3x \sin 4x} = \tan 2x \).

6. Show that \( \frac{(\cos \theta - \cos 3\theta)(\sin 8\theta + \sin 2\theta)}{(\sin 5\theta - \sin \theta)(\cos 4\theta - \cos 6\theta)} = 1 \).

7. Prove that \( \sin x + \sin 2x + \sin 3x = \sin 2x(1 + 2\cos x) \)

8. Prove that \( \frac{\sin 4x + \sin 2x}{\cos 4x + \cos 2x} = \tan 3x \).

9. Prove that \( 1 + \cos 2x + \cos 4x + \cos 6x = 4\cos x \cos 2x \cos 3x \).

10. Prove that \( \sin \frac{\theta}{2} \sin \frac{7\theta}{2} + \sin \frac{3\theta}{2} \sin \frac{11\theta}{2} = \sin 2\theta \sin 5\theta \).

11. Prove that \( \cos(30^\circ - A) \cos(30^\circ + A) + \cos(45^\circ - A) \cos(45^\circ + A) = \cos 2A + \frac{1}{4} \).

12. Prove that \( \frac{\sin x + \sin 3x + \sin 5x + \sin 7x}{\cos x + \cos 3x + \cos 5x + \cos 7x} = \tan 4x \).

13. Prove that \( \frac{\sin(4A - 2B) + \sin(4B - 2A)}{\cos(4A - 2B) + \cos(4B - 2A)} = \tan(A + B) \).

14. Show that \( \cot(A + 15^\circ) - \tan(A - 15^\circ) = \frac{4\cos 2A}{1 + 2\sin 2A} \).

### 3.5.4 Conditional Trigonometric Identities

We know that trigonometric identities are true for all admissible values of the angle involved. There are some trigonometric identities which satisfy the given additional conditions. Such identities are called conditional trigonometric identities.

In this section, we shall make use of the relations obtained in the earlier sections to establish some conditional identities based on some relationship.

### Example 3.39

If \( A + B + C = \pi \), prove the following

(i) \( \cos A + \cos B + \cos C = 1 + 4\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \)

(ii) \( \sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \leq \frac{1}{8} \)

(iii) \( 1 < \cos A + \cos B + \cos C \leq \frac{3}{2} \)

**Solution:**

(i) \( \cos A + \cos B + \cos C = 2\cos \frac{A + B}{2} \cos \frac{A - B}{2} + \cos C \)
\[
= 2\cos \left(\frac{\pi}{2} - \frac{C}{2}\right) \cos \frac{A - B}{2} + \cos C \quad (A + B + C = \pi \Rightarrow \frac{A + B}{2} = \frac{\pi}{2} - \frac{C}{2})
\]
\[
= 2\sin \frac{C}{2} \cos \frac{A - B}{2} + 1 - 2\sin^2 \frac{C}{2}
\]
\[
= 1 + 2\sin \frac{C}{2} \left( \cos \frac{A - B}{2} - \sin \frac{C}{2} \right)
\]
\[
= 1 + 2\sin \frac{C}{2} \left( \cos \frac{A - B}{2} - \cos \left(\frac{\pi}{2} - \frac{C}{2}\right) \right)
\]
\[
= 1 + 2\sin \frac{C}{2} \left( \cos \frac{A - B}{2} - \cos \frac{A + B}{2} \right)
\]
\[
= 1 + 4\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2}
\]

(ii) Let \( u = \sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} = -\frac{1}{2} \left( \cos \frac{A + B}{2} - \cos \frac{A - B}{2} \right) \sin \frac{C}{2} \)
\[
= -\frac{1}{2} \left( \cos \frac{A + B}{2} - \cos \frac{A - B}{2} \right) \cos \frac{A + B}{2}
\]

This gives \( \cos^2 \frac{A + B}{2} - \cos \frac{A - B}{2} \cos \frac{A + B}{2} + 2u = 0 \), which is a quadratic in \( \cos \frac{A + B}{2} \).

Since \( \cos \frac{A + B}{2} \) is real number, the above equation has a solution.

Thus, the discriminant \( b^2 - 4ac \geq 0 \), which gives
\[
\cos^2 \frac{A - B}{2} - 8u \geq 0 \Rightarrow u \leq \frac{1}{8} \cos^2 \frac{A - B}{2} \leq \frac{1}{8}
\]

Hence, \( \sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \leq \frac{1}{8} \)

(iii) From (i) and (ii), we have \( \cos A + \cos B + \cos C > 1 \) and
\[
\cos A + \cos B + \cos C \leq 1 + 4 \times \frac{1}{8}
\]

Thus, we get \( 1 < \cos A + \cos B + \cos C \leq \frac{3}{2} \).

(Note: \( \sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} > 0 \), if \( A + B + C = \pi \))

### Example 3.40

Prove that
\[
\sin \frac{A}{2} + \sin \frac{B}{2} + \sin \frac{C}{2} = 1 + 4\sin \frac{\pi - A}{4} \sin \frac{\pi - B}{4} \sin \frac{\pi - C}{4},
\]
if \( A + B + C = \pi \)

**Solution:**

L.H.S. \( = \cos\left(\frac{\pi}{2} - \frac{A}{2}\right) + \cos\left(\frac{\pi}{2} - \frac{B}{2}\right) + \cos\left(\frac{\pi}{2} - \frac{C}{2}\right) \)
\[
= \left[2\cos \frac{\frac{\pi}{2} - \frac{A}{2} + \frac{\pi}{2} - \frac{B}{2}}{2} \cos \frac{\frac{\pi}{2} - \frac{A}{2} - \left(\frac{\pi}{2} - \frac{B}{2}\right)}{2}\right] + \left[1 - 2\sin^2 \left(\frac{\pi}{4} - \frac{C}{4}\right)\right]
\]
\[
= 1 + 2\sin \left(\frac{\pi}{4} - \frac{C}{4}\right) \cos \frac{B - A}{4} - 2\sin^2 \left(\frac{\pi}{4} - \frac{C}{4}\right)
\]
\[
= 1 + 2\sin \left(\frac{\pi}{4} - \frac{C}{4}\right) \left[ \cos \frac{B - A}{4} - \sin \left(\frac{\pi}{4} - \frac{C}{4}\right) \right]
\]
\[
= 1 + 2\sin \left(\frac{\pi}{4} - \frac{C}{4}\right) \left[ \cos \frac{B - A}{4} - \sin \frac{A + B}{4} \right]
\]
\[
= 1 + 2\sin \left(\frac{\pi}{4} - \frac{C}{4}\right) \left[ \cos \frac{B - A}{4} - \cos \left(\frac{\pi}{2} - \frac{A + B}{4}\right) \right]
\]
\[
= 1 + 4\sin \frac{\pi - A}{4} \sin \frac{\pi - B}{4} \sin \frac{\pi - C}{4}
\]

### Example 3.41

If \( A + B + C = \pi \), prove that \( \cos^2 A + \cos^2 B + \cos^2 C = 1 - 2\cos A \cos B \cos C \).

**Solution:**

\[
\cos^2 A + \cos^2 B + \cos^2 C = \frac{1}{2}[2\cos^2 A + 2\cos^2 B + 2\cos^2 C]
\]
\[
= \frac{1}{2}[(1 + \cos 2A) + (1 + \cos 2B) + (1 + \cos 2C)]
\]
\[
= \frac{3}{2} + \frac{1}{2}[(\cos 2A + \cos 2B) + \cos 2C]
\]
\[
= \frac{3}{2} + \frac{1}{2}[2\cos(A + B)\cos(A - B) + (2\cos^2 C - 1)]
\]
\[
= \frac{3}{2} + \frac{1}{2}[-2\cos C \cos(A - B) + 2\cos^2 C - 1] \quad (A + B = \pi - C)
\]
\[
= 1 + \frac{1}{2}[-2\cos C(\cos(A - B) - \cos C)]
\]
\[
= 1 - \cos C[\cos(A - B) - \cos C]
\]
\[
= 1 - \cos C[\cos(A - B) + \cos(A + B)]
\]
\[
= 1 - \cos C[2\cos A \cos B]
\]
\[
= 1 - 2\cos A \cos B \cos C
\]

## Exercise 3.7

1. If \( A + B + C = 180^\circ \) prove that
   (i) \( \sin 2A + \sin 2B + \sin 2C = 4\sin A \sin B \sin C \)
   (ii) \( \cos A + \cos B - \cos C = -1 + 4\cos \frac{A}{2} \cos \frac{B}{2} \sin \frac{C}{2} \)
   (iii) \( \sin^2 A + \sin^2 B + \sin^2 C = 2 + 2\cos A \cos B \cos C \)
   (iv) \( \sin^2 A + \sin^2 B - \sin^2 C = 2\sin A \sin B \cos C \)
   (v) \( \tan \frac{A}{2} \tan \frac{B}{2} + \tan \frac{B}{2} \tan \frac{C}{2} + \tan \frac{A}{2} \tan \frac{B}{2} = 1 \)
   (vi) \( \sin A + \sin B + \sin C = 4\cos \frac{A}{2} \cos \frac{B}{2} \cos \frac{C}{2} \)
   (vii) \( \sin(B + C - A) + \sin(C + A - B) + \sin(A + B - C) = 4\sin A \sin B \sin C \).

2. If \( A + B + C = 2s \), then prove that \( \sin(s - A) \sin(s - B) + \sin s \sin(s - C) = \sin A \sin B \).

3. If \( x + y + z = xyz \), then prove that \( \frac{2x}{1 - x^2} + \frac{2y}{1 - y^2} + \frac{2z}{1 - z^2} = \frac{2x}{1 - x^2} \cdot \frac{2y}{1 - y^2} \cdot \frac{2z}{1 - z^2} \).

4. If \( A + B + C = \frac{\pi}{2} \), prove the following
   (i) \( \sin 2A + \sin 2B + \sin 2C = 4\cos A \cos B \cos C \)
   (ii) \( \cos 2A + \cos 2B + \cos 2C = 1 + 4\sin A \sin B \sin C \).

5. If \( \triangle ABC \) is a right triangle and if \( \angle A = \frac{\pi}{2} \), then prove that
   (i) \( \cos^2 B + \cos^2 C = 1 \)
   (ii) \( \sin^2 B + \sin^2 C = 1 \)
   (iii) \( \cos B - \cos C = -1 + 2\sqrt{2}\cos \frac{B}{2} \sin \frac{C}{2} \).

## 3.6 Trigonometric equations

The equations containing trigonometric functions of unknown angles are known as trigonometric equations. A solution of trigonometric equation is the value of unknown angle that satisfies the equation. Unless the domain is restricted, the trigonometric equations have infinitely many solutions, a fact due to the periodicity of trigonometric functions. Some of the equations may not have a solution at all.

For example, the equation \( \sin \theta = \frac{3}{2} \), does not have solution, since \( -1 \leq \sin \theta \leq 1 \).

The equation \( \sin \theta = 0 \) has infinitely many solutions given by \( \theta = \pm \pi, \pm 2\pi, \pm 3\pi, \ldots \) and note that these solutions occur periodically.

### General Solution

The solution of a trigonometric equation giving all the admissible values obtained with the help of periodicity of a trigonometric function is called the general solution of the equation.

### Principal Solution

The smallest numerical value of unknown angle satisfying the equation in the interval \( [0, 2\pi] \) (or \( [-\pi, \pi] \)) is called a principal solution. We shall take the interval \( [-\pi, \pi] \) for defining the principal solution. Further, in this interval we may have two solutions. Even though both are valid solutions, we take only the numerically smaller one. This helps us to define the principal domain of the trigonometric functions in order to have their inverses.

Principal value of sine function lies in the interval \( \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \) and hence lies in I quadrant or IV quadrant. Principal value of cosine function is in \( [0, \pi] \) and hence in I quadrant or II quadrant. Principal value of tangent function is in \( \left(-\frac{\pi}{2}, \frac{\pi}{2}\right) \) and hence in I quadrant or IV quadrant.

(i) Trigonometric equations are different from trigonometric identities, since trigonometric identities are true for all admissible values of unknown angle \( \theta \). But trigonometric equations are valid only for particular values of unknown angle.

(ii) There is no general method for solving trigonometric equations. However, one may notice that some equations may be factorisable; some equations may be expressed in terms of single function; some equations may be squared.

(iii) To find solutions to trigonometric equations, sometimes one may go for the technique of squaring both sides. One has to take care as it can also produce false solutions (extraneous solutions).

For example, to find solution for \( \sin x - \cos x = 1 \) in \( 0 \leq x < 360^\circ \), we do squaring on both sides to get \( (\sin x - 1)^2 = \cos^2 x \), which gives \( 2\sin x(\sin x - 1) = 0 \). So, we get \( x = 0, \frac{\pi}{2}, \pi \). Clearly \( x = 0 \) is a false solution. Thus, we have to check for correct solutions, in the squaring process.

(iv) Mostly we write the solutions of trigonometric equations in radians.

Now, we find the solutions to different forms of trigonometrical equations.

(i) To solve an equation of the form \( \sin \theta = k \) \( (-1 \leq k \leq 1) \)

Let \( \alpha \) be the numerically smallest angle such that \( \sin \alpha = k \). Thus,

\[
\sin \theta = \sin \alpha
\]
\[
\sin \theta - \sin \alpha = 0
\]
\[
2\cos \frac{\theta + \alpha}{2} \sin \frac{\theta - \alpha}{2} = 0
\]

which gives either
\[
\cos \frac{\theta + \alpha}{2} = 0 \Rightarrow \frac{\theta + \alpha}{2} = (2n + 1)\frac{\pi}{2} \Rightarrow \theta = (2n + 1)\pi - \alpha
\]
or
\[
\sin \frac{\theta - \alpha}{2} = 0 \Rightarrow \frac{\theta - \alpha}{2} = n\pi \Rightarrow \theta = 2n\pi + \alpha
\]

Thus,
\[
\sin \theta = \sin \alpha \Rightarrow \theta = n\pi + (-1)^n \alpha, n \in \mathbb{Z}. \tag{3.13}
\]

(ii) To solve an equation of the form \( \cos \theta = k \) \( (-1 \leq k \leq 1) \):

Let \( \alpha \) be the numerically smallest angle such that \( \cos \alpha = k \). Thus,

\[
\cos \theta = \cos \alpha
\]
\[
\cos \theta - \cos \alpha = 0
\]
\[
-2\sin \frac{\theta + \alpha}{2} \sin \frac{\theta - \alpha}{2} = 0
\]

Either
\[
\sin \frac{\theta + \alpha}{2} = 0 \Rightarrow \frac{\theta + \alpha}{2} = n\pi \Rightarrow \theta = 2n\pi - \alpha
\]
or
\[
\sin \frac{\theta - \alpha}{2} = 0 \Rightarrow \frac{\theta - \alpha}{2} = n\pi \Rightarrow \theta = 2n\pi + \alpha
\]

Combining (i) and (ii), we have
\[
\cos \theta = \cos \alpha \Rightarrow \theta = 2n\pi \pm \alpha, n \in \mathbb{Z}. \tag{3.14}
\]

(iii) To solve an equation of the form \( \tan \theta = k \) \( (-\infty < k < \infty) \):

Let \( \alpha \) be the numerically smallest angle such that \( \tan \alpha = k \). Thus,

\[
\tan \theta = \tan \alpha \Rightarrow \frac{\sin \theta}{\cos \theta} = \frac{\sin \alpha}{\cos \alpha}
\]
\[
\sin \theta \cos \alpha - \cos \theta \sin \alpha = 0
\]
\[
\sin(\theta - \alpha) = 0 \Rightarrow \theta - \alpha = n\pi
\]
\[
\theta = n\pi + \alpha, n \in \mathbb{Z}
\]

Thus,
\[
\tan \theta = \tan \alpha \Rightarrow \theta = n\pi + \alpha, n \in \mathbb{Z} \tag{3.15}
\]

(iv) To solve an equation of the form \( a\cos \theta + b\sin \theta = c \):

Take \( a = r\cos \alpha, b = r\sin \alpha \). Then \( r = \sqrt{a^2 + b^2}; \tan \alpha = \frac{b}{a}, a \neq 0 \)

\[
a\cos \theta + b\sin \theta = c \Rightarrow r\cos \alpha \cos \theta + r\sin \alpha \sin \theta = c
\]
\[
r\cos(\theta - \alpha) = c
\]
\[
\cos(\theta - \alpha) = \frac{c}{r} = \frac{c}{\sqrt{a^2 + b^2}} = \cos \phi \ (\text{say})
\]
\[
\theta - \alpha = 2n\pi \pm \phi, n \in \mathbb{Z}
\]
\[
\theta = 2n\pi + \alpha \pm \phi, n \in \mathbb{Z}.
\]

The above method can be used only when \( c \leq \sqrt{a^2 + b^2} \). If \( c > \sqrt{a^2 + b^2} \), then the equation \( a\cos \theta + b\sin \theta = c \) has no solution.

Now we summarise the general solution of trigonometric equations.

| Trigonometric Equation | General Solution |
|------------------------|------------------|
| \( \sin \theta = 0 \) | \( \theta = n\pi; n \in \mathbb{Z} \) |
| \( \cos \theta = 0 \) | \( \theta = (2n + 1)\frac{\pi}{2}; n \in \mathbb{Z} \) |
| \( \tan \theta = 0 \) | \( \theta = n\pi; n \in \mathbb{Z} \) |
| \( \sin \theta = \sin \alpha \), where \( \alpha \in [-\frac{\pi}{2}, \frac{\pi}{2}] \) | \( \theta = n\pi + (-1)^n \alpha, n \in \mathbb{Z} \) |
| \( \cos \theta = \cos \alpha \), where \( \alpha \in [0, \pi] \) | \( \theta = 2n\pi \pm \alpha, n \in \mathbb{Z} \) |
| \( \tan \theta = \tan \alpha \), where \( \alpha \in (-\frac{\pi}{2}, \frac{\pi}{2}) \) | \( \theta = n\pi + \alpha, n \in \mathbb{Z} \) |

### Example 3.42

Find the principal solution of
(i) \( \sin \theta = \frac{1}{2} \) (ii) \( \sin \theta = -\frac{\sqrt{3}}{2} \) (iii) \( \csc \theta = -2 \) (iv) \( \cos \theta = \frac{1}{2} \)

**Solution:**

(i) \( \sin \theta = \frac{1}{2} > 0 \) so principal value lies in the I quadrant.
\( \sin \theta = \frac{1}{2} = \sin \frac{\pi}{6} \)
Thus, \( \theta = \frac{\pi}{6} \) is the principal solution.

(ii) \( \sin \theta = -\frac{\sqrt{3}}{2} \)

We know that principal value of \( \sin \theta \) lies in \( \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \).

Since, \( \sin \theta = -\frac{\sqrt{3}}{2} < 0 \), the principal value of \( \sin \theta \) lies in the IV quadrant.

\[
\sin \theta = -\frac{\sqrt{3}}{2} = -\sin\left(\frac{\pi}{3}\right) = \sin\left(-\frac{\pi}{3}\right).
\]

Hence, \( \theta = -\frac{\pi}{3} \) is the principal solution.

(iii) \( \csc \theta = -2 \Rightarrow \frac{1}{\sin \theta} = -2 \Rightarrow \sin \theta = -\frac{1}{2} \)

Since \( \sin \theta = -\frac{1}{2} < 0 \), the principal value of \( \sin \theta \) lies in the IV quadrant.

\[
\sin \theta = -\frac{1}{2} = -\sin \frac{\pi}{6} = \sin\left(-\frac{\pi}{6}\right)
\]

Thus, \( \theta = -\frac{\pi}{6} \) is the principal solution.

(iv) \( \cos \theta = \frac{1}{2} \)

Principal value of \( \cos \theta \) lies in the I and II quadrant.

Since \( \cos \theta = \frac{1}{2} > 0 \), the principal value of \( \cos \theta \) lies in the interval \( \left[0, \frac{\pi}{2}\right] \).

\[
\cos \theta = \frac{1}{2} = \cos \frac{\pi}{3}
\]

Thus, \( \theta = \frac{\pi}{3} \) is the principal solution.

### Example 3.43

Find the general solution of \( \sin \theta = -\frac{\sqrt{3}}{2} \)

**Solution:**

The general solution of \( \sin \theta = \sin \alpha, \alpha \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \), is \( \theta = n\pi + (-1)^n \alpha, n \in \mathbb{Z} \)

\[
\sin \theta = -\frac{\sqrt{3}}{2} = \sin\left(-\frac{\pi}{3}\right),
\]

Thus the general solution is
\[
\theta = n\pi + (-1)^n \left(-\frac{\pi}{3}\right) = n\pi + (-1)^{n+1} \left(\frac{\pi}{3}\right); n \in \mathbb{Z} \quad \dots \text{(i)}
\]

In arriving at the above general solution, we took the principal value as \( -\left(\frac{\pi}{3}\right) \) with our convention that principal value is the numerically smallest one in the interval \( [-\pi, \pi] \). Now through this example, we shall justify that the principal value may also be taken in \( [0, 2\pi] \), as we mentioned in the definition of principle solution. If we take the principal solution in the interval \( [0, 2\pi] \), then the principal solution is \( \theta = \frac{4\pi}{3} \) and the general solution is

\[
\theta = n\pi + (-1)^n \left(\frac{4\pi}{3}\right), n \in \mathbb{Z}, \frac{4\pi}{3} \in [0, 2\pi] \quad \dots \text{(ii)}
\]

From (ii), for \( n = 0, -1, 1, -2, 2, \ldots \) the corresponding solutions are \( \frac{4\pi}{3}, \frac{-7\pi}{3}, \frac{-\pi}{3}, \frac{-2\pi}{3}, \frac{10\pi}{3}, \ldots \)

From (i), for \( n = 0, -1, 1, -2, 2, \ldots \) the corresponding solutions are \( \frac{-\pi}{3}, \frac{-2\pi}{3}, \frac{4\pi}{3}, \frac{-7\pi}{3}, \frac{5\pi}{3}, \ldots \)

In both the cases, we get the same set of solutions, but in different order. Thus, we have justified that the principal solution can be taken either in \( [0, 2\pi] \) or in \( [-\pi, \pi] \).

### Example 3.44

Find the general solution of
(i) \( \sec \theta = -2 \) (ii) \( \tan \theta = \sqrt{3} \)

**Solution:**

(i) \( \sec \theta = -2 \Rightarrow \cos \theta = -\frac{1}{2} \)

We know that the general solution of \( \cos \theta = \cos \alpha, \alpha \in [0, \pi] \), is \( \theta = 2n\pi \pm \alpha, n \in \mathbb{Z} \)

Let us find \( \alpha \in [0, \pi] \) such that \( \cos \alpha = -\frac{1}{2} = \cos\left(\pi - \frac{\pi}{3}\right) = \cos \frac{2\pi}{3} \)

So, \( \alpha = \frac{2\pi}{3} \)

Thus, the general solution is \( \theta = 2n\pi \pm \frac{2\pi}{3}, n \in \mathbb{Z} \).

(ii) \( \tan \theta = \sqrt{3} = \tan \frac{\pi}{3} \)

We know that the general solution of \( \tan \theta = \tan \alpha, \alpha \in \left(-\frac{\pi}{2}, \frac{\pi}{2}\right) \) is \( \theta = n\pi + \alpha, n \in \mathbb{Z} \)

Thus, \( \theta = n\pi + \frac{\pi}{3}, n \in \mathbb{Z} \) is the general solution.

### Example 3.45

Solve \( 3\cos^2 \theta = \sin^2 \theta \)

**Solution:**

\[
3\cos^2 \theta = 1 - \cos^2 \theta \Rightarrow \cos^2 \theta = \frac{1}{4}
\]
\[
\frac{\cos 2\theta + 1}{2} = \frac{1}{4} \Rightarrow \cos 2\theta = -\frac{1}{2} = \cos\left(\pi - \frac{\pi}{3}\right) = \cos\left(\frac{2\pi}{3}\right)
\]
\[
2\theta = 2n\pi \pm \frac{2\pi}{3}, n \in \mathbb{Z} \Rightarrow \theta = n\pi \pm \frac{\pi}{3}, n \in \mathbb{Z}.
\]

Try to solve by writing \( \tan^2 \theta = 3 \).

### Example 3.46

Solve \( \sin x + \sin 5x = \sin 3x \)

**Solution:**

\[
\sin x + \sin 5x = \sin 3x \Rightarrow 2\sin 3x \cos 2x = \sin 3x
\]
\[
\sin 3x(2\cos 2x - 1) = 0
\]

Thus, either \( \sin 3x = 0 \) (or) \( \cos 2x = \frac{1}{2} \)

If \( \sin 3x = 0 \), then \( 3x = n\pi \Rightarrow x = \frac{n\pi}{3}, n \in \mathbb{Z} \) \dots (i)

If \( \cos 2x = \frac{1}{2} \Rightarrow \cos 2x = \cos \frac{\pi}{3} \) \dots (ii)
\[
2x = 2n\pi \pm \frac{\pi}{3} \Rightarrow x = n\pi \pm \frac{\pi}{6}, n \in \mathbb{Z}
\]

From (i) and (ii), we have the general solution \( x = \frac{n\pi}{3} \) (or) \( x = n\pi \pm \frac{\pi}{6}, n \in \mathbb{Z} \).

### Example 3.47

Solve \( \cos x + \sin x = \cos 2x + \sin 2x \)

**Solution:**

\[
\cos x + \sin x = \cos 2x + \sin 2x \Rightarrow \cos x - \cos 2x = \sin 2x - \sin x
\]
\[
2\sin \left(\frac{x + 2x}{2}\right) \sin \left(\frac{2x - x}{2}\right) = 2\cos \left(\frac{2x + x}{2}\right) \sin \left(\frac{2x - x}{2}\right)
\]
\[
2\sin \left(\frac{3x}{2}\right) \sin \left(\frac{x}{2}\right) = 2\cos \left(\frac{3x}{2}\right) \sin \left(\frac{x}{2}\right)
\]
\[
\sin \left(\frac{x}{2}\right) \left[\sin \left(\frac{3x}{2}\right) - \cos \left(\frac{3x}{2}\right)\right] = 0
\]

Thus, either \( \sin \left(\frac{x}{2}\right) = 0 \) (or) \( \sin \left(\frac{3x}{2}\right) - \cos \left(\frac{3x}{2}\right) = 0 \)

For \( \sin \left(\frac{x}{2}\right) = 0 \), \( \frac{x}{2} = n\pi \Rightarrow x = 2n\pi, n \in \mathbb{Z} \)

For \( \sin \left(\frac{3x}{2}\right) - \cos \left(\frac{3x}{2}\right) = 0 \), \( \tan \frac{3x}{2} = 1 \Rightarrow \frac{3x}{2} = n\pi + \frac{\pi}{4} \Rightarrow x = \frac{2n\pi}{3} + \frac{\pi}{6}, n \in \mathbb{Z} \)

Thus, the general solution is \( x = 2n\pi \) (or) \( x = \frac{2n\pi}{3} + \frac{\pi}{6}, n \in \mathbb{Z} \).

(If \( \sin \theta = \cos \theta \), then \( \theta \neq (2n + 1)\frac{\pi}{2}, n \in \mathbb{Z} \). So, we have \( \frac{\sin \theta}{\cos \theta} = 1 \))

### Example 3.48

Solve the equation \( \sin 9\theta = \sin \theta \)

**Solution:**

\[
\sin 9\theta = \sin \theta \Rightarrow \sin 9\theta - \sin \theta = 0
\]
\[
2\cos 5\theta \sin 4\theta = 0
\]

Either \( \cos 5\theta = 0 \) (or) \( \sin 4\theta = 0 \)

When \( \cos 5\theta = 0 \Rightarrow 5\theta = (2n + 1)\frac{\pi}{2} \Rightarrow \theta = (2n + 1)\frac{\pi}{10}, n \in \mathbb{Z} \)

When \( \sin 4\theta = 0 \Rightarrow 4\theta = n\pi \Rightarrow \theta = \frac{n\pi}{4}, n \in \mathbb{Z} \)

Thus, the general solution of the given equation is \( \theta = (2n + 1)\frac{\pi}{10}, \theta = \frac{n\pi}{4}, n \in \mathbb{Z} \).

### Example 3.49

Solve \( \tan 2x = -\cot\left(x + \frac{\pi}{3}\right) \)

**Solution:**

\[
\tan 2x = -\cot\left(x + \frac{\pi}{3}\right) = \tan\left(\frac{\pi}{2} + x + \frac{\pi}{3}\right) = \tan\left(\frac{5\pi}{6} + x\right)
\]
\[
2x = n\pi + \frac{5\pi}{6} + x, n \in \mathbb{Z} \Rightarrow x = n\pi + \frac{5\pi}{6}, n \in \mathbb{Z}.
\]

### Example 3.50

Solve \( \sin x - 3\sin 2x + \sin 3x = \cos x - 3\cos 2x + \cos 3x \)

**Solution:**

\[
\sin x - 3\sin 2x + \sin 3x = \cos x - 3\cos 2x + \cos 3x
\]
\[
\sin 3x + \sin x - 3\sin 2x = \cos 3x + \cos x - 3\cos 2x
\]
\[
2\sin 2x \cos x - 3\sin 2x = 2\cos 2x \cos x - 3\cos 2x
\]
\[
(\sin 2x - \cos 2x)(2\cos x - 3) = 0
\]

Then, \( \sin 2x - \cos 2x = 0 \) since \( 2\cos x - 3 \neq 0 \)

\[
\sin 2x = \cos 2x \Rightarrow \tan 2x = 1 \Rightarrow x = \frac{n\pi}{2} + \frac{\pi}{8}, n \in \mathbb{Z}.
\]

### Example 3.51

Solve \( \sin x + \cos x = 1 + \sin x \cos x \)

**Solution:**

Let \( \sin x + \cos x = t \)
\[
\Rightarrow 1 + 2\sin x \cos x = t^2 \Rightarrow \sin x \cos x = \frac{t^2 - 1}{2}
\]

Thus, the given equation becomes
\[
t = 1 + \frac{t^2 - 1}{2} \Rightarrow t^2 - 2t + 1 = 0 \Rightarrow t = 1
\]

Hence, \( \sin x + \cos x = 1 \)

\[
\sqrt{2}\left(\frac{1}{\sqrt{2}} \sin x + \frac{1}{\sqrt{2}} \cos x\right) = 1
\]
\[
\sqrt{2} \cos\left(\frac{\pi}{4} - x\right) = 1 \Rightarrow \cos\left(\frac{\pi}{4} - x\right) = \frac{1}{\sqrt{2}}
\]

Thus, we have \( x - \frac{\pi}{4} = \pm \frac{\pi}{4} + 2n\pi, n \in \mathbb{Z} \)

\[
x = \frac{\pi}{2} + 2n\pi \text{ or } x = 2n\pi, n \in \mathbb{Z}.
\]

### Example 3.52

Solve \( 2\sin^2 x + \sin^2 2x = 2 \)

**Solution:**

\[
2\sin^2 x + \sin^2 2x = 2 \Rightarrow 2\sin^2 x + (2\sin x \cos x)^2 = 2
\]
\[
2\sin^2 x + 4\sin^2 x \cos^2 x = 2
\]
\[
2\sin^2 x + 4\sin^2 x(1 - \sin^2 x) = 2
\]
\[
2\sin^2 x + 4\sin^2 x - 4\sin^4 x = 2
\]
\[
6\sin^2 x - 4\sin^4 x - 2 = 0
\]
\[
4\sin^4 x - 6\sin^2 x + 2 = 0
\]
\[
2\sin^4 x - 3\sin^2 x + 1 = 0
\]
\[
(2\sin^2 x - 1)(\sin^2 x - 1) = 0
\]

Thus, either \( \sin^2 x = \frac{1}{2} \) or \( \sin^2 x = 1 \)

If \( \sin^2 x = \frac{1}{2} \), \( \sin x = \pm \frac{1}{\sqrt{2}} \Rightarrow x = n\pi \pm \frac{\pi}{4}, n \in \mathbb{Z} \)

If \( \sin^2 x = 1 \), \( \sin x = \pm 1 \Rightarrow x = \frac{(2n + 1)\pi}{2}, n \in \mathbb{Z} \)

Thus the solution is \( x = (2n + 1)\frac{\pi}{2}, x = n\pi \pm \frac{\pi}{4}, n \in \mathbb{Z} \).

### Example 3.53

Prove that for any \( a \) and \( b \), \( -\sqrt{a^2 + b^2} \leq a\sin \theta + b\cos \theta \leq \sqrt{a^2 + b^2} \)

**Solution:**

\[
a\sin \theta + b\cos \theta = \sqrt{a^2 + b^2} \left[\frac{a}{\sqrt{a^2 + b^2}} \sin \theta + \frac{b}{\sqrt{a^2 + b^2}} \cos \theta\right]
\]
\[
= \sqrt{a^2 + b^2} [\cos \alpha \sin \theta + \sin \alpha \cos \theta]
\]
where \( \cos \alpha = \frac{a}{\sqrt{a^2 + b^2}}, \sin \alpha = \frac{b}{\sqrt{a^2 + b^2}} \)
\[
= \sqrt{a^2 + b^2} \sin(\alpha + \theta)
\]

Thus, \( |a\sin \theta + b\cos \theta| \leq \sqrt{a^2 + b^2} \)

Hence, \( -\sqrt{a^2 + b^2} \leq a\sin \theta + b\cos \theta \leq \sqrt{a^2 + b^2} \).

### Example 3.54

Solve \( \sqrt{3}\sin \theta - \cos \theta = \sqrt{2} \)

**Solution:**

\( \sqrt{3}\sin \theta - \cos \theta = \sqrt{2} \)

Here \( a = -1; b = \sqrt{3}; c = \sqrt{2}; r = \sqrt{a^2 + b^2} = 2 \).

Thus, the given equation can be rewritten as
\[
\frac{\sqrt{3}}{2} \sin \theta - \frac{1}{2} \cos \theta = \frac{1}{\sqrt{2}}
\]
\[
\sin \theta \cos \frac{\pi}{6} - \cos \theta \sin \frac{\pi}{6} = \sin \frac{\pi}{4}
\]
\[
\sin\left(\theta - \frac{\pi}{6}\right) = \sin \frac{\pi}{4}
\]
\[
\theta - \frac{\pi}{6} = n\pi + (-1)^n \frac{\pi}{4}, n \in \mathbb{Z}
\]

Thus, \( \theta = n\pi + \frac{\pi}{6} + (-1)^n \frac{\pi}{4}, n \in \mathbb{Z} \).

### Example 3.55

Solve \( \sqrt{3}\tan^2 \theta + (\sqrt{3} - 1)\tan \theta - 1 = 0 \)

**Solution:**

\[
\sqrt{3}\tan^2 \theta + (\sqrt{3} - 1)\tan \theta - 1 = 0
\]
\[
\sqrt{3}\tan^2 \theta + \sqrt{3}\tan \theta - \tan \theta - 1 = 0
\]
\[
(\sqrt{3}\tan \theta - 1)(\tan \theta + 1) = 0
\]

Thus, either \( \sqrt{3}\tan \theta - 1 = 0 \) (or) \( \tan \theta + 1 = 0 \)

If \( \sqrt{3}\tan \theta - 1 = 0 \), \( \tan \theta = \frac{1}{\sqrt{3}} = \tan \frac{\pi}{6} \Rightarrow \theta = n\pi + \frac{\pi}{6}, n \in \mathbb{Z} \)

If \( \tan \theta + 1 = 0 \), \( \tan \theta = -1 = \tan\left(-\frac{\pi}{4}\right) \Rightarrow \theta = n\pi - \frac{\pi}{4}, n \in \mathbb{Z} \)

Thus, the general solution is \( \theta = n\pi + \frac{\pi}{6} \) or \( \theta = n\pi - \frac{\pi}{4}, n \in \mathbb{Z} \).

From (i) and (ii) we have the general solution.

## Exercise 3.8

1. Find the principal solution and general solutions of the following:
   (i) \( \sin \theta = -\frac{1}{\sqrt{2}} \) (ii) \( \cot \theta = \sqrt{3} \) (iii) \( \tan \theta = -\frac{1}{\sqrt{3}} \).

2. Solve the following equations for which solutions lies in the interval \( 0^\circ \leq \theta < 360^\circ \)
   (i) \( \sin^4 x = \sin^2 x \)
   (ii) \( 2\cos^2 x + 1 = -3\cos x \)
   (iii) \( 2\sin^2 x + 1 = 3\sin x \)
   (iv) \( \cos 2x = 1 - 3\sin x \).

3. Solve the following equations:
   (i) \( \sin 5x - \sin x = \cos 3x \)
   (ii) \( 2\cos^2 \theta + 3\sin \theta - 3 = 0 \)
   (iii) \( \cos \theta + \cos 3\theta = 2\cos 2\theta \)
   (iv) \( \sin \theta + \sin 3\theta + \sin 5\theta = 0 \)
   (v) \( \sin 2\theta - \cos 2\theta - \sin \theta + \cos \theta = 0 \)
   (vi) \( \sin \theta + \cos \theta = \sqrt{2} \)
   (vii) \( \sin \theta + \sqrt{3}\cos \theta = 1 \)
   (viii) \( \cot \theta + \csc \theta = \sqrt{3} \)
   (ix) \( \tan \theta + \tan\left(\theta + \frac{\pi}{3}\right) + \tan\left(\theta + \frac{2\pi}{3}\right) = \sqrt{3} \)
   (x) \( \cos 2\theta = \frac{\sqrt{5} + 1}{4} \)
   (xi) \( 2\cos^2 x - 7\cos x + 3 = 0 \)

## 3.7 Properties of Triangles

We shall discuss some properties of triangles using trigonometric functions. In any triangle \( ABC \), the angles are usually denoted by \( A, B, C \) and the sides opposite to these angles are denoted by \( a = BC, b = AC, c = AB \) respectively. 

### 3.7.1 Law of Sines

**Theorem 3.1 (The Law of Sines):** In any triangle \( ABC \), \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R \), where \( R \) is the circumradius of the triangle \( ABC \).

**Proof.** There are three possibilities for the type of triangle \( ABC \). We shall prove this theorem for all three cases.

**Case I:** \( \angle A \) is acute. 

Produce \( BO \) to meet the circle at \( D \). 
\[
\angle BDC = \angle BAC = A
\]
\[
\angle BCD = 90^\circ
\]
\[
\sin \angle BDC = \frac{BC}{BD} \text{ or } \sin A = \frac{a}{2R} \Rightarrow \frac{a}{\sin A} = 2R
\]

**Case II:** \( \angle A \) is right angle.

In this case \( O \) must be on the side \( BC \) of the \( \triangle ABC \). 
\[
\frac{a}{\sin A} = \frac{BC}{\sin 90^\circ} = \frac{2R}{1} = 2R \Rightarrow \frac{a}{\sin A} = 2R
\]

**Case III:** \( \angle A \) is obtuse.

Produce \( BO \) to meet the circle at \( D \).
\[
\angle BDC + \angle BAC = 180^\circ
\]
\[
\angle BDC = 180^\circ - \angle BAC = 180^\circ - A
\]
\[
\angle BCD = 90^\circ
\]
\[
\sin \angle BDC = \frac{BC}{BD} \text{ or } \sin(180^\circ - A) = \sin A = \frac{a}{2R} \Rightarrow \frac{a}{\sin A} = 2R
\]

In each case, we have \( \frac{a}{\sin A} = 2R \)

Similarly, by considering angles \( B \) and \( C \), we can prove that \( \frac{b}{\sin B} = 2R \) and \( \frac{c}{\sin C} = 2R \) respectively.

\[
\therefore \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R.
\]

(i) The Law of Sines can be written as a collection of three equations
\[
\frac{a}{b} = \frac{\sin A}{\sin B}; \quad \frac{a}{c} = \frac{\sin A}{\sin C}; \quad \frac{b}{c} = \frac{\sin B}{\sin C};
\]

(ii) The Law of Sines says that the sides of a triangle are proportional to the sines of their opposite angles.

(iii) Using the Law of Sines, it is impossible to find the solution to a triangle given two sides and the included angle.

(iv) An interesting geometric consequence of the Law of Sines is that the largest side of any triangle is opposite to the largest angle. (Prove)

### Napier's Formula

**Theorem 3.2:** In \( \triangle ABC \), we have
\[
\frac{a - b}{a + b} \cot \frac{C}{2} = \tan \frac{A - B}{2}
\]
\[
\frac{b - c}{b + c} \cot \frac{A}{2} = \tan \frac{B - C}{2}
\]
\[
\frac{c - a}{c + a} \cot \frac{B}{2} = \tan \frac{C - A}{2}
\]

**Proof.**

We know the sine formula: \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R \)

Now,
\[
\frac{a - b}{a + b} \cot \frac{C}{2} = \frac{2R\sin A - 2R\sin B}{2R\sin A + 2R\sin B} \cot \frac{C}{2}
\]
\[
= \frac{\sin A - \sin B}{\sin A + \sin B} \cot \frac{C}{2}
\]
\[
= \frac{2\cos \frac{A + B}{2} \sin \frac{A - B}{2}}{2\sin \frac{A + B}{2} \cos \frac{A - B}{2}} \cot \frac{C}{2}
\]
\[
= \cot \frac{A + B}{2} \tan \frac{A - B}{2} \cot \frac{C}{2}
\]
\[
= \cot\left(90^\circ - \frac{C}{2}\right) \tan \frac{A - B}{2} \cot \frac{C}{2}
\]
\[
= \tan \frac{C}{2} \tan \frac{A - B}{2} \cot \frac{C}{2} = \tan \frac{A - B}{2}
\]

Similarly we can prove the other two results.

### 3.7.2 Law of Cosines

When two sides and included angle or the three sides of a triangle are given, the triangle cannot be solved using the sine formula. In such a situation, the law of cosines can be used to solve the triangle. Also, the Law of Cosines is used to derive a formula for finding the area of a triangle given two sides and the included angle.

**Theorem 3.3 (The Law of Cosines):** In \( \triangle ABC \), we have
\[
\cos A = \frac{b^2 + c^2 - a^2}{2bc}, \quad \cos B = \frac{c^2 + a^2 - b^2}{2ca}, \quad \cos C = \frac{a^2 + b^2 - c^2}{2ab}.
\]

**Proof.** In \( \triangle ABC \), draw \( AD \perp BC \).

In \( \triangle ABD \), we have \( AB^2 = AD^2 + BD^2 \Rightarrow c^2 = AD^2 + BD^2 \).

Now, we find the values of \( AD \) and \( BD \) in terms of the elements of \( \triangle ABC \).

\[
\frac{AD}{AC} = \sin C \Rightarrow AD = b \sin C
\]
\[
BD = BC - DC = a - b \cos C
\]

\[
c^2 = (b \sin C)^2 + (a - b \cos C)^2
\]
\[
= b^2 \sin^2 C + a^2 + b^2 \cos^2 C - 2ab \cos C
\]
\[
= a^2 + b^2 (\sin^2 C + \cos^2 C) - 2ab \cos C
\]
\[
= a^2 + b^2 - 2ab \cos C
\]

Thus, \( c^2 = a^2 + b^2 - 2ab \cos C \) or \( \cos C = \frac{a^2 + b^2 - c^2}{2ab} \).

Similarly, we can prove the other two results, namely
\[
a^2 = b^2 + c^2 - 2bc \cos A \text{ or } \cos A = \frac{b^2 + c^2 - a^2}{2bc}
\]
\[
b^2 = c^2 + a^2 - 2ca \cos B \text{ or } \cos B = \frac{c^2 + a^2 - b^2}{2ca}
\]

(i) \( a^2 = b^2 + c^2 - 2bc \cos A \) says that the square of a side is the sum of squares of other two sides diminished by twice the product of those two sides and the cosine of the included angle. Also one formula will give the other formula by cycling through the letters \( a, b, c \)

(ii) The Laws of Cosine for right triangles reduce to Pythagorean theorem. Thus, the Law of cosines can be viewed as a generalisation of Pythagorean theorem.

(iii) The advantage of using law of cosines over law of sines is that unlike the sine function, the cosine function distinguishes between acute and obtuse angles. If cosine of an angle is positive, then it is acute. Otherwise, it is obtuse.

(iv) The Law of Cosines says: The direct route is the shortest. Let us explain this. In a \( \triangle ABC \), \( c^2 = a^2 + b^2 - 2ab \cos C \). Since \( \cos C < 1 \), we have \( c^2 < a^2 + b^2 + 2ab = (a + b)^2 \). Thus, we have \( c < a + b \). Hence, in \( \triangle ABC \), we have \( a < b + c \), \( b < c + a \), \( c < a + b \)

(v) When using the law of cosines, it is always best to find the measure of the largest unknown angle first, since this will give us the obtuse angle of the triangle if there is one such angle.

### 3.7.3 Projection Formula

**Theorem 3.4:** In a \( \triangle ABC \), we have
\[
a = b \cos C + c \cos B, \quad b = c \cos A + a \cos C, \quad c = a \cos B + b \cos A
\]

**Proof.** In \( \triangle ABC \), we have \( a = BC \). Draw \( AD \perp BC \)

\[
a = BC = BD + DC
\]
\[
= \frac{BD}{AB} \cdot AB + \frac{DC}{AC} \cdot AC
\]
\[
= (\cos B)c + (\cos C)b
\]
\[
= b \cos C + c \cos B
\]

**Figure 3.20**

Similarly, one can prove the other two projection formulas.

\( a = b \cos C + c \cos B \) says that \( a = \) projection of \( b \) on \( a + \) projection of \( c \) on \( a \). Thus, a side of triangle is equal to sum of the projections of other two sides on it.

### 3.7.4 Area of the Triangle

We shall use some elements of an oblique triangle and the sine function to find the area of the triangle. Recall that area formula for \( \triangle ABC \) is \( \frac{1}{2} bh \) where \( b \) is the base and \( h \) is the height. For oblique triangle, we must find \( h \) before using the area formula.

**Theorem 3.5:** In \( \triangle ABC \), area of the triangle is
\[
\Delta = \frac{1}{2} ab \sin C = \frac{1}{2} bc \sin A = \frac{1}{2} ac \sin B
\]

**Proof.** In \( \triangle ABC \), draw \( AD \perp BC \)

In \( \triangle ADC \), \( \frac{AD}{AC} = \sin C \Rightarrow AD = b \sin C \)

Thus, \( \Delta = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times a \times (b \sin C) = \frac{1}{2} ab \sin C \).

**Figure 3.21**

Similarly we can derive the other two results.

(i) The formula for the area of an oblique triangle says that the area is equal to one half of the product of two sides and the sine of their included angle.

(ii) The area formula is used to compute the area of the segment of a circle. Segment of a circle is the region between a chord and the arc it cuts off. Let \( r \) be the radius of a circle and \( \theta \) be the angle subtended by the chord \( AB \) at the centre.

**Figure 3.22**

Area of the segment \( ABD = \) Area of the sector - Area of the \( \triangle OAB \)
\[
= \frac{1}{2} r^2 \theta - \frac{1}{2} r^2 \sin \theta
\]
\[
= \frac{1}{2} r^2 (\theta - \sin \theta)
\]

(iii) The area formula of a triangle is viewed as generalisation of area formula of a right triangle.

(iv) In the above formula, it is clear that the measure of third side is not required in finding the area of the triangles. Also there is no need of finding the altitude of the triangle in order to find its area.

### Example 3.56

The Government plans to have a circular zoological park of diameter \( 8 \) km. A separate area in the form of a segment formed by a chord of length \( 4 \) km is to be allotted exclusively for a veterinary hospital in the park. Find the area of the segment to be allotted for the veterinary hospital.

**Solution:**

Let AB be the chord and \( O \) be the centre of the circular park. Let \( \angle AOB = \theta \)

**Figure 3.23**

Area of the segment = Area of the sector - Area of \( \triangle OAB \)
\[
= \frac{1}{2} r^2 \theta - \frac{1}{2} r^2 \sin \theta
\]
\[
= \left(\frac{1}{2} \times 4^2\right)[\theta - \sin \theta] = 8[\theta - \sin \theta] \quad \dots \text{(i)}
\]

But \( \cos \theta = \frac{4^2 + 4^2 - 4^2}{2(4)(4)} = \frac{1}{2} \)

Thus, \( \theta = \frac{\pi}{3} \)

From (i), area of the segment to be allotted for the veterinary hospital
\[
= 8\left[\frac{\pi}{3} - \frac{\sqrt{3}}{2}\right] = \frac{4}{3}[2\pi - 3\sqrt{3}] \text{ km}^2
\]

### 3.7.5 Half-Angle formula

**Theorem 3.6:** In \( \triangle ABC \),
(i) \( \sin \frac{A}{2} = \sqrt{\frac{(s - b)(s - c)}{bc}} \)
(ii) \( \cos \frac{A}{2} = \sqrt{\frac{s(s - a)}{bc}} \)
(iii) \( \tan \frac{A}{2} = \sqrt{\frac{(s - b)(s - c)}{s(s - a)}} \)
where \( s \) is the semi-perimeter of \( \triangle ABC \) given by \( s = \frac{a + b + c}{2} \)

**Proof.**

(i) \( \sin \frac{A}{2} = +\sqrt{\sin^2 \frac{A}{2}} = \sqrt{\frac{1 - \cos A}{2}} = \sqrt{\frac{1}{2}\left(1 - \frac{b^2 + c^2 - a^2}{2bc}\right)} \)
\[
= \sqrt{\frac{2bc - b^2 - c^2 + a^2}{4bc}} = \sqrt{\frac{a^2 - (b - c)^2}{4bc}}
\]
\[
= \sqrt{\frac{(a + b - c)(a - b + c)}{4bc}} = \sqrt{\frac{(a + b + c - 2c)(a + b + c - 2b)}{4bc}}
\]
\[
= \sqrt{\frac{(2s - 2b)(2s - 2c)}{4bc}} = \sqrt{\frac{(s - b)(s - c)}{bc}}
\]

Thus, \( \sin \frac{A}{2} = \sqrt{\frac{(s - b)(s - c)}{bc}} \)

Similarly, we can prove the other two results.

The other half-angle formulas are
\[
\sin \frac{B}{2} = \sqrt{\frac{(s - c)(s - a)}{ac}}, \quad \sin \frac{C}{2} = \sqrt{\frac{(s - a)(s - b)}{ab}}
\]
\[
\cos \frac{B}{2} = \sqrt{\frac{s(s - b)}{ac}}, \quad \cos \frac{C}{2} = \sqrt{\frac{s(s - c)}{ab}}
\]
\[
\tan \frac{B}{2} = \sqrt{\frac{(s - a)(s - c)}{s(s - b)}}, \quad \tan \frac{C}{2} = \sqrt{\frac{(s - a)(s - b)}{s(s - c)}}
\]

**Corollary:**
\[
\sin A = 2\sin \frac{A}{2} \cos \frac{A}{2} = 2\sqrt{\frac{(s - b)(s - c)}{bc}} \sqrt{\frac{s(s - a)}{bc}}
\]
\[
\sin A = \frac{2}{bc} \sqrt{s(s - a)(s - b)(s - c)}
\]

### Area of a triangle (Heron's Formula)

Heron's formula is named after Hero of Alexandria, a Greek Engineer and Mathematician in (CE 10-70). This formula is used only when all the three sides are known.

**Theorem 3.7:** In \( \triangle ABC \), \( \Delta = \sqrt{s(s - a)(s - b)(s - c)} \) where \( s \) is the semi-perimeter of \( \triangle ABC \).

**Proof.**
\[
\Delta = \frac{1}{2} ab \sin C = \frac{1}{2} ab \left(2\sin \frac{C}{2} \cos \frac{C}{2}\right)
\]
\[
= ab \sqrt{\frac{(s - a)(s - b)}{ab}} \sqrt{\frac{s(s - c)}{ab}} = \sqrt{s(s - a)(s - b)(s - c)}
\]

(i) Using Heron's formula, Pythagorean theorem can be proved for right triangle and conversely, using Pythagorean theorem for right triangle one can establish Heron's area formula.

(ii) If area of a triangle is given as an integer, then Heron's formula is useful in finding triangles with integer sides.

(iii) If the perimeter of a triangle is fixed, then Heron's formula is useful for finding triangles having integer area and integer sides. For example, if the perimeter of a triangle is \( 100 \) m, then there is a triangle with sides \( 32 \) m, \( 34 \) m, \( 34 \) m and area \( 480 \) m\(^2 \).

### Example 3.57

In a \( \triangle ABC \), prove that \( b^2 \sin 2C + c^2 \sin 2B = 2bc \sin A \).

**Solution:**

The Sine formula is, \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R \)

Thus, \( a = 2R \sin A; b = 2R \sin B; c = 2R \sin C \)

\[
b^2 \sin 2C + c^2 \sin 2B = 4R^2 \sin^2 B \cdot \sin 2C + 4R^2 \sin^2 C \cdot \sin 2B
\]
\[
= 4R^2(2\sin^2 B \sin C \cos C + 2\sin^2 C \sin B \cos B)
\]
\[
= 8R^2 \sin B \sin C (\sin B \cos C + \sin C \cos B)
\]
\[
= 8R^2 \sin B \sin C \sin(B + C)
\]
\[
= 8R^2 \sin B \sin C \sin(\pi - A) = 8R^2 \sin B \sin C \sin A
\]
\[
= 8R^2 \left(\frac{b}{2R}\right) \left(\frac{c}{2R}\right) \sin A = 2bc \sin A.
\]

### Example 3.58

In a \( \triangle ABC \), prove that \( \sin\left(\frac{B - C}{2}\right) = \frac{b - c}{a} \cos \frac{A}{2} \).

**Solution:**

The Sine formula is, \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R \)

\[
\frac{b - c}{a} \cos \frac{A}{2} = \frac{2R\sin B - 2R\sin C}{2R\sin A} \cos \frac{A}{2}
\]
\[
= \frac{2\cos \frac{B + C}{2} \sin \frac{B - C}{2}}{2\sin \frac{A}{2} \cos \frac{A}{2}} \cos \frac{A}{2}
\]
\[
= \frac{\sin \frac{B - C}{2} \cos\left(90^\circ - \frac{A}{2}\right)}{\sin \frac{A}{2}}
\]
\[
= \frac{\sin \frac{B - C}{2} \cdot \sin \frac{A}{2}}{\sin \frac{A}{2}} = \sin\left(\frac{B - C}{2}\right).
\]

### Example 3.59

If the three angles in a triangle are in the ratio \( 1:2:3 \), then prove that the corresponding sides are in the ratio \( 1:\sqrt{3}:2 \).

**Solution:**

Let the angles be \( \theta, 2\theta, 3\theta \).

Then \( \theta + 2\theta + 3\theta = 180^\circ \)

Thus, \( \theta = 30^\circ \)

Using the sine formula, \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} \), we have,

\[
\frac{a}{\sin 30^\circ} = \frac{b}{\sin 60^\circ} = \frac{c}{\sin 90^\circ}
\]
\[
a:b:c = \sin 30^\circ : \sin 60^\circ : \sin 90^\circ
\]
\[
= \frac{1}{2} : \frac{\sqrt{3}}{2} : 1 = 1 : \sqrt{3} : 2
\]

### Example 3.60

In a \( \triangle ABC \), prove that
\[
(b + c)\cos A + (c + a)\cos B + (a + b)\cos C = a + b + c
\]

**Solution:**

\[
\text{L.H.S} = b\cos A + c\cos A + c\cos B + a\cos B + a\cos C + b\cos C
\]
\[
= b\cos C + c\cos B + c\cos A + a\cos C + b\cos A + a\cos B
\]
\[
= a + b + c \quad [\text{by projection formula}]
\]

### Example 3.61

In a triangle \( ABC \), prove that \( \frac{a^2 + b^2}{a^2 + c^2} = \frac{1 + \cos(A - B)\cos C}{1 + \cos(A - C)\cos B} \)

**Solution:**

The sine formula is, \( \frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R \)

\[
\text{L.H.S} = \frac{a^2 + b^2}{a^2 + c^2} = \frac{(2R\sin A)^2 + (2R\sin B)^2}{(2R\sin A)^2 + (2R\sin C)^2}
\]
\[
= \frac{\sin^2 A + \sin^2 B}{\sin^2 A + \sin^2 C} = \frac{1 - \cos^2 A + \sin^2 B}{1 - \cos^2 A + \sin^2 C}
\]
\[
= \frac{1 - (\cos^2 A - \sin^2 B)}{1 - (\cos^2 A - \sin^2 C)} = \frac{1 - \cos(A + B)\cos(A - B)}{1 - \cos(A + C)\cos(A - C)}
\]
\[
= \frac{1 + \cos(A - B)\cos C}{1 + \cos(A - C)\cos B}.
\]

### Example 3.62

Derive cosine formula using the law of sines in a \( \triangle ABC \).

**Solution:**

\[
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R
\]
\[
\frac{b^2 + c^2 - a^2}{2bc} = \frac{(2R\sin B)^2 + (2R\sin C)^2 - (2R\sin A)^2}{2(2R\sin B)(2R\sin C)}
\]
\[
= \frac{\sin^2 B + \sin^2 C - \sin^2 A}{2\sin B \sin C}
\]
\[
= \frac{\sin^2 B + \sin(C + A)\sin(C - A)}{2\sin B \sin C}
\]
\[
= \frac{\sin B[\sin B + \sin(C - A)]}{2\sin B \sin C}
\]
\[
= \frac{\sin(C + A) + \sin(C - A)}{2\sin C} = \cos A
\]

Thus, \( \cos A = \frac{b^2 + c^2 - a^2}{2bc} \). Similarly we can derive other two cosine formulas.

### Example 3.63

Using Heron's formula, show that the equilateral triangle has the maximum area for any fixed perimeter. [Hint: In \( xyz \leq k \), maximum occurs when \( x = y = z \)].

**Solution:**

Let \( ABC \) be a triangle with constant perimeter \( 2s \). Thus \( s \) is constant.

We know that \( \Delta = \sqrt{s(s - a)(s - b)(s - c)} \)

Observe that \( \Delta \) is maximum, when \( (s - a)(s - b)(s - c) \) is maximum.

Now,
\[
(s - a)(s - b)(s - c) \leq \left(\frac{(s - a) + (s - b) + (s - c)}{3}\right)^3 = \frac{s^3}{27} \quad [\text{G.M.} \leq \text{A.M.}]
\]

Thus, we get \( (s - a)(s - b)(s - c) \leq \frac{s^3}{27} \)

Equality occurs when \( s - a = s - b = s - c \). That is, when \( a = b = c \), maximum of \( (s - a)(s - b)(s - c) \) is \( \frac{s^3}{27} \)

Thus, for a fixed perimeter \( 2s \), the area of a triangle is maximum when \( a = b = c \).

Hence, for a fixed perimeter, the equilateral triangle has the maximum area and the maximum area is given by \( \Delta = \sqrt{s \cdot \frac{s^3}{27}} = \frac{s^2}{3\sqrt{3}} \) sq. units.

## Exercise 3.9

1. In a \( \triangle ABC \), if \( \frac{\sin A}{\sin C} = \frac{\sin(A - B)}{\sin(B - C)} \), prove that \( a^2, b^2, c^2 \) are in Arithmetic Progression.

2. The angles of a triangle \( ABC \), are in Arithmetic Progression and if \( b:c = \sqrt{3}:\sqrt{2} \), find \( \angle A \).

3. In a \( \triangle ABC \), if \( \cos C = \frac{\sin A}{2\sin B} \), show that the triangle is isosceles.

4. In a \( \triangle ABC \), prove that \( \frac{\sin B}{\sin C} = \frac{c - a\cos B}{b - a\cos C} \).

5. In a \( \triangle ABC \), prove that \( a\cos A + b\cos B + c\cos C = 2a\sin B \sin C \).

6. In a \( \triangle ABC \), \( \angle A = 60^\circ \). Prove that \( b + c = 2a\cos\left(\frac{B - C}{2}\right) \).

7. In a \( \triangle ABC \), prove the following
   (i) \( a\sin\left(\frac{A}{2} + B\right) = (b + c)\sin \frac{A}{2} \)
   (ii) \( a(\cos B + \cos C) = 2(b + c)\sin^2 \frac{A}{2} \)
   (iii) \( \frac{a^2 - c^2}{b^2} = \frac{\sin(A - C)}{\sin(A + C)} \)
   (iv) \( \frac{a\sin(B - C)}{b^2 - c^2} = \frac{b\sin(C - A)}{c^2 - a^2} = \frac{c\sin(A - B)}{a^2 - b^2} \)
   (v) \( \frac{a + b}{a - b} = \tan\left(\frac{A + B}{2}\right) \cot\left(\frac{A - B}{2}\right) \).

8. In a \( \triangle ABC \), prove that \( (a^2 - b^2 + c^2)\tan B = (a^2 + b^2 - c^2)\tan C \).

9. An Engineer has to develop a triangular shaped park with a perimeter \( 120 \) m in a village. The park to be developed must be of maximum area. Find out the dimensions of the park.

10. A rope of length \( 12 \) m is given. Find the largest area of the triangle formed by this rope and find the dimensions of the triangle so formed.

11. Derive Projection formula from (i) Law of sines, (ii) Law of cosines.

## 3.8 Application to Triangle

Much of architecture and engineering relies on triangular support on any structure where stability is desired. Trigonometry helps to calculate the correct angle for the triangular support. Also trigonometry envisages the builders to correctly layout a curved structure. For a right triangle, any two information with atleast one side say SS, SA are sufficient to find the remaining elements of the triangle. But, to find the solution of an oblique triangle we need three elements with atleast one side. If any three elements with atleast one side of a triangle are given, then the Law of Sines, the Law of Cosines, the Projection formula can be used to find the other three elements.

### Working Rule:

In a right triangle, two sides determine the third side via the Pythagorean theorem and one acute angle determine the other by using the fact that acute angles in a right triangle are complementary. If all the sides of a triangle are given, then we can use either cosine formula or half-angle formula to calculate all the angles of the triangle. If any two angles and any one of the sides opposite to given angles are given, then we can use sine formula to calculate the other sides. If any two sides of a triangle and the included angle are given, we cannot use the Law of sines; but then we can use the law of cosines to calculate other side and other angles of the triangle. In this case we have a unique triangle. All methods of solving an oblique triangle require that the length of atleast one side must be provided.

Let us summarise the working rule to solve an oblique triangle in the following table

| Oblique triangle (all angles are acute or one angle is obtuse) | Given Information | Details and Application for solutions |
|---------------------------------------------------------------|------------------|----------------------------------------|
| | AAS | Law of sines |
| | ASA | Law of sines |
| | SSA* | Law of sines* (ambiguity arises) |
| | SAS | The given angle must be included angle; Either law of Cosines or tangents |
| | SSS | Law of Cosines; First find the largest angle |
| | AAA | Infinite number of triangles |

*Angle is not included; We may have more than one triangle;

Application of law of sines yields three cases: No solution or one triangle or two triangles.

Suppose \( a, b, A \) are known. Let \( h = b \sin A \)

If \( a < h \) there is no triangle,

If \( a = h \) then it is right triangle.

If \( a > h \) and \( a < b \) we have two triangles.

If \( a \geq b \) we have only one triangle.

*SSA means Side, Side and Angle

### Example 3.64

In a \( \triangle ABC \), \( a = 3, b = 5 \) and \( c = 7 \). Find the values of \( \cos A, \cos B \) and \( \cos C \).

**Solution:**

By Cosine formula,
\[
\cos A = \frac{b^2 + c^2 - a^2}{2bc} = \frac{5^2 + 7^2 - 3^2}{2(5)(7)} = \frac{13}{14}
\]
Similarly, \( \cos B = \frac{11}{14}, \cos C = -\frac{1}{2} \).

### Example 3.65

In \( \triangle ABC \), \( A = 30^\circ \), \( B = 60^\circ \) and \( c = 10 \). Find \( a \) and \( b \).

**Solution:**

Given that \( A = 30^\circ \), \( B = 60^\circ \), \( C = 180^\circ - (A + B) = 90^\circ \)

Using sine formula,
\[
\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C}
\]
\[
\frac{a}{\sin 30^\circ} = \frac{b}{\sin 60^\circ} = \frac{10}{\sin 90^\circ}
\]
\[
a = \frac{10 \sin 30^\circ}{\sin 90^\circ} = \frac{10 \cdot \frac{1}{2}}{1} = 5
\]
\[
b = \frac{10 \sin 60^\circ}{\sin 90^\circ} = \frac{10 \cdot \frac{\sqrt{3}}{2}}{1} = 5\sqrt{3}.
\]

### Example 3.66

In a \( \triangle ABC \), if \( a = 2\sqrt{2} \), \( b = 2\sqrt{3} \) and \( C = 75^\circ \), find the other side and the angles.

**Solution:**

Given that \( a = 2\sqrt{2} \), \( b = 2\sqrt{3} \) and \( C = 75^\circ \)

Using cosine formula,
\[
\cos C = \frac{a^2 + b^2 - c^2}{2ab}
\]
\[
\cos 75^\circ = \frac{8 + 12 - c^2}{2 \cdot 2\sqrt{2} \cdot 2\sqrt{3}} = \frac{20 - c^2}{8\sqrt{6}}
\]
\[
\cos 75^\circ = \cos(45^\circ + 30^\circ) = \cos 45^\circ \cos 30^\circ - \sin 45^\circ \sin 30^\circ = \frac{\sqrt{6} - \sqrt{2}}{4}
\]

Thus,
\[
\frac{\sqrt{6} - \sqrt{2}}{4} = \frac{20 - c^2}{8\sqrt{6}} \Rightarrow 2\sqrt{6}(\sqrt{6} - \sqrt{2}) = 20 - c^2
\]
\[
2(6 - \sqrt{12}) = 20 - c^2 \Rightarrow 12 - 4\sqrt{3} = 20 - c^2 \Rightarrow c^2 = 8 + 4\sqrt{3}
\]
\[
c = \sqrt{8 + 4\sqrt{3}} = \sqrt{(\sqrt{6} + \sqrt{2})^2} = \sqrt{6} + \sqrt{2}
\]

Also,
\[
\cos A = \frac{b^2 + c^2 - a^2}{2bc} = \frac{12 + (8 + 4\sqrt{3}) - 8}{2 \cdot 2\sqrt{3} \cdot (\sqrt{6} + \sqrt{2})} = \frac{12 + 4\sqrt{3}}{4\sqrt{3}(\sqrt{6} + \sqrt{2})} = \frac{4\sqrt{3}(\sqrt{3} + 1)}{4\sqrt{3}(\sqrt{6} + \sqrt{2})}
\]
\[
= \frac{\sqrt{3} + 1}{\sqrt{6} + \sqrt{2}} = \frac{1}{\sqrt{2}} \Rightarrow A = 45^\circ
\]

Thus, \( B = 180^\circ - (A + C) = 60^\circ \).

### Example 3.67

Find the area of the triangle whose sides are \( 13 \) cm, \( 14 \) cm and \( 15 \) cm.

**Solution:**

\[
s = \frac{a + b + c}{2} \Rightarrow s = \frac{13 + 14 + 15}{2} = 21 \text{ cm}.
\]

Area of a triangle \( = \sqrt{s(s - a)(s - b)(s - c)} \)
\[
= \sqrt{21(21 - 13)(21 - 14)(21 - 15)} = \sqrt{21 \times 8 \times 7 \times 6} = \sqrt{7056} = 84 \text{ sq.cm}.
\]

### Example 3.68

In any \( \triangle ABC \), prove that \( a\cos A + b\cos B + c\cos C = \frac{8\Delta^2}{abc} \).

**Solution:**

We know that \( a\cos A + b\cos B + c\cos C = 2a\sin B \sin C \)

Also, \( \Delta = \frac{1}{2} ac \sin B \Rightarrow \sin B = \frac{2\Delta}{ac} \)
\[
\Delta = \frac{1}{2} ab \sin C \Rightarrow \sin C = \frac{2\Delta}{ab}
\]

Thus,
\[
a\cos A + b\cos B + c\cos C = 2a \cdot \frac{2\Delta}{ac} \cdot \frac{2\Delta}{ab} = \frac{8\Delta^2}{abc}
\]

### Example 3.69

Suppose that there are two cell phone towers within range of a cell phone. The two towers are located at \( 6 \) km apart along a straight highway, running east to west and the cell phone is north of the highway. The signal is \( 5 \) km from the first tower and \( \sqrt{31} \) km from the second tower. Determine the position of the cell phone north and east of the first tower and how far it is from the highway.

**Figure 3.24**

**Solution:**

Let \( \theta \) be the position of the cell phone from north to east of the first tower. Then, using the cosine formula, we have,

\[
(\sqrt{31})^2 = 5^2 + 6^2 - 2 \times 5 \times 6 \cos \theta
\]
\[
31 = 25 + 36 - 60 \cos \theta
\]
\[
\cos \theta = \frac{1}{2} \Rightarrow \theta = 60^\circ
\]

Let \( x \) be the distance of the cell phone's position from the highway.

Then, \( \sin \theta = \frac{x}{5} \Rightarrow x = 5\sin \theta = 5\sin 60^\circ = \frac{5\sqrt{3}}{2} \) km.

### Example 3.70

Suppose that a boat travels \( 10 \) km from the port towards east and then turns \( 60^\circ \) to its left. If the boat travels further \( 8 \) km, how far from the port is the boat?

**Figure 3.25**

**Solution:**

Let \( BP \) be the required distance. By using the cosine formula, we have,

\[
BP^2 = 10^2 + 8^2 - 2 \times 10 \times 8 \times \cos 120^\circ = 100 + 64 - 160 \times \left(-\frac{1}{2}\right) = 164 + 80 = 244
\]
\[
BP = \sqrt{244} = 2\sqrt{61} \text{ km}
\]

### Example 3.71

Suppose two radar stations located \( 100 \) km apart, each detect a fighter aircraft between them. The angle of elevation measured by the first station is \( 30^\circ \), whereas the angle of elevation measured by the second station is \( 45^\circ \). Find the altitude of the aircraft at that instant.

**Figure 3.26**

**Solution:**

Let \( R_1 \) and \( R_2 \) be two radar stations and \( A \) be the position of fighter aircraft at the time of detection. Let \( x \) be the required altitude of the aircraft.

Draw \( \perp AN \) from \( A \) to \( R_1R_2 \) meeting at \( N \)

\[
\angle A = 180^\circ - (30^\circ + 45^\circ) = 105^\circ
\]

Thus,
\[
\frac{a}{\sin 45^\circ} = \frac{100}{\sin 105^\circ} \Rightarrow a = \frac{100}{\sin 105^\circ} \cdot \sin 45^\circ
\]

\[
\sin 105^\circ = \sin(60^\circ + 45^\circ) = \frac{\sqrt{6} + \sqrt{2}}{4}
\]

\[
a = \frac{100 \times \frac{1}{\sqrt{2}}}{\frac{\sqrt{6} + \sqrt{2}}{4}} = \frac{100 \times 4}{\sqrt{2}(\sqrt{6} + \sqrt{2})} = \frac{400}{2\sqrt{3} + 2} = \frac{200}{\sqrt{3} + 1} = 100(\sqrt{3} - 1) \text{ km}
\]

Now, \( \sin 30^\circ = \frac{x}{a} \Rightarrow x = a \cdot \frac{1}{2} = 50(\sqrt{3} - 1) \) km.

## Exercise 3.10

1. Determine whether the following measurements produce one triangle, two triangles or no triangle: \( \angle B = 88^\circ, a = 23, b = 2 \). Solve if solution exists.

2. If the sides of a \( \triangle ABC \) are \( a = 4, b = 6 \) and \( c = 8 \) then show that \( 4\cos B + 3\cos C = 2 \).

3. In a \( \triangle ABC \), if \( a = \sqrt{3} - 1, b = \sqrt{3} + 1 \) and \( C = 60^\circ \), find the other side and other two angles.

4. In any \( \triangle ABC \), prove that the area \( \Delta = \frac{b^2 + c^2 - a^2}{4\cot A} \).

5. In a \( \triangle ABC \), if \( a = 12 \) cm, \( b = 8 \) cm and \( C = 30^\circ \), then show that its area is \( 24 \) sq cm.

6. In a \( \triangle ABC \), if \( a = 18 \) cm, \( b = 24 \) cm and \( c = 30 \) cm, then show that its area is \( 216 \) sq cm.

7. Two soldiers \( A \) and \( B \) in two different underground bunkers on a straight road, spot an intruder at the top of a hill. The angle of elevation of the intruder from \( A \) and \( B \) to the ground level in the eastern direction are \( 30^\circ \) and \( 45^\circ \) respectively. If \( A \) and \( B \) stand \( 5 \) km apart, find the distance of the intruder from \( B \).

8. A researcher wants to determine the width of a pond from east to west, which cannot be done by actual measurement. From a point \( P \), he finds the distance to the eastern-most point of the pond to be \( 8 \) km, while the distance to the western most point from \( P \) to be \( 6 \) km. If the angle between the two lines of sight is \( 60^\circ \), find the width of the pond.

9. Two Navy helicopters \( A \) and \( B \) are flying over the Bay of Bengal at same altitude from the sea level to search a missing boat. Pilots of both the helicopters sight the boat at the same time while they are apart \( 10 \) km from each other. If the distance of the boat from \( A \) is \( 6 \) km and if the line segment \( AB \) subtends \( 60^\circ \) at the boat, find the distance of the boat from \( B \).

10. A straight tunnel is to be made through a mountain. A surveyor observes the two extremities \( A \) and \( B \) of the tunnel to be built from a point \( P \) in front of the mountain. If \( AP = 3 \) km, \( BP = 5 \) km and \( \angle APB = 120^\circ \), then find the length of the tunnel to be built.

11. A farmer wants to purchase a triangular shaped land with sides \( 120 \) feet and \( 60 \) feet and the angle included between these two sides is \( 60^\circ \). If the land costs \( ₹500 \) per sq.ft, find the amount he needed to purchase the land. Also find the perimeter of the land.

12. A fighter jet has to hit a small target by flying a horizontal distance. When the target is sighted, the pilot measures the angle of depression to be \( 30^\circ \). If after \( 100 \) km, the target has an angle of depression of \( 60^\circ \), how far is the target from the fighter jet at that instant?

13. A plane is \( 1 \) km from one landmark and \( 2 \) km from another. From the plane's point of view the land between them subtends an angle of \( 45^\circ \). How far apart are the landmarks?

14. A man starts his morning walk at a point \( A \) reaches two points \( B \) and \( C \) and finally back to \( A \) such that \( \angle A = 60^\circ \) and \( \angle B = 45^\circ \), \( AC = 4 \) km in the \( \triangle ABC \). Find the total distance he covered during his morning walk.

15. Two vehicles leave the same place \( P \) at the same time moving along two different roads. One vehicle moves at an average speed of \( 60 \) km/hr and the other vehicle moves at an average speed of \( 80 \) km/hr. After half an hour the vehicle reach the destinations \( A \) and \( B \). If \( AB \) subtends \( 60^\circ \) at the initial point \( P \), then find \( AB \).

16. Suppose that a satellite in space, an earth station and the centre of earth all lie in the same plane. Let \( r \) be the radius of earth and \( R \) be the distance from the centre of earth to the satellite. Let \( d \) be the distance from the earth station to the satellite. Let \( 30^\circ \) be the angle of elevation from the earth station to the satellite. If the line segment connecting earth station and satellite subtends angle \( \alpha \) at the centre of earth, then prove that \( d = R\sqrt{1 + \left(\frac{r}{R}\right)^2 - 2\frac{r}{R}\cos\alpha} \).

## 3.9 Inverse Trigonometric Functions

A function \( f(x) \) has inverse if and only if it is one-to-one and onto. Thus, inverse of a function cannot be defined if it fails to be one-to-one. However, if we restrict the domain suitably, we can make the function to be one-to-one in the restricted domain. For example, \( y = x^2 \) is not one-to-one for all real numbers. But \( y = x^2 \) is one-to-one and onto either for \( x \geq 0 \) or \( x \leq 0 \). Hence \( y = x^2, x \geq 0 \) has the inverse \( f^{-1}(x) = \sqrt{x}, x \geq 0 \). Now, owing to their periodicity, none of six trigonometric functions is one-to-one over their natural domains. We shall restrict their domains so that trigonometric functions are one-to-one enabling the existence of their inverse functions. This restriction can be done in many ways once again due to their periodicity. The conventional choices for the restricted domains are arbitrary but they have some important characteristics. Each restricted domain includes the number 0 and some positive angles and the image of restricted domain contains the entire range.

Let us define the inverse of sine function. Consider \( f(x) = \sin x, x \in \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \). Then, \( \sin x \) is one-to-one and onto in this restricted domain. Hence, the inverse of sine function exists. Note that \( f^{-1}(y) = x \) if and only if \( f(x) = y \). We write \( f^{-1}(x) = \sin^{-1}(x) \). Thus, inverse of sine is defined as \( \sin^{-1}(y) = x \) if and only if \( \sin x = y \).

Clearly, \( \sin x : \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \to [-1, 1] \) and \( \sin^{-1} x : [-1, 1] \to \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \). Thus, \( \sin^{-1} t \) is an angle whose sine is equal to \( t \) and which is located in \( \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \). Similarly we can define the other inverse trigonometric functions.

The inverse functions \( \sin^{-1} x, \cos^{-1} x, \tan^{-1} x, \csc^{-1}(x), \sec^{-1}(x), \cot^{-1}(x) \) are called inverse circular functions. For the function \( y = \sin x \), there are infinitely many angles \( x \) which satisfy \( \sin x = t, -1 \leq t \leq 1 \). Of these infinite set of values, there is one which lies in the interval \( \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \). This angle is called the principal angle and denoted by \( \sin^{-1} t \). The principal value of an inverse function is that value of the general value which is numerically least. It may be positive or negative. When there are two values, one is positive and the other is negative such that they are numerically equal, then the principal value is the positive one.

We shall illustrate below the restricted domains, ranges of trigonometric functions and the domains, ranges of the corresponding inverse functions.

(i) \( \sin x : \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \to [-1, 1] \); \( \sin^{-1} x : [-1, 1] \to \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] \)

(ii) \( \cos x : [0, \pi] \to [-1, 1] \); \( \cos^{-1} x : [-1, 1] \to [0, \pi] \)

(iii) \( \tan x : \left(-\frac{\pi}{2}, \frac{\pi}{2}\right) \to (-\infty, \infty) \); \( \tan^{-1} x : (-\infty, \infty) \to \left(-\frac{\pi}{2}, \frac{\pi}{2}\right) \)

(iv) \( \cot x : (0, \pi) \to (-\infty, \infty) \); \( \cot^{-1} x : (-\infty, \infty) \to (0, \pi) \)

(v) \( \csc x : \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] - \{0\} \to \mathbb{R} - (-1, 1) \); \( \csc^{-1} x : \mathbb{R} - (-1, 1) \to \left[-\frac{\pi}{2}, \frac{\pi}{2}\right] - \{0\} \)

(vi) \( \sec x : [0, \pi] - \left\{\frac{\pi}{2}\right\} \to \mathbb{R} - (-1, 1) \); \( \sec^{-1} x : \mathbb{R} - (-1, 1) \to [0, \pi] - \left\{\frac{\pi}{2}\right\} \)

(i) \( \sin^{-1} x \) does not mean \( \frac{1}{\sin x} \).

(ii) Another notation for \( \sin^{-1} x \) is \( \arcsin x \) due to Sir. John FW Herschel (1813).

(iii) While discussing the inverse of sine function, we confined to \( y = \sin x, -\frac{\pi}{2} \leq x \leq \frac{\pi}{2} \) and \( x = \sin^{-1} y, -1 \leq y \leq 1 \)

(iv) The graph of inverse function \( f^{-1} \) is the reflection of the graph of \( f \) about the line \( y = x \). Thus, if \( (a, b) \in f \) then \( (b, a) \in f^{-1} \).

Principal values of inverse trigonometric functions are listed below:

| Function | Principal value for \( x \geq 0 \) | Principal value for \( x < 0 \) |
|----------|-----------------------------------|--------------------------------|
| \( \sin^{-1}(x) \) | \( 0 \leq \sin^{-1}(x) \leq \frac{\pi}{2} \) | \( -\frac{\pi}{2} \leq \sin^{-1}(x) < 0 \) |
| \( \cos^{-1}(x) \) | \( 0 \leq \cos^{-1}(x) \leq \frac{\pi}{2} \) | \( \frac{\pi}{2} < \cos^{-1}(x) \leq \pi \) |
| \( \tan^{-1}(x) \) | \( 0 \leq \tan^{-1}(x) < \frac{\pi}{2} \) | \( -\frac{\pi}{2} < \tan^{-1}(x) < 0 \) |
| \( \cot^{-1}(x) \) | \( 0 < \cot^{-1}(x) \leq \frac{\pi}{2} \) | \( -\frac{\pi}{2} < \cot^{-1}(x) < 0 \) |
| \( \sec^{-1}(x) \) | \( 0 \leq \sec^{-1}(x) < \frac{\pi}{2} \) | \( \frac{\pi}{2} < \sec^{-1}(x) \leq \pi \) |
| \( \csc^{-1}(x) \) | \( 0 < \csc^{-1}(x) \leq \frac{\pi}{2} \) | \( -\frac{\pi}{2} < \csc^{-1}(x) < 0 \) |

(i) Properties, graphs, theorems on inverse trigonometric functions will be studied in higher secondary second year.

(ii) Inverse trigonometric functions are much useful in the evaluation of some integrals which will be studied later.

### Example 3.72

Find the principal value of (i) \( \sin^{-1}\left(\frac{\sqrt{3}}{2}\right) \), (ii) \( \csc^{-1}\left(\frac{2}{\sqrt{3}}\right) \), (iii) \( \tan^{-1}\left(-\frac{1}{\sqrt{3}}\right) \).

**Solution:**

(i) Let \( \sin^{-1}\left(\frac{\sqrt{3}}{2}\right) = y \), where \( -\frac{\pi}{2} \leq y \leq \frac{\pi}{2} \)

\( \Rightarrow \sin y = \frac{\sqrt{3}}{2} = \sin \frac{\pi}{3} \Rightarrow y = \frac{\pi}{3} \)

Thus, the principal value of \( \sin^{-1}\left(\frac{\sqrt{3}}{2}\right) = \frac{\pi}{3} \)

(ii) Let \( \csc^{-1}\left(\frac{2}{\sqrt{3}}\right) = y \), where \( -\frac{\pi}{2} \leq y \leq \frac{\pi}{2} \)

\( \Rightarrow \csc y = \frac{2}{\sqrt{3}} \Rightarrow \sin y = \frac{\sqrt{3}}{2} = \sin \frac{\pi}{3} \Rightarrow y = \frac{\pi}{3} \)

Thus, the principal value of \( \csc^{-1}\left(\frac{2}{\sqrt{3}}\right) = \frac{\pi}{3} \)

(iii) Let \( \tan^{-1}\left(-\frac{1}{\sqrt{3}}\right) = y \), where \( -\frac{\pi}{2} < y < \frac{\pi}{2} \)

\( \tan y = -\frac{1}{\sqrt{3}} \Rightarrow \tan y = \tan\left(-\frac{\pi}{6}\right) \Rightarrow y = -\frac{\pi}{6} \)

Thus the principal value of \( \tan^{-1}\left(-\frac{1}{\sqrt{3}}\right) = -\frac{\pi}{6} \).

## Exercise 3.11

1. Find the principal value of
   (i) \( \sin^{-1}\frac{1}{\sqrt{2}} \) (ii) \( \cos^{-1}\frac{\sqrt{3}}{2} \) (iii) \( \csc^{-1}(-1) \) (iv) \( \sec^{-1}(-\sqrt{2}) \) (v) \( \tan^{-1}(\sqrt{3}) \).

2. A man standing directly opposite to one side of a road of width \( x \) meter views a circular shaped traffic green signal of diameter \( a \) meter on the other side of the road. The bottom of the green signal is \( b \) meter height from the horizontal level of viewer's eye. If \( \alpha \) denotes the angle subtended by the diameter of the green signal at the viewer's eye, then prove that
   \[
   \alpha = \tan^{-1}\left(\frac{a + b}{x}\right) - \tan^{-1}\left(\frac{b}{x}\right).
   \]

## Multiple Choice Questions

1. \( \frac{1}{\cos 80^\circ} - \frac{\sqrt{3}}{\sin 80^\circ} = \)
   (1) \( \sqrt{2} \) (2) \( \sqrt{3} \) (3) 2 (4) 4

2. If \( \cos 28^\circ + \sin 28^\circ = k^3 \), then \( \cos 17^\circ \) is equal to
   (1) \( \frac{k^3}{\sqrt{2}} \) (2) \( -\frac{k^3}{\sqrt{2}} \) (3) \( \pm \frac{k^3}{\sqrt{2}} \) (4) \( -\frac{k^3}{\sqrt{3}} \)

3. The maximum value of \( 4\sin^2 x + 3\cos^2 x + \sin \frac{x}{2} + \cos \frac{x}{2} \) is
   (1) \( 4 + \sqrt{2} \) (2) \( 3 + \sqrt{2} \) (3) 9 (4) 4

4. \( \left(1 + \cos \frac{\pi}{8}\right)\left(1 + \cos \frac{3\pi}{8}\right)\left(1 + \cos \frac{5\pi}{8}\right)\left(1 + \cos \frac{7\pi}{8}\right) = \)
   (1) \( \frac{1}{8} \) (2) \( \frac{1}{2} \) (3) \( \frac{1}{\sqrt{3}} \) (4) \( \frac{1}{\sqrt{2}} \)

5. If \( \pi < 2\theta < \frac{3\pi}{2} \), then \( \sqrt{2 + \sqrt{2 + 2\cos 4\theta}} \) equals to
   (1) \( -2\cos \theta \) (2) \( -2\sin \theta \) (3) \( 2\cos \theta \) (4) \( 2\sin \theta \)

6. If \( \tan 40^\circ = \lambda \), then \( \frac{\tan 140^\circ - \tan 130^\circ}{1 + \tan 140^\circ \tan 130^\circ} = \)
   (1) \( \frac{1 - \lambda^2}{\lambda} \) (2) \( \frac{1 + \lambda^2}{\lambda} \) (3) \( \frac{1 + \lambda^2}{2\lambda} \) (4) \( \frac{1 - \lambda^2}{2\lambda} \)

7. \( \cos 1^\circ + \cos 2^\circ + \cos 3^\circ + \ldots + \cos 179^\circ = \)
   (1) 0 (2) 1 (3) -1 (4) 89

8. Let \( f_k(x) = \frac{1}{k}[\sin^k x + \cos^k x] \) where \( x \in \mathbb{R} \) and \( k \geq 1 \). Then \( f_4(x) - f_6(x) = \)
   (1) \( \frac{1}{4} \) (2) \( \frac{1}{12} \) (3) \( \frac{1}{6} \) (4) \( \frac{1}{3} \)

9. Which of the following is not true?
   (1) \( \sin \theta = -\frac{3}{4} \) (2) \( \cos \theta = -1 \) (3) \( \tan \theta = 25 \) (4) \( \sec \theta = \frac{1}{4} \)

10. \( \cos 2\theta \cos 2\phi + \sin^2(\theta - \phi) - \sin^2(\theta + \phi) \) is equal to
    (1) \( \sin 2(\theta + \phi) \) (2) \( \cos 2(\theta + \phi) \) (3) \( \sin 2(\theta - \phi) \) (4) \( \cos 2(\theta - \phi) \)

11. \( \frac{\sin(A - B)}{\cos A \cos B} + \frac{\sin(B - C)}{\cos B \cos C} + \frac{\sin(C - A)}{\cos C \cos A} \)
    (1) \( \sin A + \sin B + \sin C \) (2) 1 (3) 0 (4) \( \cos A + \cos B + \cos C \)

12. If \( \cos p\theta + \cos q\theta = 0 \) and if \( p \neq q \), then \( \theta \) is equal to (\( n \) is any integer)
    (1) \( \frac{\pi(3n + 1)}{p - q} \) (2) \( \frac{\pi(2n + 1)}{p \pm q} \) (3) \( \frac{\pi(n \pm 1)}{p \pm q} \) (4) \( \frac{\pi(n + 2)}{p + q} \)

13. If \( \tan \alpha \) and \( \tan \beta \) are the roots of \( x^2 + ax + b = 0 \), then \( \frac{\sin(\alpha + \beta)}{\sin \alpha \sin \beta} \) is equal to
    (1) \( \frac{b}{a} \) (2) \( \frac{a}{b} \) (3) \( -\frac{a}{b} \) (4) \( -\frac{b}{a} \)

14. In a triangle \( ABC \), \( \sin^2 A + \sin^2 B + \sin^2 C = 2 \), then the triangle is
    (1) equilateral triangle (2) isosceles triangle (3) right triangle (4) scalene triangle.

15. If \( f(\theta) = |\sin \theta| + |\cos \theta| \), \( \theta \in \mathbb{R} \), then \( f(\theta) \) is in the interval
    (1) \( [0, 2] \) (2) \( \left[1, \sqrt{2}\right] \) (3) \( [1, 2] \) (4) \( [0, 1] \)

16. \( \frac{\cos 6x + 6\cos 4x + 15\cos 2x + 10}{\cos 5x + 5\cos 3x + 10\cos x} \) is equal to
    (1) \( \cos 2x \) (2) \( \cos x \) (3) \( \cos 3x \) (4) \( 2\cos x \)
