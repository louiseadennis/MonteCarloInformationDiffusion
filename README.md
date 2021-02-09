# MonteCarloInformationDiffusion
A Monte Carlo Simulator for Studying Information Diffusion in Social Networks modelled as Markov Chains

Arguments:

1st Argument: Number of Nodes in Graph
2nd Argument: filename

Results (digest average over 100 runs and raw data) will be stored in 

results/filename
results/raw_filename

Simulator.py - generates data for increasing number of messages (in multiples (1-6) of nodes on the graph)
SimulatorProbExp.py - generates data for increasing probabilities that someone will change their mind (from 0.1 - 0.5) for 3*n messages (where n is the number of nodes in the graph)
