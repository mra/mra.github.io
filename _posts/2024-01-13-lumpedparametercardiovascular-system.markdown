---
layout: post
title:  "Lumped parameter cardiovascular system"
date:   2024-01-13 17:30:15 +0530
categories: LPM
img: CVSnetwork.jpeg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [OoC, MoC]
---

**Proposed system**

<p style="text-align:justify">Lumped parameter cardiovascular models for blood flow draw parallels with hydraulic systems, representing the cardiovascular system as a network of resistors, capacitors, and inductors. This analogy enables the modelling of blood vessel resistance, compliance, and inertance, facilitating the analysis of pressure and flow rates over time. The resulting ordinary differential equations (ODEs) describe blood flow and pressure dynamics, allowing for parameter estimation and simulation. We develop a zero-dimensional (0D)  model for the cardiovascular system, starting from the base model, which has the heart chambers, systemic and pulmonary circulation. Compartments are added to this model one by one – lungs, aorta, kidney, liver – tuning at each stage to form a comprehensive model that would simulate blood flow and pressures in these compartments for a healthy individual. The novelty here is that once we have the model, we want to use not just the clinical measurements but inform the model with underlying ventricular volumes and other information obtained from echocardiography to drive the model. Essentially, we fit/ feed the actual time series volume curve of the ventricles into this model. By integrating actual ventricular volume curves, the model becomes data-driven and is personalized for a specific individual. Finally, we incorporate pharmacokinetic models to assess treatment effects say, how it affects the functioning of lungs and overall cardiovascular response, and then connect all this to the model, which eventually could be used to predict patient response to medication under systemic sepsis.Lumped parameter cardiovascular models for blood flow draw parallels with hydraulic systems, representing the cardiovascular system as a network of resistors, capacitors, and inductors. This analogy enables the modelling of blood vessel resistance, compliance, and inertance, facilitating the analysis of pressure and flow rates over time. The resulting ordinary differential equations (ODEs) describe blood flow and pressure dynamics, allowing for parameter estimation and simulation. We develop a zero-dimensional (0D)  model for the cardiovascular system, starting from the base model, which has the heart chambers, systemic and pulmonary circulation. Compartments are added to this model one by one – lungs, aorta, kidney, liver – tuning at each stage to form a comprehensive model that would simulate blood flow and pressures in these compartments for a healthy individual. The novelty here is that once we have the model, we want to use not just the clinical measurements but inform the model with underlying ventricular volumes and other information obtained from echocardiography to drive the model. Essentially, we fit/ feed the actual time series volume curve of the ventricles into this model. By integrating actual ventricular volume curves, the model becomes data-driven and is personalized for a specific individual. Finally, we incorporate pharmacokinetic models to assess treatment effects say, how it affects the functioning of lungs and overall cardiovascular response, and then connect all this to the model, which eventually could be used to predict patient response to medication under systemic sepsis.</p>




![Cardiovascular system network]({{site.baseurl}}/assets/img/CVSnetwork.jpeg)




