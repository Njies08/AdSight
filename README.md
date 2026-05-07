

# AdSight: Predictive Campaign Performance & Brand Safety

MSc Data Analytics and Artificial Intelligence – Project repository.

## Overview
AdSight is a decision-support prototype that:
1) predicts campaign outcomes (CTR/CVR) from impression logs,
2) monitors KPI time series for anomalies,
3) scores brand-safety risk using NLP.

## Data (public)
- Criteo Attribution Modeling for Bidding (performance): https://ailab.criteo.com/criteo-attribution-modeling-bidding-dataset/
- Jigsaw / Civil Comments toxicity (brand safety): 
  - Kaggle: https://www.kaggle.com/competitions/jigsaw-unintended-bias-in-toxicity-classification/data
  - TFDS: https://www.tensorflow.org/datasets/catalog/civil_comments

## Repo structure (planned)
- `notebooks/` – experiments and analysis
- `src/` – reusable code (training, evaluation, utilities)
- `app/` – Streamlit dashboard (optional)
- `docs/` – proposal/report assets

## Notes
Raw datasets will not be committed to the repository.
