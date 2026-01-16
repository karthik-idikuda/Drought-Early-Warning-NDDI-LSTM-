# Drought Early Warning System (NDDI-LSTM) - Main

## Overview
A predictive analytics model designed to forecast drought conditions using the Normalized Difference Drought Index (NDDI) and Long Short-Term Memory (LSTM) networks. This tool aids agricultural planning by predicting water stress levels well in advance.

## Features
-   **Time-Series Forecasting**: LSTM models trained on historical climate data.
-   **Index Calculation**: Automatic computation of NDDI from NDVI and NDWI.
-   **Regional Analysis**: Focused predictions for specific agricultural zones.
-   **Visualization**: Trend graphs showing drought severity over time.

## Technology Stack
-   **Deep Learning**: TensorFlow / Keras (LSTM).
-   **Data Storage**: NetCDF / CSV.
-   **Analysis**: NumPy, Pandas, Scikit-learn.

## Usage Flow
1.  **Input**: Upload historical rainfall and satellite index data.
2.  **Train**: Model learns temporal patterns and seasonality.
3.  **Forecast**: System predicts NDDI values for the next 3-6 months.
4.  **Report**: Visual dashboard highlights regions at risk.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/Drought-Early-Warning.git

# Install requirements
pip install -r requirements.txt

# Train the model
python train_model.py
```

## License
MIT License

## Author
**Karthik Idikuda**