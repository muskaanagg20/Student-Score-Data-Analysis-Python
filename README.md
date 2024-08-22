# 📚 Student Academic Performance Analysis 📚

![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3.3-blue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.3-blue.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-blue.svg)

## Overview

This project involves a comprehensive analysis of a student performance dataset to uncover insights related to academic performance and influencing factors. The dataset comprises 30,641 entries and 15 columns, providing various details about students, including their demographics, education background, and academic scores. The analysis leverages Python within a Jupyter Notebook environment, utilizing advanced data manipulation and visualization libraries.

## Table of Contents

- [Dataset](#dataset)
- [Tools Used](#tools-used)
- [Analysis Steps](#analysis-steps)
- [Files Included](#files-included)
- [Usage](#usage)
- [Conclusion](#conclusion)

## Dataset

The dataset, `Student Scores.csv`, includes the following columns:
- **Gender**: Gender of the student
- **EthnicGroup**: Ethnic group of the student
- **ParentEduc**: Education level of the parents
- **LunchType**: Type of lunch (Standard or free/reduced)
- **TestPrep**: Whether the student completed test preparation (Yes/No)
- **ParentMaritalStatus**: Marital status of the student's parents
- **PracticeSport**: Whether the student practices sports (Yes/No)
- **IsFirstChild**: Indicates if the student is the first child (Yes/No)
- **NrSiblings**: Number of siblings the student has
- **TransportMeans**: How the student commutes to school
- **WklyStudyHours**: Weekly study hours of the student
- **MathScore**: Score in Math
- **ReadingScore**: Score in Reading
- **WritingScore**: Score in Writing

## Tools Used

- **Python**: Core programming language for data analysis.
- **Jupyter Notebook**: Interactive environment for code execution, data visualization, and analysis.
- **Pandas**: Library for data manipulation and analysis.
- **NumPy**: Library for numerical operations and array manipulation.
- **Matplotlib & Seaborn**: Libraries for creating static, animated, and interactive visualizations.

## Analysis Steps

1. **Data Loading**: Import the CSV file into a Pandas DataFrame.
2. **Data Cleaning**: Handle missing values, remove duplicates, and prepare the data for analysis.
3. **Exploratory Data Analysis (EDA)**: Examine the dataset to understand its structure and generate summary statistics.
4. **Data Visualization**: Create visualizations to illustrate:
   - Correlation between test preparation and academic scores (Math, Reading, Writing).
   - The effect of parents' education level on student scores.
   - The influence of sports participation on academic performance.
   - Gender distribution and its impact on scores.
   - The impact of parent marital status on student scores.
   - Correlation between weekly study hours and student scores.
   - Performance differences between students on free/reduced lunch and those on standard lunch.

## Files Included

- `Student Scores.csv`: Raw dataset used for analysis.
- `Student Scores.ipynb`: Jupyter Notebook containing the Python code for the analysis.

## Usage

To reproduce the analysis:
1. Clone the repository or download the files to your local machine.
    ```sh
    git clone https://github.com/yourusername/student-academic-performance-analysis.git
    cd student-academic-performance-analysis
    ```
2. Ensure you have Python installed along with the necessary libraries: Pandas, Matplotlib, and Seaborn.
    ```sh
    pip install pandas matplotlib seaborn jupyter
    ```
3. Open `Student Scores.ipynb` in Jupyter Notebook.
    ```sh
    jupyter notebook Student Scores.ipynb
    ```
4. Run the cells in the notebook sequentially to perform the analysis step-by-step.

## Conclusion

The analysis of the student performance data provides valuable insights into academic performance trends and factors influencing student achievement. These findings can inform educational strategies, support targeted interventions, and enhance understanding of student performance dynamics.

---

⭐️ If you found this project interesting or helpful, please give it a star! ⭐️
