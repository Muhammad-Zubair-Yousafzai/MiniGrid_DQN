# MiniGrid_DQN
This code is for training an agent to play the MiniGrid environment using Deep Q-Learning (DQN). The MiniGrid environment is a partially observable gridworld environment, where the agent must navigate and complete tasks like picking up a key and unlocking a door. 

The code sets up the MiniGrid environment, defines a neural network policy for the agent, and implements the DQN algorithm with experience replay and a target network. It trains the agent over multiple episodes, storing transitions in a replay buffer and updating the policy network's weights using temporal difference learning.

After training, the code evaluates the agent's performance by running multiple episodes and computing the average return. Finally, it converts the trained PyTorch model to the ONNX format, which can be used for submission to a challenge server or for deployment on other platforms.
