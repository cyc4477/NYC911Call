# NYC911Call
# NYC 311 Calls Analysis

## Overview

This project involves the analysis of NYC 311 calls data, which provides insights into non-emergency City services and information about City government programs for the residents of New York. The dataset, sourced from the NYC Open Data portal, contains information on millions of service requests made to 311.

## Dataset

The dataset, available on the NYC Open Data portal [here](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9), includes details on various types of service requests, their resolution status, and other relevant information. The data has been preprocessed, removing unnecessary columns and ensuring a clean format.

## Exploratory Data Analysis (EDA)

The initial phase of the project involves extensive Exploratory Data Analysis (EDA) to understand the characteristics of the dataset. Key aspects covered in EDA include:
- Types of complaints
- Complaint descriptions
- Earliest and latest dates
- Distribution of complaints by borough
- Analysis of monthly call trends
- Identification of the quietest month historically

## Data Exploration Code

The Jupyter notebook in this repository contains the Python code used for data exploration and analysis. It covers loading the data, setting the index, visualizing distributions, and answering specific questions posed in the project.

## Dependencies

Ensure you have the following Python libraries installed to run the code:
- pandas
- matplotlib
- seaborn
- fbprophet (for time series forecasting)



How to Run

Clone this repository to your local machine:
git clone https://github.com/your-username/nyc-311-calls-analysis.git

Open the Jupyter notebook NYC_311_Calls_Analysis.ipynb using Jupyter or a compatible environment.
Run the code cells in the notebook to perform data exploration and analysis.
Results

The analysis provides insights into complaint types, trends over time, and other relevant aspects of NYC 311 calls. Specific results for each question posed in the project can be found in the notebook.

Future Work

Potential future enhancements to this project include:

Time series forecasting with more advanced models
Additional visualizations for a deeper understanding of data patterns
Exploration of external factors affecting call volumes on specific dates
License

This project is licensed under the MIT License.
