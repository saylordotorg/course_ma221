**Unit 3: Higher-Order Linear ODEs** <span id="3"></span> 
*While one can always convert a higher-order ODE into a system of
first-order ODEs, this is not always the best approach toward solving
the ODE.  Homogeneous linear ODEs with constant coefficients are a
particularly easy-to-solve class of ODEs.  In order to find a solution
of an N<sup>th</sup>-order linear ODE with constant coefficients, you
need to find the roots of an N<sup>th</sup>-order polynomial.*  
  
 *Finding solutions is not quite as simple for the case of linear ODEs
with variable coefficients—that is, with coefficients that are functions
of the independent variable.  These ODEs are not generally solvable in
closed form, but methods for solving some special cases do exist.*  
  
 *The general solution to non-homogeneous linear ODEs is the addition of
the general solution of the related homogeneous ODE plus a particular
solution of the non-homogeneous ODE.  There are a number of approaches
to finding a particular solution, and we will sample several of the most
straightforward.  However, finding particular solutions is less a
process of following an algorithm than it is an art form.*  
  
 *You are already familiar with the idea that nearly any “well-behaved”
function can be approximated by a power series.  You can use this
concept to find solutions to a wide range of ODEs.  In most cases, the
solution itself is expressed as a power series, a fact that has led to
the development of an enormous field of applied mathematics known as
“special functions theory,” to which we will return later.  In this
unit, we will examine the solution of a specific example—Bessel’s
equation (which was actually introduced by Bernoulli!). *

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, the student should be able
to:  
-   Find the solution for second-order ordinary differential equations.
-   Find the solution for second-order ordinary differential equations
    within applications involving Newton’s law of motion.
-   Find the solution for second-order differential equations within
    applications involving spring-mass systems.
-   Find the solution for second-order ordinary differential equations
    within applications involving air resistance.
-   Find the solution for second-order ordinary differential equations
    within applications involving Schrödinger’s one-dimensional
    time-independent equation.
-   Find the solution for higher order differential equations.
-   Find the solution for homogeneous ordinary differential equations
    with constant coefficients.
-   Find the solution for homogeneous ordinary differential equations
    with variable coefficients.
-   Find the solution for Euler-Cauchy ordinary differential equations.
-   Find the particular solution for non-homogeneous ordinary
    differential equations.
-   Apply the use of linear differential operators within selected
    applications.
-   Find the solution for an ordinary differential equation by the
    method of undetermined coefficients.
-   Identify the trial functions which arise within solutions involving
    the method of undetermined coefficients.
-   Find the solution for an ordinary differential equation using the
    variation of parameters.
-   Distinguish between the use of the method of undetermined
    coefficients and variation of parameters to solve ordinary
    differential equations.
-   Find the solution for an ordinary differential equation using a
    method called the reduction of order.
-   Use a method called the reduction of order to convert an ordinary
    differential equation to another ordinary differential equation of
    lower order.
-   Find the solution for an ordinary differential equation using the
    method of inverse operators.
-   Identify the inverse operators which arise within solutions
    involving the method of inverse operators.
-   Find the power series solution for an ordinary differential
    equation.
-   Distinguish between a power series solution for an ordinary
    differential equation about an ordinary point and a singular point.
-   Find the solution for an ordinary differential equation using the
    Frobenius method.
-   Describe how the general solution depends upon the order of the
    Bessel equation.

