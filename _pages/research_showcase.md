---
layout: archive
title: "Research Showcase"
permalink: /research_showcase/
author_profile: true
---

On this page, I will showcase some of the research research projects that I have worked on.


## Model-Based Clustering in Latent Factor Analysis
Ensuring fairness and interpretability in instruments like surveys, questionnaires and educational tests is crucial. One way to address this is by a Differential Item Functioning (DIF) analysis, which examines if different subgroups respond differently to a particular item, controlling for their overall latent construct level. Traditional DIF analysis methods require knowing the comparison groups (reference and focal groups) and anchor items (a subset of DIF-free items). Such prior knowledge may not always be available, and statistical methods have been proposed for DIF analysis when one piece of information is unknown. More specifically, when the comparison groups are unknown while anchor items are known, latent DIF analysis methods have been proposed that estimate the unknown groups by latent classes. When anchor items are unknown while comparison groups are known, methods have also been proposed, typically under a sparsity assumption – the number of DIF items is not too large. However, DIF analysis when both pieces of information are unknown has not received much attention. Me and my collaborators have proposed a general statistical framework under this setting. In the proposed framework, we model the unknown groups by latent classes and introduce item-specific DIF parameters to capture the DIF effects. Assuming the number of DIF items is relatively small, a regularised estimator is proposed to simultaneously identify the latent classes and the DIF items. A computationally efficient Expectation-Maximisation (EM) algorithm is developed to solve the non-smooth optimisation problem for the regularised estimator. 

In the figure below, we illustrate how estimates of the easiness level of each question in a university placement test are adjusted for two identified latent clusters: one cluster that reacts to the time-limit of the test by engaging in rapid response behavior towards the end of the test, and one baseline cluster which does not change behavior.

<div style="text-align: center;">
    <img src="/images/Param_estimates.png" alt="Figure Description" style="width:65%;">
</div>

The proposed framework is currently being extended in a number of directions, including statistical inference for the DIF effect. Please let me know if you are working with categorical data, possibly with large numbers of measurement units (respondents/costumers/students etc) and variables, and are interested in multi-group analysis. I am both interested in collaboration and consulting on these matters.

