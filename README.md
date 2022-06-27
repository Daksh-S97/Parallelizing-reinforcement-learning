# Parallelizing-reinforcement-learning

A simple model for an agent moving in a grid. The movement of the agent is modellled on a Markov Decision Process.

Values of states are updated using a serial function and a kernel function implemented with CUDA. Significant speedup achieved for the parallel execution underlines the effectiveness of parallelization for this particular problem.  

Project developed as part of ME 574 Applied Parallel Computing (University of Washington, Spring 2022)
