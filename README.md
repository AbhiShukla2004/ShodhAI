# 🧠 Shodh Deep Learning & Offline Reinforcement Learning Project

This repository contains two major components:
1. **Deep Learning Experiments** (`shodh-dl-final.ipynb`) — implementing, training, and evaluating deep learning models using modern architectures.
2. **Offline Reinforcement Learning Agent** (`Task 3 Offline Reinforcement Learning Agent.ipynb`) — implementing reinforcement learning techniques for decision-making tasks without live environment interactions.

Both notebooks are part of a research-oriented exploration under the **Shodh Project**, integrating **machine learning** and **reinforcement learning** paradigms.

---

## 🚀 Project Overview

### 🔹 Shodh Deep Learning (DL)
This notebook explores:
- Neural network architectures for supervised learning tasks  
- Model training, validation, and performance analysis  
- Use of modern deep learning libraries such as TensorFlow or PyTorch  
- Visualization of loss curves and accuracy metrics  

### 🔹 Task 3: Offline Reinforcement Learning Agent
This notebook demonstrates:
- Reinforcement Learning (RL) setup for offline (batch) environments  
- Agent training from pre-collected datasets instead of live interactions  
- Algorithms such as DQN, CQL, or BCQ (depending on implementation)  
- Evaluation of policies and learning stability  

---

## ⚙️ Installation

Clone the repository and set up the environment.

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

It is recommended to use a Python virtual environment.
python -m venv venv
source venv/bin/activate       # For Linux/Mac
venv\Scripts\activate          # For Windows

Then install dependencies:
pip install numpy pandas matplotlib torch torchvision gym tensorflow scikit-learn tqdm
