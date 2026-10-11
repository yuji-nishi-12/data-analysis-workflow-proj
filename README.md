# End-to-End Data Analysis Workflow

## Authors
- Yuji Nishi (school email: yuji.nishi@sjsu.edu | GitHub username: yuji-nishi-12)

## Project Description
This project is an end-to-end data analysis workflow that takes a real-world dataset from raw data into structured insights. I will audit and clean the data while documenting every cleaning decision and use descriptive statistics and inferential analysis to identify meaningful patterns. I will then build a set of static visualizations to tell a clear story, with attention to chart choice, colorblind accessibility, and potential bias. After this, I will turn my findings into an interactive dashboard to allow users to filter and explore the data on their own. Then finish off the project with a written report and presentation of my findings.

## Project Outline/Plan

### Interface Plan
* **Analysis environment:** Jupyter Notebooks (Python) for the full workflow.
* **Statistic visualization:** Matplotlib and seaborn charts.
* **Interactive dashboard:** Plotly dashboard exported as a standalone HTML file.
* **Repository layout:**
- `notebooks`: analysis and visualization notebooks.
- `code`: Python scripts (e.g., data loading, helper functions).
- `data`: local data files ignored by git.

### Data Collection and Storage Plan
* Get a dataset from a publicly available source and record the dataset name, source URL, description, and a data dictionary that describes every column.
* Download the dataset if it requires downloading; if not, use the dataset URL, and ensure raw data files are kept out by `.gitignore`.
* Store the raw data separately in a directory called `data/raw`, while the cleaned version goes in `data/processed`.
* Run an initial quality audit before making any changes, such as counting rows and columns, data types, missing values, duplicates, and outliers.

### Data Analysis and Visualization Plan
* Document every cleaning decision (what was changed and why), so that the cleaning process is transparent.
* **Descriptive statistics:** Compute summary statistics (e.g., mean, median, min, max, mode) and examine the relationships between variables.
* **Inferential analysis:** Run at least one statistical test (e.g., t-test, ANOVA, chi-square test) and interpret the result.
* **Static visualization:** Create at least 5 charts that show a narrative. Justify each chart type and use a colorblind-friendly palette with clear labels and titles.
* **Interactive dashboard:** Build a Plotly dashboard with hover details, filters, and zoom features so users can explore the data. Gather feedback from peers and revise the dashboard based on their comments.
* **Optional:** Add a machine learning model for prediction, evaluating it properly.
