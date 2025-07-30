# Spam-Detector-using-Machine-Learning


 Spam Detector using Machine Learning

This project uses a machine learning model to classify emails or text messages as **spam** or **ham (not spam)**. The goal is to build a simple and interpretable classifier using natural language processing (NLP) techniques and basic machine learning algorithms.



Project Overview

- Cleaned and preprocessed a labeled dataset containing SMS text messages
- Converted text data into numerical format using **TF-IDF Vectorization**
-  Trained a **Multinomial Naive Bayes** classifier to detect spam
-  Evaluated model performance using **confusion matrix** and **accuracy score**
-  Visualized results using interactive Plotly graphs (if applicable)



##  Dataset

- Dataset used: `spam.csv` or a similar SMS spam collection
- Columns: `label` (spam/ham), `message` (text message)


## Technologies & Libraries

- Python
- Jupyter Notebook
- pandas, numpy, scikit-learn
- matplotlib or plotly for visualization
- nltk (if used for text preprocessing)

---

How to Run

```bash
git clone https://github.com/yourusername/spam-detector.git
cd spam-detector
jupyter notebook spamdetector.ipynb