**3.1 Examples of Second-Order Linear Differential Equations** <span
id="3.1"></span> 
**3.1.1 Newton’s Law of Motion** <span id="3.1.1"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Basic Concepts”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “[Basic
    Concepts](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)”
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read only the section titled “Differential
    Equation” on page 2.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: NYU: Mark Tuckerman’s: “G25.2600: Molecular Dynamics”:
    “Notes for Lecture 1”: “Newton’s Laws of Motion”**
    Link: NYU: Mark Tuckerman’s: “G25.2600: Molecular Dynamics”: “Notes
    for Lecture 1”: [“Newton’s Laws of
    Motion”](http://www.nyu.edu/classes/tuckerman/mol.dyn/lectures/lecture_1/node2.html#SECTION00011000000000000000)
    (HTML)  
        
     Instructions: Click on link above and read the notes included.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.2 Motion of a Mass on a Spring** <span id="3.1.2"></span> 
-   **Web Media: YouTube: Jason Gregersen’s “Modeling Spring Motion
    Using Differential Equations Part One”**
    Link: YouTube: Jason Gregersen’s [“Modeling Spring Motion Using
    Differential Equations Part
    One”](http://www.youtube.com/watch?v=JbwGlTz0wqk) (YouTube)  
        
     Instructions: Click on the link above to watch this video (5:11
    minutes), which models spring motion (assuming that there is no air
    resistance).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.3 Motion with Air Resistance** <span id="3.1.3"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Mechanical Vibrations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Mechanical
    Vibrations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Go to page 162 and read the section titled
    “Mechanical Vibrations,” (pages 162-164).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.4 One-Dimensional Time-Independent Schrödinger Equation** <span
id="3.1.4"></span> 
-   **Reading: Georgia Institute of Technology: C. David Sherrill’s A
    Brief Review of Elementary Quantum Chemistry: “The Schrödinger
    Equation”: “The Time-Independent Schrödinger Equation”**
    Link: Georgia Institute of Technology: C. David Sherrill’s *A Brief
    Review of Elementary Quantum Chemistry:* “The Schrödinger Equation”:
    [“The Time-Independent Schrödinger
    Equation”](http://vergil.chemistry.gatech.edu/notes/quantrev/node8.html)
    (HTML)  
        
     Instructions: Click on the link above and read the entire
    section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2 Higher Order Differential Equations** <span id="3.2"></span> 
-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2F. Linear Operators
    and Higher Order ODE’s”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”: “[2F. Linear Operators and Higher
    Order
    ODE’s](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above and go to page 6. 
    Work with exercise 2F-1 (items c, d, e, and f,); exercise 2F-2; and
    exercise 2F-3, item d.  When you finish, please check your answers
    with “[Section II
    Solutions](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf)”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.1 Homogeneous Linear ODEs with Constant Coefficients** <span
id="3.2.1"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Second Order Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Second Order Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Go to Page 104 and read the sections
    titled: “Basic Concepts,” “Real, Distinct Roots,” “Complex Roots,”
    and “Repeated Roots,” pages 104-121.  Then go to page 126 and read
    the sections titled “Fundamental Sets of Solutions” and “More on the
    Wronskian” (pages 126-136).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Higher Order
    Linear ODE’s”: “2.3 Higher Order Linear ODE’s”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “Higher Order
    Linear ODE’s”: [“2.3 Higher Order Linear
    ODE’s”](http://www.saylor.org/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 57.   Please read
    the section titled “2.3 Higher Order Linear ODE’s” (pages 57-60).  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).  

     

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: “Second Order
    (Homogeneous)”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: [“Second Order
    (Homogenous)”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Second Order (Homogeneous).”  Click on the
    corresponding link.  Go to page 5 and work on exercises 1 to 16 on
    pages 5 to 7.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2C. Second Order
    Linear ODE’s with Constant Coefficients”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”: “[2C. Second Order Linear ODE’s
    with Constant
    Coefficients](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above and go to page 3. 
    Work with exercises 2C-1 and 2C-2.  When you finish, please check
    your answers with “[Section II
    Solutions](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf)”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.2 Homogeneous Linear ODEs with Variable Coefficients** <span
id="3.2.2"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Reduction of Order”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Reduction of
    Order”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Go to page 122 and read the section titled
    “Reduction of Order” (pages 122-125).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Caltech: Sean Mauch’s Introduction to Methods of
    Applied Mathematics: “Ordinary Differential Equations”: “Chapter
    17”: “17.7 Additional Exercises”**
    Link: Caltech: Sean Mauch’s *Introduction to Methods of Applied
    Mathematics*: “[Ordinary Differential Equations”: “Chapter
    17”: “17.7 Additional
    Exercises](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Unit-3.2.2-intro-to-methods-of-applied-math-mauch-anti-copyright.pdf)” (PDF)  
        
     Instructions: Please click on the link above and go to page 955.
    Work on exercises 17.18, 17.19, 17.20, and 17.21.  After finishing
    each exercise, click on the “solution” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.3 Euler-Cauchy ODEs** <span id="3.2.3"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Series Solutions to Differential Equations”: “Euler Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Series Solutions to Differential Equations”: [“Euler
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Go to page 340 and read the section titled:
    “Euler Equations” (pages 340-344).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Activity: University of Hartford: Virginia Noonburg’s M344
    Advanced Engineering Mathematics: “Lecture 5”**
    Link: University of Hartford:  Virginia Noonburg’s M344 Advanced
    Engineering Mathematics: [“Lecture
    5”](http://uhaweb.hartford.edu/NOONBURG/) (PDF)  
        
     Instructioons: Click on the link above and scroll down until you
    see “M344 Advanced Engineering Math.”  Then click on the link titled
    “Lecture 5: Cauchy-Euler Equations, Method of Frobenius.”  Go to
    page 4 and look for “Practice Problems.”  Complete items a and b
    under problem 2 and then check for the answers.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Caltech: Sean Mauch’s Introduction to Methods of
    Applied Mathematics: “Ordinary Differential Equations”: “Chapter
    17”: “17.7 Additional Exercises”**
    Link: Caltech: Sean Mauch’s *Introduction to Methods of Applied
    Mathematics*: “Ordinary Differential Equations”: “Chapter 17”:
    [“17.7 Additional
    Exercises”](http://www.its.caltech.edu/~sean/book/unabridged.html)
    (PDF)  
        
     Instructions: Click on the link above. Click on “PDF (Portable
    Document Format).”  Go to page 953. Work on exercises 17.11, 17.12,
    17.13, and 17.14.  After finishing each exercise, click on the
    “solution” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4 Non-homogeneous Linear ODEs – Finding Particular Solutions**
<span id="3.2.4"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Nonhomogeneous Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Nonhomogeneous Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Nonhomogeneous
    Differential Equations” on pages 137-138.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4.1 Linear Differential Operators** <span id="3.2.4.1"></span> 
-   **Reading: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Notes”: “Linear Differential Operators”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Notes”: “[Linear Differential
    Operators](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Unit-3.2.4.1-Reading-Mattuck-Linear-Differential-Operators.pdf)”
    (PDF)  
        
     Instructions: Please click on the link above and read pages 1 to 5
    of  “Linear Differential Operators.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2F. Linear Operators
    and Higher Order ODE’s”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”:  “[2F. Linear Operators and
    Higher Order
    ODE’s](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above and go to page
    6. Work with exercise 2F-1 items “a” and “b”, and exercise 2F-3
    items “a” and “b”.   When you finish, please check your answers for
    these exercises with “[Section II
    Solutions](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf).”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4.2 Trial Solutions – Method of Undetermined Coefficients** <span
id="3.2.4.2"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Undetermined Coefficients”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Undetermined
    Coefficients”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Undetermined
    Coefficients” on pages 139-155.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Higher Order Differential Equations”: “Undetermined Coefficients”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Higher Order Differential Equations”: [“Undetermined
    Coefficients”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Undetermined
    Coefficients” on pages 355-356.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: Graham McDonald’s
    “Second Order (Inhomogeneous)”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: Graham McDonald’s
    [“Second Order
    (Inhomogenous)”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Second Order (Inhomogeneous).”  Click on
    the corresponding link.  Go to page 5 and work on exercises 1 to 13
    on pages 5 and 6.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solutions.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2C. Second Order
    Linear ODE’s with Constant Coefficients”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”: “[2C. Second Order Linear ODE’s
    with Constant
    Coefficients](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above and go to page
    3.  Work with exercises 2C-7 and 2C-8 on page 3.   When you finish,
    please check your answers for these exercises with “[Section II
    Solutions](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf).”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2F. Linear Operators
    and Higher Order ODE’s”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”:  “[2F. Linear Operators and
    Higher Order
    ODE’s](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above and go to page
    6. Work with exercise 2F-6.   When you finish, please check your
    answers to this exercise with “[Section II
    Solutions.](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf)”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4.3 Variation of Parameters** <span id="3.2.4.3"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Second Order Differential Equations”: “Variation of Parameters”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Second Order Differential Equations”: [“Variation of
    Parameters”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Variation of
    Parameters” on pages 156-161.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Higher Order Differential Equations”: “Variation of Parameters”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Higher Order Differential Equations”: [“Variation of
    Parameters”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled: “Variation of
    Parameters” on pages 357-362.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “Higher-Order ODE’s”: “2D. Variation of
    Parameters”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “Higher-Order ODE’s”: “[2D. Variation of
    Parameters](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF linked above and go to page
    4.  Work with exercises 2D-1 and 2D-2 on page 4.  When you finish,
    please check your answers to these exercises with “[Section II
    Solutions.”](http://www.saylor.org/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-Higer-Order-Linear-ODEs-Solutions.pdf)  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Caltech: Sean Mauch’s Introduction to Methods of
    Applied Mathematics: “Ordinary Differential Equations”: “Chapter
    21”: “21.10 Exercises”**
    Link: Caltech: Sean Mauch’s *Introduction to Methods of Applied
    Mathematics*: “Ordinary Differential Equations”: “Chapter 21”:
    [“21.10
    Exercises”](http://www.its.caltech.edu/~sean/book/unabridged.html)
    (PDF)  
        
     Instructions: Click on the link above.  Click on “PDF (Portable
    Document Format).”  Go to page 1117 and work on exercises 21.3,
    21.4, and 21.5.  After finishing each exercise, click on the
    “solution” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4.4 Reduction of Order** <span id="3.2.4.4"></span> 
-   **Reading: CliffsNotes: “Reduction of Order”**
    Link: CliffsNotes: [“Reduction of
    Order](http://www.cliffsnotes.com/math/differential-equations/second-order-equations/reduction-of-order)[”](http://www.cliffsnotes.com/math/differential-equations/second-order-equations/reduction-of-order)
    (HTML)  
        
     Instructions: Read this webpage.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Efunda’s “Higher Order Linear Differential Equations”:
    “Method of Reduction of Order”**
    Link: Efunda’s “Higher Order Linear Differential Equations”:
    “[Method of Reduction of
    Order](http://www.efunda.com/math/ode/linearode_reduceorder.cfm)”
    (HTML)  
        
     Instruction: Please click on the above link and read the entire
    article.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4.5 Method of Inverse Operators** <span id="3.2.4.5"></span> 
-   **Reading: Efunda’s “Higher Order Linear Differential Equations”:
    “Inverse Operators”**
    Link: Efunda’s “Higher Order Linear Differential Equations”:
    “[Inverse
    Operators](http://www.efunda.com/math/ode/linearode_invoperator.cfm)”
    (HTML)  
        
     Instruction: Please click on the above link and read the entire
    section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.3 Power Series Solutions of Linear Differential Equations** <span
id="3.3"></span> 
-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Power Series
    Methods”: “7.1 Power Series”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “Power Series
    Methods”: [“7.1 Power
    Series”](http://www.saylor.org/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](http://www.saylor.org/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
      
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 261.   Please read
    the section titled “7.1 Power Series”  
      on pages 261-268.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).  

     

**3.3.1 Power Series Solutions about an Ordinary Point** <span
id="3.3.1"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Series Solutions to Differential Equations”: “Series Solutions to
    Differential Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Series Solutions to Differential Equations”: [“Series Solutions to
    Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Series Solutions
    to Differential Equations” on pages 330-339.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Higher Order Differential Equations”: “Series Solutions”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Higher Order Differential Equations”: [“Series
    Solutions”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Series Solutions”
    on pages 370-373.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s *18.03 Notes and
    Exercises*: “Power Series: 6C. Solving Second-order ODE’s”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    [“Power Series: 6C. Solving Second-order
    ODE’s”](http://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/readings/notes_exe/MIT18_03S10_6ex.pdf)
    (PDF)  
        
     Instructions: Go to page 2 of the PDF. Do exercises 6C-2, 6C-3,
    6C-4, 6C-5, 6C-6 and 6C-7. When you finish, check your work with
    the [Solutions](http://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/readings/notes_exe/MIT18_03S10_6sol.pdf).  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.3.2 Singular Points: The Frobenius Method** <span
id="3.3.2"></span> 
-   **Reading: California State University, East Bay: Massoud Malek’s
    Differential Equations: “Series Solutions of Linear Differential
    Equations”**
    Link: California State University, East Bay: Massoud Malek’s
    *Differential Equations:* “[Series Solutions of Linear Differential
    Equations](http://www.mcs.csueastbay.edu/~malek/Class/)” (PDF)  
        
     Instructions: Click on the link above.  Scroll down until you find
    “Series Solutions of LDE.”  Click on that link and read the entire
    document.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Caltech: Sean Mauch’s Introduction to Methods of Applied
    Mathematics: “Ordinary Differential Equations”: “Chapter 23”: “23.2
    Regular Singular Points of Second Order Equations”**
    Link: Caltech: Sean Mauch’s *Introduction to Methods of Applied
    Mathematics*: “Ordinary Differential Equations”: “Chapter 23”:
    [“23.2 Regular Singular Points of Second Order
    Equations”](http://www.its.caltech.edu/~sean/book/unabridged.html)
    (PDF)  
        
     Instructions: Click on the link above and then click on “PDF
    (Portable Document Format).”  Go to page 1198.  Read the section
    titled “23.2 Regular Singular Points of Second Order Equations” on
    pages 1198-1215.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Caltech: Sean Mauch’s Introduction to Methods of
    Applied Mathematics: “Ordinary Differential Equations”: “Chapter
    23”: “23.5 Exercises”**
    Link: Caltech: Sean Mauch’s *Introduction to Methods of Applied
    Mathematics*: “Ordinary Differential Equations”: “Chapter 23”:
    [“23.5
    Exercises”](http://www.its.caltech.edu/~sean/book/unabridged.html)
    (PDF)  
        
     Instructions: Click on the link above and then click on “PDF
    (Portable Document Format).”  Go to page 1220 and work on exercises
    23.3, 23.5, 23.6,  and 23.7.  After finishing each exercise, click
    on the “solution” link.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.3.3 Bessel’s Equation** <span id="3.3.3"></span> 
-   **Reading: University of Hartford: Virginia Noonburg’s M344 Advanced
    Engineering Mathematics: “Lecture 6: Bessel’s Equation”**
    Link: University of Hartford:  Virginia Noonburg’s M344 Advanced
    Engineering Mathematics: [“Lecture 6: Bessel’s
    Equation”](http://uhaweb.hartford.edu/NOONBURG/) (PDF)  
        
     Instructions: Click on the link above and scroll down until you see
    “M344 Advanced Engineering Math.”  Under that title, click on the
    link that reads: “Lecture 6: Bessel’s Equation.”  Read the entire
    lecture.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Holon Institute of Technology: Professor Benzion
    Shklyar’s “Solution of Bessel Equation with v=1/3”**
    Link: Holon Institute of Technology: Professor Benzion Shklyar’s
    [“Solution of Bessel Equation with
    *v*=1/3”](http://www.hit.ac.il/ac/files/shk_b/Differential.Eqn.html)
    (PDF)  
        
     Instructions: Click on the link above and scroll down until you
    find “Bessel Equation.”  Under that title, click on the link for
    “Solution of Bessel Equation with *v*=1/3.”  Read the question and
    work on it on your own.  After you finish, look under the question
    for all the steps of the solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


