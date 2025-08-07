# 📰 Fake News Detection Using Machine Learning

This project aims to detect whether a news article is **real** or **fake** using natural language processing (NLP) and machine learning. The model is trained on a labeled dataset of true and fake news articles, making it capable of predicting the authenticity of unseen news content.

---

## 🔍 Problem Statement

With the rise of misinformation and fake news, especially on social media platforms, it has become critical to develop automated tools that can classify and flag fake news articles. This project tackles the problem using a logistic regression model trained on real-world datasets.

---

## 🧠 Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

---

## 📁 Dataset

The dataset used in this project comes from **Kaggle** and includes:
- `True.csv` — Articles verified as real.
- `Fake.csv` — Articles identified as fake.

Each file contains:
- `title`: Headline of the news
- `text`: Full news article text
- `subject`: Category (e.g., politics, world news)
- `date`: Publication date

---

## 📊 Approach

1. **Data Preprocessing**
   - Combine real and fake datasets
   - Clean and label the data
   - Split into training and testing sets

2. **Feature Extraction**
   - Convert text to numerical data using **TfidfVectorizer**

3. **Model Training**
   - Use **Logistic Regression** to train the model

4. **Evaluation**
   - Calculate accuracy and confusion matrix
   - Visualize results using a heatmap

5. **Model Saving**
   - Save both the trained model and vectorizer using Joblib for future predictions

---

## ✅ Results

- **Accuracy**: ~99%
- **Confusion Matrix**: High precision and recall on both classes

---

## 🧪 How to Run

1. Clone this repository or download the project folder.
2. Make sure you have Python 3 installed.
3. Install required packages:
   ```bash
   pip install -r requirements.txt
