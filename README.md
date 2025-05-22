# 📈 Multi-Stage Feature-Enhanced LSTM-XGBoost for Alpha Generation

This repo contains code and research for a hybrid deep learning + boosting model with sentiment-aware trading strategy for Indian equities.

### 🧠 Components
- LSTM + GRU temporal modeling
- XGBoost, LightGBM, CatBoost base regressors
- FinBERT-based sentiment fusion
- Ridge/GBR meta-learner stacking
- Backtesting module with Sharpe Ratio

### 📊 Results (on RELIANCE.NS)
- RMSE: 0.0182
- Sharpe Ratio: 1.86
- Directional Accuracy: 72.4%

### 📁 Folder Overview
- `model_pipeline.ipynb`: full model + training
- `finbert_sentiment.py`: sentiment scorer
- `backtest_strategy.py`: backtest logic
