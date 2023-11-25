# Olympic 2021 Data Analysis using Azure
![Images/dataset-cover.jpg]
## Table of Contents
- [Overview](#overview)
- [Architecture](#architecture)
- [Data Ingestion](#data-ingestion)
- [Data Transformation](#data-transformation)
- [Data Analysis](#data-analysis)
  - [Average Number of Entries by Gender for Each Discipline](#average-number-of-entries-by-gender-for-each-discipline)
  - [Number of Teams By Country](#number-of-teams-by-country)
  - [Top Countries By Medals Won](#top-countries-by-medals-won)
  - [Top Disciplines in Participation](#top-disciplines-in-participation)
  - [Top Countries by Participants](#top-countries-by-participants)
  - [Number of Teams Per Events in Discipline](#number-of-teams-per-events-in-discipline)
  - [Number of Coaches By Country](#number-of-coaches-by-country)
  - [Main Disciplines Of Coaches](#main-disciplines-of-coaches)
- [Data Viz](#data-analysis)
- [License](#license)

## Overview

This project analyzes Olympic 2021 data using Azure services, including Azure Data Factory, Azure DataBricks Azure Data Lake Gen2, and Synapse Analytics and Tableau. The data is ingested, transformed using Spark in ADF, and analyzed to derive meaningful insights to visualize in Tableau.

## Architecture

Include a description of the architecture of your project and how the different Azure services interact. 

![Images/Architecture.png]

## Data Ingestion

### Step 1: Ingest Data To Our DataLake

1. Extract raw data from this Github Repository using Azure Data Factory.
2. Ingest the dataset By building a data flow and loading it into Azure Data Lake storage. 

![Images/DataIngestion.png]

## Data Transformation

### Step 2: Data Transformation using Azure DataBricks

1. Write Spark code to read data from the Data Lake.
2. Apply transformation techniques.
3. Load the transformed data back to Data Lake for analysis.
- Our code is available under **Tokyo Olympic Transformation.ipynb** Notebook File for Spark Transformations.

![Images/DataAnalytics.png]

## Data Analysis

### Step 3: Data Analysis

Use Synapse Analytics to run SQL queries on transformed data and visualize insights.
In our Case we choose to create Pipeline to create analytical data so that we can visualize in Tableau.

![Images/DataAnalytics.png]


### Counting the Number of Athletes by Country

[Add image for Counting Number of Athletes by Country]


### Number of Teams By Country

[Add image for Number of Teams By Country]


### Top Countries By Medals Won

[Add image for Top Countries By Medals Won]

### Top Disciplines in Participation

[Add image for Top Disciplines in Participation]


### Top Countries by Participants

[Add image for Top Countries by Participants]


### Number of Teams Per Events in Discipline

[Add image for Number of Teams Per Events in Discipline]


### Number of Coaches By Country

[Add image for Number of Coaches By Country]


### Main Disciplines Of Coaches

[Add image for Main Disciplines Of Coaches]

## Data Visualization

### Step 3: Data Visualization using Tableau.

![Add image for Main Disciplines Of Coaches]


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
