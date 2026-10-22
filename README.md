❤️ Heart Disease Prediction Dashboard

 1. Project Title
**Heart Disease Prediction Dashboard: Power BI**

2. Short Description
An interactive Power BI dashboard that analyzes 918 patient records to uncover which clinical and demographic factors are most strongly linked to heart disease, helping users spot risk patterns at a glance.

 3. Tech Stack
- **Power BI Desktop**: data modeling and visualization
- **DAX**: calculated measures (average resting BP, average cholesterol)
- **Power Query**: data cleaning (duplicate removal, age grouping)
- **Excel / CSV**: source data format

 4. Data Source
- Heart disease patient dataset , with data cleaning
- 918 patient records, 14 columns
- Fields include age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, ST depression (Oldpeak), ST slope, and the heart disease outcome
- Source:Kaggle "Heart Failure Prediction" dataset]

 5. Features & Highlights
- 55.3% of patients in the dataset have heart disease (508 of 918)
- Disease rate rises sharply with age: **34%** (Young) → **52%** (Mid) → **73%** (Old)
- **63%** of male patients have heart disease vs. **26%** of female patients
- Exercise-induced angina is a strong signal: **85%** disease rate vs. 35% without it
- Asymptomatic chest pain has the highest disease rate at **79%**
- Heart disease patients have a lower average max heart rate (**128 vs. 148 bpm**) and higher ST depression (**1.27 vs. 0.41**)
- Interactive slicers to filter and explore different patient segments

6. Problem Solved
Clinicians and analysts often hold large amounts of patient data but lack a quick way to see **which factors actually signal higher heart disease risk**. This dashboard turns raw records into clear visuals, supporting earlier screening and more informed, data-driven decisions.
