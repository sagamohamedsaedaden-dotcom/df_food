# Saudi Arabia National Football Match Results

## Overview

This project explores the performance of Saudi Arabia national football match results, with a special focus on international matches from 2000 to 2025. It was developed to gain deeper insights into team trends and to better understand factors influencing success.

## Data Source

The analysis uses the publicly available "International Football Results from 1872 to 2025" dataset by Mart Jürisoo on Kaggle, containing match outcomes, scores, tournaments, venues, and goal details.

## The Questions

1. Who are the top goalscorers in Saudi Arabia?
2. How has Saudi Arabia’s goal scoring changed over time (2000–2025)?
3. Which year did Saudi Arabia score the highest number of goals in international matches?
4. In which tournaments did Saudi Arabia score the most goals?
5. What proportion of Saudi Arabia’s goals came from penalties?
6. Which factors (penalties, own goals, total goals, and year) are most strongly related to Saudi Arabia’s goal scoring?
7. Does Saudi Arabia have a home advantage when playing international matches?

## Tools Used

In exploring the performance of Saudi Arabia’s national football team through in-depth analysis, I relied on a robust set of tools:

- **Python**: Served as the core engine for processing data and uncovering key patterns.
  I incorporated these essential Python libraries:

  - **Pandas**: Enabled efficient data manipulation and exploration.
  - **Matplotlib**: Powered the creation of foundational data visualizations.
  - **Seaborn**: Elevated my charts with more sophisticated and polished graphics.

- **Jupyter Notebooks**: My interactive environment for executing code, blending scripts with inline commentary and results.

- **Visual Studio Code**: The primary editor where I wrote and ran my Python programs.

## The Analysis

Each query for this project aimed at investigating specific aspects of Saudi Arabia national football match results. Here’s how I approached each question:

View my notebook with detailed steps here:[football](football.ipynb)

### 1. Who are the top goalscorers in Saudi Arabia?

## Results

![Top 10 Goalscorers](images/Top_10_Goalscorers.png)

## Insights

- Mohammad Al-Sahlawi is the clear top goalscorer for Saudi Arabia since 2000, leading with 19 goals – 2 more than the second-placed player.
- The top 5 goalscorers (Al-Sahlawi, Al-Meshal, Al-Qahtani, Al-Dawsari, Al-Jaber) account for a significant portion of the team's goals, showing heavy reliance on a few key players.
- There is a sharp drop-off after the top 7 players (from 12 goals to 8), indicating limited depth in consistent goal-scoring talent during this period.

### 2. How has Saudi Arabia’s goal scoring changed over time (2000–2025)?

## Results

![Ksa Goals Trend](images\Ksa_Goals_Trend.png)

## Insights

- Saudi Arabia's goalscoring peaked dramatically in the early 2000s (around 2001–2002), reaching over 60 goals in a single year .
- After the early 2000s spike, there is a clear long-term downward trend, with average annual goals dropping significantly
- Since around 2010, scoring has become much more inconsistent and volatile , reflecting tougher competition

### 3. Which year did Saudi Arabia score the highest number of goals in international matches?

## Results

![Saudi Arabia Goals by Year](images\Saudi_Arabia_Goals_by_Year.png)

## Insights

- Saudi Arabia experienced a clear standout peak in goalscoring very early in the period, far higher than any other year, suggesting an exceptionally productive phase in the opening years.
- After that early high point, goal output settled into a noticeably lower and more consistent range for most of the following decade, indicating a shift to more restrained attacking production.
- In more recent years, scoring has shown greater year-to-year variability with occasional modest recoveries , reflecting changing competitive dynamics over time.

### 4. In which tournaments did Saudi Arabia score the most goals?

## Results

![tournaments](images/Tournament.png)

## Insights

- FIFA World Cup qualification dominates Saudi Arabia's goal tally, reflecting the high volume of matches and scoring opportunities in qualifiers.
- Gulf Cup ranks second, showing strong offensive performance in this regional competition.
- Qualifying tournaments overall account for the majority of goals, while final tournaments and Arab Cup contribute much less.

### 5. What proportion of Saudi Arabia’s goals came from penalties?

## Results

![Proportion of Saudi Arabia's Goals from Penalties](images/Saudi_Arabia_Penalty_Goals.png)

## Insights

- The vast majority of Saudi Arabia's goals in international matches come from open play or other non-penalty situations, showing strong reliance on general attacking play rather than set-piece conversions from the spot.
- Penalties represent only a very small portion of the team's total goal output, indicating they are not a primary or dominant source of scoring.
- This distribution highlights that Saudi Arabia's offensive success depends far more on creating chances through movement, combinations, and finishing than on winning and converting penalty kicks.

### 6. Which factors (penalties, own goals, total goals, and year) are most strongly related to Saudi Arabia’s goal scoring?

## Results

![Correlation](images/Correlation_Analysis.png)

## Insights

- Saudi goals have a moderate positive correlation (0.42) with total match goals, meaning high-scoring matches are often driven by Saudi Arabia's offense.
- Penalty goals also show a moderate positive correlation (0.42) with total match goals, indicating penalties contribute noticeably to overall scoring.
- Year has a weak negative correlation (-0.2) with Saudi goals, suggesting a slight decline in goals scored per match over time.

### 7. Does Saudi Arabia have a home advantage when playing international matches?

To answer this question, a chi-square test of independence was used.

**Null Hypothesis (H₀):**
There is no difference in Saudi Arabia’s win rate when playing at home versus away.

**Alternative Hypothesis (H₁):**
Saudi Arabia’s win rate is higher when playing at home.

**Result:**

- p-value = 0.032
- Decision: Reject H₀

**Insight:**
Saudi Arabia shows a statistically significant home advantage.

## Conclusion

This analysis explores the performance of the Saudi Arabia national football team across international matches from 2000 to 2025.
It highlights key trends in goal scoring, tournament performance, and home advantage.
The findings provide data-driven insights into factors influencing match outcomes and team success.
This project serves as a foundation for future football analytics and performance evaluation.
