# bwstools

Tools for Best-Worst Scaling (a.k.a., MaxDiff) Designs

### Installation

An in-development version of this package can be installed using the `devtools` package:

```
devtools::install_github(markhwhiteii/bwstools)
```

### Contents

- Aggregate estimates, based on: analytical estimation of the multinomial logit model using `ae_mnl()`

- Individual estimates, based on: difference scores (best minus worst) using `diffscoring()`, random walks in directed networks using `walkscoring()`, empirical Bayes using `e_bayescoring()`, and Elo scores using `eloscoring()`

- A data.frame of balanced incomplete block designs for creating these studies

### Future

Planned for 1.0 release:

- A function to generate a balanced incomplete block design from the data.frame of designs

- Additional ways to calculate individual-level estimates
