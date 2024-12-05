# Jailbreak_ChatGPT3.5

This repository contains research and implementation for generating adversarial prompts to bypass ChatGPT-3.5's moderation framework using the KOV algorithm. The project aims to evaluate the effectiveness of adversarial suffixes in circumventing moderation systems and explores hyperparameter tuning to optimize this process.

The repository is organized into main components:
- **KOV-main**: Contains the implementation of the KOV algorithm and its dependencies.
- **Output**: Includes csv files related to the results generated during the evaluation process for Q1, Q2 and Q3
- **Jailbreaking_Starter.ipynb**: To run our KOV implementation.
- **harmful_behaviors.csv**: Prompts for Q3


## Repository Structure

### **KOV-main**
This folder contains all the scripts and utilities required to implement and evaluate the KOV algorithm:
- **`DPW_Solver.py`**: Implements the DPW (Double Progressive Widening) solver for Monte Carlo Tree Search.
- **`KOV.py`**: The main script that orchestrates the KOV algorithm's workflow, including hyperparameter tuning and adversarial prompt generation.
- **`WhiteBox.py`**: Provides the white-box functionality for generating adversarial suffixes and scoring them.
- **`utils.py`**: Contains utility functions used across the implementation.
- **`advbench_subset.csv`**: A subset of adversarial benchmark prompts used for testing.
- **`LICENSE`**: Licensing information for this repository.

### **Output**
This folder contains csv files with results for each subpart asked in the question.

JSON files are stored in a shared Google Drive folder:
[Google Drive: Output JSON Files](https://drive.google.com/drive/folders/1Igpp3dTSPpMTACdFn4wa9VJ9EWdUUH9Y?usp=share_link)
