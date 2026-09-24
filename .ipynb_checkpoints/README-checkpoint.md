# 🏏 IPL Match Analysis & EDA

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA) on IPL 2022 match data** to understand team performance, toss results, match outcomes, player performances, winning methods, and venue-wise trends.

The project uses Python-based data analysis and visualization techniques to transform raw IPL match data into meaningful insights.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze team-wise match wins
- Study the relationship between the toss winner and match winner
- Analyze toss decisions
- Identify top-performing players
- Analyze winning margins and winning methods
- Analyze match distribution across venues
- Compare team performance across different venues
- Identify important patterns and trends in IPL matches

---

## 📊 Dataset

The dataset contains IPL 2022 match-level information.

### Dataset Features

| Column | Description |
|---|---|
| `match_id` | Unique match identifier |
| `date` | Date of the match |
| `venue` | Stadium where the match was played |
| `team1` | First participating team |
| `team2` | Second participating team |
| `stage` | Tournament stage |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Decision taken after winning the toss |
| `first_ings_score` | First innings score |
| `first_ings_wkts` | Wickets lost in first innings |
| `second_ings_score` | Second innings score |
| `second_ings_wkts` | Wickets lost in second innings |
| `match_winner` | Team that won the match |
| `won_by` | Method of victory |
| `margin` | Winning margin |
| `player_of_the_match` | Player receiving Player of the Match |
| `top_scorer` | Top scorer of the match |
| `highscore` | Highest individual score |
| `best_bowling` | Best bowling performer |
| `best_bowling_figure` | Best bowling figure |

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data cleaning and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Analysis environment

---

## 🔍 Analysis Performed

### 1. Team Performance
Analyzed the number of matches won by each team to compare overall team performance.

### 2. Toss Analysis
Studied:
- Toss-winning teams
- Toss decisions
- Relationship between toss winner and match winner

### 3. Match Winning Analysis
Analyzed:
- Teams with the most wins
- Winning methods
- Winning margins

### 4. Player Performance
Analyzed:
- Player of the Match awards
- Top scorers
- Highest individual scores
- Best bowling performances

### 5. Venue Analysis
Analyzed:
- Number of matches played at each stadium
- Team wins at different venues
- Venue-wise team performance

---

## 📈 Visualizations

The project includes visualizations such as:

- Team-wise match wins
- Toss decision distribution
- Toss winner vs match winner
- Winning methods
- Player of the Match analysis
- Top scorer analysis
- Venue-wise match distribution
- Venue-wise team wins
- Batting and bowling performance analysis

---

## 💡 Key Insights

Some important observations from the analysis include:

- Winning the toss does not always result in winning the match.
- Match wins are distributed differently among teams.
- Teams use different strategies after winning the toss.
- Certain players had a higher number of Player of the Match awards.
- Match distribution varies across venues.
- Venue-wise analysis provides additional insight into team performance.

---

## 📁 Project Structure

```text
IPL-Match-Analysis-EDA/
│
├── IPL.csv
├── IPL_Match_Analysis.ipynb
├── README.md
└── .gitignore