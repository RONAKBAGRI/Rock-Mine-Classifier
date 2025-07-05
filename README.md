# 🛰️ Sonar Rock vs Mine Classification

This project uses a Logistic Regression model to classify objects detected by sonar signals as either **Rock** or **Mine**, based on the Sonar dataset.

---

## 📄 Dataset

- **Source:** [UCI Machine Learning Repository - Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+sonar+mines+vs.+rocks)
- **Description:** The dataset contains 208 samples with 60 features each. Each feature represents the energy of a sonar signal at a particular frequency band. The label is either `R` (Rock) or `M` (Mine).

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn

---

## 🚀 Project Workflow

### 1️⃣ Data Loading & Exploration

- Load sonar data using Pandas.
- Separate features and labels.

### 2️⃣ Data Splitting

- Split data into training and test sets using `train_test_split`, ensuring balanced classes via stratification.

### 3️⃣ Model Training

- Train a Logistic Regression model using the training data.

### 4️⃣ Model Evaluation

- Evaluate the model’s accuracy on both training and test sets.
- Check for overfitting or underfitting.

### 5️⃣ Prediction on New Data

- Test the trained model on custom input data to predict whether it is a rock or a mine.

---

## ✅ Results

- **Training Accuracy:** High accuracy on training data (as per output).
- **Test Accuracy:** Good generalization on test data.
- **Sample Prediction:** The model correctly predicts unseen input as Rock or Mine.

---

## 💡 What We Learned

- How to preprocess and explore real-world datasets.
- Applying Logistic Regression to a binary classification problem.
- Evaluating model performance using accuracy.
- Making predictions on new data points.

---

## 📥 How to Run

1️⃣ **Clone this repository:**

```bash
git clone https://github.com/RONAKBAGRI/Rock-Mine-Classifier.git
```

2️⃣ **Install dependencies:**
```bash
pip install numpy pandas scikit-learn
```

3️⃣ **Run the script:**
```bash
python sonar_classification.py
```


