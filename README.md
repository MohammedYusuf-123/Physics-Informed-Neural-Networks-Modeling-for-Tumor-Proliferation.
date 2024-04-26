# Physics-Informed-Neural-Networks-Modeling-for-Tumor-Proliferation.

# Introduction
This README.md describe the steps to run the Physics-Informed Neural Network to stimulate the growth of Glioblastoma tumor which effects the healthy tissues of the brain.

# Execution
This code is completely compatible with Google Colab and can be directly imported in it and executed.

# Features
This model provides users with more flexiblity when it comes to changing any of the parameters such as:
1. LAYERS (Used in the model during training)
2. NEURONS_PER_LAYER (Number of neurons per layer to get appropriate results)
3. EPOCHS (Number of epochs)
4. LEARNING_RATE (which is a hyper-parameter used to govern the pace at which an model updates or learns the values of a parameter estimate)

# Files
This Github repository contains following siles:
1. Google Colab compatible .ipynb file.
2. Report on how the code works and how it solves Diffusion-Reaction equation to simulate tumor growth in brain.
3. A PPT showing the entire project in a understandable manner.
4. Graph depicting Loss function changes during training.
5. Image showing Initial estimate done by PINN for Glioblastoma tumor
6. Image showing the growth simulated by PINN by the end of the training process.

# Requirements
All the necessary libraries are already included in Google Colab and can be executed without downloading them.
The major libraries used were:
1. PyTorch.
2. NumbPy.
3. Matplotlib.
4. Autograd.
5. Standard Python Libraries such as "os", "time", and "functools".
