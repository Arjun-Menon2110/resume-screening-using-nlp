# 🧠 Resume Screening using NLP

A machine learning project that uses Natural Language Processing (NLP) techniques to automatically classify resumes into job categories such as *Data Science*, *HR*, *Java Developer*, and more.

---

## 📌 Project Overview

This project streamlines the HR recruitment process by classifying resumes into job roles using machine learning and NLP. It covers:

- Resume data preprocessing
- Feature extraction using TF-IDF
- Model training using Naive Bayes
- Resume classification from raw text or PDF files

---

## 📂 Dataset

- **File**: `UpdatedResumeDataSet.csv`
- **Total Records**: 962
- **Columns**:
  - `Category`: Job role label
  - `Resume`: Raw resume content

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- PyMuPDF (for reading PDFs)
- Matplotlib, Seaborn (for optional visualization)

---

## 🛠️ Workflow

1. **Preprocessing**
   - Clean text (remove special characters, digits)
   - Tokenization, stopword removal, stemming

2. **Vectorization**
   - TF-IDF (Top 3000 features)

3. **Modeling**
   - Multinomial Naive Bayes
   - Train-test split: 80/20

4. **PDF Prediction**
   - Extract text using `PyMuPDF`
   - Apply same preprocessing and prediction pipeline

---

## 📈 Performance

- **Accuracy**: `98.96%`
- **Classification Report**: Precision, Recall, F1-Score all ~0.99 for most classes

---

## 🚀 How to Use

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/resume-screening-nlp.git
cd resume-screening-nlp
