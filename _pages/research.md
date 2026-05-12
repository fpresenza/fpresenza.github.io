---
layout: page
permalink: /research/
title: Research
description: Research interests and current directions.
nav: true
nav_order: 2
---

The central object of my research is the modeling, design, and analysis of **estimation and control methods for multi-robot systems**.
The goal is to allow robot teams to achieve coordination in unstructured environments using only local perception and inter-agent communication.
This interest is driven by the need to **eliminate dependence on installed infrastructure** such as central computers, global positioning systems, or communication facilities, which strongly compromise autonomy, resilience, and scalability.
To do this I combine tools from _graph theory_, _nonlinear control_, _event-driven networked systems_, and _multi-agent learning_.

## Rigidity Theory
One of the main research directions focuses on multi-robot systems performing distributed localization from relative measurements, such as distances, bearings, and angles.
I have studied how network topology and sensing geometry shape rigidity, which provide a structural foundation for analyzing when such systems can be reliably localized. In particular, I have contributed to the quantitative characterization of rigidity through spectral metrics, establishing rigorous bounds that relate these quantities to fundamental graph invariants such as diameter and vertex connectivity.
These results clarify how observability degrades as networks grow in size or become increasingly sparse, and provide theoretical limits on achievable estimation performance and robustness.

Building on this foundation, I investigated how rigidity can be assessed by analyzing the rigidity of local subgraphs.
This perspective is particularly well suited to large-scale systems, where rigidity become impractical to compute or enforce. 
For instance, graph rigidity is not a robust indicator of observability: the removal of a single edge may eliminate it, even though rigid local subgraphs typically persist.

# Decentralized Rigidity Maintenance Control
Expanding upon this work, a second major research direction concerns the design of control laws for multi-robot systems without central control, especially targeted at large-scale systems.
By properly identifying local subgraphs, I designed feedback laws that preserve rigidity using only locally available measurements. Under this scheme, the robotic sustem is free to undergo arbitrary changes, both in structure and shape, as long as local rigidity is preserved.
These formulations are grounded in optimization-based control, allowing the systematic incorporation of sensing constraints and collision avoidance mechanisms. 

# Event-based Simulation for Network Multi-Agent Systems
As a third major line of work, I have worked on the design and implementation of event-based simulation frameworks for multi-agent systems.
This line of work leverages the Emergent Behavior Discrete Event System Specification (EB-DEVS), enabling the representation of both direct and indirect interactions between agents via event messages and through macroscopic-microscopic state sharing, respectively.
This simulation approach allows for the systematic evaluation of collective behavior under asynchronous events, multi-hop interactions, and time-varying interaction topologies. 
By enabling computational experiments in complex settings, this approach provides a principled bridge between theoretical analysis and large-scale system behavior.


