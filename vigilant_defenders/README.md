# Defenders Performance Analysis
## Project Overview

This project analyzes football defenders’ performance to identify the top performers across key defensive metrics. Using a combination of data preprocessing, filtering, ranking, and visualization, the project highlights defenders excelling in Interceptions, Clean Sheets, and Duels Won, and presents insights through glow-enhanced horizontal bar charts.

View my notebook with detailed steps here:
[Run on Colab](https://colab.research.google.com/github/saggar07/Premier-League-Analysis/blob/main/defensive_stats.ipynb)

## 1. Workflow Description
Importing Libraries and Preparing the Dataset

Essential Python libraries are imported:

Pandas and NumPy for data manipulation

Seaborn and Matplotlib for visualization

datetime for date handling

The dataset is loaded from a CSV file, missing values are replaced with zeros, and key numerical columns (Age, Interceptions, Clean sheets, Duels won) are converted to integers. This ensures a clean, structured dataset ready for analysis.

## 2. Filtering Defenders

The dataset is filtered to include only players with Position labeled as 'Defender'. This focuses the analysis on metrics relevant to defensive performance.

## 3. Identifying Top Interceptors

The notebook identifies defenders with the highest number of interceptions. By grouping data by Name and selecting the maximum Interceptions per player, the top 5 defenders are ranked. This metric highlights players excelling at intercepting the ball.
<img width="465" height="207" alt="image" src="https://github.com/user-attachments/assets/ce438b18-0a82-4db9-9272-8c7dcb81b10b" />

## 4. Identifying Defenders with Most Clean Sheets

Defenders are evaluated based on Clean Sheets, indicating the number of matches in which no goals were conceded. The top 5 defenders are identified by selecting the maximum Clean Sheets per player. This metric emphasizes team defensive stability associated with each player.

<img width="514" height="219" alt="image" src="https://github.com/user-attachments/assets/777bcc12-5373-418d-94f2-e526ff08a32b" />


## 5. Identifying Defenders with Most Duels Won

The analysis examines Duels Won to evaluate one-on-one defensive effectiveness. By selecting the top 5 defenders based on maximum duels won per player, the notebook identifies those most successful in direct defensive challenges.
<img width="503" height="209" alt="image" src="https://github.com/user-attachments/assets/31806fb7-994a-4f81-bbb6-885aac4e782c" />

## 6. Visualizing Top Defensive Performers with Glow Bar Charts

A custom glow_barh function is used to create horizontal bar charts with a glowing effect for each defensive metric:

Green for Interceptions

Blue for Clean Sheets

Yellow for Duels Won

This visual enhancement highlights top performers while producing a visually engaging, portfolio-ready representation of defensive metrics.

## 7. Enhancing Defender Charts with Titles and Styling

Descriptive subplot titles (Interceptions, Clean Sheets, Duels Won) and a main figure title are added. Axis labels are removed for a clean look, grid lines improve readability, and unnecessary spines are hidden. Layout adjustments ensure proper spacing. These refinements produce a polished, professional visualization suitable for GitHub or portfolio display.
<img width="988" height="789" alt="image" src="https://github.com/user-attachments/assets/eac8cd83-e15d-4e6c-bcc0-53626deb7e5d" />

## Key Insights

Highlights the top-performing defenders in three critical defensive metrics.

Allows easy comparison of individual defensive effectiveness.

Provides a clean, engaging visualization that emphasizes recruiter-friendly storytelling.
