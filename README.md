<div align="center">

# Student Performance Indicator
## End to End Machine Learning Project
<p align='center'>
<!-- <img src="https://img.shields.io/badge/Django-239120?logo=django&logoColor=white" /> -->
<img src="https://img.shields.io/badge/Python-1572B6?logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-darkblue?logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/scikit_learn-yellow?logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Jupyter_Notebook-orange?logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-blue?logo=flask&logoColor=white" />
<!-- <img src="https://img.shields.io/badge/bootstrap-563D7C?logo=bootstrap&logoColor=white" /> -->
<a href="https://github.com/bhuvaneshwarguttula"><img src="https://img.shields.io/badge/Github-181717?logo=github&logoColor=white" /><a>
</p>

</div>
<hr class="dotted">

## Project Overview

Education is a critical factor in shaping an individual's future. The primary objective of this project is to develop a predictive model that can predict the performance of students in their academics. This project aims to explore various factors that may affect students' performance, including demographic information, family background, and school-related attributes. By analyzing this data, we can gain insights into potential areas for improvement in educational systems.

## Dataset Overview
The dataset consists of the following columns:

* gender: Gender of the student (categorical: 'male', 'female')
* race/ethnicity: Ethnic background of the student (categorical: five levels)
* parental level of education: Highest level of education attained by the student's parents (categorical: 'high school', 'some college', 'associate's degree', 'bachelor's degree', 'master's degree')
* lunch: Type of lunch received (categorical: 'standard', 'free/reduced')
* test preparation course: Whether the student completed a test preparation course (categorical: 'none', 'completed')
* math score: Score in mathematics (numerical: 0-100)
* reading score: Score in reading (numerical: 0-100)
* writing score: Score in writing (numerical: 0-100)

## Key Features

- **Data Cleaning and Preprocessing**: Handling missing values, correcting data types, and preparing the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Visualization of key variables to understand their distribution and relationships.
- **Statistical Analysis**: Identifying significant factors that correlate with student performance using correlation analysis and regression models.
- **Visualization**: Visualizing relationships between variables through various plots, such as bar charts, and scatter plots.
- **Model Training**: Model training on several machine learning models and finding out which model performed the best.

## Technologies Used

- **Python**
  - pandas
  - NumPy
  - seaborn
  - matplotlib
  - scikit-learn
  - Flask
- **Jupyter Notebook**

## Results
- The project provides insights into which factors have a significant impact on student performance. These findings can be utilized to tailor educational strategies and improve academic outcomes.

## Installation Steps
Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Repository**
   - Open your terminal or command prompt.
   - Navigate to the directory where you want to install the project.
   - Run the following command to clone the GitHub repository:
     ```
     git clone https://github.com/bhuvaneshwarguttula/Student-Performance-Indicator.git
     ```

2. **Create a Virtual Environment** (Optional but recommended)
   - It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
     ```
     conda create -p <Environment_Name> python==<python version> -y
     ```

3. **Activate the Virtual Environment** (Optional)
   - Activate the virtual environment based on your operating system:
       ```
       conda activate <Environment_Name>/
       ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

5. **Run the Project**
   - Start the project by running the appropriate command.
     ```
     python app.py
     ```

6. **Access the Project**
   - Open a web browser or the appropriate client to access the project.

