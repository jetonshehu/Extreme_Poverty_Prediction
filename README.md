# Extreme Poverty Prediction

<a href="https://zenodo.org/badge/latestdoi/639107975"><img src="https://zenodo.org/badge/639107975.svg" alt="DOI"></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Overview
The goal of this research project is to perform an exploratory data analysis and modeling to gain insights into the following questions:

What percentage of the world population lives in extreme poverty?
Which characteristics are predictive for countries with large populations living in extreme poverty?
Which characteristics are predictive for populations emerging from extreme poverty?

To accomplish this, we utilize various libraries from scikit-learn (sklearn) for data analysis and modeling. In addition, standard Python libraries are imported at the beginning of the Jupyter Notebook to ensure smooth execution of the project. One crucial library we use is <b>world_bank_data</b>, which facilitates direct loading of datasets from the World Bank database.

https://github.com/mwouts/world_bank_data

## Project Structure
The project is organized as follows:

Data Collection: We utilize the world_bank_data library to retrieve relevant datasets from the World Bank database. These datasets contain information on poverty indicators and various characteristics of countries around the world.

Data Preprocessing: Before conducting the exploratory data analysis, we preprocess the data to ensure its quality and suitability for analysis. This includes handling missing values, performing data transformations, and combining relevant variables.

Modeling: Using the preprocessed data, we employ machine learning techniques provided by scikit-learn to develop predictive models. These models aim to identify the characteristics that are predictive for populations emerging from extreme poverty.

Results and Discussion: The findings obtained from the modeling stages are summarized and discussed, addressing the research questions stated at the beginning.

## Dependencies
The following dependencies are required to run this research project:

### Standard Libraries

- numpy (version 1.17.4): Scientific computing library.
- matplotlib (version 3.1.2): Data visualization library.
- pandas (version 0.25.3): Data manipulation library.
- seaborn (version 0.9.0): Statistical data visualization library.

### Machine Learning Libraries

- scikit-learn (sklearn) (version 0.22): Machine learning library.
- lightgbm (version 3.3.5): Gradient boosting framework.

### GIS Libraries

- geopandas (version 0.6.2): Geographic data manipulation library.

### Visualization Libraries

- plotly (version 4.5.0): Interactive visualization library.

### Other Libraries

- world_bank_data (version 0.1.3): Library for accessing World Bank data.

## Usage
Clone the repository to your local machine or download the project files as a ZIP archive.
Open the Jupyter Notebook (Extreme_Poverty_Prediction.ipynb) using Jupyter Notebook or any compatible environment.

Follow the instructions within the notebook to execute the cells sequentially.
Analyze the results, interpretations, and visualizations provided in the notebook to answer the research questions.

## Datasets
Datasets are already included in this repository but if needed to be extracted from the repository dataset for some reason this are the DOI where the data can be accessed.

[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.1201635.svg)](https://doi.org/10.5072/zenodo.1201635) The dataset CountryTable_1.9.csv which needs to be saved in the file path data/CountryTable_1.9.csv

[![DOI](https://sandbox.zenodo.org/badge/DOI/10.5072/zenodo.1201693.svg)](https://doi.org/10.5072/zenodo.1201693)
The indicators datasets:
wb_education.csv
wb_gender.csv 
wb_health.csv 
wb_worlddev.csv
which needs to be saved in the file path data/wb_api


## Conclusion
By performing this exploratory data analysis and modeling, we aim to gain valuable insights into the world's extreme poverty situation and identify predictive characteristics for countries with large populations living in extreme poverty and those emerging from it. The results obtained from this research can contribute to a better understanding of the factors influencing extreme poverty and aid in the development of targeted interventions and policies.

For further details, please refer to the Jupyter Notebook (Extreme_Poverty_Prediction.ipynb) included in this repository.

Note: The above instructions assume familiarity with Jupyter Notebook and the necessary setup to run Python code. If you encounter any issues or have questions, please refer to the documentation of the respective libraries or seek assistance from the project authors.
