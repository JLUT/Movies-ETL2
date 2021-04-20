<img width="631" alt="Screen Shot 2021-04-20 at 11 26 25 AM" src="https://user-images.githubusercontent.com/71113701/115432007-8d8a0d80-a1cb-11eb-9a1e-8203da183775.png">

# Movies-ETL

In this project, we learned how to use the Extract, Transform, Load (ETL) process to create data pipelines. A data pipeline moves data from a source to a destination, and the ETL process creates data pipelines that also transform the data along the way. Analysis is impossible without access to good data, so creating data pipelines is often the first step before any analysis can be performed. Therefore, understanding ETL is an essential skill for data analysis.

# Resources
The Movies-ETL uses Kaggle data. The Kaggle dataset pulls from the MovieLens dataset of over 20 million reviews and contains a metadata file with details about the movies from The Movie Database (TMDb). There, we downloaded the zip file from Kaggle, extracted, and decompressed the CSV files we were interested in; movies_metadata.csv and ratings.csv files.
# Objectives
Create an ETL pipeline from raw data to a SQL database.
Extract data from disparate sources using Python.
Clean and transform data using Pandas.
Use regular expressions to parse data and to transform text into numbers.
Load data with PostgreSQL.

# ETL
The idea behind ETL is straightforward. Raw data exists in multiple places and needs to be cleaned and structured before it can be analyzed. ETL breaks this problem into three steps, or phases: Extract, Transform, and Loa
d.

#EXTRACT
In the Extract phase, data is pulled from external or internal sources, possibly disparate. The sources could be flat files, scraped webpages in HTML or JavaScript Object Notation (JSON) format, SQL tables, or even streams of sensor data. The extracted data is held in a staging area in between the data sources and data targets.

TRANSFORM
After data is extracted, there are many transformations it may need to go through. The data may need to be filtered, parsed, translated, sorted, interpolated, pivoted, summarized, aggregated, merged, or more. The goal is to create a consistent structure in the data. Without a consistent structure in our data, it’s almost impossible to perform any meaningful analysis.
We used Python and Pandas to explore, document, and perform our data transformation.

LOAD
Finally, after the data is transformed into a consistent structure, it’s loaded into the data target. The data target can be a relational database.
We loaded our data into a PostgreSQL table.
