# Algorithmic Trading & Stock Prediction System

## Why This Exists
Financial prediction projects often stop at model training and ignore
evaluation rigor, deployment considerations, and real-world constraints.
This project explores end-to-end stock prediction and algorithmic trading
logic using machine learning.

## Architecture
Market Data  
→ Feature Engineering  
→ Prediction Model  
→ Strategy Logic  
→ Trade Simulation

The system separates prediction from trading decisions to allow
strategy experimentation.

## Key Design Decisions
- Clear separation between prediction and execution
- Emphasis on reproducibility
- Focus on interpretable features
- Offline simulation before live usage

## Features
- Time-series stock prediction
- Feature engineering pipeline
- Trading strategy simulation
- Performance evaluation

## Getting Started
```bash
pip install -r requirements.txt
python main.py
