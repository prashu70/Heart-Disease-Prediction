# Heart Disease Prediction

A data science project that analyzes medical data and builds machine learning models to **predict the presence of heart disease** based on patient health indicators.  
The project includes exploratory data analysis (EDA), feature engineering, model training & evaluation, and performance comparison across multiple algorithms.

---

## 🫀 Project Overview

This repository demonstrates a complete workflow for solving a classification problem using real healthcare data. The core objective is to **identify whether a patient is likely to have heart disease** using features like age, blood pressure, cholesterol, and more.

---

## 📊 Key Objectives

- Perform **Exploratory Data Analysis (EDA)** to understand patterns in the data
- Prepare and preprocess the dataset for modeling
- Train multiple machine learning models
- Evaluate and compare model performance
- Visualize results and insights

---

## 📈 Features

- Data preprocessing and cleaning
- Visual data analysis with graphs and plots
- Training classification models such as:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine
  - XGBoost (optional)
- Performance evaluation using:
  - Accuracy
  - Precision, Recall
  - F1-Score
  - ROC-AUC

---

## 📁 Repository Structure

```
Heart-Disease-Prediction/
│
├── data/                  # Raw and processed dataset files
├── notebooks/             # Jupyter notebooks for EDA & modeling
├── models/                # Saved trained models
├── visuals/               # Plots and graphs
├── requirements.txt       # Python dependencies
├── LICENSE                # License information
└── README.md              # Project documentation
```

---

## 🛠️ Technologies Used

- Python
- Scikit-Learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧠 Dataset Description

The dataset consists of patient medical records with attributes such as:

| Feature | Description |
|---------|-------------|
| age | Patient age |
| sex | Sex (male/female) |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| fbs | Fasting blood sugar |
| thalach | Maximum heart rate achieved |
| target | Heart disease presence (0 = no, 1 = yes) |

> The dataset is commonly used for heart disease classification tasks and is publicly available from sources like UCI Machine Learning Repository.

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/prashu70/Heart-Disease-Prediction.git
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. Explore notebooks in `/notebooks/`:
   - Data loading
   - EDA
   - Model training
   - Evaluation

---

## 📊 Model Evaluation Metrics

- **Accuracy**
- **Precision & Recall**
- **F1-Score**
- **ROC-AUC Curve**

Visual plots are included to compare model performance and help interpret results.

---

## 📦 License

This project is licensed under the **Apache-2.0 License**.  
See the `LICENSE` file for details.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Open issues
- Suggest improvements
- Submit pull requests

---

## 👤 Author

**Prasanth Kumar**  
Full Stack Developer & Machine Learning Enthusiast

⭐ If you found this project helpful, consider **starring the repository!**
