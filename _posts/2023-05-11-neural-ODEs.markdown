---
layout: post
title:  "Neural Ordinary Differential Equation"
date:   2022-08-22 17:30:15 +0530
categories: NODEs
---

**Neural ordinary differential equation for parameter estimation**
<p style="text-align:justify">Ricky Chen (2018) introduced a new family of differential equation network models</centre></p>

A broad outer view:

*	 parameterize the derivative of the hidden state using a neural network

*	output of network computed using a black box differential equation solver.

Basically neural ODEs map input variables to derivative of hidden variables, which may be integrated before use. The output is supposed to pass through ODE solver.

The core idea is to use NN in parameter estimation using a two-stage approach. Neural ODE as data-driven model.

Once NODE is trained derivative estimates are obtained by integrating trained NODE from t=0 to tf of measured data using same process as measured data.







