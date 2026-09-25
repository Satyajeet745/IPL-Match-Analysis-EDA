# 🏏 IPL 2022 Match Analysis — Exploratory Data Analysis

An EDA project on the **IPL 2022 season**, digging into 74 matches to understand team performance, toss trends, winning margins, and standout players — using Python, Pandas, Matplotlib, and Seaborn.

## 📌 Overview

This project explores match-level data from the 2022 Indian Premier League season to answer questions like:

- Which teams won the most matches?
- Does winning the toss actually help you win the match?
- Do teams win more often by defending a total (runs) or chasing (wickets)?
- Who were the standout batters, bowlers, and Player-of-the-Match winners?
- Which venues hosted the most games?

## 📊 Dataset

The dataset (`IPL.csv`) contains **74 matches** and **20 columns**:

| Column | Description |
|---|---|
| `match_id`, `date`, `venue`, `stage` | Match metadata |
| `team1`, `team2` | Teams competing |
| `toss_winner`, `toss_decision` | Toss result and decision (bat/field) |
| `first_ings_score`, `first_ings_wkts` | 1st innings score & wickets |
| `second_ings_score`, `second_ings_wkts` | 2nd innings score & wickets |
| `match_winner`, `won_by`, `margin` | Result of the match |
| `player_of_the_match` | Player awarded POTM |
| `top_scorer`, `highscore` | Top run-scorer of the match & their score |
| `best_bowling`, `best_bowling_figure` | Best bowler of the match & figures |

No missing values or duplicate rows were found in the dataset.

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** – data loading, cleaning, aggregation
- **NumPy** – numerical operations
- **Matplotlib** & **Seaborn** – visualization

## 📁 Project Structure

IPL-Match-Analysis/
├── IPL_Match_Analysis.ipynb # Main analysis notebook
├── IPL.csv # Dataset
└── README.md # Project documentation


## 🔍 Analysis Performed

1. Initial data inspection (shape, dtypes, nulls, duplicates)
2. Most match wins by team
3. Toss decision trends (bat vs field)
4. Toss winner vs. match winner
5. How teams win — by runs vs. by wickets
6. Most Player-of-the-Match awards
7. Top 5 run-scorers of the tournament
8. Top 5 bowling performances
9. Most-used venues

## 💡 Key Insights

**1. Team Performance**
Gujarat topped the standings with **12 wins**, followed by Rajasthan (10), and Bangalore and Lucknow (9 each). Chennai and Mumbai struggled, with only **4 wins each** — a sharp fall from their usual form in past seasons.

**2. Toss Decision**
Teams overwhelmingly chose to **field first** after winning the toss — **59 of 74 times (79.7%)**, versus only 15 choosing to bat. This points to chasing-friendly conditions across the season.

**3. Toss Winner vs. Match Winner**
Despite that strong preference, winning the toss barely translated into winning the match: the toss winner won only **36 of 74 games (48.6%)** — essentially a coin flip.

**4. How Matches Were Won**
Wins were split **exactly evenly — 37 by runs, 37 by wickets** — showing neither batting first nor chasing had a real structural edge this season.

**5. Player of the Match**
**Kuldeep Yadav** led with **4 POTM awards**, ahead of Jos Buttler (3), and Umesh Yadav, Quinton de Kock, and David Miller (2 each).

**6. Top Run-Scorers**
**Jos Buttler** was in a league of his own — **651 runs** across his top-scoring innings, nearly double the next best: Quinton de Kock (377), KL Rahul (351), Shubman Gill (288), and Faf du Plessis (257).

**7. Venues**
All matches were played across just **6 venues in Maharashtra, Kolkata, and Ahmedabad** (a neutral-venue format that season). **Wankhede Stadium, Mumbai** hosted the most matches — **21** — followed by Dr DY Patil Sports Academy (20) and Brabourne Stadium (16).

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/IPL-Match-Analysis.git
cd IPL-Match-Analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook IPL_Match_Analysis.ipynb
```

## 📈 Sample Visuals

The notebook includes bar charts and count plots for:
- Most match wins by team
- Toss decision trends
- Toss winner vs. match winner outcome
- Wins by runs vs. wickets
- Top 5 batters and bowlers
- Most-used venues

#



---
