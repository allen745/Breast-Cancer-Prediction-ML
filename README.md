# Breast-Cancer-Prediction-ML
# 🩺 Breast Cancer Classification using Machine Learning

## 📌 Project Overview

This project is a **Breast Cancer Classification System** that predicts whether a tumor is:

- 🔴 Malignant (Cancerous)
- 🟢 Benign (Non-Cancerous)

The model is built using **Machine Learning Logistic Regression**.

Project Workflow:

```
Data Collection
        ↓
Data Preprocessing
        ↓
Train Test Split
        ↓
Logistic Regression Model
        ↓
Model Evaluation
        ↓
Cancer Prediction System
```

---

# 🎯 Objective

To develop a machine learning model that can classify breast cancer tumors using medical features.

Prediction:

```
0 → Malignant

1 → Benign
```

---

# 🛠️ Technologies Used

- Python 🐍
- NumPy
- Pandas
- Scikit-Learn
- Logistic Regression


---

# 📂 Project Structure

```
Breast-Cancer-Classification/

│
├── Breast Cancer Classification.py
│
├── README.md
│
└── requirements.txt

```

---

# 📊 Dataset Information

Dataset:

**Breast Cancer Wisconsin Dataset**

Source:

Scikit-Learn Built-in Dataset


Dataset Size:

```
569 Rows

30 Features
```


Features include:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension
- Worst Values


---

# 🔎 Data Preprocessing

Steps performed:


### Loading Dataset

Dataset loaded using:

```python
sklearn.datasets.load_breast_cancer()
```


---

### DataFrame Creation

Converted dataset into Pandas DataFrame.


---

### Feature and Target Separation

Features:

```
X = Input Features
```


Target:

```
Y = Cancer Label
```


---

# 🤖 Machine Learning Model


## Logistic Regression


Used because:

- Binary classification problem
- Fast and efficient algorithm
- Works well with medical classification datasets


---

# 🔄 Model Training


Dataset split:

```
Training Data : 80%

Testing Data  : 20%
```


Algorithm:

```
Logistic Regression
```


---

# 📈 Model Performance


## Training Accuracy

```
93.18%
```


## Testing Accuracy

```
92.98%
```


---

# 🧪 Prediction System


The project includes a prediction system.

Example:


Input:

```
Medical Feature Values
```


Output:

```
The Breast Cancer is Benign
```


or


```
The Breast Cancer is Malignant
```

---

# 📌 Machine Learning Workflow


```
Dataset

   ↓

Data Preprocessing

   ↓

Train Test Split

   ↓

Logistic Regression

   ↓

Accuracy Evaluation

   ↓

Prediction

```


---

# 🚀 How to Run Project


Clone repository:

```bash
git clone <your-repository-link>
```


Install dependencies:

```bash
pip install -r requirements.txt
```


Run project:

```bash
python "Breast Cancer Classification.py"
```


---

# 📦 Requirements

```
numpy
pandas
scikit-learn
```


---

# 👨‍💻 Author


<a href="https://github.com/YOUR_GITHUB_USERNAME">
<img src="https://github.com/allen745.png" width="120px">
</a>


## Allen Christian

Machine Learning Developer 🚀

GitHub:

https://github.com/allen745
