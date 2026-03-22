**Python EDA of 2017 NOAA Weather Data: Mapping Seasonal Trends and Data Quality**

**What is this?**
An exploratory data analysis of 416,000+ NOAA weather records from 2017, investigating seasonal temperature patterns, precipitation trends, and data quality issues across U.S. weather stations. The project produced 17 visualizations.

**Who made this?**
Bonolo Ramolapong
completed 22 March 2026

**Tools Used**
Pandas, Matplotlib, Seaborn, Python Datetime

**How to Run**
1. Install: pip install pandas seaborn matplotlib
2. Add weather.csv.gz to your project folder
3. Run weather_analysis.ipynb

**Key Findings**
- Temperatures follow a clear seasonal wave, peaking in July
- A single faulty sensor in Alaska was responsible for all impossible temperature readings (261.68°F)
- Western states dominate the dataset, making the national average cooler than reality
- Daytime and nighttime temperatures are strongly correlated (0.8)
- Summer has the largest daily temperature swings (~23°F), winter the smallest (~18°F)

**Files**
- weather.csv.gz — raw dataset
- weather_analysis.ipynb — full analysis notebook
- Weather_Report_Visuals.docx — all 17 visualizations and captions
- README.md — this file

**Credits**
Data: NOAA. Thanks to Miss Ishe for guidance throughout the project.
