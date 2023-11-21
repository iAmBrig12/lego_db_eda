# LEGO Database Analysis

### Project Overview
This data analysis project aims to provide insights into the LEGO sets released between 1950 and 2017.

### Data Sources
LEGO Data: https://www.kaggle.com/datasets/rtatman/lego-database

### Tools
- Python 3.11.6
  - matplotlib.pyplot
  - Seaborn
  - Numpy
  - Pandas

### Data Cleaning
In the initial data preperation phase, I performed the following tasks:
1. Data loading and inspection
2. Check for missing values
3. Data cleaning and formatting

### Exploratory Data Analysis
EDA involved exploring the LEGO data to answer key questions, such as
- What is the trend in the volume of sets released by LEGO?
- What is the trend in the average number of parts used in sets?
- How has the number of LEGO set themes changed?
- What themes have the most parts on average?
- What are the most common parts in LEGO sets?

### Results/Findings
The analysis results are summarized as follows:
1. LEGO has been steadily releasing more sets as the years pass. Some years have significant spikes in sets released.
   
   ![image](https://github.com/iAmBrig12/lego_db_eda/assets/97715791/0cefdb12-a5b7-4cb3-8309-ad9c18ef1fd6)
   
3. The average number of pieces in a particular set has also increased over the years.
   
   ![image](https://github.com/iAmBrig12/lego_db_eda/assets/97715791/c0d831b0-728c-4cc1-ae7a-4de207c9d612)
   
5. LEGO has been increasingly adding themes over the years, though there is a major dip in theme count in the years after 2012.
   
   ![image](https://github.com/iAmBrig12/lego_db_eda/assets/97715791/f7b61af1-e762-4cfa-ac1e-01c70c0e8c9e)
   
7. The top 5 themes with the most parts on average are Modular Buildings, Mosaic, Sculptures, Ultimate Collector Series, and FIRST LEGO League, in that order.
8. The top 5 part categories are Minifigs, Minifig Accessories, Non-LEGO, (Duplo, Quatro and Primo), and Tiles Printed, in that order.



