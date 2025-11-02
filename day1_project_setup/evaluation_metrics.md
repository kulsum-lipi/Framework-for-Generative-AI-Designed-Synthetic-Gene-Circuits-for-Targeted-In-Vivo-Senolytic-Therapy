
# Evaluation Metrics & Acceptance Thresholds - Senolytic AI: Paper 4

## 1. Classifier Performance Metrics
| Metric | Description | Notes / Threshold |
|--------|------------|-----------------|
| AUROC | Area Under ROC Curve | High AUROC indicates better separation of senescent vs non-senescent cells; target ≥ 0.85 |
| AUPR | Area Under Precision-Recall Curve | Focus on positive class (senescent); target ≥ 0.80 |
| Accuracy | Fraction of correct predictions | Optional; less useful for imbalanced datasets |
| F1-score | Harmonic mean of precision & recall | Good balance of false positives and negatives |

## 2. Circuit Performance / Safety Metrics
| Metric | Description | Notes / Threshold |
|--------|------------|-----------------|
| Leakiness | Unintended circuit activation | Keep as low as possible, e.g., < 5% of max output |
| Burden | Cellular resource usage of the circuit | Estimated using BioCRNpyler ribosomal load models |
| Off-target activity | Unintended gene expression | Predicted with DeepBind, Enformer, Basenji |
| Simulation success rate | % of circuits that run without errors | Target ≥ 90% |
