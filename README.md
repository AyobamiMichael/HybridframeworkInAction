# A Hybrid Framework for Predicting Global Temperature Anomalies Using Machine Learning and Deep Learning

## Overview
This repository contains a Jupyter Notebook implementing a hybrid framework for predicting global temperature anomalies. The framework leverages machine learning and deep learning models to analyze historical climate data from various sources.

## Data Sources
The following datasets are used for analysis:
- **Extended Reconstructed Sea Surface Temperature (ERSST)**
- **Global Historical Climatology Network monthly (GHCNm)**
- **International Comprehensive Ocean-Atmosphere Data Set (ICOADS)**
- **International Arctic Buoy Programme (IABP)**

### Spatial Coverage
The dataset provides **global 5° × 5° spatial resolution**.

## Dependencies
To run the notebook, install the required Python libraries:
```bash
pip install xarray netCDF4 tensorly
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hybrid-framework-temperature.git
   cd hybrid-framework-temperature
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook hybridframework1.ipynb
   ```
3. Execute the cells in order to preprocess the data, train models, and analyze predictions.

## Features
- Uses **xarray** for handling climate datasets.
- Implements **machine learning and deep learning models** for prediction.
- Supports **tensor decomposition** techniques for feature extraction.

## License
This project is open-source and available under the MIT License.

## Author
[Ayobami Opefeyijimi] - [ayobamiwealth@gmail.com]

