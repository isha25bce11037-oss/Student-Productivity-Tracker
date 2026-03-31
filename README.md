# Student-Productivity-Tracker
This project is a fundamental Artificial Intelligence and Machine Learning application that predicts a student’s productivity score and burnout level based on daily habits like study time, sleep, screen usage, mood, and physical activity.

It demonstrates how basic ML models can be used to solve real-life student problems in a simple and interactive way. The project was developed using Google Colab and includes an interactive UI for real-time predictions.

Features

Predicts Productivity Score (0–100)

Classifies Burnout Level (Low / Medium / High)

Interactive UI using sliders and buttons

Provides personalized suggestions

Combines both Regression + Classification models

Tech Stack

Python
Pandas
Scikit-learn
Google Colab
ipywidgets
📂 Dataset

The dataset is manually created for demonstration purposes and includes:

Study Hours Sleep Hours Screen Time Mood (1–5 scale) Physical Activity (Yes/No)

Outputs:

Productivity Score Burnout Level

Machine Learning Models

Linear Regression Used for predicting productivity score (continuous value)

Logistic Regression Used for classifying burnout levels (categorical output)

How It Works

Dataset is created and stored using Pandas
Features and outputs are separated
Data is split into training and testing sets
Models are trained using Scikit-learn
User inputs are taken via interactive widgets
Predictions are displayed instantly
User Interface

The project uses ipywidgets to create an interactive interface: Sliders for study hours, sleep, screen time Mood selection (1–5) Activity toggle (Yes/No) Predict button for instant results

Output Example

Productivity Score: 82.5 / 100 Burnout Risk: Medium Suggestion: Balance study and rest properly.

Objective

The goal of this project is to: Demonstrate basic ML concepts Apply AI to real-life student scenarios Build an interactive and beginner-friendly system

Future Improvements

Use a real-world dataset
Add more features (stress, diet, social life)
Implement advanced ML models

AUTHOR : ISHA OJHA , REG no. : 25BCE1137
Deploy as a web/app-based system
Conclusion

This project is a beginner-level AI/ML system (similar to foundational student projects like Vidyarthi-type models) that combines simplicity with practical application. It shows how machine learning can be used to improve productivity and manage burnout effectively.
