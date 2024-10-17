
# Lunar Lander - Q-Learning with Neural Networks 🚀

## Overview

This project showcases the implementation of **Deep Q-Learning** using a neural network to solve the Lunar Lander environment from the [Gymnasium](https://gymnasium.farama.org/) library. The goal is to train an agent to land a spacecraft safely on the moon's surface by learning optimal actions through reinforcement learning.

### Features
- **Neural Network for Q-Learning**: A deep neural network approximates the Q-value function, helping the agent choose optimal actions.
- **Experience Replay**: The agent stores past experiences to improve learning stability and efficiency by breaking correlations between consecutive experiences.
- **Soft Updates**: Gradual updates to the target network parameters for more stable training.
- **Hyperparameter Tuning**: Optimized hyperparameters like learning rate, discount factor (`gamma`), and exploration (`epsilon`) to achieve better performance.

---

## Hyperparameters

- **Learning Rate**: 0.0005
- **Batch Size**: 100
- **Gamma (Discount Factor)**: 0.99
- **Replay Memory Size**: 100,000
- **Tau**: 0.001 (for soft target updates)

Feel free to adjust them for experimentation.

---

## Results

The agent is trained to solve the Lunar Lander environment by landing the spacecraft safely within the landing zone. The goal is to achieve an average score of at least 220 across 100 consecutive episodes. When the agent reaches this score, the model is saved, and the training process ends.

---

## License

This project is licensed under the MIT License.

