# Weather-Data-Reconstruction-with-Neural-Networks

## Overview

This repository contains a Jupyter notebook that walks through the process of reconstructing missing daily weather measurements for a European city over four decades. The approach covers:

1. Exploratory visualization of corrupted vs. original data  
2. Data preparation using PyTorch  
3. Neural network training for gap-filling  
4. Analysis of reconstructed results  

## Repository Structure
```
├── DeepLearning_NB.ipynb # Main analysis and model code
├ # CSV files required
│ ├── training_set_0.csv
│ ├── training_set_0_nogaps.csv
│ └── …
├── models/ # Saved model checkpoints
│ └── best_model.pt
└── README.md#
```
## Cloning the Repository 
```
git clone https://github.com/yourusername/weather-data-reconstruction.git
cd weather-data-reconstruction
```

## Launch the Notebook 
```
jupyter notebook notebook.ipynb
```

