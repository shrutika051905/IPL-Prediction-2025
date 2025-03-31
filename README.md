# IPL-Prediction-2025
This a  ML project for Predicting IPL matches of 2025 schedule.
IPL 2025 Match & Toss Outcome Prediction using Machine Learning
Welcome to the IPL 2025 Prediction Project, where data meets cricket! This repository uses historical IPL data and machine learning algorithms to forecast:
🪙 Toss Winners
🏆 Match Winners
Based on match conditions, teams, venues, and past performance data.
📂 Project Structure

datasets/
├── matches.csv
└── deliveries.csv
Major Project ML.ipynb        # Full Jupyter Notebook with model training and results
IPL_2025_Prediction_Report.md # Data storytelling report (Markdown format)
README.md                     # Repository overview

📊 Datasets Used
• matches.csv: Match-level data like teams, venue, toss winner, match winner, etc.
• deliveries.csv: Ball-by-ball player performance data.
Source: Kaggle - IPL Dataset
🧠 Machine Learning Models
We trained and compared the performance of several classification models:
• Random Forest
• Logistic Regression
• K-Nearest Neighbors (KNN)
• Decision Tree
• Gradient Boosting ✅ (Best Performer)
• Support Vector Classifier (SVC)
🎯 Accuracy Results
Toss Prediction
Model	Accuracy
Gradient Boosting	51.14%
Decision Tree	45.66%
Random Forest	45.21%
Match Winner Prediction
Model	Accuracy
Gradient Boosting	50.00%
Random Forest	46.33%
Decision Tree	43.12%
📈 Insights
• Toss and venue have predictive value.
• Ensemble models outperform traditional classifiers.
• With further data (e.g., player form, weather), predictions could improve significantly.
🚀 How to Run
1. Clone the repo:
   git clone https://github.com/your-username/IPL2025-Prediction.git
   cd IPL2025-Prediction

2. Install dependencies:
   pip install -r requirements.txt

3. Launch Jupyter Notebook:
   jupyter notebook
📌 Author
Shrutika Sagarshetti.
Student at MIT ACSC Alandi | Data Science Enthusiast | Pythonista
