# Olympic Games Data Analysis Project

## Overview
This project analyzes historical data from the Modern Olympic Games, spanning from Athens 1896 to Rio 2016. The analysis includes various aspects such as medal distributions, athlete demographics, and country-wise performance trends.

## Dataset
The dataset contains information about Olympic athletes and events, including:
- Athlete details (ID, Name, Gender, Age, Height, Weight)
- Team and country information
- Olympic event details (Year, Season, City, Sport, Event)
- Medal information

## Requirements

### Dependencies
```
python
pandas
matplotlib
seaborn
```

### Installation
1. Clone this repository:
```
bash
git clone https://github.com/SafeerAbbas624/Olympic_Games_Data_Analysis_Project.git
```

2. Install required packages:
```
bash
pip install pandas matplotlib seaborn
```

3. Download the required datasets:
- `athlete_events.csv`
- `NOC_Regions.csv`

## Features

### Data Cleaning
- Removal of duplicate entries
- Column renaming ('Sex' to 'Gender')
- Data standardization (M/F to Male/Female)
- Handling missing values in Medal column

### Analysis Components

#### Objective Analysis
1. **Gender-based Medal Analysis**
   - Analysis of medal distribution across genders
   - Visualization using bar plots

2. **Country Performance Analysis**
   - Top 5 countries with most gold medals
   - Visualization using bar plots with gold coloring

3. **Participation Trends**
   - Year-wise analysis of participant numbers
   - Trend analysis for top 20 countries
   - Line plot visualizations

4. **Sport-specific Analysis**
   - Analysis of silver medals in 2014 Olympics
   - Sport-wise medal distribution

5. **Age Distribution Analysis**
   - Medal-wise age distribution analysis
   - Box plot visualizations

#### Subjective Analysis
1. **Age-Medal Relationship**
   - Analysis of age impact on medal winning
   - Statistical distribution and visualization

2. **Country Improvement Trends**
   - Analysis of countries showing significant improvement
   - Year-over-year medal count changes

3. **Seasonal Analysis**
   - Comparison between Summer and Winter Olympics
   - Sport-wise medal distribution analysis

#### Challenge Analysis
1. **Top Athletes by Country**
   - Implementation of list-based filtering
   - Analysis of top performers from specific countries

2. **Age Range Analysis**
   - Analysis of athletes aged 18-30
   - Gold medal performance analysis

3. **Country Data Integration**
   - Merging of athlete data with country information
   - Analysis of athlete heights by country

## Usage
1. Open the Jupyter notebook `Olympic_Games_Assignment.ipynb`
2. Ensure all required datasets are in the same directory
3. Run the cells sequentially to perform the analysis

## Visualizations
The project includes various visualizations:
- Bar plots for medal distributions
- Line plots for temporal trends
- Box plots for age distributions
- Stacked bar charts for seasonal comparisons

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss the proposed change.

## License
Free

## Author
[Safeer Abbas]

## Acknowledgments
- Data source: www.sports-reference.com
- Original dataset compiled in May 2018

