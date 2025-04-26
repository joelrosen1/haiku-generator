# Haiku Generator

A Python-based project that generates haikus using two different approaches: Recurrent Neural Networks (RNN) and Markov Models.

## Overview

This project explores two different methods for generating haikus:
1. **RNN-based Generator**: Uses a Recurrent Neural Network to learn patterns from existing haikus and generate new ones
2. **Markov Model Generator**: Uses Markov chains to generate haikus based on word transition probabilities

## Requirements

- Python 3.x
- Dependencies listed in `requirements.txt`:
  - pandas>=1.3.0
  - nltk>=3.6.0
  - torch>=2.0.0
  - numpy>=1.21.0
  - gensim>=4.0.0
  - scikit-learn>=0.24.0

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
cd haiku-generator-1
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Project Structure

- `RNN/`: Contains the Recurrent Neural Network implementation
- `Markov Model/`: Contains the Markov Model implementation
- `all_haiku.csv`: Dataset of haikus used for training
- `requirements.txt`: List of Python dependencies

