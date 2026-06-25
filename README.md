
# 📊 End-to-End Time Series Forecasting System

## 🎯 Objective
Production-ready forecasting system predicting **next 8 weeks of sales** for each US state.

## 🤖 Models Implemented
| Model | Type | Status |
|-------|------|--------|
| **Prophet** | Statistical | ✅ Trained |
| **ARIMA** | Statistical | ✅ Trained |
| **XGBoost** | Machine Learning | ✅ Trained |
| **LSTM** | Deep Learning | ✅ Trained |

## 📈 Best Results
| State | Best Model | RMSE |
|-------|-----------|------|
| Alabama | LSTM | $12,469,972 |
| Arizona | LSTM | $15,142,373 |
| Arkansas | XGBoost | $6,110,281 |
| California | LSTM | $52,718,836 |
| Colorado | XGBoost | $11,164,906 |

## 🚀 API Endpoints
- `GET /predict/{state}?weeks=8` - Get forecast
- `GET /compare/{state}` - Compare all models
- `GET /performance` - View metrics

## 🛠️ Tech Stack
- Python 3.12
- FastAPI, Prophet, ARIMA, XGBoost, LSTM (TensorFlow)
- pandas, numpy, scikit-learn
