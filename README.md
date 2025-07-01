# Aviation_Project
**README.md**

# Aviation Risk Analysis Project

## Overview

This project analyzes historical aviation accident data to help a company expand safely into the aviation industry. The goal is to identify **which aircraft types present the lowest risk** for commercial and private operations, providing actionable insights for the company's new aviation division[1].

## Business Problem

The company is diversifying its portfolio by entering the aviation sector. However, it lacks expertise regarding the risks associated with different aircraft. The core business question is:  
**Which aircraft are the lowest risk for purchase and operation, based on historical accident and incident data?**[1]

## Objectives

- **Analyze** a comprehensive aviation accident dataset (88,889 records, 31 columns) for patterns and risk factors.
- **Clean and prepare** the data, standardizing column names and removing irrelevant or incomplete fields.
- **Identify** aircraft makes and models with the lowest rates of severe incidents and injuries.
- **Provide recommendations** to guide the company in selecting safer aircraft for acquisition[1].

## Data

- **Source:** AviationData.csv
- **Size:** 88,889 rows × 31 columns
- **Key Features:**  
  - Event details (date, location, investigation type)  
  - Aircraft characteristics (make, model, engines, category)  
  - Injury and damage severity  
  - Weather and flight phase information[1]

## Data Preparation

- **Standardized column names** (lowercase, underscores, removed periods).
- **Dropped irrelevant columns** (IDs, coordinates, registration numbers, etc.).
- **Handled missing values:**  
  - Many columns contain nulls; non-essential or sparse columns were removed.
  - Focused on fields critical for risk assessment (injury severity, aircraft type, etc.).
- **Final dataset:** 18 columns retained for analysis[1].

## Analysis Approach

- **Exploratory Data Analysis (EDA):**  
  - Assessed distributions, missing values, and unique entries.
  - Summarized injury counts, accident types, and aircraft models.
- **Risk Evaluation:**  
  - Compared aircraft types by frequency and severity of incidents.
  - Analyzed contextual factors (weather, flight phase, etc.).
- **Visualization:**  
  - Used Python (pandas, seaborn, matplotlib) for data exploration and plotting[1].
 
  1. Frequency of injury_severity
       
![image](https://github.com/user-attachments/assets/9ab49a4a-3a27-498a-a928-b9b7f95899ca)

  2. Number of Injuries vs Weather Conditions

![image](https://github.com/user-attachments/assets/04b70083-0f26-43dd-b70b-158ee1ce1c29)

3. How weather,make and flight-phase affect injuries
   ![image](https://github.com/user-attachments/assets/191b40e8-738c-492b-9134-7c03502abcf5)


## Results & Recommendations

- Identified aircraft makes/models with the **lowest rates of fatal and serious injuries**.
- Highlighted operational and environmental factors contributing to risk.
- Provided **actionable recommendations** for aircraft selection and risk mitigation.

## How to Run

1. Clone the repository.
2. Install dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Place `AviationData.csv` in the working directory.
4. Run the analysis notebook or script.

## Author

- **Fridah Mumbi Njung'e**
- Instructor: Mr. William Okomba
- Student Pace: Full time-Remote

## License

This project is for academic and demonstration purposes.

*For more details, see the full analysis notebook in this repository.*[1]

[1]: Notebook.pdf

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/33520540/304cc21e-c2a6-436c-aa1b-db7109769960/Notebook.pdf
