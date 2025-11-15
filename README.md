# sql-looker-studio
Construction of a multi-dimensional analytical dataset from an e-commerce BigQuery database, with insights visualized in Looker Studio.

# E-commerce SQL & Looker Studio Project

This project contains the final SQL task completed for the SQL Advanced module.  
The goal was to build a unified analytical dataset based on an e-commerce BigQuery database and create a visualization in Looker Studio.

## Objectives
- Analyze account creation dynamics.
- Evaluate email activity: sends, opens, visits.
- Compare user behavior across countries and account attributes: send_interval, is_verified, is_unsubscribed.
- Identify top markets based on account creation and sent messages.

## Key Requirements
- One SQL query that builds the full dataset.
- Use of CTEs and window functions.
- Separate logic for accounts and emails with UNION.
- Final selection limited to top 10 countries by rankings.
- Looker Studio visualization based on resulting data.

## Output Fields
- date, country, send_interval, is_verified, is_unsubscribed
- account_cnt, sent_msg, open_msg, visit_msg
- total_country_account_cnt, total_country_sent_cnt
- rank_total_country_account_cnt, rank_total_country_sent_cnt

## Visualization
- Overall figures by country (accounts, sent messages, rankings)
- Trend over time for sent_msg

## Tools / Technology
- SQL (BigQuery)
- Looker Studio
