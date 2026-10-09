# D1NAMO Data Analysis

## Overview
Brief description of what you're investigating.

## Dataset: [D1NAMO ECG Glucose Data on Kaggle](https://www.kaggle.com/datasets/sarabhian/d1namo-ecg-glucose-data)
This project uses the D1NAMO dataset, which contains physiological and
health data from diabetic and healthy participants, including ECG,
blood glucose, breathing, accelerometer, and food-related data.

The D1NAMO dataset is divided into diabetic and healthy participant subsets.
Participant directories (`001/`, `002/`, etc.) contain measurements collected
over multiple days.

The dataset includes:

- **ECG data** — Electrocardiogram recordings
- **Accel data** — Accelerometer measurements
- **BB data** — Beat-to-beat physiological measurements
- **Breathing data** — Respiratory measurements
- **RR data** — R-R interval measurements
- **Summary data** — Summarized physiological sensor measurements
- **Glucose data** — Blood glucose measurements
- **Food data** — Information associated with meals
- **Food pictures** — Images corresponding to recorded meals
- **Insulin data** — Insulin records for diabetic participants
- **Annotations** — Additional annotations provided for healthy participants

The raw dataset is not stored in this repository because of its size.
The analysis notebooks access the dataset through the Kaggle environment.

## Dataset Structure
```
d1namo-ecg-glucose-data/
├── diabetes_subset_ecg_data/
│   └── diabetes_subset_ecg_data/
│       ├── 001/
│       │   └── sensor_data/
│       │       ├── 2014_10_01-10_09_39/
│       │       │   └── 2014_10_01-10_09_39_ECG.csv
│       │       └── ...
│       ├── 002/
│       ├── 003/
│       └── ...
│
├── diabetes_subset_pictures-glucose-food-insulin/
│   └── diabetes_subset_pictures-glucose-food-insulin/
│       ├── 001/
│       │   ├── food.csv
│       │   ├── food_pictures/
│       │   │   ├── 001.jpg
│       │   │   └── ...
│       │   ├── glucose.csv
│       │   └── insulin.csv
│       └── ...
│
├── diabetes_subset_sensor_data/
│   └── diabetes_subset_sensor_data/
│       ├── 001/
│       │   └── sensor_data/
│       │       ├── 2014_10_01-10_09_39/
│       │       │   ├── 2014_10_01-10_09_39_Accel.csv
│       │       │   ├── 2014_10_01-10_09_39_BB.csv
│       │       │   ├── 2014_10_01-10_09_39_Breathing.csv
│       │       │   ├── 2014_10_01-10_09_39_RR.csv
│       │       │   └── 2014_10_01-10_09_39_Summary.csv
│       │       └── ...
│       └── ...
│
├── healthy_subset_ecg_data/
│   └── healthy_subset_ecg_data/
│       ├── 001/
│       │   └── sensor_data/
│       │       └── ...
│       └── ...
│
├── healthy_subset_pictures-glucose-food/
│   └── healthy_subset_pictures-glucose-food/
│       ├── 001/
│       │   ├── annotations.csv
│       │   ├── food.csv
│       │   ├── food_pictures/
│       │   └── glucose.csv
│       └── ...
│
└── healthy_subset_sensor_data/
    └── healthy_subset_sensor_data/
        ├── 001/
        │   └── sensor_data/
        │       └── ...
        └── ...
```

## Analysis
Explain what your notebook does:
- Load participant data
- Clean and preprocess sensor readings
- Explore glucose measurements
- Analyze ECG and other sensor features
- Prepare data for machine learning

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Kaggle

## Running the Notebook
Notebook is designed to run in Kaggle environment where the dataset is mounted and can be accessed directly
