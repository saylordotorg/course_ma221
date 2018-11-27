---
layout: default
title: "MA221: Differential Equations"
course_description: "An introduction to the fundamentals behind numerical solutions and Ordinary Differential Equations, with a goal of moving from a microscopic view of relevant physics to a macroscopic view of the behavior of a system as a whole."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Systems of Linear Differential Equations** <span
id="4"></span> 
*In the previous units, we worked with differential equations with one
unknown function.  However, some problems involve several functions that
depend on a single variable.  In these cases, a system of ordinary
differential equations can be created to model the problem. *  
  
 *The concept of the differential operator will help us develop
techniques for solving systems of linear ODEs.  Briefly, if we define
the differentiation operator D<sub>x</sub> = d/dx, so that
D<sub>x</sub>Y = dY/dx, a general linear ordinary differential equation
can be written as a polynomial in D<sub>x</sub>.  This allows us to form
an equivalence between a system of linear ODEs and a matrix equation,
which can then be solved as an eigenvalue problem using linear algebra. 
This is quite a boon, as most problems in linear algebra can indeed be
solved!*

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Find the solution for a system of ordinary differential equations.
-   Interpret the role of each differential equation within a system of
    ordinary differential equations in modeling a selected application.
-   Create a system of ordinary differential equations to model a
    selected application.
-   Find the solution for a system of ordinary differential equations
    within applications involving spring-mass dynamics.
-   Describe all components of the differential equation used within the
    predator-prey model.
-   Describe all components of the differential equation used to
    describe the double pendulum.
-   Distinguish between the usage of existence and uniqueness theorems
    to support claims which arise within selected applications.
-   Convert an nth order ordinary differential equation into an
    n-dimensional system of first order ordinary differential equations.
-   Apply selected linear algebra-based methods to find the solution for
    the systems of linear ordinary differential equations.

**4.1 Examples of Systems of ODEs** <span id="4.1"></span> 
**4.1.1 Mass and Spring Systems** <span id="4.1.1"></span> 
-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Systems of
    ODEs”: “3.1 Introduction to Systems of ODEs”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “Systems of ODEs”:
    [“3.1 Introduction to Systems of
    ODEs”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 85 and read the
    section titled “3.1 Introduction to Systems of ODEs” on pages
    85-88.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).  

     

