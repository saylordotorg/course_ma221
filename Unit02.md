---
layout: default
title: "MA221: Differential Equations"
course_description: "An introduction to the fundamentals behind numerical solutions and Ordinary Differential Equations, with a goal of moving from a microscopic view of relevant physics to a macroscopic view of the behavior of a system as a whole."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: First Order ODEs** <span id="2"></span> 
*In this unit, we examine the simplest class of ODEs: the linear
first-order ODEs.  There are at least three reasons for starting here. 
First, these are the simplest ODEs that exist.  Second, they obey rather
general existence and uniqueness theorems—that is, you can be determine
whether a solution can be obtained, and can ensure that there is only
one solution.  Finally, any n<sup>th</sup> order linear ODE can be
converted into a system of n first-order ODEs.  This is why the theory
of first-order ODEs serves as a foundation for the entire field.*

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student should be able
to:  
-   Find the solution for first-order ordinary differential equations.
-   Find the solution for first-order ordinary differential equations
    within applications involving radioactive decay.
-   Find the solution for first-order ordinary differential equations
    within applications involving the discharge of a capacitor.
-   Find the solution for first-order differential equations within
    applications involving atmospheric pressure.
-   Rewrite an Nth-order ordinary differential equation as a system of N
    first-order ordinary differential equations.
-   Determine the existence of a solution for a first-order ordinary
    differential equation using Picard’s Existence Theorem.
-   Analyze directional fields and trajectories to evaluate the
    qualitative behavior of solutions to selected ordinary differential
    equations.
-   Define linear ordinary differential equations.
-   Distinguish linear ordinary differential equations from nonlinear
    ordinary differential equations.
-   Find the solution for an exact ordinary differential equation.
-   Find the solution for separable ordinary differential equations.
-   Find the solution for Bernoulli differential equations.
-   Find the solution for homogeneous ordinary differential equations.

**2.1 Examples of First-order ODEs** <span id="2.1"></span> 
**2.1.1 Radioactive Decay** <span id="2.1.1"></span> 
-   **Reading: University of British Columbia: Leah Keshet’s Math 102
    Course Notes: “Chapter 9”**
    Link: University of British Columbia: Leah Keshet’s *Math 102 Course
    Notes*: [“Chapter
    9”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-2.1.1.pdf)
    (PDF)  
        
     Instructions: Click on the link above, then click on the link for
    “9. Exponential Growth and Decay: Differential Equations.”  Go to
    page 11.  Please read sections 9.9 and 9.10 on pages 11 and 12.  
      
     Terms of Use: The linked material above has been reposted with the
    kind permission of Leah Keshet.  Please note that this material is
    under copyright and cannot be reproduced in any capacity without
    explicit permission from the copyright holder.

