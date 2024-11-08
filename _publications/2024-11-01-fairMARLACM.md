---
title: "Cooperation and Fairness in Multi-Agent Reinforcement Learning"
collection: publications
permalink: /publication/fairMARLACM
date: 2024-11-01
venue: "ACM Journal on Autonomous Transportation Systems"
---

Authors: Jasmine Jerry Aloor, **Siddharth Nayak**, Sydney Dolan, Hamsa Balakrishnan

Multi-agent systems are trained to maximize shared cost objectives, which typically reflect system-level efficiency. However, in the resource-constrained environments of mobility and transportation systems, efficiency may be achieved at the expense of fairness — certain agents may incur significantly greater costs or lower rewards compared to others. Tasks could be distributed inequitably, leading to some agents receiving an unfair advantage while others incur disproportionately high costs. It is, therefore, important to consider the tradeoffs between efficiency and fairness in such settings. We consider the problem of fair multi-agent navigation for a group of decentralized agents using multi-agent reinforcement learning (MARL). We consider the reciprocal of the coefficient of variation of the distances traveled by different agents as a measure of fairness and investigate whether agents can learn to be fair without significantly sacrificing efficiency (i.e., increasing the total distance traveled). We find that by training agents using min-max fair distance goal assignments along with a reward term that incentivizes fairness as they move towards their goals, the agents (1) learn a fair assignment of goals and (2) achieve almost perfect goal coverage in navigation scenarios using only local observations. For goal coverage scenarios, we find that, on average, the proposed model yields a 14% improvement in efficiency and a 5% improvement in fairness over a baseline model that is trained using random assignments. Furthermore, a 21% improvement in fairness can be achieved by the proposed model as compared to a model trained on optimally efficient assignments; this increase in fairness comes at the expense of only a 7% decrease in efficiency. Finally, we extend our method to environments in which agents must complete coverage tasks in prescribed formations and show that it is possible to do so without tailoring the models to specific formation shapes. [[PDF]](https://arxiv.org/abs/2410.14916), [[Website]](https://jaroan.github.io/jasminejerrya/Fair_MARL)

<!-- Recommended citation: Your Namesdas, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->
