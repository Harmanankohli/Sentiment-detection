# Sentiment Analysis on IMDb Dataset

This repository contains the solution for a sentiment analysis challenge. The goal of the project is to classify IMDb movie reviews into positive or negative sentiments using natural language processing (NLP) and machine learning techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Setup](#setup)
- [Usage](#usage)
- [Models and Performance](#models-and-performance)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

The project focuses on building a sentiment detection model for movie reviews by:
1. Preprocessing and cleaning text data.
2. Transforming text into numerical representations using Bag of Words and TF-IDF techniques.
3. Training various machine learning models, including Logistic Regression, Naive Bayes, and Decision Trees.
4. Evaluating and comparing model performances using validation and test datasets.

---

## Features

- **Sentiment Analysis**: Classifies reviews into positive or negative categories.
- **Text Preprocessing**: Includes cleaning, lemmatization, and removal of duplicates, HTML tags, punctuation, and stopwords.
- **Model Tuning**: Hyperparameter tuning for optimal performance.
- **Visualization**: Confusion matrices and distribution plots for better interpretability.

---

## Dataset

The project uses the **IMDb Movie Reviews Dataset**, which contains:
- 50,000 reviews with labels (`positive` or `negative`).
- Balanced classes with 25,000 reviews in each sentiment category.
- Available as a CSV file in the repository.

---

## Setup

### Prerequisites

- Python (>=3.8)
- Jupyter Notebook
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, NLTK

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sentiment-analysis-imdb.git
   cd sentiment-analysis-imdb
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Fellowship_NLP_Challenge_Sentiment_Detection_imdb.ipynb
   ```

2. Follow the notebook to:
   - Preprocess the data.
   - Train and evaluate the models.
   - Visualize results.

---

## Models and Performance

### Models Evaluated:
- **Logistic Regression**
- **Naive Bayes**
- **Decision Tree**

### Performance on the Test Set:
| Model              | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 89.9%    | 89.5%     | 90.6%  | 90.0%    |
| Naive Bayes         | 89.9%    | 89.5%     | 90.6%  | 90.0%    |
| Decision Tree       | 86.3%    | 88.5%     | 83.7%  | 86.0%    |

---

## Results

- Logistic Regression and Naive Bayes performed best with an accuracy of **89.9%**.
- Decision Tree had relatively lower performance but was useful for interpretability.
- Both Bag of Words and TF-IDF showed similar results across all models.

---

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- [IMDb Dataset](https://www.imdb.com/interfaces/)
- Libraries: Scikit-learn, NLTK, Pandas, Matplotlib
- Inspiration from NLP challenges and tutorials.

---
