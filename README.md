# LSTM-Based Music Generation (ABC Notation)

This project implements a character-level LSTM model to generate music sequences in **ABC notation**, following the deep learning sequence modeling techniques introduced in MIT’s 6.S191 course. The model learns musical patterns from a dataset of folk tunes and generates new melodies by sampling from the learned character distribution.

---

## 🎯 Overview

The goal of this project is to:

- Train a **character-level RNN** (specifically an LSTM) to model music as a sequence of characters.
- Generate original music in **ABC format** by sampling from the trained model.
- Explore hyperparameters, sequence sampling temperature, and training behavior.

This project includes:
- Data preprocessing and vectorization  
- LSTM model implementation  
- Training loop  
- Text/music generation  
