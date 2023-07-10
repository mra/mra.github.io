---
layout: post
title:  "Neural Ordinary Differential Equation"
date:   2022-08-22 17:30:15 +0530
categories: NODEs
img: deeplearning.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [DeepLearning, Optimisation]
---

**Neural ordinary differential equation for parameter estimation**
<p style="text-align:justify">Ricky Chen (2018) introduced a new family of differential equation network models</centre></p>

A broad outer view:

*	 parameterize the derivative of the hidden state using a neural network

*	output of network computed using a black box differential equation solver.

Basically neural ODEs map input variables to derivative of hidden variables, which may be integrated before use. The output is supposed to pass through ODE solver.

The core idea is to use NN in parameter estimation using a two-stage approach with neural ODE as data-driven model.

Once NODE is trained derivative estimates are obtained by integrating trained NODE from t=0 to tf of measured data using same process as measured data.

Advantages:

*	minimal prior knowledge of their values
*	minimal parameter scaling
*	potential to improve parameter estimates by solving NLP with global optimal solvers
*	computationally flexible - bypass integration

![Optimisation]({{site.baseurl}}/assets/img/deeplearning.jpg)

**Details on Implementation**

Basics of PyTorch required

Prediction: Pytorch model

Gradients computation: Autograd

Loss computation: Pytorch loss

Parameter updates: Pytorch optimizer

Author William Bradley shared a simple kinetics model with three concnetration equations.

Pytorch implementation of ODE solvers - torchdiffeq

AG-fns: odeint(), class Eul(object): init,rk4_step_fn,integrate, class store: reset,l_update,update
Main-file: class lambda - init(),forward() ; class ODEFunct

Stage-1 

First NN (Lambda) 

input:initial values and param values
output: derivatives 
Integrate to get conc (plotting)

->Obtained derivatives as training data

Second NN

input: input size, hidden_l_size, output size
output: derivatives
loss fn and optimizer

odeint takes NN model as input in both cases and at each time point again calls NN model - implemented using Euler method

To implement stage 2

1.	We have derivatives from NODE
2.	Using data calculate the RHS of equations to get derivatives 
Minimize error to get parameters of MM

In stage 2 the neural ODE need not be used. Instead use predicted derivatives of the trained NODE at times where training data is available along with mechanistic equations to estimate mechanistic parameters.


Every nn.Module subclass implements the operations on input data in forward method.
nn.Linear applied linear transformation on input using stored weights and biases -> a = wx + b

odeint(NN model): y_NN prediction
pass to equation with init parameter values -> derivatives (using detach from NN fn)

**Challenge**

Less observables, more equations (coupled equations like in insulin-glucose systems) - how to make the method work? 








