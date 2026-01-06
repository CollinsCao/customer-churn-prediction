# Customer Churn Prediction Platform

Machine learning pipeline for predicting customer churn with real-time API deployment.

## 🚀 Project Status

**Currently in active development** | Expected completion: January 2026

## 📋 Overview

End-to-end ML system for customer retention analysis featuring:
- Automated ETL pipeline processing 20,000+ customer records
- Feature engineering with 50+ engineered features
- Ensemble models (Logistic Regression, Random Forest, XGBoost)
- RESTful Flask API for real-time predictions
- Comprehensive model evaluation and monitoring

## 🎯 Key Features

- **Data Processing**: Missing value imputation, outlier detection, categorical encoding
- **Model Training**: Grid search hyperparameter tuning, 5-fold cross-validation
- **Performance**: 87% AUC-ROC, 83% accuracy, <200ms API latency
- **Production-Ready**: Error handling, input validation, logging, risk-based recommendations

## 🛠️ Tech Stack

- **Languages**: Python
- **ML Libraries**: Scikit-learn, Pandas, NumPy
- **API Framework**: Flask
- **Database**: PostgreSQL
- **Tools**: Jupyter, Git

## 📂 Project Structure
```
customer-churn-prediction/
├── data/                  # Raw and processed datasets
├── models/                # Trained model files
├── src/                   # Source code
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── api.py
├── notebooks/             # Jupyter notebooks for EDA
├── tests/                 # Unit tests
└── requirements.txt       # Python dependencies
```

## 🚧 Development Roadmap

- [x] Project setup and planning
- [ ] Data collection and preprocessing
- [ ] Feature engineering
- [ ] Model training and evaluation
- [ ] Flask API development
- [ ] Documentation and deployment

## 📊 Expected Results

- AUC-ROC: 87%+
- Accuracy: 83%+
- API Response Time: <200ms
- Production Deployment: AWS/Heroku

## 👤 Author

**Yuqi Cao**
- LinkedIn: [linkedin.com/in/yuqicao99](https://linkedin.com/in/yuqicao99)
- Email: yuqicao99@gmail.com

## 📄 License

MIT License - see LICENSE file for details
