# Welcome to epoch 13 of FruitPunch AI Code!

This time we have a more practical experimentation session.

See the installation_instructions file for python, gym and keras installation instructions

# The Deep Q Learning challenges:
This time the challenges are a bit more open ended, so work together and have fun!

1. Try modifying one the Deep Q Networks. Read all about the layers, activations, optimizers and losses that keras has to offer, and try out the ones you think can improve the DQN.
https://keras.io/

2. Try training one of the DQN's on some different environments at the same time. If you modify and refine the DQN enough, you might end up with a gym AGI!
https://gym.openai.com/envs/#classic_control


# The theory:
https://en.wikipedia.org/wiki/Q-learning


# original readme

# deep-q-learning

Introduction to Making a Simple Game AI with Deep Reinforcement Learning



![animation](./assets/animation.gif)

Minimal and Simple Deep Q Learning Implemenation in Keras and Gym. Under 100 lines of code!

The explanation for the `dqn.py` code is covered in the blog article
[https://keon.io/deep-q-learning/](https://keon.io/deep-q-learning/)


I made minor tweaks to this repository such as `load` and `save` functions for convenience.

I also made the `memory` a deque instead of just a list.
This is in order to limit the maximum number of elements in the memory.


The training might be unstable for `dqn.py`. This problem is mitigated in `ddqn.py`.
I'll cover `ddqn` in the next article.
