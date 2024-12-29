# ASDN: Adaptive Smoothing Drift Normalization

This repository provides the **Adaptive Smoothing Drift Normalization (ASDN)** framework, designed to handle non-stationary behavior in net load forecasting. 
## Key Features

- **Entropy-Weighted Update**  
  Dynamically adjusts the balance between historical estimates and current observations based on local variance changes, using a Rényi entropy factor.

- **Wiener Gain-Like Filtering**  
  Ensures near mean-square optimal weighting of old and new information, stabilizing the estimation process in varying conditions.

## Repository Structure

