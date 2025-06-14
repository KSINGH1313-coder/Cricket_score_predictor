# 🏏 Cricket Score Predictor

The **Cricket Score Predictor** is a machine learning web application that predicts the final score of a cricket team in limited-overs matches (typically T20 or ODI formats) based on the current match situation like runs, wickets, overs, and more.

## 🚀 Features

- Predicts final score based on current match stats
- Utilizes Machine Learning models (Random Forest/XGBoost)
- Easy-to-use web interface built with Flask
- Clean and interactive UI with HTML/CSS
- Real-time prediction functionality

## 🧠 ML Model Overview

We trained and evaluated multiple regression models including:

- **Random Forest Regressor**
- **XGBoost Regressor**

The model takes inputs like:

- Batting Team
- Bowling Team
- Current Score
- Wickets Fallen
- Overs Completed
- Runs in Last 5 Overs

And outputs the **predicted final score**.

## 🖥️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Python, Flask
- **ML Models:** Scikit-learn, XGBoost
- **Deployment:** (Optional) Render / Heroku / Localhost


