# AWS ML Engineer Associate 1.1 Collect, Ingest, and Store Data

* Initial phase of machine learning lifecycle.

**Fundamentals of Data collection:**<br/>
    1. Relevant data must be available for efficient training - Accurate data without bias and highly precise/correct.
    2. Collecting data - Get all data into one dumping house - **DataLakes**
    3. **DataLakes** - Central storing structure which holds - structured, un-structured, semi-structured data- This data can be used for training or loaded to databases.
    4. **Data warehouses** - Store _structured_ data in relational databases - Online Analytical process model - Contain data on well defined _tables_.
    5. Ensure that the dataset collection has _highly performing data_ 
   
            * Representative 
            * Relevant
            * Feature Rich
            * Consistent

**Types of Data** <br/>

1. **Text** - Textual data like documents, website content - converted to numbers for analyzing using NLP techniques for tasks like ex- sentiment analysis. Model uses _numeric_ representation of text for analysis.

 <br /> 

2. **Tabular** - Table structured data organization with rows and columns. Data from spreadsheets and databases.
<br/>

3. **Timeseries** - Data Collected on units of time as measure. sensor data, financial data - stock exchange. ML model is used for predicting trends.
   <br/>

4. **Image** - Image data refers to the actual pixel values that make up a digital image. Image is frequently used in machine learning for object recognition, autonomous driving, and image classification.

**Data Format types** <br/>
    Row based - Ex: CSV, Avro RecordIO
    Column based - Ex: Parquet,ORC
    Object Notation - Ex: JSON, JSONL


**EDA**
Categorical data => Visualization techniques - Bar chart, Pie chart, Heatmaps
Numeric data => Visualization techniques - Scatterplot, BoxPlot, Histogram, Density Plots.

**AWS Storage Options**

[Storage Options](StorageOptionsForData.md)