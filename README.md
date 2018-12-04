# Kazhdan-Lusztig-polynomial-calculator

We recursively compute Kazhdan-Lusztig polynomials of a special class of graphical matroids. These matroids correspond to "chorded" cycles, i.e. cycles with one edge connecting two previously non-adjacent vertices, forming a graph consisting of two smaller cycles sharing one common edge. Thus, our inputs are $n$ and $m$, the sizes of these two cycles. The algorithm relies on the dictionary (mainassoc) of previously computed polynomials and some combinatorial facts regarding this kind of matroids. Most importantly, palindromicity of the Z-polynomial [1] is at the core of this algorithm's design.

Also, this file contains a "GuessKLPolynomial" function. There is a strong empirical evidence that computing KL-polynomials of the above described graphical matroids can be reduced to computing those of uniform matroids. Lacking the proof of the proposed formula for arbitrary coefficients, we test it using this function. Note that "GuessKLPolynomial" only calls to compute KL-polynomials of uniform matroids but arrives at the exact same result.

This project is still in progress and is to be updated.
 
References:
[1] Proudfoot, Nicholas & Young, Ben & Xu, Yuan. (2017). The Z-polynomial of a matroid. Electronic Journal of Combinatorics. 25.
