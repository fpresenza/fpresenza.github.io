---
layout: page
permalink: /research/
title: Research
description: Research interests and current directions.
nav: true
nav_order: 2
---

The central object of my research is the modeling, design, and analysis of distributed estimation and control methods for multi-robot systems.
To do this I combine tools from graph theory, optimization, nonlinear control, event-driven systems, and multi-agent learning.

## Rigidity Theory
One of my main research directions focuses on the localizability of multi-robot systems performing distributed localization from relative measurements, such as distances, bearings, and angles. In this context, I have studied how network topology and sensing geometry shape rigidity properties in multi-robot networks, which provide a structural foundation for analyzing when such systems can be reliably localized.

In particular, I have contributed to the quantitative characterization of rigidity through spectral metrics, establishing rigorous bounds that relate these quantities to fundamental graph invariants such as diameter and vertex connectivity.
These results clarify how observability degrades as networks grow in size or become increasingly sparse, and provide theoretical limits on achievable estimation performance and robustness.

Building on this foundation, I investigated how rigidity, which is a global property, can be assessed by analyzing the rigidity of local subgraphs.
This perspective is particularly well suited to large-scale systems, where global attributes become impractical to compute or enforce. 
For instance, graph rigidity is not a robust indicator of observability: the removal of a single edge may eliminate it, even though rigid local subgraphs typically persist.
These results provide a theoretical foundation for the design of scalable control strategies where the interaction topology is explicitly embedded in the system model.
