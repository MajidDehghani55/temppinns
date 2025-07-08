# Physics-Informed Neural Networks with PyTorch

This repository explores **Physics-Informed Neural Networks (PINNs)** using PyTorch.  
PINNs integrate physical laws, expressed as partial differential equations (PDEs), into the training of neural networks.  
This approach is especially useful when data is scarce but the governing physics is well-understood.

## Overview

This project demonstrates how to implement PINNs to solve PDEs by embedding physical constraints directly into the loss function of a neural network.  

📝 For a detailed tutorial, check out the accompanying [Medium article](https://medium.com/@theo.wolf/physics-informed-neural-networks-a-simple-tutorial-with-pytorch-f28a890b874a).

## Installation 

### Clone the Repository

```
git clone https://github.com/TheodoreWolf/pinns.git
cd pinns
```

### Install the requirements

It is recommended to use a virtual environment.
```
python -m venv .venv           # Create a virtual environment
source .venv/bin/activate      # activate the virtual environment
```
Install the dependencies listed in pyproject.toml.
```
pip install -e .               
```

## Acknowledgments

Inspired by the foundational work by Raissi et al.  
This repo aims to provide an approachable and practical introduction to PINNs with PyTorch.
