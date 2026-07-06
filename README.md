# Lung Cancer Detection
A hybrid XGBoost + CNN fusion model trained on LIDC-IDRI dataset.

## Architecture
- XGBoost branch: radiomic features
- CNN branch: ResNet18 on nodule patches  
- Fusion layer: weighted average

## Dataset
LIDC-IDRI — 1,018 CT scans with per-nodule malignancy scores.
