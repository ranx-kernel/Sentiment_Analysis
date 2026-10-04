# 😊 Sentiment Analysis

A Natural Language Processing mini-project that analyzes text and classifies its sentiment as **Positive, Negative, or Neutral**.

## 🎯 Objective

To develop an NLP-based system that analyzes textual input and determines the sentiment expressed in the text.

## 🧠 Algorithm

**VADER (Valence Aware Dictionary and sEntiment Reasoner)**

VADER is a lexicon and rule-based sentiment analysis tool designed for analyzing sentiments expressed in text.

## 🛠️ Technologies

- Python
- NLTK
- VADER
- Pandas
- Matplotlib
- Gradio
- Google Colab

## ⚙️ How It Works

```text
User Text
    ↓
VADER Sentiment Analyzer
    ↓
Polarity Scores
    ↓
Compound Score
    ↓
┌──────────┬──────────┬──────────┐
│ Positive │ Neutral  │ Negative │
└──────────┴──────────┴──────────┘
    ↓
Display Result
```

## 📊 Sentiment Classification

| Compound Score | Classification |
|---:|---|
| >= 0.05 | Positive |
| -0.05 to 0.05 | Neutral |
| <= -0.05 | Negative |

## 🚀 Features

- Analyze custom text
- Positive sentiment detection
- Negative sentiment detection
- Neutral sentiment detection
- Compound sentiment score
- Multiple text analysis
- Sentiment visualization
- Interactive Gradio interface

## ▶️ How to Run

1. Open `Sentiment_Analysis.ipynb` in Google Colab.
2. Install the required libraries.
3. Download the VADER lexicon.
4. Run the sentiment analyzer.
5. Enter text.
6. View the predicted sentiment and compound score.

## 🔮 Future Enhancements

- Train a machine-learning sentiment classifier
- Use a larger dataset
- Add Tamil sentiment analysis
- Add multilingual sentiment analysis
- Analyze social-media sentiment
- Add speech-to-text input
- Deploy as a web application

## 👩‍💻 Author

**Rania**

Text and Speech Analysis Mini Project
