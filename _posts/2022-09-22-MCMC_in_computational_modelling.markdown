---
layout: post
title:  "Markov Chain Monte Carlo"
date:   2022-09-12 16:30:15 +0530
categories: Computational Modelling
---

**MCMC**

<p style="text-align:justify">
If we can't integrate something, approximate it by sampling.</p>

MCMC is a sampler : it is based on likeliness and acceptance ratio. At the end of the process a posterior distribution or a chain of the parameters are obtained. We cannot say a particular theta, which is a parameter set is best fit.

We will need a function which returns a number corresponding to how good a fit your model is to the data for a given set of parameters.

Bayesian thinking is combining prior beliefs and current events. The posterior can be computed say the probability that there will be rice for lunch today.

One MCMC method is the Metropolis Hastings algorithm. It can be used to compute distribution over the parameters given a set of observations and a prior belief. For this method, we need a proposal distribution to randomly walk in the distribution space. So at each point a new step is taken which is based on some rules of acceptance. If the current distribution is accepted it moves closer to the true destination or it will take a step back.

Useful links:

1.	[Markov Chain Monte Carlo (MCMC) methods](https://www.statlect.com/fundamentals-of-statistics/Markov-Chain-Monte-Carlo)



