# Problem Statement

## Problem Statement
Teachers and academic institutions often struggle to identify students who are at risk of failing until it is too late — usually after final results are declared. By the time poor performance is visible, there is little opportunity left to intervene and provide support. There is a need for a simple, early-warning system that can estimate a student's likely performance based on measurable factors such as study habits, attendance, and past academic history, so that at-risk students can be identified and supported in time.

## Scope of the Project
This project is a lightweight, educational demonstration of how machine learning can be applied to predict student outcomes. It is built as a **from-scratch implementation** of Logistic Regression (without using external ML libraries) to clearly show how such predictions are made under the hood. The scope is limited to:
- Using three input factors: study hours, attendance percentage, and previous exam score
- Predicting a binary outcome: Pass or Fail
- Running as a terminal-based Python program
- Training on a small, illustrative dataset defined within the code

This project is intended for academic and learning purposes only, and is not designed for deployment in a real institution without a much larger dataset, further validation, and ethical review.

## Target Users
- **First-year computer science / engineering students** learning the fundamentals of machine learning
- **Teachers or academic mentors** who want a simple early-warning tool to identify students who may need extra support
- **Students** who want to self-assess their likely performance based on their study habits and attendance

## High-Level Features
- Accepts three inputs: study hours, attendance percentage, and previous exam score
- Trains a Logistic Regression model from scratch using Gradient Descent
- Normalizes input data so all three factors are weighed fairly
- Outputs a Pass/Fail prediction with an associated confidence score
- Displays the model's training accuracy for transparency
- Supports predicting multiple students interactively in a single session