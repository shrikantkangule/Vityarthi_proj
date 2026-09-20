# Student Performance Prediction System

## Overview of the Project
This project predicts whether a student will **PASS** or **FAIL** based on three factors: study hours, attendance percentage, and previous exam score. It is built entirely **from scratch in pure Python**, without using any machine learning libraries such as scikit-learn. The core algorithm — Logistic Regression — is implemented manually using gradient descent, so every calculation the model performs is visible and explainable.

## Features
- Predicts student performance (Pass/Fail) using three input factors
- Machine learning model built completely from scratch (no external ML libraries)
- Trains itself using Gradient Descent on a small sample dataset
- Displays model accuracy after training
- Interactive terminal input — users can enter their own values and get predictions
- Shows a confidence percentage along with each prediction
- Allows predicting multiple students in a single run

## Technologies / Tools Used
- **Language:** Python 3
- **Libraries:** `math` (Python standard library only — no external packages required)
- **Concepts used:** Logistic Regression, Gradient Descent, Sigmoid Function, Data Normalization

## Steps to Install & Run the Project
1. Make sure Python 3 is installed on your system.
2. Clone this repository:
   ```
   git clone <your-repository-link>
   cd <repository-folder>
   ```
3. Run the program:
   ```
   python student_performance_from_scratch.py
   ```
4. No additional installation is required — the project uses only Python's built-in `math` module.

## Instructions for Testing
1. Run the program using the command above.
2. The program will first train the model and display its **accuracy** on the training data.
3. You will then be prompted to enter:
   - Study hours (e.g., `5`)
   - Attendance percentage (e.g., `74`)
   - Previous exam score (e.g., `58`)
4. The program will output a prediction (**PASS** or **FAIL**) along with a confidence percentage.
5. Sample test cases to try:
   | Study Hours | Attendance % | Previous Score | Expected Result |
   |---|---|---|---|
   | 9 | 90 | 85 | PASS |
   | 1 | 45 | 30 | FAIL |
   | 5 | 74 | 58 | PASS |
6. After each prediction, choose `y` to test another student or `n` to exit.

## Screenshots
*(Add screenshots of your terminal output here before submission — optional but recommended.)*