---
title: "A capture-recapture hidden Markov model framework for register-based inference of population size and dynamics"
collection: publications
category: manuscripts
permalink: /publication/HMM_CR
excerpt: ''
date: 2026-03-26
venue: 'TBC'
paperurl: 'https://arxiv.org/abs/2603.24643'
citation: 'Brown, L. Y., Matechou, E., Santos, B., & Mussino, E. (2026). A capture–recapture hidden Markov model framework for register‑based inference of population size and dynamics. arXiv. https://arxiv.org/abs/2603.24643'
---
Submitted to Annals of Applied Statistics.

## Abstract
Accurate inference on population dynamics, such as migration and changes in population size, is essential for policymaking, resource allocation and demographic research. Traditional censuses are expensive, infrequent and not timely, leading many countries to adopt administration registerbased approaches to replace or complement them. A primary challenge in this shift is that such registers are incomplete: even when individuals are present in the population, their activities may not generate records in specific registers in a given period, resulting in false negative observation error at the register level. Conversely, some registers do not constitute a direct “sign of life” from the individual but arise from administrative or household-level processes, so that individuals may appear in registers despite being absent, leading to false positive observation error. Existing approaches for register data often either rely on ad-hoc decisions that ignore one or both types of observation error, or only offer inference on population snapshots but not on dynamics, or are computationally too slow to be used in practice. We propose a scalable framework for inferring population size and dynamics from register data, building on Cormack-Jolly-Seber type capture-recapture models formulated as hidden Markov models. Inference is carried out using maximum likelihood estimation, with uncertainty quantified via the Bag of Little Bootstraps. The model accounts for temporary emigration, incorporates an arbitrary number of possibly interacting observation registers subject to false positive and false negative observation error, and allows observation probabilities to vary with individual characteristics and unobservable heterogeneity. We illustrate the approach using Swedish population registers, where overcoverage - individuals registered as living in the country although they are no longer present - provides a motivating example. The application yields new insights into population dynamics and individual trajectories, demonstrating the potential of the proposed model for register-based demographic research.
