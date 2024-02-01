**Stress Prediction from Reddit Posts**
**Overview**
This project aims to analyze and predict stress levels in individuals based on their posts on Reddit. It involves web scraping to collect data, pre-processing the data for analysis, and applying machine learning models to predict the presence of stress. The goal is to identify stress-related patterns and sentiments expressed in the posts, providing insights into mental well-being.

**Project Structure**
Data Collection and Preprocessing: The dataset is sourced from Reddit, focusing on specific subreddits related to stress and mental health. The preprocessing steps include text normalization, removing stop words, and feature extraction.
Data Analysis: Initial analysis includes visualizing the distribution of stress levels across different subreddits and ensuring the dataset's balance.
Model Training and Evaluation: Several models, including Logistic Regression, Random Forest, and LSTM (Long Short-Term Memory), are trained and evaluated based on their accuracy in predicting stress levels.
Model Application: The trained model is applied to new, scraped data to predict stress levels, demonstrating its practical use.
**Key Components**
Libraries and Frameworks: The project utilizes libraries such as Pandas, Seaborn, Matplotlib, NLTK, Keras, TensorFlow, and Scikit-learn for data manipulation, visualization, natural language processing, and machine learning.
Data Visualization: Insights are visualized using Seaborn and Matplotlib, highlighting the distribution of data and model performance.
Model Comparison: A comparative analysis of different models is presented, showcasing their accuracy in predicting stress levels.
Prediction Function: A function named predictor is implemented to classify text data into stress or no stress, allowing for practical application on unseen data.
