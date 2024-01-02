# Project Analysis Notebook (updated)
## About the project
![image](https://github.com/tonminhce/data-analyst/assets/87883380/baf715be-e25d-40f5-b867-6bc682b16d3b)


## Feedback from the Profressor for this notebook
![image](https://github.com/tonminhce/data-analyst/assets/87883380/b95cc028-9c54-4505-968d-3f766d8051bb)


## Overview
This repository contains a Jupyter notebook (`final.ipynb`) that demonstrates an in-depth analysis of programming language data sourced from multiple CSV files. The notebook includes data loading, cleaning, merging, and detailed analysis, resulting in key findings regarding programming language activity and trends.

## Data
The data consists of several CSV files that encompass information on issues, pull requests, repositories, and programming languages. These files are processed and merged to create a comprehensive dataset for analysis.

## Notebook Contents

### Libraries
The following Python libraries are used in the project:
- `pandas`: for data manipulation and analysis
- `matplotlib.pyplot`: for creating visualizations
- `seaborn`: for statistical graphics
- `numpy`: for numerical processing

### Data Loading
CSV files are read into pandas DataFrames:
- `issues.csv`
- `prs.csv`
- `repos.csv`
- `languages.csv`

### Data Merging
Data from these DataFrames are merged based on common columns to create a single DataFrame for comprehensive analysis.

### Data Cleaning
Specific columns are dropped from the merged DataFrame, and data types are adjusted where necessary to ensure proper data representation.

## Findings from Analysis

### Finding 1: Top 10 Languages by Activity
The analysis determined the top 10 programming languages by the total number of pull requests and issues, highlighting the most actively used and contributed-to languages by the developer community.

### Finding 2: Growth Trends in Repositories
We observed growth trends among repositories over different time periods, which showed the adoption rates of various programming languages over time.

### Finding 3: Correlation between Issues and Pull Requests
The relationship between issues and pull requests was analyzed to understand how contributions in one area might relate to activity in the other across different languages.

### Finding 4: Impact of Language Features on Community Engagement
Our analysis sought to uncover if there's a connection between specific programming language features and the level of community engagement they receive.

### Finding 5: Language Popularity and Repository Statistics
The final part of our analysis looked at the popularity of programming languages in relation to repository statistics such as stars, forks, and watchers.

**Note**: For detailed figures, graphs, and discussions, please refer to the respective sections of the notebook.

## Usage
To run this notebook, make sure you have a Python environment with the necessary libraries installed. Clone this repository and execute the notebook in Jupyter to replicate the analysis.

## Contribute
Contributions to improve the notebook or extend the analysis are welcome. Please feel free to fork the repository and submit pull requests.

## Contact
If you have any questions or comments about this notebook, please open an issue in this repository.

---

**Reminder**: This notebook is for demonstration purposes only and is part of a larger data analysis project. The findings are based on the data available up to the last update and are subject to change with new data.
