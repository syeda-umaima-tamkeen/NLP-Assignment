 COLAB NOTEBOOK : https://colab.research.google.com/drive/14aRr9cQVcGcaKAa8Tc92CJwspW5LpqY_#scrollTo=Kq-3dbHkzhl8
IMDB Sentiment Analysis

PROJECT BY: SYEDA UMAIMA TAMKEEN
Project Title: IMDB Sentiment Analysis and Topic Modeling
Summary
In this project, I developed a comprehensive pipeline to analyze movie reviews from the IMDB dataset. The analysis includes sentiment classification using both machine learning and deep learning models, as well as topic modeling to identify prevalent themes in the reviews. Using a labeled dataset of positive and negative reviews, I trained and evaluated multiple models to classify sentiments and explored the topics present in the review text.

Key Steps
Data Exploration
Loaded the IMDB dataset and examined its structure, including the number of reviews and their corresponding sentiment labels.
Analyzed sample reviews and distributions of sentiments to understand the dataset.
Data Preprocessing
Cleaned the text by removing HTML tags, non-alphabetic characters, and stopwords, and converted the text to lowercase.
Created a new column, cleaned_review, containing the processed text for further analysis.
Sentiment Classification
Implemented and evaluated machine learning models, including Naive Bayes, to classify reviews as positive or negative.
Built and trained an LSTM (Long Short-Term Memory) model to capture sequential patterns in the text and achieved higher accuracy compared to traditional methods.
Topic Modeling
Applied Latent Dirichlet Allocation (LDA) using both sklearn and Gensim to identify prominent themes in the reviews.
Visualized the topics interactively using pyLDAvis, and saved the visualization as an HTML file for easy sharing.
Visualizations
Created bar plots to show the distribution of the best and worst-reviewed genres based on randomly assigned genre labels.
Generated a word cloud for positive reviews to highlight frequently used words.
Results
Model Evaluation Metrics
Naive Bayes:

Accuracy: 85.4%
Precision: 86.29%
Recall: 84.44%
F1 Score: 85.35%
LSTM:

Accuracy: 88.16%
Topics Identified via LDA
Topic 1: Characters, life, story, movie, film.
Topic 2: Horror, bad, like, one, film, movie.
Topic 3: Movies, good, bad, one, like, film, movie.
Topic 4: Comedy, show, funny, great, one, film, movie.
Topic 5: Action, story, good, movie, film.
Conclusion
The sentiment analysis models successfully classified reviews as positive or negative, with the LSTM model achieving the highest accuracy of 88.16%. The topic modeling process revealed key themes such as action, comedy, and horror, reflecting the variety of movie genres in the dataset. The project demonstrates the effectiveness of combining traditional machine learning, deep learning, and natural language processing techniques for sentiment classification and text analysis.

Future work could include fine-tuning hyperparameters for the LSTM model, exploring transformer-based models like BERT for better performance, and using real genre labels instead of random ones to enhance topic analysis.
