# Artificial Bee Colony (ABC) Algorithm
![Swarm_intelligence](https://img.shields.io/badge/Swarm%20intelligence%20-%20brown?style=plastic)
![Artificial_Bee_Colony](https://img.shields.io/badge/Artificial_Bee_Colony-2005-%20teal?style=plastic)
![License](https://img.shields.io/badge/license%20-%20MIT%20-%20darkred?style=plastic)
![Python Version](https://img.shields.io/badge/Python-3-%20teal?style=plastic)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Open_Issues](https://img.shields.io/badge/Issues%20-%200%20-%20orange?style=plastic)

## Description
This repository contains a Python implementation of the Artificial Bee Colony (ABC) algorithm. ABC is a population-based metaheuristic for continuous optimization, inspired by the foraging behavior of honey bees. It leverages self-organization and division of labor to find optimal solutions.

## The ABC algorithm operates with three types of bees:
1. Employed Bees: Exploit the information of food sources.
2. Onlooker Bees: Choose food sources based on their quality.
3. Scout Bees: Search for new food sources when old ones are abandoned.

The algorithm iteratively refines a population of candidate solutions to converge towards the optimal solution. It can be applied to both minimization and maximization problems.

## Installation
1. Clone the repository: `git clone https://github.com/KhalidMustafaElenani/Artificial-Bee-Colony-optimization-Algorithm.git`
2. Navigate to the project directory: `cd Artificial-Bee-Colony-optimization-Algorithm`

## Usage Examples
  - Run the PSO algorithm by executing the main.py file: `python ABC_algorithm.ipynb`

## Example Output -> Minimization
```
[$]Iteration: 9
=========================================================================================================
	Population	 |	  Objective Values	|	  Fitness Values	|	Counters
---------------------------------------------------------------------------------------------------------
[-0.67  1.24  0.69 -5.39]| 		31.56		|		0.03		|  	  2
[-0.66 -3.71  5.73  1.4 ]| 		49.02		|		0.02		|  	  0
[-5.47  2.23 -1.13  3.01]| 		45.19		|		0.02		|  	  0
[-8.54  0.27  1.59  0.93]| 		76.46		|		0.01		|  	  0
[-0.28  0.71  3.88  3.36]| 		26.91		|		0.04		|  	  0
=========================================================================================================
[$]Iteration: 10
=========================================================================================================
	Population	 |	  Objective Values	|	  Fitness Values	|	Counters
---------------------------------------------------------------------------------------------------------
[-0.67  1.24  0.23 -3.64]| 		15.27		|		0.06		|  	  1
[-0.66 -3.71  4.07  1.4 ]| 		32.74		|		0.03		|  	  0
[-5.47  2.23 -1.13  3.01]| 		45.19		|		0.02		|  	  1
[-8.54  0.27  1.59  0.93]| 		76.46		|		0.01		|  	  1
[-0.28  0.71  3.88  3.36]| 		26.91		|		0.04		|  	  2
=========================================================================================================
As a Minimization Problem:
---------------------------
Best Solution: ['-0.28', '0.71', '3.88', '3.36']
Best Fitness: 0.01
```

## Example Output -> Maximization
```
[$]Iteration: 9
=========================================================================================================
	Population	 |	  Objective Values	|	  Fitness Values	|	Counters
---------------------------------------------------------------------------------------------------------
[-0.11 -4.99  1.24 -1.34]| 		28.2		|		0.03		|  	  2
[-8.88 -3.23 -7.63  2.13]| 		152.01		|		0.01		|  	  0
[-0.03 -2.24 -9.73 -4.75]| 		122.23		|		0.01		|  	  0
[-2.23 -4.12 -2.39 -4.77]| 		50.43		|		0.02		|  	  0
[ 0.2  -2.25  0.32 -2.99]| 		14.15		|		0.07		|  	  0
=========================================================================================================
[$]Iteration: 10
=========================================================================================================
	Population	 |	  Objective Values	|	  Fitness Values	|	Counters
---------------------------------------------------------------------------------------------------------
[-0.11 -4.43  1.24 -1.34]| 		23.01		|		0.04		|  	  1
[-8.88 -3.23 -7.63  2.13]| 		152.01		|		0.01		|  	  2
[-0.03 -2.24 -9.73 -4.75]| 		122.23		|		0.01		|  	  1
[ 0.52 -4.12 -2.39 -4.77]| 		45.75		|		0.02		|  	  0
[ 0.2  -2.25 -0.3  -2.99]| 		14.14		|		0.07		|  	  1
=========================================================================================================
As a Maximization Problem:
---------------------------
Best Solution: ['0.20', '-2.25', '-0.30', '-2.99']
Best Fitness: 0.07
```

## Notes
For more details on the algorithm's functionality and setup, refer to the [NOTES.md](NOTES.md).
