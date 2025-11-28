# CPE342-KAGGLE

Kaggle competition workspace for the CPE342 Karena series, part of CPE342 Machine Learning (1/2025) at Computer Engineering, KMUTT. These notebooks produced the final submissions (1st place on both public and private leaderboards).

- Competition: https://www.kaggle.com/competitions/cpe342-karena

## Repository layout
- `Task1/code.ipynb` — Anti-cheat binary classification with F2-focused stacking and threshold tuning.
- `Task2/code.ipynb` — Player segment multiclass classification optimized for macro F1 (stacked models).
- `Task3/code.ipynb` — Monthly spending regression optimized for MAE with ensemble stacking.
- `Task4/code.ipynb` — Five-class image classifier using a combined CSV (id, file_name, label) and stratified train/validation split; trains on images in `combined/` and infers on `test/`.
- `Task5/code.ipynb` — Unsupervised anomaly scoring on tabular test data using a PCA-based detector (median imputation, scaling, PyOD PCA with contamination/thresholding) producing per-id scores and flags.
