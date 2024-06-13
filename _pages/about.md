---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<head>
<style>
p {
  text-align: justify;
}
div.title {
  text-align: left;
  font-weight: bold;
}
div.description {
  text-align: left;
  opacity: 0.8;
}
@counter-style repeating-emoji {
  system: cyclic;
  symbols: "\1F431" "\1F436" "\1F984"; // unicode code point
  suffix: " ";
}
.repeating-counter-rule {
  list-style-type: repeating-emoji;
}
</style>
</head>

# Welcome!

<p>Proactive Robotics researcher and engineer specialized in autonomous unmanned aerial vehicles with 10+ years of experience delivering multiple industrial solutions, including long-range GPS denied navigation for unmanned aerial systems as well as heterogeneous swarms of aerial robots for maximum area coverage. Driven by an ongoing quest for knowledge and a dedication to solving complex challenges with exceptional proficiency across both hardware and software domains.</p>

## Research

### Visual Tracking
<img src="/images/visual_tracking.gif" alt="Demonstrating our system's ability to detect, track, and navigate toward a running moving target in challenging outdoor environments." style="width:100%">
<p>Visual control allows quadrotors to navigate using real-time sensory data, but challenges like generalization, reliability, and real-time response remain. Our research addresses these issues with a new perception framework using foundation models for universal object detection and tracking. This framework, combined with a multi-layered tracker, ensures continuous target visibility despite motion blur, light changes, and occlusions. We also introduce a model-free visual controller for resilient tracking. Our system works efficiently with limited hardware, using only an onboard camera and an inertial measurement unit.</p>

### Perpetual Autonomy
<img src="/images/perpetual_autonomy.gif" alt="AutoCharge, an autonomous charging system for quadrotors that is capable of universal, highly efficient, and robust charging." style="width:100%">
<p>Battery endurance is a major challenge for long-term autonomy and long-range aerial robot operations. Our solution, AutoCharge, addresses this with an autonomous charging system for quadrotors. AutoCharge combines a portable ground station with a lightweight, flexible charging tether for universal, efficient, and robust charging. We designed circular magnetic connectors for precise, orientation-agnostic connections between the ground station and tether. An electromagnet on the ground station increases tolerance to localization and control errors during docking, ensuring smooth undocking after charging.</p>

### Consensus with unsorted measurements
<img src="/images/jpdaf.gif" alt="Demonstrating the performance  of our Joint Probabilistic Data Association Filter (JPDAF) for consensus with unsorted measurements." style="width:100%">
<p>Consensus algorithms are essential for multi-robot systems, but they often require sorting measurements or rely on a central processor. Our research introduces a new consensus algorithm that works with unsorted measurements, allowing robots to share information without central processing. This algorithm, based on the Joint Probabilistic Data Association Filter (JPDAF), enables robots to reach a consensus on shared information, even when measurements are unsorted or incomplete. We demonstrate this algorithm with a swarm of quadrotors, showing that it can achieve consensus on the position of a moving target using only onboard sensors.</p>

### Control barrier functions to maintain graph topology
<img src="/images/cbf.gif" alt="Demonstrating the use of control barrier functions to maintain connectivity in a swarm of quadrotors." style="width:100%">
<p> To achieve common objectives and tasks, multi robot agents need to coordinate their motion and communication capabilities properly. Inter-connections among the robots are often modeled as a graph, whose topology can become time-varying when robots are allowed to move within the environment.  In this work, we address the problem of keeping the graph topology constant while considering robots’ limited sensing capabilities and lack of communication. Specifically, we propose a Control Barrier Function-based optimization controller that enforces topology maintenance within the team while considering limitations in the field of view of each robot</p>

### Multi-robot area coverage
<img src="/images/multi_tracking.gif" alt="Demonstrating our system's ability to coordinate multiple robots for maximum area coverage." style="width:100%">
<p>Here we address the relative detection and tracking problems of deploying multiple aerial vehicles in a distributed manner with no centralized coordinate provided by GNSS or a motion capture system. As the output of the drone detection provides unsorted measurements from each  observing drone’s perspective, the tracking also address the the corresponding perception consensus problem (i.e., uniqueness and identical IDs across all observing agents). With a deep consideration for swarms applications that use micro aerial vehicles constraint by Size, Weight, and Power (SWaP), we carefully designed a lightweight perception pipeline that rely only on a single camera and Inertial Measurement Unit. As resolving the association problem between the incoming unsorted measurements and existing agents is a computation bottleneck for multi-tracking algorithms, we propose several Bayesian filtering strategies and provide a comparative evalualution on their computation complexity.

### Sensor Fusion
<p>The aerial systems ability to effectively operate in a various application domains has been increasing steadily over the years. This was mainly due to the increased availability of sensory and computing hardware, coupled with their improved reliability, cost and performance. Their ability to perform high-level autonomous operations, however, requires a reliable and stable long-term state estimation and localization, especially during complex missions that require transitioning between outdoor and GPS-denied environments. In this paper the performance of various localization strategies employed during UAV missions with indoor/outdoor transitioning is evaluated using a dataset collected during a representative field test that includes outdoor-indoor traversals.</p>

### Autonomous UAV for reconnissance
<p>This work was done for the development of an autonomous UAV for the International Aerial Robotics Competition's mission 6. The UAV was designed to locate an opening in a building, enter when a surveillance camera was not looking, navigate crowded hallways, avoid or disable security systems, interpret signage in Arabic, and finally reach a particular room without bumping any walls or landing. From there, the robot had to locate a particular paper inbox containing a flash drive. It had to then retrieve that flash drive, replace it with an identical blank flash drive, and exit the building within a short time span.<p>
