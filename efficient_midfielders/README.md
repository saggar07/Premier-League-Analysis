# Midfielder Performance & Efficiency Analysis
## Project Overview

This project analyzes football midfielders’ performance to identify the most efficient players across key creative and playmaking metrics. Using a combination of data preprocessing, normalization, ranking, and visualization, the project highlights top performers and presents insights through a radar chart for easy comparison.

View my notebook with detailed steps here: [efficient midfielders.ipynb]()
## 1. Workflow Description
Importing Libraries and Preparing the Dataset

The notebook begins by importing essential Python libraries:

Pandas and NumPy for data manipulation

Seaborn and Matplotlib for visualization

scikit-learn’s MinMaxScaler for data normalization

The dataset is loaded from a local CSV file, missing values are replaced with zeros, and key numerical columns (Age, Interceptions, Clean sheets, Duels won, Jersey Number) are converted to integers. These preprocessing steps ensure a clean, structured dataset ready for analysis.

## 2. Filtering Midfielders and Selecting Key Performance Metrics

The analysis focuses on midfielders, selecting metrics most relevant to their role:
Assists, Passes per match, Big chances created, Through balls, and Accurate long balls. This subset allows for targeted analysis on creativity and playmaking contributions, which are crucial for midfield performance evaluation.

## 3. Normalizing Performance Metrics and Calculating Efficiency Score

To compare metrics fairly, Min-Max normalization is applied to scale all performance attributes between 0 and 1. An Efficiency Score is computed for each player by averaging the normalized metrics, providing a single, interpretable measure of overall midfielder effectiveness.

<img width="505" height="296" alt="image" src="https://github.com/user-attachments/assets/bab3daa2-37f6-47ef-9e9f-50b62deeab61" />

## 4. Identifying Top Performing Midfielders

Players are ranked based on their Efficiency Scores, and the top 7 midfielders are selected. This step objectively highlights the most well-rounded and impactful midfielders across multiple performance dimensions.

## 5. Mapping Efficiency Scores to Player Names

Player names are mapped back to the Efficiency Scores using index alignment from the original dataset. The final table sets player names as the index, creating a clean, readable output that associates each top-performing midfielder with their overall score.
<img width="1067" height="316" alt="image" src="https://github.com/user-attachments/assets/0a5f4306-5dc0-464d-8ab9-f6208a2837b2" />

## 6. Visualizing Midfielder Performance with a Radar Chart

A radar chart is created to visually compare the top midfielders across all selected metrics. Each axis represents one performance attribute, and player values are plotted after normalization. Distinct neon-inspired colors and layered transparency enhance clarity and visual depth. The chart provides an intuitive view of relative strengths and weaknesses, highlighting overall performance profiles.

## 7. Enhancing Radar Chart with Titles and Legend

The radar chart is finalized with a descriptive, bold, italic title indicating Top 7 Efficient Midfielders. The legend is positioned outside the plot for clarity, listing each player with their corresponding color. Frame lines are removed for a clean aesthetic. These refinements produce a publication-ready visualization, suitable for GitHub, reports, or dashboards.
<img width="976" height="819" alt="image" src="https://github.com/user-attachments/assets/88c1beca-f17f-45cf-a0bf-fe8c19434abb" />

## Key Insights

Identifies the most efficient midfielders using a data-driven composite score.

Highlights relative strengths and weaknesses across critical creative and passing metrics.

Provides a visually intuitive radar chart for performance comparison.
