# 1. Language-Prediction-using-Machine-Learning
#### Built a language detection model in Python using pandas and CountVectorizer for text feature extraction. Addressed challenges with overlapping linguistic traits by enhancing preprocessing and tuning model parameters. Achieved improved accuracy, enabling precise language identification across diverse multilingual datasets.
# 2. Project Overview: A Journey into Language Prediction
#### The project focuses on developing a machine learning model to predict the language of textual data. Using a dataset of multilingual text samples, the goal was to preprocess, analyze, and classify the language accurately. The process involved transforming raw text into numerical features, training a Naive Bayes classifier, and evaluating its performance. Additionally, an interactive feature was built to allow user input for language prediction.
# 3. Key Steps and Analysis Performed
#### Loading and Exploring Data:
##### • Imported a multilingual dataset with 10,000 rows and no missing values.
##### • Checked for data quality and analyzed language distribution.
#### Data Preparation:
##### • Transformed text into numerical features using CountVectorizer.
##### • Split data into training (67%) and testing (33%) sets.
#### Model Initialization and Training:
##### • Selected a Multinomial Naive Bayes classifier for its efficiency in text classification.
##### • Trained the model on preprocessed training data.
#### Model Evaluation:
##### • Evaluated model performance using accuracy on the testing data.
#### User Interaction:
##### • Implemented functionality to input custom text for language prediction.
##### • Preprocessed user input and generated accurate predictions with the trained model.
# 4. Technologies and Tools Used
#### Programming Language: Python
#### Libraries:
##### • Pandas: For data manipulation and analysis.
##### • Scikit-learn: For text preprocessing, model building, and evaluation.
##### • Numpy: For efficient array operations.
##### • CountVectorizer: For converting text data into numerical format.
#### Model: Multinomial Naive Bayes
#### Environment: Jupyter Notebook
# 5. Model Evaluation Metrics
#### Accuracy: 95%
##### • The proportion of correct predictions to total predictions, showcasing the model's effectiveness.
#### Insights:
##### • High accuracy was achieved, reflecting the model's ability to generalize well on unseen data.
##### • The simple yet powerful Naive Bayes algorithm performed robustly due to the structured preprocessing pipeline.
