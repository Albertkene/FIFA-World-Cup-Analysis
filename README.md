# Goals Scored in International Soccer: Women vs Men

# Project Overview
As a sports journalist specializing in soccer analysis, this project investigates whether more goals are scored in women's international soccer matches compared to men's. Based on long-term observation of international competitions, this analysis applies statistical hypothesis testing to validate or refute this assumption using historical match data.

# Research Question
Are more goals scored in women's international soccer matches than in men's?

# Hypotheses
The following statistical hypotheses were tested at a **10% significance level (α = 0.10):**

- Null Hypothesis (H₀):
  The mean number of goals scored in women's international soccer matches is equal to that of men's.

- Alternative Hypothesis (H₁):
  The mean number of goals scored in women's international soccer matches is greater than that of men's.

# Dataset Description
Two datasets were used in this analysis, containing results of every official international soccer match since the 19th century:

- `women_results.csv` — Women's international match results  
- `men_results.csv` — Men's international match results  

To ensure fairness and relevance, the analysis was limited to:
- Official FIFA World Cup matches only (excluding qualifiers)
- Matches played from January 1, 2002 onward

This restriction accounts for changes in the sport over time and ensures comparability across tournaments.

# Methodology
The analysis followed these steps:
1. Data loading and inspection
2. Filtering matches to FIFA World Cup games since 2002
3. Calculation of total and average goals per match
4. Statistical hypothesis testing to compare mean goals scored
5. Interpretation of results based on the chosen significance level

# Tools & Technologies
- Python
- Pandas
- Statistical hypothesis testing

# Conclusion
This project demonstrates how data-driven analysis and statistical testing can be used to investigate commonly held assumptions in sports journalism, providing evidence-based insights into goal-scoring patterns in international soccer.

📌 *This project was completed as part of my data analytics learning journey.*