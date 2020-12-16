# Neural-network chemical master equation (NN-CME)

***
This repository contains the julia code and parameters corresponding to the effeciency test presented in:
Neural network aided approximation and parameter inference of stochastic models of gene expression

File descriptions:

- "SSA_single_channel_tau10_.csv" is the source data 
- "main.ipynb" is the code for training and testing NN-CME
- "NN-CME.png" shows the prediction result by means of NN-CME

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

3. cd to the resository in terminal (Linux) or command window (Windows) and open jupyter notebook web
   ```jupyter notebook```

   
