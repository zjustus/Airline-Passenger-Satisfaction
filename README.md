# Airline Passenger Satisfaction

This Is A Project for California State University Los Angeles CS4661
The goal is to determine what factors lead to highest customer satisfaction for an Airline
This Project Comes from Kaggle - https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction

# Progress and Roadblocks
- Loaded in the data set
- established pandas train and test data
- attempted nearest neighbor classification
    - This failed due to certain data columns being in a string format. Data Manipulation required
    - This failed due to some columns missing data
- Mapped out all columns that need re-mapping and listed its unique values
- Ran statistical analysis to find all columns missing data
  - Used the mean of that column to fill in the missing data
- removed the ID column
- removed the index column
- Added Decision tree classification
- Added Random Forest classification
- Added XGBoost Classification
- Compared all AI results.