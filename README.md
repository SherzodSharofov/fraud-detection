ml model for detecting fraudulent transactions in mobile banking

description:
lightgbm-based model for real-time fraud detection. developed for fortebank hackathon

model metrics:
- roc-auc: ~0.85
- recall (threshold 0.3): 0.36
- precision (threshold 0.3): 0.39

files:
- `fraud-detection (1).ipynb` — main notebook with eda, feature engineering and training
- `model_5_antifraud.pkl` — trained model
- `model_5_best_params.pkl` — best hyperparameters
- `model_5_columns.pkl` — feature list for inference
