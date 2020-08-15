# Kernel-PCA

A Python implementation of Kernel Principal Component Analysis (KPCA). Kernels implemented:

- Linear
- Radial Basis Function
- Exponential
- Laplacian
- Anova
- Polynomial
- Sigmoid
- Rotational quadratic
- Multiquadric
- Power
- Spherical
- Circular



## Requirements

<<<<<<< HEAD
* numpy

* matplotlib

=======
* python 3.7 version
* numpy
* matplotlib
>>>>>>> 6b09ac1fc5adfacde10980d6c5df6c2aa4e1638a
* seaborn

## Run

~~~python
```sh
from kpca import KPCA
from kernels import kernel
X = np.array([[2,3,4], [1,2,3]]) # dxn
k = kernel(sigma=0.0009, d_anova=3).anova
kpca = KPCA(X, k, 3)
scores = kpca.project().T
```
~~~

