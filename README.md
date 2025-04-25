

# 🐯 Bagh-Chal Reinforcement Learning Environment

A custom reinforcement learning environment for the traditional Nepali board game **Bagh-Chal (Tiger and Goats)**.  
This repository includes a playable GUI as well as a functional environment suitable for training reinforcement learning (RL) agents.

---

## 📦 Contents

- `baghchal_environment.ipynb`: Contains the logic for the Bagh-Chal environment including state management, rules, and agent interaction.
- `gui_updated.ipynb`: A graphical user interface to play the game manually or visualize agent decisions.

---

## 🎯 Goal

To provide a **publicly accessible** RL-compatible environment where researchers, students, and developers can:
- Learn RL using a traditional strategy game
- Train custom agents
- Interact via GUI for debugging or demonstrations

---

## 🧠 RL Environment Features

- **Customizable observation and action spaces**
- **Turn-based mechanics** supporting both Tiger and Goat agents
- **Reward structure** that can be extended for multi-agent learning

---

## 🚀 Getting Started

### 1. Setup Python Environment

```bash
git clone https://github.com/Aashishrimal/Baghchal.git
cd Baghchal
```

Install dependencies:

```bash
pip install -r requirements.txt
```

(Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate
```

### 2. Launch the GUI

Use the following command to open the interactive GUI in Jupyter:

```bash
jupyter notebook gui_updated.ipynb
```

### 3. Explore the Environment

Run and modify `baghchal_environment.ipynb` to:
- Understand the game rules
- Simulate game episodes
- Integrate and test your RL agents

---

## 🤝 Contributing

Pull requests are welcome!  
If you plan to extend the environment, implement agents, or enhance the GUI, feel free to fork and contribute.

---

## 🇳🇵 About Bagh-Chal

_Bagh-Chal_ (translates to "Tiger's Move") is a traditional strategy board game from Nepal.  
It is played between two players: one controls **four tigers**, and the other controls **up to twenty goats**.  
- Tigers try to "eat" goats by jumping over them.
- Goats try to trap the tigers by blocking their moves.

---

## ✨ Future Plans

- ✅ Gym-compatible environment wrapper  
- ✅ Custom reward system for RL training  
- ⏳ Sample RL agent implementations (DQN, PPO)  
- ⏳ Enhanced GUI with agent playback and move visualization

---
