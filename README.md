# Enhancing Public Safety in Philadelphia with Data Science

## Introduction

This project aims to enhance public safety in Philadelphia, Pennsylvania, by predicting the type of crimes that occur in different zip codes. The project consists of three main parts:
1. Data acquisition and cleaning 
2. Exploratory data analysis
3. Machine learning modeling.

## Data Acquisition and Cleaning
We collected data on population and poverty from the US Census Bureau and crime data from OpenDataPhilly. We also used the Google Maps API to map longitude and latitude to zip codes. The population and poverty data were cleaned by removing irrelevant columns and handling missing values. The crime data was cleaned by removing unnecessary columns, converting dates and times into the appropriate format, and mapping longitude and latitude to zip codes.

## Exploratory Data Analysis
In the exploratory data analysis, we examined the relationships between crime, population, and poverty. We created various visualizations, including Pie chart, trend graphs, and bar charts, to better understand the data. We also used Folium to create an interactive map of Philadelphia that displays crime rates in different zip codes.

## Machine Learning Modeling
In the machine learning modeling, we merged all the cleaned datasets and performed multiclass classification using Logistic Regression and Random Forest algorithms. We split the data into training and testing sets and evaluated the performance of each algorithm using accuracy, precision, recall, and F1-score metrics.

## Libraries used

The following libraries were used in this project:

**Scikit-learn** for machine learning modeling

**Folium** for visualization on maps

**Pandas** for data manipulation

**NumPy** for numerical computing

**Seaborn and Matplotlib** for data visualization

## Data Sources

The following data sources were used in this project:

US Census Bureau: https://www.census.gov/quickfacts/philadelphiacountypennsylvania

OpenDataPhilly: https://www.opendataphilly.org/

## Running the code

To run the code, follow these steps:

Run Poverty and Population notebooks first to acquire and clean population and poverty data.

Next, run the Crime Cleaning notebook to clean the crime data.

Finally, run the Modeling notebook to merge all the datasets and build a crime classifier.
## Conclusion

By predicting the types of crimes that occur in different zip codes, we hope to help law enforcement agencies allocate resources more effectively and enhance public safety in Philadelphia. This project demonstrates the power of data science in solving real-world problems and making a positive impact on society.




