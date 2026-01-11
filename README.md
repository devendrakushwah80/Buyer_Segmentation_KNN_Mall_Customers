# 🛍️ Buyer Segmentation using KNN (Mall Customers Dataset)

## 📌 Project Overview
This project focuses on **Buyer Segmentation** using the **K-Nearest Neighbors (KNN)** algorithm.  
The goal is to classify customers into meaningful segments based on their purchasing behavior and demographic attributes.  
Such segmentation helps businesses in **targeted marketing, personalized offers, and better decision-making**.

---

## 🎯 Objectives
- Understand customer behavior through data analysis
- Segment buyers based on selected features
- Build a **KNN Classification model**
- Experiment with different values of **K**
- Use **Cross-Validation** to select the optimal K
- Explain the **bias–variance trade-off**

---

## 📂 Dataset Used
**Mall Customer Segmentation Dataset**

### Key Features:
- Customer Age  
- Annual Income  
- Spending Score  

(Target column is derived based on clustering/labeling logic used in the notebook)

---

## 🛠️ Tools & Technologies
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧪 Workflow
1. **Data Loading & Inspection**
2. **Exploratory Data Analysis (EDA)**
3. **Handling Missing Values**
4. **Feature Selection**
5. **Data Preprocessing**
   - Scaling
   - ColumnTransformer
6. **Pipeline Creation**
7. **KNN Model Training**
8. **Hyperparameter Tuning**
   - Different K values
   - Distance metrics
9. **Cross-Validation**
10. **Model Evaluation**
11. **Result Interpretation**

---

## 🔁 Machine Learning Pipeline
The project uses a **Scikit-learn Pipeline** to ensure:
- Clean preprocessing
- Reproducibility
- Prevention of data leakage

Pipeline includes:
- Scaling
- KNN Classifier

---

## 📊 Model Evaluation
- Accuracy Score
- Cross-validation score comparison
- Bias vs Variance analysis using different K values

---

## 📈 Key Learnings
- Effect of K value on model performance
- Trade-off between underfitting and overfitting
- Importance of feature scaling in KNN
- Practical use of pipelines and cross-validation

---

## 📁 Project Structure
Buyer-Segmentation-KNN/
│
├── Buyer_Segmentation_KNN_Mall_Customers.ipynb
├── README.md
├── requirements.txt
└── Mall_Customers.csv

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Buyer-Segmentation-KNN.git
```
2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Notebook
jupyter notebook Buyer_Segmentation_KNN_Mall_Customers.ipynb
