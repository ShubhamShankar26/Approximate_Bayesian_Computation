# Model for communicable disease outbreak dynamics

This repository contains the simulator code for the disease outbreak model by Lintusaari et al. 2018. 
The attached jupyter notebook contains the ABC inference using ELFI. 
The observed data is the tuberculosis epidemic data from San Francisco Bay area.

The attached code is tested with Python 3.5 and ELFI v. 0.7.1.

## Files

- **code/simulator.py**
  Contains a general Python implementation of the simulator for the model
- **code/elfi_operations.py**
  Contains ELFI operations to run parameter inference with ELFI
- **inference.ipynb**
  Jupyter notebook defining the ELFI model and running the inference

