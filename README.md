# 📊 Obesity Level Prediction Using Machine Learning

This project applies machine learning algorithms to predict obesity levels based on individuals' eating habits and physical conditions. The study investigates lifestyle attributes such as caloric intake, physical activity, family history, and body measurements to classify obesity levels.

## 📌 Project Objectives
- Analyze lifestyle and physical attributes influencing obesity.
- Build machine learning models to classify obesity levels.
- Compare model performance using standard evaluation metrics.
- Identify key predictors contributing to obesity categories.

## 📂 Dataset Description
Source: UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

Dataset Details:
- Rows: 2111  
- Columns: 17  
- Type: Multiclass classification  
- Target Variable: Obesity Level  
  - Categories include: Insufficient Weight, Normal Weight, Overweight (Type I & II), Obesity (Type I & II).

## 🤖 Machine Learning Models Used

### 1️⃣ K-Nearest Neighbors (KNN)
- Non-parametric, instance-based algorithm  
- Predicts class based on nearest feature proximity  
- **Best-performing model in this project (89% accuracy)**

### 2️⃣ Logistic Regression
- Linear classifier suitable for categorical prediction  
- Effective when features and target show linear relationships
- **This model also performed good in this project (86% accuracy)**
  
### 3️⃣ Naive Bayes
- Probabilistic classifier  
- Based on Bayes theorem with feature independence assumptions  
- Fast, simple, and works well with categorical features
- **Lower compared to others but computationally efficient**

## 🧪 Model Evaluation
- Accuracy, Precision, Recall, F1-score, Confusion Matrix

## ▶️ How to Run the Notebook
You can run the notebook easily using:
- Google Colab (recommended)
Simply open the `Obesity_Analysis.ipynb` file and run the cells.

## 📈 Visualizations & Insights
The notebook includes distribution plots, correlation heatmaps, confusion matrices and model comparison charts

## 🔮 Future Work
- Incorporate genetic and psychological data for better obesity prediction
- Explore deep learning models to improve accuracy
- Apply advanced feature selection techniques 
- Integrate real-time data from wearable health devices

## 👩‍💻 Author
Farhanaaz J

Machine Learning Coursework Assignment
