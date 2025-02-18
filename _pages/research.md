---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Hierarchical Latent Class Models for Mortality Surveillance

### Overview
Monitoring causes of death is crucial for understanding disease burdens and shaping public health interventions. In many low-resource settings, **verbal autopsy (VA)** is the primary tool for cause-of-death surveillance, relying on structured interviews with caregivers of the deceased. However, existing VA models often require **extensive domain knowledge** or **large labeled datasets**, making them **ill-suited for emerging diseases** with rapidly evolving epidemiological patterns.

### Our Contribution
In our research, we propose a **Bayesian hierarchical latent class model** that accounts for **partially verified VA data**, enabling robust **cause-of-death estimation** under real-world data constraints. Key innovations include:

- **Hierarchical Latent Class Modeling**  
  - Captures the joint distribution of symptoms and their shifts over time and across subpopulations.
  - Accounts for **selective verification bias**, a common issue where cause-of-death verification is **not randomly assigned**.

- **Structured Priors for Improved Estimation**  
  - Incorporates **domain adaptation techniques** to refine estimates for **small subpopulations**.
  - Allows for **flexible borrowing of information** across related demographic groups.

- **Application to COVID-19 Surveillance in Brazil**  
  - We apply our model to **COVID-19 mortality data** in Brazil (2021), demonstrating how traditional models suffer from bias under selective verification.
  - Our method produces **more accurate prevalence estimates** compared to existing approaches.
 
![Latent Class_Profiles](_images/R1_latent_class_profiles.png)

### Why This Matters
- **Adaptable to Future Public Health Crises**  
  - The framework can be **quickly deployed for new diseases** where **symptom-cause relationships are initially unknown**.
  
- **More Reliable Mortality Estimates**  
  - Reduces **bias** from non-random cause-of-death verification, critical for **global disease surveillance**.

- **Bridging Statistical Innovation with Real-World Impact**  
  - This research integrates **Bayesian inference**, **semi-supervised learning**, and **domain adaptation** to enhance **public health decision-making**.

### Read More
📄 **[Full Paper: Hierarchical Latent Class Models for Mortality Surveillance](#)** *(https://arxiv.org/abs/2410.09274)*
