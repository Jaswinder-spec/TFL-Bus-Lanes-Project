# TfL Bus Lanes Analysis

## Description
This notebook (`tflbuslanes.ipynb`) analyzes Transport for London (TfL) bus lanes data. It loads a CSV file (`Bus_Lanescleaned.csv`) and performs data exploration and visualization. The analysis covers:
- Operational status of bus lanes
- Vehicles allowed (bus, cycle, motorcycle, taxi)
- Lane lengths and directions
- Borough-wise distribution
# Data Cleaning (Excel)

The initial cleaning process involved:

Removing duplicates and irrelevant columns

Standardizing date and time formats

Correcting data inconsistencies (e.g., road names, boroughs)

Ensuring consistent units for lane lengths
  ##Analysis Insights
Top 10 Boroughs with the Most Bus Lanes 🚏
  
The borough with the highest number of bus lanes is Transport for London, followed by major boroughs like Westminster, Camden, and Lambeth.


This suggests high bus lane density in central London areas.

Distribution of Bus Lane Lengths 📏

Most bus lanes are relatively short, with many under 500 meters.

A few lanes extend beyond 1,000 meters, but they are less common.

Most Common Operational Hours ⏳

Many bus lanes operate 24/7 (00:00-23:59).

Some have restricted hours, primarily during peak times.

## Dependencies
To run this notebook, you need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install the dependencies by running:
```bash
pip install pandas matplotlib seaborn
```

## How to Run
1. Open the notebook in Jupyter or any compatible IDE.
2. Ensure the CSV file (`Bus_Lanescleaned.csv`) is in the same directory or update the file path accordingly.
3. Run the cells sequentially.

## Output
The notebook generates various visualizations, including:
- Distribution of bus lane lengths
- Bus lane operations by borough
- Vehicle types allowed in different lanes
  Visuals
  ![Salary Dashboard](https://raw.githubusercontent.com/Jaswinder-spec/salary_dataset/refs/heads/main/Screenshot%202025-03-20%20174756.png)
   (https://github.com/Jaswinder-spec/TFL-Bus-Lanes-Project/blob/main/visual_1.png)

## License
This project uses data from Transport for London and is intended for educational and analytical purposes.



