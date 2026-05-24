# Dual Affine Spiral Orbits on ℤ² from Paired Unit Squares

Chuck Wrathall  
Independent Researcher  
Sydney, Nova Scotia, Canada

---

### Abstract

We introduce a simple iterative geometric construction on the integer lattice ℤ² consisting of paired unit squares that share a single corner. At each step, a new square is constructed outwardly on the hypotenuse of the isosceles right triangle formed by the outer edges adjacent to the shared corner.

This process generates two interlocking affine spiral orbits on ℤ²: a positive orbit {P_n} starting at (0,0) and a negative orbit {N_n} starting at (−1,2).

Both sequences satisfy clean linear recurrences driven by multiplication by the Gaussian integer 1+i. The paired points remain symmetric with respect to the fixed midpoint  
M = (−1/2, 1)  
satisfying the invariant P_n + N_n = (−1, 2) for all n.

Extending the iteration backward produces the attractor of the well-known Twindragon fractal. The construction also yields the normalized quadratic sequence  
a(n) = (|P_n|² + |N_n|²)/5 = 2^{n+1} + 1 − 2 Re((1+i)^n)  
which is always an integer and appears as A396151 in the OEIS.

---

### View the Full Paper

- Beautiful web version → [Open the Full Paper](https://chuckwrathall.github.io/dual-affine-spiral-orbits/)  
  (clean academic layout with all equations, figures, and the new Appendix A)

- Download the finished PDF → [paper.pdf](paper.pdf)

---

### What’s New in This Version
- Full 8-page finished paper
- New Appendix A: Explicit coordinate tables verifying the Corner Sum Identity (n = 0 to 8 for both orbits)

### References
- OEIS A396151: https://oeis.org/A396151
- C. Davis and D. E. Knuth, “Number representations and dragon curves,” Journal of Recreational Mathematics, 3:66–81 and 133–149, 1970.

---

Repository Contents
- index.html – Full web version of the paper
- paper.pdf – The finished 8-page paper (with Appendix A)
- figures/ – All figures from the paper

Last updated: May 2026
