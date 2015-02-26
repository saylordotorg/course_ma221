---
layout: default
title: "MA221: Differential Equations"
course_description: "An introduction to the fundamentals behind numerical solutions and Ordinary Differential Equations, with a goal of moving from a microscopic view of relevant physics to a macroscopic view of the behavior of a system as a whole."
next: ../Unit01
previous: ../../../
---
Course Syllabus for "MA221: Differential Equations"
---------------------------------------------------

Differential equations are, in addition to a topic of study in
mathematics, the main language in which the laws and phenomena of
science are expressed. In basic terms, a differential equation is an
expression that describes how a system changes from one moment of time
to another, or from one point in space to another. When working with
differential equations, the ultimate goal is to move from a microscopic
view of relevant physics to a macroscopic view of the behavior of a
system as a whole. Let’s look at a simple differential equation. Based
on previous math and physics courses, you know that a car that is
constantly accelerating in the x-direction obeys the equation
d<sup>2</sup>x/dt<sup>2</sup> = a, where a is the applied acceleration.
This equation has two derivations with respect to time, so it is a
second-order differential equation; because it has derivations with
respect to only one variable (in this example, time), it is known as an 
ordinary differential equation, or an ODE. Let’s say that we want to
solve the above ODE for the position of the car as a function of time.
We can do so by using direct integration: the integration of both sides
with respect to time gives us dx/dt = at + c, where c is a constant of
integration. If the velocity of the car is known to be a particular
value at some point in time T, we can solve for c as c =
[dx/dt]<sub>t=T</sub> / aT. More simply, if the velocity is zero at time
0, then c = 0. Integrating again gives us the desired solution:  x(t) =
at<sup>2</sup>/2 + ct + e, where e is another constant of integration.
Again, if the position of the car at t=0 is taken to be zero, then the
solution for the position of the car becomes x(t) = at<sup>2</sup>/2. It
is useful to note that checking the validity of a solution to an ODE is
easily accomplished by substituting it back into the ODE. Unfortunately,
not all differential equations are this easy to solve. Generally, an ODE
is a functional relation (it would be a function, except that the
“variables” are themselves functions!) between an independent variable
t, a dependent function U(t), and some of its derivatives
d<sup>i</sup>U(t)/dt<sup>i</sup>.  An ODE is linear if it can be written
as a functional relation in which no powers of U or its derivatives
appear—otherwise, the ODE is nonlinear. For the most part, nonlinear
ODEs can only be solved numerically; this course will focus on linear
ODEs. This course will also introduce several other subclasses and their
respective properties. However, despite centuries of study, the only
practical approach to the solution of complicated ODEs that has emerged
is numerical approximation. Although these numerical techniques are the
subject of numerical analysis courses (see [MA213: Numerical
Analysis](http://www.saylor.org/courses/ma213/)), this course will
introduce you to the fundamentals behind numerical solutions. The
prerequisites for this course are
[MA101](http://www.saylor.org/courses/ma101/),
[MA102](http://www.saylor.org/courses/ma102/),
[MA103](http://www.saylor.org/courses/ma103/), and
[MA211](http://www.saylor.org/courses/ma211/). Considerable motivation
will be gained if [PHYS101](http://www.saylor.org/courses/phys101/) and
[PHYS102](http://www.saylor.org/courses/phys102/) are also taken as pre-
or co-requisites. This course will make use of a PDF text by Paul
Dawkins of Lamar University as its principal reading material. You may
wish to download this PDF at the outset of this course so that you have
it on hand throughout. You can find this file by clicking
[here](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1) and then
looking for the line that says “Here is the file you requested:
Differential Equations (Math 3301).”  Click on the link associated with
“Differential Equations (Math 3301).”

### Learning Outcomes

Upon successful completion of this course, you will be able to:  

-   identify ordinary differential equations and their respective
    orders;
-   explain and demonstrate how differential equations are used to model
    certain situations;
-   solve first order differential equations as well as initial value
    problems;
-   solve linear differential equations with constant coefficients;
-   use power series to find solutions of linear differential equations;
-   solve linear systems of differential equations with constant
    coefficients;
-   use the Laplace transform to solve initial value problems; and
-   use select methods of numerical approximation to find solutions to
    differential equations.

### Course Requirements

  
 In order to take this course you must:  
    
 √    Have access to a computer.  
    
 √    Have continuous broadband Internet access.  
    
 √    Have the ability/permission to install plug-ins or software (e.g.,
Adobe Reader or Flash).  
    
 √    Have the ability to download and save files and documents to a
computer.  
    
 √    Have the ability to open Microsoft files and documents (.doc,
.ppt, .xls, etc.).  
    
 √    Be competent in the English language.  
        

