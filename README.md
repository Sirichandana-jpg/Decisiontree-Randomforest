# 🧠 Task 5: Decision Trees & Random Forests

## 📌 Overview
This task focuses on understanding and implementing tree-based machine learning models.  
You explore how Decision Trees work, how to visualize them, how to avoid overfitting, and how Random Forests improve accuracy through ensembling.

---

## 🎯 Objectives
- Understand the working of **Decision Trees**
- Visualize a trained decision tree using Graphviz/PlotTree
- Learn how tree depth affects **overfitting**
- Train and evaluate a **Random Forest model**
- Compare the performance of Decision Trees vs Random Forests
- Interpret **feature importance**
- Perform model evaluation using **cross-validation**

---

## 📂 Dataset Used
- **Heart Disease Dataset**
- Features: patient attributes such as age, cholesterol, resting BP, etc.
- Target: `0 = No Heart Disease`, `1 = Heart Disease`

---

## 🛠 Tools & Libraries
- **Scikit-learn** – building ML models  
- **Pandas** – data handling  
- **Matplotlib** / **Graphviz** – tree visualization  
- **Numpy** – numerical operations  

---

## 📘 Concepts Covered

### 🔹 Decision Tree Classifier
- A tree-structured model that splits data based on rules.
- Each split tries to increase purity of classes.
- Easy to visualize and interpret.

### 🔹 Entropy & Information Gain
- **Entropy** measures impurity.  
- **Information Gain** tells how much a split improves purity.
- Trees choose the split with the highest information gain.

### 🔹 Overfitting in Trees
- Decision Trees tend to memorize training data.
- Controlled using:
  - Max depth  
  - Minimum samples per split  
  - Minimum samples per leaf  
  - Pruning  

### 🔹 Random Forest Classifier
- Collection of multiple decision trees (ensemble).
- Uses bagging + random feature selection.
- More stable and accurate than a single tree.
- Reduces variance and prevents overfitting.

### 🔹 Feature Importance
- Shows which features contribute most to prediction.
- Helps interpret the model and identify key attributes.

### 🔹 Cross-Validation
- Splits data into multiple folds.
- Tests model on different subsets.
- Gives a more reliable performance estimate.

---

## 📊 Model Comparison Summary
| Model | Strengths | Weaknesses |
|-------|-----------|------------|
| **Decision Tree** | Easy to interpret, visualizable | Overfits easily |
| **Depth-Controlled Tree** | Better generalization | May miss complex patterns |
| **Random Forest** | Most accurate, robust, reduces overfitting | Harder to interpret |

---

## 💡 Key Learnings
- Decision Trees provide transparency and interpretability.
- Limiting tree depth greatly helps with overfitting.
- Random Forests significantly boost performance.
- Feature importance helps understand the model's behavior.
- Cross-validation increases evaluation reliability.



## ✔ Summary
This task teaches the fundamentals of tree-based ML models, how to interpret them, and how ensemble techniques like Random Forests enhance predictive performance. It also strengthens understanding of model evaluation and feature importance.

