Python Projects: EDA and Machine Learning on Apple Store and Suicide Rate Data
This repository contains two Python projects focused on Exploratory Data Analysis (EDA) and Machine Learning on two distinct datasets:

Apple Store Dataset - EDA to uncover trends and insights about app genres, ratings, and device compatibility.
Suicide Rates Dataset - EDA combined with Machine Learning to analyze global suicide rates and predict trends based on socioeconomic and demographic factors.
Table of Contents
Introduction
Project 1: Apple Store Data Analysis
Dataset Overview
Key Objectives
Data Pre-Processing
Insights and Visualizations
Project 2: Suicide Rates Analysis and Machine Learning
Dataset Overview
Key Objectives
Data Pre-Processing
Analysis and Insights
Machine Learning Models
Tools and Libraries
How to Use
Results
Future Scope
Contributing
License
Introduction
These projects utilize Python for data manipulation, visualization, and machine learning. The goal is to:

Explore trends and key patterns in datasets through Exploratory Data Analysis (EDA).
Build predictive models to derive actionable insights.
Present data-driven conclusions for both datasets.
Project 1: Apple Store Data Analysis
Dataset Overview
The dataset contains information about apps on the Apple Store, including:
Genres, ratings, sizes, prices (Free vs. Paid), and supported devices.
Key Objectives
Understand the distribution of apps across genres.
Compare Free vs. Paid apps and their performance in various genres.
Identify the most popular apps and genres based on ratings.
Analyze multilingual and multi-device support.
Data Pre-Processing
Checked for missing values and removed duplicate rows.
Converted app sizes from Bytes to MB for better interpretation.
Used one-hot encoding for categorical data.
Insights and Visualizations
Genre Analysis:
Identified the distribution of apps across genres.
Highlighted most popular genres for Free and Paid apps.
Rating Analysis:
Found the most popular apps with ratings between 4 and 5.
Explored the highest-rated Free and Paid apps.
Device and Language Analysis:
Highlighted apps with the most supported devices.
Analyzed apps available in multiple languages.
Project 2: Suicide Rates Analysis and Machine Learning
Dataset Overview
The dataset contains global suicide data across countries and years, with fields such as:
Gender, age group, GDP per capita, and Human Development Index (HDI).
Key Objectives
Explore demographic and socioeconomic trends in suicide rates.
Identify correlations between economic indicators (GDP, HDI) and suicide rates.
Build Machine Learning models to predict suicide trends.
Data Pre-Processing
Handled missing values and removed duplicates.
Standardized numeric fields (e.g., GDP per capita).
Encoded categorical variables for Machine Learning models.
Analysis and Insights
Key Findings:
Suicide rates vary significantly by gender, age, and region.
Strong correlations were observed between GDP, HDI, and suicide rates.
Machine Learning Models:
Built models like Decision Tree, Random Forest, and Logistic Regression.
Evaluated performance using metrics like RMSE and accuracy.
Identified feature importance (e.g., GDP, HDI, gender).
Tools and Libraries
Both projects utilize the following Python libraries:

Pandas and NumPy: Data manipulation and processing.
Matplotlib and Seaborn: Data visualization.
Scikit-learn: Machine Learning and evaluation.
Plotly: Interactive visualizations.

How to Use
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git

Install dependencies:
pip install -r requirements.txt

Run the respective Jupyter notebooks or Python scripts for each project:
AppleStore_EDA.ipynb for Apple Store data analysis.
Suicide-Rates-Eda-Visualization.ipynb for Suicide Rates analysis and ML models.
