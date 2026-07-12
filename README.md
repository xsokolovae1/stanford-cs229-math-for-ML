# Stanford CS229 — Math for ML

A from-scratch Python/NumPy implementation of the mathematics behind
Stanford's CS229, Machine Learning.

## About the course

CS229 is Stanford's introductory graduate machine learning course, taught by
Andrew Ng and the CS229 teaching staff. It covers statistical pattern recognition, linear and non-linear regression, non-parametric methods, the exponential family, GLMs, support vector machines, kernel methods, deep learning, model and feature selection, learning theory, clustering, density estimation, the EM algorithm, dimensionality reduction, ICA, PCA, reinforcement learning and adaptive control, Markov decision processes, approximate dynamic programming, and policy search.  Unlike more applied ML courses, CS229 emphasizes deriving each algorithm from first principles — the probabilistic assumptions behind a loss function, the optimization problem being solved, the theoretical guarantees — rather than treating models as ready-made library calls.

## What this repository is

Each notebook here derives the math for one topic by hand (in LaTeX,
alongside the reasoning) and implements it in NumPy without relying on
`scikit-learn` or other ML libraries for the core algorithms.

## Topics covered

- Supervised learning — linear regression, locally weighted regression,
  logistic regression, generalized linear models, generative learning
  algorithms (GDA, Naive Bayes), support vector machines
- Learning theory — bias/variance tradeoffs, regularization, model selection
- Deep learning — neural networks and backpropagation from scratch
- Unsupervised learning — k-means, Gaussian mixture models, the EM
  algorithm, PCA, ICA
- Reinforcement learning and control — MDPs, value/policy iteration, LQR
