# Detecting high-order epistasis in nonlinear genotype-phenotype maps
**Zachary R Sailer and Michael J Harms**

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/harmslab/notebooks-nonlinear-high-order-epistasis)

This repository contains Jupyter notebooks that reproduce the results and analysis in our paper: "Detecting high-order epistasis in nonlinear genotype-phenotype maps." published in Genetics.

See an early release of the paper [here](http://www.genetics.org/content/early/2017/01/17/genetics.116.195214).

## Try out the notebooks!

All results and analysis are reproducible in Jupyter notebooks. Try the the notebooks [now](http://mybinder.org:/repo/harmslab/notebooks-nonlinear-high-order-epistasis), graciously provided by the Binder web service.

## Download and Install

If you'd like to run the notebooks locally, clone this repository and make sure you have all the necessary dependencies are installed and are running Python 3. Here's a list of everything you'll need:

1. epistasis
2. gpmap
3. Jupyter Notebook
4. IPython
5. Numpy
6. Scipy
7. Scikit-learn
8. Matplotlib
9. ipywidgets

All packages can be installed using `pip`.

## Data formats

The following formats are used in to create all data, metadata, and figures for the paper. The point of listing them is the provide documentation for anyone interested in sifting through through the data.

- Experimental data, and final results are saved in JSON format (`.json` files). This makes the data easily accessible to basically any programming language -- an attempt to practice true reproducibility. Also, this format is fairly human-readable.
- Data, analysis, raw-figures, code, etc. were all done in Jupyter Notebooks saved as `.ipynb` files. Guaranteed to work with Python 3.

## Table of Contents

- Figure 1: **Epistasis can be quantified using Walsh polynomials** (no notebook for this figure)
- [Figure 2](figures-notebooks/figure-02.ipynb): **Nonlinearity in phenotype creates spurious high-order epistatic coefficients.**
- [Figure 3](figures-notebooks/figure-03.ipynb): **Epistasis and nonlinear scale induce different patterns of nonadditivity.**
- [Figure 4](figures-notebooks/figure-04.ipynb): **Experimental genotype-phenotype maps exhibit nonlinear phenotypes.**
- [Figure 5](figures-notebooks/figure-05.ipynb): **High-order epistasis is present in genotype-phenotype maps.**
- [Figure 6](figures-notebooks/figure-06.ipynb): **Nonlinear phenotypes distort measured epistatic coefficients.**
