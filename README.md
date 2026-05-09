# ANNCA — Adaptive Neural Network Chess Agent

## Overview
ANNCA is an experimental chess agent exploring neural network-based decision making for chess gameplay. The system is designed to interact with online chess platforms and learn from historical game data.

This project focuses on early-stage experimentation with machine learning approaches to chess, combined with automation and web interaction tools.

---

## Features

- Neural network-based move evaluation (Keras)
- Training pipeline using historical chess game data (PGN format)
- Automated interaction with online chess platforms
- Web automation and scraping capabilities
- Simple GUI interface for control and monitoring

---

## Technologies Used

- Python 3.12+
- TensorFlow / Keras
- Tkinter (GUI)
- python-chess (PGN parsing and game handling)
- PyAutoGUI (UI automation)
- Selenium (web interaction and scraping)

---

## Project Structure

- `ANNCA.py` — Main execution file  
- `requirements.txt` — Dependency list  
- Training modules — Neural network training and data processing components  
- Automation layer — Handles interaction with chess websites  

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

- neural network training for board evaluation  
- automated interaction with online chess environments  
- integration of machine learning with UI automation systems
