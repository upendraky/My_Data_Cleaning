# 🌸 Iris Flower Data Analysis

## 📌 Project Overview

This project focuses on performing a complete Data Science workflow on the Iris Flower Dataset using Python.

The objective is to understand the dataset, perform data quality checks, clean and preprocess the data, conduct Exploratory Data Analysis (EDA), visualize patterns, and prepare the dataset for Machine Learning classification.

The analysis explores the relationships between sepal and petal measurements across three Iris flower species.

## 🎯 Project Objectives

- Understand the structure and characteristics of the Iris dataset.
- Perform data inspection and quality checks.
- Identify missing values and duplicate records.
- Clean and standardize column names and categorical values.
- Detect potential outliers using the IQR method.
- Perform Exploratory Data Analysis (EDA).
- Analyze relationships between numerical features.
- Visualize species-wise measurement differences.
- Perform feature encoding and scaling.
- Prepare data for Machine Learning.

## 📂 Dataset Information

The project uses the `Iris.csv` dataset.

| Attribute | Description |
|---|---|
| Total Records | 150 |
| Total Columns | 6 |
| Numerical Features | 5, including Id |
| Categorical Features | 1 |
| Missing Values | 0 |
| Duplicate Rows | 0 |
| Unique Species | 3 |

### Dataset Features

| Column | Description |
|---|---|
| Id | Unique record identifier |
| SepalLengthCm | Sepal length in centimeters |
| SepalWidthCm | Sepal width in centimeters |
| PetalLengthCm | Petal length in centimeters |
| PetalWidthCm | Petal width in centimeters |
| Species | Iris flower species |

### Target Classes

The dataset contains three species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each species contains 50 observations.

## 🛠️ Technologies Used

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Data preprocessing and Machine Learning preparation
- **Jupyter Notebook** – Interactive analysis environment

## 🔍 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Examined the first and last records.
- Checked dataset dimensions and column names.

### 2. Data Understanding
- Examined data types using `info()`.
- Generated descriptive statistics using `describe()`.
- Investigated unique values and species distribution.

### 3. Data Cleaning
- Checked missing values.
- Calculated missing-value percentages.
- Checked duplicate records.
- Standardized column names.
- Removed the identifier column from analytical features.
- Standardized categorical species labels.
- Validated numerical measurements.

### 4. Outlier Detection
- Used boxplots to visualize potential outliers.
- Applied the Interquartile Range (IQR) method.
- Investigated measurement distributions across species.

Outliers were investigated rather than automatically removed because unusual measurements may represent genuine biological variation.

### 5. Exploratory Data Analysis (EDA)
- Species distribution analysis.
- Numerical feature distribution analysis.
- Sepal length versus sepal width.
- Petal length versus petal width.
- Pairplot for feature relationships.
- Correlation heatmap.
- Species-wise statistical comparison.

### 6. Data Preprocessing
- Separated independent and dependent variables.
- Encoded categorical target labels.
- Split data into training and testing sets.
- Applied StandardScaler.
- Applied MinMaxScaler as an alternative scaling technique.

### 7. Data Export
- Exported the cleaned dataset into CSV format.
- Prepared the dataset for subsequent Machine Learning experiments.

## 📊 Key Analytical Findings

Based on the uploaded dataset:

### Species Distribution

| Species | Observations |
|---|---:|
| Iris-setosa | 50 |
| Iris-versicolor | 50 |
| Iris-virginica | 50 |

The dataset is balanced across all three species.

### Average Flower Measurements

| Species | Sepal Length | Sepal Width | Petal Length | Petal Width |
|---|---:|---:|---:|---:|
| Setosa | 5.01 | 3.42 | 1.46 | 0.24 |
| Versicolor | 5.94 | 2.77 | 4.26 | 1.33 |
| Virginica | 6.59 | 2.97 | 5.55 | 2.03 |

*Measurements are in centimeters.*

### Correlation Insights

- Petal length and petal width have a strong positive correlation (approximately 0.963).
- Sepal length and petal length also have a strong positive correlation (approximately 0.872).
- Sepal width has a weaker negative correlation with petal length (approximately -0.421).

These relationships indicate that petal measurements are particularly informative for distinguishing Iris species.

## 📈 Visualizations

The project includes:

1. Species distribution countplot.
2. Feature distribution histograms.
3. Sepal measurement scatterplot.
4. Petal measurement scatterplot.
5. Pairplot of numerical features.
6. Feature correlation heatmap.
7. Species-wise average measurement comparison.
8. Outlier detection boxplots.

## 📁 Repository Structure

```text
Iris-Data-Analysis/
│
├── datasets/
│   ├── Iris.csv
│   └── Iris_Cleaned.csv
│
├── notebooks/
│   └── Iris_Data_Analysis.ipynb
│
├── visualizations/
│   ├── species_distribution.png
│   ├── feature_distributions.png
│   ├── pairplot.png
│   ├── correlation_heatmap.png
│   └── species_comparison.png
│
├── README.md
└── requirements.txt
```

## ⚙️ Installation and Usage

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project

```bash
cd Iris-Data-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Navigate to:

`notebooks/Iris_Data_Analysis.ipynb`

Run the notebook cells sequentially.

## 📚 Learning Outcomes

Through this project, I practised:

- Working with structured datasets using Pandas.
- Data inspection and validation.
- Handling missing values and duplicates.
- Numerical and categorical data preprocessing.
- Statistical analysis and outlier detection.
- Exploratory Data Analysis.
- Data visualization using Matplotlib and Seaborn.
- Feature scaling and target encoding.
- Preparing datasets for classification problems.

## 🚀 Future Improvements

- Implement Logistic Regression.
- Train Decision Tree and Random Forest classifiers.
- Experiment with K-Nearest Neighbors.
- Compare model performance using classification metrics.
- Perform cross-validation.
- Build an interactive dashboard for Iris data exploration.

## 👨‍💻 Author

**Upendra Kumar Yadav**

B.Tech – Computer Science Engineering

Interested in Data Science, Machine Learning, Data Analytics, and Artificial Intelligence.

---

*This project is part of my continuous Data Science learning journey, where I practise transforming raw datasets into meaningful analytical insights.*
## 📊 Visualizations

### Species Distribution
![Species Distribution](visualizations/species_distribution.png)

### Feature Distributions
![Feature Distributions](visualizations/feature_distributions.png)

### Sepal Comparison
![Sepal Comparison](visualizations/sepal_comparison.png)

### Petal Comparison
![Petal Comparison](visualizations/petal_comparison.png)

### Pairplot
![Pairplot](visualizations/pairplot.png)

### Correlation Heatmap
![Correlation Heatmap](visualizations/correlation_heatmap.png)

### Species Comparison
![Species Comparison](visualizations/species_comparison.png)