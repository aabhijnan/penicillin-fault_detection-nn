# Neural Network-Based Fault Detection in Industrial Penicillin Fermentation (IndPenSim V3)
## Overview
* **Objective**: Apply PyTorch neural networks to detect process faults across 100 simulated industrial-scale penicillin fermentation batches using online bioprocess sensor data.
*  **Dataset**: Uses the `100_Batches_IndPenSim_V3.csv` benchmark dataset (~1.9 GB). Link to download the dataset: https://data.mendeley.com/datasets/pdnjz7zz5x/1/files/e7007dff-4061-494f-a9f5-16c20f457d1d
*  **Deep Learning Framework**: Built with `PyTorch` (`2.11.0+cu128`) using `torch.nn` for neural network modeling.
## How to Run
1. Clone this repository and download `100_Batches_IndPenSim_V3.csv`[cite: 1].
2. Update the dataset path in the CSV loading cell of `PenSim_Ver3.2_CPE_520.ipynb`[cite: 1].
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn torch
