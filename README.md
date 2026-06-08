# 📰 Fake News Detection using Machine Learning & NLP

This project is an end-to-end Machine Learning and Natural Language Processing (NLP) workflow where textual news data is transformed into meaningful predictions. The objective of the project is to classify news articles as **Fake** or **Real** using text preprocessing techniques and Machine Learning algorithms.

**-- Dataset Source:** Fake News Dataset
**Format:** CSV

The dataset contains news articles along with labels indicating whether the news is fake or real. This data was used to build a classification model capable of identifying misinformation.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## -- Project Steps

### 1. Data Loading

Imported the dataset using Pandas and explored its structure, columns, and data types to understand the available information.

### 2. Exploratory Data Analysis (EDA)

Performed initial analysis to understand the distribution of fake and real news articles.

* Checked dataset dimensions
* Analyzed class distribution
* Identified missing values
* Explored text patterns

### 3. Data Cleaning

Prepared the text data for machine learning by:

* Removing special characters and punctuation
* Converting text to lowercase
* Removing stopwords
* Applying stemming techniques
* Handling missing values

### 4. Text Preprocessing

Used Natural Language Processing techniques to convert raw text into structured data.

* Tokenization
* Stopword Removal
* Stemming using Porter Stemmer
* Text normalization

### 5. Feature Engineering

Converted textual data into numerical format using:

* Bag of Words (Count Vectorizer)

This transformation allows machine learning algorithms to process textual information effectively.

### 6. Model Building

Split the dataset into training and testing datasets and trained a **Multinomial Naive Bayes** classification model.

### 7. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Confusion Matrix
* Classification Metrics

The trained model successfully classified news articles as Fake or Real based on their textual content.

### 8. Reporting & Analysis

Analyzed the model results and interpreted classification performance to understand the effectiveness of the Fake News Detection system.

---

## -- Model Features

The model provides:

* Automated Fake News Classification
* Text Processing using NLP
* Machine Learning-Based Predictions
* Classification Performance Evaluation
* Real vs Fake News Detection

---

## 📊 Key Concepts Used

* Natural Language Processing (NLP)
* Text Cleaning
* Stopword Removal
* Stemming
* Bag of Words
* Count Vectorization
* Machine Learning Classification
* Multinomial Naive Bayes
* Confusion Matrix
* Accuracy Evaluation

---

## 🚀 Future Enhancements

* TF-IDF Vectorization
* Logistic Regression
* Random Forest Classifier
* XGBoost
* Deep Learning Models (LSTM)
* Transformer Models (BERT)

---

## 📈 Project Outcome

Successfully developed a Fake News Detection system capable of classifying news articles as Fake or Real using NLP techniques and Machine Learning algorithms. The project demonstrates the practical application of text analytics and predictive modeling for combating misinformation.
