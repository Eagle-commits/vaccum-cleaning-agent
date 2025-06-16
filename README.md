# vaccum-cleaning-agent Labwork

Student Name= Amish Wagle <br>
CRN = 021-308


# 🧹 Intelligent Vacuum Cleaner Agents
Project Overview

This repository contains Python implementations of three types of **vacuum cleaner agents** designed to operate within a virtual 2D room environment with randomly distributed dirt. Each agent showcases different AI decision-making strategies, from basic reflex behavior to utility-based reasoning.

---

## 🤖 Agent Types

### 1. **Goal-Based Agent**
- Operates with a defined goal: a completely clean environment.
- Maintains memory of previously visited and cleaned locations.
- Uses goal testing to choose actions that lead to efficient cleaning.

### 2. **Simple Reflex Agent**
- Reacts based solely on the current percept (e.g., whether the tile is dirty).
- Has no memory or internal model of the environment.
- Uses a simple condition-action rule to clean dirt immediately.

### 3. **Utility-Based Agent**
- Chooses actions based on a utility function to maximize performance.
- Balances exploration and cleaning to optimize long-term results.
- Demonstrates more advanced reasoning and prioritization.

---

## 🗺️ Environment

- The environment is a **2D grid room** where each cell may be:
  - 🟩 Clean
  - 🟥 Dirty (randomly initialized)
- Agents can move in four directions: **up, down, left, right**.
- They clean the tile they currently occupy if it contains dirt.
- The simulation tracks and visualizes each agent's actions and performance.

---

## 🚀 Features

- Modular and extensible agent designs.
- Randomized environment generation for varied testing.
- Simple visualization and logging of agent behavior.

---
