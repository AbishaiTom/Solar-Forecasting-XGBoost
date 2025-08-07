# Dataset for "Adaptive Solar Forecasting: A Data-Driven Exploration of Model Generalizability Across Diverse US Climates"

## 📄 Overview

This repository contains the curated datasets used for the research paper titled, **"Adaptive Solar Forecasting: A Data-Driven Exploration of Model Generalizability Across Diverse US Climates"**.

The core objective of this research was to develop and validate a single, adaptive machine learning model capable of accurately forecasting solar photovoltaic (PV) power output across multiple, distinct climatic zones. This dataset was instrumental in training and evaluating the model's ability to generalize its predictions, a significant challenge in the field of renewable energy forecasting.

We are making this data openly available to the research community to facilitate reproducibility and encourage further innovation in solar forecasting.

---

## 📂 Dataset Description

The repository contains three primary CSV files, each corresponding to a distinct and climatically diverse location within the United States. Each file includes a comprehensive time-series of meteorological data, PV system metadata, and the corresponding measured AC power output.

### Locations and Climates

The data covers full annual cycles for the following sites to ensure seasonal patterns are well-represented:

1.  **`final_cocoa.csv`**:
    * **Location:** Cocoa Beach, Florida
    * **Climate Type:** Humid Subtropical / Coastal

2.  **`final_henderson.csv`**:
    * **Location:** Henderson, Nevada
    * **Climate Type:** Hot Desert

3.  **`final_golden_dataset.csv`**:
    * **Location:** Golden, Colorado
    * **Climate Type:** High-Altitude / Semi-Arid

### Data Columns (Key Features)

Each file contains the following key columns:

* `timestamp`: The date and time of the observation.
* `GHI`: Global Horizontal Irradiance (W/m²).
* `DNI`: Direct Normal Irradiance (W/m²).
* `DHI`: Diffuse Horizontal Irradiance (W/m²).
* `Temperature`: Ambient air temperature (°C).
* `Wind Speed`: Wind speed (m/s).
* `ac_power`: The measured AC power output from the PV system (this was the primary target for forecasting).
* `dc_capacity_kW`: The nominal DC capacity of the solar plant (kW).
* `tilt`: The tilt angle of the PV panels (degrees).
* `azimuth`: The azimuth angle of the PV panels (degrees).
* ... and other relevant meteorological data from the NSRDB.

---

##  Citing This Dataset

If you use this dataset in your research, please cite our original paper:

> A. Tom, J. S., & N. John. (Year). "Adaptive Solar Forecasting: A Data-Driven Exploration of Model Generalizability Across Diverse US Climates." *Conference/Journal Name*.

## 📧 Contact

For any questions regarding this dataset, please contact **Abishai Tom** at `abishaitom2002@gmail.com`.
