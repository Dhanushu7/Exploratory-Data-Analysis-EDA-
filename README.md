# Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs an exploratory data analysis on the Titanic dataset to uncover patterns, trends, and insights related to passenger survival. The analysis is done using Python in a Google Colab environment with libraries like Pandas, Matplotlib, and Seaborn.

## Objective

The primary goal of this project is to apply EDA techniques to understand how different features such as age, gender, ticket class, and fare influenced survival rates in the Titanic disaster.

## Dataset

The dataset used is the classic Titanic dataset, containing data on 891 passengers including:
- Passenger details (name, age, gender)
- Ticket and cabin information
- Survival status (0 = No, 1 = Yes)

## Tools Used

- Python (3.x)
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Key Steps

1. **Data Loading and Exploration**
   - Used `.info()`, `.describe()` and `.value_counts()` to explore the structure and statistics of the dataset.

2. **Data Cleaning**
   - Handled missing values in `Age`, `Embarked`, and dropped the `Cabin` column due to high missing percentage.
   - Converted categorical variables (`Sex`, `Embarked`) into numerical format for analysis.

3. **Visual Analysis**
   - Visualized relationships using histograms, boxplots, countplots, and a correlation heatmap.
   - Explored survival patterns based on gender, age, passenger class, fare, and family size.

4. **Insights Summary**
   - Survival was strongly related to gender and class.
   - Women and children had higher survival rates.
   - First-class passengers had a better chance of survival than those in lower classes.
   - Fare and age showed some correlation with survival, though not as strongly as gender and class.

## How to Run

1. Open the Colab notebook.
2. Upload the `train.csv` Titanic dataset file when prompted.
3. Run each cell in sequence to load, clean, visualize, and interpret the data.
4. Export the notebook as a PDF for reporting if needed.

## Outcome

This project demonstrates how to use EDA techniques to extract meaningful insights from raw data. It builds a foundational understanding of how to approach real-world datasets and identify key patterns and relationships using Python.

## Contact

**Author**: Dhanushu V  
**Email**: dhanushu77@gmail.com
