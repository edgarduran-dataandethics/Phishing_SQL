# Phishing SQL README
## Purpose

This project is a practice exercise using SQL (BigQuery) to perform a full clean and analysis of a phishing URL dataset and answer key business questions. The goal was to identify which URL features are most associated with phishing behavior and translate those findings into practical recommendations for users and cybersecurity awareness. 

The dataset is a widely used public dataset from [Kaggle](https://www.kaggle.com/datasets/danielfernandon/web-page-phishing-dataset?resource=download&select=web-page-phishing.csv) and is commonly used in portfolio projects. It contained 100,077 rows and 20 columns.

## Tools
For this analysis, I exclusively used SQL for an analysis. 

## Business Questions:
- Which field(s) has/have the strongest correlation with the “phishing” field?  Which field(s) has/have the weakest correlation with the “phishing” field?
- Would you say that the URL length is a strong indicator of whether or not the URL is phishing?  Why or why not?  What metrics do you have to support your answer?
- Would you say the number of redirections is a strong indicator of whether or not the URL is phishing?  Why or why not?  What metrics do you have to support your answer?
- Based on your analysis, what advice would you give to others for deciphering whether or not a URL is phishing? 

## Highlights
* **URL length**: Longer URLs are more likely to be phishing.
* **Uncommon symbols**: Characters such as @, &, *, #, $ appear more frequently in phishing URLs. That should be taken into consideration before clicking a link.
* **Redirection count** was not a reliable signal. Legitimate URLs redirected nearly **twice as often** as phishing ones.

## Notes
- [SQL Analysis Notebook](https://github.com/edgarduran-dataandethics/Phishing_SQL/blob/main/SQL_Notebook) – a detailed walkthrough of the analysis, queries, and thought process.  
- [Executive Summary](https://github.com/edgarduran-dataandethics/Phishing_SQL/blob/main/Summary) – a concise, business-facing report for recruiters and stakeholders.
