---
layout: page
title: Research
subtitle: Physics-based digital twins, PBPK modeling, and AI-assisted simulation.
permalink: /research/
---

## Whole-body cardiovascular digital twin

A closed-loop, lumped-parameter (RCR) circulatory network for whole-body hemodynamics. The model captures organ-specific pressure and flow under physiological and disease conditions and serves as the backbone for downstream PK/PD predictions across cardiovascular and interstitial routes of administration.

**Methods:** Blood flow–electrical-system analogy (resistance, compliance, inertance); ODE integration in Python/JAX; parameter calibration via Bayesian and gradient-based methods.

## Whole-body lymphatic transport

A comprehensive computational framework for whole-body lymphatic transport simulation—an underdeveloped but pharmacokinetically critical compartment for subcutaneous biologics, mAbs, and immuno-oncology agents.

**Status:** Manuscript submission-ready.

## DigiLoCS — digital liver-on-chip

A predictive organ-on-chip simulator that integrates biological factors, device hardware, and physicochemical drug properties to reproduce hepatic drug distribution in liver-on-chip platforms. The framework differentiates active vs. passive hepatic processes and bridges in vitro findings to clinical predictions through IVIVE.

**Published:** Aravindakshan MR _et al._ _DigiLoCS: A leap forward in predictive organ-on-chip simulations._ **PLOS ONE** 20(1): e0314083 (2025).

## Cranial–spinal CSF & Circle of Willis coupling

A coupled cranial–spinal lumped-parameter model linking the Circle of Willis with the cerebrospinal fluid (CSF) system. Captures Monro–Kellie volume coupling, intracranial pulsatility, and cerebrovascular autoregulation—directly relevant to intrathecal delivery of genetic medicines to the CNS.

**Status:** Manuscript in preparation.

## Insulin–glucose dynamics in type 2 diabetes

An extended oral minimal model incorporating adipokine (leptin) and BMI coupling, used to distinguish parameter signatures between obese and non-obese T2D phenotypes. Applied to rural Indian community-health data to identify three distinct patho-clinical clusters.

**Published:** _DNA and Cell Biology Reports_ (2024); _BMJ Open Diabetes Research & Care_ (2022).

## A DSL for compartmental PK + AI agents

A domain-specific language for compartmental PK models that lets AI agents reliably author, validate, and iterate on PBPK models. Integrates a hierarchy of agents into the **Design–Make–Test–Analyze (DMTA) cycle** to accelerate the discovery, development, and commercialization of innovative therapeutics.

**Stack:** Python, JAX, custom DSL, LLM-based agent orchestration.

---

For full publication details, see the [Publications]({{ '/publications/' | relative_url }}) page.
