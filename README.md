# Weather-Exploratory-Analysis
Python EDA of 2017 NOAA weather data: Mapping seasonal trends and data quality.
Project2_WeatherAnalysis
2017 U.S. Daily Weather Analysis What is this? This is my exploratory data analysis (EDA) project where I investigated over 416,000 weather records from NOAA. I wanted to see if I could find clear seasonal patterns in the numbers and check if the data was actually accurate. I produced 13 different visualizations to uncover the story behind the weather in 2017.

Who made this? Lead Student: Bonolo Ramolapong

Completion Date 12 March 2026

Project Requirements To build this analysis, I used:

Pandas (to handle the 400k+ rows of weather data)

Matplotlib & Seaborn (to turn those numbers into 13 different charts)

Python Datetime (to convert raw text into a format that tracks time)

How to Run My Project Install the tools: pip install pandas seaborn matplotlib

The Data: Make sure the weather.csv.gz file (included in this repo) is in your project folder.

Launch the analysis: Run the provided Python script or Jupyter Notebook.

See the results: The code automatically cleans the dates and generates the visualizations showing everything from temperature "mountains" to correlation heatmaps.

Quick Lessons from the Data The "Mountain" Shape: By converting raw strings into month numbers, I found a perfect seasonal wave that peaks in July.

Catching Errors: I spotted "impossible" temperatures over 200°F using boxplots. This proved that even professional datasets can have sensor glitches!

Western Bias: Most records come from Utah and Montana, so the "national" average is actually weighted heavily toward the American West.

The Heat Link: My heatmap showed a strong 0.8 correlation between daytime highs and nighttime lows, meaning they almost always move together.

Files in this Repository weather.csv.gz: The raw dataset used for the analysis. weather_analysis.ipynb: The Python code/notebook containing the EDA. Weather_Report_Visuals.docx: A document containing all 13 visualizations and detailed captions. README.md: This project summary.

Credits Data provided by NOAA. Big thanks to my lecturer Miss Ishe for the guidance on how to explore and visualize complex datasets!
