# Internal PSI training on LCA, scenario-based LCA and prospective LCA

This repository holds the teaching material for 
the internal PSI LEA training.

## Course objectives

The objective of this course is to provide an introduction to the
LCA methodology and the tools used to perform it. The course will
be divided in four parts:

1. Introduction to [``brightway``](https://docs.brightway.dev/en/latest/) and [``activity-browser``](https://github.com/LCA-ActivityBrowser/activity-browser).
2. Introduction to the [``wurst``](https://github.com/polca/wurst) library.
3. Introduction to the [``premise``](https://github.com/polca/premise) library.
4. Practical session on scenario-based and prospective LCA.


## Course description

This course will introduce participants to LCA, software to conduct it, LCA data manipulation,
and prospective LCA. Hence, the course is divided in four parts. 

The first part will be an introduction to ``brightway`` and ``activity-browser``.

The second part will be an introduction to
the ``wurst`` library, which is a python library used to operate
large-scale modification on LCA databases. 

The third part will be
an introduction to the ``premise`` library, which is a python library
used to create and operate prospective LCA database based on IAM
scenarios. 

The fourth part will be a practical session where the
participants will be able to build their own prospective scenarios
using the ``premise`` library.

## Contact

[Romain Sacchi](mailto:romain.sacchi@psi.ch)

## License

Unless otherwise specified, all material in this repository is licensed [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode).

## Requirements

No special requirements are needed at the beginning of the course.
We will install the required software during the course.
We only ask the participants to download the following software before the course:

- Anaconda: https://www.anaconda.com/products/distribution
- Git: https://git-scm.com/downloads

## Instructions

Install the `libmamba` solver in conda, for faster environment resolution:

```bash
  conda install -n base conda-libmamba-solver
  conda config --set solver libmamba
```