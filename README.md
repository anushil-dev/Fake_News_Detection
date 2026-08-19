# 📰 Fake News Detection using Linear ML Models

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit_Learn-orange)
![NLTK](https://img.shields.io/badge/Library-NLTK-green)
![License](https://img.shields.io/badge/License-MIT-success)

> 🏆 **Published Research:** This repository contains the official codebase for our paper, *"Fake News Detection Using Machine Learning Algorithm,"* published in the IIP Series. <br>
> **[📖 Read the full published paper here](https://iipseries.org/viewpaper.php?pid=8744&pt=fake-news-detection-using-maschine-learning-algorithm)**

---

## 📌 Overview
This repository contains the code and methodology for an automated Fake News Detection system. Designed to combat the rapid spread of misinformation, this project utilizes a custom Natural Language Processing (NLP) pipeline and a **Passive Aggressive Classifier (PAC)** to identify deceptive news articles with high accuracy (~95%).

This project proves that for text-based misinformation detection, high-quality data cleaning and optimized linear models can outperform computationally expensive Deep Learning architectures.

## ✨ Key Features
* **Advanced Text Preprocessing:** Custom pipeline utilizing Regex and NLTK Lemmatization to handle noisy web data while retaining critical numerical context.
* **TF-IDF Vectorization:** Efficient mathematical mapping of text to capture the "semantic language of lies."
* **Ultra-Fast Classification:** Implements the Passive Aggressive algorithm, ideal for large-scale, continuous text data streams.
* **High Accuracy:** Achieved **94.98%** accuracy on a held-out testing dataset.

## 📊 Results & Performance
Our model was evaluated against several baselines and demonstrated superior performance:

* **Accuracy:** 94.98%
* **Precision:** ~95.2%
* **Recall:** ~94.7%

### 📉 Data Insights & Evaluation
To better understand the semantic relationships in our dataset and evaluate the model's prediction accuracy, we generated the following visualizations:

**Word Co-occurrence Matrix (Top 40 Words)**
![Word Co-occurrence Matrix](images/word_matrix.png)

**Confusion Matrix**
![Confusion Matrix](images/confusion_graph.png)
