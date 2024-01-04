## SQL Challenge - Employee Database Project

### Background

As a newly hired data engineer at Pewlett Hackard, your first major task is to conduct a research project on individuals employed by the company during the 1980s and 1990s. The only remnants of the employee database from that period are six CSV files.

This project involves designing tables to store data from the CSV files, importing them into a SQL database, and subsequently analyzing the data. The process includes data modeling, data engineering, and data analysis.
        
## Data Engineering

Used the provided information to create a table schema for each of the six CSV files. Ensure the following:
        Specify data types, primary keys, foreign keys, and other constraints.
        For primary keys, confirm uniqueness. If not unique, create a composite key, which requires two primary keys to uniquely identify a row.
        Create tables in the correct order to handle foreign keys.

Import each CSV file into its corresponding SQL table.

Data Modeling

Entity Relationship Diagram (ERD):
        The CSV files were thoroughly inspected to create a detailed Entity Relationship Diagram to visualize the structure of the database tables.
        Tools like [QuickDBD][Entity Relationship Diagram (ERD)](https://www.quickdatabasediagrams.com/)
 were employed to facilitate the sketching of the ERD.

Data Engineering

Table Schema Creation:
        Utilizing the provided information, a robust table schema was meticulously crafted for each of the six CSV files.
        Specific attention was given to data types, primary keys, foreign keys, and other constraints.
        In cases where primary keys lacked uniqueness, composite keys were created, requiring two primary keys to uniquely identify a row.
        Tables were created in the optimal order to seamlessly handle foreign keys.

CSV File Import:
        Each CSV file was successfully imported into its corresponding SQL table, ensuring the data was seamlessly integrated into the database for further analysis.
