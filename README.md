## 📌 Objective

To build and improve deep learning models for sentiment classification of tweets, using a real-world dataset and applying preprocessing, exploratory data analysis (EDA), and various neural architectures.

## 🗂 Dataset

We used the **TweetEval – Sentiment Subset**:  
🔗 [TweetEval Sentiment Dataset on Hugging Face](https://huggingface.co/datasets/cardiffnlp/tweet_eval/viewer/sentiment)

The dataset contains ~45K tweets labeled as:
- **0**: Negative  
- **1**: Neutral  
- **2**: Positive

## 🔨 Project Structure

### Part 1: Preprocessing & Baseline Models
- Cleaned the data by removing URLs, usernames, hashtags, and emojis
- Performed lemmatization and tokenization
- Conducted EDA on tweet length and class distribution
- Implemented 3 baseline models:
  - RNN-based sentiment classifier
  - LSTM-based sentiment classifier
  - Feedforward neural network (FFNN) classifier

### Part 2: Model Enhancement Trials
Conducted trials to improve performance:
- Restructured models by changing hidden layers and neuron sizes
- Experimented with pre-trained word embeddings (e.g., Word2Vec)
- Tried data augmentation strategies

## Evaluation
- Training & validation accuracy curves for all models
- Confusion matrices and classification metrics (accuracy, F1-score)
- Comparison table showing performance across all models and trials
- Analysis of what worked and why

## Tools & Libraries
- Python  
- PyTorch  
- scikit-learn  
- NLTK  
- Hugging Face Datasets

