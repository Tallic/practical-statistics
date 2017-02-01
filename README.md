# Practical Statistics
*Practical statistics with R and Python with a focus on research applications*

This repository contains short self-contained tutorials about basic statistical
with a focus on research applications.
The examples are implemented in R as in Python and will range from basic data
cleaning and wrangling, to descriptive, exploratory and inferential statistics.
Furthermore it contains basic topics of machine learning as some pragmatic issues.

The content will be extended over the time and the notebooks and script might
be subject to changes given some feedback.


## Installation
You will need [Anaconda](https://www.continuum.io/downloads) which is a package
manager that provides you with and R and Python runtime.
The repository contains the requirements in within the requirements.yaml
which you can install via:

```
user@user: ~/practical-statistics$ conda-env create -f requirements.yml
```

This also installs [Jupyter](http://jupyter.org/) from which you can open, edit
and run the notebooks.
You can start Jupyter with

```
user@user: ~/practical-statistics$ jupyter notebook
```
which opens a tree view in you browser from which you can select your desired
notebook.

## Disclaimer

This series is intended to give you an overview over a specific set of technology
and how you can leverage it during your research activities.
Hence the tutorials do not try, by any means, to give you an in-depth introduction
or course in R or Python.
