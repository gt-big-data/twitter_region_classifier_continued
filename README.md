# Twitter Region Classifier Continued

## Preparation
1.  `brew install python3` or `apt install python3` or `conda install python3`
2.  `pip3 install jupyter`
3.  `pip3 install pymongo`
4.  `pip3 install numpy`
5.  `pip3 install scipy`
6.  `pip3 install sklearn`
7.  `pip3 install nltk`
8.  `brew install git` or `apt install git` or `conda install git`
9.  `git clone https://github.com/gt-big-data/twitter_region_classifier_continued.git`
10. `cd twitter_region_classifier_continued`
11. `jupyter-notebook twitter_region_classifier.ipynb`
12. open `localhost:8888` in your web browser

## Understanding the code

### Preprocessing
1.  Fetch tweets in the database
2.  Feature engineering*

### Training
1.  Use Scikit Learn's logistic regression library
2.  Train the model

### Results
1.  Make predictions
2.  Get test set accuracy
3.  Get result of your input sentence

### Analysis
1.  Look into the logistic regression model we trained

## Future goals
1.  Add extra features at the feature engineering step
2.  Use word embeddings instead of one-hot word vectors
