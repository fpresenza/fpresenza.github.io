---
layout: page
permalink: /research/
title: Research
description: Research interests and current directions.
nav: true
nav_order: 2
---

My research centers on estimation and control strategies for **multi-robot systems**.
The goal is to enable teams of robots to operate in unstructured environments **using only local perception and inter-agent communication**.
This direction is motivated by the need to reduce dependence on installed infrastructure, such as centralized computers, global positioning systems, or fixed communication facilities, thereby improving **autonomy**, **resilience**, and **scalability**.

My current work addresses the following closely related research directions:
+ Designing distributed pose estimators based on inter-agent measurements provided by onboard sensors such as cameras.
+ Developing rigidity theory that helps compare these estimators and understand their observability properties.
+ Designing perception-aware control strategies that maintain sufficient observability while robots execute a mission.
+ Model the integrated localization-and-cotrol strategies using tailored event-based multi-agent simulators.
  
<!--
The goal is to enable teams of robots to operate in unstructured environments using only local perception and inter-agent communication. This direction is motivated by the need to **reduce dependence on installed infrastructure**, such as centralized computers, global positioning systems, or fixed communication facilities, thereby improving autonomy, resilience, and scalability. To achieve this, I combine tools from _graph theory_, _nonlinear control_, _event-driven dynamical systems_, and _multi-agent learning_.

### Rigidity Theory
A fundamental way to achieve coordination on multi-robot systems is by performing distributed localization from inter-robot measurements, such as distances, bearings, and angles.
Rigidity theory provides a structural foundation for analyzing when such systems can be reliably localized.
In this context, I study how rigidity relates with fundamental graph invariants such as diameter and vertex connectivity.
For example, my work have helped clarify how observability degrades as networks grow in size or become increasingly sparse which provide theoretical limits on achievable estimation performance and robustness.

### Decentralized Subgraph-based Control
Building on this foundation, I am very interested in studying how rigidity can be estimated by analyzing local properties.
This perspective is particularly important for large-scale systems, where rigidity become impractical to compute or enforce: the removal of a single edge may eliminate it, even though rigid local subgraphs typically persist.
This perspective gives rise to the design of scalable rigidity maintenance control laws for multi-robot systems.
By properly identifying local subgraphs, I designed decentralized control laws that preserve rigidity using only locally available information.

### Event-based Simulation for Network Multi-Agent Systems
As a third major line of work, I have worked on the design and implementation of event-based simulation frameworks for multi-agent systems.
This line of work leverages the Emergent Behavior Discrete Event System Specification (EB-DEVS), enabling the representation of both direct and indirect interactions between agents via event messages and through macroscopic-microscopic state sharing, respectively.
This simulation approach allows for the systematic evaluation of collective behavior under asynchronous events, multi-hop interactions, and time-varying interaction topologies.
-->

