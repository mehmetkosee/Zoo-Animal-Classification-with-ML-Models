# 🦁 Zoo Animal Classification

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project applies Machine Learning techniques to classify animals into **7 categories** (Mammal, Bird, Reptile, Fish, Amphibian, Bug, Invertebrate) based on physical attributes like hair, feathers, and milk.

## 📊 Dataset Details
The dataset contains **101 animals** and **17 features**.
* **Input:** 16 physical traits (Boolean/Integer).
* **Target:** Class Type (1 to 7).

## ⚙️ Methodology
1.  **Preprocessing:** Data cleaning and splitting.
2.  **Model Training:** Tested 3 different algorithms.
3.  **Evaluation:** Used **5-Fold Cross-Validation** to get realistic accuracy scores.

## 🏆 Model Performance
Since the dataset is small, we used Cross-Validation to ensure the results are reliable.

| Model | Average Accuracy |
| :--- | :--- |
| **Random Forest** | **97.00%** 🥇 |
| **Logistic Regression** | 95.00% |
| **Decision Tree** | 94.00% |

*Random Forest performed the best, providing the most stable predictions.*

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mehmetkosee/zoo-animal-classification.git](https://github.com/mehmetkosee/zoo-animal-classification.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy scikit-learn
    ```
3.  **Run the notebook:**
    Open `zoo-classification.ipynb` to see the training process.

---
*Author: [Mehmet Köse](https://github.com/mehmetkosee)*
