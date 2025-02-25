# Filter Pruning in FashionMNIST

This repository contains an implementation of filter pruning on a CNN trained on
the FashionMNIST dataset. The goal is to reduce the number of filters while
maintaining accuracy.

## Features

- Prunes filters based on their importance
- Re-trains the model after pruning
- Evaluates performance before and after pruning

## Usage

1. Load the provided unpruned model:
   ```python
   import torch
   model = torch.load("trained_model_unpruned.pth")
   ```
2. Perform filter pruning.
3. Fine-tune the pruned model.
4. Evaluate accuracy and compare results.

Use the provided `.pth` file for experimentation by loading it into your
environment. It is not the pruned model but the unpruned one, You can make
modifications to it as your wish to improve it
