# EV Charging Demand Forecasting

This repository contains LSTM-based models for forecasting electric vehicle (EV) charging demand. It includes both a baseline model and an enhanced model that incorporates external features such as weather and traffic data.

## Contents

| File/Folder         | Description |
|---------------------|-------------|
| `Baseline.ipynb`    | Baseline LSTM model using only historical EV load data. |
| `LSTM_WEEKLY.ipynb` | Enhanced LSTM model with additional features (weather, traffic, etc.). |
| `Kaggle_Dataset`   | Folder containing preprocessed dataset and related CSV files. |
| `README.md`         | Project overview and instructions. |

## Model Description

1. **Baseline Model (`Baseline.ipynb`)**  
   Focuses solely on historical EV charging load to make future predictions.

2. **With Features Model (`LSTM_WEEKLY.ipynb`)**  
   Uses engineered features like:
   - Temperature
   - Relative Humidity
   - Traffic volume
   - Holiday flag
   - Week number

These features help improve model accuracy by incorporating behavioural and environmental influences.

## Requirements

- Python 3.x
- TensorFlow
- Pandas, NumPy
- Matplotlib
- scikit-learn



## License
This project is part of a Final Year Dissertation at UNIVERSITI TEKNOLOGI PETRONAS by Muhammad Nazeem Bin Dzahrin (Student ID: 21001994) . For academic reference and educational use only.
