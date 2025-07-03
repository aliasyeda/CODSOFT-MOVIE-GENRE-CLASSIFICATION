# CODSOFT-MOVIE-GENRE-CLASSIFICATION

# 🎬 Movie Genre Classification

This project predicts the **genre of a movie** based on its **plot summary** using machine learning and Natural Language Processing (NLP) techniques.


## 📌 Problem Statement

Given a dataset of movie plot summaries and their corresponding genres, the goal is to build a machine learning model that can classify unseen movie plots into one of the known genres.


## 🧠 Key Concepts Used

- **Text Vectorization** using TF-IDF
- **Label Encoding** of genres
- **Multi-class classification** using Logistic Regression
- **Accuracy evaluation** of predictions
- **Handling large datasets in memory-friendly ways**


## 📂 Dataset

The dataset contains the following files:

- `traindata.txt` — Movie plot summaries with genre labels (used for training)
- `testdata.txt` — Movie plots without genres (used for prediction)
- `testdata.solution.txt` — Actual genres for the test set (used for evaluation)

> ✅ All files are packaged in a zip file.

🔗 [**Click here to download the dataset**](https://drive.google.com/file/d/1tUWpnyiSt38TXm05fjyDi770_bV1Z9y6/view?usp=sharing)  


## 🛠️ How It Works

### 1. **Preprocessing**
- Extracts plots and genres from the dataset
- Converts plots to TF-IDF vectors
- Encodes genres into numeric labels

### 2. **Model Training**
- Uses `LogisticRegression` to train on TF-IDF features
- Predicts genres on test plots

### 3. **Evaluation**
- Predicted genres are compared to actual genres using accuracy score
- Due to system limits, accuracy was computed on a subset (5,000 and 10,000 test samples)


## 📊 Results

| Subset Tested | Accuracy |
|---------------|----------|
| 5000 samples  | 59.26%   |
| 10000 samples | 57.98%   |

> 📌 Note: Full test set contains 54,200 plots. Due to size, evaluation was done on smaller samples.


## 🧪 Technologies Used

- Python 🐍
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Google Colab
- Jupyter Notebook

