---
layout: post
title:  "Proposal on organ-on-chip"
date:   2022-03-22 17:30:15 +0530
categories: OoC modelling
---

**Computational modeling of crosstalk of adipocytes and β-cell in insulin-glucose
pathway through organ-on-chip**

Obesity is a key risk factor of type 2 diabetes mellitus (T2DM). Obesity-associated insulin resistance (IR), followed
by a gradual decline in pancreatic β-cell function, leads to T2DM. However, studies have reported that β-cell function
may also increase with adiposity independent of IR. Also, adipokines are reported to play a protective role for β-cells
in the context of T2DM. As the secretory patterns of visceral adipose tissue (VAT) and subcutaneous adipose tissue
(SAT) are different, their impacts over β-cells are expected to differ. Reports of non-obese T2DM (having a greater
proportion of VAT) with predominant β-cell defect as a distinct clinicopathological entity makes a case for investigating
the crosstalk between adipose tissue and pancreatic β-cells in T2DM pathogenesis for non-obese people. Hence, we
propose to include the role of VAT and SAT over β-cells in the conventional model of insulin-glucose (IG) pathway
as an extended IG (XIG) pathway. A study based on clinical data to identify distinct patho clinical clusters among
patients with uncontrolled type 2 diabetes has been made by the authors [1].

We propose a parameterised ordinary differential equations(ODE) model that incorporates the crosstalk between
adipocytes and β-cells of the pancreas. Adequate time-series data under well-controlled experimental conditions is
needed to determine the model parameters for individual subjects with different VAT and SAT proportions. In this
context, a co-culture model of organ-on-chip (OOC) is considered, which accommodates the XIG pathway involving:

a. adipocytes (VAT and SAT separately) and 
b. β-cells of islets of Langerhans. 

Such an OOC would allow regulated
administration of glucose to excite the XIG pathway and observe the resulting changes in insulin and various adipokines
and gather time-series data (at all time points) to identify the model parameters. This model augments Bergman’s minimal model [2] to include the role of adipokines.

This model enables experimental estimation of parameters (patient-specific corresponding to individual body distribution of VAT and SAT differing across age groups, sex, ethnicity, etc.) governing the working of the model.
Subsequently, it would be desirable to determine the ranges of various parameters and limit the observables needed to
model these pathways in patients. In the OOC, adipocytes (VAT and SAT) are cultured in the basolateral chamber
and β-cells in the apical chamber, interacting through circulating plasma via the porous membrane. Two experimental
setups are proposed. The first setup will be an acute system of two hour duration, monitoring the insulin secretion
by mimicking the feeding pattern and the second setup will be a long term experiment (about 24 hours) involving
adipocytes from different individuals having different adipokine profiles. The second setup will monitor any difference
in insulin secretion in the presence of adipokines. Use of human adipocytes and β-cell lines from mice is planned. The
experiments will be performed using a single OOC involving the co-culture of adipocytes and β-cells, as in Figure 1.

![Figure 1: OOC experimental setup, the co-culture model and its cross-sectional view](setup_synvivo.jpeg "")

 Model parameter determination
through time-series observations can be done using the OOC. The model behaviour across age groups, sex, ethnicity,
etc. can be studied. Possible beneficial effects of cross-talk between adipose tissue and beta-cells is to be explored.
This is likely to be the first study to investigate the role and dynamics of human adipose tissue secretion over beta
cells in the context of non-obese T2DM. Beta cell impairment being the predominant pathology in non-obese T2DM,
this study will help in identification of the precise pathology behind non-obese T2DM thereby raising the possibility
of a precise prevention and therapy in non-obese T2DM. In the future, the work is expected to proceed as follows:

a) prediction of the behaviour of non-obese type 2 diabetic patients based on their glucose and insulin levels and the
profile of their adipose tissue across various patient groups and

 b) development of more advanced models to include
the roles of liver cells in the pathophysiology of T2DM.

