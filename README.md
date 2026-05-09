⚽ FIFA 21 Data Cleaning & Exploratory Data Analysis

📌 Project Overview
This project focuses on cleaning and analysing the FIFA 21 dataset.  
The dataset contains messy real-world football player data, which was cleaned and transformed into a structured format for analysis.

The goal is to demonstrate data cleaning, transformation, and exploratory data analysis (EDA) skills using Python.


🧠 Objectives
- Clean messy FIFA 21 raw dataset
- Handle inconsistent formats (currency, height, weight, ratings)
- Rename and structure columns properly
- Perform exploratory data analysis (EDA)
- Extract insights from player data


🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib

🧹 Data Cleaning Process
The dataset required significant cleaning, including:

- Converting **Value** and **Wage** from strings (€, K, M) to numeric values
- Converting **Height** from feet/inches to centimeters
- Converting **Weight** from lbs to kilograms
- Renaming inconsistent column names (e.g. `↓OVA` → `Overall`)
- Handling missing values
- Standardizing data formats

📊 Exploratory Data Analysis (EDA)
Key analyses performed:

- Distribution of player ages
- Relationship between Overall rating and Wage
- Top 10 highest-rated players
- Nationality distribution of players

📈 Key Insights
- Most players are between 20–27 years old
- Higher-rated players generally earn higher wages
- Player value and wage vary significantly across leagues and nationalities


📁 Dataset Source
Kaggle FIFA 21 dataset

🚀 Future Improvements
- Build a dashboard using Power BI or Streamlit
- Deeper analysis of player performance metrics
- Predict player value using machine learning
