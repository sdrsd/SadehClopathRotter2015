## General description

Simulating and analysing plastic recurrent networks as in: Sadeh, Clopath and Rotter. Emergence of Functional Specificity in
Balanced Networks with Synaptic Plasticity. [PLOS Computational Biology 2015](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004307).

### List of files

(1) [network_simulator.py](network_simulator.py)

Simulates a network of integrate-and-fire neurons with plastic
synapses using Exact Integration

(2) [params.py](params.py)

Default set of parameters in (Table 1 of) [1]

(3) [network_run.py](network_run.py)

Uses network_simulator.py and runs a simulation of a plastic recurrent network.

(4) [plot_figures.py](plot_figures.py)

Reads the results from network_run.py and plots Figures 1 and 3 in [1]

### To simulate the network and plot the figure(s):

First run (3): simulates the network and saves the results;

then run (4): reads the results and plots Figures 1 (top below) and
3 (2 bottom below):

<img src="./figure_1.png" alt="Figure 1" width="550">

<img src="./figure_3A-C.png" alt="Figure 3ABC" width="550">

<img src="./figure_3D-G.png" alt="Figure 3DEFG" width="550">


