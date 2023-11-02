# CongressPythonVizProject
Overview:
This project visualizes the trend of the average age of Congress members over time. By examining data from various congresses, we're able to uncover a consistent rise in the average age of members, suggesting a shift in the generational representation of our legislators. Enhancing this data with the addition of party names adds ease of analysis of age in relation to party. 

### Prerequisites
Ensure you have the following tools and libraries installed:
- [Python](https://www.python.org/downloads/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

To install the required packages, use the command:
```bash
%pip install pandas matplotlib
```

Data:
The primary dataset, data_aging_congress.csv is sourced from https://github.com/fivethirtyeight/data/tree/master/congress-demographics
This dataset includes details of Congress members along with their respective party codes and ages. This dataset is transformed to generate a visualization showing the age trend of Congress over the years.

Usage
Data Processing: The code reads the dataset, maps party codes to their respective party names, standardizes the capitalization of member names, and then saves the processed data into a new CSV file.

Visualization: The processed data is used to plot the average age of Congress members against their term's start date. This visualization provides a clear insight into the aging trend of Congress over time.

Features:
Party Code Mapping: Unique party codes are mapped to their respective party names for better readability and understanding.
Name Standardization: The 'bioname' column is standardized to ensure consistent name capitalization.
Age Trend Visualization: A plot showcasing the average age of Congress members based on the start date of their terms.

Insights:
The primary insight derived from this project is the consistent rise in the average age of Congress members over the years, hinting at potential implications for legislative focus and representation.

Future Enhancements:
Integrate more demographic data for a multifaceted analysis.
Compare the age trends of Congress with those of the general population.
Extend the project to analyze other aspects of Congress member profiles, such as gender, education, and tenure.

Tableau: 
I utilized the enhanced dataset to create an interactive Tableau dashboard visualizing how age demographics in Congress have changed over time, with insights specific to state, party, chamber, and generational distribution. This dashboard is available for public viewing at https://public.tableau.com/app/profile/megan.es/viz/congreesaging/Dashboard2