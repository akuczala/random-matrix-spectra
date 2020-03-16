# random-networks

Python libraries developed for research in recurrent neural networks

## Random matrix spectra
Includes libraries for generating N x N random matrices with structured correlations, and their spectra for large N, as described in https://arxiv.org/abs/1610.09353. Includes a Jupyter notebook reproducing the figures.

genRandom.py generates finite N realizations from the matrix distributions described in the paper.

genSpec.py produces the Green's functions and mean eigenvalue densities for large random matrices using the semi-analytical approach described in the paper.

The data folder contains precomputed eigenvalues for various matrix distributions. These are used to approximate eigenvalue densities for comparison with theory.

## Information in recurrent networks
fisherlib.py computes the information capacity of coupled random recurrent networks. An example notebook is included.



