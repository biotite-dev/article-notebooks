# article-notebooks

This repository contains the *Jupyter* notebooks from the 2023 journal article
'*Biotite: New tools for a versatile Python bioinformatics library*'.

## Setup

The `environment.yml` provides a
[Conda](https://docs.conda.io/en/latest/miniconda.html) environment including
the dependencies for these notebooks.
The environment can be created with

```
conda env create -f environment.yml
```

and activated with

```
conda activate biotite-article
```

Then the *Jupyter* notebooks can be accessed via

```
jupyter notebook
```