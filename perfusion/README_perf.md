# In Vivo Imaging and Physiological Modelling - BMED 360 Spring 2020


### _perfusion_


## Software

- Model-Free Deconvolution of 4D DCE MRI scans (https://github.com/liob/non-parametric_deconvolution) [[PubMed](https://www.ncbi.nlm.nih.gov/pubmed/31276264)]


### Quantiphyse  (making a new virtual environment `qp`)

Quantiphyse is a visual tool for quantitative analysis of medical images. The aim is to bring advanced analysis tools to users via an easy-to-use interface rather than focusing on the visualisation features themselves. See the [[Overview](https://quantiphyse.readthedocs.io/en/latest/basics/overview.html)] for more information.

#### Dynamic Susceptibility Contrast (DSC) MRI

The DSC-MRI package provides a Bayesian modelling tool for quantification of perfusion and other haemodynamic parameters from Dynamic Susceptibility Contrast perfusion MRI of the brain.

- DSC vascular model: Mouridsen K, Friston K, Hjort N, Gyldensted L, Østergaard L, Kiebel S. Bayesian estimation of cerebral perfusion using a physiological model of microvasculature. NeuroImage 2006;33:570–579. doi: 10.1016/j.neuroimage.2006.06.015.

#### Installation

See **installation for Anaconda 3.x** (dependencies from pip) [[here](https://quantiphyse.readthedocs.io/en/latest/basics/install.html#anaconda-python-3-x-dependencies-from-pip)]

> conda deactivate
> conda create -n qp python=3.7
> conda activate qp
> pip install quantiphyse

This installs the basic Quantiphyse app. To install plugins use pip, for example this is to install all current plugins:

> pip install quantiphyse-cest quantiphyse-asl quantiphyse-qbold quantiphyse-dce quantiphyse-dsc quantiphyse-t1 quantiphyse-fsl quantiphyse-sv quantiphyse-perfsim

On Mac you will also need to do:

> pip install pyobjc

