# AI-ML-Class-HW5
This is a homework assignment that is being hosted for an assignment

This repository contains a script for training a Morgan Fingerprint model for the Lipophilicity dataset. The script takes in hyperparameters and calculates the test set RMSE.

## Contents
- `src/train_model.py`: The script for training the model.
- `environment.yml`: Conda environment file.
- `LICENSE`: License for this project.
- 'Data': Contains the csv file data utilized in this repository

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/smithjt6/AI-ML-Class-HW5

2. Activate the enviornment.yml to ensure all packages are available 

3. Edit the "Input.json" file to adjust for the wanted hyperparameters
   NOTE: Currently only supports a single layer of neurons due to limitations of sk-learn's MLPRegressor function

