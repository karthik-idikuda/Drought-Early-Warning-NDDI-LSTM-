# Drought Early Warning System (NDDI-LSTM)

Climate forecasting model that combines Normalized Difference Drought Index (NDDI) with LSTM networks for early drought prediction from satellite data.

## Features

- NDDI computation from satellite remote sensing data
- LSTM-based temporal drought forecasting
- Multi-step ahead prediction (7, 14, 30 days)
- Spatial drought severity mapping
- Historical drought pattern analysis
- Evaluation with RMSE, MAE, and R-squared metrics

## Tech Stack

Python, TensorFlow, Keras, GDAL, Pandas, Matplotlib

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
git clone https://github.com/karthik-idikuda/Drought-Early-Warning-NDDI-LSTM-.git
cd Drought-Early-Warning-NDDI-LSTM-
pip install -r requirements.txt
```

### Usage

```bash
jupyter notebook Drought_Prediction.ipynb
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
