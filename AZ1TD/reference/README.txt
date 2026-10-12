README - AZT1D 2025 Dataset

This dataset contains real-world data collected from 25 individuals with Type 1 Diabetes (T1D) using Automated Insulin Delivery (AID) systems.

The folder is organized as follows:

1. CGM Records
   - This folder contains 25 subfolders named Subject 1 to Subject 25.
   - Each subject folder contains one CSV file (e.g., Subject 1.csv).
   - The CSV file is the main dataset and includes timestamped records such as:
     - Glucose values (CGM/BGM)
     - Insulin delivery (bolus and basal)
     - Carbohydrate intake
     - Device mode (normal, sleep, exercise)

2. Visual Statistics
   - This folder also contains 25 subfolders (one per subject).
   - Each folder includes multiple images showing daily and summary visualizations.
   - These include:
     - Daily glucose curves with insulin and food markers
     - Number and duration of hyperglycemia and hypoglycemia events
     - Daily statistics like mean, median, max, min values

Notes:
- The CSV files are the core data for analysis.
- The image files are generated for visualization purposes only.
- All times are in local time (Arizona).
- Subject IDs are anonymized.


Please cite the related publication if you use this dataset for research.