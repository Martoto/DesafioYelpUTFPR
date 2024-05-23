# Project Title

O desafio consiste em criar um modelo de Machine Learning para prever a nota de uma avaliação de um local no yelp. O dataset contém avaliações de usuários e a nota que eles deram para o local. O objetivo é criar um modelo que consiga prever a nota de uma avaliação com base no texto da avaliação.

A estratégia que utilizei foi criar um modelo de classificação de texto para prever a nota de uma avaliação. Para isso, utilizei a biblioteca HuggingFace, que é uma biblioteca de Machine Learning que lida bem com dados categóricos e é otimizada para trabalhar com textos.

## Components

1. **.gitignore**: This file is used to tell git which files (or patterns) it should ignore. It's used to avoid committing transient files from your working directory that aren't useful to other collaborators, such as compilation products, temporary files IDEs create, etc.

2. **CatBoostClassifier.ipynb**: This Jupyter notebook contains the implementation of the CatBoost Classifier, a machine learning algorithm. It includes the code, visualizations, and narrative text that explain the process.

3. **SentimentAnalysis.ipynb**: This Jupyter notebook is used for sentiment analysis on the dataset. It includes preprocessing of the data, model training, and evaluation.

4. **SentimentAnalysis_test.ipynb**: This is the testing notebook for the sentiment analysis model. It includes unit tests for the functions defined in the SentimentAnalysis notebook.

5. **catboost_info**: This directory contains files related to the training of the CatBoost model. It includes training logs, error logs, and other related files.

6. **exported_data.csv**: This is the dataset that has been exported after preprocessing. It is ready to be used for model training.

7. **exported_data_test.csv**: This is the test dataset that has been exported after preprocessing. It is used for testing the model.

8. **kaggle**: This directory contains the input data for the project, which includes training and testing datasets.

9. **predictions.csv**: This file contains the predictions made by the model on the test dataset.

## Installation

Provide steps on how to install and setup the project.

## Usage

Provide steps on how to use the project.

## Contributing

Provide guidelines on how to contribute to the project.

## License

Provide information about the license.