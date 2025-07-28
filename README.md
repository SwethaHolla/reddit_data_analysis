# reddit_data_analysis
# Reddit Investment Forum Analysis

**Network + NLP study of investment and support subreddits**  
Identify influential users, model crowd behavior over time, and quantify the sentiment impact of investment advice using social network analysis and VADER sentiment.

---

## TL;DR

- **Goal:** Understand who influences investment conversations on Reddit, when engagement peaks, and how advice shifts community sentiment.
- **Methods:** Network centralities (Degree, Betweenness, Closeness), time-series traffic/trend analysis, VADER sentiment, and a simple trust-scoring framework.
- **Stack:** Python (pandas, networkx, nltk/VADER, matplotlib), Reddit API (via `praw`) or pre-exported data.

---

## Key Questions

1. Which users are most central/influential in investment discussions?
2. When do threads peak and how do themes/trends evolve over time?
3. How does investment advice affect short-term community sentiment?
4. What signals (structure, text, metadata) are most predictive of high engagement?

---

## Contributions

- Analyzed Reddit investment/support forums using **network metrics** (Degree, Betweenness, Closeness) to identify influential users.
- Performed **time-based traffic analysis** and **trend detection** to capture **peak engagement** and **crowd behavior**.
- Applied **VADER sentiment** and a **trust scoring** approach to assess the impact of investment advice on community sentiment.
- Combined **network theory, NLP, and data wrangling** to generate insights relevant to **FinTech** and **social media analysis**.
