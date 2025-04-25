
```markdown
# 🐯 Bagh-Chal Reinforcement Learning Environment

A custom reinforcement learning environment for the traditional Nepali board game **Bagh-Chal (Tiger and Goats)**.
This repository includes a playable GUI as well as a functional environment suitable for training reinforcement learning (RL) agents.

## 📦 Contents

- `baghchal_environment.ipynb`: Contains the logic for the Bagh-Chal environment including state management, rules, and agent interaction.
- `gui_updated.ipynb`: A graphical user interface to play the game manually or visualize agent decisions.
  
## 🎯 Goal

To provide a **publicly accessible** RL-compatible environment where researchers, students, and developers can:
- Learn RL using a traditional strategy game
- Train custom agents
- Interact via GUI for debugging or demonstrations

## 🧠 RL Environment Features

- **Customizable observation and action spaces**
- **Turn-based mechanics** supporting both Tiger and Goat agents
- **Reward structure** that can be extended for multi-agent learning

'''

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Aashishrimal/Baghchal.git
cd Baghchal
```

### 2. Setup Python Environment

You can use a virtual environment or conda. Then install the requirements:

```bash
pip install -r requirements.txt
```

### 3. Launch the GUI

You can interact with the game manually using:

```bash
jupyter notebook gui_updated.ipynb
```

### 4. Explore the Environment

Use `baghchal_environment.ipynb` to understand the rules, run test episodes, or begin integrating your own RL agents.

---

## 🤝 Contributing

Pull requests are welcome! If you plan to extend the environment or add agent training scripts, feel free to contribute.

--

## 🇳🇵 About Bagh-Chal

_Bagh-Chal_ (translates to "Tiger's Move") is a strategic board game originating from Nepal. It is played between two players: one controls four tigers and the other controls up to twenty goats. The tigers try to "eat" goats by jumping over them, and goats try to trap the tigers.

---

## ✨ Future Plans

- 
- Gym Compatible environment
- Sample RL agent implementations (DQN, PPO)
- Enhanced GUI with agent playback

---
