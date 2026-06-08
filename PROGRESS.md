# Project Progress Log

This file tracks weekly progress for my Manufacturing Defect Analysis project. The purpose is to document what I completed, what I learned, and what I plan to improve next.

## Week 1: Project Setup and First EDA

### Completed
- Set up Python environment using Anaconda and Jupyter Notebook
- Created the GitHub repository for the project
- Loaded the synthetic manufacturing defect dataset into pandas
- Used `df.head()`, `df.info()`, and `df.describe()` to inspect the dataset
- Created initial EDA visualizations:
  - DefectStatus count
  - DefectRate distribution
  - DefectRate vs QualityScore
  - DefectRate vs DowntimePercentage
- Updated README with project goal, dataset description, first findings, and AI assistance disclosure

### Key Knowledge Learned
- `df.head()` previews the first rows of a dataset
- `df.info()` shows columns, data types, and missing-value information
- `df.describe()` gives summary statistics for numerical columns
- `value_counts()` counts categories in a column
- Histograms show the distribution of one numerical variable
- Scatter plots help explore relationships between two variables
- A messy scatter plot can still be a valid finding if no clear pattern appears

### Reflection
The first EDA showed that `QualityScore` and `DowntimePercentage` alone do not clearly explain `DefectRate`. This suggests that defect rate may be related to multiple production, quality, maintenance, and workforce factors.

### Next Steps
- Compare grouped averages by `DefectStatus`
- Create grouped bar charts for key variables
- Continue documenting findings carefully without overstating causation


