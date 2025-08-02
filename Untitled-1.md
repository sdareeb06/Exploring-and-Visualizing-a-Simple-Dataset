# Task 1: Exploring and Visualizing a Simple Dataset

## ✅ Objective
The goal of this task is to load, inspect, and visualize a simple dataset to understand its structure, trends, and feature distributions. This builds a foundation for data preprocessing and model-building tasks.

## 📊 Dataset
**Name**: Iris Dataset  
**Source**: Built-in Seaborn dataset (`sns.load_dataset("iris")`)  
**Description**: This dataset contains measurements of 150 iris flowers from three different species (Setosa, Versicolor, Virginica) across four features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

## 🧪 Steps Performed

### 1. Data Loading and Inspection
- Loaded the dataset using `seaborn.load_dataset()`
- Printed the shape, column names, and first 5 rows
- Used `.info()` and `.describe()` to understand data types and summary statistics

### 2. Data Visualization
- **Scatter Plot**: Compared sepal and petal lengths, colored by species
- **Histograms**: Showed distributions of each feature
- **Box Plots**: Identified potential outliers in numeric features

## 📌 Libraries Used
- **Pandas** for data handling
- **Matplotlib** and **Seaborn** for plotting

## 📈 Key Insights
- Petal length and sepal length show a clear distinction among species
- Setosa species has significantly different measurements from the other two
- Box plots help visualize the spread and detect potential outliers

## 🧠 Skills Gained
- Dataset loading and inspection using Pandas
- Basic data exploration and visualization
- Understanding feature distribution and correlation patterns

## 📁 Files Included
- `Task_1_Iris_Data_Exploration.ipynb`: Jupyter Notebook with full code and visualizations
- `README.md`: This file

---

✅ This task is complete and ready for submission to the internship repo.
