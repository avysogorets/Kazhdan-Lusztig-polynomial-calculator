# Kazhdan-Lusztig-polynomial-calculator

We recursively compute Kazhdan-Lusztig polynomials of "double-cycle" matroids---a special class of graphic matroids. These matroids correspond to graphs obtained from two cycles joined by an edge. Inputs are $n$ and $m$---the sizes of these two cycles. The algorithm relies on the dictionary of previously computed polynomials and some combinatorial facts regarding this kind of matroids. Most importantly, palindromicity of the Z-polynomial [1] is at the core of this algorithm's design.
 
For a more complete description of the algorithm, see Appendix of [2] (added to this project's branch).

References:
[1] Proudfoot, Nicholas & Young, Ben & Xu, Yuan. (2017). The Z-polynomial of a matroid. Electronic Journal of Combinatorics. 25.
[2] Vysogorets, Artem (2019). The Kazhdan-Lusztig Polynomial of a Deletion Matroid.
