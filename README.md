# Amazon Product Reviews Sentiment Analysis

This project predicts the sentiment (positive or negative) of Amazon product reviews using Natural Language Processing (NLP) and machine learning techniques.

## Project Description

The sentiment analysis project involves cleaning and preprocessing Amazon product reviews, extracting features using TF-IDF Vectorizer, training a machine learning model (Random Forest), and generating WordClouds to visualize frequent words in positive and negative reviews.

## Features

- **Data Cleaning**: Uses NLTK to remove stop words and unwanted characters.
- **Feature Extraction**: Uses TF-IDF Vectorizer to convert text data into numerical features.
- **Model**: Trains a Random Forest Classifier for sentiment prediction.
- **Visualization**: Generates WordClouds for positive and negative reviews.

## How to Run the Project

1. Clone this repository:  
   `git clone https://github.com/your-username/your-repo-name.git`
   
2. Install dependencies:  
   `pip install -r requirements.txt`
   
3. Run the Jupyter Notebook:  
   `jupyter notebook`

4. Execute the cells sequentially to train the model and generate WordCloud visualizations.

## Future Improvements

- **Data Preprocessing**: Further enhance text cleaning by removing punctuation, special characters, and using lemmatization.
- **Model Enhancement**: Explore other models such as XGBoost or deep learning models like LSTM for improved accuracy.
- **Hyperparameter Tuning**: Use techniques like grid search or random search to find optimal model hyperparameters.
- **Cross-Validation**: Implement k-fold cross-validation for better model performance.
- **Evaluation Metrics**: Explore metrics like ROC-AUC for deeper evaluation of the model.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
