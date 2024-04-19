---

# Flappy Bird NEAT

Flappy Bird NEAT is a Python implementation of the popular Flappy Bird game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm for artificial intelligence to play the game. NEAT is used to evolve neural networks that control the birds in the game.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)

## Introduction

This project aims to demonstrate the application of NEAT in training an AI to play Flappy Bird. Instead of relying on hardcoded rules or heuristics, the birds in this game learn to navigate through the pipes by evolving neural networks through genetic algorithms.

## Features

- Flappy Bird gameplay with AI-controlled birds.
- NEAT algorithm for evolving neural networks.
- Dynamic pipe generation and collision detection.
- Real-time visualization of the best performing bird's neural network.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/Flappy-Bird-NEAT.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Flappy-Bird-NEAT
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to start training the AI:

    ```bash
    python flappy_bird_neat.py
    ```

2. Monitor the training progress in the console output. The script will display information about the current generation, score, and the best performing genome.

3. Once the training is complete, the script will output the best genome found during the evolution process.

## Configuration

The NEAT algorithm parameters and Flappy Bird game settings can be configured using the `configuration.txt` file. You can adjust parameters such as population size, mutation rates, and neural network structure in this file to customize the training process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
