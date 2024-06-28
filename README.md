# Sentiment Analysis of ChatGPT Tweets

This project focuses on sentiment analysis of tweets related to ChatGPT using machine learning techniques. It includes preprocessing, model building, and evaluation to classify tweets into ("good"), negative ("bad"), or neutral sentiments.

## Dataset

Because of the huge size of the dataset, We uploaded it on Google Drive. 
You can find the link commented in the notebook with a note, in case it is preferred to download the dataset and run it locally.
If you choose to run on Google Collab, ensure to import the drive folder correctly.

## Project run

Preferred to run at Google Colab or Kaggle

## Prerequisites

- Python programming language installed

Ensure you have the following libraries installed:
- `numpy` and `pandas` for data handling
- `tensorflow` for deep learning capabilities
- `keras` for building and training neural networks
- `scikit-learn` for preprocessing and evaluation
- `matplotlib` for result visualization

```bash
pip install numpy pandas tensorflow keras scikit-learn matplotlib
```

## Project Structure

### Phase 1: Data Preprocessing

- **Tokenization, Stemming, and Lemmatization:** Clean and prepare the dataset to extract meaningful features.
- **Word Embeddings:** Utilize word embeddings to represent text data numerically.

### Phase 2: Model Building and Training

- **Model Selection:** Implement two classifiers CNN and LSTM to classify tweets.
- **Hyperparameter Optimization:** Train models multiple times to optimize accuracy.
- **Evaluation:** Evaluate model performance on a test set to ensure at least 85% accuracy.

### Outputs

- **IPython Notebooks:** Display model accuracy, visualize results and allow user interaction for sentiment prediction.
- **Report:** Detail model choices, fine-tuning and selection of best hyperparameters, and accuracy metrics across trials, supported by graphical representations.

## Usage

1. **Data Preparation:** Ensure your dataset is structured as per the example provided.
2. **Model Training:** Run the IPython notebook to preprocess data, train models, and evaluate performance.
4. **Prediction:** Use trained models to predict sentiment for new tweets interactively.

## Report Overview

The project report (`report.pdf`) contains detailed findings and analysis from the sentiment analysis of ChatGPT tweets. It includes:

- **Models and Fine-Tuning:** Details on classifiers (CNN, LSTM) and the process of optimizing hyperparameters to achieve optimal performance.
  
- **Performance Evaluation:** Comprehensive analysis of model accuracy across different trials.

- **Output Examples:** Sample predictions showcasing how the trained models classify new tweets into positive, negative, or neutral sentiments.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


