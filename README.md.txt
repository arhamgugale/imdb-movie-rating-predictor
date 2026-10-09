# 🎬 IMDb Movie Rating Predictor using NLP

## 📌 Project Overview

This project predicts IMDb movie rating categories using Natural Language Processing (NLP) and machine learning. It combines movie summaries with metadata to classify movies into four categories: Poor, Average, Good, and Excellent.

## 🎯 Objectives

* Process movie summaries using NLP techniques.
* Perform Named Entity Recognition (NER) using spaCy.
* Demonstrate BIO tagging for identifying entity boundaries.
* Convert text into numerical features using TF-IDF.
* Train a Logistic Regression classifier.
* Evaluate model performance and analyze prediction differences.
* Build an interactive Gradio interface for predictions.

## 🧰 Technologies Used

* Python
* Google Colab
* Pandas and NumPy
* spaCy
* Scikit-learn
* TF-IDF
* Logistic Regression
* Matplotlib and Seaborn
* Gradio

## 🔄 Project Workflow

1. Load and inspect the IMDb dataset.
2. Clean missing values and prepare movie metadata.
3. Convert numerical IMDb scores into rating categories.
4. Perform NER and BIO tagging on movie summaries.
5. Extract TF-IDF features and combine them with genre, crew, budget, and revenue.
6. Train and evaluate the Logistic Regression classifier.
7. Analyze performance across summary lengths and genres.
8. Launch the interactive Gradio prediction interface.

## ⭐ Rating Categories

* Poor: IMDb score below 5.0
* Average: IMDb score from 5.0 to below 7.0
* Good: IMDb score from 7.0 to below 8.0
* Excellent: IMDb score of 8.0 or above

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload the IMDb dataset.
3. Install the required Python packages.
4. Run the notebook cells in order.
5. Launch the Gradio interface and enter movie details.

## 📊 Evaluation

The project evaluates classification performance using accuracy, precision, recall, F1-score, and a confusion matrix. It also examines differences in performance across movie genres and summary lengths.

Add your actual evaluation results and screenshots here after running the notebook.

## ⚠️ Limitations

* NER performance depends on the spaCy model and the text provided.
* Rating categories simplify the original numerical IMDb scores.
* Revenue is generally available after release, so predictions using revenue are not strictly pre-release predictions.
* The model's predictions are estimates and do not represent official IMDb ratings.

## 📚 Dataset

Dataset source: [IMDb Movies Dataset on Kaggle](https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset)

Please follow the dataset provider's terms and licensing conditions before redistributing the data.

## 👨‍💻 Author

Add your name, course, and institution here.
