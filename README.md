# Extreme Poverty Prediction

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

Python (version 3.x)
Jupyter Notebook
scikit-learn (sklearn) library
world_bank_data library
Standard Python libraries such as numpy, pandas, matplotlib, and seaborn.
Please ensure that these dependencies are installed before running the Jupyter Notebook.

## Usage
Clone the repository to your local machine or download the project files as a ZIP archive.

Install the required dependencies mentioned in the "Dependencies" section.

Open the Jupyter Notebook (research_project.ipynb) using Jupyter Notebook or any compatible environment.

Follow the instructions within the notebook to execute the cells sequentially. This will run the data collection, preprocessing, EDA, and modeling steps.

Analyze the results, interpretations, and visualizations provided in the notebook to answer the research questions.

## Conclusion
By performing this exploratory data analysis and modeling, we aim to gain valuable insights into the world's extreme poverty situation and identify predictive characteristics for countries with large populations living in extreme poverty and those emerging from it. The results obtained from this research can contribute to a better understanding of the factors influencing extreme poverty and aid in the development of targeted interventions and policies.

For further details, please refer to the Jupyter Notebook (research_project.ipynb) included in this repository.

Note: The above instructions assume familiarity with Jupyter Notebook and the necessary setup to run Python code. If you encounter any issues or have questions, please refer to the documentation of the respective libraries or seek assistance from the project authors.
