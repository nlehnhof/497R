# 497R
497R Airframe Project 2023

ME EN 497R Airfoil Analysis Assignment
Background
Airfoils are the cross sections of wings and rotors, so airfoil performance directly affects
the performance of any lifting object. A simple way to analyze airfoils is by using a panel
method. For this assignment, you will be utilizing a code produced by Mark Drela, a professor
at MIT, called XFOIL. Rather than the original Fortran, you will use a Julia version written
by students in the FLOWLab called Xfoil.jl.
Assignment
Start a new local branch and push it to your github repository. Name it something relevant
to the project. Create github issues for at least steps 3-6. You should use these issues to write
down questions you have about those steps of the assignment for reference in your weekly
meeting with your graduate student mentor. Close each issue you create with a comment as
you finish each step.
1. Read through the chapter 2 in the ME EN 515 Text (linked below), specifically sections 5
and 6. As you read and come across unfamiliar terms ()see hint below), look them up and
include them in an appendix in your report. As part of the definitions, include images
and equations to add clarity where applicable.
- You may consider, rather than including an appendix in your papers, producing a
dictionary of terms for yourself using the wiki feature on github.
2. Complete the examples given in the Xfoil.jl documentation. Take notes on which functions
you’ll need for the rest of the assignment and how to use them (i.e. write some pseudo
code).
3. Explore the effect of airfoil angle of attack on airfoil lift, drag, and moment.
4. Compare data collected from XFoil to published data (experimental or other).
5. Explore the effect of Reynolds number on airfoil lift, drag, and moment.
6. Explore the effect of airfoil thickness and camber on airfoil lift to drag ratio and lift curve
slope behavior.
7. Write a short write on your methods, results, and takeaways. You should include introduction and discussion material on what you learned in steps 1-6, giving special attention
to the methods and results from steps 3-6.
8. Submit your code and paper (.tex and .pdf files) via a pull request for your assignment
branch on github.
Hint: Here are some common terms that you may want to include in your appendix dictionary. You should also include other terms you come across that are unfamiliar.
1
ME EN 497R Airfoil Analysis Assignment
– Coefficient of Drag (2D), cd
– Coefficient of Lift (2D), cl
– Coefficient of Moment (2D), cm
– Angle of Attack, α
– Airfoil Polar
– Lift Curve Slope
– Stall
– Airfoil Chord, c
– Airfoil Camber
– Airfoil Thickness
– Freestream Velocity, V∞
– Reynolds Number, Re
– Mach Number, M
Useful Resources
– ME 515 Textbook : Chapter 2 Sections 5 & 6
– Original XFoil Documentation
– Xfoil.jl Documentation
– Google
– Adding wiki pages to your repository.
2
