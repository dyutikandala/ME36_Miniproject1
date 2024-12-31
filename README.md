# ME36_Miniproject1

A Comprehensive ETL Workflow with Python for Data Engineers.

Problem statement: This project highlights the practical implementation of ETL processes using Python. The data extraction from multiple file formats (csv,xml,json), transformation of units(height from inches to meters, weight from pounds to kilograms), and loading of the final data into a structured CSV format demonstrate essential data engineering skills. Additionally, it also involves logging each step of the etl process with a timestamp, to be able to monitor the progress and debug issues if they arise.

Approach: Extract-> transform -> load and logging of each step.

Extract Data: This step extracts data from multiple sources into a singke dataframe and unitifed format.
  Three different functions to extract data from CSV, JSON, and XML files respectively.
  A master function will call the relevant function based on the file type and combine the extracted data into a single DataFrame, returns the same.
  
Transform Data: This step ensures the data is in the desired format for further analysis or storage. 
  A function with arithematic operations on data to do below conversion converting:
    Height from inches to meters.
    Weight from pounds to kilograms.
  Takes extracted dataframe from extract phase as input and returns transformed data frame.
 
Load Data: A function to load transformed data frame to a target CSV file, which can later be loaded into a relational database or used for further processing. 
  
Logging: A function to record beginning and ending of each ETL phase (Extraction, Transformation, Loading) with timestamp.

Execution flow: Extract -> Transform -> load and loggin of each step.





