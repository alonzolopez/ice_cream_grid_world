# Icecream_Grid_World

## Description
Consider the gridworld problem discussed in class, diagrammed below.  The system (with noisy gridworld dynamics) gets positive rewards $R_D, R_S$ for being in the two green ice cream store states, and negative reward $R_W$ for being in any red road state.
Formulate solve out a complete MDP problem, finding the optimal policy for a variety of task definitions.  Some questions to answer:

How would we formulate a problem that ends with a one-time (discounted) reward $R_D$ or $R_S$ whenever the system is in the respective ice cream store state as an infinite time horizon problem?  What if the reward was not discounted?
How instead would we formulate an infinite horizon, never-ending problem such that the system only achieves a reward upon entering the store rather than simply being in the store?
How many different optimal trajectories can we find by changing just the task definition ($R_D, R_S, R_W, \gamma$), each starting at the $\star$?
How do those trajectories / policies change as the system dynamics (error probabilities) change?
Under what conditions would it be an optimal strategy to visit both ice cream stores in the same trajectory?

See the Coauthor page corresponding to this code here: https://coauthor.csail.mit.edu/UCLA-ECE209AS-2-2020F/m/SpDFQHJYsXp4DmQqq

## Setup

### Virtual env setup
On Windows:
```bash
python -m venv in-class-env
.\in-class-env\Scripts\activate
```

### Install Requirements
On Windows:
```bash
pip install -r .\requirements.txt
```


## Running
Activate your virtual env if you haven't already done so with
```bash
.\in-class-env\Scripts\activate
```
Then launch the jupyter server with
```bash
jupyter notebook
```