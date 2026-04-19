# Indian Names Neural Network

A character-level language model trained on Indian names, built from scratch in PyTorch.

Inspired by Andrej Karpathy's `makemore` series, this project explores name generation step by step, starting with a bigram model and later moving to an MLP.

## Goal

Generate new Indian-style names by learning character patterns from a cleaned dataset of Indian names.

## Current Progress

- [x] Dataset collected and cleaned
- [x] Bigram model implemented
- [ ] MLP model in progress
- [ ] Regional conditioning

## Files

- `notebooks/00_data_prep.ipynb` - dataset cleaning and preparation
- `notebooks/01_bigram.ipynb` - bigram model
- `notebooks/02_mlp.ipynb` - next-stage model work
- `data/names.txt` - cleaned training data

## Requirements

```bash
pip install -r requirements.txt
```
