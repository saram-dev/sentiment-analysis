# Amazon Product Reviews Sentiment Analysis

This project aims to predict the sentiment (positive or negative) of Amazon product reviews using Natural Language Processing (NLP) and machine learning techniques.

## Project Description

This project performs sentiment analysis on Amazon product reviews. The reviews are processed to remove stop words, and TF-IDF features are used for model training. The model used is Logistic Regression. We also generate WordClouds to visualize the most frequent words in positive and negative reviews.

## Features

- Data cleaning using NLTK
- Text feature extraction using TF-IDF Vectorizer
- Sentiment classification using Logistic Regression
- WordCloud generation for review visualization

## How to Run the Project

1. Clone this repository:  
   `git clone https://github.com/your-username/your-repo-name.git`
   
2. Install dependencies:  
   `pip install -r requirements.txt`
   
3. Run the Jupyter Notebook:  
   `jupyter notebook`

4. Execute the cells sequentially to train the model and generate WordCloud visualizations.

## Future Improvements

- **Data Preprocessing**: Enhance text cleaning by removing punctuation, special characters, and lemmatizing words.
- **Model Tuning**: Try advanced algorithms like Random Forest, XGBoost, or deep learning models for better accuracy.
- **Hyperparameter Optimization**: Use grid search or random search to fine-tune hyperparameters for better performance.
- **Cross-Validation**: Implement k-fold cross-validation for a more robust evaluation.
- **Evaluation Metrics**: Explore additional metrics like ROC-AUC for a better evaluation of model performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
