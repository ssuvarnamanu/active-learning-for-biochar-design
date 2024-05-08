# Active learning for biochar design with enhanced CO2 capture

This repository contains the code for the paper titled Active learning based guided synthesis of engineered biochar for CO2 capture

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Data preparation](#data-preparation)
- [Model training](#training)

# Overview

This repository contains the codes and dataset to train models for an active learning loop using the Random forest surrogate model coupled with the Particle Swarm Optimizer.  
This repository contains the following:

* The main jupyter notebook whihc contains the code used to develop the active learning loop for the research project.
* For the notebook, we include the curated dataset in clean Excel sheets which are labelled corresponding to the cycles of the active learning.
* Necessary instructions to run the model and expected outcome are provided as comments in the notebook.

# System Requirements

## Hardware requirements
The code can run on any standard computer and does not require GPUs or clusters.

## Software requirements
The package has been tested on the following systems:
+ Windows 11 Pro for Workstations with 64-bit operating system, x64-based processor

### Python

A Python version of 3.6 or above is recommended. Most of the code is developed using standrad library packages including:

* Pandas 2.0.3 
* Numpy1.24.3 
* Scikit-learn 1.3.0
* Tensorflow 2.12.1
* Shap 0.40.0

## Installation guide

The codes can also be run on an exisiting environment provided the above listed packages are systemically installed using pip or conda commands.
Alternately users can create a dedicated `conda` environment and install the required the packages. The conda environment can be created by, for example:

* conda create -n active-learning python=3.7
* conda activate active-learning


## Data preparation

We provide the clean and labelled curated data as Excel sheets titled "Data for model" which includes all the experimental data used for model training. The file itself contains 4 tabs, with each tab corresponding to the experimental data from each of the active learning cycles.

## Model training

The workflow uses standard training process for implementing the Random forest and we provide detailed instructions for the same. The hyperparameters of the the algorithm are optimized usingthe gridsearch methodology. Implementing the Particel Swarm Optimizer (PSO) needs MORE ATTENTIONn. Though we provide instructions to run the PSO specific to our datasets and basic tuning of its parameters The expected outcome after the end of the PSO campaign and its implication to this research project is explained in the notebooks.

## Referencing

The active learning model devised in this study employs RF regressor and PSO optimizer to recommend experimental conditions aimed at designing property specific biochar.If you find this work relevant, please cite our published paper:

### Active learning based guided synthesis of engineered biochar for CO2 capture
X. Yuan, M. Suvarna, J.Y. Lim, J. Pérez-Ramírez, X. Wang, Y.S. Ok
Environ. Sci. Technol. 2024, 15, 6628–6636. (https://pubs.acs.org/doi/10.1021/acs.est.3c10922)
