---
title: "Cascaded Hydropower Operations"
layout: single
permalink: /research/Project_03_DOE_PGE/ 
tags: [Cascaded Hydropower, Reinforcement Learning, Multi-Parametric Programming]
---
This project is supported by the [U.S. Department of Energy (DOE)](https://www.energy.gov/nepa/articles/cx-101766-exploring-multidimensional-spatial-temporal-hydropower-operational).

We collaborate with the University of Arizona team (led by [Prof. Neng Fan](https://sie.engineering.arizona.edu/faculty-staff/faculty/neng-fan) and [Dr. Zhong](https://zhimingzhong1.github.io/zhongz.github.io/)) and [Portland General Electric (PGE)](https://portlandgeneral.com/about) to assist cascaded hydropower fleets in achieving greater operational efficiency in modern power systems.

The project uses [PGE's Pelton Round Butte system](https://lowimpacthydro.org/lihi-certificate-25-pelton-round-butte-project-oregon/) as the real-world case.
<p align="center">
  <img src="/assets/images/Project_03_Fig02_CHP.jpg" alt="Alt text" width="100%">
        <figcaption style="font-style: italic;">Illustration of the Pelton Round Butte Project.</figcaption>

</p>

A key deliverable of this project is an analytical future value function that quantifies the hydropower generation (MWh) that water storage (Mm³) can provide in the future, known as *future value*. This function is user-friendly and interpretable. Given this function, hydropower operators can view the future value surface and access specific results with a simple click.
<p align="center">
  <img src="/assets/images/Project_03_Fig03_3D.gif" alt="Alt text" width="100%">
        <figcaption style="font-style: italic;">Illustration of the visualized future value function.</figcaption>

</p>

PGE 

Another key deliverable of this project is a medium-term planning method tailored for renewable-integrated cascaded hydropower systems.

<p align="center">
  <img src="/assets/images/Project_03_Fig04_VCHP.jpg" alt="Alt text" width="100%">
        <figcaption style="font-style: italic;"> Illustration of the Pelton Round Butte Project integrated with variable renewables.</figcaption>

</p>

The medium-term planning method uses deep reinforcement learning (DRL), offering two key advantages:  
1. It uses short-term contextual inputs, such as day-ahead electricity prices and renewable forecasts, as inputs to determine medium-term planning strategy.  
2. The strategy's quality is measured by its ability to improve profits in short-term operations.

As you can see, this medium-term planning method involves the [closed-loop predict-then-optimize idea.](https://xianbangchen.github.io/research/Project_02_CPO/)

<p align="center">
  <img src="/assets/images/Project_03_Fig05_OPO.jpg" alt="Alt text" width="100%">
        <figcaption style="font-style: italic;">The existing open-loop relationship between mid-term planning and short-term operations.</figcaption>
</p>
<p align="center">
  <img src="/assets/images/Project_03_Fig06_CPO.jpg" alt="Alt text" width="100%">
        <figcaption style="font-style: italic;">The presented closed-loop relationship between mid-term planning and short-term operations.</figcaption>
</p>


**Related Papers**
<ul style="font-size: 75%; list-style: none; margin: 0; padding: 0;">
  <li style="padding-left: 2em; text-indent: -1.5em;">
    [1] Xianbang Chen, Yikui Liu, Zhiming Zhong, Neng Fan, Zhechong Zhao, Lei Wu. "A carryover storage valuation framework for medium-term cascaded hydropower planning: A Portland General Electric system study," <em>arxiv</em>, 2025.
    <a href="/assets/papers/Project_03_Paper_01.pdf">[PDF »]</a>
  </li>

  <li style="padding-left: 2em; text-indent: -1.5em;">
    [2] Xianbang Chen, Yikui Liu, Neng Fan, Lei Wu. "DRL-based medium-term planning of renewable-integrated self-scheduling cascaded hydropower to guide wholesale market participation," <em>arxiv</em>, 2025.
    <a href="/assets/papers/Project_03_Paper_02.pdf">[PDF »]</a>
  </li>  
  
    <li style="padding-left: 2em; text-indent: -1.5em;">
    [3] Yikui Liu, Xianbang Chen, Neng Fan, Zhechong Zhao, Lei Wu. "Stochastic day-ahead operation of cascaded hydropower systems with Bayesian neural network-based scenario generation: A Portland General Electric system study," <em>International Journal of Electrical Power & Energy Systems</em>, 2023.
  </li>  
  
    <li style="padding-left: 2em; text-indent: -1.5em;">
    [4] Zhiming Zhong, Neng Fan, Lei Wu. "Multistage stochastic optimization for mid-term integrated generation and maintenance scheduling of cascaded hydroelectric system with renewable energy uncertainty," <em>European Journal of Operational Research</em>, 2024.
  </li>  
  
    <li style="padding-left: 2em; text-indent: -1.5em;">
    [5] Zhiming Zhong, Neng Fan, Lei Wu. "Multistage robust optimization for the day-ahead scheduling of hybrid thermal-hydro-wind-solar systems," <em>Journal of Global Optimization</em>, 2024.
  </li>
  
    <li style="padding-left: 2em; text-indent: -1.5em;">
    [6] Zhiming Zhong, Neng Fan, Lei Wu. "A hybrid robust-stochastic optimization approach for day-ahead scheduling of cascaded hydroelectric system in restructured electricity market," <em>European Journal of Operational Research</em>, 2023.
  </li>
</ul>
