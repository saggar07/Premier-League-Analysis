# Top Goal Scorers Analysis
## Project Overview

This project analyzes football player performance using a structured dataset to identify and visualize the top goal scorers across different clubs. The analysis focuses on data cleaning, aggregation, ranking, and visualization to highlight the most impactful players and present insights through a clean, publication-ready chart.

View my notebook with detailed steps here: [most goals for their club.ipynb]()
[Run on Colab](https://colab.research.google.com/github/saggar07/Premier-League-Analysis/blob/main/Top-Scorers/most-goals-for-their-club.ipynb)


## 1. Workflow Description
Importing Libraries and Loading the Dataset

The notebook begins by importing essential Python libraries required for data analysis and visualization. Pandas and NumPy are used for data manipulation, Seaborn and Matplotlib for visual analysis, ast for handling structured data where required, and datetime for date-related operations.
The dataset is loaded from a local CSV file into a Pandas DataFrame. Missing values are handled by replacing them with zeros to maintain consistency, and the Age column is explicitly converted to an integer data type. These preprocessing steps ensure the dataset is clean and ready for analysis.

## 2. Identifying Top Goal Scorers by Club

To determine standout performers, the notebook groups the dataset by Club and selects the player with the highest number of goals from each club using idxmax(). The resulting records are then sorted in descending order based on goals scored. From this list, the top 10 players overall are selected, and only relevant columns (Name, Goals, Club) are retained. The index is reset to improve clarity and presentation.

## 3. Visualizing Top Goal Scorers

For effective comparison, the notebook visualizes the top scorers using a horizontal bar chart created with Seaborn. A clean darkgrid theme is applied for readability, and players’ last names are extracted to create concise x-axis labels.
A custom color palette is used to differentiate clubs clearly, and bars are outlined for better visual separation. Each bar is annotated with the exact number of goals scored, allowing viewers to quickly interpret player performance.
<img width="519" height="377" alt="image" src="https://github.com/user-attachments/assets/0548c0ec-956d-437d-bc55-18cad2ccf01f" />

## 4. Enhancing Plot Styling and Readability

Additional styling is applied to produce a polished, professional visualization. Axis labels are formatted with appropriate font sizes and styles, and x-axis labels are rotated to prevent overlap. Unnecessary plot spines are removed to create a clean look, and the legend is customized with clear labeling and improved contrast. Layout adjustments are applied to ensure proper spacing before rendering the final chart.
<img width="1184" height="584" alt="image" src="https://github.com/user-attachments/assets/ab72fd61-bbec-42e1-91ea-de07ea55cbfc" />

## Key Insights

Identifies the top goal scorer from each club and ranks them by total goals scored.

Highlights the top 10 active players based on goal contribution to their teams.

Uses clean and well-annotated visualizations to make performance comparisons intuitive and easy to understand.
