# Apple Stock Price Prediction with SARIMA Model

**Author:** Akritichhaya  
**Project Link (Deployed App):** [Apple Stock Prediction App](YOUR_STREAMLIT_APP_LINK_HERE)

---

## Project Overview
This project is designed to **predict future stock prices of Apple Inc.** using a **SARIMA (Seasonal AutoRegressive Integrated Moving Average) model**.  
It captures both trend and seasonality in historical stock data, providing accurate forecasts of future closing prices.

The app is deployed using **Streamlit**, allowing users to interactively upload data, visualize predictions, and explore forecast results.

---

## Features
- Forecast Apple stock prices for future dates.  
- Capture seasonal trends using the SARIMA model.  
- Interactive visualizations with Streamlit.  
- Uses pre-trained model and scalers for consistent predictions.  

---

## Repository Structure

| File | Description |
|------|-------------|
| `Apple_stock_prediction.ipynb` | Jupyter Notebook with EDA, model training, and evaluation. |
| `P587 DATASET.csv` | Historical Apple stock dataset. |
| `app.py` | Streamlit app for real-time forecasting. |
| `best_model.pkl` | Trained SARIMA model saved for deployment. |
| `scaler_X_sarimax.pkl` | Scaler for input features. |
| `scaler_y.pkl` | Scaler for target variable. |
| `requirements.txt` | Python dependencies for running the app. |
| `runtime.txt` | Specifies Python version for Streamlit Cloud. |
| `postBuild` | Optional script to cleanly reinstall dependencies on Streamlit Cloud. |

---

## Setup Instructions

1. **Clone the repository**
```bash
git clone <repository_url>
cd <repository_folder>
