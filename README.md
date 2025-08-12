# VizDoom: Defend the Center – PPO Agent

This repository contains a reinforcement learning agent trained to play the **"Defend the Center"** scenario from [VizDoom](https://github.com/mwydmuch/ViZDoom) using **Proximal Policy Optimization (PPO)** from [Stable-Baselines3](https://github.com/DLR-RM/stable-baselines3).  
The VizDoom environment is wrapped in a **Gym-compatible interface** to integrate seamlessly with Stable-Baselines3.

---

## 📜 Overview

In the **Defend the Center** scenario, the player stands in the middle of a circular arena while enemies spawn around the perimeter and approach the center. The goal is to **survive as long as possible** by eliminating enemies before they get too close.

This project demonstrates:

- Wrapping **VizDoom** in a **Gym-compatible environment**.
- Training a PPO agent with Stable-Baselines3.
- Preprocessing raw pixel observations for better training performance.
- Logging and evaluation of training progress.

