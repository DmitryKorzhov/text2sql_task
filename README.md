# Task for Text2SQL. 
The goal of the project is to generate and execute SQL using natural language. 

Our current project which works quite good:
https://app.hex.tech/92584165-8120-4675-b37b-3cc63b887871/hex/d7c06e6d-2eeb-4983-86a0-99376da9c4e3/draft/logic

It can connect to our ClickHouseDB and understand our specific structure, tables, columns and so on. 

Your task is to make a Text2SQL App that will generate, execute SQL and give answers to these questions:
1. Cross channel report with device dimension for Facebook and Google Ads with device type normalization;
2. Show me top 10 pages that have the best conversion rate and more than 10 opps in the last 12 months and add 3 columns Paint points, Gain or Product features for this page;
3. Top 10 Worst ROI campaign for last week, with spend;
4. Top 10 best ROI ad campaign;
5. Top 5 marketing campaigns by conversions;
6. Make cross-channel normalization for facebook, bing, google_ads_ql and linkedin_ads tables with the same granularity (account_id, campaign_id, adset_id, ad_id) with basic performance metrics (clicks, impressions, spend, revenue, engagements, purchase).

## Where to start: 
Look at the code we have;
Create a test ClickHouseDB (important to use exactly ClickHouseDB);
Make a test Database locally or in any cloud. 
Fill DB with dummy data;
Make an application that will generate SQL and execute it;
Ask all the questions above to the application. 

## Desirable output: 
Statistics of correct answers to questions from the application and your approach to this task.

## Useful documents to check about LLMs and Text2SQL before you start: 

- https://docs.langchain.com/docs/
- https://gpt-index.readthedocs.io/
