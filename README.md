Enhancing Public Safety in Philadelphia with Data Science

Introduction

In this project, we aim to enhance public safety in Philadelphia, Pennsylvania, by predicting the type of crimes that occur in different zip codes. We have collected data on population and poverty from the US Census Bureau and crime data from OpenDataPhilly. We also used the Google Maps API to map longitude and latitude to zip codes.

We merged all the cleaned datasets and performed multiclass classification using Logistic Regression and Random Forest algorithms. We achieved an accuracy of 58.34% with the Random Forest algorithm.

Libraries used

Scikit-learn
Folium
Pandas
NumPy
Seaborn
Matplotlib
Data Sources

US Census Bureau: https://www.census.gov/quickfacts/philadelphiacountypennsylvania
OpenDataPhilly: https://www.opendataphilly.org/
Running the code

Run Poverty and Population notebooks first to acquire and clean population and poverty data.
Next, run the Crime Cleaning notebook to clean the crime data.
Finally, run the Modeling notebook to merge all the datasets and build a crime classifier.
Conclusion

By predicting the types of crimes that occur in different zip codes, we hope to help law enforcement agencies allocate resources more effectively and enhance public safety in Philadelphia.




