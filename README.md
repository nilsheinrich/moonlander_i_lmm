# moonlander_i_lmm
linear mixed models analysis for first moonlander / dodgeAsteroids experiment

Data folder contains the various data sets obtained from experiment 1, even the ones that are not used in publications (saccades).There is one specific analysis script for each of the various data sets (one analysis script for close fixations, another one for distant fixations etc.)

Model selection - random effects are chosen based on BIC.
Hypothesis testing is done on the basis of parametric bootstraps with N=10000 iterations. An effect is considered significant if the 95% HDPI of  the distribution of values obtained from the bootstrap does not intersect with the 0-line.