-   **Reading: San Diego State University: Joseph M. Mahaffy’s Linear
    Differential Equations**
    Link: San Diego State University: Joseph M. Mahaffy’s *[Linear
    Differential
    Equations](http://www-rohan.sdsu.edu/~jmahaffy/courses/f00/math536/dynamic/linde/linde536.htm) *(HTML)  
        
     Instructions: Click on the link above and read the sections titled:
    “Introduction,” “Malthusian Growth,” and “Radioactive Decay.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Richard Williamson’s Introduction to Differential
    Equations and Dynamical Systems: “Supplementary Applications”:
    “Radioactive Decay”**
    Link: Richard Williamson’s *Introduction to Differential Equations
    and Dynamical Systems: *“Supplementary Applications”: [“Radioactive
    Decay”](http://www.mhhe.com/math/advmath/williamson/student/supp_apps.mhtml)
    (HTML)  
        
     Instructions: Click on the link above, then click on “1.
    Radioactive Decay (Chapter 2).” Read the entire section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1.2 Discharge of a Capacitor** <span id="2.1.2"></span> 
-   **Reading: Georgia State University: Department of Physics and
    Astronomy’s Hyperphysics: “Capacitor Discharge”**
    Link: Georgia State University: Department of Physics and
    Astronomy’s Hyperphysics: “[Capacitor
    Discharge](http://hyperphysics.phy-astr.gsu.edu/hbase/math/deinhom.html#c2)”
    (HTML)  
        
     Instructions: Click on the link above and the scroll down to the
    section titled: “Capacitor Discharge.”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1.3 Atmospheric Pressure** <span id="2.1.3"></span> 
-   **Reading: Home Climate Analysis Blog’s “Atmospheric Pressure”**
    Link: Home Climate Analysis Blog’s “[Atmospheric
    Pressure](http://homeclimateanalysis.blogspot.com/2010/03/atmospheric-pressure.html)”
    (HTML)  
        
     Instructions: Click on the link above and read the entire
    document.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Clinton Community College: Elizabeth Wood’s Math 155
    Supplemental Notes 5: “Growth and Decay”**
    Link: Clinton Community College: Elizabeth Wood’s *Math 155
    Supplemental Notes 5*: “[Growth and
    Decay](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA121-2.1.3.pdf)”
    (PDF)  
        
     Instructions: Read from the beginning to the end of “Example 1.”  
      
     Terms of Use: The linked material above had been reposted with the
    kind permission of Elizabeth Wood, and can be viewed in its original
    form
    [here](http://faculty.eicc.edu/bwood/ma155supplemental/supplemental5.htm).
     Please note that this material is under copyright and cannot be
    reproduced in any capacity without explicit permission from the
    copyright holder.

**2.2 All Nth-order ODEs Are Systems of N First-order ODEs** <span
id="2.2"></span> 
-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Chapter 3”:
    “3.1 Introduction to Systems of ODEs”**
    Link: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Chapter 3”: [“3.1
    Introduction to Systems of ODEs
    “](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    titled “Download the book as PDF.” Go to page 85 and read only pages
    85-88 from section 3.1.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/diffyqs/) (PDF).

**2.3 Picard’s Existence Theorem for First Order ODEs** <span
id="2.3"></span> 
-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Chapter 1”:
    “First Order ODE’s”**
    Link: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “Chapter 1”: [“First
    Order
    ODE’s”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 13.   Please read
    sections 1.1 and 1.2 from pages 13 to 21.  Note that section 1.2.1
    will also cover subunit 2.4 below.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/diffyqs/) (PDF)  

     

-   **Reading: SOS Math: “Existence and Uniqueness of Solution”**

    Link: SOS Math: “[Existence and Uniqueness of
    Solution](http://www.sosmath.com/diffeq/first/existence/existence.html)”
    (HTML)  
        
     Instructions: Click on the link above and read the entire
    section.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: SOS Math: “Picard Iterative Process”**
    Link: SOS Math: “[Picard Iterative
    Process](http://www.sosmath.com/diffeq/first/picard/picard.html)”
    (HTML)  
        
     Instructions: Click on the link above and read the entire
    section.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.4 Direction Fields and Trajectories as Solutions** <span
id="2.4"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “Basic Concepts”: “Direction Fields”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “Basic Concepts”: [“Direction
    Fields”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Please read the entire section titled
    “Direction Fields” on pages 8 to 18.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “First Order
    ODE’s”: “1.2 Slopes Field”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “First Order
    ODE’s”: [“1.2 Slopes
    Field”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
      
     Instructions: Click on the link above and then click on the link
    that says “Download the book as PDF.”  Go to page 18.  Read section
    1.2 up to the end of subsection 1.2.1 on pages 18 and 19.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/diffyqs/) (PDF).  

     

-   **Reading: MIT: Professor Arthur Mattuck’s *18.03 Differential
    Equations*: Notes and Exercises: “Graphical and Numerical Methods”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Differential
    Equations:* Notes and Exercises: [“Graphical and Numerical
    Methods”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Unit-2.4-Reading-Miller-Notes-Graphical-and-Numerical-Methods.pdf)
    (PDF)  
        
     Instructions: Read the first two pages (Pages 0 and 1) of these
    notes, up to the end of the section titled “1. Graphical Methods.”  
        
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

-   **Assessment: MIT: Professor Arthur Mattuck’s *18.03 Differential
    Equations*: Notes and Exercises: “First Order ODE’s”: “1C. Graphical
    and Numerical Methods”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Differential
    Equations:* Notes and Exercises: “First Order ODE’s”: [“1C.
    Graphical and Numerical
    Methods”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2014/04/MA221-Assessments-Mattuck-First-Order-ODEs.pdf)
    (PDF)  
        
     Instructions: Work through all items in exercise 1C-1 on pages 3
    and 4 of the document.  When you finish, check your work with the
    answers in [“Section 1
    Solutions”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf),
    starting on page 9.   
      
     Terms of Use: Terms of Use: This resource is licensed under a
    [Creative Commons Attribution-NonCommercial-ShareAlike 3.0
    License](http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

**2.5 Linear ODEs** <span id="2.5"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “First Order Differential Equations”: “Linear Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “First Order Differential Equations”: [“Linear Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Linear
    Differential Equations” on pages 21 to 33.  Try to work through the
    examples by yourself first and then read through the text to check
    your work.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “First Order
    ODE’s”: “1.4 Linear Equations and the Integrating Factor”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “First Order
    ODE’s”: [“1.4 Linear Equations and the Integrating
    Factor”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and the click on the link
    that says “Download the book as PDF.”  Go to page 27.   Please read
    the section titled “1.4 Linear Equations and the Integrating Factor”
    on pages 27 to 30.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl and the original version can be found
    [here](http://www.jirka.org/diffyqs/) (PDF).<span
    class="Apple-style-span"
    style="font-family: arial; font-size: small; color: rgb(0, 0, 0); "><span
    style="color: rgb(34, 34, 34); font-family: Arial, Verdana, sans-serif; font-size: 12px; "><span
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); "> </span></span></span>

     

-   **Reading: Furman University: Dan Sloughter’s Difference Equations
    to Differential Equations: “Chapter 8: Differential Equations”:
    “Section 8.3: First Order Differential Equations”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations: *“Chapter 8: Differential Equations”:
    [“Section 8.3: First Order Differential
    Equations”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-2.5-8.3.pdf)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to “Chapter 8:
    Differential Equations.” Under that title, click on the link for
    “First Order Linear Differential Equations.”  Read the entire
    section.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec83.pdf) (PDF).  

     

-   **Assessment: Furman University: Dan Sloughter’s Difference
    Equations to Differential Equations: “Chapter 8: Differential
    Equations”: “Section 8.3: First Order Differential Equations:
    “Problems”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations:*“Chapter 8: Differential Equations”:
    “Section 8.3: First Order Differential Equations”:
    [“Problems”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-2.5-8.3.pdf)
    (PDF)  
        
     Instructions: Click on the link above and scroll down to “Chapter
    8: Differential Equations.”  Then click on the link for “First Order
    Linear Differential Equations.”  Go to page 5 and work with
    problems: 1-a, c, d; 2-a; 3-b, c, d; 5-b; 6-b, c.  After you finish,
    click here for the
    [solutions](http://de2de.wordpress.com/2007/08/21/section-83/).  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec83.pdf) (PDF).  

     

-   **Assessment: Carleton University: A. Mingarelli’s Calculus:
    “Functions and Their properties”: “Exercises: Differential
    Equations”**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.6 Exact ODEs and Integrating Factors** <span id="2.6"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “First Order Differential Equations”: “Exact Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “First Order Differential Equations”: [“Exact Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Please read the section titled: “Exact
    Differential Equations” on pages 45 to 55.  Try to solve examples 2,
    3, 4 and 5 on your own before reading the solution explained in the
    reading.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Cliff Notes: *Differential Equations*: “Integrating
    Factors”**
    Link: Cliff Notes: *Differential Equations*: [“Integrating
    Factors”](http://www.cliffsnotes.com/math/differential-equations/first-order-equations/integrating-factors)
    (HTML)  
        
     Instructions: Click on the link above and read this article.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Efunda’s “Exact First Order Differential Equations”**
    Link: Efunda’s [“Exact First Order Differential
    Equations”](http://www.efunda.com/math/ode/ode1_exact.cfm) (HTML)  
        
     Instructions: Click on the link above and read the entire page.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “First Order ODE’s”: “1B. Standard
    First-Order Methods”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “First Order ODE’s”: “[1B. Standard First-Order
    Methods](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf)”
    (PDF)  
        
     Instructions: Please, click on the PDF link above.  Work with all
    items in exercise 1B-1 and 1B-2 on page 1.  When you are finished,
    please compare your answers for these exercises with “[Section 1
    Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf)”.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: “Exact
    Equations”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: [“Exact
    Equations”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Exact Differential Equations.”  Click on
    the corresponding link.  Go to page 4 and work on exercises 1 to 11
    on pages 4 to 6.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.7 Separable ODEs** <span id="2.7"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “First Order Differential Equations”: “Separable Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “First Order Differential Equations”: [“Separable Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Separable
    Differential Equations” on pages 34 to 44.  Try to solve examples 3,
    4, 5, and 6 on your own.  After finishing, check your work against
    the solution provided by the text.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Furman University: Dan Sloughter’s Difference Equations
    to Differential Equations: “Chapter 8: Differential Equations”:
    “Section 8.2: Separation of Variables”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations:*“Chapter 8: Differential Equations”:
    [“Section 8.2: Separation of
    Variables”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-2.7.pdf)
    (PDF)  
        
     Instructions: Click on the link above, scroll down to “Chapter 8:
    Differential Equations.”  Click on the link for “Separation of
    Variables.”  Read the entire section.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec82.pdf) (PDF).  

     

-   **Assessment: Furman University: Dan Sloughter’s Difference
    Equations to Differential Equations: “Chapter 8: Differential
    Equations”: “Section 8.2: Separation of Variables: Problems”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations:*“Chapter 8: Differential Equations”:
    “Section 8.2: Separation of Variables”:
    [“Problems”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-2.7.pdf)
    (PDF)  
        
     Instructions: Click on the link above and scroll down to “Chapter
    8: Differential Equations.”  Click on the link for “Separation of
    Variables.”  Go to page 7 and work through the following problems:
    1-a, 1-c, 1-e, 1-g, 2-a, 2-c, 3-a, 4-a, 4-c, 4-e, and 5-b.  After
    you finish, check your work against the solutions provided
    [here](http://de2de.wordpress.com/2007/08/20/section-82/).  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec82.pdf) (PDF).  

     

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: “Separation of
    Variables”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: [“Separation of
    Variables”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Separation of Variables.”  Click on the
    corresponding link.  Go to page 4 and work on exercises 1 to 16 on
    pages 4 to 8.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “First Order ODE’s”: “1A. Introduction;
    Separation of Variables”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “First Order ODE’s”: “[1A. Introduction; Separation of
    Variables](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on the PDF above. Work through all items
    in exercises 1A-3, 1A-4, and 1A-5 on page 1.  When you finish please
    check your answers for these exercises against “[Section 1
    Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf)” 

**2.8 Bernoulli Equations** <span id="2.8"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “First Order Differential Equations”: “Bernoulli Differential
    Equations”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “First Order Differential Equations”: [“Bernoulli Differential
    Equations”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Bernoulli
    Differential Equations” on pages 56 to 62.  Try to work through
    examples 2, 3, and 4 on your own before reading through the text.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Jirka.org: Jiri Lebl’s Notes on Diffy Qs: “First Order
    ODE’s”: “1.5 Substitution”: “1.5.2 Bernoulli Equations”**
    Link: Jirka.org: Jiri Lebl’s *Notes on Diffy Qs*: “First Order
    ODE’s”: “1.5 Substitution”: [“1.5.2 Bernoulli
    Equations”](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/06/MA221-book.pdf)
    (PDF)  
        
     Also available in:  
     [HTML](http://www.jirka.org/diffyqs/htmlver/diffyqs.html)  

    [EPUB](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2011/08/MA221-book-Notes-on-Diffy-Qs-Jiri-Lebl.epub)  
        
     Instructions: Click on the link above and then click on the link
    titled “Download the book as PDF.”  Go to page 33.   Please read the
    section titled: “1.5.2 Bernoulli Equations” on pages 33 and 34.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/us/) (HTML).
     It is attributed to Jiri Lebl, and the original version can be
    found [here](http://www.jirka.org/diffyqs/) (PDF).<span
    class="Apple-style-span"
    style="font-family: arial; font-size: small; color: rgb(0, 0, 0); "><span
    style="color: rgb(34, 34, 34); font-family: Arial, Verdana, sans-serif; font-size: 12px; "><span
    style="font-family: Arial, 'Helvetica Neue', 'Liberation Sans', FreeSans, sans-serif; font-size: 13px; line-height: 22px; color: rgb(0, 0, 0); "> </span></span></span>

     

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “First Order ODE’s”: “1B. Standard
    First-Order Methods”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “First Order ODE’s”: “[1B. Standard First-Order
    Methods](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Click on the link above and then scroll down to the
    section titled “Exercises.”  Click on the PDF link for “1.
    First-order ODE’s.”  Work with the two items in exercise 1B-9 on
    page 2.  When you finish, please compare your answers to these
    exercises with “[Section 1
    Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf)”  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: “Bernoulli
    Equations”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: [“Bernoulli
    Equations”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Bernoulli Equations.”  Click on the
    corresponding link.  Go to page 4 and work on exercises 1 to 9 on
    pages 4 to 6.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.9 Homogeneous ODEs** <span id="2.9"></span> 
-   **Reading: Lamar University: Paul Dawkins’ Differential Equations:
    “First Order Differential Equations”: “Substitutions”**
    Link: Lamar University: Paul Dawkins’ *Differential Equations*:
    “First Order Differential Equations”:
    [“Substitutions”](http://tutorial.math.lamar.edu/download.aspx?PDF=B,1;1)
    (PDF)  
        
     Instructions: Click on the link above and then look for the line
    that says “Here is the file you requested: Differential Equations
    (Math 3301).”  Click on the link associated with “Differential
    Equations (Math 3301).”  Read the section titled “Substitutions” on
    pages 63 to 67, up to the end of the example 2.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Web Media: Khan Academy: “First Order Homogeneous Equations”**
    Link:  Khan Academy: “[First Order Homogeneous
    Equations](https://www.khanacademy.org/math/differential-equations/first-order-differential-equations/homogeneous-equations/v/first-order-homegenous-equations)”
     (YouTube)  
      
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/us/podcast/first-order-homegenous-equations/id391036091?i=86817950)  
      
     Instrucitons: Please watch the lecture, which is about first order
    homogenous equations.   
      
     Watching this lecture should take approximately 10 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to the Khan Academy.  
      

-   **Web Media: Khan Academy: “First Order Homogeneous Equations 2”**
    Link:  Khan Academy: “[First Order Homogeneous Equations
    2](https://www.khanacademy.org/math/differential-equations/first-order-differential-equations/homogeneous-equations/v/first-order-homogenous-equations-2)”
    (YouTube)  
      
     Also available in:  
     [iTunes
    U](http://itunes.apple.com/us/podcast/first-order-homogenous-equations/id391036091?i=86817928)  
        
     Instrucitons: Please watch the lecture, which is about first order
    homogenous equations.   
      
     Watching this lecture should take approximately 10 minutes.  
      
     Terms of Use: This resource is licensed under a [Creative Commons
    Attribution-NonCommercial-NoDerivs 3.0 Unported
    License](http://creativecommons.org/licenses/by-nc-nd/3.0/). It is
    attributed to the Khan Academy.

-   **Assessment: MIT: Professor Arthur Mattuck’s 18.03 Notes and
    Exercises: “Exercises”: “First Order ODE’s”: “1B. Standard
    First-Order Methods”**
    Link: MIT: Professor Arthur Mattuck’s *18.03 Notes and Exercises*:
    “Exercises”: “First Order ODE’s”: “[1B. Standard First-Order
    Methods](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Questions.pdf)”
    (PDF)  
        
     Instructions: Please click on above PDF link. Work with all the
    items in exercise 1B-3 on page 2.  When you finish, please check
    your answers for these exercises with “[Section 1
    Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/07/MA221-Assessments-Mattuck-First-Order-ODEs-Solutionspdf.pdf).”   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: “Homogeneous
    Functions”**
    Link: University of Salford: “Mathematics Hyper-Tutorials”:
    “Ordinary Differential Equations Math Tutorials”: [“Homogeneous
    Functions”](http://www.cse.salford.ac.uk/profiles/gsmcdonald/PPLATO.php#MTODEs)
    (PDF)  
        
     Instructions: Click on the link above, then scroll down until you
    find the tutorial titled “Homogeneous Functions.”  Click on the
    corresponding link.  Go to page 5 and work on exercises 1 to 11 on
    pages 5 to 8.  After finishing each exercise, click on the
    “EXERCISE” link for full worked solution.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


