# cartpole-deep-policy-gradient
A fork of [ddpg.py](https://github.com/pemami4911/deep-rl/blob/master/ddpg/ddpg.py). Gets rid of the deterministic part of the deep deterministic policy gradient algorithm, and makes all the required changes to get it to work with the CartPole-v0 OpenAI gym environment.

This is just a reference for my CartPole actor-critic model [here](https://github.com/crypdick/actor-critic-cartpole).

Dependencies: 

* [Tensorflow 1.0.0](https://www.tensorflow.org/install/)
* [tflearn](http://tflearn.org/installation/)
* [OpenAI Gym 0.7.3](https://github.com/openai/gym/)

So far: 

1. DDPG - Deep Deterministic Policy Gradients, evaluated on the Pendulum environment in OpenAI Gym
