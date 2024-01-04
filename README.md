## Predicting a Song's Genre Using ML Models and Sentiment Analysis

Our project used Spark and various ML models to predict whether a song is pop or rap (binary classification). This notebook utilizes sentiment analysis (AFINN) to facilitate training each model.
The model types we evaluated are Logistic Regression, Decision Tree, Random Forest and Gradient Boosted Trees(GBT). We evaluated each model using accuracy, precision, recall, fscore, and AUC-ROC.
Through comparing each metric, we determined that Random Forest was our best performing model. We used the following ML pipeline:

1. Data Collection: Gather relevant data for predicting a song's genre
2. Inspect Quality of Data: Check the data for issues
3. Extract Subsets of Data: Work with smaller subsets for exploration
4. Transform Data: Preprocess and clean the data
5. Exploratory Data Analysis (EDA): Gain insights and understand the data
6. Build Models from Data: Select and train machine learning models
7. Obtain Raw Data: Get new, unseen data for evaluation
8. Feature Extraction: Extract features from raw data
9. Supervised Learning: Apply the trained models to make predictions on unseen data
10. Evaluation: Assess each model's performance
 
The song dataset can be found on Kaggle using this [link](https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information) 
