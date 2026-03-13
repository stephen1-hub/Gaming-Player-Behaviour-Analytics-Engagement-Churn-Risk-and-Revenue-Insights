# Gaming-Player-Behaviour-Analytics-Engagement-Churn-Risk-and-Revenue-Insights
Gaming Player Behavior Analytics
Project Overview

This project explores player behavior in an online gaming environment to understand what drives engagement, identify churn risk, and analyze revenue patterns.

Using exploratory data analysis and player segmentation techniques, the project identifies key behavioral indicators that influence player activity and retention.

The goal is to demonstrate how gaming platforms can use data analytics to improve player engagement, reduce churn, and optimize monetization strategies.

Business Questions

The analysis focuses on answering three key questions:

Which players are most likely to churn?

What factors drive player engagement?

Which player segments generate the most revenue?

Dataset Overview

The dataset contains 40,034 player records with information about player demographics, gameplay behavior, and engagement metrics.

Key Features
Feature	Description
PlayerID	Unique player identifier
Age	Player age
Gender	Player gender
Location	Player location
GameGenre	Preferred game genre
PlayTimeHours	Total gameplay hours
InGamePurchases	Number of in-game purchases
GameDifficulty	Difficulty level selected
SessionsPerWeek	Average number of weekly gaming sessions
AvgSessionDurationMinutes	Average session length
PlayerLevel	Player progression level
AchievementsUnlocked	Number of achievements completed
EngagementLevel	Player engagement category
Tools and Technologies

The following tools were used for the analysis:

Python

Pandas – Data manipulation

NumPy – Numerical computation

Matplotlib / Seaborn – Data visualization

Scikit-learn – Clustering and data preprocessing

Jupyter Notebook – Analysis environment

Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to understand player behavior patterns and engagement drivers.

Key analyses included:

Distribution of player engagement levels

Relationship between playtime and engagement

Session frequency analysis

Achievement progression analysis

Session duration analysis

Key Findings
1. Session Frequency is the Strongest Engagement Driver

Highly engaged players participate in significantly more gaming sessions per week compared to low-engagement players.

2. Session Duration Influences Engagement

Players who spend longer time per gaming session are more likely to fall into the high engagement category.

3. Achievement Progression Supports Engagement

Players who unlock more achievements tend to maintain higher levels of engagement.

4. Total Playtime Alone Does Not Explain Engagement

Total gameplay hours were relatively similar across engagement levels, suggesting that frequency and session duration are more important than total playtime.

Churn Risk Analysis

Since the dataset does not include a direct churn variable, Low Engagement players were used as a proxy for churn risk.

The analysis revealed:

26% of players fall into the churn-risk category

Churn-risk players have significantly fewer weekly sessions

They also have shorter session durations

These findings highlight behavioral signals that gaming platforms can monitor to identify players at risk of leaving the game.

Revenue Insights

Revenue was analyzed using the InGamePurchases metric.

Key insights:

High engagement players generate the highest revenue per player

Medium engagement players generate the highest total revenue due to their larger population

Low engagement players contribute the least to monetization

This suggests that improving engagement among medium-level players could significantly increase overall revenue.

Player Segmentation

K-Means clustering was used to identify behavioral player segments.

The analysis identified three player groups:

Long Session Players – Players who spend long periods in each gaming session

Achievement-Oriented Players – Players focused on progression and achievements

Casual Players – Players with shorter gameplay sessions

These segments highlight different player motivations and gameplay styles, which can help gaming platforms design targeted engagement strategies.

Business Recommendations

Based on the analysis, gaming platforms could improve engagement and retention by:

Encouraging frequent gameplay sessions

Designing achievement-based reward systems

Offering incentives for longer play sessions

Implementing targeted retention strategies for low-engagement players

Project Structure
gaming-player-analytics/
│
├── data/
│
├── notebooks/
│   └── gaming_player_analysis.ipynb
│
├── images/
│
└── README.md
Conclusion

This project demonstrates how data analytics can uncover behavioral insights in gaming platforms. By analyzing player engagement patterns, churn risk indicators, and revenue trends, gaming companies can develop strategies to improve player retention and maximize monetization opportunities.

Author

Stephen Yaw Ayamah

Customer Support @ SportyBet Ghana
Aspiring Data Analyst / Data Scientist

Skills: Python | SQL | Power BI | Data Analytics | Machine Learning
