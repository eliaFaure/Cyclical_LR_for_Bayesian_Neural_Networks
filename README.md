# Cyclical_LR_for_Bayesian_Neural_Networks

In this brief work, I implement the approach proposed by https://arxiv.org/abs/1902.03932.
The key idea is to apply a cyclical learning rate decay to encourage exploration of multimodal surfaces, preventing the model from getting stuck in a single mode.
Specifically, I implement standard Monte Carlo methods such as LSGD and Hamiltonian Monte Carlo, and compare their accuracy against their cyclical learning rate variants.

