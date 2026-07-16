# 🐦 AI Flappy Bird using NEAT

An AI-powered implementation of the classic **Flappy Bird** game built with **Python**, **Pygame**, and **NEAT (NeuroEvolution of Augmenting Topologies)**. Instead of manually coding the bird's behavior, the AI evolves neural networks through genetic algorithms, learning to navigate obstacles and achieve higher scores over successive generations.

---

## ✨ Features

* AI learns to play Flappy Bird automatically
* Uses the **NEAT-Python** library for neuroevolution
* Visualizes the learning process in real time
* Multiple AI agents trained simultaneously
* Fitness-based evolution across generations
* Configurable NEAT parameters
* Built with Pygame for smooth gameplay

---

## 🛠️ Technologies Used

* Python 3
* Pygame
* NEAT-Python

---

## 📁 Project Structure

```text
AI-Flappy-Bird/
├── flappy_bird.py        # Main game logic
├── config-feedforward.txt # NEAT configuration
├── assets/               # Bird, pipe, background, and base images
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Flappy-Bird.git
cd AI-Flappy-Bird
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the project

```bash
python flappy_bird.py
```

---

## ⚙️ How It Works

1. The game starts with multiple AI-controlled birds.
2. Each bird is controlled by its own neural network.
3. Birds receive inputs such as:

   * Distance from the next pipe
   * Bird's current height
   * Position of the pipe gap
4. The neural network decides whether the bird should jump.
5. Birds earn fitness by surviving longer and passing pipes.
6. The best-performing networks reproduce and evolve into the next generation.
7. Over time, the AI becomes increasingly skilled at the game.

---

## 📊 Learning Process

The NEAT algorithm improves performance by:

* Evolving network topology and weights
* Selecting the fittest genomes
* Mutating and crossing over genomes
* Preserving species diversity
* Optimizing decision-making over generations

---

## 📌 Future Enhancements

* Save and load trained AI models
* Adjustable game speed
* Training statistics and graphs
* Human vs AI mode
* Different difficulty levels
* Support for custom game environments

---

## 🎯 Learning Outcomes

This project demonstrates:

* Neuroevolution using NEAT
* Artificial Intelligence for games
* Genetic Algorithms
* Neural Networks
* Reinforcement through evolutionary learning
* Python game development with Pygame

---

## 📜 License

This project is intended for educational and learning purposes. Feel free to modify and extend it for personal or academic use.
