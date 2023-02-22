# Automated Damage Control in a Hexapod Robot

This repository contains all of the code necessary to replicate the simulated experiments from the paper we submitted to the Gecco 2023 conference.   


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

## Videos
Coming soon

## Submodules
Each of the different controllers used in the paper have their own GitHub repo. For simplicity, the different controllers independent repos have been added as submodules (i.e., links to them). The correlation between each controller and their respective folder/submodule in this repo is detailed below:


| Controller     | Folder/Submodule |
|----------------|------------------|
| HyperNEAT+NEAT | ann-controller   |
| CPG            | cpg-controller   |
| SUPG           | supg-controller  |
 
