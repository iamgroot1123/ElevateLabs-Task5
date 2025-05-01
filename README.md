# Task 5: Decision Trees and Random Forests

This repository contains the fifth task of my internship at **Elevate Labs**, focused on learning tree-based models for classification and regression, specifically **Decision Trees** and **Random Forests**.

## 📌 Objective

The objective of this task was to train a Decision Tree Classifier, visualize the tree, analyze overfitting, train a Random Forest model, compare their accuracy, interpret feature importances, and evaluate the models using cross-validation.

## 🛠️ Tools Used

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Graphviz

## 🔍 Steps Performed

1. **Dataset**  
   Used the Heart Disease dataset to predict whether a person has heart disease (target = 1) or not (target = 0).

2. **Preprocessing**  
   - Handled missing values (if any) and converted categorical variables (if any) into numerical form  
   - Split data into training and testing sets  
   - Standardized features to ensure proper model performance

3. **Model Training**  
   - Trained a Decision Tree Classifier with different tree depths and visualized the tree structure  
   - Evaluated the Decision Tree performance and analyzed overfitting by adjusting the maximum depth of the tree  
   - Trained a Random Forest Classifier and compared its accuracy with the Decision Tree

4. **Model Evaluation**  
   - Evaluated models using:
     - Cross-validation (to assess model stability)
     - Accuracy score
     - Feature importances for Random Forest

5. **Feature Importances**  
   - Analyzed the importance of each feature in making predictions with Random Forest

6. **Overfitting Analysis**  
   - Controlled tree depth and other hyperparameters to reduce overfitting in Decision Trees

## 📁 Files

- `task5.ipynb` - Notebook containing all model implementation and evaluation
- `Heart_Disease_Dataset.csv` - Original dataset
- `README.md` - Documentation for this task

## 📊 Dataset

Dataset: Heart Disease Dataset (1025 entries, 13 features, and binary target)

## 📈 Evaluation Metrics

- **Accuracy**  
- **Cross-validation**  
- **Feature Importances**

## 🔑 Key Learnings

- Decision Trees and Random Forests for classification tasks
- Overfitting in Decision Trees and how to control it
- Feature importance analysis with Random Forests
- Model evaluation using cross-validation and accuracy score
