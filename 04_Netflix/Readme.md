# Netflix Movies and TV Shows – Data Cleaning & Exploratory Data Analysis

## Project Overview

This project focuses on cleaning, exploring, and analysing the Netflix Movies and TV Shows dataset using Python.

The objective is to understand the dataset, handle missing values, remove duplicate records, perform exploratory data analysis (EDA), and create visualizations to discover meaningful patterns in Netflix content.

## Objectives

- Understand the structure and characteristics of the dataset.
- Identify and handle missing values.
- Detect and remove duplicate records.
- Perform basic data cleaning and preprocessing.
- Analyse Movies and TV Shows separately.
- Explore content distribution by release year, country, genre, and rating.
- Create visualizations to communicate findings.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Data analysis environment |

## Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains information about Netflix movies and television shows, including:

- Show ID
- Content Type
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Genre
- Description

## Project Structure

```text
04_Netflix_Analysis/
│
├── Datasets/
│   ├── netflix_titles.csv
│   └── Netflix_Cleaned.csv
│
├── Notebooks/
│   └── Netflix_Data_Cleaning_and_EDA.ipynb
│
├── Visualisations/
│   ├── content_type_distribution.png
│   ├── release_year_distribution.png
│   ├── top_countries.png
│   ├── top_genres.png
│   └── rating_distribution.png
│
└── README.md
```

## Data Cleaning Process

The following operations were performed:

1. Loaded the dataset using Pandas.
2. Inspected the dataset using `head()`, `info()`, `describe()`, and `shape`.
3. Identified missing values using `isnull()`.
4. Checked and removed duplicate records.
5. Handled missing values in selected columns.
6. Converted the `date_added` column into datetime format.
7. Checked the dataset again after cleaning.
8. Exported the cleaned dataset into a CSV file.

## Exploratory Data Analysis

The following questions were explored:

1. How many Movies and TV Shows are available?
2. Which countries have the highest number of Netflix titles?
3. Which years have the most content releases?
4. Which genres are most common?
5. Which content ratings appear most frequently?
6. What is the average duration of Netflix movies?

## Visualizations

The project includes visualizations for:

- Movies vs TV Shows distribution
- Content released by year
- Top 10 countries
- Top 10 genres
- Netflix content ratings

Visualizations are saved in the `Visualisations/` folder.

## Key Learnings

Through this project, I practised:

- Data inspection and understanding.
- Handling missing values.
- Removing duplicate records.
- Working with Pandas DataFrames.
- Data type conversion.
- Grouping and aggregating data.
- Exploratory Data Analysis.
- Creating charts using Matplotlib and Seaborn.
- Saving cleaned datasets and visualizations.

## How to Run the Project

**1. Clone the repository**

```bash
git clone YOUR_REPOSITORY_URL
```

**2. Install dependencies**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**3. Download the dataset**

Download `netflix_titles.csv` from Kaggle and place it inside the `Datasets/` folder.

**4. Open Jupyter Notebook**

```bash
jupyter notebook
```

**5. Run the notebook**

Open `Netflix_Data_Cleaning_and_EDA.ipynb` and execute the cells sequentially.

## Author

**Upendra Kumar Yadav**

B.Tech – Computer Science Engineering

GitHub: [@upendraky](https://github.com/upendraky)

---

*This project is part of my Data Science learning journey, where I practise data cleaning, exploratory data analysis, and data visualization using real-world datasets.*