## Some important notes for the BFGS-Algorithm: (any mathematical symbols will be represented in the LaTeX language for a better reading. May contain German explanations)
`` Every Method here is based on solving linear equations or finding the inverse of a matrix A. ``
- The Gauß-Jordan-Algorithm is perhaps the easiest way to determine the searched vector(s) x of a system of linear equations (A|b) with b being the solution vector. My version only functions with inverse matrices A, so that my algorithm only solves a unique vector x. 
- The QR-Decomposition describes every matrix A \in \mathbb{R}^{m \times n} with m \geq n in an easier way A = Q \cdot R, with Q being an orthogonal matrix, and R an upper triangular matrix.
-  The Cholesky-Decomposition describes that every symmetric, positive definite matrix 𝐴 \in \mathbb{R}^{n \times n} can be uniquely decomposed as A = LDL^T, where L is a lower triangular matrix with ones on the diagonal and D is a diagonal matrix.
-  The SOR method is an iterative technique for solving linear systems of the form Ax=b. It is a generalization of the Gauss-Seidel method, where a relaxation factor ω is introduced to accelerate convergence.
-  The Inverse Iteration method is an iterative algorithm used to compute an eigenvector corresponding to an eigenvalue of a matrix A, especially when an approximate eigenvalue \lambda is known.
-  My codes are free for coping and changing the inputs of the algorithm.
-  Feel free to message me for any questions you all might have. Have fun with the methods.
