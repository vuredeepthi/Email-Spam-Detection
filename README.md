# 📧 Email Spam Detection System

## 📌 Overview
The Email Spam Detection System is a Machine Learning project designed to classify messages as Spam or Not Spam (Ham). This system leverages Natural Language Processing (NLP) techniques and the Naive Bayes algorithm to effectively filter unwanted messages.

---

## 🎯 Objectives
- To build a reliable spam detection model using real-world data  
- To preprocess and transform textual data into numerical features  
- To evaluate model performance using accuracy metrics  
- To provide predictions on unseen messages  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **Environment:** Google Colab  

---

## 🧠 Machine Learning Approach
- **Algorithm Used:** Multinomial Naive Bayes  
- **Feature Extraction:** CountVectorizer  
- **Model Type:** Supervised Learning (Classification)  

---

## 🔄 Project Workflow
1. Data Collection from SMS Spam Dataset  
2. Data Cleaning and Preprocessing  
3. Label Encoding (Spam = 1, Ham = 0)  
4. Feature Extraction using CountVectorizer  
5. Train-Test Split  
6. Model Training using Naive Bayes  
7. Model Evaluation  
8. Prediction on new input data  

---

## 📊 Model Performance
- **Accuracy:** ~98.3%  
- The model demonstrates high precision in distinguishing spam from legitimate messages.  

---

## 🚀 Key Features
- Efficient spam classification  
- Handles real-world text data  
- High accuracy and fast prediction  
- Easy to extend into web applications  

---

## 📁 Dataset
- **Name:** SMS Spam Collection Dataset  
- **Source:** Kaggle  

---

## ▶️ How to Run the Project
1. Open the `.ipynb` file in Google Colab  
2. Upload the dataset (`spam.csv`)  
3. Execute all cells sequentially  
4. Test the model using custom input messages  

---

## 💡 Sample Predictions
| Input Message | Output |
|--------------|--------|
| "You won a lottery! Claim now" | Spam |
| "Let's meet tomorrow" | Not Spam |

---

## 📌 Future Enhancements
- Use TF-IDF for better feature extraction  
- Deploy as a web application using Streamlit  
- Integrate Deep Learning models for improved performance  

