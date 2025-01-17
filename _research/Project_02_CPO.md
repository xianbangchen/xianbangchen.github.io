---
title: "Closed-Loop Predict-Then-Optimize"
layout: single
permalink: /research/Project_02_CPO/
tags: [Predict Then Optimize, Unit Commitment, Prescriptive Analytics, Value-Oriented Prediction, Bi-Level Mixed-Integer Programming]
---

This project marks the **first** of my Ph.D. career, introducing an idea called *closed-loop predict-then-optimize (CPO).* Traditionally, power system operations follow an **open-loop predict-then-optimize (OPO)** process:
1. **Predict** uncertainties such as wind power availability as accurately as possible.
2. **Optimize** the operation plan (e.g., unit commitment) based on these predictions.

The ultimate objective is to minimize overall operating costs.

![Open-Loop Process](/assets/images/Project_02_Fig02_OPO.gif)

However, due to the **nonlinearity** and **complexity** of power systems, the relationship between prediction accuracy and operating cost is **non-monotonic** and **asymmetric**:

![Accuracy–Cost Relationship](/assets/images/Project_02_Fig03_Trend.gif)

As a result, focusing solely on immediate prediction accuracy in the OPO approach can be **myopic**—the operational decisions may not fully account for the downstream impacts of prediction errors. To address this, **closed-loop predict-then-optimize (CPO)** **feeds back** the operational performance to the prediction phase, so that the quality of predictions is evaluated by their **actual impact** on operational economics.

![Closed-Loop Process](/assets/images/Project_02_Fig04_Title.gif)


## Related Papers

[1] Xianbang Chen, Yafei Yang, Yikui Liu, Lei Wu. "Feature-driven economic improvement for network-constrained unit commitment: A closed-loop predict-and-optimize framework," *IEEE Transactions on Power Systems*, 2021. [PDF »](/assets/papers/Project_02_Paper_01.pdf)

[2] Xianbang Chen, Yikui Liu, Lei Wu. "Towards improving unit commitment economics: An add-on tailor for renewable energy and reserve predictions," *IEEE Transactions on Sustainable Energy*, 2024. [PDF »](/assets/papers/Project_02_Paper_02.pdf)
