---
title: "A Capture-Recapture Model with Temporary Emigration for Estimating Population Size from Incomplete Registers"
collection: talks
type: "Talk"
permalink: /talks/SWE-REG
venue: "Elite Hotel Carolina Tower, Stockholm, Sweden"
date: 2024-12-02
location: "Stockholm, Sweden"
slides_url: "https://lucyybrown.github.io/files/Stockholm Slides.pdf"
---

Presentation at the The Swedish Register-Based Research Summit in Stockholm in December 2024. 

## Abstract
Overcoverage occurs when individuals are registered as living in a country but in fact live elsewhere (imperfect emigration registration) or have passed away and their death was not recorded (imperfect death registration). Overcoverage can lead to serious bias in population estimates, negatively influencing policymaking and research.  Demographers in Sweden have been working towards estimating overcoverage, and in turn the true population size by using Swedish Population registers. Existing approaches rely on multiple systems estimation (MSE) and only consider annual snapshots of the register data. Instead, for this project, we have employed a longitudinal approach, following individuals, and hence registers, over different years. The proposed approach builds on capture-recapture (CR) models, with a hidden Markov model (HMM) formulation, providing an efficient model-fitting framework that accounts for the observations (registers) as well as inferring the latent states (presence in the country). The model accounts for temporary emigration and uses multinomial regression to incorporate an arbitrary number of, possibly interacting, observation lists, whilst accounting for individual heterogeneity in the observation and the latent process. The model has been employed on simulated and real data, providing new insights into population dynamics and individual trajectories. While this model was built with the aim to estimate overcoverage and the true population size from incomplete registers in Sweden, it naturally applies to other similar countries, such as Norway.    

[**[Download Slides]({{ page.slides_url }})**]
