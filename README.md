# npcausal

This package provides a variety of tools for nonparametric estimation of causal effects across a wide range of settings. The methods are based on the theory of influence functions, and can incorporate flexible machine learning and high-dimensional regression tools, while still yielding inference in the form of confidence intervals and hypothesis tests. Many of the methods are doubly robust.

## Installing

To install and load this package in R from GitHub, run the following commands:

```
install.packages("devtools")
library(devtools) 
install_github("ehkennedy/npcausal")
library(npcausal)
```
Along with standard treatment effect estimators, npcausal can also implement methods from my papers, including:

    Kennedy EH, Balakrishnan S, G'Sell M. Sharp instruments for classifying compliers and generalizing causal effects. [arxiv:1801.03635](https://arxiv.org/abs/1801.03635)
    Kennedy EH. Nonparametric causal effects based on incremental propensity score interventions. Journal of the American Statistical Association. (to appear). arxiv:1704.00211​
    Kennedy EH, Ma Z, McHugh MD, Small DS. Nonparametric methods for doubly robust estimation of continuous treatment effects. Journal of the Royal Statistical Society: Series B. 2017; 79(4): 1229-1245. doi:10.1111/rssb.12212 (arxiv:1507.00747)
    Kennedy EH, Sjolander A, Small DS. Semiparametric causal inference in matched cohort studies. Biometrika. 2015; 102(3): 739-746. doi:10.1093/biomet/asv025
