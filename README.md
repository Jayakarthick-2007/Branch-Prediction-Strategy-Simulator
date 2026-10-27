# BranchLab – Branch Prediction Strategy Simulator

## 🌐 Live Demo
**[Click here to try the live website](https://jayakarthick-2007.github.io/Branch-Prediction-Strategy-Simulator/)**

## 📌 Project Overview
BranchLab is an interactive web-based simulator designed to demonstrate and compare different branch prediction strategies used in modern processors. It helps students understand how branch prediction improves processor performance by reducing incorrect predictions and associated penalties.

## ✨ Features
- **Static Prediction:** Simulates an always-taken prediction strategy.
- **1-Bit Dynamic Predictor:** Updates its prediction based on the previous branch outcome.
- **2-Bit Saturating Counter:** Uses a four-state prediction model to reduce unnecessary prediction changes.
- **Accuracy Comparison:** Displays the prediction accuracy of each strategy.
- **Misprediction Analysis:** Counts incorrect predictions for each strategy.
- **Penalty Cycle Calculation:** Estimates performance penalties caused by mispredictions.
- **Execution Trace:** Shows predictions and actual outcomes branch by branch.
- **Interactive Interface:** Enter a custom sequence of taken (T) and not-taken (N) branch outcomes and run the simulation.

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript

## 🚀 How to Run Locally
1. Clone or download this repository.
2. Open the project folder.
3. Open `index.html` in your web browser.
4. Enter a branch outcome sequence using `T` and `N`.
5. Click **Run Simulation** to compare the prediction strategies.

## 🎯 Project Objective
The objective is to understand how different branch prediction algorithms behave and how their prediction accuracy affects processor performance.

## 📚 Academic Context
This project was developed as part of a Computer Organization and Architecture (COA) project to explore branch prediction techniques through an interactive simulation.

## 👨‍💻 Project Type
Educational Web Application
