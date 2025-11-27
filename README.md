ml model for detecting fraudulent transactions in mobile banking

description:
lightgbm-based model for real-time fraud detection. developed for fortebank hackathon

model metrics:
- roc-auc: 0.9465
- precision: 0.69
- recall: 0.42
- f1-score: 0.52

files:
- `fraud-detection (1).ipynb` — main notebook with eda, feature engineering and training
- `model_5_antifraud.pkl` — trained model
- `model_5_best_params.pkl` — best hyperparameters
- `model_5_columns.pkl` — feature list for inference
