# TfL Bus Lanes Analysis

## Description
This notebook (`tflbuslanes.ipynb`) analyzes Transport for London (TfL) bus lanes data. It loads a CSV file (`Bus_Lanescleaned.csv`) and performs data exploration and visualization. The analysis covers:
- Operational status of bus lanes
- Vehicles allowed (bus, cycle, motorcycle, taxi)
- Lane lengths and directions
- Borough-wise distribution
  # Dataset  - <a href="https://gis-tfl.opendata.arcgis.com/datasets/0b276a1705ff43a9917c7b1fceb65c01_0/explore"> </a>
# Data Cleaning (Excel)

The initial cleaning process involved:

Removing duplicates and irrelevant columns

Standardizing date and time formats

Correcting data inconsistencies (e.g., road names, boroughs)

Ensuring consistent units for lane lengths
 

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
  ### Visual Preview
![Visual 1](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_1.png)
 ##Analysis Insights
Top 10 Boroughs with the Most Bus Lanes 🚏
The borough with the highest number of bus lanes is Transport for London, followed by major boroughs like Westminster, Camden, and Lambeth.
This suggests high bus lane density in central London areas.
![Visual 2](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_2.png)
This show distribution of bus lane lengths.
![Visual 3](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_3.png)
Most common operational hours.
![Visual 4](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_4.png)
Top 10 road with high bus lanes.
![Visual 5](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_5.png)
Vehicles allowed in bus lanes.
![Visual 6](https://raw.githubusercontent.com/Jaswinder-spec/TFL-Bus-Lanes-Project/main/visual_6.png)
Distribution of bus lanes by borough with lane types.

## License
This project uses data from Transport for London and is intended for educational and analytical purposes.



