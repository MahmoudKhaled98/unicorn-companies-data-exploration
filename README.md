# Unicorn Companies Data Exploration

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a dataset of unicorn companies—companies valued at over one billion dollars. Through this analysis, we gain insights into the characteristics of these companies, such as when they were founded, how long it took them to achieve unicorn status, and their valuation trends.

By conducting various transformations, particularly on datetime data, we can explore trends and patterns related to company growth and the timeline for achieving unicorn status. Visualizations such as histograms, box plots, and bar plots help to reveal meaningful insights.

## Table of Contents

- [Introduction](#introduction)
- [Tools Used](#tools-used)
- [Project Structure](#project-structure)
- [EDA Steps](#eda-steps)
  - [Step 1: Imports](#step-1-imports)
  - [Step 2: Data Exploration](#step-2-data-exploration)
  - [Step 3: Time-to-Unicorn Visualization](#step-3-time-to-unicorn-visualization)
  - [Step 4: Results and Evaluation](#step-4-results-and-evaluation)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [References](#references)

## Introduction

Unicorn companies represent a fascinating segment of the business world, with their rapid rise to billion-dollar valuations. In this project, you will analyze a dataset of 1074 unicorn companies, exploring trends in company age, valuation, and time to achieve unicorn status.

The analysis aims to answer key questions:

- How long do companies take to achieve unicorn status?
- What are the valuation trends over time?
- How do different industries or regions affect these patterns?

## Tools Used

- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.
- **Seaborn**: For visualization.
- **Matplotlib**: For plotting graphs and charts.

## Project Structure

This Jupyter notebook is divided into the following sections:

- **Step 1: Imports**: Import relevant libraries.
- **Step 2: Data Exploration**: Explore dataset characteristics (e.g., structure, types, and uniqueness).
- **Step 3: Time-to-Unicorn Visualization**: Analyze the time it took companies to become unicorns.
- **Step 4: Results and Evaluation**: Visualize the trends over time and draw conclusions.

## EDA Steps

### Step 1: Imports
Import the necessary libraries, including Pandas, NumPy, Seaborn, and Matplotlib.

### Step 2: Data Exploration
Explore the dataset by:
- Displaying the first 10 rows.
- Identifying the number of rows and columns.
- Checking for duplicates.
- Identifying column data types.

### Step 3: Time-to-Unicorn Visualization
- Convert `Date Joined` to datetime format and create a `Years To Join` column.
- Analyze when companies gained unicorn status.
- Visualize trends over time using box plots and bar plots.

### Step 4: Results and Evaluation
- Visualize time-to-unicorn trends for different years.
- Compare quarterly trends in unicorn company valuation.

## Key Insights

- The median time for companies to reach unicorn status varies across months.
- More recent companies tend to become unicorns faster than older companies.
- 2021 saw the highest number of companies attaining unicorn status, especially in the first and second quarters.
- Valuations were generally higher in 2020 than in 2021 across all quarters.

## Conclusion

This project provides a comprehensive exploration of unicorn companies, offering valuable insights into their growth timelines and valuation patterns. The analysis reveals trends that can help investors make informed decisions about when and where to invest.

## How to Run

1. **Clone the repository**:

    ```bash
    git clone <https://MahmoudKhaled98@github.com/MahmoudKhaled98/unicorn-companies-data-exploration.git>
    ```

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:

    ```bash
    jupyter notebook
    ```

## References

- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
