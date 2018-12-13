# Explaining and Exploring Pattern Completion

This repository contains Jupyter notebooks to recreate pattern completion simulations I have created, modeled after *Synaptic mechanisms of pattern completion in the hippocampal CA3 network* by Guzman, Schlogl, Frotscher, and Jonas (2016). Details can be found in the report I wrote to accompany these simulations: [pattern-completion.pdf]()

There are three Jupyter notebooks to work with:

*  [PatternCompletion_Walkthrough.ipynb]() includes code to create the visualization of the networks (e.g. the figure below), and walks through the simulation details slowly.
*  [PatternCompletion_addMotifs.ipynb]() includes code to increase the number of select connectivity motifs in the underlying connectivity matrix.
*  [PatternCompletion_Experiments.ipynb]() includes code to run experiments on how pattern completion varies as a function of the connectivity of the network, the number of patterns loaded, and the increase of select connectivity motifs.


![alt](viz-example.png)

This work was done as the final project of the class [Computation and the Brain](https://computationandbrain.github.io/about/) taught by Professor Christos Papadimitriou in Fall 2018 in the Computer Science Department of Columbia University.

## Set Up

These simulations were developed in Python 3.6 and have the following dependencies:

```
numpy
scipy
matplotlib
```

Please let me know if you have any issues.