## Welcome to Computational Physics PHY 354

This is a very hands-on course which will involve a lot of programming assignments. The main aims of the course are two fold:
1. Learning basic methods, tools and techniques of computational physics.
2. Developing practical computational problem solving skills.

### Syllabus

The syllabus can be downloaded from [here](https://github.com/iiscphy354/computational-physics/blob/master/Course_syllabus.pdf).

```markdown
**1. Introduction to computational physics, computer architecture overview, tools of computational physics (3 hours)**
What is computational physics? Why do we need it?; Computer hardware: basic computer architecture, hierarchical memory,
cache, latency and bandwidth; Moore’s law, power bottleneck; Software: compiled (Fortran, C) vs. interpreted languages
(MATLAB, python); software management.; Parallelization: MPI; OpenMP; CUDA.

**2. Machine representation, precision and errors (1.5 hours)**
Representation on a computer: Integer representation; floating-point representation; Machine precision; Errors: round-off;
approximation errors; random errors; errors of the third kind; Quadratic equations; Power series; Delicate numerical expressions; 
Dangerous subtractions; Preserving small numbers; Partial Fractions; Cubic equations; Sketching functions;

**3. Quadrature and Derivatives (6 hours)**
Direct fit polynomials; Quadrature methods on equal subintervals; Newton-Cotes formula; Romberg Extrapolation; Gaussian 
quadrature; Adaptive step size; Special cases;

**4. Solutions of linear and non-linear equations (9 hours)**
Simultaneous linear equations: Gauss elimination (pivoting, scaling); LU factorization; Calculating inverse; Tri-diagonal 
systems; Eigenvalues and Eigenvectors: QR Factorization; Gram-Schmidt Orthogonalization; Real roots of single variable function; 
Relaxation method; qualitative behavior of the function; Closed domain methods (bracketing): Bisection; False
position method; Open domain methods: Newton-Raphson, Secant method; Complications; Roots of polynomials; Roots of non-linear equations;

**5. Fourier methods (3 hours)**
Fast Fourier transform; Convolution; Correlation; Power spectrum;

**6. Random numbers and Monte-Carlo (6 hours)**
Random number generators; Monte-Carlo integration; Non-uniform distribution; Random Walk; Metropolis algorithm;

**7. Ordinary differential equations (9 hours)**
Initial value problems: First order Euler method; Second order single point methods; RungeKutta methods; Multipoint methods; 
Boundary value problems: Shooting method; equilibrium boundary value method;

**8. Partial differential equations (6 hours)**
Types of partial differential equations: Hyperbolic, parabolic and elliptic; Boundary value problems: Overrelaxation; Gauss-
Siedel Method; Initial value problems: FTCS method; Numerical stability; Implicit and Crank-Nicolson methods; Spectral methods;
```

### Textbooks
1. Mark Newman, *Computational Physics*, CreateSpace Independent Publishing Platform
(2013).
2. Forman Acton, *Real computing made real: Preventing Errors in Scientific and Engineering Calculations*, Dover Publications.
3. Lloyd N. Trefethen and David Bau, *Numerical Linear Algebra*, SIAM.
4. William H. Press, Saul A. Teukolsky, William T. Vetterling and Brian P. Flannery,
*Numerical Recipes 3rd Edition: The Art of Scientific Computing*

### Lecture Notes

1. [Lecture Note 1](https://github.com/iiscphy354/computational-physics/blob/master/lec1.pdf)
2. [Lecture Note 2](https://github.com/iiscphy354/computational-physics/blob/master/Lec2.pdf)
3. [Lecture Note 3](https://github.com/iiscphy354/computational-physics/blob/master/Lec3.pdf)
4. [Lecture Note 4](https://github.com/iiscphy354/computational-physics/blob/master/Lec4.pdf)
5. [Lecture Note 5](https://github.com/iiscphy354/computational-physics/blob/master/Lec5.pdf)
6. [Lecture Note 6](https://github.com/iiscphy354/computational-physics/blob/master/Lec6.pdf)
7. [Lecture Note 7](https://github.com/iiscphy354/computational-physics/blob/master/Lec7.pdf)
8. [Lecture Note 8](https://github.com/iiscphy354/computational-physics/blob/master/Lec8.pdf)
9. [Lecture Note 9](https://github.com/iiscphy354/computational-physics/blob/master/Lec_deriv.pdf)


**There are similar lecture notes available in [Prof. Prateek Sharma](http://www.physics.iisc.ernet.in/~prateek/numerical_analysis/)'s webpage and [Prof. Manish Jain](http://www.physics.iisc.ernet.in/~mjain/pages/teaching.html)'s webpage.**

### Grading Policy
1. No Exam !!!
2. There will be homeworks and projet. The grading policy is `50%` homework and `50%` project.
3. Project will be decided by the student in consultation with the Masters/PhD/Bachelors advisor 
– subject to the Instructors approval as well.
4. Stand alone project – which you have to get working and submit a working code and report. 
Also, make a presentation on it at the end of the course.
5. Projects can start right away.

### Homeworks
Homeworks will be uploaded here periodically. There will be decent amount of time to submit the homeworks in time.

**There is a penalty for the late submission of the homeworks.** 
*For every day you are late (unless informed prior to submission) `25%` of the marks will be deducted. After 4 days there wont't be any credit for the homework.*

1. Homework set 1 is uploaded on 8th January, 2020 ; due on **20th January, 2020.**
   Click [here](https://github.com/iiscphy354/computational-physics/blob/master/HW1.pdf) to download.
   
   Additional files: [millikan.txt](https://raw.githubusercontent.com/iiscphy354/computational-physics/master/millikan.txt), 
   [stm.txt](https://raw.githubusercontent.com/iiscphy354/computational-physics/master/stm.txt), 
   [sunspots.txt](https://raw.githubusercontent.com/iiscphy354/computational-physics/master/sunspots.txt)

2. Homework set 2 is uploaded on 26th January, 2020 ; due on **10th February, 2020.**
   Click [here](https://github.com/iiscphy354/computational-physics/blob/master/HW2.pdf) to download.

   Additional files: [altitude.txt](https://github.com/iiscphy354/computational-physics/blob/master/altitude.txt),
   [stm.txt](https://github.com/iiscphy354/computational-physics/blob/master/stm.txt), 
   [gaussxw.py](https://github.com/iiscphy354/computational-physics/blob/master/gaussxw.py),
   [velocities.txt](https://github.com/iiscphy354/computational-physics/blob/master/velocities.txt)
  
3. Homework set 3 is uploaded on 5th February, 2020 ; due on **24th February, 2020.**
   Click [here](https://github.com/iiscphy354/computational-physics/blob/master/HW2.pdf) to download.



### Contact
1. [Prof. Prateek Sharma](http://www.physics.iisc.ernet.in/~prateek/); 
   Course Instructor
2. [Prof. Manish Jain](http://www.physics.iisc.ernet.in/~mjain/); 
   Course Instructor
3. Sanat Gogoi; 
   TA

