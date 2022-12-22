<img src = 'https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Logo_HEC_Lausanne.png/640px-Logo_HEC_Lausanne.png' width="200">

# **Data Mining & Machine Learning 2022 Project**
## Group: UNIL_OMEGA 
### *Detecting the difficulty level of French texts* 

<!--TABLE OF CONTENTS --> 
<details>
  <summary>📂Table of contents</summary>
  <ol>
    </li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#about-the-project">About the project</a></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#methodology">Methodology</a></li>
    <li><a href="#results">Results</a></li>
        <ul>
        <li><a href="#without-data-cleaning">Without data cleaning</a></li>
      </ul>
      <ul>
        <li><a href="#with-data-cleaning">With data cleaning</a></li>
      </ul>
    <li><a href="#video">Video</a></li>
  </ol>
</details>

## Authors
🐉Sophie Kern: sophie.kern@unil.ch  
🦖Guillaume Emery: guillaume.emery@unil.ch

## About the project
As part of our Master's in Information Systems & Digital Innovation, we participated in a [Kaggle competition](https://www.kaggle.com/competitions/detecting-french-texts-difficulty-level-2022). The objective of this project was to build a model that could predict the difficulty level of written texts in French (A1, A2, B1, B2, C1, C2). The model could potentially be used in a recommendation system to recommend texts, such as recent news articles, that are suitable for a person's language level.

## Data
This project uses two datasets: `training_data` and `unlabelled_test_data`. The `training_data` has 3 features: id, sentence, and difficulty, wheras the `unlabelled_test_data` has only 2 features: id and sentence. Our goal is to use several models to predict the difficulty level for the `unlabelled_test_data`, aiming for the highest accuracy score possible.

## Methodology
We..
1. Imported the packages needed
2. Loaded the data (`training_data` and `unlabelled_test_data`)
3. Had a look at them 
   - infomation on both data set
   - number of observations by difficulty level
   - basline
4. Prepared the data for classification 
   - set random side
   - split the training data into a train and test set using specific parameters 
   - set a Tfidf vectorizer
5. We defined methods to generate and test the models
   - *evaluation()* which computes & prints the evaluation scores (accuracy, precision, recall, f1 score) on the test set and plots & display the confusion matrix
   - *pipeline()* which creates a pipeline usinf Tfidf vectorizer & a classifier
   - *fit_and_predict()* which fits the model on the training set and make predictions
6. Trained and made predictions on 4 models (without data cleaning)
   - logistic regression
   - knn
   - decision tree classifier
   - random forests classifier 
10. Generated a model (with data cleaining) with a higher accuracy

## Results 

#### Without data cleaning
||Logistic Regression|KNN|Decision Tree|Random Forests|
| :---: | :---: | :---: | :---: | :---: | 
|Precision|||||
|Recall|||||
|F1-score|||||
|Accuracy |||||

#### With data cleaning
||XXXX|
| :---: |:---: |
|Precision||
|Recall||
|F1-score||
|Accuracy ||

## Video 🎥 



