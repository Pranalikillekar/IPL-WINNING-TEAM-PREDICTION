# 🏏 IPL Win Predictor & Match Analysis

This project uses machine learning and data visualization to analyze Indian Premier League (IPL) matches and predict outcomes based on live match data. It also includes rich visual insights into team and player performances using historical datasets.

## 📊 Features

- **Win Prediction Model** based on match progression using Logistic Regression
- **Match Progression Plots**: Win probability, runs, and wickets over time
- **Player Stats**: Top batsmen by average and strike rate
- **Team Insights**: Home vs Away win comparison, total wins per team
- Data cleaning, feature engineering, and model training using real match data

## 📁 Project Structure

```bash
.
├── ipl.py                             # Main ML pipeline and visualizations
├── matches.csv                        # Match-level data
├── deliveries.csv                     # Ball-by-ball data
├── most_runs_average_strikerate.csv  # Player batting stats
├── teamwise_home_and_away.csv        # Home vs Away performance
├── teams.csv                          # Team info
├── Players.xlsx                       # Player master data
├── pipe.pkl                           # Trained model
├── README.md                          # Project documentation
