This repository contains the Python code used to produce the numerical results presented in the article _"On the existence of eigenvalues of a one-dimensional Dirac operator"_ [[arXiv]](https://arxiv.org/abs/2408.12697) [[Journal]](https://link-url-here.org) written by Daniel Sánchez-Mendoza and Monika Winklmeier.

The Jupyter notebook [Variational_Principle_Dirac_1d.ipynb](src/Variational_Principle_Dirac_1d.ipynb) numerically implements the variational principle and applies it to an example taken form [[DKTZ23]](https://arxiv.org/abs/2312.04033). The output is saved into the files [(t,lambda).csv](src/(t,lambda).csv) and [S_Eig.json](src/S_Eig.json). The [(t,lambda).csv](src/(t,lambda).csv) file is loaded into the Wolfram Mathematica notebook [Plots.nb](src/Plots.nb) where it is plotted alongside some analytical examples.

__Dependencies:__
- numpy, scipy, matplotlib, IPython.
