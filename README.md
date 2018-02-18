# YADDPG

YADDPG is yet another implementation of Deep Deterministic Policy Gradients (DDPG) described in this paper from Deepmind: [Continuous control with deep reinforcement learning](https://arxiv.org/abs/1509.02971). DDPG is similar to Deep Q-Networks except that it allows an agent to learn a policy rather than just a Q function which allows it to operate in continous environments.

This runs DDPG implemented with tensorflow on the [swing up pendulum control problem from the openAI gym](https://gym.openai.com/envs/Pendulum-v0/). This is a classic control problem in which the agent must apply torques to the base of a pendulum to balance it on its end. The torques available to the agent aren't sufficient to just brute force the pendulum into place so instead it needs to learn to "swing it up" then balance the pendulum once it's in place. This implementation manages to do just that after about 30-40 training episodes:

<p align="center">
  <img src="https://user-images.githubusercontent.com/2457362/36352295-0b57ffd6-14fa-11e8-82bd-effc2794d479.gif" alt="Episode 125"/>
</p>
