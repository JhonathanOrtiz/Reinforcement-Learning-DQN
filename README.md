# Reinforcement-Learning-DQN

This is an implementation about DQN Paper, With OpenAI envoirements.

DQN (Deep Q Network) is a Deep Mind's paper based in Q-Learning.

## Q-Learning
This algorithm learns the Q(s,a) functions (Action - Value) how good is the action for a specify state.
In Q-Learning we biuld a table with each possible Q-value for each state(s) and action(a) and Q-value is an float value that we define like the matematical hope to get a Reward(r) take an Action(a) in the State(s). So, If we sample an Action(a) find a Reward(r) and new State(s'), we want determinate the Action(a') that maximize Q(s,a).


![1_5ffOxpSgIJCYn0XccfFYUQ](https://user-images.githubusercontent.com/59035193/81778443-e122b000-94c0-11ea-948d-adb8f9462800.png)


However, if the combinations of actions-states are so large the memory computation is too much expensive, in this case, we switch to DQN.

## Deep Q-Network
With the new approach, we generalize the approximation of the Q-value function rather than remembering the solutions.


Neural network to get the best Q-value for an action given an state, However, When we train when a sequence of action and values we get a problem correlation into the data.

Memory Replay to train de Neural network.

If you want learn more about Q-Learning and Deep Q-Network:

Q-Learing and Q-Learning Algorithm.

https://medium.com/@jonathan_hui/rl-dqn-deep-q-network-e207751f7ae4

Markov Decission Process:

https://en.wikipedia.org/wiki/Markov_decision_process

Epsilon Greedy policy

https://medium.com/analytics-vidhya/the-epsilon-greedy-algorithm-for-reinforcement-learning-5fe6f96dc870

Thank you to

Andrés Matesanz

https://github.com/Matesanz
