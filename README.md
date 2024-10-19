# Betting Odds Analysis Project

This project analyzes betting odds data from various bookmakers for Premier League matches during the 2023/2024 season. The objective is to determine which bookmaker consistently offers the best value odds for different match outcomes, such as Home Win, Away Win, Draw, Over 2.5 Goals, and Under 2.5 Goals.

## Project Overview

The analysis focuses on comparing the odds provided by different bookmakers (e.g., Bet365, BetVictor) to identify trends and determine which bookmaker offers the highest potential returns for bettors based on historical data. By performing data cleaning, exploratory data analysis, and visualizations, the project provides insights into the consistency and value of odds across markets.

## Files Included

- **betting_odds_analysis.ipynb**: Jupyter notebook containing the full analysis.
- **premier_league.csv**: The dataset used in the analysis, including odds from multiple bookmakers for Premier League matches.
- **boxplot_odds.png**: A visualization showing the distribution of odds across different bookmakers.
- **betting_odds_analysis.html**: An HTML version of the notebook for easy viewing without running the code.
- **requirements.txt**: A list of Python libraries and dependencies required to run the notebook.

## Data Source

The dataset used in this project was obtained from Football-data.co.uk (https://www.football-data.co.uk/englandm.php). It contains betting odds data for Premier League matches from various seasons and bookmakers.

## How to Run the Project

To run this project on your local machine, follow these steps:

1. **Clone the repository**:
git clone https://github.com/your-username/betting-odds-analysis.git

2. **Navigate  to the project directory**:
cd betting-odds-analysis

3. **Install the required dependencies**:
pip install -r requirements.txt

4. **Run the Jupyter notebook**:
jupyter notebook betting_odds_analysis.ipynb

5. **Open the notebook in Jupyter and run all the cells to reproduce the analysis and visualizations.**

Key Findings
------------
After analyzing the betting odds data, bookmaker PS was found to offer the highest value odds in most markets (Home, Away, Draw). However, the difference between bookmakers was marginal, indicating that no single bookmaker consistently provides a significantly better value than others across all markets.

Visualizations
-------------
The project generated several visualizations, including:

Boxplots: Used to detect outliers and understand the distribution of odds across different markets and bookmakers.
Line plots: Created to compare the average odds for each bookmaker in specific markets (Home, Away, Draw, Over 2.5, Under 2.5).
These visualizations helped identify which bookmakers tend to offer higher odds in various markets, providing insights for potential bettors.

Future Work
------------
Possible extensions of this project include:

Extending the analysis to other football leagues or other seasons.
Adding additional betting markets or comparing odds for different sports.
Performing more advanced statistical modeling to predict which bookmakers will offer the best odds in future events.

## Disclaimer
This project is for educational purposes only. The analysis and conclusions drawn are based on historical data and should not be used for real-world betting or financial decision-making. No guarantees or warranties are provided regarding the accuracy of the analysis or the data used.
