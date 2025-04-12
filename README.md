# 📊 Exploratory Data Analysis on IPL Matches

## 📖 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on detailed ball-by-ball data from an **Indian Premier League (IPL)** match between **Royal Challengers Bengaluru (RCB)** and **Delhi Capitals (DC)**. The primary goal was to explore match dynamics, player performances, and strategic trends across different match phases (Powerplay, Middle Overs, Death Overs).

Using **Python** and popular data science libraries, this analysis extracts actionable insights that could help refine cricket strategies, evaluate player performances, and enhance fan understanding of the game.

---

## 📂 Dataset Source

The dataset was sourced from a **public cricket data repository (like ESPN Cricinfo)** and shared in CSV format.  
Each record represents a single delivery in the match, including:
- **Match details**: Teams, batter, bowler, non-striker
- **Run breakdown**: Runs per ball, extras, total runs
- **Wicket information**: Dismissal type, fielders involved
- **Over number**: To identify match phases (1-20)

---

## 📝 EDA Process

Key steps in the analysis:

1. **Data Loading**: Imported using `pandas.read_csv()`.
2. **Data Cleaning**: Handled missing values and standardized player names.
3. **Feature Engineering**:
   - Added flags like `is_boundary`
   - Classified match phases by over number
   - Calculated performance metrics (strike rate, bowling economy)
4. **Visualization**:
   - Line charts for run rates
   - Bar plots for boundaries
   - Heatmaps for correlations
   - Pie charts for wicket distributions
5. **Statistical Insights**:
   - Regression trends to study wicket impact on run rate
   - Basic clustering to group player types (planned for future scope)

---

## 📊 Analysis Highlights

- **Powerplay Phase**: RCB dominated with high boundary frequency.
- **Death Overs**: DC lost momentum with frequent wickets.
- **Top Performers**:
  - **Virat Kohli** (RCB): Highest strike rate and boundary count.
  - **Kuldeep Yadav** (DC): Best economy and key middle-over wickets.
- **Boundary Impact**: RCB's superior 6-hitting made a decisive difference.
- **Correlation Insight**: Wickets in middle overs slowed scoring rates, especially for DC.

---

## 📈 Visualizations

- **Line Graph**: Over-by-over runs comparison
- **Bar Graph**: 4s and 6s by team
- **Heatmap**: Correlation between runs, wickets, overs
- **Pie Chart**: Wicket types distribution
- **Regression Plot**: Wickets vs. run rate trends

---

## 📝 Conclusion

This project provided valuable hands-on experience in working with messy sports data, uncovering performance patterns and match dynamics using data visualization and basic modeling techniques. It reaffirmed how crucial clean data, context-aware features, and visual storytelling are in sports analytics.

---

## 🚀 Future Scope

- **Predictive Modeling**: Forecast match outcomes and player performances.
- **Advanced Clustering**: Group players by style and situational performance.
- **Interactive Dashboards**: Build real-time visual insights using `Plotly` or `Dash`.
- **Multi-Match Analysis**: Extend to entire IPL seasons for deeper trends.
- **Fantasy Cricket Recommendations**: Use data to suggest optimal fantasy teams.

---

## 📚 References

- Wes McKinney, *Python for Data Analysis*, O’Reilly Media  
- [pandas documentation](https://pandas.pydata.org/)  
- [seaborn documentation](https://seaborn.pydata.org/)  
- [scikit-learn documentation](https://scikit-learn.org/stable/)  
- [matplotlib documentation](https://matplotlib.org/)
