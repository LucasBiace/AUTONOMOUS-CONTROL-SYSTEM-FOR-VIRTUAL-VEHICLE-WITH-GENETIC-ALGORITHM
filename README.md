# AUTONOMOUS-CONTROL-SYSTEM-FOR-VIRTUAL-VEHICLE-WITH-GENETIC-ALGORITHM
This repository contains the complete project developed in Unity Engine with C# for the simulation and training of an autonomous vehicle using artificial neural networks optimized by a Genetic Algorithm (GA). The project was conceived in an academic context in order to test methods of controlling autonomous vehicles

The main objective is to train a virtual car to navigate a track without collisions and in the shortest time possible, using only simulated sensors (raycasts) and a neural network that makes decisions based on detected distances. The learning process is entirely autonomous, with no human intervention during training, and is driven by a genetic algorithm that performs selection, crossover, and mutation of the best individuals in each generation.
The project includes:
- Modeling and simulation of a track and car in a 2D environment using Unity
- Environmental perception system with 11 sensors (raycasts) in different directions
- Neural network with 12-8-6-2 architecture:
- 12 inputs (11 distances + car speed)
- 2 outputs (horizontal and vertical movement)
- 2 hidden layers
- Configurable genetic algorithm with parameters such as mutation rate, mutation strength, and population size
- Automatic neural network optimization across generations, including elitism, mutation, and weight crossover
- Early discarding system for underperforming individuals to speed up training



- Requirements
- Graphics card
- Unity version 6000.0.38f1

