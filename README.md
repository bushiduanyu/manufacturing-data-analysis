# Manufacturing Defect Analysis with Python

This is a beginner Python-based engineering analytics project focused on manufacturing quality and defect analysis. The project uses a synthetic manufacturing dataset to practice reading, exploring, visualizing, and interpreting production-related data using Python.

## Project Goal

The goal of this project is to explore how production, quality, maintenance, downtime, supplier, inventory, and workforce-related variables may relate to defect rates in a manufacturing environment.

This project is part of my summer learning plan to build stronger engineering analytics skills as a mechanical engineering student exploring the intersection of manufacturing systems, data analysis, and industrial engineering.

## Dataset

The dataset is a synthetic manufacturing dataset created for educational purposes. It includes variables related to:

- Production volume
- Production cost
- Supplier quality
- Delivery delay
- Defect rate
- Quality score
- Maintenance hours
- Downtime percentage
- Inventory turnover
- Stockout rate
- Worker productivity
- Safety incidents
- Energy consumption
- Additive manufacturing process time
- Defect status

Because the dataset is synthetic, the findings should be interpreted as practice-based exploratory analysis rather than real-world factory conclusions.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook
- GitHub

## Current Progress

- Set up Python environment using Anaconda
- Created a GitHub repository for the project
- Completed an initial pandas and matplotlib practice notebook using a small sample machine dataset
- Loaded the manufacturing defect dataset into Jupyter Notebook
- Used `df.head()` to preview the dataset
- Used `df.info()` to inspect column names, data types, and missing values
- Used `df.describe()` to generate summary statistics
- Created the first round of exploratory visualizations:
  - DefectStatus count
  - DefectRate distribution
  - DefectRate vs QualityScore
  - DefectRate vs DowntimePercentage

## Initial Findings

1. The `DefectStatus` count shows the number of low-defect and high-defect records in the dataset.

2. The `DefectRate` histogram shows the overall distribution of defect rates across production records.

3. The scatter plot between `QualityScore` and `DefectRate` does not show a clear linear pattern, suggesting that quality score alone may not fully explain defect rate.

4. The scatter plot between `DowntimePercentage` and `DefectRate` appears widely dispersed, suggesting that downtime percentage alone may not be a strong visual predictor of defect rate.

5. The first EDA suggests that defect rate may be related to multiple factors rather than a single variable. Future analysis will compare grouped averages by `DefectStatus` and explore additional variables such as supplier quality, maintenance hours, delivery delay, and worker productivity.

## AI Assistance Disclosure

I used AI tools as a learning assistant to help:

- Explain pandas and matplotlib code line by line
- Understand the purpose of `df.head()`, `df.info()`, `df.describe()`, `value_counts()`, histograms, and scatter plots
- Interpret why scatter plots may appear dispersed
- Draft clear and honest README wording
- Organize the project into beginner-friendly steps

All code was run and checked in Jupyter Notebook, and the project findings are based on my own review of the outputs.

## Next Steps

- Compare average values by `DefectStatus`
- Explore supplier quality, delivery delay, maintenance hours, and worker productivity
- Create additional visualizations
- Save figures into the `figures/` folder
- Continue documenting the project clearly on GitHub
