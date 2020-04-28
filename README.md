# BEL1D

BEL1D is a program for the **stochastic** 1D imaging of the subsurface based on geophysical data.
It relies on the Bayesian Evidential Learning (BEL) framework called BEL 1D imaging (BEL1D in short) [(Michel et al., 2020)](https://doi.org/10.1016/j.cageo.2020.104456). The framework basically consists in 6 steps:
1. Generation of models from the prior model space and their associated data (forward modeling)
2. Reduction of the dimensionality of the dataset
3. Canonical correlation between the data and the models parameters
4. Extraction of the posterior distributions in the reduced model space
5. Sampling of models in reduced space
6. Back-transformation to original space

The toolbox that is inside this package is an imporoved version of the codes used in [(Michel et al., 2020)](https://doi.org/10.1016/j.cageo.2020.104456) . They normally support 3 different applications:
1. Interpretation of SNMR data (Forward model from MRSmatlab - [(Mueller-Petke et al., 2016)](https://doi.org/10.1190/geo2015-0461.1) )
2. Interpretation of dispersion curves from surface waves analyses (Forward model from GEOPSY [(Wathelet, 2018)](https://doi.org/10.1029/2008GL033256) )
3. General case (Need to be in matlab and not the executable version!!!)

## Installation
[![win](https://img.shields.io/badge/Windows%2064bit-BEL1D%20v3.0-blue.svg?style=flat&logo=Microsoft&logoColor=white)](https://github.com/hadrienmichel/fastbel1d/releases/download/v3.0/BEL1D.exe)

Download the [(windows installer)](https://github.com/hadrienmichel/fastbel1d/releases/download/v3.0/BEL1D.exe). This will install the BEL1D interface on your computer along with the Matlab runtime.
There is no version for UNIX systems.

## Usage

The program is an executable. All the elements should be self-explainatory. However, a manual is currently beeing written.

## Compatibility

The codes have only been teste under Winbdows environment.
They are devellopped in Matlab R2018a.