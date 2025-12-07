# Language Detection using Machine Learning

## 📌 Project Overview
This project detects the **language** of a given text using Machine Learning models.  
The dataset contains sentences of multiple languages, and the system predicts the correct language using text classification.

The project is developed in **Google Colab** using Python.

---

## 📂 Dataset
**File:** `languagededection.csv`

**Columns:**
- `TEXT` – Input text
- `LANGUAGE` – Language label

---

## 🧠 Machine Learning Models Used
You trained and compared:

1. **Multinomial Naive Bayes**
2. **Support Vector Machine (SVM)**
3. **Logistic Regression**

For each model you calculated:
- Accuracy  
- Classification report  
- Confusion matrix  

---

## 🔧 Workflow
1. Load dataset from Google Drive  
2. Display:
   - Total languages  
   - Language count  
   - Null value check  
   - Dataset shape  
3. Visualize data using:
   - Bar chart  
   - Pie chart  
4. Convert text into vectors using **CountVectorizer**  
5. Train ML models  
6. Test and compare accuracy  
7. User inputs text to detect language  

---

## 📊 Visualizations
The project includes:
- Bar chart showing number of texts per language  
- Pie chart showing language distribution  
- Bar chart comparing Naive Bayes, SVM, and Logistic Regression accuracy  
- Confusion matrices for all models  

---

## 🚀 How to Run the Project
1. Open **Google Colab**
2. Upload dataset to Google Drive
3. Mount drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
