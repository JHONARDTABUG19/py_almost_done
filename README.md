ACADEMIC ANALYTICS LITE

This python based program handles data ingestion,validation,basic CRUD operations, and detailed grade analytics and reporting.

FEATURES
The command line menu is run by a TUI 

Data Management
Add/Save Students - Insert new student in the records.
Read/Display - View the current contents of the student record file.
Delete by ID - Remove a specific student in the record by ID.
Sort Data - Sort the entire dataset based on any column

Grade Analysis
Weighted grade computation
Grade Distribution
Percentiles
Improvement Trackinga

File Structure

File Name
Description
main.py
Contains the menu  and handles user input, calling functions from other modules.
ingest.py
Contains clean_ingest function responsible for reading  studentRecord.csv, validating data types, range check(0 - 100), and handling missing values.
array_operations.py
Used for data manipulation and it includes functions for saving new data, overwriting cleaned data, deleting rows, selecting columns,projecting records and sorting datasets.
analytics.py
Contains all functions for calculating weighted averages and checking for improvements.
reportz.py
Contains functions for generating overall summary reports, exporting at-risk student list, and displaying section specific data.
studentRecord.csv
File containing the student records.


Prerequisites
To run this application, you need Python and the numpy library.

1.Ensure that you have Python 3.6+ installed.
2. Install numpy using this command in the Command Prompt





How to Run
1. Ensure that you have python files and the data file in the same directory.
2.Open your terminal in that directory.
3. Run the program normally or with python main.py
4.Follow the on screen menu prompts to interact with the system.


AI USE DISCLOSURE
AI Disclosure: Portions of this script were generated or refined using ChatGPT  for debugging, fixing grammatical errors and optimization. The author verified, tested, and modified all AI outputs.
