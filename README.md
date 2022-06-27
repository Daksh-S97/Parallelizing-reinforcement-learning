# Parallelizing-reinforcement-learning

A simple model for an agent moving in a grid. The movement of the agent is modellled on a Markov Decision Process.

Values of states are updated using a serial function and a kernel function implemented with CUDA. Significant speedup achieved for the parallel execution underlines the effectiveness of parallelization for this particular problem.  
