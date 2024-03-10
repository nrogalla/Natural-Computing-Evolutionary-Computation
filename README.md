# Natural Computing Assignment 5: README

This repository contains the Python code for Assignment 5 of the Natural Computing course. It includes a Python notebook that demonstrates the use of genetic algorithms (GAs) for solving binary sequence optimization problems and explores the impact of mutation on the algorithm's performance. The assignment also investigates the use of a tournament-based genetic algorithm for generating sequences that match a target string, leveraging concepts such as mutation rate, crossover probability, and tournament selection.

## Dependencies

- Python 3.x
- Numpy
- Matplotlib
- Seaborn
- Logomaker

To install the dependencies, run:

```
pip install numpy matplotlib seaborn logomaker
```

## Contents

- **Binary Sequence Optimization**: The notebook implements functions to generate random binary sequences, mutate them, and evaluate their fitness compared to a target binary sequence. It demonstrates the use of a simple genetic algorithm (GA) to evolve a population of binary sequences towards a goal sequence.

- **Tournament-Based Genetic Algorithm for Sequence Generation**: Implements a genetic algorithm that uses tournament selection to evolve sequences towards a target string. The effectiveness of different mutation rates and the impact of incorrect parent selection are explored.

- **Analysis of Genetic Algorithm Performance**: The assignment includes experiments to compare the performance of the GA with correct and incorrect parent selection strategies. It also examines the algorithm's stochastic nature by running multiple iterations and averaging the results.

- **Sequence Logo Generation**: As part of the exploration of genetic algorithms, the notebook demonstrates the generation of sequence logos, which are graphical representations of the nucleotide or amino acid patterns within a multiple sequence alignment.

- **Evolutionary Algorithm for the Traveling Salesman Problem**: Introduces a simple evolutionary algorithm to solve the Traveling Salesman Problem (TSP) and compares its performance with a memetic algorithm that combines a GA with local search optimization (2-opt algorithm).


## Files and directories

- **exercise4_graphs_solutions.ipynb**: This notebook presents the graphs for an evolutionary algorithm (EA) with no convergence stop and a memetic algorithm (MA) with convergence stop (due to high computational time)

- **exercise4_solutions.ipynb**: Discusses Exercise 4 with an implementation for both EA and MA with no convergence stop. It also highlights an issue with the comparison function running indefinitely (due to no convergence stop).

- **exercise5_4_NC_finalresults_nographs.ipynb**: Contains the final results for Exercise 5.4, including 10 runs with convergence stop but without graphical representations.

- **exercise_solutions.ipynb**: Offers solutions for Exercises 2 to 3, providing comprehensive coverage of the exercises' requirements and solutions.

## Running the Notebook

1. Ensure all dependencies are installed.
2. Open the Jupyter notebook in your preferred environment (e.g., JupyterLab, classic Jupyter Notebook).
3. Execute the cells in order to reproduce the results and analyses presented.

## Note

This repository is intended for educational purposes and the exploration of genetic algorithms and their applications in optimizing sequences and solving combinatorial problems like the TSP.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

