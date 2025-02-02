# TOPSIS for Text Generation Models Ranking

This repository implements the **TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution)** method to evaluate and rank pre-trained text generation models based on multiple criteria. The models are evaluated based on **Performance (BLEU Score)**, **Speed (Response Time)**, and **Memory Consumption**.

## Overview

This project ranks different pre-trained models for text generation based on a set of criteria using the TOPSIS method. It normalizes the data, calculates the weighted decision matrix, computes the ideal and negative ideal solutions, and ranks the models according to their relative closeness to the ideal solution. It then visualizes the results using bar charts, radar charts, and scatter plots.

### Key Features:
- **TOPSIS Methodology**: Used to rank models based on multiple criteria.
- **Multiple Visualizations**: Includes bar charts, radar charts, and scatter plots to visualize the ranking and model comparison.
- **Flexible**: Easily adaptable to different models and criteria for ranking.

## Requirements

To run the code, ensure you have the following libraries installed:

- `numpy`
- `pandas`
- `matplotlib`

<img src="https://github.com/spookynavz/Topsis-for-Pretrained-Model/blob/main/Screenshot%202025-02-02%20212201.png" alt="Sample Image" />

<img src="https://github.com/spookynavz/Topsis-for-Pretrained-Model/blob/main/Screenshot%202025-02-02%20212220.png" alt="Sample Image" />
