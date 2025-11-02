# Baseline Benchmark Plan - Senolytic AI: Paper 4

This plan outlines how classifiers will be evaluated and compared, even before datasets are finalized.

## 1. Data Splits
- Train / Validation / Test sets (e.g., 70% / 15% / 15%)
- Exact splits TBD based on actual datasets.

## 2. Baselines to Run
- Logistic Regression
- Random Forest
- Simple Neural Network
- Purpose: Compare new model performance against standard approaches.

## 3. Metrics for Reporting
- AUROC, AUPR, F1-score, Accuracy
- Optional: runtime, memory usage, model size

## 4. Reporting Format
- Tables showing each model's performance on the test set
- Include metrics and thresholds defined in evaluation_metrics.md

## 5. Optional Notes
- Cross-validation or hyperparameter tuning can be added once datasets are available.
