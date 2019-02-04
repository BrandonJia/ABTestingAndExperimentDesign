<p>This is a case where we used <b>Kernel Density Estimate</b> and <b>Bootstrapping</b> to make wise business decision.</p>

# Kernel Density Estimate
[<p><b>Kernel Density Estimate(KDE)</b>](https://www.google.com) is a non-parametric way to estimate the probability density function of a random variable. If you are not familiar with KDE, just think it is a deriviative from histogram. I am not going to demonstrate the knowledge behind KDE, since it may require Calculas knowledge. </p>

# Bootstrapping
[<b>Bootstrapping</b>](https://en.wikipedia.org/wiki/Bootstrapping_(statistics)) is common idea in machine learning, specifically, in Ensemble Model (bagging). The basic idea is that sampling from dataset with replacement. In our case, we conduct bootstrapping 500 times in analyzing A/B testing results in order to prove the statistically significnat different amont two groups.

Let's see how I use this two power tools to assist business decision.
