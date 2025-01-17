---
title: "Closed-Loop Predict-Then-Optimize"
layout: single
permalink: /research/Project_02_CPO/
tags: [Predict Then Optimize, Unit Commitment, Prescriptive Analytics, Value-Oriented Prediction, Bi-Level Mixed-Integer Programming]
---

This is the first project in my Ph.D. career. It aims to sell an idea called *closed-loop predict-then-optimize (CPO).* Traditionally, power system operations follow an *open-loop predict-then-optimize (OPO)* process:
![Open-Loop Process](/assets/images/Project_02_Fig02_OPO.gif)

1. **Predict** uncertainties, such as wind power availability, as accurately as possible.
2. **Optimize** the operation plan (e.g., unit commitment) based on the predictions.

The ultimate objective is to minimize overall operating costs.

However, due to the nonlinearity and complexity of power systems, the relationship between prediction accuracy and operating cost is **non-monotonic** and **asymmetric**:
![Accuracy–Cost Relationship](/assets/images/Project_02_Fig03_Trend.jpeg)

As a result, the OPO approach can be **myopic** as it focuses solely on immediate prediction accuracy without considering the impact of predictions on operations. To address this, the CPO idea suggests:
![Closed-Loop Process](/assets/images/Project_02_Fig04_Title.gif)

1. Feed the operational cost induced by the prediction back to the prediction phase.
2. Evaluate prediction quality based on the induced operational cost instead of statistical accuracy.



## Related Papers

[1] Xianbang Chen, Yafei Yang, Yikui Liu, Lei Wu. "Feature-driven economic improvement for network-constrained unit commitment: A closed-loop predict-and-optimize framework," *IEEE Transactions on Power Systems*, 2021. [PDF »](/assets/papers/Project_02_Paper_01.pdf)

[2] Xianbang Chen, Yikui Liu, Lei Wu. "Towards improving unit commitment economics: An add-on tailor for renewable energy and reserve predictions," *IEEE Transactions on Sustainable Energy*, 2024. [PDF »](/assets/papers/Project_02_Paper_02.pdf)
