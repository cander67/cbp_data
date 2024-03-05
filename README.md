Pollution Factors and Wage Growth by Industry
=====================

This project downloads, parses, cleans, and analyzes EPA pollution factors, US Census Bureau GDP, and County Business Patterns data for 2017-2021. The current scope is analysis of pollution emissions by industry and analysis of wage growth within polluting industries.

Pre-requisites
---------------------

Local deployment can be accomplished by creating a virtual environment using Python 3.11 and installing the necessary dependencies as described below.

Install dependencies from the terminal using the following command: `pip install -r requirements.txt`

OR

- Python 3.11
- Jupyter notebook 6.5.4
- [API key](https://api.census.gov/data/key_signup.html)

The following third party Python libraries were used:
- requests 2.31.0
- NumPy 1.26.4
- Pandas 2.2.1
- Matplotlib 3.8.3
- Seaborn 0.13.2

County Business Pattern data was accessed by API. Documentation for the US Census Bureau API can be found at https://www.census.gov/data/developers/guidance/api-user-guide.html. 

Getting Started
---------------------

To run this project, download and unzip the following files:

1) datasets.zip (Contains the below csv files)
    *   2012_to_2017_NAICS.csv
    *   all_geocodes_v2021.csv
    *   CAP_HAP_national_2017_v0.1_864d573.csv
    *   CRHW_national_2017_v0.1_864d573.csv
    *   SAGDP2N__ALL_AREAS_1997_2022.csv
    *   SupplyChainGHGEmissionFactors_v1.2_NAICS_CO2e_USD2021.csv
2) pollution_and_wages.ipynb (Project notebook)

Open the .ipynb file in Jupyter Notebook and run the code to download, parse, clean, and analyze the raw US Census Bureau and EPA data.

Support
---------------------

Contributions and suggestions are welcome and may be submitted by forking this project and submitting a pull request through GitHub.
