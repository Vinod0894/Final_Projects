# 📚 Data Science Final Projects

---

## 🚀 Overview
This repository contains three final projects showcasing skills in **data wrangling, exploratory data analysis (EDA), machine learning model building, and deployment**.  
Each project is self-contained in its own folder with code, notebooks, and requirements.  
The venv folders are excluded using `.gitignore` — environments can be recreated using the provided `requirements.txt`.

---

## 📂 Projects Included

### 🐦 Project 1: Twitter Sentiment Analysis
- **Objective:** Build a classification model to predict tweet sentiment (negative, neutral, positive).  
- **Dataset:** Publicly available dataset of **1.6M pre-labeled tweets** (not scraped manually).  
- **Features:** target, ids, date, flag, user, text.  
- **Approach:**  
  - Text preprocessing (cleaning, tokenization, stopword removal, stemming/lemmatization).  
  - Feature extraction (Bag of Words, TF-IDF).  
  - Classification models (Logistic Regression, Naive Bayes, SVM, Random Forest).  
  - Evaluation with Accuracy, Precision, Recall, F1 Score.  
- **Outcome:** Reliable classification of tweets into sentiment categories.  

---

### 🎓 Project 2: Guvi Course Ratings Prediction
- **Objective:** Build a regression model to predict learner ratings for Guvi courses.  
- **Dataset:** Course details including title, URL, price, subscribers, reviews, lectures, level, rating, duration, published timestamp, subject.  
- **Approach:**  
  - Data preprocessing and feature engineering.  
  - Regression models (Linear Regression, Decision Trees, Random Forests).  
  - Evaluation with MAE, MSE, RMSE, R² Score.  
- **Outcome:** Predicted course ratings based on features, helping track performance and revenue opportunities.  

---

### 📸 Project 3: Instagram Influencers Analysis
- **Objective:** Perform exploratory analysis on influencer metrics.  
- **Dataset:** Includes rank, username, influence score, posts, followers, likes, engagement rate, country.  
- **Tasks:**  
  1. Identify correlated features.  
  2. Frequency distribution of influence score, followers, posts.  
  3. Country-wise influencer counts (barchart).  
  4. Top 10 influencers by followers, average likes, total likes.  
  5. Relationship analysis between followers, likes, posts, influence score.  
- **Outcome:** Insights into influencer trends, correlations, and country-level distributions.  

---

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn)  
- **Streamlit** (for interactive apps, where applicable)  
- **Jupyter Notebooks** (for EDA and model building)  
