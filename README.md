Sentiment Analysis using HuggingFace Transformers

This project performs sentiment analysis using a pre-trained Transformer model (DistilBERT) through HuggingFace’s pipeline("sentiment-analysis").

The model classifies sentences as Positive or Negative, compares predictions with true labels, and shows evaluation metrics.

Features:

Uses DistilBERT, a fast and lightweight Transformer model

Classifies text sentiment (positive/negative)

Custom dataset of 20 labeled examples

Prediction using HuggingFace pipelines

Performance evaluation (accuracy)

Clear results table

Easy to understand and extend

Project Structure:
/sentiment-analysis-transformer
│
├── Sentiment_Analysis_Pipeline.ipynb   # Main notebook
└── README.md                            # Documentation

🛠️ Technologies Used

Python

HuggingFace Transformers

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

How to Run:

Open the notebook in Google Colab

Install dependencies

Run all cells

No external dataset required — the mini dataset is created inside the notebook.

Sample Output:
Text	Predicted Label	Score
Loved this movie!	POSITIVE	1.00
Waste of money.	NEGATIVE	1.00
Accuracy

The model provides highly accurate predictions on the sample dataset.

Author
Ayushman Das

Feel free to star this repository if you find it useful!
