# Cobra FCC

Cobra FCC is a reinforcement learning project focused on developing an AI agent capable of playing the classic Snake game. The project utilizes PyTorch for the machine learning model and Pygame for game development. This repository contains the code for both the game environment and the AI model.

## Features

- **Snake Game Environment**: A custom-built game environment using Pygame for visualizing the snake's movement, food placement, and score tracking.
- **AI Agent**: An AI agent trained to play the Snake game, using a deep reinforcement learning model.
- **Training and Evaluation**: Scripts for training the AI model and evaluating its performance over time.

## Installation

To run this project, you will need Python 3.6 or later. First, clone the repository to your local machine:

```bash
git clone https://github.com/cfiestas6/cobra-fcc.git
```

Then, install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To train and visualize the AI model, execute:

```bash
python agent.py
```

## Project Structure

- `game.py`: The main script for the Snake game environment.
- `agent.py`: Contains the AI agent and training loop.
- `model.py`: Defines the neural network model for the AI agent.
- `helper.py`: Utility functions for plotting training progress.
- `model/model.pth`: Pre-trained model weights.
