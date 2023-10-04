# Sentiment Analysis with Multinomial Naive Bayes

## Overview

This project performs sentiment analysis on movie reviews using machine learning techniques. It classifies reviews as either positive or negative based on their text content. The Multinomial Naive Bayes algorithm is employed for classification. The dataset used for this project is sourced from Kaggle's "IMDb Dataset of 50K Movie Reviews" [link](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

## Key Features

- **Data Preprocessing:** The dataset underwent comprehensive cleaning, including HTML tag removal, special character removal, stemming, and stopword removal.

- **Feature Extraction:** Two popular text vectorization techniques, Bag of Words (BoW) and TF-IDF, were employed to convert raw text data into numerical features suitable for machine learning models.

- **Model Training:** Multinomial Naive Bayes models were trained on the transformed text data, allowing us to predict sentiment labels for movie reviews.

- **Model Evaluation:** Model performance was assessed using accuracy, classification reports, and confusion matrices, providing insights into the effectiveness of the sentiment analysis models.

## Dataset Source

The dataset used in this project was obtained from Kaggle's "IMDb Dataset of 50K Movie Reviews." You can find the dataset [here](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). We would like to express our gratitude to the dataset creator for making this valuable resource available.

## Results

Our trained models achieved competitive accuracy in sentiment classification on the test data. These models can be effectively used for sentiment analysis tasks and provide valuable insights into the sentiment of movie reviews.

## Repository Contents

- `Sentiment Analysis.ipynb`: Jupyter Notebook containing the project code, including data preprocessing, model training, and evaluation.

## Usage

To replicate or explore this project:

1. Clone this repository to your local machine.
2. Ensure you have the required libraries and dependencies installed (as listed in the Jupyter Notebook).
3. Open and run the `Sentiment Analysis.ipynb` notebook to see the detailed code and results.

## Contributions

Contributions to this project are welcome! Feel free to submit issues, suggest enhancements, or fork this repository for your own projects.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


Happy Sentiment Analysis!
