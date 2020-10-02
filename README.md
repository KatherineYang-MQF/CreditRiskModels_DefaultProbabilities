Introduction: This is a course project.

Contents: Theoretical basis is credit risk models: Given a portfolio of 30 assets under normal distribution and Student-t distribution, use Monte Carlo simulation to estimate default probabilities within specified default times.

Programming Language: Python

Steps:

1. Generate outputs of normal distribution to build a matrix of 30X250,000.
30 stands for 30 assets, and 250,000 stands for 250,000 times of Monte Carlo simulation.
2. Given correlation of 0%, 20%, or 40%, among 30 assets, generate cumulative distribution function of each asset.
3. According to formulas, calculate default time of each asset.
4. Now we can calculate default probabilities.
For example, we want to calculate default probabilities of within 1 year and more than 9 assets default.
We count how many simulation has more than 9 assets default, and divide this count by times of simulation, i.e. 250,000, and this is the default probability.
