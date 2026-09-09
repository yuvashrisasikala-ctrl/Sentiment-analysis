# Sentiment Analysis

## Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) project used to identify the emotional tone of a given text.

The system analyzes user-provided text and classifies it into different sentiment categories such as **Positive, Negative, or Neutral**.

This project helps understand people's opinions, feedback, and emotions from textual data.

## Objectives

* Analyze text data automatically.
* Identify the sentiment of the given text.
* Classify text into Positive, Negative, or Neutral categories.
* Reduce the time required for manual analysis.
* Provide a simple and easy-to-use sentiment analysis system.

## Technologies Used

* Python
* Natural Language Processing (NLP)
* Machine Learning
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Streamlit

## How It Works

1. The user enters a text or sentence.
2. The input text is preprocessed.
3. Unnecessary characters and words are removed.
4. The processed text is given to the sentiment analysis model.
5. The model analyzes the text.
6. Finally, the system displays the sentiment as **Positive, Negative, or Neutral**.

## Project Structure

```text
Sentiment-Analysis/
│
├── app.py
├── model.py
├── dataset.csv
├── requirements.txt
└── README.md
```

## Installation

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Open the Project Folder

```bash
cd Sentiment-Analysis
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
streamlit run app.py
```

## Example

**Input:**

```text
I really enjoyed this movie. It was amazing!
```

**Output:**

```text
Sentiment: Positive
```

Another example:

**Input:**

```text
The product was very disappointing.
```

**Output:**

```text
Sentiment: Negative
```

## Features

* Simple and user-friendly interface.
* Fast sentiment prediction.
* Supports text-based sentiment analysis.
* Easy to understand results.
* Can be extended with larger datasets and advanced NLP models.

## Future Enhancements

* Add emotion detection such as Happy, Sad, Angry, and Fear.
* Support multiple languages.
* Use advanced Transformer-based models.
* Add sentiment analysis for social media data.
* Improve prediction accuracy using larger datasets.

## Conclusion

The Sentiment Analysis system provides an efficient way to understand the sentiment expressed in text. By using NLP and Machine Learning techniques, the system can automatically classify text into different sentiment categories and help users understand opinions and emotions from textual data.
