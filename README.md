# 🦁 Zoo Animal Classification with ML Models

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit_Learn-orange)
![Library](https://img.shields.io/badge/Library-Pandas-yellow)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📖 Project Overview
This project focuses on **Multi-Class Classification** using the famous Zoo Dataset. The goal is to predict the classification of an animal (e.g., Mammal, Bird, Fish) based on various physical attributes like hair, feathers, eggs, milk, airborne, etc.

We implemented and compared multiple Machine Learning algorithms to find the best performing model for this dataset.

## 📊 The Dataset
The dataset consists of **101 animals** with **17 boolean/integer attributes**.
* **Input Features:** Hair, Feathers, Eggs, Milk, Airborne, Aquatic, Predator, Toothed, Backbone, Breathes, Venomous, Fins, Legs, Tail, Domestic, Catsize.
* **Target (Class Type):** 1. Mammal
    2. Bird
    3. Reptile
    4. Fish
    5. Amphibian
    6. Bug
    7. Invertebrate

## 🛠️ Tech Stack & Methodology
* **Python**: Core programming language.
* **Pandas & NumPy**: Data manipulation and analysis.
* **Matplotlib & Seaborn**: Data visualization (Count plots, Correlation Matrix).
* **Scikit-Learn**: Building and evaluating ML models.

### Steps:
1.  **Data Preprocessing:** Checking for null values, analyzing feature distribution.
2.  **Exploratory Data Analysis (EDA):** Visualizing the correlation between animal features and classes.
3.  **Model Training:** Applied various Supervised Learning algorithms.
4.  **Evaluation:** Comparing models based on Accuracy Score.

## 🤖 Models Used & Results
Several algorithms were tested to achieve the highest accuracy. Here is the performance comparison:

| Model | Accuracy Score |
| :--- | :--- |
| **Logistic Regression** | [Örn: 95%] |
| **K-Nearest Neighbors (KNN)** | [Örn: 92%] |
| **Support Vector Machine (SVM)** | [Örn: 96%] |
| **Decision Tree** | [Örn: 94%] |
| **Random Forest** | [Örn: 98%] |

*(Note: Random Forest / SVM performed best due to [Buraya neden iyi sonuç verdiğine dair kısa bir yorum ekleyebilirsin, örneğin: its ability to handle feature importance well])*

## 📈 Visualizations
<p align="center">
  </p>

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/mehmetkosee/zoo-animal-classification.git](https://github.com/mehmetkosee/zoo-animal-classification.git)
