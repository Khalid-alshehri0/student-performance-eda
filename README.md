# Student Performance EDA

This repository contains an Exploratory Data Analysis (EDA) project on the "Students Performance" dataset (from Kaggle). The analysis was done using Python and Google Colab and includes data cleaning, descriptive statistics, and visualizations to explore relationships between students' demographic attributes and their exam scores.

## Project structure

- Exploratory_Data_Analysis_(EDA)_on_Student_Performance_Dataset.ipynb  - Main Colab notebook with the EDA
- StudentsPerformance.csv - Dataset used in the analysis
- README.md - This file

## Dataset

- Source: Kaggle (Students Performance in Exams)
- File: StudentsPerformance.csv

Columns used:
- gender
- race/ethnicity
- parental level of education
- lunch
- test preparation course
- math score
- reading score
- writing score

## What this project does

- Load and clean the dataset (fix formatting issues and column names)
- Provide summary statistics and check for missing values
- Visualize distributions and relationships, e.g.:
  - Distribution of math scores
  - Math scores by gender
  - Relationship between reading and writing scores
- Draw simple insights about factors affecting student performance

## How to run

Option 1 — Open in Google Colab (recommended):
1. Open `Exploratory_Data_Analysis_(EDA)_on_Student_Performance_Dataset.ipynb` in Colab.
2. Upload `StudentsPerformance.csv` to the Colab session (or mount Drive) if not already present.
3. Run the notebook cells in order.

Option 2 — Run locally:
1. Create a virtual environment and install dependencies:
   pip install pandas numpy matplotlib seaborn
2. Start Jupyter and open the notebook:
   jupyter notebook
3. Make sure `StudentsPerformance.csv` is in the notebook working directory and run the cells.

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn

## Key findings (brief)

- Reading and writing scores are strongly correlated.
- Female students tend to score higher in reading and writing in this dataset.
- Test preparation completion is associated with slightly higher scores on average.

## Notes and suggestions

- The notebook contains steps used to fix an initial CSV formatting issue where the header row and data were read into a single column.
- You can expand the analysis by adding models, more demographic breakdowns, or interactive plots (Plotly / Altair).

## License

This repository is provided for learning purposes. Feel free to reuse or adapt the notebook and code.
