---
title: "Closed-Loop Predict-Then-Optimize"
layout: single
permalink: /research/Project_02_CPO/
tags: [Predict Then Optimize, Unit Commitment, Prescriptive Analytics, Value-Oriented Prediction, Bi-Level Mixed-Integer Programming]
---

This is the first project of my Ph.D. career. It aims to sell a *closed-loop predict-then-optimize (CPO)* idea.

To achieve the lowest operating cost, power system operations generally use an *open-loop predict-then-optimize (OPO)* process:
1. **Predict** uncertainties, e.g., wind power, as accurately as possible.
2. **Optimize** the operation plan, e.g., unit commitment, using the predictions.


<p align="center">
  <img src="/assets/images/Project_02_Fig02_OPO.gif" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;"> Open-loop predict-then-optimize.</figcaption>
</p>
<p align="center">
  <img src="/assets/images/Project_02_Fig04_CPO.gif" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;"> Closed-loop predict-then-optimize.</figcaption>
</p>

The OPO process does make sense. Yet, due to the nonlinearity and complexity of power systems, the relationship between prediction accuracy and operating cost is **non-monotonic** and **asymmetric**. *This implies that a more accurate prediction may NOT lead to a lower-cost operating plan.*
<p align="center">
  <img src="/assets/images/Project_02_Fig03_Trend.jpg" alt="Alt text" width="80%">
      <figcaption style="font-style: italic;">Testing results on the IEEE 118-bus system. Each dot represents a specific testing sample with a prediction error and the corresponding increase in operating cost, while the red line indicates the overall trend. As observed, Point A has a smaller mean absolute percentage error (MAPE), but it leads to a higher operating cost compared to Point B.</figcaption>
</p>

To this end, we are selling you the CPO idea, which features that:
1. It feeds the operating cost back to the prediction phase.
2. The predictor training evaluates prediction quality via operating costs rather than statistical accuracy criterion (e.g., MAPE).

## Related Papers

[1] Xianbang Chen, Yafei Yang, Yikui Liu, Lei Wu. "Feature-driven economic improvement for network-constrained unit commitment: A closed-loop predict-and-optimize framework," *IEEE Transactions on Power Systems*, 2021. [PDF »](/assets/papers/Project_02_Paper_01.pdf)[Code »](https://github.com/asxadf/Closed_Loop_NCUC_Dataset)

[2] Xianbang Chen, Yikui Liu, Lei Wu. "Towards improving unit commitment economics: An add-on tailor for renewable energy and reserve predictions," *IEEE Transactions on Sustainable Energy*, 2024. [PDF »](/assets/papers/Project_02_Paper_02.pdf)
