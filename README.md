#TELO Hexapod 2024
## Automated Damage Control in a Hexapod Robot

This repository contains all of the code necessary to replicate the simulated experiments for automated damage recovery in hexapod robots using various controllers: HyperNEAT & NEAT (ANN controllers), CPG & Reference, SUPG.


## Python package dependencies
```shell
pip install -r requirements.txt
```
* numpy
* pybullet
* matplotlib
* sklearn
* mpi4py
* GPy
* scipy

## Submodules
Each of the different controllers used in the paper have their own GitHub repo. For simplicity, the different controllers independent repos have been added as submodules (i.e., links to them). The correlation between each controller and their respective folder/submodule in this repo is detailed below:


| Controller      | Folder/Submodule |
|-----------------|------------------|
| HyperNEAT+NEAT  | ann-controllers  |
| CPG + Reference | cpg-controller   |
| SUPG            | supg-controller  |
 
