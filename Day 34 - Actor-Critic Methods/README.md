## Day 34 - Actor Critic Methods

- ActorCritic that is intended for reinforcement learning tasks, two main components: an actor and a critic.

- The actor generates a probability distribution over actions, taking the state as input, and consists of two linear layers with ReLU activation functions. The output is transformed using a softmax function to obtain action probabilities.

- The critic estimates the state-value function, with two linear layers, and outputs a single value representing the expected cumulative reward from a given state. This architecture combines both policy (actor) and value function (critic) estimation, making it suitable for actor-critic reinforcement learning algorithms.