---
title: "Trust Region Policy Optimization | Course Project"
date: 2024-04-30 00:00:00 +0530
categories: [Project]
tags: [reinforcement learning, course project]
---

## Project Overview

This course project was completed under the guidance of **Prof. Subrahmanya Swamy Peruru**, in collaboration with my teammates **Yash Verma** and **Paritosh Pankaj**. Our primary focus was to develop a deep understanding of **Trust Region Policy Optimization (TRPO)** and to implement a practical algorithm based on this method.

In the later stages of the project, we employed the **MuJoCo physics simulation environment**, which provided us with a continuous state space of **376 dimensions**, where each state could range from **minus infinity to infinity**. This environment was used to model a **bipedal robot** designed to simulate **human walking**.

Our experiments involved training the robot's walking motion using **TRPO**, and we demonstrated that TRPO outperforms other models, such as **Proximal Policy Optimization (PPO)** and **Soft Actor-Critic (SAC)**, particularly in training a **humanoid walk**. The findings underscored the superior efficiency of **TRPO** for complex tasks, especially in scenarios involving large state spaces and intricate dynamics.

## Resources

- [Link to the Research Paper](https://arxiv.org/pdf/1502.05477.pdf)
- [Presentation: The Mathematics Behind the Model](https://docs.google.com/presentation/d/1SvSRa8LQY9OYLLbO5gEWhcIGgx3YTSaeOVJ-FYU3jBA/edit#slide=id.p)
- [Implementation Details in the Simulation](https://docs.google.com/presentation/d/1fjHPl11lA-PWJJobQR5Dp2lViF3Cjf5F8WiBu-3XEq0/edit#slide=id.g2d1a7f1cc29_4_59)
