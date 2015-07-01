Adaptive Simulated Annealing (ASA)

# Introduction #

Adaptive Simulated Annealing (ASA) is a C-language code developed to statistically find the best global fit of a nonlinear constrained non-convex cost-function over a D-dimensional space. This algorithm permits an annealing schedule for "temperature" T decreasing exponentially in annealing-time k, T = T\_0 exp(-c k^1/D). The introduction of re-annealing also permits adaptation to changing sensitivities in the multi-dimensional parameter-space. This annealing schedule is faster than fast Cauchy annealing, where T = T\_0/k, and much faster than Boltzmann annealing, where T = T\_0/ln k.  ASA has over 100 OPTIONS to provide robust tuning over many classes of nonlinear stochastic systems.


# Details #


Google Code has closed all new contributions of code as of mid-January 2014. The versions here should be considered deprecated. This project is still at:

http://www.ingber.com
AND
http://alumi.caltech.edu/~ingber
AND
http://asa-caltech.sourceforge.net

New versions may be added here under Source -> Browse -> ASA as long as this is permitted.