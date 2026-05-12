---
layout: page
permalink: /research/
title: Research
description: Research interests and current directions.
nav: true
nav_order: 2
---

My research centers around **localizability-and-interaction aware coordination for multi-robot systems**.
The goal is to allow a team of robot of any size to achieve coordination in unstructured environments using only local perception and inter-agent communication.
This interest is driven by the need to **eliminate dependence on installed infrastructure** such as central computers, global positioning systems, or communication facilities, in order to ensure autonomy, resilience, and scalability.
To achive these goals I combine tools from _graph theory_, _nonlinear control_, _event-driven dynamical systems_, and _multi-agent learning_.

### Rigidity Theory
One important way to achieve coordination on multi-robot systems is by performing distributed localization from inter-robot measurements, such as distances, bearings, and angles.
Rigidity theory provides a structural foundation for analyzing when such systems can be reliably localized.
In this context, I study quantitative characterizations of rigidity through spectral metrics, to better understand how rigidity relates with fundamental graph invariants such as diameter and vertex connectivity.
For example, my work have helped clarify how observability degrades as networks grow in size or become increasingly sparse, and provide theoretical limits on achievable estimation performance and robustness.

### Decentralized Subgraph-based Control
Building on this foundation, I am very interested in studying how rigidity can be estimated by analyzing local properties.
This perspective is particularly important for large-scale systems, where rigidity become impractical to compute or enforce: the removal of a single edge may eliminate it, even though rigid local subgraphs typically persist.

This gives rise to the design of scalable rigidity maintenance control laws for multi-robot system.
By properly identifying local subgraphs, I designed feedback laws that preserve rigidity using only locally available information.
These formulations are grounded in optimization-based control, allowing the systematic incorporation of sensing constraints and collision avoidance mechanisms. 

### Event-based Simulation for Network Multi-Agent Systems
As a third major line of work, I have worked on the design and implementation of event-based simulation frameworks for multi-agent systems.
This line of work leverages the Emergent Behavior Discrete Event System Specification (EB-DEVS), enabling the representation of both direct and indirect interactions between agents via event messages and through macroscopic-microscopic state sharing, respectively.
This simulation approach allows for the systematic evaluation of collective behavior under asynchronous events, multi-hop interactions, and time-varying interaction topologies. 
By enabling computational experiments in complex settings, this approach provides a principled bridge between theoretical analysis and large-scale system behavior.


