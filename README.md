# 🌱 Soil Nutrient Analysis for Crop Prediction

## 📌 Project Overview

This project explores how soil nutrients influence crop prediction using Machine Learning. The goal is to evaluate how well individual soil features (**Nitrogen (N), Phosphorus (P), Potassium (K), and pH**) can predict the type of crop grown.

Instead of building a complex model directly, this project focuses on **feature-level performance**, helping identify the most informative soil attribute.

---

## 🎯 Objectives

* Analyze soil dataset for missing values and structure
* Train a **Logistic Regression** model for each individual feature
* Evaluate performance using **F1-score**
* Identify the **most predictive soil feature**

---

## 🧠 Methodology

### 1. Data Preprocessing

* Loaded dataset using `pandas`
* Checked for missing values
* Separated features (`X`) and target (`y`)

### 2. Model Training

* Used **Logistic Regression (multinomial)** for multi-class classification
* Trained **separate models for each feature**:

  * N (Nitrogen)
  * P (Phosphorus)
  * K (Potassium)
  * pH

### 3. Evaluation Metric

* Used **F1-score (weighted)** to balance precision and recall across multiple classes

---

## 📊 Results

| Feature | F1 Score      |
| ------- | ------------- |
| N       | (your result) |
| P       | (your result) |
| K       | (your result) |
| pH      | (your result) |

✅ **Best Feature:** Potassium (K)
This indicates that **K is the most predictive single feature** for determining crop type in this dataset.

---

## 📁 Project Structure

```
├── soil_measures.csv   # Original dataset
├── crops.csv           # Exported dataset
├── main.py             # Model training & evaluation script
└── README.md           # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install pandas scikit-learn
```

3. Run the script:

```bash
python main.py
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* Scikit-learn

---

## 💡 Key Insights

* Simple models can provide valuable insights when used correctly
* Feature-level evaluation helps understand **which variables matter most**
* Even with basic models, meaningful patterns can be extracted from data

---

## 📈 Future Improvements

* Combine all features into a single model
* Apply feature scaling and normalization
* Try advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Handle class imbalance if present

---

## 🤝 Contributing

Feel free to fork this repo and improve the model or add new features!

---

## 📬 Contact

If you have questions or suggestions, feel free to reach out or connect on LinkedIn.

---

⭐ If you found this project useful, consider giving it a star!
