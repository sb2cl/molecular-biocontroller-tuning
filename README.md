# Molecular biocontroller tuning with multiobjective optimization

This is the repository of the code we used to generate the results in "Modeling and optimization of a molecular biocontroller for the regulation of complex metabolic pathways".

# Content

[TOC]

## Matlab Version

We used Matlab version 9.9.0.1467703 (R2020b), we did not test if this code works with other Matlab versions.

## Repository structure

**scripts/** 
 
In this folder it is placed all the scripts necesary to run the multiobjective optimization of the biocontroller for the regulation of complex metabolic pathways used in the manuscript.

**spMODEx algorithm files**

The files `spMODEII.m`,`spMODEparam.m`,`SphPruning.m` and `PhyIndex.m`,`CostFunction.m` are the multiobjective optimization algorithm used, and can be found on https://www.mathworks.com/matlabcentral/fileexchange/47035
**Example simulation result from the metabolic pathway with dynamic regulation model**
![Model Simulation](/images/temporales_naringenin.png)
**Example result from a multiobjective optimization**
![Pareto Front](/images/pareto_front.png)
![Pareto Set](/images/pareto_set.png)
