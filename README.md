<<<<<<< HEAD
# 🏏 IPL 2022 Match Analysis — Exploratory Data Analysis
=======
🏏 Turns out winning the toss in IPL 2022 was basically a coin flip when it came to actually winning the match. Here's what I found analyzing all 74 games of the season.
>>>>>>> 2e96e5e (Update IPL analysis and README)

📊 About the project:
Dataset of all 74 matches from IPL 2022, covering toss results, innings scores, match winners, margins, Player of the Match, top scorers, and best bowling figures — 20 features in total, no missing data or duplicates.

🛠️ Tools used:
Python, Pandas & NumPy for cleaning and aggregation, Matplotlib & Seaborn for visualization.

💡 Key insights:

<<<<<<< HEAD
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

IPL-Match-Analysis-EDA/
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
Gujarat topped the standings with **12 wins**, followed by Rajasthan (10), and Bangalore and Lucknow (9 each). Chennai and Mumbai struggled, with only **4 wins each** — a sharp fall from their usual form.

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
git clone https://github.com/Satyajeet745/IPL-Match-Analysis-EDA.git
cd IPL-Match-Analysis-EDA
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

## 🔮 Future Improvements

- Add team-vs-team head-to-head breakdown
- Bring in ball-by-ball data for deeper player analysis
- Build an interactive dashboard (Plotly / Streamlit)

## 🙋‍♂️ Author

Made with 🏏 and Python by **Satyajeet**
GitHub: [Satyajeet745](https://github.com/Satyajeet745)

=======
1️⃣ Toss ≠ advantage
The toss winner won the match only 48.6% of the time (36/74 games) — statistically no better than a coin flip.

2️⃣ Everyone wanted to chase, but it didn't matter
Teams chose to field first after winning the toss 59 out of 74 times. Yet wins were split exactly 50/50 between defending (37) and chasing (37) — the "chase advantage" wasn't real in 2022.

3️⃣ Big drop for the usual heavyweights
Gujarat topped the table with 12 wins, while Chennai and Mumbai — historically two of the strongest franchises — each managed only 4.

4️⃣ One batter, way ahead of the pack
Jos Buttler scored 651 runs across his top-scoring innings — nearly double the next best, Quinton de Kock (377).

5️⃣ Most consistent match-winner
Kuldeep Yadav led all players with 4 Player-of-the-Match awards for the season.

6️⃣ Venues were concentrated, not spread out
All 74 matches were played across just 6 venues in Maharashtra, Kolkata & Ahmedabad. Wankhede Stadium, Mumbai hosted the most — 21 matches.

This was a great exercise in asking the data real questions instead of just making charts — especially the toss vs. win-rate finding, which challenged my assumption going in.

🔗 Full code, charts & write-up on GitHub: [https://github.com/Satyajeet745/IPL-Match-Analysis-EDA]

📝 This is one of my early data analysis projects, and I'm actively looking to improve — if you spot something I could've analyzed differently, a metric I missed, or better ways to present this, please drop it in the comments. Genuinely appreciate any feedback, big or small!

#Python #DataAnalysis #EDA #IPL2022 #Pandas #Matplotlib #Seaborn #DataScience #Cricket #SportsAnalytics

