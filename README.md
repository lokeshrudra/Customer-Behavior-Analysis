🏏 **Test Cricket Performance \& Statistical Outlier Analysis**

📌 **Project Overview:**

This project is a deep-dive into the history of Test Cricket batting. I transformed a raw dataset into a cleaned, queryable database to answer complex questions about player performance, reliability, and legendary status.



🛠️ **Data Cleaning:**

Before analysis, the raw data required significant transformation to be usable:



Feature Extraction: Split player names to extract their Country and cleaned the highestScore column to remove "not out" markers (\*).



Dynamic Calculations: Built a virtual column for average to ensure accuracy and calculated yearsPlayed from career spans.



Normalization: Handled NULL values and inconsistent country naming conventions (e.g., ICC/World XI).



**🔍 Key Business Questions \& Insights:**

Chapter 1: Scoring Power \& Conversion

The Conversion Kings: I calculated the ratio of Hundreds to Fifties to identify which players are the most clinical at converting a "good start" into a "match-winning" score.



Innings per Century: I analyzed how many innings it takes for a player to hit a hundred, filtering for those with at least 5 centuries to ensure statistical significance.



Run Distribution: I measured what percentage of a player's total career runs came from a single high score to determine if a player was a "one-hit wonder" or a consistent run-getter.



Chapter 2: Reliability \& Technical Stability

Duck-to-Inning Ratio: By analyzing how often a player is dismissed for zero, I identified the most technically stable "anchors" in cricket history.



The "Nervous Fifties": I tracked players who have many half-centuries but zero hundreds, highlighting those who struggle with "finishing" an innings.



Correlation of Experience: I used statistical correlation to prove that players who play more matches tend to maintain a higher average, suggesting that longevity is often a result of sustained quality.



Chapter 3: Global \& Team Analysis

Era Comparison: I compared player production from countries before and after the year 2000 to show how the "center of gravity" in cricket talent has shifted over time.



Collective Country Strength: I calculated the combined batting average for entire nations to rank which countries have the deepest talent pools.



The "Workload" Metric: I analyzed "Matches per Year" to see which players had the highest professional workload based on their career span.



Chapter 4: Statistical Outliers (Advanced Math)

The 3-Standard Deviation Test: I identified "Super-Human" performers by finding those whose average sits more than 3 standard deviations above the mean.



The Skewness Gap: By comparing the Mean (20.54) and Median (18.00), I proved that the dataset is "Right-Skewed," meaning elite superstars make the "average" look higher than it actually is for a typical player.



📊 **Statistical Deep Dive: The "Skewness Gap":**

One of the most important findings in this project was the comparison between the Mean and the Median.



Mean Average: 20.54



Median Average: 18.00



The Gap: 2.54



The Insight: Because the Mean is higher than the Median, the data has a Positive Skew. This proves that cricket history is dominated by a small group of high-performing outliers who "pull" the average up. While the Mean gives an optimistic view of the game, the Median provides a more accurate look at the typical professional experience.



**💻 Technical Skills Demonstrated:**

Advanced SQL: Common Table Expressions (CTEs), Window Functions (PERCENT\_RANK), and Subqueries.



Data Cleaning: String manipulation (SUBSTRING\_INDEX, REPLACE), CASE statements, and IF logic.



Statistics: Standard Deviation, Correlation Coefficients, Mean vs. Median analysis, and Z-Score logic.

