# Data-Cleaning-Tool---Python
The Python project herein simplifies the data cleaning process by developing a function with just two inputs: the data sheet and data source, and Python does the cleaning. From removing duplicates, cleaning, or filling missing values, this is the utmost requirement for any business or data analyst.

**Project Name - Data Cleaning Master Script**

**Problem Statement**

Data cleaning is a crucial stage in the data analysis lifecycle. It calls for business and data analysts to ensure that they using correct and cosistent datasets in order to draw correct insights from data. 
This script tackles the common issues such as:
- Duplicated data
- Missing values
- Inconsistent formatting

- 
**Solution Summary**
  
The DataCleaningMaster script automates the process by:
- Checking file path validity
- Supporting .csv and .xlsx formats
- Identifying and exporting duplicate records
- Handling missing values based on column type
- Saving a clean dataset ready for analysis
- 
**Key Features**
- Exports duplicate rows before removal
- Fills numeric missing values with mean
- Drops categorical missing records
- Easy to reuse across projects
- 
**How to Use**
  
1. Install required packages:
pip install pandas numpy

3. Use the function:
from DataCleaningMaster import DataCleaningMaster
cleaned_data = DataCleaningMaster("path/to/data.csv", "DatasetName")

Output Files
- DatasetName_duplicates.csv
- DatasetName_Clean_data.csv
- 
**Use Case Examples**
- Cleaning retail datasets before visualization
- Preparing data for machine learning
- 
Author
Robin Mwenda
Portfolio: https://datascienceportfol.io/robinmwendi8
Contact: robinmwendi8@gmail.com
