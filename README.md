# Metaheuristics Assignment 

For Metaheuristic Optimization class, DSTI SPOC (A19). 

## Problem Set

For each function you are expected to report:

- The chosen algorithm and a justification of this choice
- The parameters of the algorithm
- The final results, both solution and fitness
- The number of function evaluations
- The stopping criterion
- The computational time
- The convergence curve (fitness as a function of time)

### Discrete Optimization (TSP)

Solved the TSP problems for Djibouti (38 cities) and Qatar (194 cities) using a Genetic Algorithm. 

### Continuous Optimization 

- F1: Shifted Sphere Function (PSO)
- F2: Shifted Schwefel's Problem 2.21 (PSO) 
- F3: Shifted Rosenbrock's Function (BFGS)
- F4: Shifted Rastrigin's Function (GA)
- F5: Shifted Griewank's Function (N-M)
- F6: Shifted Ackley's Function (PSO)

## Environment

### Prerequisites

You will need Jupyter Notebook with Python 3 installed (this can be done through __[Anaconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)__). 


### Installing

You will need to install:

__[TSBLIP95](https://tsplib95.readthedocs.io/en/stable/pages/usage.html#rendering-problems)__

```
pip install tsplib95
```

__[DEAP](https://deap.readthedocs.io/en/master/api/tools.html#deap.tools.mutShuffleIndexes)__

```
pip install deap
```

__[SciPy](https://docs.scipy.org/doc/scipy/reference/index.html)__

```
pip install scipy
```

__[jMetalPy](https://pypi.org/project/jmetalpy/)__

```
pip install jmetalpy
```

### Running the code

To run the code as-is, install the required packages and run. 

To experiment with other TSP problems, download the files and update the example with the new source file and any updated paramenters.
For the continuous problems, you can experiment by updating the problem parameters or functions as indicated in the code. 


## Built With

* __[DEAP](https://deap.readthedocs.io/en/master/)__
* __[SciPy](https://docs.scipy.org/doc/scipy/reference/index.html)__
* __[jMetalPy](https://github.com/jMetal/jMetalPy)__


## Author

**S Crammond**
