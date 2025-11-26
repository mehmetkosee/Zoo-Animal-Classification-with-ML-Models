# 🦁 Zoo Animal Classification with ML Models

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Library](https://img.shields.io/badge/Library-Scikit_Learn-orange?style=flat&logo=scikit-learn)
![Library](https://img.shields.io/badge/Library-Pandas-150458?style=flat&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project aims to classify animals into **7 distinct categories** (Mammal, Bird, Reptile, Fish, Amphibian, Bug, Invertebrate) based on their physical attributes using Machine Learning.

Using the **Zoo Dataset**, we implemented and compared three different supervised learning algorithms to find the most effective model for this multi-class classification problem.

## 📊 Dataset Details
The dataset consists of **101 animals** with **17 features**.
* **Input Features:** Hair, Feathers, Eggs, Milk, Airborne, Aquatic, Predator, Toothed, Backbone, Breathes, Venomous, Fins, Legs, Tail, Domestic, Catsize.
* **Target Classes (Class Type):**
    1. Mammal
    2. Bird
    3. Reptile
    4. Fish
    5. Amphibian
    6. Bug
    7. Invertebrate

## ⚙️ Methodology
1.  **Data Loading & Inspection:** Loaded the dataset using Pandas and checked for missing values (dataset is clean).
2.  **Preprocessing:**
    * Dropped non-predictive columns (`animal_name`).
    * Separated features (`X`) and target (`y`).
3.  **Data Splitting:** Split the data into **80% training** and **20% testing** sets using `train_test_split` (random_state=42).
4.  **Model Training:** Trained three different models:
    * Logistic Regression
    * Decision Tree Classifier
    * Random Forest Classifier
5.  **Evaluation:** Evaluated models using **Accuracy Score** and **Classification Report**.

## 🤖 Model Performance
Due to the clear distinct features of animals (e.g., milk is unique to mammals, feathers to birds), all models performed exceptionally well.

| Model | Accuracy Score |
| :--- | :--- |
| **Logistic Regression** | **95.24%** |
| **Decision Tree** | **95.24%** |
| **Random Forest** | **95.24%** |

*(Note: The models achieved identical accuracy on the test set due to the small size of the dataset and distinct feature separability.)*

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/mehmetkosee/zoo-animal-classification.git](https://github.com/mehmetkosee/zoo-animal-classification.git)
    ```
2.  **Install requirements:**
    ```bash
    pip install pandas numpy scikit-learn
    ```
3.  **Run the script:**
    You can run the notebook via Jupyter Lab, Google Colab, or execute the python script if exported.

## 🔗 Links
* **Dataset:** [Zoo Animal Classification Dataset](https://www.kaggle.com/uciml/zoo-animal-classification)

---
*Author: [Mehmet Köse](https://github.com/mehmetkosee)*
