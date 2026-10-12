# AZT1D 2025 Dataset

> **Note:** This is the original README provided with the AZT1D 2025 dataset. It is included in this repository for dataset documentation and reference. The dataset and this README were not created as part of this project.

This dataset contains real-world data collected from 25 individuals with Type 1 Diabetes (T1D) using Automated Insulin Delivery (AID) systems.

The folder is organized as follows:

1. **CGM Records**
   - This folder contains 25 subfolders named Subject 1 to Subject 25.
   - Each subject folder contains one CSV file (e.g., `Subject 1.csv`).
   - The CSV file is the main dataset and includes timestamped records such as:
     - Glucose values (CGM/BGM)
     - Insulin delivery (bolus and basal)
     - Carbohydrate intake
     - Device mode (normal, sleep, exercise)

2. **Visual Statistics**
   - This folder also contains 25 subfolders (one per subject).
   - Each folder includes multiple images showing daily and summary visualizations.
   - These include:
     - Daily glucose curves with insulin and food markers
     - Number and duration of hyperglycemia and hypoglycemia events
     - Daily statistics like mean, median, max, and min values

### Notes

- The CSV files are the core data for analysis.
- The image files are generated for visualization purposes only.
- All times are in local time (Arizona).
- Subject IDs are anonymized.

Please cite the related publication if you use this dataset for research.

---

## Source and Citation

**Original Dataset:**  
[AZT1D: A Real-World Dataset for Type 1 Diabetes](https://data.mendeley.com/datasets/gk9m674wcx/1)

**Citation:**  
Khamesian, Saman; Arefeen, Asiful; Thompson, Bithika M.; Grando, Adela; Ghasemzadeh, Hassan (2025), *“AZT1D: A Real-World Dataset for Type 1 Diabetes”*, Mendeley Data, V1, doi: 10.17632/gk9m674wcx.1