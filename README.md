![GMIT_Logo.png](img/gmit-logo.png)
# Machine_Learning_And_Statistic

Author: Shane Rylands

G00387904@gmit.ie
***

## Overview

This repository contains my project submission for the Machine Learning and Statistics module for 2021. The purpose of this project is to demonstrate that I have achieved the learning outcomes of the module, which are:
- Describe the stochastic nature of real-world measurements.
- Select an appropriate mathematical model of a real-world problem.
- Select an appropriate cost function for a given machine learning task.
- Apply an optimisation technique to the parameters of a model.

The reposiory consists of two separate jupyter notebooks. The first notebook deals with Scikit-Learn and includes an overview of Scikit-Learn and a comparison of three difference machine learning modules within it; linear, ridge and lasso. The second notebook focuses on the SciPy library in which I performing a one-way ANOVA test using SciPy and investigate the assumptions associated with this test.

***

## Table of Contents

- Scikit-Learn ipynb
- SciPy ipynb
- ReadMe.md
- gitignore
- requirements.txt

***

## Quick View

You can easily view a static version of repository by clicking this image

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/shaner1/Machine_Learning_And_Statistic/tree/main/)

You can easily view a dynamic version of repository by clicking this image

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/shaner1/Machine_Learning_And_Statistic/HEAD?labpath=scikit-learn.ipynb)

***

## Install

To run my project submission from your local device you will need a python environment like Jupyter Lab. Jupyter Lab is an interactive python web environment that runs on your local machine. Projects in Jupyter Lab are referred to as notebooks. The easiest way to do this is to install Anaconda, which is a helpful python distribution package. You can find out how to do this here: [Installation Guide](https://docs.anaconda.com/anaconda/install/index.html)

Next, download the GitHub repository (repo) to your local device. To do so, simple open this link [github repo](https://github.com/shaner1/Machine_Learning_And_Statistic). Click the green code button and select download ZIP at the bottom, then unzip the folder on your device. In your command line interface (CLI) navigate to the folder using `cd` + filepath, for example:`cd Downloads/Machine_Learning_And_Statistic-main`. From your CLI you can open the notebook in your web browser with `jupyter notebook` + notebook name. For example, `jupyter notebook scikit-learn ipynb` to open the scikit notebook or `jupyter notebook scipy ipynb` to open the SciPy notebook.


To enusre no error and run the project as I have, you will need to install all the same packages as on my device. I am working off a MAC. The requirements.txt file contains all the necessary package and their versions. The easiest way to install these files is, while you are in the repo folder in your CLI, enter: `pip install -r requirements.txt`.

Alternatively, if you do not wish to install all these package and files to your local device you can run them in a virtual environment. While in the folder with the repo in your CLI, do the following:

1. Type `python3 -m venv venv` to create a virtual environment.
2. Then `source venv/bin/activate` for MAC or `.\venv\Script\activate.bat` for Windows to open the environment.
3. Then `pip install -r requirements.txt` to install the necessary packages
4. Then `jupyter notebook` + notebook name to run the notebooks


***

## Conclusion

In conclusion, I am happy with how my submission has turned out, but there are a few aspect I would like to improve upon. For the Scikit-learn notebook, I wanted to use neural networks, but wasnt able to find a suitable dataset for what I hoped to achieve. I invested a lot of time in trying to understand neural networks and seraching for appropriate datasets. This was not time wasted as I learnt a lot, but it is time spent that I could have use to better understand the theorical aspect of regression analysis. For the my SciPy notebook, I would also improve my explanation of the theory behind ANOVA and hypothesis testing in general. I would also have liked to include post hoc tests.

***

## Troubleshooting

If you encounter errors with this project please contact me at [G00387904@gmit.ie](mailto) and I will be happy to assist you in any way I can.

***

## Credits

Throughout this project, I have borrowed heavily from the Machine Learning and Statistic module course work created by Dr.Ian McLoughlin of GMIT. I also replied upon the Scikit-Learn and SciPy documentation. For help with markdown, I have referenced this blog https://www.markdownguide.org/basic-syntax/.

***