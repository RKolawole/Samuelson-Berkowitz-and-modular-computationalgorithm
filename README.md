# Samuelson-Berkowitz-and-modular-computation algorithm
Gaussian elimination method is a fast and widely used algorithm for efficient computation of the determinant of square matrices. But keep in mind, it involves division, which may yield non-integer coefficients. In fact, it forces us to work in the rational domain instead of the integer domain we so much desired. 

This project considers two algorithms: first, a division-free algorithm for obtaining the characteristics polynomial and the determinant of square matrices whose coefficients are in any unital commutative ring R, which is not an integral domain. 

The second method, a modular computation algorithm, which utilizes both division-free and division-based techniques to calculate the determinant of square matrices with integer coefficients. This algorithm is fast but can become very slow if too many primes are used, leading to an excessive number of unnecessary modular computations. We use fewer odd primes to speed up the algorithm by defining a function that asks for the number of primes we would like to use in our computation.
