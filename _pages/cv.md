---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- PhD, Aeronautics and Astronautics, MIT, (Expected 2025)
- SM, Aeronautics and Astronautics, MIT, 2022
- B.Tech, Electrical Engineering, IIT Madras, 2020

# Theses

- Learning-based Scheduling
  - S.M. Thesis, Massachusetts Institute of Technology, 2022
  - Advisor: Prof. Hamsa Balakrishnan
- Reinforcement Learning for Improving Object Detection
  - Undergraduate Thesis, Indian Institute of Technology Madras, 2020
  - Advisor: Prof. Balaraman Ravindran

# Work experience

- DINaMo Lab, MIT, Graduate Research Assistant - Fall 2020-Present

  - Advisor: [Prof. Hamsa Balakrishnan](https://www.mit.edu/~hamsa/index.html)
    - Developed and deployed a language model-based architecture for multi-agent embodied robotic tasks resulting in 30% improvement in task completion.
    - Designed a graph neural network-based architecture for scaling multi-agent reinforcement learning algorithms in limited-information scenarios resulting in 1.9× improvement in success rates.
    - Exploring LLMs for creating interpretable communication protocols for multi-agent reinforcement learning.
    - Developed a hybrid solution combining reinforcement learning (RL) and integer programming to optimize crew schedules, achieving 33% - 48% fewer disruptions compared to the baseline formulation.

- MERL, Cambridge, MA, Research Scientist Intern, Summer 2024

  - Advisor: [Dr. Anoop Cherian](https://users.cecs.anu.edu.au/~cherian/)
    - Developed a multimodal language model for aligning visual, aural, and language modalities for autonomous navigation in embodied robotic environments leading to 21% improvement in prediction accuracy of navigation actions.
    - Implemented a data-distributed parallel RL model to train a conversational embodied robotic agent to include inputs from the trained multimodal language model.

- MERL, Cambridge, MA, Research Scientist Intern, Summer 2023

  - Advisor: [Dr. Abraham Vinod](https://abyvinod.github.io/)
    - Developed a data-driven bi-level approach incorporating multi-armed bandits and integer programming to enhance multi-agent environmental monitoring strategies
    - Devised a real-time implementable graph-based heuristic planner, significantly improving solution speed
    - Obtained anytime guarantees and upper bounds on computing time as well as task completion time

- TCS Research and Innovation Lab, Mumbai, India, Research Intern, Summer 2019

  - Advisor: [Dr. Harshad Khadilkar](https://sites.google.com/view/harshad/home)
    - Co-developed a heuristic + reinforcement learning-based method for the online version of 3D-bin packing problem to improve the packing efficiency by 3% over heuristic-based methods along with speeding up prediction by a factor of 6.
    - Experimented with a behavioural cloning + heuristics model to achieve 85% average packing efficiency

- RISE Lab, IIT Madras, UnderFall 2018-2019: Undergraduate Research Assistant

  - Advisor: [Prof. Balaraman Ravindran](https://www.cse.iitm.ac.in/~ravi/)
    - Utilized RL to enhance digital transformations on images, optimizing object detection performance in a pre-trained network.
    - Applied graph neural networks for molecule property prediction, achieving a notable ROC-AUC of $0.807$ on the Pseudomonas dataset. Ranked 13th globally in the MIT AI Cures Challenge. [Leaderboard](https://www.aicures.mit.edu/tasks)

- Daimler AG R&D, Sindelfingen, Germany, Research Intern, Summer 2018
  - Advisor: [Dr. Hannes Gorniaczyk](https://de.linkedin.com/in/gorniaczyk)
    - Analyzed the impact of on-board vehicle camera parameters, including _Shutter Speed_ and _Voltage Gains_, on the performance of pre-trained object detection neural networks.
    - Developed a performance matrix to identify the optimal combination of shutter speed and voltage gain, maximizing the F1-score for a pre-trained object detection network.

# Skills

- Multi-Agent Reinforcement Learning
- Graph Learning
- Foundational Models
- Distributed Parallel Computing
- Slurm
- Python
  - PyTorch
  - TensorFlow
- C, C++
- ROS (Robot Operating Software)

# Talks

- NASA ULI Safe Aviation Autonomy Seminar. "Scalable Multi-Agent Reinforcement Learning through Intelligent Information Aggregation"
- Tata Consultancy Services Research and Innovation Labs. --"--

# Service

## Conference Reviewing

- AAAI (2021, 2024)
- CVPR (2024)
- IROS (2024)
- IFAC (2024)
- NeurIPS (2024)
- ICLR (2024)
- ACL (2024)

## Journal Reviewing

- IEEE Transactions on Circuits and Systems for Video Technology (2023)
- Complex & Intelligent Systems (CIS)
- Information Science (IS)
- IEEE Robotics and Automation Letters (RAL)
- Journal of Guidance, Control, and Dynamics (JDCD)

## Workshop Reviewing

- [The 4th Workshop on Mathematical Reasoning and AI](https://mathai2024.github.io/) @NeurIPS (2024)
- [NeurIPS 2024 Workshop on Multimodal Algorithmic Reasoning](https://marworkshop.github.io/neurips24/) @NeurIPS (2024)
- [Robotic Tasks and How to Specify Them?](https://sites.google.com/view/rss-taskspec) @RSS (2024)

# Workshop Organisation

- [Coordination and Cooperation in Multi-Agent Reinforcement Learning](https://sites.google.com/view/cocomarl-2024/home) (CoCoMARL) @RLC 2024

# Mentoring

A list of UROPs+MEngs I have mentored:

- Wenqi Ding (EECS, S.B., MIT) 2022, 2024
- Vittal Thirumalai (EECS, S.B.+ M.Eng.), 2024
- Jackson Zhang (EECS, S.B.+ M.Eng.), 2024
- Adelmo Morrison Orozco (EECS + Math, S.B.) 2024
- Marina Ten Have (EECS + AI, S.B.) 2024
- Darren Chen (EECS, S.B.) 2024
- Daniel Liu (EECS, M.Eng.) 2021-2022
- Kenneth Choi (EECS, S.B.) 2022
- Carson Smith (EECS, M.Eng) 2021
- Laura Peralta (Electrical and Electronics, B.E.; Hampton University) 2021
- Akila Sarvanan (AeroAstro, S.B.; MIT) 2021
- Simran Pabla (AeroAstro, M.Eng.; MIT) 2021

# Honors and Awards

- R&D 100 Awards - Software and Services Category (2023)
- USAF Analytics Excellence Award for the Space Training and Readiness Command (STARCOM) (2022)
- HULT Prize: Chennai Regional WInner and Singapore Regional Finalist (2017-2018)
- Ranked among the top 1% in the National Standard Examination in Physics (Physics Olympiad) (2016)

# Relevant Coursework

- Visual Navigation for Autonomous Vehicles
- Multiagent Communication
- Computational Sensorimotor Learning
- Intelligent Robotic Manipulation
- Underactuated Robotics
- Principles of Autonomy and Decision Making
- Reinforcement Learning
- Advanced Topics in Artificial Intelligence
- Parallel Computing and Scientific Machine Learning

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

For a detailed CV/resume please email me at `sidnayak at mit dot edu`
