# NASA_SPACEAPPS_2024
NASA SPACE APPS CHALLENGE 2024
Gender Inequality Analysis
Overview
This project presents a comprehensive analysis of gender inequality across various countries, utilizing the Gender Inequality Index (GII) and associated gender statistics. The data is organized in a 7z compressed file format to facilitate easy download and extraction. Users are encouraged to extract the contents using compatible software such as 7-Zip or other archive management tools.

Table of Contents
Project Description
Getting Started
File Structure
Data Sources
Methodology
Code Structure
Visualizations
Key Findings
Contributing
License
Project Description
Gender inequality remains a pressing global issue, affecting economic growth, social development, and overall well-being. This project aims to analyze gender inequality through the Gender Inequality Index (GII) and relevant gender statistics, highlighting disparities across countries. By examining various metrics, the analysis sheds light on the implications of gender inequality on societal health and progress.

Getting Started
Download the Project: The project files are provided in a 7z compressed format. Use appropriate software to extract the contents of the archive.

Install Required Libraries: The project requires Python and several libraries for data manipulation and visualization. Use the following command to install the necessary libraries:

bash
Copy code
pip install pandas matplotlib seaborn
Run the Analysis: Once the required libraries are installed and the files are extracted, you can run the Python script (e.g., gender_inequality_analysis.py) to execute the analysis.

File Structure
mathematica
Copy code
/Gender-Inequality-Analysis
│
├── GII_data.xlsx
├── Gender_StatsCSV.csv
├── Gender_Statscountry-series.csv
├── gender_inequality_analysis.py
├── cleaned_gender_analysis.csv
└── README.md
GII_data.xlsx: Contains the Gender Inequality Index data.
Gender_StatsCSV.csv: Provides gender-related statistics from various countries.
Gender_Statscountry-series.csv: Contains additional series data related to gender stats.
gender_inequality_analysis.py: The main Python script that conducts the analysis.
cleaned_gender_analysis.csv: The cleaned and processed data file for future reference.
README.md: This documentation file.
Data Sources
GII Dataset: The Gender Inequality Index data was sourced from reputable organizations, such as the United Nations Development Programme (UNDP).
Gender Statistics: Additional gender statistics were obtained from the World Bank and other relevant sources.
Methodology
Data Cleaning: The initial datasets were inspected to identify inconsistencies. Necessary preprocessing steps included renaming columns, removing unnecessary data, and handling missing values.

Merging Datasets: Multiple data sources were merged to create a comprehensive view of gender inequality across various countries.

Data Visualization: Various visualizations were created to highlight key patterns in the data. This includes scatter plots, box plots, histograms, and correlation heatmaps.

Final Analysis: Conclusions were drawn from the analysis to inform actionable insights regarding gender inequality.

Code Structure
The code is organized into several key sections:

Importing Libraries: Necessary libraries like pandas, matplotlib, and seaborn are imported for data manipulation and visualization.

Loading Data: The GII dataset and gender statistics are loaded into data frames for analysis.

Data Preprocessing: This section includes cleaning and preparing the data for analysis.

Data Visualization: Various visualizations are created to illustrate findings, including scatter plots, box plots, and heatmaps.

Final Data Export: The cleaned data is exported as a CSV file for further analysis or reporting.

Visualizations
The project includes several insightful visualizations that highlight the relationship between gender inequality and related statistics:

Scatter Plot: Shows the relationship between GII and gender statistics for 2022.

Box Plot: Illustrates the distribution of GII scores among different countries.

Histograms: Display the distribution of Female GII and Male GII.

Correlation Heatmap: Provides a visual representation of the correlations between various metrics.

Key Findings
There exists a clear negative correlation between GII and gender statistics, suggesting that higher GII scores correlate with lower gender equality.
Significant disparities are present between countries, with notable outliers representing extreme cases of gender inequality.
Trends indicate both progress and setbacks in gender equality over the years.
