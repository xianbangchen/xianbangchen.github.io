---
title: "Enhancing Economics and Resilience of Greenhouse via Closed-Loop Performance-Driven Learning-Based Control"
layout: single
permalink: /research/Project_05_CEA_Cornell/ 
tags: [Greenhouse, Model Predictive Control, Deep Reinforcement Learning, Microgrid]
---
<p align="center">
  <video autoplay loop muted playsinline width="100%">
    <source src="/assets/images/Project_05_Fig01_Title.webm" type="video/webm">
    Your browser does not support WebM.
  </video>
  <figcaption style="font-style: italic;">Illustration of a greenhouse facility.</figcaption>
</p>

This is an ongoing [project](https://www.ceaforum.org/) supported by the [USDA NIFA Specialty Crop Research Initiative](https://www.nifa.usda.gov/).

We study how to coordinate greenhouse climate control to reduce energy use while maintaining suitable growing conditions. The tomato greenhouse considered in this work includes heating and cooling, ventilation, humidity control, CO<sub>2</sub> enrichment, supplemental lighting, and shading systems. These devices jointly influence indoor temperature, humidity, CO<sub>2</sub> concentration, and daily light integral (DLI), making their coordinated operation essential as outdoor conditions change.

<figure style="text-align: center;">
  <img src="/assets/images/Project_05_Fig02_GH.gif" alt="Tomato greenhouse structure showing heating, cooling, ventilation, humidity control, CO2 enrichment, LED lighting, and screens." width="100%" loading="lazy">
  <figcaption style="font-style: italic;">The studied greenhouse and its climate-control equipment.</figcaption>
</figure>

Our recent work develops an online decision-focused learning framework to augment model predictive control (MPC). At each control step, MPC uses a climate model, the current greenhouse state, and forecasts of outdoor conditions to select control actions. The first action is applied to the greenhouse simulator, and the resulting state provides the starting point for the next step.

<figure style="text-align: center;">
  <img src="/assets/images/Project_05_Fig03_FlowChart.gif" alt="Decision-focused learning workflow linking system identification, MPC optimization, greenhouse simulation, and control-performance feedback for model adaptation." width="100%" loading="lazy">
  <figcaption style="font-style: italic;">The closed-loop framework: model, optimize, apply, and adapt using control-performance feedback.</figcaption>
</figure>

The key idea is to feed control performance back into model learning, so that online model updates directly support better control decisions. Simulations demonstrate energy savings relative to a nominal baseline MPC, with a tunable trade-off in climate-regulation performance. This work connects greenhouse modeling and operation through a shared objective: balancing energy use and climate regulation.

<strong>Related Papers</strong>
<ul style="font-size: 75%; list-style: none; margin: 0; padding: 0;">
  <li style="padding-left: 1.9em; text-indent: -2.1em;">
    <span style="font-family: monospace;">[1]</span> Xianbang Chen, Fengqi You. "Decision-focused learning-augmented MPC for climate control in controlled-environment agriculture greenhouses," <em>Computers and Electronics in Agriculture</em>, 2026.
    <a href="https://www.sciencedirect.com/science/article/abs/pii/S016816992601094X">[Article »]</a>
  </li>
</ul>
