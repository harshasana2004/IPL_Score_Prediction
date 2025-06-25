# 🏏 IPL Score Prediction

This project predicts the final score of an ongoing IPL match based on the current match conditions using a machine learning model trained on historical IPL data.

## 📌 Features

- Predicts final score of a T20 match based on:
  - Batting team
  - Bowling team
  - Venue
  - Current runs, wickets, overs
- Trained using regression techniques (Keras + Scikit-learn)
- Interactive UI built with `ipywidgets` for prediction
- Dataset preprocessing included

## 📂 Project Structure

📁 IPL_Score_Prediction/
│
├── IPL_score_prediction.ipynb # Main notebook (Colab-compatible)
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## ⚙️ Requirements

Install the required packages using:

pip install -r requirements.txt

Key Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
keras
tensorflow
ipywidgets

## 🚀 Usage
Run the notebook in Google Colab or locally in Jupyter Notebook. Choose the batting team, bowling team, venue, and provide match stats to get the predicted final score.

If you cloned the repository and the notebook doesn't render, ensure you have cleaned metadata using nbstripout.

## 📊 Model Overview
Algorithm: Neural Network Regressor (Keras)

Input Features: Categorical + Numeric

Output: Predicted final score

Data: Historical IPL ball-by-ball dataset (cleaned and preprocessed)

## 💡 Motivation
In T20 cricket, especially IPL, estimating the final score mid-innings is valuable for analysis, strategy, and fantasy league predictions. This project demonstrates how machine learning can enhance cricket insights.

✅ Future Improvements
Add ball-by-ball live feed integration

Improve prediction accuracy with more features (e.g., player stats, pitch report)

Deploy the model with a Flask or Streamlit web interface

📌 Author
Harsha Vardhan
GitHub: @harshasana2004
