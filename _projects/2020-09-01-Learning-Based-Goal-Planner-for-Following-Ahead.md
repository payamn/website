---
layout:     project
title:     "LBGP: Learning Based Goal Planner for Following Ahead"
date:       2020-09-01
code:
doc:  https://arxiv.org/pdf/2011.03125.pdf
demo: XSOUdPFPMmA
best:       true
image_small: /files/projects_files/2020-09-01-Learning-Based-Goal-Planner-for-Following-Ahead.png
short:   We propose LBGP, a follow ahead method that uses both reinforcement learning and point based navigation. We address the limitations of classical methods and end-to-end approaches by combining Deep RL and classical motion planner
---
This paper investigates a hybrid solution which combines deep reinforcement learning (RL) and classical trajectory planning for the ``following in front'' application. Here, an autonomous robot aims to stay ahead of a person as the person freely walks around. Following in front is a challenging problem as the user's intended trajectory is unknown and needs to be estimated, explicitly or implicitly, by the robot. In addition, the robot needs to find a feasible way to safely navigate ahead of human trajectory. Our deep RL module implicitly estimates human trajectory and produces short-term navigational goals to guide the robot. These goals are used by a trajectory planner to smoothly navigate the robot to the short-term goals, and eventually in front of the user. We employ curriculum learning in the deep RL module to efficiently achieve a high return. Our system outperforms the state-of-the-art in following ahead and is more reliable compared to  end-to-end alternatives in both the simulation and real world experiments. In contrast to a pure deep RL approach, we demonstrate zero-shot transfer of the trained policy from simulation to the real world.