**4.1.2 The Predator-Prey Model** <span id="4.1.2"></span> 
-   **Reading: Scholarpedia.org: Frank Hoppensteadt’s “Predator-Prey
    Model”**
    Link: Scholarpedia.org: Frank Hoppensteadt’s “[Predator-Prey
    Model](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-4.1.2.pdf)”
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-4.1.2-Frank-Hoppensteadts.epub)  
      
     Instructions: Click on the link above and read the entire
    article.  
      
     Terms of Use: The linked material above has been reposted with the
    kind permission of Frank Hoppensteadts, and can be viewed in its
    original form
    [here](http://www.scholarpedia.org/article/Predator-prey_model).
     Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**4.1.3 The Double Pendulum** <span id="4.1.3"></span> 
-   **Reading: The MathWorks: Cleve Moler’s Numerical Computing with
    MATLAB: “Ordinary Differential Equations”**
    Link: The MathWorks: Cleve Moler’s Numerical Computing with MATLAB:
    “[Ordinary Differential
    Equations](http://www.mathworks.com/moler/chapters.html)” (PDF)  
        
     Instructions: Click on the link above.  Click on the link “Ordinary
    Differential Equations (53 pages).”  Go to page 49 and read the item
    numbered “7.23.”  Read only up to page 50.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2 Existence and Uniqueness Theorems** <span id="4.2"></span> 
-   **Reading: Michigan State University: Sheldon Newhouse’s Math 235
    Lecture Notes: “16. Systems of Differential Equations”**
    Link: Michigan State University: Sheldon Newhouse’s Math 235 Lecture
    Notes: “[16. Systems of Differential
    Equations](http://www.mth.msu.edu/~sen/Math_235/)” (PDF)  
        
     Instructions: Click on the link above, scroll down, and, under the
    title “Lecture Notes,” click on the link for “16. Systems of
    Differential Equations.”  Go to page 5.  Read the section titled “2
    Systems of Differential Equations” on pages 5-11.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Systems of
    ODEs”: “3.3 Linear Systems of ODEs”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “Systems of ODEs”:
    [“3.3 Linear Systems of
    ODEs”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 99.   Please read
    the section titled “3.3 Linear Systems of ODEs” on pages 99-102.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).  

     

**4.3 Conversion to Systems of First-Order ODEs** <span
id="4.3"></span> 
-   **Reading: Wikipedia’s Ordinary Differential Equation: “Reduction to
    a First Order System”**
    Link: Wikipedia’s Ordinary Differential Equation: “[Reduction to a
    First Order
    System](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-4.3.pdf)”
    (PDF)  
        
     Instructions: Click on the link above.  Read the sections titled:
    “Reduction to a First Order System” and “Linear Ordinary
    Differential Equations.”  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to Wikipedia, and the original version can be
    found [here](http://en.wikipedia.org/wiki/Ordinary_differential_equation#Reduction_to_a_first_order_system) (HTML).

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Linear Systems”: “4B. General Systems;
    Elimination; Using Matrices”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Linear Systems”: “[4B. General Systems; Elimination;
    Using
    Matrices](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Questions.pdf)”
    (PDF)  
                                                       
     Instructions: Please click on the PDF linked above. Work with
    exercises 4B-1 and 4B-2 on page 1.   When you finish, please check
    your answers to these exercises with “[Linear Systems
    Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Solutions.pdf).”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.4 Linear Algebra-Based Solutions of Systems of Linear ODEs** <span
id="4.4"></span> 
-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Systems of
    ODEs”: “3.4 Eingenvalue Method”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “Systems of ODEs”:
    [“3.4 Eingenvalue
    Method”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 99.   Please read
    the section titled “3.4 Eingenvalue Method” on pages 103-109.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Linear Systems”: “4B. General Systems;
    Elimination; Using Matrices”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Linear Systems”: “[4B. General Systems; Elimination;
    Using
    Matrices](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above. Work with
    exercises 4B-4, 4B-5, and 4B-6 on pages 1 and 2.   When you finish,
    please check your answers for these exercises with “[Linear Systems
    Solutions.”](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Solutions.pdf)  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Arthur Mattuck’s 18.03 Notes and Exercises:
    “Exercises”: “Linear Systems”: “4C. Eingenvalues and Eigenvectors”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Linear Systems”: “[4C. Eingenvalues and
    Eigenvectors](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Questions.pdf)”
    (PDF)  
        
     Instructions: Click on the PDF linked above and go to page 2.  Work
    with exercises 4C-1 and 4C-5.   When you finish, please check your
    answers to these exercises with “[Linear Systems
    Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Solutions.pdf).”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Linear Systems”: “4D. Complex and Repeated
    Eingenvalues”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Linear Systems”: “[4D. Complex and Repeated
    Eingenvalues](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above, and go to page
    3.  Work with exercises 4D-1, 4D-2, and 4D-3.   When you finish,
    please check your answers to these exercises with “[Linear Systems
    Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Solutions.pdf).”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Systems of Differential Equations”: “Nonhomogeneous Systems”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Systems of Differential Equations”: [“Nonhomogeneous
    Systems”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Go to Page 303 and read the section titled
    “Nonhomogeneous Systems” on pages 303-306.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Linear Systems”: “4I. Inhomogeneous
    Systems”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Linear Systems”: “[4I. Inhomogeneous
    Systems](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above and go to page
    6.  Work with exercises 4I-1, 4I-2, 4I-3, 4I-4, and 4I-5.   When you
    finish, please check your answers to these exercises with “[Linear
    Systems
    Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Linear-Systems-Solutions.pdf).”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


