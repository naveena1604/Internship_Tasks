# 💳 Task 4 – Fraud Transaction Detection

Detecting fraudulent credit card transactions using machine learning (Task 4 - Future Intern ML Internship)

This project is part of my **Machine Learning Internship at Future Intern (June–July 2025)**. The objective is to build a model that detects fraudulent credit card transactions using machine learning techniques, with a focus on handling imbalanced data.

---

## 📌 Project Objective

To develop a fraud detection system that:

- Identifies fraudulent transactions from real-world credit card data
- Handles severe class imbalance using techniques like **SMOTE**
- Trains multiple ML models to compare performance
- Evaluates performance using metrics suitable for fraud detection

---

## 🗃️ Dataset

- Original dataset :  
  🔗 [Credit Card Fraud Detection Dataset](https://drive.google.com/file/d/1xTBC6Mjcpb2iYoOe2yBgonBFkKEMW8ta/view?usp=sharing)
- Contains **284,807** transactions, with only **492** labeled as fraud (~0.17%)
- Features are PCA-transformed for confidentiality
- Highly imbalanced: 0 = Normal, 1 = Fraud

---

## 🧠 Models Used

- Logistic Regression
- Random Forest Classifier
- (Optional) Neural Network
- SMOTE (Synthetic Minority Over-sampling Technique)

---

## 🧪 Workflow

### Data Preprocessing

- Loaded and explored the dataset
- Checked for missing/null values
- Scaled numerical features
- Handled class imbalance using **SMOTE**

### Model Training

- Split data into 80% training and 20% testing
- Trained:
  - Logistic Regression
  - Random Forest Classifier
- (Optional) Tuned hyperparameters

### Evaluation

- Metrics Used:
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **Confusion Matrix**
- Focus on **Recall** to reduce false negatives (missing frauds)

---

## 📈 Results

- Random Forest performed best, achieving high recall and balanced precision
- Demonstrated strong fraud detection ability despite class imbalance

---

## 🖥️ Demo Video

🎥 [Click to Watch](https://drive.google.com/file/d/1wnz6Odt-hVljA8_d5yEoiGgVDiyT8JKY/view?usp=sharing)

---

## 🔗 LinkedIn Post

🔗 [View My LinkedIn Post](https://www.linkedin.com/posts/naveena-sivaiah-91b0b6326_machinelearning-frauddetection-creditcardfraud-activity-7342878408432832523-YX7g?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFI9iKcBwcCFvahb-MaFocwHJSF22yC6mYE&utm_campaign=copy_link)

---

## 📁 Files in This Repository

- `fraud_detection_model.ipynb` – Complete code
- `video/` or `video_link.txt` – Demo showcase
- `README.md` – Project overview

---

## 🧰 Tools & Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📌 Tags

#FutureIntern #FraudDetection #MachineLearning #CreditCardFraud #SMOTE #Classification #Python #InternshipTasks #DataScience #CyberSecurity
