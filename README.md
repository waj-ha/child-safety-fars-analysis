# Analysis of Child Seat Safety in Road Accidents Using Data Analytics

## Project Overview

This project analyzes child safety in road traffic accidents using the Fatality Analysis Reporting System (FARS) dataset. The objective is to identify factors associated with child fatalities and evaluate the effectiveness of child restraint systems.

## Business Problem

Road accidents remain one of the leading causes of injury and death among children. Understanding the factors that contribute to severe outcomes can help improve safety regulations and public awareness.

## Objectives

- Analyze child fatalities in traffic accidents.
- Evaluate the effectiveness of child restraint systems.
- Identify high-risk age groups.
- Study the influence of vehicle type, seating position, and crash conditions.
- Provide data-driven recommendations for improving child safety.

## Dataset

Source:
- FARS (Fatality Analysis Reporting System) 2024

Files Used:
- accident.csv
- vehicle.csv
- person.csv

## Data Preparation

Steps performed:

1. Data Cleaning
   - Removed invalid and unknown values.
   - Handled missing data.
   - Standardized column formats.

2. Data Integration
   - Merged Accident, Vehicle, and Person datasets.
   - Established relationships using primary keys.

3. Feature Engineering
   - Child age categories.
   - Restraint usage classification.
   - Vehicle categories.

## Methodology

### Exploratory Data Analysis (EDA)

- Age distribution analysis
- Gender analysis
- Restraint usage analysis
- Vehicle type analysis
- Temporal trends

### Statistical Analysis

- Fatality rates by age group
- Comparison of restrained vs unrestrained children
- Impact of crash characteristics

### Visualization

- Bar Charts
- Histograms
- Heat Maps
- Stacked Bar Charts
- Geographic Visualizations

## Key Findings

- Children without proper restraints showed significantly higher fatality rates.
- Certain age groups are more vulnerable during crashes.
- Passenger vehicles account for the majority of incidents involving children.
- Nighttime crashes show increased fatality risk.

## Recommendations

- Increase awareness of child restraint systems.
- Strengthen enforcement of child safety regulations.
- Improve public education on proper child seat installation.
- Target high-risk demographics through safety campaigns.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Project Structure

```
project/
│
├── data/
│   ├── accident.csv
│   ├── vehicle.csv
│   └── person.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── outputs/
│   ├── figures/
│   └── reports/
│
├── README.md
└── requirements.txt
```

## How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run the notebook

```bash
jupyter notebook
```

## Future Work

- Predictive modeling of child fatality risk.
- Interactive dashboard development.
- Geographic hotspot analysis.
- Comparison with previous FARS years.

## Author

Wajahat Hanif

Data Analytics Project – ReDI School
