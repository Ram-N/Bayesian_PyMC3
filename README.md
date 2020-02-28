# Bayesian_PyMC3

Examples and notebooks of using PyMC3 for learning Bayesian Analysis

Repo for Tutorial on Getting started with Bayesian Analysis and PyMC3.

### Slides (to follow along)
In case you wish to have a look, the slides are at:
https://speakerdeck.com/ramnarasimhan/getting-started-with-bayesian-analysis-and-pymc3

### Notebooks
In the `notebooks/` folder, there are 3 notebooks with Examples:

        Example1_Linear_Regression_Using PyMC3.ipynb
        Example2_OilExporation_Success_probability_using_PyMC3.ipynb
        Example3_AB Testing in a Bayesian Framework Using PyMC3.ipynb

For some participants, it might be easier to follow these notebooks along with the Slides in the presentation.

## Packages to be Installed (Minimal set)

You really only need PyMC3
- To install PyMC3 use `pip install pyMC3`
- To install arviz try `pip install arviz`


## Install a Virutalenv and work there

`> conda create -n bayes python=3.8`
`> conda activate bayes`
`pip install -r requirements.txt`

To make your virtual env show up in Jupyter you have to type:
`python -m ipykernel install --user --name=bayes`

If you get an error about ipykernel, install it using: `conda install -c anaconda ipykernel`

