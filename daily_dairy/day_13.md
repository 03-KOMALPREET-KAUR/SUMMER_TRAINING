**DAY 13(09/07/2025)**

Today, I explored the fundamental linear algebra concepts that are essential for understanding the internal workings of machine learning models. 

1) **Vectors:** A vector is a one-dimensional array of numbers. It represents features of a data point (for example: height, weight, age of a person).

   a) **Vector Addition:** Vector addition is the operation of adding two vectors by summing their corresponding components.

   b) **Vector Subtraction:** Subtracting one vector from another involves subtracting corresponding components.

   c) **Scalar Multiplication:** A vector can be scaled by multiplying each of its components by a scalar (real number).

   d) **Magnitude of a Vector:** The norm of a vector (also called its magnitude or length) is the distance of the vector from the origin in space.

   e) **Angle Between Two Vectors:** If the angle between two vectors is small, then the vectors are quite similar. If the angle between two vectors is large, then the vectors are very different.

   f) **Dot Product:** The dot product of two vectors is the sum of the products of their corresponding entries.

   g) **Cross Product:** The cross product of two vectors results in a third vector that is perpendicular to both.

   h) **Projection of Vector a onto Vector v:** The projection of **a** onto **v** is given by projᵥ a = ((a · v) / ||v||²) * v

2) **Matrices:** A matrix is a 2D array of numbers, used to represent datasets or transformations. It is denoted by uppercase letters like A, X, or W. A dataset with m samples and n features can be represented as an m×n matrix.

   a) **Matrix Addition and Subtraction:** Two matrices can be added or subtracted only if they have the same dimensions. The operation is performed element-wise.

   b) **Scalar Multiplication:** Each element of a matrix is multiplied by a scalar.

   c) **Matrix Multiplication:** Matrix A (m×n) can be multiplied by matrix B (n×p) to get a new matrix C (m×p). This operation is not element-wise. It involves the dot product of rows of A with columns of B.

   d) **Transpose of a Matrix:** The transpose of a matrix flips its rows and columns.

   e) **Identity Matrix(I):** A square matrix where all diagonal elements are 1, and others are 0.

   f) **Inverse of a matrix:** For a square matrix A, its inverse satisfies A · A⁻¹ = I. Not all matrices are invertible (only non-singular ones with non-zero determinant are invertible). Inverse helps in solving linear systems: To solve Ax = b, x = A⁻¹ · b.

   
