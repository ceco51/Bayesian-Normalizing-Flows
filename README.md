# Assessing Parameter Identifiability in Agent-Based Models with Bayesian Amortized Inference

## Contents

- **Jupyter notebooks**  
  Two Jupyter (IPython) notebooks implementing the two toy models, along with the complete BayesFlow estimation pipeline, including simulation-based calibration (SBC) and parameter recoverability tests.

- **Synthetic datasets and posterior estimates**  
  - Four `.csv` files containing synthetic datasets, treated as empirical observations from four distinct opinion distributions observed in online communities (Figure 4, bounded confidence toy model).  
  - Corresponding `.csv` files containing the estimated posterior distributions for each dataset (Figure 5, bounded confidence toy model).

- **Trained model weights**  
  Serialized `.pkl` files containing the trained weights for all network architectures used in the two toy models, including both summary networks and cINNs.

- **Training diagnostics**  
  `.csv` files containing time series of training losses across epochs for all estimated models, enabling inspection of convergence and training dynamics.
