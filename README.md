# NBA_Analysis_of_the_Atlantic_Division

### NBA Atlantic Division: Team Performance Analysis & Predictive Modeling

## Project Overview

The growing role of data analytics in professional basketball has transformed how teams evaluate performance, develop strategies, and make decisions.

This project analyzes the five NBA Atlantic Division teams using historical game data. We will study how their performance changes over time, compare their strengths and weaknesses, and estimate the chance that the home team wins before tipoff.

We will develop and evaluate predictive models using information available before tipoff. Model selection will be guided by predictive performance, interpretability, and computational requirements.

The results will power an interactive website. Visitors will be able to choose a historical matchup, see the model’s pregame win probability, and reveal the final score and key game statistics.

By combining **Sports Analytics, Statistical Analysis, Data Visualization, and Machine Learning**, we aim to translate historical NBA data into meaningful insights and predictions.

## Teams Under Analysis

The project focuses on the five teams competing in the NBA's Eastern Conference Atlantic Division:

| Team | Abbreviation |
|---|---|
| Boston Celtics | BOS |
| Brooklyn Nets | BKN |
| New York Knicks | NYK |
| Philadelphia 76ers | PHI |
| Toronto Raptors | TOR |

These teams will be evaluated individually and comparatively to explore their performance, competitive advantages, and historical trends.

## Project Objectives

The primary objectives of this project are:

1. **Team Performance Analysis:** Evaluate historical team statistics, including scoring efficiency, defensive performance, rebounds, assists, turnovers, and shooting percentages.

2. **Exploratory Data Analysis (EDA):** Identify relationships between statistical metrics and game outcomes while examining patterns in team performance.

3. **Comparative Analysis:** Compare the five Atlantic Division teams to understand their strengths, weaknesses, and overall competitiveness.

4. **Predictive Modeling:** Develop machine learning models capable of predicting game outcomes using historical team performance and relevant statistical indicators.

5. **Interactive Website:** Publish matchup filters, team comparisons, pregame predictions, and a postgame result reveal

6. **Website Hosting:** Explore free hosting options for the interactive site and its game data.

## Key Research Questions

This project aims to address the following questions:

- Which statistical factors have the strongest relationship with winning NBA games?
- How do offensive and defensive performances differ among Atlantic Division teams?
- How have team performance trends changed across different NBA seasons?
- Can historical team statistics accurately predict future game outcomes?
- Which machine learning algorithms demonstrate the strongest predictive performance?
- How well do the predicted win probabilities match actual outcomes?
- How can analytical insights support basketball performance evaluation and decision-making?

## Data Collection & Preparation

The project will use historical NBA data to investigate team performance and develop predictive models.

### Potential Data Sources

- NBA official statistics: https://www.nba.com/stats
- Basketball Reference: https://www.basketball-reference.com/
- Additional publicly available basketball datasets and APIs, as applicable

### Key Performance Indicators (KPIs)

| Category | Performance Metrics |
|---|---|
| Team Performance | Wins, Losses, Win Percentage |
| Offensive Performance | Points Per Game, Offensive Rating, Field Goal Percentage |
| Defensive Performance | Points Allowed, Defensive Rating, Steals, Blocks |
| Shooting Efficiency | 3-Point Percentage, Free Throw Percentage, Effective FG% |
| Ball Movement | Assists, Turnovers, Assist-to-Turnover Ratio |
| Rebounding | Offensive, Defensive, and Total Rebounds |
| Game Context | Home/Away Performance, Recent Form, Opponent Strength |

Final variables will depend on dataset availability and their relevance to the predictive models.

## Project Methodology

### Phase 1: Data Collection & Preprocessing

Collect historical NBA game and team statistics, address missing values, remove inconsistencies, and prepare structured datasets for analysis.

### Phase 2: Exploratory Data Analysis (EDA)

Apply descriptive statistics, correlation analysis, and visualizations to identify performance trends and explore relationships between basketball metrics and game outcomes.

### Phase 3: Atlantic Division Comparative Analysis

Evaluate the five teams using selected performance indicators, comparing offensive efficiency, defensive capabilities, consistency, and historical success.

### Phase 4: Predictive Modeling

Develop statistical and machine learning models to predict NBA game outcomes using information available before each game.

Potential algorithms include:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting
- Other suitable predictive modeling techniques

### Phase 5: Model Evaluation

Evaluate the predictive models using appropriate classification metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

Where applicable, chronological training and testing splits will be used to evaluate predictions on later games and reduce the risk of data leakage.

### Phase 6: Findings & Interpretation

Interpret model results, identify influential variables, summarize key analytical findings, and discuss limitations and potential improvements.

### Phase 7: Interactive Website & Deployment

Start with a historical Celtics–Knicks matchup. Let visitors view the model’s win probability before revealing the score and postgame comparison. Expand to other Atlantic Division matchups once the first flow works.

Prepare game records for the website with the matchup ID, date, prediction cutoff, home-team win probability, and postgame results. The website will use these records to filter matchups and display charts.

The team will evaluate free hosting and data options before choosing how to deploy. Test shareable matchup links, mobile and keyboard use, and how the site handles missing data.

## Tools & Technologies

The following tools and libraries may be used throughout the project:

| Technology | Purpose |
|---|---|
| Python | Data analysis and predictive modeling |
| Pandas & NumPy | Data cleaning and manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | Machine learning and evaluation |
| Jupyter Notebook | Data exploration and experimentation |
| Git & GitHub | Version control and collaboration |

*The technology stack will be updated as the project progresses.*

## Expected Outcomes

At the conclusion of this project, we aim to produce:

- A comprehensive statistical analysis of the NBA Atlantic Division.
- A comparative evaluation of all five teams.
- Visualizations illustrating historical performance and key trends.
- Predictive models for estimating pregame win probabilities.
- An evaluation of the model’s win probabilities on later games.
- A deployed interactive matchup explorer with pregame probabilities and a postgame reveal.
- A final summary of analytical findings, limitations, and future opportunities.

## Project Status

**Current Status: In Development**

This repository will be updated throughout the project's development, including data preparation, exploratory analysis, model development, evaluation, and final findings.

## Meet the Team

This project is developed collaboratively by three team members with a shared interest in sports analytics, data science, and applying predictive modeling to real-world basketball performance.

### Team Member 1: Anshuman Agrawal

**GitHub:** agrawalanshuman

### Team Member 2: Hemanth Kumar Gopi

**GitHub:** Hemanth-55

### Team Member 3: Paris Taliadouros

**GitHub:** ptaliadouros00

---

*Using data science and predictive analytics to explore the numbers behind NBA basketball.*
