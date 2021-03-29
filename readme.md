# Neural-network chemical master equation (NN-CME)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4643094.svg)](https://doi.org/10.5281/zenodo.4643094)

***
This repository contains the julia code and parameters corresponding to the effeciency test presented in:
Neural network aided approximation and parameter inference of stochastic models of gene expression

File descriptions:

- "SSA_single_channel_tau10_.csv" is the source data 
- "main.ipynb" is the code for training and testing NN-CME in Jupyter notebook
- "NN-CME.png" shows the prediction result by means of NN-CME
- "processed.mat" summarizes the experimental data from literature for Fig. 4b (inset)

Requirements:

- Julia >= 1.4.2
- Flux v0.10.4
- DifferentialEquations v6.15.0
- DiffEqSensitivity v6.26.0

How to run:

1. Install Jupyter notebook by conda/pip, or you can use [Anaconda](https://www.anaconda.com/) 

   ```conda install jupyter notebook```

   ``` pip install jupyter notebook```  

2. Add 'IJulia' in the julia console
   ```Pkg.add('IJulia')```

3. cd to the resository in terminal (Linux) or command window (Windows) and open jupyter notebook web
   ```jupyter notebook```

Please cite the paper:
* Q. Jiang \textit{et. al.} [Neural network aided approximation and parameter inference of stochastic models of gene expression](https://www.biorxiv.org/content/10.1101/2020.12.15.422883v1.full.pdf). \textit{bioRxiv} (2020).
   
