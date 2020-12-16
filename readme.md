# Approximation and inference of non-Markov models of gene expression by neural network chemical master equations

***
This repository contains the julia code and parameters corresponding to the effeciency test presented in:
Approximation and inference of non-Markov models of gene expression by neural network chemical master equations

File descriptions:

- "SSA_single_channel_tau10_.csv" is the source data 
- "params" is the set of trained params for testing
- "Train from scratch.ipynb" is used for train a NN-CME from scratch
- "Test with trained params.ipynb" is used for testing with a trained NN-CME

Requirements:

- Julia >= 1.4.2
- Flux
- DifferentialEquations
- DiffEqSensitivity

How to run:

1. Install Jupyter notebook by conda/pip, or you can use [Anaconda](https://www.anaconda.com/) 

   ```conda install jupyter notebook```

   ``` pip install jupyter notebook```  

2. Add 'IJulia' in the julia console
   ```Pkg.add('IJulia')```

3. cd to the resository in terminal (Linux) or command window (windows) and open jupyter notebook web
   ```jupyter notebook```

   
