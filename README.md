# 🎬 Sentiment Analysis on IMDB Movie Reviews

This project focuses on building a **Sentiment Analysis model** using a machine learning pipeline in Python. It classifies movie reviews from the IMDB dataset as either **positive** or **negative** based on their content.


## 🛠️ Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn (TfidfVectorizer, LinearSVC, Pipeline)

## 🔄 Workflow

1. Loaded and cleaned the dataset (handled NaNs and blank reviews).
2. Visualized missing values using heatmaps.
3. Split the dataset into training and test sets.
4. Created a machine learning pipeline:
   - TF-IDF Vectorization
   - Linear Support Vector Classifier
5. Trained the model and evaluated its performance using:
   - Confusion Matrix
   - Classification Report
   - Accuracy Score

## ✅ Outcomes

- **Accuracy Achieved:** ~**87.9%**

- **Confusion Matrix:**

[[1901 265]
[ 272 1990]]


- **Classification Report:**

| Sentiment | Precision | Recall | F1-Score | Support |
|-----------|-----------|--------|----------|---------|
| Negative  |   0.87    |  0.88  |   0.88   |  2166   |
| Positive  |   0.88    |  0.88  |   0.88   |  2262   |

> The model performs well in identifying both positive and negative sentiments in reviews.

## 📊 Visualization

Used seaborn's heatmap to detect and handle missing values during the preprocessing phase.

## 📁 Files

- `IMDB Dataset.csv` - Dataset file
- `sentiment_analysis.py` - Python script for preprocessing, training, and evaluation
- `README.md` - Project documentation

## 🚀 Future Improvements

- Add deep learning models like LSTM or BERT for comparison
- Handle neutral sentiment for multi-class classification
- Improve preprocessing using advanced NLP techniques

---


