# 🏏 IPL Data Analysis (2008–2024)

## 📌 About This Project

An exploratory data analysis of IPL cricket data spanning 17 seasons,
uncovering patterns in team performance, player statistics, venue
scoring trends, and seasonal evolution of the game.

## ❓ Questions Explored

1. Which team has won the most IPL matches overall?
2. Does winning the toss help win the match?
3. Who are the top 10 run scorers in IPL history?
4. Which venues produce the highest average first innings scores?
5. How has average match scoring changed across seasons (2008–2024)?

## 🛠️ Tools & Libraries Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 💡 Key Findings

- Mumbai Indians are the most successful IPL team with 144 wins
- Winning the toss provides no significant advantage — only 38%
  of toss winners go on to win the match
- Virat Kohli dominates IPL run scoring with 8014 total runs —
  over 1200 runs ahead of second place
- M Chinnaswamy Stadium records the highest average first innings
  score of 173 runs across 94 matches
- IPL average match scores have increased dramatically from 309
  runs in 2008 to 365 runs in 2024 — driven by rule changes
  and batting technology improvements

## 📁 Project Structure

ipl-analysis/
│
├── data/
│ ├── matches.csv
│ └── deliveries.csv
│
├── ipl_analysis.ipynb
├── .gitignore
└── README.md

## 📊 Dataset

- Source: Kaggle — IPL Complete Dataset (2008–2024)
- matches.csv — match level data (1095 matches)
- deliveries.csv — ball by ball data (~180,000 deliveries)
