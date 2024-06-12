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
