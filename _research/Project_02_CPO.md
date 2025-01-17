---
title: "Closed-Loop Predict-Then-Optimize"
layout: single
permalink: /research/Project_02_CPO/
tags: [Predict Then Optimize, Unit Commitment, Prescriptive Analytics, Value-Oriented Prediction, Bi-Level Mixed-Integer Programming]
---

This is the first project in my Ph.D. career. It is to sell a *closed-loop predict-then-optimize (CPO)* idea. Power system operations generally follow an *open-loop predict-then-optimize (OPO)* process:
1. **Predict** uncertainties, e.g., wind power, as accurately as possible.
2. **Optimize** the operation plan, e.g., unit commitment, using the predictions.

The ultimate objective is to minimize the operating cost.

<p align="center">
  <img src="/assets/images/Project_02_Fig02_OPO.gif" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;"> Open-loop predict-then-optimize.</figcaption>
<p align="center">
  <img src="/assets/images/Project_02_Fig04_CPO.gif" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;"> Closed-loop predict-then-optimize.</figcaption>
</p>

The OPO process does make sense. However, due to the nonlinearity and complexity of power systems, the relationship between prediction accuracy and operating cost is **non-monotonic** and **asymmetric**. *This implies that a more accurate prediction may not lead to a lower-cost operating plan.*
<p align="center">
  <img src="/assets/images/Project_02_Fig03_Trend.jpg" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;">Testing results on the IEEE 118-bus system. The dots represent specific testing samples with a specific prediction error, and the red line represents the trend line. As can be seen, Point A has a smaller mean absolute percentage error (MAPE), but it leads to a higher operating cost compared to Point B.</figcaption>
</p>

To this end, we introduce the CPO idea, which emphasizes that:
1. Feed the operating cost back to the prediction phase.
2. Evaluate prediction quality via the operating cost instead of statistical accuracy.

## Related Papers

[1] Xianbang Chen, Yafei Yang, Yikui Liu, Lei Wu. "Feature-driven economic improvement for network-constrained unit commitment: A closed-loop predict-and-optimize framework," *IEEE Transactions on Power Systems*, 2021. [PDF »](/assets/papers/Project_02_Paper_01.pdf)

[2] Xianbang Chen, Yikui Liu, Lei Wu. "Towards improving unit commitment economics: An add-on tailor for renewable energy and reserve predictions," *IEEE Transactions on Sustainable Energy*, 2024. [PDF »](/assets/papers/Project_02_Paper_02.pdf)
