| Operation | Function | Definition |
| --- | --- | --- |
| **Matrix Creation and Manipulation** | | |
| Create a Matrix | `A = [1, 2, 3; 4, 5, 6; 7, 8, 9];` | Create a 3x3 matrix `A`. |
| Transpose | `B = A';` | Transpose matrix `A` to get `B`. |
| Matrix Multiplication | `C = A * B;` | Multiply matrices `A` and `B` to get `C`. |
| Element-Wise Multiplication | `D = A .* B;` | Multiply matrices `A` and `B` element-wise to get `D`. |
| **Matrix Operations** | | |
| Determinant | `det_A = det(A);` | Compute the determinant of matrix `A`. |
| Inverse | `inv_A = inv(A);` | Compute the inverse of matrix `A`. |
| Matrix Rank | `rank_A = rank(A);` | Calculate the rank of matrix `A`. |
| Eigenvalues and Eigenvectors | `[V, D] = eig(A);` | Compute eigenvalues and eigenvectors of matrix `A`. |
| Matrix Exponentiation | `eA = expm(A);` | Compute the matrix exponential of `A`. |
| **Solving Linear Systems** | | |
| Linear System Ax = b | `[x, flag] = linsolve(A, b);` | Solve the linear system `Ax = b` for `x`. |
| Least Squares Solution | `[x, residual] = lsqminnorm(A, b);` | Find the least squares solution to `Ax = b`. |
| **Matrix Factorizations** | | |
| LU Decomposition | `[L, U, P] = lu(A);` | Perform LU decomposition with pivoting. |
| QR Decomposition | `[Q, R] = qr(A);` | Compute QR decomposition of matrix `A`. |
| Singular Value Decomposition (SVD) | `[U, S, V] = svd(A);` | Perform Singular Value Decomposition of `A`. |
| **Vector Operations** | | |
| Vector Dot Product | `dot_product = dot(v1, v2);` | Calculate the dot product of two vectors. |
| Vector Cross Product | `cross_product = cross(v1, v2);` | Compute the cross product of two vectors. |
| Vector Norm | `norm_v = norm(v);` | Calculate the Euclidean norm (magnitude) of vector `v`. |
| Vector Projection | `projection = dot(v1, v2) / norm(v2) * v2;` | Compute the projection of `v1` onto `v2`. |
| **Special Matrices** | | |
| Identity Matrix | `I = eye(n);` | Create an identity matrix of size `n`. |
| Zero Matrix | `Z = zeros(m, n);` | Create a zero matrix of size `m x n`. |
| Diagonal Matrix | `D = diag([1, 2, 3]);` | Create a diagonal matrix from a vector. |
| **Matrix Manipulation Functions** | | |
| Reshaping a Matrix | `B = reshape(A, m, n);` | Reshape matrix `A` into a `m x n` matrix `B`. |
| Extracting a Submatrix | `submatrix = A(2:4, 1:2);` | Extract a submatrix from `A`. |
