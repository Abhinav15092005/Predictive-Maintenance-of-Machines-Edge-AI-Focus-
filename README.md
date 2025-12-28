# 🛠️ Machine Predictive Maintenance Classification

A web-based machine learning application that predicts machine failures using a trained Random Forest classifier. Built with Streamlit and scikit-learn.

## 📁 Dataset
- **File:** `predictive_maintenance.csv`
- **Features Used:**
  - `Type` (Low/Medium/High → Encoded as 0,1,2)
  - `Air temperature [K]`
  - `Process temperature [K]`
  - `Rotational speed [rpm]`
  - `Torque [Nm]`
  - `Tool wear [min]`
- **Target:** Binary classification (Failure/No Failure)

## 🚀 Features
- Interactive web interface built with Streamlit
- Real-time failure prediction
- User-friendly input form with dropdown and text inputs
- Instant classification results

## 🛠️ Tech Stack
- **Python 3.11+**
- **Streamlit** - Web interface
- **scikit-learn** - Machine learning model
- **joblib** - Model serialization
- **Random Forest Classifier** - Prediction algorithm

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/predictive-maintenance-ML.git
   cd predictive-maintenance-ML
