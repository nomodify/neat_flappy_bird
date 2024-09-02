# neat_flappy_bird

**Overview**
This project is an implementation of an AI that learns to play the popular game Flappy Bird using the NeuroEvolution of Augmenting Topologies (NEAT) algorithm. The AI is capable of adapting its gameplay strategy over time through evolutionary neural networks, demonstrating the power of machine learning and evolutionary computation.

Features
AI-Powered Gameplay: The AI uses NEAT to evolve neural networks that control the Flappy Bird character, learning and optimizing its actions to survive longer in the game.
Real-Time Learning: As the AI plays, it continually improves its performance by evolving better strategies through genetic algorithms.
Performance Visualization: Track the progress and performance of the AI with visual feedback, including metrics like survival time and score.
Customizable Parameters: Tweak NEAT parameters such as population size, mutation rates, and fitness functions to experiment with different AI behaviors and outcomes.
Installation
Prerequisites
Python 3.6+
pygame for running the Flappy Bird game environment
neat-python for implementing the NEAT algorithm
Setup
Clone the repository:
git clone https://github.com/nomodify/flappy-bird-ai-neat.git
cd flappy-bird-ai-neat
Install dependencies:
pip install -r requirements.txt
Run the AI:
python flappy_bird_ai.py

Certainly! Below is a sample README for your Flappy Bird AI project using NEAT in Python, tailored for a GitHub repository:

Flappy Bird AI using NEAT (Python)
Overview
This project is an implementation of an AI that learns to play the popular game Flappy Bird using the NeuroEvolution of Augmenting Topologies (NEAT) algorithm. The AI is capable of adapting its gameplay strategy over time through evolutionary neural networks, demonstrating the power of machine learning and evolutionary computation.

Features
AI-Powered Gameplay: The AI uses NEAT to evolve neural networks that control the Flappy Bird character, learning and optimizing its actions to survive longer in the game.
Real-Time Learning: As the AI plays, it continually improves its performance by evolving better strategies through genetic algorithms.
Performance Visualization: Track the progress and performance of the AI with visual feedback, including metrics like survival time and score.
Customizable Parameters: Tweak NEAT parameters such as population size, mutation rates, and fitness functions to experiment with different AI behaviors and outcomes.
Installation
Prerequisites
Python 3.6+
pygame for running the Flappy Bird game environment
neat-python for implementing the NEAT algorithm
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/flappy-bird-ai-neat.git
cd flappy-bird-ai-neat
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the AI:

bash
Copy code
python flappy_bird_ai.py
How It Works
NEAT Algorithm
NEAT (NeuroEvolution of Augmenting Topologies) is an evolutionary algorithm that creates and evolves neural networks. In this project, NEAT is used to evolve a population of neural networks, where each network represents a potential Flappy Bird player. The AI’s fitness is determined by how long the bird survives in the game, with the best-performing networks being selected and mutated to create the next generation.

Game Environment
The AI interacts with a clone of the Flappy Bird game built using pygame. The game provides inputs such as the bird’s position and the distance to the next pipe, which the neural network processes to decide whether the bird should flap its wings.

Evolutionary Process
Initialization: The NEAT algorithm starts with a random population of neural networks.
Evaluation: Each network is tested in the game environment, and its fitness score is calculated based on survival time and score.
Selection and Mutation: The best networks are selected to reproduce, introducing mutations and crossover to create the next generation.
Iteration: This process repeats for many generations, with each generation improving over the last.
Customization
The AI's behavior can be adjusted by modifying the NEAT configuration file (config-feedforward.txt). Key parameters include:

Population Size: Number of neural networks in each generation.
Mutation Rates: Probability of mutations in the network structure.
Fitness Function: Criteria for evaluating the success of each network.
Experimenting with these parameters can lead to different AI behaviors and learning efficiencies.

Results
Over time, the AI learns to survive longer in the game, demonstrating the effectiveness of NEAT in training neural networks for complex tasks. The progress of the AI can be visualized through graphs and performance metrics displayed during runtime.
![image](https://github.com/user-attachments/assets/b2887190-cbba-49bd-aebd-8c07d79efa92)
