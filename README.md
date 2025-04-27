# AI-Driven Short and Medium Term Crude Oil & Carbon Black Price Forecasting

## Description

This project aims to predict the **short** and **medium-term prices** of **Crude Oil** and **Carbon Black** using various machine learning and deep learning models. The models employed include:

- **SVR (Support Vector Regression)**
- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Units)**
- **XGBoost**
- **Hybrid Models**:
  - GRU + AdaBoost
  - GRU + XGBoost
  - LSTM + AdaBoost
  - LSTM + XGBoost

### Objective
- Predict the **Crude Oil prices** based on historical price data using the above models.
- Predict **Carbon Black prices** based on historical price data using the same set of models.

## Installation Instructions

Follow these steps to set up the project:

1. **Clone the repository** to your local machine:
   ```bash
   git clone https://github.com/DipeshMPatel/Crude_Oil_and_Carbon_Black_Price_Forecasting.git
   cd Crude_Oil_and_Carbon_Black_Price_Forecasting

2. **Create a virtual environment** (recommended):
   - For **Windows**:
     ```bash
     python -m venv venv
     .\venv\Scripts\Activate
     ```
   - For **macOS/Linux**:
     ```bash
     python -m venv venv
     source venv/bin/activate
     ```

3. **Install dependencies**:
   After the virtual environment is activated, run the following command to install the required dependencies:
   ```bash
   pip install -r requirements.txt

4. The uploaded Jupyter Notebook files can now be executed to rerun the models.
