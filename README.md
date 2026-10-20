# PCA from Scratch

Implementation of Principal Component Analysis using NumPy eigendecomposition,
validated against scikit-learn and applied to handwritten digit images.

## What's inside
- PCA built from the covariance matrix and its eigenvectors
- Verification against `sklearn.decomposition.PCA`
- Explained variance analysis and 2D visualization
- Eigen-digit images, compression, and reconstruction error
- Classifier accuracy vs. number of components
- Proof-by-code that PCA via SVD matches the eigendecomposition

## Key results
- 29 of 64 components capture 95% of the variance
- kNN accuracy with 15 components: ~0.978 (all 64 pixels: ~0.984)

## Run it
pip install numpy matplotlib scikit-learn jupyter
jupyter notebook pca_from_scratch.ipynb

## Math concepts
Covariance matrices, eigenvalues and eigenvectors, orthonormal bases,
projections, and the singular value decomposition.
