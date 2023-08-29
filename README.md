# fake-news-classification
Glove file link : https://www.kaggle.com/datasets/anindya2906/glove6b
# WELFake Dataset Repository

Welcome to the GitHub repository for the WELFake dataset project. This repository contains code and resources related to the analysis and classification of news articles as real or fake using various machine learning techniques. The dataset used in this project comprises 72,134 news articles, with 35,028 labeled as real and 37,106 labeled as fake. The dataset was curated by merging four popular news datasets: Kaggle, McIntire, Reuters, and BuzzFeed Political. This approach aimed to prevent overfitting of classifiers and enhance the quality of text data for improved machine learning training.

# Dataset Information

The dataset is structured with the following columns:

- Serial Number: A unique identifier for each entry, starting from 0.
- Title: The title or headline of the news article.
- Text: The content of the news article.
- Label: A binary label indicating whether the article is fake (0) or real (1).

There are a total of 78,098 entries in the CSV file, but the data frame accessed for analysis contains 72,134 entries.

# Objective

The main objective of this project was to develop and evaluate machine learning models for classifying news articles as real or fake based on their content. To achieve this, various techniques were employed, including TF-IDF-based classification algorithms, deep learning models using GloVe and BERT embeddings, and iterative improvement of accuracy.

## Contributions

Contributions to this repository are welcome! If you'd like to enhance the code, add new features, or suggest improvements, feel free to create a pull request. Please ensure that your contributions align with the project's objectives and follow good coding practices.

## Acknowledgments

We would like to express our gratitude to the creators of the original datasets (Kaggle, McIntire, Reuters, BuzzFeed Political) for providing valuable data for this project. This work builds upon their efforts.

Thank you for visiting this repository and exploring our work on classifying news articles as real or fake. If you have any questions or suggestions, please don't hesitate to open an issue or contact us.

**Note:** Please remember to appropriately cite this repository if you use the code or findings in your own research or projects.
