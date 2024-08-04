## OVERVIEW
The project is my capstone project for CODE:You. The project analyzes 3 socioeconomic factors across 50 US states, school quality, mean income, and mental health, in year 2023.  The objective is to deduce rankings of those factors, to help determine which areas are most attractive to live in.

## DATA
The dataset used in this project contains information about school quality, school safety, income by occupation, mental health indicators (i.e. depressive and anxiety factors) across all 50 states and District of Columbia.

### Data 1 - Schools - https://scholaroo.com/report/state-education-rankings/ 
This dataset already has the schools ranked based on Student Success, Student Safety, and School Quality variables for year 2023.

### Data 2 - Income - https://www.cnbc.com/2024/04/14/median-annual-income-in-every-us-state.html
This dataset lists income levels in 2023 for various areas in the States based on different occupations.

### Data 3 - Mental Health - https://www.cdc.gov/nchs/covid19/pulse/mental-health-care.htm
This dataset utilizes survey results from various households throughout the US, focusing on depressive and anxiety indicators.  Surveys were done over the course of several years, including year 2023.

## PROJECT STRUCTURE
### The project is organized as follows:

Data Exploration: Jupyter notebooks or scripts to explore the dataset.

Analysis: Using Python with the Pandas package to clean the data.

Visualizations :  Tableau dashboard

## FEATURES
| Feature |	Description |
|---------| ----------- |
| Read TWO data files |	Used 3 CSV files from kaggle and online sources |
|Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set | Cleaned my data and merged them with pandas. Calculated rankings from various data points |
| Visualization - Tableau dasboard | Made a dashboard with my findings |
| Utilize a virtual environment |	Made a venv for this project to keep my computer clean |
| Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find notes describing each code block |

## Getting Started
To run this project, follow these steps:

1. Clone the repository: git clone https://github.com/kittysinaga/Capstone_Project
2. Install the necessary dependencies: pip install -r requirements.txt
3. Explore the Jupyter notebooks or scripts in the respective folders

## Dependencies
All dependencies or libraries are contained in requirements.txt file

## Virtual Environment Instructions
1. After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal.
2. Create a virtual environment in the project folder.
3. Activate the virtual environment.
4. Install the required packages.
5. When you are done working on your repo, deactivate the virtual environment.

Virtual Environment Commands

| Command |	Linux/Mac |	GitBash |
| -------- | --------- | -------- |
| Create |	python3 -m venv venv |	python -m venv venv |
| Activate | source venv/bin/activate |	source venv/Scripts/activate |
| Install |	pip install -r requirements.txt |	pip install -r requirements.txt |
| Deactivate |	deactivate |	deactivate |