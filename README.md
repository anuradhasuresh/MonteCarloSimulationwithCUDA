# Monte Carlo Simulation with CUDA
The goal of this project is to estimate the mathematical constant π (pi) using the Monte Carlo method, accelerated by CUDA, which uses the GPU (Graphics Processing Unit) for faster computation. 

# What is the Monte Carlo Simulation?
The Monte Carlo simulation is a mathematical technique that predicts possible outcomes of an uncertain event. It's named after the famous casino in Monaco because it relies on randomness, much like games of chance. Computer programs use this method to analyze past data and predict a range of future outcomes based on a choice of action. Monte Carlo simulations help to explain the impact of risk and uncertainty in prediction and forecasting models.

# How do we use this method to estimate π (pi)?
We can estimate π with the Monte Carlo Simulation by generating random points in a unit square and determining how many fall inside a unit circle. The ratio of points inside the circle to total points gives us an estimation of π/4, which can help us approximate the value of π.

# Why use CUDA?
CUDA allows us to use the power of GPU, which excels at handling large amounts of parallel computation, making it much faster than traditional CPU-based computations.

# Setup
Select GPU as the hardware accelerator:

1. Go to Runtime -> Change runtime type.
2. Select GPU under Hardware accelerator.
3. Click Save.
