# YADDPG

YADDPG is yet another implementation of Deep Deterministic Policy Gradients (DDPG). DDPG is described in this paper from Deepmind: [Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971) and is similar to Deep Q-Networks except that it allows an agent to learn a policy and operate in continous environments.

To test this out, this repo runs DDPG on the [swing up pendulum control problem from the openAI gym](https://gym.openai.com/envs/Pendulum-v0/). Generally after about 30-40 episodes the agent solves this classic control problem and is able to swing up and stabilise the pendulum like so:

![125](https://user-images.githubusercontent.com/2457362/36352295-0b57ffd6-14fa-11e8-82bd-effc2794d479.gif)
