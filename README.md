# Convex-Optimization-with-LMIs-in-MATLAB
Solving Semidefinite Programming (SDP) and Linear Matrix Inequalities (LMIs) with YALMIP and MOSEK
This code intends to compute the optimal numerical solution to convex constraints in terms of linear matrix inequalities (LMIs)
for mean arterial blood pressure (MAP) regulation in clinical resuscitation for critical hypotensive patients.

The details of linear parameter-varying (LPV) of dynamic MAP response to vasoactive drug injection with the parameter estimation
scheme methodology can be found in the following papers. Square-root cubature Kalman filter is utilized for parameter estimation 
and has its own details and complexity which will not be discussed in these files. In this work, I have added injection 
magnitude constraints, known as input saturation, to the original problem. Simulations are conducted via MATLAB Simulink where
the files are subject to copyright and not provided.

In these codes, I have computed the matrix variable parameters for the output feedback control of automated drug infusion. The
controller is designed to satisfy the LMI constraints of the induced L_2-norm characterization of the closed-loop system, AKA
H_\infty control in linear time-invariant (LTI) systems. MATLAB is equipped with YALMIP and MOSEK solver. In the author's point of view and experience, YALMIP may seem better and more versatile in terms of performance and computational time, specifically for handling complicated LMIs and large matrices and constraints as in my problem.

Please feel free to contact me with any questions.

For details please take a look at my recent papers.
https://scholar.google.com/citations?user=ydv1fIcAAAAJ&hl=en
