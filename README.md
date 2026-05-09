# ANNCA — Adaptive Neural Network Chess Agent

## Overview
ANNCA is an experimental chess agent exploring neural network-based decision making for chess gameplay. The system is designed to interact with online chess platforms and learn from historical game data.

This project focuses on early-stage experimentation with machine learning approaches to chess, combined with automation and web interaction tools.

The system was able to play complete games at a low intermediate level (~500 Elo), with stronger performance in early-game positions and progressively weaker performance in longer, more complex mid-to-late game states.

---

## Features

- Neural network-based move evaluation (Keras)
- Training pipeline using historical chess game data (PGN format)
- Automated interaction with online chess platforms
- Web automation and scraping via Selenium
- Simple GUI interface for control and monitoring

---

## Technologies Used

- Python 3.12+
- TensorFlow / Keras
- Tkinter (GUI)
- python-chess (PGN parsing and game handling)
- PyAutoGUI (UI automation)
- Selenium (web interaction and data collection)

---

## Project Structure

- `ANNCA.py` — Main execution file  
- `requirements.txt` — Dependency list  
- Training modules — Neural network training and data processing components  
- Automation layer — Handles interaction with chess websites and data scraping  

---

## How to Run

1. Install Python 3.12 or higher

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the main program:
```bash
python ANNCA.py
```

4. Follow the instructions printed in the console

---

## Status

Experimental / discontinued research prototype.

This project was an early attempt at building a neural network-based chess agent and has since been superseded by more advanced systems.

---

## Notes

ANNCA was primarily a learning project exploring:

- Neural network training for board evaluation  
- Pattern learning limitations in sequential decision problems like chess  
- Automated interaction with online chess environments  
- Integration of machine learning with web automation systems  

A key observation from this project was that the model struggled with long-horizon planning in complex positions, which led to weaker performance in later stages of games compared to the opening phase.
