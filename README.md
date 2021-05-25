# PGMs
Notes on probabilistic graphical models (PGMs)

## Bayesian networks

A Bayesian network (BN):
- is a directed DAG <img src="https://render.githubusercontent.com/render/math?math=G">
- nodes represent random variables <img src="https://render.githubusercontent.com/render/math?math=X_1, ..., X_n">
- for each node we have a conditional probablility distribution (CPD) represented by <img src="https://render.githubusercontent.com/render/math?math=P(X_i|Parents_G(X_i))">
- a Bayesian network represents a joint distribution of all its nodes via the chain rule for BNs: <img src="https://render.githubusercontent.com/render/math?math=P(X_i, ..., X_n) = \Pi P(X_i|Parents_G(X_i))">
