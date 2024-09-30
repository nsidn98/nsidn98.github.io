---
title: "Data-Driven Monitoring with Mobile Sensors and Charging Stations using Multi-Arm Bandits and Coordinated Motion Planners"
collection: publications
permalink: /publication/envMonitoring
date: 2024-07-09
venue: "ACC"
---

Authors: **Siddharth Nayak**, Marcus Greiff, Arvind Raghunathan, Stefano Di Cairano, Abraham P Vinod

We study the problem of data-driven monitoring using an autonomous search team. We consider a typical monitoring task of classifying a search environment into interesting and uninteresting regions as quickly as possible using a search team comprised of mobile sensors (e.g., drones) and mobile charging stations (e.g., ground vehicles). For widespread deployment in the physical world, the search team must also accommodate noisy data collected by the mobile sensors, overcome energy constraints on the mobile sensors which limit their range, and ensure collision avoidance for the charging stations. We address these challenges using a novel, bi-level approach for the monitoring task, where a high-level planner uses past data to determine the potential regions of interest for the drones to visit, and a low-level path planner coordinates the paths for the entire search team to visit these regions subject to the posed constraints. We design the high-level planner using a multi-armed bandit framework. For the low-level planner, we propose two approaches: an optimal integer program-based motion planner and a real-time implementable graph-based heuristic planner. We characterize several theoretical properties of the proposed approaches, including anytime guarantees, upper bounds on computing time, and task completion time. We show the efficacy of our approach in simulations, including one in Gazebo where we identify harvest-ready trees using an autonomous heterogeneous search team. [[PDF]](https://shadow.merl.com/publications/docs/TR2024-078.pdf)

<!-- Recommended citation: Your Namesdas, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->
