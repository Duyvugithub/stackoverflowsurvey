# Stack Overflow Developer Survey Analysis
 
## 1. Installations
To run the analysis, you'll need the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
 
You can install these libraries using pip:
 
```bash
pip install pandas numpy matplotlib seaborn
```
 
## 2. Project Motivation
In the world of tech, understanding what drives salaries is crucial not just for professionals charting their career paths, but also for organizations looking to attract top talent. As a data scientist, I’ve had the opportunity to analyze how factors like education level, years of experience, and programming language proficiency influence salaries. This project aims to provide insights into these factors by analyzing data from the Stack Overflow Developer Surveys conducted between 2021 and 2023.
 
## 3. File Descriptions
`data/`: This folder contains all the data used in this project, including:
- `survey_2021.csv`, `survey_2022.csv`, `survey_2023.csv`: Raw survey data from 2021 to 2023.
- `schema.csv`: Defines the schema for ambiguous columns across the three datasets.
- `currency_exchange.csv`: Contains currency exchange rates for converting all salaries to USD.
 
`Stackoverflow_developer_analysis.ipynb`: The main analysis file where data is transformed and visualized using Python. This notebook includes steps to clean the data, handle missing values, and perform exploratory data analysis (EDA) with visualizations to uncover trends and patterns in salary data.
 
## 4. How to Interact with the Project
To interact with the project:
1. Install Stack Overflow Annual Developer Survey in 2021, 2022, 2023
2. Unzip those files in data folder with file path like `data/stack-overflow-developer-survey-2023`
3. Open and run all code in `Stackoverflow_developer_analysis.ipynb`
 
## 5. Licensing, Authors, Acknowledgements, etc.
You can access the data used in this analysis via this link:
- [Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co/).

## Medium post:
[Understanding the Impact of Education, Experience, and Programming Languages on Salary of Developer: A Data-Driven Analysis](https://medium.com/@vu38988/understanding-the-impact-of-education-experience-and-programming-languages-on-salary-of-99d413c5a589)
