---
layout: page
title: Code
permalink: /code/
---
## LMPC GitHub Repo
[Here](https://github.com/urosolia/LMPC) I have collected few implementations of the LMPC for linear and non-linear systems. The simplest example is the [Constrained Linear Quadratic Regulator](https://github.com/urosolia/LMPC/tree/master/LinearLMPC), where the LMPC is used to solve the constrained optimal control problem introduced below. The figure on the right shown that the LMPC after few iterations converges to the optimal closed-loop trajectory.  

<p align="center">
	<img src="https://github.com/urosolia/urosolia.github.io/raw/main/images/codeImg/CLQR.png" width="420" />
	<img src="https://github.com/urosolia/urosolia.github.io/raw/main/images/codeImg/CLQR_cl.png" width="420" />
</p>

In the same repo you can find also non-linear LMPC examples. For instance, [this example](https://github.com/urosolia/LMPC/tree/master/NonlinearLMPC/DubinsRacing_ConvexSafeSet) shows how to code the LMPC to drive a dubins car from a starting point to a goal set. The control problem is the described by the optimal control problem introduced below. The figure on the right shown that the LMPC after few iterations converges to a trajectory which cuts the curve saturating the road boundaries.  


<p align="center">
	<img src="https://github.com/urosolia/urosolia.github.io/raw/main/images/codeImg/nonlinear.png" width="420" />
	<img src="https://github.com/urosolia/urosolia.github.io/raw/main/images/codeImg/nonlinear_cl.png" width="420" />
</p>




## LMPC: A Simple Matlab Example
I have implemented a simple LMPC to solve an infinite time optimal control problem. A summary of the LMPC implementation strategy and the code are described in the [LMPC cookbook](https://github.com/urosolia/LMPC_SimpleExample/raw/master/PDF_README.pdf). This simple example is ideal to get started with LMPC as it consists of few lines of code, which can be found [here](https://github.com/urosolia/LMPC_SimpleExample).

## Autonomous Racing Open Source Code
I have implemented the Learning Model Predictive Control (LMPC) algorithm for autonomous racing in Python using QP solvers. All the code can be found on my [here](https://github.com/urosolia/RacingLMPC/tree/master).

The Learning Model Predictive Control (LMPC) uses forecast to plan the vehicle trajectory looking few seconds into the future. This trajectory is planned in order to minimize the lap time, but it is constrained to land in a set of safe states. In the animation below we see the closed-loop trajectory (in black) of the vehicle after 5 laps of learning. The LMPC plans an open-loop trajectory (in red) which minimizes the lap time and lands in the safety set (in blue).

<p align="center">
	<img src="https://github.com/urosolia/urosolia.github.io/raw/main/images/codeImg/racing.gif" />
</p>