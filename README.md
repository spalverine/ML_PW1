# Machine Learning Practical Works

This repository contains my university practical assignments (PWs) for the Machine Learning course. Each folder represents a specific topic and implementation.

---

## 📂 Project Structure

### 🧪 [PW1] K-Nearest Neighbors (KNN)
**Topic:** Supervised Learning - Classification  
**Goal:** Predict burnout levels among remote workers.
* **Dataset:** `work_from_home_burnout_dataset.csv`
* **Implementations:**
    * `KNN_scratch.ipynb`: Manual implementation of the KNN algorithm logic.
    * `KNN_lib.ipynb`: Implementation using the `scikit-learn` library.
* **Key Tasks:** Data preprocessing, distance calculation, and model evaluation.

---

### 🧪 [PW2] Naive Bayes Classification
**Topic:** Probabilistic Graphical Models  
**Goal:** Compare different Naive Bayes variants on text and numerical data.

#### Part 1: Email Spam Classification (Text Data)
* **Dataset:** `email_classification_dataset.csv`
* **Objective:** Classify emails as "Spam" or "Ham."
* **Techniques:** NLP preprocessing (CountVectorizer & TF-IDF), comparison between **MultinomialNB** and **BernoulliNB**.
* **Evaluation:** Focus on Accuracy, Precision, Recall, F1-Score, and Confusion Matrix visualization.

#### Part 2: Diabetes Prediction (Numerical Data)
* **Dataset:** `diabetes.csv`
* **Objective:** Predict diabetes diagnosis based on medical measurements.
* **Model:** **Gaussian Naive Bayes**.
* **Evaluation:** Focus on Accuracy, Precision, Recall, F1-Score, and Confusion Matrix visualization.

---

## 🛠️ Requirements
* Python 3.x
* Jupyter Notebook 
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## 🚀 How to Run
1. Navigate to the desired PW folder (e.g., `cd PW2`).
2. Launch Jupyter Notebook: `jupyter notebook`.
3. Open the `.ipynb` files to view the implementation and results.
