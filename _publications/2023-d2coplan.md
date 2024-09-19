---
title: "NAVINACT: Combining Navigation and Imitation Learning for Bootstrapping Reinforcement Learning"
collection: publications
permalink: https://arxiv.org/pdf/2408.04054
excerpt: '<b>Amisha Bhaskar</b>, Zahiruddin Mahammad, Sachin R Jadhav, Pratap Tokekar (2024). &quot;NAVINACT: Combining Navigation and Imitation Learning for Bootstrapping Reinforcement Learning.&quot; <br /><i>Under Review</i>'
# date: 2009-10-01
# :venue: ''
paperurl: 'https://arxiv.org/pdf/2408.04054'
# citation: 'Vishnu Sharma, Lifeng Zhou, Pratap Tokekar. (2023). &quot;NAVINACT: Combining Navigation and Imitation Learning for Bootstrapping Reinforcement Learning.&quot; <i>Under Review</i>.'
---

[Webpage](https://raaslab.org/projects/NAVINACT/) <br/>
**Abstract:**
Reinforcement Learning (RL) has shown remarkable progress in simulation environments, yet its application to real-world robotic tasks remains limited due to challenges in exploration and generalization. To address these issues, we introduce NAVINACT, a framework that chooses when the robot should use classical motion planning based navigation and when it should learn a policy. To further improve the efficiency in exploration, we use imitation data to bootstrap the exploration. NAVINACT dynamically switches between two modes of operation: navigating to a waypoint using classical techniques when away from the objects and reinforcement learning for fine-grained manipulation control when about to interact with objects. NAVINACT consists of a multi-head architecture composed of ModeNet for mode classification, NavNet for waypoint prediction, and InteractNet for precise manipulation. By combining the strengths of RL and Imitation Learning (IL), NAVINACT improves sample efficiency and mitigates distribution shift, ensuring robust task execution. We evaluate our approach across multiple challenging simulation environments and real-world tasks, demonstrating superior performance in terms of adaptability, efficiency, and generalization compared to existing methods.In both simulated and real-world settings, NAVINACT demonstrates robust performance. In simulations, NAVINACT surpasses baseline methods by 10-15% in training success rates at 30k samples and by 30-40% during evaluation phases. In real-world scenarios, it demonstrates a 30-40% higher success rate on simpler tasks compared to baselines and uniquely succeeds in complex, two-stage manipulation tasks.


<b>Amisha Bhaskar</b>, Zahiruddin Mahammad, Sachin R Jadhav, Pratap Tokekar (2023). &quot;NAVINACT: Combining Navigation and Imitation Learning for Bootstrapping Reinforcement Learning.&quot; <br /><i>Under Review</i><br /> 

