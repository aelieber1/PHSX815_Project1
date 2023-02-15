# PHSX815 Spring 2023 Project #1 Ashley Lieber

## Simple Simulation of Soccer Goals Using a Poisson Distribution & Hypothesis Testing

### This repository contains several programs:

- `GoalData.py` [Python]
- `GoalDataAnalysis.py` [Python]
- `MySort.py` [Python]
- `Random.py` [Python]

### Requirements

The Python code in this repository requires the use of several packages which can be 
easily installed from the command line using `HomeBrew` or `pip install` commands. 

In order to compile the program `GoalData.py` and `Random.py`, these external 
packages are required:
- `numpy`
- `scipy.stats`
    - `from scipy.stats import poisson`
- `math`

In order to compile the programs `GoalDataAnalysis.py` and `MySort.py`, these external 
packages are required:
- `math`
- `numpy`
- `matplotlib.pyplot`
- `pandas`
- `scipy.stats` import `poisson`

### Usage

The python file `GoalData.py` can be run from the command
line by typing:

	<> python3 GoalData.py -rate [rate] -seed [seed] -Nmeas [number of games observed] -Nexp [number of sets of measurments or seasons observed] -output ["filename"]

This script will either print the result to the command line or save to a file 
if given a filename from the command line.

The python file `GoalDataAnalysis.py` can be run from the command
line by typing:

	<> python3 GoalData.py -inputH0 ["filename"] -inputH1 ["filename"]
    
This script will output two plots, (1) a histogram of the data, (2) loglikelihood

All of the Python programs can be called from the command line with the `-h` 
or `--help` flag, which will print the options

    
    
