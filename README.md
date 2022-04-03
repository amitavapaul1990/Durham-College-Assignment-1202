# Build Key statistics using python 
In this project we will learn how to get key statistics of a given dataset using python code.
## Description
In this Document, we will learn how to use Python for preprocessing your data when Imported from a csv file. By the end of this document, you will be familiar with basic python function for analyzing your dataset.
## Getting started
### Prerequisites
Before we starting to import the csv file, we need to import below library functions 
* Anaconda
* Pandas 
* matplotlib
## Executing Program  
1. Import CSV files:

- Create a data frame named as ‘df’ and then we need to use read_excel() function from pandas and pass the path & sheet name as argument.
After that we will use head () function to display the first 5 rows from the dataset.
df = pd.read_excel('location', sheet_name='Sheet1')
df.head()

2. Use of different basic functions for analyzing key statistics:

   **df.decribe()**
   
   The describe function displays the below for all the columns with continuous data in the file

- count of record for each column 
- Mean of the records for that column 
- Standard deviation
- Minimum value
- Qualrtile1 range (25% data range)
- Quartile2 range (50% data range)
- Quartile2 range (75% data range)
- Maximum value in the column

3. We can use this below function to measure mean, standard deviation, median for individual columns.

    1. **df[‘Column name’].mean()**

    This will return the average value for the column
    For example: df['Hits']. mean ()
    
    2. **df[‘Column name’].median()**
    
    This will return the return the median value for the particular column.
    For example: df['Hits']. median ()
    
 ## Help
 
 
 ## Author
 
 Amitava Paul
 
 ## Version History
 
 * 0.1 
     * Initial Release




