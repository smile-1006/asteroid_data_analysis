# Asteroid Classification Project

This project analyzes and classifies asteroid data from NASA JPL for the Planet Hunt Hackathon organized by IIT BHU.

## Project Overview

The project performs comprehensive analysis of asteroid data including:
- Feature analysis and visualization
- Class imbalance handling
- Machine learning-based classification
- Performance evaluation and visualization

## Setup Instructions

1. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Place your asteroid dataset in the project directory as 'asteroid_data.csv'

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open `asteroid_classification.ipynb` and run all cells

## Project Structure

- `asteroid_classification.ipynb`: Main Jupyter notebook containing the analysis
- `requirements.txt`: List of Python dependencies
- Generated plots will be saved as PNG files in the project directory

## Features Analyzed

- Absolute magnitude (H)
- Diameter
- Albedo
- Orbital parameters
- Classification flags (NEO, PHA, Non-hazardous)

## Output

The notebook generates several visualizations:
- Feature distributions
- Correlation heatmap
- Class distribution plots
- Confusion matrix
- Feature importance plot

All plots are automatically saved as PNG files for use in the final report. 