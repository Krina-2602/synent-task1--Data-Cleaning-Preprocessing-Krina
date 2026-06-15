# synent-task1-DataCleaningPreprocessing-Krina

[Problem Statement]:
Real-world datasets often contain missing values, duplicate records, and inconsistent data formats that can affect analysis and machine learning performance. The objective of this project is to clean and preprocess the Titanic dataset to improve data quality and make it suitable for further analysis and predictive modeling.

[Dataset Details]:
->Dataset: Titanic Passenger Dataset (tested.csv)
->Features: Passenger information such as age, gender, class, fare, ticket details, and survival status.
->Issues Found:
  Missing values in Age, Fare, and Cabin
  Duplicate records
  Inconsistent data types

[Approach]:
1.Loaded and explored the dataset.
2.Filled missing values in Age and Fare using median values.
3.Removed the Cabin column due to excessive missing data.
4.Removed duplicate records.
5.Converted categorical columns to appropriate data types.
6.Renamed columns for better readability.
7.Saved the cleaned dataset as Titanic_Cleaned.csv.

[Results]:
Missing values successfully handled.
Duplicate records removed.
Dataset cleaned and standardized.
Categorical variables properly formatted.
Final dataset is ready for exploratory analysis and machine learning tasks.

[Output]: Titanic_Cleaned.csv

[Conclusion]:
The Titanic dataset was successfully cleaned and preprocessed by handling missing values, removing duplicates, optimizing data types, and improving column readability. The resulting dataset is structured, consistent, and ready for downstream data analysis and machine learning applications.
