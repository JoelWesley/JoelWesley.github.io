{\rtf1\ansi\ansicpg1252\cocoartf1348\cocoasubrtf170
{\fonttbl\f0\fmodern\fcharset0 Courier;}
{\colortbl;\red255\green255\blue255;}
\margl1440\margr1440\vieww24340\viewh15860\viewkind0
\deftab720
\pard\pardeftab720

\f0\fs26 \cf0 \expnd0\expndtw0\kerning0
#### Pair Problem\
\
An Eigenvector is a vector V associated with a matrix A, such that when you multiply A by the eigenvector, you get a scalar multiple of the eigenvalue.  In other words, A simply scales V by some amount.   Eigenvectors and Eigenvalues are a central feature of dimensionality reduction, including PCA (Principal Component Analysis) and SVD (Singular Value Decomposition.)  SVD, in turn, is central to Latent Semantic Analysis.  Calculate the three eigenvectors and eigenvalues of the following matrix  1. Using numpy, 2. by hand.  \
\
```\
A = [[5, 3, 7],   \
     [2, 4, 1],\
	 [1, 3 9]        \
```\
\
Hint:  To do this by hand, write the following: \
\
\pard\pardeftab720
\cf0 \expnd0\expndtw0\kerning0
```\
AV = lambda * V\
```\
\
where V is an eigenvector, and lambda is a scalar constant, which is the eigenvalue.  This is equivalent to writing\
\
```\
AV = lambda * I * V\
```\
\
Where I is the identity matrix.\
}