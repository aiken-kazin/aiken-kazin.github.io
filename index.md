
PCA is a dimensionality reduction technique that finds directions in the data space along which the variance is maximized.

---

## 1. Data Setup

Let \(X \in \mathbb{R}^{n \times d}\) be centered data:

- \(n\): number of samples
- \(d\): number of features

Centering means subtracting the mean from each feature.

---

## 2. Covariance Matrix

The covariance matrix measures how features vary together:

\[
\Sigma = \frac{1}{n-1} X^T X
\]

---

## 3. Eigenvalues and Eigenvectors

PCA relies on the eigen-decomposition of the covariance matrix:

\[
\Sigma v = \lambda v
\]

- \(v\): eigenvector (direction)
- \(\lambda\): eigenvalue (variance along that direction)
