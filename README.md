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
      </ul>
    <li><a href="#video">Video</a></li>
  </ol>
</details>

## Authors
🐉Sophie Kern: sophie.kern@unil.ch  
🦖Guillaume Emery: guillaume.emery@unil.ch

## About the project
As part of our Master's in Information Systems & Digital Innovation, we participated in a [Kaggle competition](https://www.kaggle.com/competitions/detecting-french-texts-difficulty-level-2022). The objective of this project was to build a model that could predict the difficulty level of written texts in French (A1, A2, B1, B2, C1, C2). The model could potentially be used in a recommendation system to recommend texts, such as recent news articles, that are suitable for a person's language level.

## Methodology

The code is composed of 2 files: 
*	#1 file:  with the 4 models asked without data cleaning (Logistic Regression, KNN, Decision Tree Classifier, Random Forest Classifier) 
*	#2 file: with the model which gave us the best accuracy on Kaggle (Bert)
###
In each file we: 
* Imported the package needed
* Loaded the data 
* Prepared the data for classification
* Defined appropriated methods to generate, predict and test the models
* Created and trained the models
* Evaluate the models

To discover more about what we did, click on the link of our video below! 


## Results 

#### Models asked without data cleaning
||Logistic Regression|KNN|KNN improved|Decision Tree|Decision Tree improved|Random Forest|
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
|Precision|0.4656|0.4030|0.4242|0.3018|0.3249|0.4439|
|Recall|0.4667|0.3187|0.3677|0.3000|0.3219|0.4333|
|F1-score|0.4640|0.3022|0.3571|0.2980|0.3081|0.4211|
|Accuracy |0.4667|0.3187|0.3677|0.3000|0.3219|0.4333|

#### The model that gave us the best accuracy on Kaggle 
||Bert|
| :---: |:---: |
|Precision|0.6984|
|Recall|0.4211|
|F1-score|0.5223|
|Accuracy |0.5945|

## Video 🎥 



