# Temperature Analysis with PySpark

This project is a small exercise to review and learn about PySpark by analyzing global temperature data. The dataset used in this project is sourced from [Redivis](https://redivis.com/datasets/1e0a-f4931vvyg/tables).

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
- [Results](#results)

## Introduction

This project demonstrates how to use PySpark for data analysis and visualization. It covers the following steps:
1. Creating a SparkSession
2. Loading and exploring the dataset
3. Data cleaning
4. Descriptive statistics
5. Data visualization

## Dataset

The dataset used in this project contains global temperature records. It can be found [here](https://redivis.com/datasets/1e0a-f4931vvyg/tables).

## Setup

To run this project, you need to have the following installed:
- Python 3.x
- PySpark
- Pandas
- Matplotlib
- Seaborn

You can install the required packages using pip:
```bash
pip install pyspark pandas matplotlib seaborn
```

## Usage

1. Clone the repository:
```bash
git clone https://github.com/huylys54/Simple-PySpark.git
cd temperature-analysis
```

2. Place the dataset file (`global_temperatures.csv`) in the `data` directory.

3. Run the Jupyter Notebook:
```bash
jupyter notebook temperature_analysis.ipynb
```

## Analysis Steps

1. **Create SparkSession**: Initialize a SparkSession to use PySpark.
2. **Load and Explore Dataset**: Load the dataset and explore its schema and sample records.
3. **Data Cleaning**: Handle missing values by dropping rows with null values.
4. **Descriptive Statistics**: Generate summary statistics for the dataset.
5. **Data Visualization**: Visualize the data using Matplotlib and Seaborn.

## Results

The analysis includes the following visualizations:
- Average temperature by year
- Top 20 average temperatures by country
- Temperature and uncertainty by year
- Rolling average of temperature
- Average temperature difference by year
- Filtered data after the year 1980
