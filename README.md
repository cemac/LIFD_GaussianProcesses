
<div align="center">
<img src="https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/images/LIFDlogo.png"></a>
<a href="https://www.cemac.leeds.ac.uk/">
  <img src="https://github.com/cemac/cemac_generic/blob/master/Images/cemac.png"></a>
  <br>
</div>

# Leeds Institute for Fluid Dynamics Machine Learning For Earth Sciences #

# Gaussian Processes


[![GitHub release](https://img.shields.io/github/release/cemac/LIFD_GaussianProcesses.svg)](https://github.com/cemac/LIFD_GaussianProcesses/releases) [![GitHub top language](https://img.shields.io/github/languages/top/cemac/LIFD_GaussianProcesses.svg)](https://github.com/cemac/LIFD_GaussianProcesses) [![GitHub issues](https://img.shields.io/github/issues/cemac/LIFD_GaussianProcesses.svg)](https://github.com/cemac/LIFD_GaussianProcesses/issues) [![GitHub last commit](https://img.shields.io/github/last-commit/cemac/LIFD_GaussianProcesses.svg)](https://github.com/cemac/LIFD_GaussianProcesses/commits/master) [![GitHub All Releases](https://img.shields.io/github/downloads/cemac/LIFD_GaussianProcesses/total.svg)](https://github.com/cemac/LIFD_GaussianProcesses/releases) ![GitHub](https://img.shields.io/github/license/cemac/LIFD_GaussianProcesses.svg)[![DOI](https://zenodo.org/badge/366734586.svg)](https://zenodo.org/badge/latestdoi/366734586)

[![LIFD_GaussianProcesses](https://github.com/cemac/LIFD_GaussianProcesses/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/cemac/LIFD_GaussianProcesses/actions/workflows/python-package-conda.yml)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cemac/LIFD_GaussianProcesses/HEAD?labpath=GaussianProcesses.ipynb)

This notebook explores Gaussian Processes to find theoretical functions and then uses advanced python machine learning libraries to

## Recommended Background Reading

If you are unfamiliar with some of the concepts covered in this tutorial it's recommended to read through the background reading below either as you go through the notebook or beforehand.

* [An Intuitive Guide to Gaussian Processes](https://towardsdatascience.com/an-intuitive-guide-to-gaussian-processes-ec2f0b45c71d)
* [Visual article on Gaussian Processes](https://distill.pub/2019/visual-exploration-gaussian-processes/)

## Quick look

If you want a quick look at the contents inside the notebook before deciding to run it please view the [md file](https://github.com/cemac/LIFD_GaussianProcesses/blob/main/GaussianProcesses/Gaussian_Processes.md) generated (*note some HTML code not fully rendered*)

## Installation and Requirements

This notebook is designed to run on a laptop with no special hardware required therefore recommended to do a local installation as outlined in the repository [howtorun](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/howtorun.md) and [jupyter_notebooks](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/jupyter_notebooks.md) sections.

### Quick start

If you're already familiar with git, anaconda and virtual environments the environment you need to create is found in GP.yml and the code below to install activate and launch the notebook

```bash
conda env create -f GP.yml
conda activate GP
jupyter-notebook
```
