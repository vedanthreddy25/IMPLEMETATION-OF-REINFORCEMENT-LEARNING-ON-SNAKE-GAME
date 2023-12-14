"""IMPLEMETATION-OF-REINFORCEMENT-LEARNING-ON-SNAKE-GAME"""

#Reinforcement Learning

First, one may wonder why reinforcement learning is being used rather than supervised machine learning. The reason for this is that supervised ML algorithms require training with an input and a "correct answer" known as the goal.A standard technique would not work in this example since we don't know what to do at every level of the game. This is the time when Reinforcement Learning comes into action.

The environment (our game) and the agent (our Snake—or, more accurately, the Deep Neural Network that controls our Snake's movements) are the two primary elements of reinforcement learning. Every time an agent acts, the environment rewards them; these rewards might be favourable or unfavourable, depending on how well the agent performed that particular activity.

This repository contains an implementation of Reinforcement Learning (RL) algorithms applied to the classic Snake game. Here's a quick overview:

What you'll find:
•	Python code for the Snake game environment.
•	Implementations of popular RL algorithms like Q-Learning and Deep Q-Learning (DQN) for playing the game.
•	Tools for training, visualizing, and evaluating the performance of the RL agents.

Requirements:
1.	Python 3.7+
2.	PyTorch 
3.	pygame

Getting Started:
1.	Clone the repository.
2.	Install the necessary libraries.
3.	Run snake_game_human.py to understand game by playing manually.
4.	Setup game enivronment (game.py)
5.	Choose model.py to use RL algorithms(e.g., Q_Learning,Deep_Q_Learning)
6.	Run the agent file (python agent.py) which imported models.
7.	Observe the training progress and agent performance in the terminal.
8.	Use provided visualization scripts to analyze the agent's behavior.
   
Structure:
1. game: Contains the Snake game environment implementation.
2. agent: Holds the RL algorithms and agent code.
3. model: Pre-trained models for each algorithm.
4. helper: Training, evaluation, and visualization scripts.
5. README.md: This file (you're reading it!)


Additional Notes:
1.	Feel free to modify the code to experiment with different RL parameters, hyperparameters, and training configurations.
2.	Share your findings and improvements via pull requests or issue reports.
Enjoy learning about RL and training your own Snake-playing AI!

Further Resources:
1. Sutton and Barto's "Reinforcement Learning: An Introduction"
2. David Silver's Reinforcement Learning Lecture Series
3. OpenAI Gym Snake environment (for comparison)

I hope this README provides a helpful starting point for your exploration of RL and the Snake game!





#REFERENCE

1.https://arxiv.org/pdf/2007.08794.pdf

2.https://www.researchgate.net/publication/221455879_High-3.level_reinforcement_learning_in_strategy_games

4.https://arxiv.org/abs/1312.5602

5.https://papers.nips.cc/paper/2017/file/39ae2ed11b14a4ccb41d35e9d1ba5d11-Paper.pdf

6.https://medium.com/@hugo.sjoberg88/using-reinforcement-learning-and-q-learning-to-7.play-snake-28423dd49e9b

8.https://towardsdatascience.com/learning-to-play-snake-at-1-million-fps-4aae8d36d2f1

9.http://cs229.stanford.edu/proj2016spr/report/060.pdf

10.https://mkhoshpa.github.io/RLSnake/

11.https://docs.python.org/3/library/multiprocessing.html

12.https://github.com/eidenyoshida/Snake-Reinforcement-Learning

13.https://github.com/python-engineer/snake-ai-pytorch/blob/main/model.py
