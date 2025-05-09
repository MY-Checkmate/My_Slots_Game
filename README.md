# My_Slots_Game

**An AI automation system designed to simulate and optimize decision-making in slot-style games.**

---

## 🧠 Overview

This project runs and tests decision-making bots in simulated gambling environments like slot machines. It automates browser interaction, detects symbols (e.g., scatters), and dynamically adjusts betting strategies using custom rules.

---

## Features

- **Scatter Detection** using OpenCV
- **Bet Optimization** based on past outcomes
- **Browser Automation** via Selenium
- **Custom Rules via JSON**
- **Real-time Alerts** (audio/visual)
- **Auto File Ingestion** and Game Surveillance

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/MY-Checkmate/My_Slots_Game.git
cd My_Slots_Game
````

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

Basic simulation:

```bash
python main.py
```

Run AI system:

```bash
python my_slots_game_main.py
```

Adjust bets manually:

```bash
python bet_adjuster.py
```

Run with specific bot and environment:

```bash
python main.py --bot bayesian_bot --env slot_machine --episodes 1000
```

---

## 🧪 Testing

```bash
pytest tests/
```

---

## 📁 Notable Files

* `main.py` — Main simulation entry point
* `my_slots_game_main.py` — Main controller for AI behavior
* `bet_adjuster.py` — Script to adjust bet amounts
* `bet_optimizer.py` — Advanced betting strategy optimizer
* `alert_engine.py` — Notification system for key events
* `ruleset/tactic.json` — Config file for decision strategies
* `assets_config.json` — Mappings for game symbols/buttons

---

## 🤝 Contributing

Contributions welcome! Fork the repo, create a feature branch, and open a PR.

```
