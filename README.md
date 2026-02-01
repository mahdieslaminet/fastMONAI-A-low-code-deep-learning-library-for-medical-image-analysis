# Fast-DDPM: A Lightweight Diffusion Model with Reconstruction-Based Evaluation

This project implements a simplified version of Fast Denoising Diffusion Probabilistic Models (Fast-DDPM) and evaluates it using a reconstruction-based binary classification task on MNIST.

The goal is to demonstrate:

a correct diffusion implementation,

a reproducible training pipeline,

and a meaningful accuracy/precision evaluation for a generative model.


# Project Structure
fast_ddpm/
│
├── model.py            # U-Net noise prediction model
├── diffusion.py        # Fast-DDPM forward and reverse processes
├── train.py            # Training script
├── sample.py           # Image generation from noise
├── binary_mnist.py     # Binary MNIST dataset (digit 0 vs 1)
├── evaluate.py         # Accuracy / precision evaluation
├── test_fast_ddpm.py   # Unit tests
├── requirements.txt
└── README.md

# installation 
pip install -r requirements.txt

in This project we implemented all the parts in just one jupyter notebook file "Fast-DDPM"

