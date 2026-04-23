# Iris Classification Machine (95.00% Accuracy)

## Project Description
A comprehensive Node.js data science project for classifying the Iris dataset (Extended Version), achieving a precision-level of 95.00%.

## Features
- **Data Pipeline:** Automated download and preprocessing from CSV.
- **Split:** 80% Training (160 samples), 20% Testing (40 samples).
- **Evolutionary Learning:** The model progressed from 87.50% to 90.00%, reaching 95.00% using a Neural Network (Synaptic MLP).
- **Predictor:** A standalone CLI tool for real-time classification.

## Installation
```bash
npm install
```

## Usage
### Run EDA:
```bash
node src/index.js
```
### Run Final Machine:
```bash
node src/classify_machine.js 5.1 3.5 1.4 0.2
```

## File Structure
- `data/`: Raw and split dataset files.
- `src/`: Core classification logic and EDA.
- `final_report.html`: Comprehensive process report.
- `iris_final.csv`: Exported final dataset.
- `PRD.md`: Detailed requirements and goals.
