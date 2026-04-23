# Product Requirements Document (PRD): Iris Classification Project

## 1. Project Goal
Develop an end-to-end classification system for the botanical Iris dataset, including a custom "No-Iris" noise class.

## 2. Key Requirements
- **Data Integration:** Combine original 150 Iris observations with 50 synthetic "No-Iris" data points.
- **Preprocessing:** Normalize features (4 numeric inputs) for model stability.
- **Evaluation:** Split data (80/20) and measure accuracy with a 4x4 Confusion Matrix.
- **Learning Visualization:** Plot error reduction (convergence) and internal weight ($W$) adaptations.
- **Final Product:** A standalone Node.js "Machine" for real-time predictions.

## 3. Success Criteria & Iterative Accuracy
The machine achieved its target through three distinct phases:
- **Baseline (KNN/Decision Tree):** 87.50%
- **Optimization (Normalized k=5):** 90.00%
- **Final Result (Neural Network):** **95.00%**
- **Validation:** 4x4 Confusion Matrix (Correct: 38/40, Errors: 2)

