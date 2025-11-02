# Labeling Plan - Senolytic AI: Paper 4

## 1. Definitions
- **Senescent cells**: Cells expressing canonical senescence markers (e.g., p16^INK4a, p21), or showing transcriptional signatures of senescence.
- **Non-senescent cells**: Cells lacking senescence markers and behaving normally in transcriptional and functional assays.

## 2. Inclusion/Exclusion Rules
- **Include:**  
  - Cells with high expression of senescence markers.
  - Cells meeting transcriptional or functional criteria for senescence.
- **Exclude:**  
  - Ambiguous or low-quality cells.
  - Cells undergoing apoptosis or other unrelated stress responses.

## 3. Labeling Format
- Binary labels:  
  - `1` = senescent  
  - `0` = non-senescent
- Optional: confidence score for uncertain cases.

## 4. Annotation Notes
- Marker genes references will be documented when datasets are finalized.
- Labeling may be performed manually, semi-automatically, or fully automated depending on dataset and availability of markers.
