---
layout: default
title: "MA221: Differential Equations"
course_description: "An introduction to the fundamentals behind numerical solutions and Ordinary Differential Equations, with a goal of moving from a microscopic view of relevant physics to a macroscopic view of the behavior of a system as a whole."
next: ../Unit07
previous: ../Unit05
---
**Unit 6: Numerical Methods** <span id="6"></span> 
*Until now, we have studied particular kinds of equations for which we
have methods to find analytical solutions.  In most cases, however, it
is impossible to find such solutions, and we must accordingly rely on
methods of numerical approximation. *  
  
 *Reasonably enough, the technique for obtaining a solution for an ODE
that can be written as a system of first-order ODEs is numerical
integration.  Roughly speaking, the value for the derivative of the
desired solution is numerically integrated in order to obtain a solution
to the ODE.   As numerical integration is a rather stable process
(meaning that the result can be made arbitrarily close to the value of
the actual integral), automated solver programs can numerically
integrate a wide range of ODEs.  Note that nonlinear ODEs can be solved
by numerical integration!  Despite the scope of numerical methods,
however, it is important to appreciate their limitations.*

**Unit6 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Find the approximate solution for an ordinary differential equation
    using Verlet integration.
-   Find the approximate solution for an ordinary differential equation
    using Predictor-Corrector methods.
-   Find the approximate solution for an ordinary differential equation
    using the Runge-Kutta methods.
-   Find the approximate solution for an ordinary differential equation
    using the Adams-Bashforth and Adams-Moulton methods.

**6.1 Verlet Integration** <span id="6.1"></span> 
-   **Reading: Wikipedia’s “Verlet Integration”**
    Link: Wikipedia’s “[Verlet
    Integration](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-6.1.pdf)”
    (PDF)  
        
     Instructions: Click on the link above and read the entire
    article.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to Wikipedia, and the original version can be
    found [here](http://en.wikipedia.org/wiki/Verlet_integration) (HTML).

**6.2 Predictor-Corrector Methods** <span id="6.2"></span> 
-   **Reading: Wikipedia’s “Predictor-Corrector Method”**
    Link: Wikipedia’s “[Predictor-Corrector
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-6.2.pdf)”
    (PDF)  
        
     Instructions: Click on the link above and read the entire
    article.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It is
    attributed to Wikipedia, and the original version can be
    found [here](http://en.wikipedia.org/wiki/Predictor-corrector_method) (HTML).

**6.3 Runge-Kutta Methods** <span id="6.3"></span> 
-   **Reading: MIT: “Honors Differential Equations”: Ernest Ngaruiya’s
    “Numerical Approximations in Differential Equations: The Runge-Kutta
    Method”**
    Link: MIT: “Honors Differential Equations”: Ernest Ngaruiya’s
    “[Numerical Approximations in Differential Equations: The
    Runge-Kutta
    Method](http://search.mit.edu/search?site=ocw&client=mit&getfields=*&output=xml_no_dtd&proxystylesheet=http%3A%2F%2Focw.mit.edu%2Fsearch%2Fgoogle-ocw.xsl&proxyreload=1&as_dt=i&oe=utf-8&departmentName=web&filter=0&courseName=&q=Runge-Kutta&btnG.x=7&btnG.y=12)”
    (PDF)  
        
     Instructions: Click on the link above.  Scroll down and click on
    the link for “18034 Honors Differential Equations.”  Read the entire
    paper.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Reading: Furman University: Dan Sloughter’s Difference Equations
    to Differential Equations: “Chapter 8: Differential Equations”:
    “Section 8.1: Numerical Solutions of Differential Equations”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations: *“Chapter 8: Differential Equations”:
    [“Section 8.1: Numerical Solutions of Differential
    Equations”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-6.3.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-6.3-Dan-Sloughter.epub)  
      
     Instructions: Click on the link above and scroll down to “Chapter
    8: Differential Equations.”  Then click on the link for “Numerical
    Solutions of Differential Equations” and read the entire section.  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec81.pdf) (PDF).  

     

-   **Reading: Furman University: Dan Sloughter’s Difference Equations
    to Differential Equations: “Chapter 8: Differential Equations”:
    “Section 8.1: Numerical Solutions of Differential Equations”:
    “Problems”**
    Link: Furman University: Dan Sloughter’s *Difference Equations to
    Differential Equations:*“Chapter 8: Differential Equations”:
    “Section 8.1: Numerical Solutions of Differential Equations”:
    [“Problems”](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-6.3.pdf)
    (PDF)  
        
     Also available in:  

    [EPUB](https://resources.saylor.org/archived/wp-content/uploads/2011/08/MA221-6.3-Dan-Sloughter.epub)  
      
     Instructions: Click on the link above and scroll down to “Chapter
    8: Differential Equations.”  Then click on the link for “Numerical
    Solutions of Differential Equations.”    Go to page 10 and work with
    problems: 4-a, c, e, g; 5-a, c, e, g; 7-b, c, d; 9-b, c, d.  After
    you finish, check your work against the solutions provided
    [here](http://de2de.wordpress.com/2007/08/20/section-81/).  
      
     Terms of Use: The work above is released under a [Creative Commons
    Attribution-Share-Alike License
    1.0](http://creativecommons.org/licenses/by-nc-sa/1.0/) (HTML).  It
    is attributed to Dan Sloughter, and the original version can be
    found [here](http://de2de.synechism.org/c8/sec81.pdf) (PDF).<span
    class="Apple-style-span"
    style="color: rgb(0, 0, 0); font-family: arial, sans, sans-serif; font-size: 13px; white-space: pre; ">
    </span>

**6.4 Adams-Bashforth and Adams-Moulton Methods** <span
id="6.4"></span> 
-   **Reading: Wapedia’s “Wiki: Linear Multistep Method”**
    Link: Wapedia’s “[Wiki: Linear Multistep
    Method](https://resources.saylor.org/archived/wp-content/uploads/2011/06/MA221-6.4.pdf)”
    (PDF)  
        
     Instructions: Click on the link above and read the entire
    article.  
        
     Terms of Use: The article above is released under a [Creative
    Commons Attribution-Share-Alike License
    3.0](http://creativecommons.org/licenses/by-sa/3.0/) (HTML).  It
    attributed to Wikipedia, and the original versin can be
    found [here](http://wapedia.mobi/en/Adams_Bashforth) (HTML).


