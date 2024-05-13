# Data-Poison-Detection-Schemes-For-Distributed-Machine-Learning
Introduction
    This project implements data poison detection schemes for distributed machine learning. It includes functionality for running experiments, processing datasets, and visualizing gradient data.

Setup
1. Dependencies: Ensure you have all the required dependencies installed. You can find them listed in the   requirements.txt file.

    pip install -r requirements.txt

2. Data Preparation
    Before running experiments, prepare the datasets by executing the Python script.

    python prepare_datasets.py

Usage
1. Running Experiments
Execute the main script to run experiments.

    python main.py

This script runs experiments with specified parameters such as experiment index, number of poisoned workers, and replacement method.

2. Visualization: The resulting gradient data is visualized and saved as an image file named defense_results.jpg.

File Structure
    - federated_learning: Contains modules for federated learning functionality.
    - data_loaders: Stores pickle files containing prepared dataset loaders.
    - models: Contains trained models.
    - logs: Stores log files from experiments.


Additional Notes

1. Make sure to update the file paths in the code to match your system's directory structure.
2. Adjust experiment parameters and dataset configurations as needed.