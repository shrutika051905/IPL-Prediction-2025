
# 🏏 Predicting IPL 2025 Outcomes: A Machine Learning Story

## 📌 Project Overview

In a nation where cricket is religion, the Indian Premier League (IPL) stands as the ultimate spectacle. To add a new dimension to this thrill, we used machine learning to predict:
- The **Toss Winner**
- The **Match Winner**

for upcoming IPL 2025 matches, based on past data and match conditions.

---

## 📊 Data Foundation

We began with two CSV files:
- `matches.csv`: Metadata for each IPL match including teams, venues, outcomes.
- `deliveries.csv`: Ball-by-ball statistics like runs, player actions, and dismissals.

Label encoding transformed categorical data (team names, venues, decisions) into numerical formats suitable for ML algorithms.

---

## 🧠 Machine Learning Models

We evaluated the performance of six models:
- **Random Forest**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Gradient Boosting**
- **Support Vector Machine (SVM)**

### 🎯 Toss Prediction Accuracy

| Model                | Accuracy |
|---------------------|----------|
| Gradient Boosting   | **51.14%** ✅
| Decision Tree       | 45.66%  
| Random Forest       | 45.21%  
| KNN                 | 38.81%  
| SVM                 | 35.16%  
| Logistic Regression | 21.92%  

> 🔍 **Gradient Boosting** outperformed others, showing its strength in handling complex patterns in toss data.

---

### 🥇 Match Winner Prediction Accuracy

| Model                | Accuracy |
|---------------------|----------|
| Gradient Boosting   | **50.00%** ✅  
| Random Forest       | 46.33%  
| Decision Tree       | 43.12%  
| SVM                 | 38.53%  
| KNN                 | 38.07%  
| Logistic Regression | 24.31%  

> 🎯 Once again, **Gradient Boosting** proved to be the most reliable, even in the more complex task of predicting full match outcomes.

---

## 📈 Insights & Observations

- **Toss has noticeable influence** on match outcomes but isn't deterministic.
- **Venue effects** and **team strength** hold predictive value.
- Ensemble models like **Gradient Boosting** and **Random Forest** consistently outperform simpler classifiers.

---

## 🧠 Conclusion

While cricket is unpredictable, data isn't. Our ML models can forecast IPL 2025 outcomes with ~50% accuracy, which is quite significant given the complexity and variables in the sport.

These results offer a valuable starting point for fans, analysts, and strategic planners looking to gain an edge in the game.
