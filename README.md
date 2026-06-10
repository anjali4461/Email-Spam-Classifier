# 📧 Email Spam Classifier

A machine learning-based Email Spam Classifier that detects whether an email/message is **Spam** or **Ham (Not Spam)** using **TF-IDF Vectorization** and **Multinomial Naive Bayes (MNB)**.

## 🚀 Project Overview

Spam emails are unsolicited messages that often contain advertisements, phishing attempts, or malicious content. This project applies Natural Language Processing (NLP) techniques to classify emails automatically.

The model converts email text into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)** and classifies them using **Multinomial Naive Bayes**, achieving strong performance with fast training and prediction times.

---

## 📂 Dataset

The dataset contains labeled email messages:

| Label | Description                           |
| ----- | ------------------------------------- |
| Ham   | Legitimate email/message              |
| Spam  | Unwanted or promotional email/message |

### Example

**Ham**

```
Hey, are we still meeting tomorrow?
```

**Spam**

```
Congratulations! You have won a free iPhone. Click here to claim now!
```

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* TF-IDF Vectorizer
* Multinomial Naive Bayes
* Jupyter Notebook
* Streamlit
* Pickle

---

## 📊 Machine Learning Pipeline

### 1. Data Preprocessing

* Convert text to lowercase
* Remove punctuation
* Remove stopwords
* Tokenization
* Stemming/Lemmatization

### 2. Feature Extraction

* TF-IDF Vectorization

### 3. Model Training

* Multinomial Naive Bayes (MNB)

### 4. Evaluation

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

---

## 📈 Model Performance

| Model                   | Precision |
| ----------------------- | --------  |
| Multinomial Naive Bayes | 99%       |
| Logistic Regression     | 94%       |
| Random Forest           | 100%      |
| KNN                     | 100%      |
| ExtraTreeClassifier     | 99%       |
| XGBoostClassifier       | 94%       |

### Best Model

✅ **TF-IDF + Multinomial Naive Bayes**

Reasons:

* High accuracy
* Fast training
* Low memory usage
* Effective for text classification tasks
---

## 🔮 Future Improvements

* Deploy using Flask or Streamlit
* Deep Learning (LSTM/BERT)
* Real-time email filtering
* Multi-language spam detection

---

website link : https://email-spam-classifier-bjhsxxoxmzbcy2fvwpaww3.streamlit.app/
