This repository contains the code, documentation, and outputs for the project “Sentiment Analysis of Agoda Hotel Reviews Using Big Data Technologies.”
It demonstrates how  an end-to-end sentiment analysis pipeline were built on Microsoft Azure following the Medallion Architecture (Bronze, Silver, Gold layers) and integrated results into Power BI dashboards.

**Project Overview**
Goal: Classify user reviews from the Agoda mobile application (Google Play Store) into sentiment categories (Positive, Neutral, Negative) at scale.

**Pipeline:**
- Bronze Layer – Web scraping and raw data ingestion to Azure Blob Storage
- Silver Layer – Data cleaning (emoji removal, language detection, normalization) and writing to Delta Tables
- Gold Layer – Sentiment modeling with machine learning (TF‑IDF + Linear SVM, Logistic Regression, Naive Bayes, Random Forest)

**Visualization ** – Power BI dashboards for trends, languages, and engagement metrics
**Best Model:** Linear SVM
**Accuracy in main pipeline:** 87%
**Accuracy in evaluation setup:** 90.22%

**Tools and Technologies**
- Cloud Platform: Microsoft Azure (Blob Storage, Databricks, Delta Lake)
- Programming: Python, PySpark, scikit-learn
- Data Engineering: Medallion Architecture (Bronze/Silver/Gold), Delta Tables
- Visualization: Power BI
- Other Libraries: google-play-scraper, langdetect, nltk (VADER), pandas

**PowerBI Dashboard**
![af54b1f3-9c28-4f47-9b21-922fb567c844](https://github.com/user-attachments/assets/ece98e09-4bca-42de-aead-f24da4bb611f)
