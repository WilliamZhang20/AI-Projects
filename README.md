# AI Projects

A collection of my AI projects for grouping them together, stored as submodules.

The current project list is:
1. The implementation of a Q-learning algorithm to train a basic AI agent to play the mathematical strategy game of Nim. It gains 'skill' by playing the game against itself around 10,000 times. After winning and losing, it will determine the optimal actions to take from a wide variety of game states, and stores them in a table. During a game play, it will consult the table and play accordingly.
2. Various machine learning algorithms from scratch, using only NumPy, no TensorFlow or PyTorch in the algorithm. So far, there is a fully working artificial neural network.
3. A Deep-Q Network for balancing a cart pole in a simulation. Similar to the 1st project in the list, but because the action and state space is so vast, a simple table won't work to determine optimal actions from states. So it uses a neural network and stores a memory array to compare and learn from both present and past experiences.
   
