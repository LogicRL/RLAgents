# RLAgents

Reinforcement learning agent master for symbolic planning, applied on MonteZuma's Revenge. In symbolic planning, the complex tasks with sparse reward is divided into multiple sub-tasks, each handled by a reinforcement learning agent, the agent master manages all the reinforcement learning agents, choose which one to use and update. The key feature for reinforcement learning master is that it could dynamically add new agents to handle new sub-tasks, because as the agents goes deeper into the game, there will be more states and more sub-tasks. Right now it supports two different types of reinforcement learning agents: deep Q-network (dueling network) agent and policy gradient agent.

## Authorship

Below is the authorship information for this project.

  * __Author__:  Shangwu Yao
  * __Email__:   shangwuyao@gmail.com

Copyright (C) 2018, Shangwu Yao. All rights reserved.
