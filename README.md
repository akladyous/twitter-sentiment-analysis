# Twitter Sentiment Analysis

![Twitter Sentiment Analysis](twitter-sentiment-analysis.webp)

## Abstract

Brand monitoring is the process of tracking multiple channels to identify where and how a brand is mentioned. Understanding how people talk about your brand helps you better assess public perception and collect valuable feedback from your audience.

---

## Goal

The goal of this project is to build a **brand monitoring tool** using **Natural Language Processing (NLP)** to derive meaningful insights, monitor market trends, and identify target audiences through sentiment analysis.

---

Human annotators labeled sentiment in over **9,000 tweets** as:

-   Positive
-   Negative
-   Neutral
-   I can’t tell (ambiguous)

---

## Evaluation Metrics

-   Accuracy
-   AUC (Area Under the Curve)

---

## Libraries

-   NumPy
-   Pandas
-   Seaborn
-   Matplotlib
-   TensorFlow
-   Scikit-learn

---

## Models

-   **TF-IDF Vectorizer + Deep Neural Network**
-   **GloVe Embeddings + Recurrent Neural Network (LSTM)**

---

## Conclusion

The TF-IDF–based model achieved an **AUC score of 87%**, despite working with a **highly imbalanced dataset**. The sentiment classes are distributed as follows:

-   Neutral: 59.26%
-   Positive: 32.75%
-   Negative: 6.27%
-   I can’t tell: 1.72%

Although class imbalance posed a challenge, proper neural network tuning and regularization techniques helped **reduce overfitting** and improve overall model performance.
