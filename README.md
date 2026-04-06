## Current Issues

the network seems to be finding that the most optimal solution is to guess the same output for every input

reason (i think): when scaling down difference is so much smaller than the current data that what seems close in the scaled down version is not as close.

## Current Architecture

4-layer neural net

input (2x1) -> 100 neurons ReLu -> 100 neurons ReLu -> 100 neurons ReLu -> 1 neuron -> output


training:
- mini batch sgd
- variational learning rate
- L2 Reg
- Input Normalisation
