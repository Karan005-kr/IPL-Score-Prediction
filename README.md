# 🏏 IPL Win Predictor

A Machine Learning-powered web application that predicts the winning probability of an IPL team during a live match based on current match conditions.

## 📌 Project Overview

IPL Win Predictor is a Machine Learning project that estimates the chances of a team winning an IPL match in real time. The prediction is based on factors such as batting team, bowling team, target score, current score, wickets remaining, overs completed, and match venue.

The model is trained on historical IPL match data and deployed using Streamlit for an interactive user experience.

## 🎯 Features

* Predicts winning probability for both teams.
* Interactive and user-friendly interface.
* Real-time match scenario analysis.
* Machine Learning-based predictions.
* Streamlit web application deployment.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Pickle

## 📊 Dataset

The model is trained on historical IPL match data containing:

* Batting Team
* Bowling Team
* Match Venue
* Target Score
* Current Score
* Overs Completed
* Wickets Lost

## 🤖 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Model Serialization using Pickle
7. Streamlit Deployment

## 📂 Project Structure

```text
IPL-Win-Predictor/
│
├── app.py
├── pipe.pkl
├── requirements.txt
├── README.md
│
└── style.css
```

## 🚀 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/your-username/IPL-Win-Predictor.git
```

Move into the project directory:

```bash
cd IPL-Win-Predictor
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python -m streamlit run app.py
```

## 📈 Model Output

The application displays:

* Winning Probability of Batting Team
* Winning Probability of Bowling Team

based on the current match situation.

## 🎓 Learning Outcomes

* Data Preprocessing
* Feature Engineering
* Classification Models
* Model Deployment
* Streamlit Application Development
* Sports Analytics using Machine Learning

## 👨‍💻 Author

**Karan Kumar**

B.Tech CSE (AI & ML)

Gateway Institute of Engineering and Technology

## ⭐ Internship Project

Developed as part of an AI/ML Internship Project to demonstrate the practical application of Machine Learning in Sports Analytics.
