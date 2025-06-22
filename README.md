# 📊 Employee Sentiment Analysis 🚀

This project performs an Employee Sentiment Analysis on internal communication data to measure employee engagement and sentiment trends. It uses **TextBlob**, an easy-to-use NLP library, for automatic sentiment labeling and applies statistical techniques and machine learning for deeper analysis.

---

## 📌 Project Overview

The goal is to analyze an unlabeled dataset of employee messages, automatically determine their sentiments (**Positive**, **Negative**, or **Neutral**), and extract actionable insights such as:

* Monthly employee sentiment scores
* Top positive and negative employees
* Employees at risk of leaving (flight risk detection)
* Predictive sentiment trend modeling

---

## 📖 Features & Workflow

✔️ **Exploratory Data Analysis (EDA):**

* Data structure review, missing values check, and distribution analysis
* Visualizations for sentiment distribution, monthly trends, and employee message patterns

✔️ **Sentiment Analysis using TextBlob:**

* Classifies messages based on sentiment polarity
* Adds a `sentiment` column for each message

✔️ **Employee Sentiment Scoring:**

* Assigns scores: +1 (Positive), 0 (Neutral), -1 (Negative)
* Calculates monthly cumulative sentiment scores per employee

✔️ **Employee Ranking:**

* Ranks top 3 positive and negative employees per month

✔️ **Flight Risk Detection:**

* Flags employees sending **4 or more negative messages in any 30-day window**

✔️ **Predictive Modeling (Linear Regression):**

* Predicts sentiment scores based on message length, word count, and message frequency
* Evaluated using Mean Squared Error and R² score

---

## 📦 Tech Stack

* **Python 3.x**
* **TextBlob**
* **Pandas**
* **Seaborn / Matplotlib**
* **scikit-learn**
* **Jupyter Notebook**

---

## 📊 Visualizations Included

* Sentiment distribution bar charts
* Top employee rankings per month
* Flight risk employee lists
* Predictive model evaluation metrics

---

## 📄 Deliverables

* `sentiment_analysis.ipynb` — complete, well-commented notebook
* `visualizations/` — sentiment and EDA plots
* `README.md` — project overview and documentation
* `final_report.docx` — formal project report
* `requirements.txt` — project dependencies

---

## 📌 About TextBlob

TextBlob is a simple and lightweight NLP library in Python for processing text data. It enables quick sentiment polarity analysis with minimal setup — ideal for internal or educational NLP projects like this one.

---

## 📣 Summary

This project demonstrates a full-cycle text analytics workflow — from raw message data to sentiment classification, employee scoring, engagement insights, risk flagging, and predictive modeling, providing a practical solution for internal HR analytics.
