# Snake Game: training using Q-learning (Reinforcement Learning Algorithm)
This repository contains a Snake Game implemented using Python and PyTorch, showcasing reinforcement learning techniques. The goal of this project is to train an AI agent to play the classic Snake game using Q-learning.

https://github.com/DmFors/ml-rl-snake/assets/62393996/3d2976b2-dd91-4e60-a0dc-6ce83633e366
## Prerequisites
Before you begin, ensure you have met the following requirements:
* python 3.x
* pygame
* pytorch (>=1.0.0)
* numpy
* matplotlib (for plotting results)

## Installation
Clone the repository to your local machine:
```
git clone https://github.com/dmfors/ml-rl-snake.git
cd ml-rl-snake
```
Install the required dependencies:
```
pip install pygame torch numpy matplotlib
```
## Project Structure
The project consists of the following files:
* game.py: Implements the Snake Game logic
* model.py: Contains the Q-learning neural network model (Linear_Qnet class) and the Q-learning trainer (QTrainer class)
* agent.py: The main entry point for training the AI agent
* helper.py: Provides a utility function for plotting a training statistics

## Usage
To train the AI agent to play the Snake Game, run the following command:
```
python agent.py
```
The training process will start, and you can monitor the agent's progress on the gameplay on the left and the learning graph on the right.

## Results
During training, the project will record the agent's score and plot it using Matplotlib. You can visualize how the agent's efficiency improves over time.

## License
This project is licensed under the MIT License.
